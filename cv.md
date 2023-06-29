![logo](/img/logo.png)
# Yauheni Shuliakouski
**Phone number:** +375 29 713-79-70   
**e-mail:** zheka1609@yandex.ru   
**Github profile:** [Aidix](https://github.com/Aidix)   
**Nickname on the rs school discord server:** Aidix   

## Objective:
Start a junior JavaScript developer career in the company and in 5 years grow to the team leader   

## Skills:
* JavaScript   
* Work experience with HTML/CSS   
* C++, C# 
* Work experience with SQL  

## Code example:
```
var strr = str.split(''),
      stack = [],
      open = [],
      close = [],
      openI, closeI, openII;

      for (var i=0; i < bracketsConfig.length; i++){
        open.push(bracketsConfig[i][0]);
        close.push(bracketsConfig[i][1]);
      }

      for(i=0; i < strr.length; i++){

        openI = open.indexOf(strr[i]);
        closeI = close.indexOf(strr[i])

        if(openI !== -1){
          openII = stack[stack.length-1];
          if(openII !== closeI){
            stack.push(openI);
            continue;
          }
        }

        if(closeI !== -1){
          openI = stack.pop();
          if(closeI !== openI){
            return false;
          }
        }
      }
      
      if(stack.length !== 0){
        return false;
      }
      return true;
```

## Education:
* BSUIR, Faculty of information technologies and control, Information Technologies in Automated Systems, 2014 - 2018 years 

## English level:
A2(Pre-intermediate)   


