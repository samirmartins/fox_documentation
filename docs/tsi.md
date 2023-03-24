Este comando calcula o indicador True strength index (TSI) para as últimas 100 barras
de um ativo em questão, dado um tempo gráfico. 

Os tempos gráficos que podem ser utilizados  são: **M5, M15, M30, H1, D1**, em 
que "M" se refere a minutos, "H" a hora e "D" a dia.

Para utilizá-lo, escolha um dos comandos abaixo: 

```console
/tsi ativo time_frame 
/tsi ativo time_frame parametro_1 parametro_2
```

Em que: 

1. parametro_1 é o tamanho da janela lenta
2. parametro_2 é o tamanho da janela rapida

Caso parametro_i, para i=1,2 não seja definido pelo usuário, 
serão utilizados 25 e 13 como valores padrão

Exemplo: 

```console
/tsi BTC/USDT D1
```

E verá como saída: 

![](img/tsi.png)