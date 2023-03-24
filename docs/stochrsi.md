Este comando calcula o indicador stoch rsi (índice de força relativa estocástico)
para as últimas 100 barras
de um ativo em questão, dado um tempo gráfico. 

Os tempos gráficos que podem ser utilizados  são: **M5, M15, M30, H1, D1**, em 
que "M" se refere a minutos, "H" a hora e "D" a dia.

Para utilizá-lo, escolha um dos comandos abaixo: 

```console
/stochrsi ativo time_frame 
/stochrsi ativo time_frame parametro_1 parametro_2 parametro_3
```

Em que: 

1. parametro_1 é o periodo 
2. parametro_2 é a janela da média móvel do estocástico RSI
3. parametro_3 é a janela da média móvel de %K

Caso parametro_i, para i=1,2,3 não seja definido pelo usuário, 
serão utilizados 14, 3 e 3 como valores padrão

Exemplo: 

```console
/stochrsi BTC/USDT D1
```

E verá como saída: 

![](img/stochrsi.png)