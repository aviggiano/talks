# Comandos Bash

### Intro

[Unix](https://en.wikipedia.org/wiki/Unix_philosophy#Do_One_Thing_and_Do_It_Well): cada comando faz apenas uma coisa e uma coisa bem

### Edição e visualização

```
touch
echo
> >>
cat
less ***
tail
head
```

### Manual

```
man
```

### Processamento

``` 
sort
|
cut
paste
grep ***
awk ***
xargs ***
find
```

### Outros

```
&
man
tee
uniq
bc
jq
xclip / pbcopy
```

### Demo

1. Ordenação do arquivo por região
2. Somatória de Total Profit (`head data.csv | cut -f14 -d, | tail -n +2 | paste -s -d+ | bc`)
3. Quantas colunas tem no arquivo
4. Instalar eslint de um projeto para o outro
5. Onde está instalado o Dota?
6. Quais são todos os projetos que tem o logger instalado?
7. Unique countries
8. Total revenue
9. Month-Year sorted by Cost

### Notas

- Para [MacOS](https://formulae.brew.sh/formula/coreutils)
- [1.5 M records CSV](http://eforexcel.com/wp/downloads-18-sample-csv-files-data-sets-for-testing-sales/)
- Regex
- [Command Line Murders](https://github.com/veltman/clmystery)