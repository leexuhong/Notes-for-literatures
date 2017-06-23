

# Study of Tracking Efficiency and Systematic Uncertainty

\(https://arxiv.org/pdf/1507.03453.pdf\)

## Key Words



tracking efficiency, the methodology, systemaic uncertainty, influence factors



## Introduction



- in the physics analysis, the systematic uncertainty of tracking i usually defined as the difference of the efficiency  between Monte Carlo \(MC\) and data



- because of the typical low background level, high statistics, broad momentum and angular distribution, etc, the clean sample of $J/\psi \rightarrow p \overline{p} \pi^{+} \pi^{-}$ decay is chosen for this study 




# Study of Tracking Efficiency and Systematic Uncertainty
(https://arxiv.org/pdf/1507.03453.pdf)
## Key Words

tracking efficiency, the methodology, systemaic uncertainty, influence factors

## Introduction

- in the physics analysis, the systematic uncertainty of tracking i usually defined as the difference of the efficiency  between Monte Carlo (MC) and data

- because of the typical low background level, high statistics, broad momentum and angular distribution, etc, the clean sample of $J/\psi \rightarrow p \overline{p} \pi^{+} \pi^{-}$ decay is chosen for this study 

## Definition
### definition
#### tracking efficiency: 
$$\epsilon_{trk}=\frac{n}{N}$$
- N: the number of signal events,all other particles are reconstructed, no matter whether the studied particle is reconstructed or not
- the subset of N, the number of signal events with the studied particle is reconstructed

#### systemaltic uncertainty : 
$$\Delta_{trk}=1-\frac{\epsilon_{trk}(MC)}{\epsilon_{trk}(data)}$$
- $\Delta_{trk}$ represnets the difference of tracking efficiency between Monte Carlo and data

#### error of tracking efficiency and uncertainty
- <font color=blue>the covariance  matrix</font> of (n,N) is 
$$
\begin{pmatrix}
cov(N,N)=(\sigma_N)^2&cov(N,n)=(\sigma_n)^2\\ cov(n,N)=(\sigma_n)^2&cov(n,n)=(\sigma_n)^2
\end{pmatrix}
$$
- <font color=blue>the derivative</font> is
$$
\frac{\partial\epsilon_{trk}}{\partial N}=-\frac{\epsilon_{trk}}{N},\frac{\partial\epsilon_{trk}}{\partial n}=-\frac{1}{N}
$$
- <font color=blue>the error on the tracking eiffciency</font> is
$$
\sigma_{\epsilon_{trk}} = \sqrt{\bigl(\begin{smallmatrix} -\frac{\epsilon_{trk}}{N}&-\frac{1}{N} \end{smallmatrix}\bigr) \bigl(\begin{smallmatrix} (\sigma_N)^2&(\sigma_n)^2\\ (\sigma_n)^2&(\sigma_n)^2 \end{smallmatrix}\bigr)\bigl(\begin{smallmatrix} -\frac{\epsilon_{trk}}{N}\\-\frac{1}{N} \end{smallmatrix}\bigr)}= \frac{1}{N}\sqrt{(1-2\epsilon_{trk})(\sigma_n)^2+\epsilon^{2}_{trk}(\sigma_{N})^2}
$$

- <font color=blue>error o tracking systematic uncertainty</font> is
$$
\sigma_{\Delta_{trk}}=(1-\Delta_{trk}) \cdot\sqrt{\frac{\sigma^{2}_{\epsilon_{trk}(MC)}}{\epsilon^{2}_{trk}(MC)}+\frac{\sigma^{2}_{\epsilon_{trk}(data )}}{\epsilon^{2}_{trk}(data)}}
$$

### example
process: $J/\psi \rightarrow p \overline{p} \pi^{+} \pi^{-}$
- at least three charged tracks should be recontructed and identiied as $\overline{p}, \pi^{+}, \pi^{-}$
- N is obtained by fitting the missing mass distribution of $\overline{p}, \pi^{+}, \pi^{-}$
- n is obtained by itting missing mass distribution while the fourth charged track is reconstructed



\#\# Definition

\#\#\# definition

\#\#\#\# tracking efficiency: 

$$\epsilon\_{trk}=\frac{n}{N}$$

- N: the number of signal events,all other particles are reconstructed, no matter whether the studied particle is reconstructed or not

- the subset of N, the number of signal events with the studied particle is reconstructed



\#\#\#\# systemaltic uncertainty : 

$$\Delta\_{trk}=1-\frac{\epsilon\_{trk}\(MC\)}{\epsilon\_{trk}\(data\)}$$

- $\Delta\_{trk}$ represnets the difference of tracking efficiency between Monte Carlo and data



\#\#\#\# error of tracking efficiency and uncertainty

- &lt;font color=blue&gt;the covariance  matrix&lt;/font&gt; of \(n,N\) is 

$$

\begin{pmatrix}

cov\(N,N\)=\(\sigma\_N\)^2&cov\(N,n\)=\(\sigma\_n\)^2\\ cov\(n,N\)=\(\sigma\_n\)^2&cov\(n,n\)=\(\sigma\_n\)^2

\end{pmatrix}

$$

- &lt;font color=blue&gt;the derivative&lt;/font&gt; is

$$

\frac{\partial\epsilon\_{trk}}{\partial N}=-\frac{\epsilon\_{trk}}{N},\frac{\partial\epsilon\_{trk}}{\partial n}=-\frac{1}{N}

$$

- &lt;font color=blue&gt;the error on the tracking eiffciency&lt;/font&gt; is

$$

\sigma\_{\epsilon\_{trk}} = \sqrt{\bigl\(\begin{smallmatrix} -\frac{\epsilon\_{trk}}{N}&-\frac{1}{N} \end{smallmatrix}\bigr\) \bigl\(\begin{smallmatrix} \(\sigma\_N\)^2&\(\sigma\_n\)^2\\ \(\sigma\_n\)^2&\(\sigma\_n\)^2 \end{smallmatrix}\bigr\)\bigl\(\begin{smallmatrix} -\frac{\epsilon\_{trk}}{N}\\-\frac{1}{N} \end{smallmatrix}\bigr\)}= \frac{1}{N}\sqrt{\(1-2\epsilon\_{trk}\)\(\sigma\_n\)^2+\epsilon^{2}\_{trk}\(\sigma\_{N}\)^2}

$$



- &lt;font color=blue&gt;error o tracking systematic uncertainty&lt;/font&gt; is

$$

\sigma\_{\Delta\_{trk}}=\(1-\Delta\_{trk}\) \cdot\sqrt{\frac{\sigma^{2}\_{\epsilon\_{trk}\(MC\)}}{\epsilon^{2}\_{trk}\(MC\)}+\frac{\sigma^{2}\_{\epsilon\_{trk}\(data \)}}{\epsilon^{2}\_{trk}\(data\)}}

$$



\#\#\# example

process: $J/\psi \rightarrow p \overline{p} \pi^{+} \pi^{-}$

- at least three charged tracks should be recontructed and identiied as $\overline{p}, \pi^{+}, \pi^{-}$

- N is obtained by fitting the missing mass distribution of $\overline{p}, \pi^{+}, \pi^{-}$

- n is obtained by itting missing mass distribution while the fourth charged track is reconstructed









