# name_maker

## what's it

It's a program help you make a normal Chinese name and its pingyin.

## prepare

1. open your cmd 
2. use`pip install xpinyin`
3. move the source code to `Python\Lib\site-packages\`
4. use `import name_maker` to use it

## how to use it

* use`makeName()` to make a name as `刘思达`
* use`makeNamePinyin('','')` to make name as `liusida`
* use`makeNamePinyin(' ','')` to make name as `liu sida`
* use`makeNamePinyin(' ',' ')` to make name as `liu si da`
* use`makeNamePinyin('-','')` to make name as `liu-sida`
* use`makeNamePinyin('-','-')` to make name as `liu-si-da`
