# Mogic
## A computer language in logic 逻辑编程语言
### example1:  
#### *in test.mgc*:  
```mgc
>>2*(7+6)  
>>9+7  
>>(8+6)*7;  
>>"hello"+"world"  
>>True or True;
>>1 or 2
>>0 and 0
```

####  result:  
*26*  
*16*  
*98*  
*helloworld*  
*Ture*  
*True*  
*False*  
##### Split statements with__semicolons__
##### 用**分号**分割语句
______
______


### example2:  
#### in *first.mgc*:  
```mgc
dom [food];  
obj [apple];  
predi [can be eaten];  

know([apple] into [food]);

know(forall [i] into [food] ([can be eaten]([i])));

>> [can be eaten]([apple]);
```

#### result:  
*can be eaten(apple) = true*  

### more example read in the file "examples.mgc" 

## vs code extension in the file "MogicExtension"  
