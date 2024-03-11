Черновая версия описания задачи (будет дополняться и уточняться)

  

$$\theta$$

$$\alpha = 0.05$$

  

$$ P\{\hat{\theta}_{1,n} \leq \theta \leq \hat{\theta}_{2,n} \} = 1 - \alpha$$

  

$$ N(M, \sigma^2), \{x_1, ..., x_n\}$$

  

$$ \overline{x_n} - \frac{S_n}{\sqrt{n}}t_{\frac{\alpha}{2}, n-1} \leq M \leq \overline{x_n} + \frac{S_n}{\sqrt{n}}t_{\frac{\alpha}{2}, n-1}$$

  
  
  
  
  
  
  

$$ n = 200; x \in N(3;5) $$

$$ k = [log_2200] + 1 \approx 8 $$

  

$$ \frac{n-1}{\chi^2_{1-\frac{\alpha}{2},n-1}}S_n^2 \leq r^2 \leq \frac{n-1}{\chi^2_{\frac{\alpha}{2},n-1}}S_n^2$$

  

  

Бернулли

$$ B(0,3; 200)$$

$$ \frac{m}{n} - \mu_\frac{\alpha}{2}\frac{\sqrt{m(n-m)}}{n} \leq P \leq \frac{m}{n} + \mu_\frac{\alpha}{2}\frac{\sqrt{m(n-m)}}{n}$$

  
  
  
  

$$ B(0,3; 50) $$

$$ P_{ниж} \leq P \leq P_{верх} $$

  

$$ \hat{P}_{ниж} = \frac{n}{n+\mu_\frac{\alpha}{2}}(\frac{m}{n} + \frac{\mu_{\frac{\alpha}{2}}^2}{2n}-\mu_{\frac{\alpha}{2}}\sqrt{\frac{m}{n}(1-\frac{m}{n})+\frac{\mu_{\frac{\alpha}{2}}^2}{2n}})$$

  

$$ \hat{P}_{верх} = \frac{n}{n+\mu_\frac{\alpha}{2}}(\frac{m}{n} + \frac{\mu_{\frac{\alpha}{2}}^2}{2n}+ \mu_{\frac{\alpha}{2}}\sqrt{\frac{m}{n}(1-\frac{m}{n})+\frac{\mu_{\frac{\alpha}{2}}^2}{2n}})$$

  

  

Пуассоновское

$$ P(\theta) $$

$$ \frac{\theta^k}{k!}e^{-\theta} $$

$$ \overline{x_n} - \frac{\sqrt{\overline{x_n}}}{\sqrt{n}}(?) \leq \theta \leq \overline{x_n} + \frac{\sqrt{\overline{x_n}}}{\sqrt{n}}\mu_{\frac{\alpha}{2}}$$

$$ n=200 $$

  
  

$$ \lambda e^{-\lambda} , x > 0$$

$$ 0, x \leq 0 $$

$$ \frac{1}{\overline{x_n}} - \frac{\mu_{\frac{\alpha}{2}}}{\sqrt{n\overline{x_n}}} \leq \lambda \leq \frac{1}{\overline{x_n}} + \frac{\mu_{\frac{\alpha}{2}}}{\sqrt{n\overline{x_n}}}$$

  
  
  
  

Ядерные оценки

$$ k(x) \geq 0 $$

$$ \int_{-\infty}^{\infty}k(x)dx = 1 $$

$$ k(-x) = k(x) $$

  
  
  
  
  
  

Ширина окна h

  

$$ \hat{f}(x) = \frac{1}{n}\sum_{j=1}^nk_h(x-x_j) $$

$$ k_h(x) = \frac{1}{h}k(\frac{x}{h}) $$

  
  
  
  
  
  

$$n \rightarrow \infty $$

$$ h \rightarrow 0 $$

$$ h \sim \frac{1}{\sqrt[5]{n}} $$

  

h оптимизированная под гауусса:

$$ h_{опт} = \frac{1,05S_n}{\sqrt[5]{n}} $$

где S<sub>n</sub> - исправленная дисперсия

  
  
  
  
  
  

Построить ядерную оценку для `N(3;5)` с h<sub>n</sub>, за k(x) взять гауссовское и прямоугольное ядра

  

То же самое сделать для `uniform[3;5]`

  

Построить графики исходных данных плотностей и ядерных оценок (?)