Este comando analisa o tamanho das barras em diferentes
tempos gráficos do ativo defindo. A análise do tamanho de 
barras é dividida em: 

1. **Dj (Tds)**, que avalia o tamanho das barras de todos os dojis (de alta e de baixa) nas últimas 100 barras
2. **Dj (Alt)**, que avalia o tamanho das barras dos dojis de alta nas últimas 100 barras
3. **Dj (Bx)**, que avalia o tamanho das barras dos dojis de baixa nas últimas 100 barras
4. **Trd (Tds)**, que avalia o tamanho das barras de tendência (de alta e de baixa) nas últimas 100 barras
5. **Trd (Alt)**, que avalia o tamanho das barras de tendência (de alta) nas últimas 100 barras
6. **Trd (Bx)**, que avalia o tamanho das barras de tendência (de baixa) nas últimas 100 barras

Em conjunto aos dados, é exibido um histograma do tamanho das últimas 100 barras no tempo gráfico "M5" (cinco minutos.)

Os tempos gráficos em questão são **5m, 15m, 30m, 1h, 1d**, em 
que "m" se refere a minutos, "h" a hora e "d" a dia.


**NOTA:** O método de Al Brooks é utilizado para classificar uma barra como Doji ou barra de tendência.  

Para utilizá-lo, digite: 

```console
/tamanhobarras ativo
```

Exemplo: 

```console
/tamanhobarras BTC/USDT
```

E verá como saída: 

![](/img/tamanhobarras.png)