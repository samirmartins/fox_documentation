Este comando calcula o indicador Awesome Oscillator (AO)
para as últimas 100 barras
de um ativo em questão, dado um tempo gráfico. 

Os tempos gráficos que podem ser utilizados  são: **M5, M15, M30, H1, D1**, em 
que "M" se refere a minutos, "H" a hora e "D" a dia.

Para utilizá-lo, escolha um dos comandos abaixo: 

```console
/ao ativo time_frame 
/ao ativo time_frame parametro_1 parametro_2
```

Em que: 

1. parametro_1 é o período curto do indicador.
2. parametro_2 é o período longo.

Caso parametro_i, para i=1,2 não seja definido pelo usuário, 
serão utilizados 5 e 34 como valores padrão.

Exemplo: 

```console
/ao BTC/USDT D1
```

E verá como saída: 

![](img/ao.png)