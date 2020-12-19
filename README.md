# Hjerbata

ビギナーに易しい FunCobal の姉妹言語。発音は/xʲɛrˈbata/。この言語名は「茶」

Sister language, beginners ease version of FunCobal-family. Pronounce is /xʲɛrˈbata/. The name means 'tea'.The extention is '\* .hjb'.

## Usecase

### JIT Compile

```FanCobal
\$ hjer filename.hjb
```

### AOT Compile

to CIL Source File

```FanCobal
\$ hjerc -o filename.ches filename.hjb
```

to Windows Excutive File

```FanCobal
\$ hjerc -o filename.exe filename.hjb
```

to Assembly Source File

```FanCobal
\$ hjerc -o filename.nas filename.hjb
```

to Object File

```FanCobal
\$ hjerc -o filename.obj filename.hjb
```

### Interpreter

```FanCobal
\$ hjer -itp filename.hjb
```

### Interactive

```FanCobal
$ hjer --ita hjr
:: Hjerbata Interactive, FunCobal family
hjer>2+3
5
```
