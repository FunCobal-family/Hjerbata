# Hjerbata
Sister language, beginners ease version of  FunCobal-family. Pronounce is /xʲɛrˈbata/. The name means 'tea'.The extention is '* .hjb'.

## Usecase

### JIT Compile 
```
$ hjer filename.hjb
```
### AOT Compile
to CIL Source File
```
$ hjerc -o filename.ches filename.hjb
```
to Windows Excutive File
```
$ hjerc -o filename.exe filename.hjb
```
to Assembly Source File
```
$ hjerc -o filename.nas filename.hjb
```
to Object File
```
$ hjerc -o filename.obj filename.hjb
```
### Interpreter
```
$ hjer -it filename.hjb
```
### Interactive
```
$ hjer --int 
:: Hjerbata Interactive
hjer>2+3
5
```
