# [xream](https://xream.io)   
####     [/sqli](http://sqli.xream.io)
####     [/x7](http://x7.xream.io) 
####     [/acku](http://acku.xream.io)
   
    to develop project quickly


## sqli
   [http://sqli.xream.io](http://sqli.xream.io)
   
[![license](https://img.shields.io/github/license/x-ream/sqli.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![maven](https://img.shields.io/maven-central/v/io.xream.sqli/sqli-parent.svg)](https://search.maven.org/search?q=io.xream)
   
        @X.Key
        @X.Mapping
        Q q = QB.of(Foo.class).select(id).eq("qty",1).build();

## x7
   [http://x7.xream.io](http://x7.xream.io)
   
[![license](https://img.shields.io/github/license/x-ream/x7.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![maven](https://img.shields.io/maven-central/v/io.xream.x7/x7-parent.svg)](https://search.maven.org/search?q=io.xream)

       
       x7-repo
          extends BaseRepository<Foo>
          extends RepositoryX
          @EnableX7Repository
          @EnableX7L2Caching
          @X.Mapping
          @X.Key
              
    
### maven dependency
```xml

<dependency>
    <groupId>io.xream.x7</groupId>
    <artifactId>x7-spring-boot-starter</artifactId>
    ....
</dependency>

```
        
## acku
   [http://acku.xream.io](http://acku.xream.io)
   
[![license](https://img.shields.io/github/license/x-ream/acku.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![maven](https://img.shields.io/maven-central/v/io.xream.acku/acku.svg)](https://search.maven.org/search?q=io.xream)

       mq transaction, with tcc option
  
 
### maven dependency
```xml

<dependency>
    <groupId>io.xream.acku</groupId>
    <artifactId>acku-spring-boot-starter</artifactId>
    ....
</dependency>

```  
   

