# Hjerbata

ビギナーに易しい FunCobal の姉妹言語。発音は/xʲɛrˈbata/。この言語名は「茶」を意味する。拡張子は.hjb。

Sister language, beginners ease version of FunCobal-family. Pronounce is /xʲɛrˈbata/. The name means 'tea'.The extension is '\* .hjb'.

## Usecase

### JIT Compile

```console
$ hjer filename.hjb
```

### AOT Compile

to CIL Source File

```console
$ hjerc -o filename.ches filename.hjb
```

to Windows Excutive File

```console
$ hjerc -o filename.exe filename.hjb
```

to Assembly Source File

```console
$ hjerc -o filename.nas filename.hjb
```

to Object File

```console
$ hjerc -o filename.obj filename.hjb
```

### Interpreter

```console
$ hjer -itp filename.hjb
```

### Interactive

```console
$ hjer --ita hjr
:: Hjerbata Interactive, FunCobal family
hjer>2+3
5
```
