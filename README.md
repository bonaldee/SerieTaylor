# Errores de truncamiento en las series de Taylor

## Modelado matemático II

### Jorge Leonardo López Agredo. Código: 2218061

### Eliana Bonalde MArcano. Código: 2218065

#### Prof.: Juan Carlos Bastos Pineda
___

El teorema de Taylor establece que dado un entero positivo $n$, y una función que es derivable al menos $n$ veces con todas sus derivadas contínuas alrededor de $x_0$, el valor de la función en un punto $x$ en la vecindad de $x_0$ se puede expresar como

 $$f(x) = f(x_0) + \sum_{j=0}^{n}\dfrac{f^{(j)}(x_0)}{j!}(x-x_0)^j +\dfrac{f^{(n+1)}(c)}{(n+1)!}(x-x_0)^{n+1}  
$$

para algún valor $c$ entre $x_0$ y $x$. Este resultado puede escribirse de la forma compacta 

$f(x) = P_n(x)+R_n(x).$

El polinomio obtenido al truncar la serie en $n$ términos es llamado $n$**-esímo polinomio de Taylor**  y $R_n$ es el **residuo** o **error de truncamiento**.
