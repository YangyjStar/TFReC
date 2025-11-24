# TFReC  
the result of TFReC Feature Analysis  

## feature_change_trends_scatter  

![feature_change_trends_scatter](https://github.com/YangyjStar/TFReC/blob/main/feature_change_trends_scatter.jpg)  
X:Flow index  
y:$$y=
\begin{cases}
 & 10^{lg\left(1+\frac{f_X(e)-f_X(0)}{f_X(0)}\right)} & iff_x(e)\geq f_x(0) \\
 & -10^{lg\left(1+\left|\frac{f_X(e)-f_X(0)}{f_X(0)}\right|\right)} & otherwise & & 
\end{cases}$$  

## feature_statistics  
![feature_statistics](./feature_statistics.svg)  
X:Perturbation intensity
y:  $y={{10}^{lg\left ({1+\frac{p(x)}{\mathrm{μ(0)}}}\right)}}$  
p(x): the statistics ($mean$, $median$, $max$, $min$, $Q_{25}$, $Q_{75}$) of feature in perturbation intexsity $x$
