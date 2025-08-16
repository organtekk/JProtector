# JProtector
a simple nodeJS (javascript) obfuscation tool written in c#


# EXAMPLE

## Before JProtecter
```
console.log("HELLO FROM JPROTECTOR!");
```
### Output
```
HELLO FROM JPROTECTOR!
```


## After JProtector
```
console.log("48454C4C4F2046524F4D204A50524F544543544F5221".replace(/.{2}/g,function(c){return String.fromCharCode(parseInt(c,16))}));
```
### Output
```
HELLO FROM JPROTECTOR!
```





> [!NOTE]
> This tool is <ins>not</ins> packed or compiled in any way, feel free to decompile it with [dnspy](https://github.com/dnSpy/dnSpy)
