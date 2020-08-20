# [xream](https://xream.io)   
####     [/sqli](http://sqli.xream.io)
####     [/x7](http://x7.xream.io) 
####     [/reliable](http://reliable.xream.io)
   
    to develop java project quickly


## sqli
   [http://sqli.xream.io](http://sqli.xream.io)
   
        @X.Key
        @X.Mapping
        Criteria
        CriteriaBuilder

## x7
   [http://x7.xream.io](http://x7.xream.io)
   
[![license](https://img.shields.io/github/license/x-ream/x7.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![maven](https://img.shields.io/maven-central/v/io.xream.x7/x7-parent.svg)](https://search.maven.org/search?q=io.xream)

       
       x7-repo
          extends BaseRepository<Foo>
          @EnableX7Repository
          @EnableX7L3Caching
  
       x7-reyc
          /reyc
              @EnableReyClient  or  @EnableReySupport
              @ReyClient
          /reliable
              @EnableReliabilityManagement
              @ReliableProducer
              @ReliableOnConsumed
              
    
### maven dependency
```xml

<dependency>
    <groupId>io.xream.x7</groupId>
    <artifactId>x7-spring-boot-starter</artifactId>
    ....
</dependency>

```  
        
        
## reliable
   [http://reliable.xream.io](http://reliable.xream.io)
   
[![license](https://img.shields.io/github/license/x-ream/reliable.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![maven](https://img.shields.io/maven-central/v/io.xream.reliable/reliable.svg)](https://search.maven.org/search?q=io.xream)

       mq transaction, with tcc option
       implements x7/x7-reyc/reliable
  
 
### maven dependency
```xml

<dependency>
    <groupId>io.xream.reliable</groupId>
    <artifactId>reliable-spring-boot-starter</artifactId>
    ....
</dependency>

```  
   

