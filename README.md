# Financial Engineering (630) Portfolio Theory

The project looks at 2 optimization methods: 


```math
(\rm{Strategy \: \: I})=   \left\{
\begin{array}{ll}
      max \:  \: \rho^T \omega - \lambda \sqrt{\omega^T \Sigma \omega } & \\
      -.5 \le \sum \beta_{i}^{m} \omega_i \le 0.5 & \\
      \sum \omega_{i} =1 , \: \: -2 \le \omega_i  \le 2\\
\end{array} 
\right.
```

```math
(\rm{Strategy \: \: II})=   \left\{
\begin{array}{ll}
      max \:  \: \frac{\rho^T \omega}{TEV(\omega)} - \lambda \sqrt{\omega^T \Sigma \omega } & \\
      -1 \le \sum \beta_{i}^{m} \omega_i \le 2 & \\
      \sum \omega_{i} =1 , \: \: -2 \le \omega_i  \le 2\\
\end{array} 
\right. 
```


```math
 TEV = \sqrt{w^T\Sigma w - 2 w^T cov(r, r_{SPY}) + \sigma^2_{SPY}} 
```

<br/>

Choose:

```math 
\lambda = .7
```

**Conclusion**

We find the strategy II has the best results

![plot](https://raw.githubusercontent.com/Riley25/FE-630/main/plots/Compare_Trends_II_lambda_7.jpg?raw=true)

