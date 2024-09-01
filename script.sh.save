#!/usr/bin/env bash

echo "Troca de colunas Managers(1) e Ano(2)"
#sed 's/,/\t/g'
#expand -t1 Managers.csv
cut -d "," -f 1 Managers.csv > PrimeiraColuna.txt
cut -d "," -f 2 Managers.csv > SegundaColuna.txt
cut -d "," -f 3,4,5,6,7,8,9,10 > RestoColunas.txt
paste -d "," SegundaColuna.txt PrimeiraColuna.txt RestoColunas.txt > JuncaoColunas.txt
head JuncaoColunas.txt
