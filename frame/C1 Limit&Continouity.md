
# 第1讲函数极限与连续  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/ba1f9a668b18f03a9711b4927a6da2d887569c1259c8b8a1a661eb2b12c526cb.jpg)  
# 函数极限的定义及使用  

# 1.定义  

$\operatorname*{lim}_{x\to\cdot}f(x\,)=A\!\leftrightarrow\!\forall\,\epsilon>0$ ，当 $x\rightarrow\bullet$ 时， $|\;f(x\,)-A\;|\!<\!\epsilon$  

# 【注】 $\lvert x\rightarrow\cdot$ 是指 $x\rightarrow x_{\bar{\imath}}\rightarrow x_{\bar{\imath}}^{+}\,,x\rightarrow x_{\bar{\imath}}^{-}\,,x\rightarrow\infty,x\rightarrow+\infty,x\rightarrow-\infty$ 这六种情形.  

# 2.使用  

当 $\operatorname*{lim}_{x\to\cdot}f(x)$ 存在时，  

$\textcircled{1}$ （是常数）常记 $\operatorname*{lim}_{x\to\cdot}f(x\,)=A\,,A$ 是一个常数.  

$\textcircled{2}$ (唯一性)A唯一:左极限 $=$ 右极限。  
 $\textcircled{3}$ （局部有界性）当 $x\rightarrow\cdot$ 时， $\exists\,M>0$  $\left|f(x)\right|\leqslant M$   
 $\circled{4}$ （局部保号性）当 $x\rightarrow\bullet$ 时,若 $A>0$ ，则 $f(x)>0$ ;若 $x\rightarrow\bullet\cdot$ 时， $f(x)\geqslant0$ ，则 $A\geqslant0$  

以下各式，只要存在，即为常数：$\operatorname*{lim}_{x\to\cdots}f(x)=A\;,\;\;\;\operatorname*{lim}_{n\to\infty}x_{n}=A\;,\;\;\;f^{\prime}(x_{0})=A\;,$  

$$
\int_{a}^{b}f(x)\mathrm{d}x=A\ ,\ \ \iint f(x,y)\mathrm{d}\sigma=A\ ,\ \cdots.
$$  

$\circled{5}$ （等式脱帽法 $)f(x)=A+\alpha$ .其中 $\operatorname*{lim}_{x\to\cdot}=0$  

例1.1  

已知 $\operatorname*{lim}_{x\to+\infty}f(x)$ 存在,且 $f(x)={\frac{x^{1+x}}{(1+x)^{x}}}-{\frac{x}{\mathrm{e}}}+2\cdot\operatorname*{lim}_{x\to+\infty}f(x)$ 求 $f(x)$  

【解】设 $\operatorname*{lim}_{\*{\to}+\infty}f(x)=A$ ，则  

即  

可得  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/fa703354a16d7ac882c9a7896c8ac6ec1435b1ef7c36c5153b1ba1c60e27d956.jpg)  
$$
\begin{array}{r l}&{=\,\frac{1}{\mathrm{e}^{2}}\operatorname*{lim}_{t\to0^{+}}\frac{\mathrm{e}^{\frac{1}{t}\ln(1+t)}-\mathrm{e}}{t}=\frac{1}{\mathrm{e}}\operatorname*{lim}_{t\to0^{+}}\frac{\mathrm{e}^{\frac{\ln(1+t)}{t}-1}-1}{t}}\\ &{=\,\frac{1}{\mathrm{e}}\cdot\operatorname*{lim}_{t\to0^{+}}\frac{\ln(1+t)-t}{t^{2}}=\,-\frac{1}{2\mathrm{e}},}\end{array}
$$  

故$f(x)={\frac{x^{1+x}}{(1+x)^{x}}}-{\frac{x}{\mathrm{e}}}-{\frac{1}{\mathrm{e}}}.$  

【注】（1）本题的命制对计算能力提出了较高要求，提醒考生重视计算  

$(2)f(x)=(1+x)^{\frac{1}{x}}$ 在 $x>0$ 时有以下性质：  
 $\textcircled{1}f(x)$ 单调减少： $;\mathcal{D}\operatorname*{lim}_{x\to0^{+}}f(x)=\;\mathbf{e};\mathcal{\ B}(1+x)^{\frac{1}{x}}-\mathbf{e}\sim-\frac{\mathbf{e}}{2}x(x\to0^{+}).$  $x_{n}=\left(1+{\frac{1}{n}}\right)$ 在 $n\rightarrow\infty$ 时有以下性质：  
 $\textcircled{1}\{x_{n}\}$ 单调增加 $\textcircled{2}\operatorname*{lim}_{n\to\infty}x_{n}=\operatorname{e};\textcircled{3}\Big(1+\frac{1}{n}\Big)^{n}-\operatorname{e}\sim-\frac{\textbf{e}}{2}\cdot\frac{1}{n}.$   
以上均是常用的性质，要熟悉。  

例1. 2已知 $\operatorname*{lim}_{x\to0}\left[a\arctan{\frac{1}{x}}+(1+\mid x\mid)^{\frac{1}{x}}\right]$ 存在,则常数 $a=-$  

【解】应填 $\frac{1-\mathrm{e}^{2}}{\pi\mathrm{e}}$   
因为 $\operatorname*{lim}_{x\to0}\left[a\arctan{\frac{1}{x}}+(1+\mid x\mid)^{\frac{1}{x}}\right]$ 存在,且$\operatorname*{lim}_{\substack{x\to0^{-}}}\left[a\arctan\frac{1}{x}+\!\left(1+|\mathbf{\Delta}x_{\mathbf{\Delta}}|\right)^{\frac{1}{x}}\right]=\operatorname*{lim}_{x\to0^{-}}a\arctan\frac{1}{x}+\operatorname*{lim}_{x\to0^{-}}(1-x)^{\frac{1}{x}}=\mathbf{\Delta}-\frac{\pi}{2}a+\frac{1}{\mathrm{e}},$ $\operatorname*{lim}_{\substack{x\to0^{+}}}\left[a\arctan\frac{1}{x}+\left(1+\mid x\mid\right)^{\frac{1}{x}}\right]=\operatorname*{lim}_{x\to0^{+}}a\arctan\frac{1}{x}+\operatorname*{lim}_{x\to0^{+}}(1+x)^{\frac{1}{x}}=\frac{\pi}{2}a+\mathbf{e},$  

所以 $-\,{\frac{\pi}{2}}a+{\frac{1}{\mathrm{e}}}=\,{\frac{\pi}{2}}a+\mathrm{e}.$ 故 $a={\frac{1-\mathrm{e}^{2}}{\pi\mathrm{e}}}$  

例 1. 3设 $f(x)$ 在 $[a,b]$ 上可导，且在点 $x=a$ 处取最小值,在点 $x=b$ 处取最大值,则).  

$$
\begin{array}{r l r}&{\mathrm{(A)}f_{+}^{\prime}(a)\leqslant0,f_{-}^{\prime}(b)\leqslant0\qquad\qquad\qquad}&{\mathrm{(B)}f_{+}^{\prime}(a)\leqslant0,f_{-}^{\prime}(b)\geqslant0}\\ &{\mathrm{(C)}f_{+}^{\prime}(a)\geqslant0,f_{-}^{\prime}(b)\leqslant0\qquad\qquad}&{\mathrm{(D)}f_{+}^{\prime}(a)\geqslant0,f_{-}^{\prime}(b)\geqslant0}\end{array}
$$  

【解】应选(D).$f(a\,)$ $f(x)\geq f(\alpha),x\in(a,b]$ $f_{{+}}^{\prime}(a)$  

$$
f_{+}^{\prime}(a)=\operatorname*{lim}_{x\to a^{+}}{\frac{f(x)-f(a)}{x-a}}\geq0.
$$  

因为 $f(b)$ 是最大值,所以 $f(x)\leqslant f(b),x\in[a,b)$ ，又 $f^{\prime}-(b)$ 存在，故  
$$
f_{-}^{\prime}(b)=\operatorname*{lim}_{x\to b^{-}}{\frac{f(x)-f(b)}{x-b}}\geq0.
$$  

应选(D).  

【注】(1)本题考查可导函数在端点处取最值的必要条件,总结如下：  
设$f(x)$ 在$[a,b]$ 上可导，则 $f(x)$ 在$[a,b]$ 上必存在最大（小）值，且   
 $\textcircled{1}$ 若 $f(x)$ 在 $x=a$ 处取 $[a,b]$ 上的最大(小)值,则 $f_{+}^{\prime}(a)\leqslant0(\geqslant0)$ ；  
 $\textcircled{2}$ 若 $f(x)$ 在 ${\boldsymbol{x}}={\boldsymbol{b}}$ 处取 $[a,b]$ 上的最大(小) 值,则 $f_{-}^{\prime}(b)\geqslant0(\leqslant0)$   
(2)若 $f(x)$ 在 $[a,b]$ 上可导,且在点 $x=c\in(a,b)$ 处取最小或最大值，则必有 $f^{\prime}(c)=0$ ，此为费马定理.  

(3) 在考研中,要习惯函数 $f(x)$ 的“升阶”或“降阶”.若本题命制成 $F(x)=\int_{a}^{x}f(t)\,\mathrm{d}t$  $\boldsymbol{x}\in[a,b]$ ，此谓“升阶”.则 $\scriptstyle F(x)$ 是 $f(x)$ 在 $[a,b]$ 上的一个原函数,于是  

$\textcircled{1}$ 若 $f(x)$ 在 $[a,b]$ 上可导,且当 $f(x)$ 在 $x{=}a$ 处取得最大(小)值时,有 $F_{+}^{\prime\prime}(a)\leqslant0(\geqslant0)$  $\textcircled{2}$ 若 $f(x)$ 在 $[a,b]$ 上可导,且当 $f(x)$ 在 $_{x=b}$ 处取得最大(小)值时,有 $F_{-}^{\prime\prime}(b)\geq0(\leqslant0)$  $\textcircled{3}$ 若 $f(x)$ 在 $[a,b]$ 上可导,且当 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{c}\in(a,b)$ 处取得最大或最小值时,有$F^{\prime\prime}(c)=\,0.$  

例1.4设 $f(x)$ 在 $x\!=\!0$ 处连续，且 $\operatorname*{lim}_{x\to0}{\frac{\mathbf{e}^{f(x)}-\cos\,x+\sin\,x}{x}}=0$ ,则 $f^{\prime}(0)\mathop{=}^{}$  

【解】应填一1.  

因题设 $:\operatorname*{lim}_{x\to0}{\frac{\operatorname{e}^{f(x)}-\cos\,x+\sin\,x}{x}}=0$ ,所以若 lim f(x)=A, 则 f(x)= A +a, $\frac{\mathsf{e}^{f(x)}-\cos\,x+\sin\,x}{x}=\alpha$ 其中α→0(x-→)，  

其中 $\operatorname*{lim}_{x\to0}=0$ ,从而 $f(x)=\ln(\alpha x+\cos x-\sin x)$  

因为 $f(x)$ 在 $_{x}=0$ 处连续，所以  

$$
\begin{array}{r l r}{\lefteqn{-\operatorname*{lim}_{x\to0}(x)-\operatorname*{lim}_{x\to0}(x+\cos x-\sin x)=0,}}\\ &{}&{f^{\prime}(0)=\operatorname*{lim}_{x\to0}\frac{f(x)-f(0)}{x}}\\ &{}&{\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\; 
$$  

[注】(\*)式不能用洛必达法则,因为不知道 $\pmb{\alpha}$ 是否可导。 $(\texttt{\textbf{\times}})$ 式来自等价无穷小替换。  
# 函数极限的计算  

即为七种未定式 $(\ast\frac{0}{0},\ast$ 型 $^{\bullet}\frac{,}{\infty},$ 型 $^{\bullet}\infty\cdot0^{\bullet}$ 型 ${\bf\nabla}^{\bullet}\infty-\infty^{\bullet\bullet}$ 型 $*_{\infty}0\,\mathfrak{m}$ 型， $\bullet\,\bullet\,\bullet$ 型， $*_{1}\infty\,{\mathfrak{m}}$ 型）的计算.  

#  $1.$ 化简先行  

（1）等价无穷小替换  

$\textcircled{1}$ 普通函数型.  

当 $x\,\rightarrow\,0$ 时，  

sin $x\sim x$ ,tan $x\sim x$ ,arcsin $x\sim x$ ,arctan $x\sim x\;,\mathrm{e}^{x}-1\sim x$ ，$\mathfrak{a}(1+x)\sim x\,,\ln(x+\sqrt{1+x^{\,^{2}}})\sim x\,,a^{\,^{x}}-1=\mathrm{e}^{x^{\ln a}}-1\sim x\ln a(a>0\,\mathrm{B})$ 且$\;a\neq1\;.$ $1-\cos\,x\sim\frac{1}{2}x^{2}\,,1-\cos^{\circ}x\sim\frac{\alpha}{2}x^{2}\,,(1+x\,)^{\circ}-1\sim\alpha x\,(\alpha\neq0).$  

【注】（1）当 $x\rightarrow0$ 时， $\ln(x+{\sqrt{1+x^{2}}}\,)\sim x$  

证由于 $\operatorname*{lim}_{x\to0}{\frac{\ln(x+{\sqrt{1+x^{2}}})}{x}}=\operatorname*{lim}_{x\to0}{\frac{\frac{1}{\sqrt{1+x^{2}}}}{1}}=1$ ，于是当 $x\rightarrow0$ 时， $\ln(x+{\sqrt{1+x^{2}}})\sim x$ (2)当 $x\rightarrow0$ 时， $1-\cos^{\circ}x\sim{\frac{\alpha}{2}}x^{2}$  

证当 $x\rightarrow0$ 时$,1-\cos^{\circ}x=1-(1+\cos\,x-1)^{\circ}\sim-\,\alpha\,(\cos\,x-1)\sim{\frac{\alpha}{2}}x^{2}.$  

以下 $\mathcal{Q},\mathcal{Q},\mathcal{\@},\mathcal{\textregistered}$ 中，设所给抽象函数均为研究区间上的连续函数.  

$\textcircled{2}$ 复合函数型.  

当 $x\rightarrow0$ 时， $f(x\,)\sim a x^{\,m}\,,g(x\,)\sim b x^{\,n}\,,a b\neq0\,,m\,,n$ 为正整数,则 $f\left[g(x)\right]\sim a b^{\prime n}x^{\prime n n}$  

【注1】证当 $x\rightarrow0$ 时， $f\,\left[g\left(x\,\right)\right]\sim a\left[g\left(x\,\right)\right]^{m}\sim a\left(b x^{\,\prime\,}\right)^{m}=a b^{m}x^{\,m}$ ，证毕  

如,当 $x\rightarrow0$ 时, $\cos(\mathrm{e}^{\frac{x^{2}}{2}}-1)-1\sim c x^{\star}$ ,则 $\scriptstyle c k\;=\;$  

解应填 $-\,{\frac{1}{2}}$  

当 $x\rightarrow0$ 时，  

$$
f(x)=\cos\ x-1\cdots-{\frac{1}{2}}x^{2}\,,g(x\,)={\mathrm{e}}^{\frac{x^{2}}{2}}-1\sim{\frac{1}{2}}x^{2}\,,
$$  

故$f\,\left[g\left(x\,\right)\right]\sim\left(-\,{\frac{1}{2}}\right)\cdot\left({\frac{1}{2}}\right)^{2}\cdot x^{2\cdot2}=-\,{\frac{1}{8}}x^{4}$ ，于是 $c=-\frac{1}{8},k=4,c k=-\frac{1}{2}.$  
【注2】对于命题 $\textcircled{2}$ ，若 $m\,,n$ 为正实数，则要求 $x\to0^{+}$ ，此时，该命题亦成立。  

如，当 $x\to0^{+}$ 时， $\mathrm{e}^{(\sqrt{\sin^{3}x})^{3}}-1\sim c x^{\star}$ ，则 $c k=$  

解应填 $\frac{9}{2}$  

当 $x\to0^{+}$ 时， $f(x)=\mathrm{e}^{x^{3}}-1\sim x^{3}\,,g(x)=\sqrt{\sin^{3}x}\,\sim x^{\frac{\pi}{2}}$ ，则 $f[g(x)]\sim x^{\frac{9}{2}}$ ，于是$c=1,k=\frac{9}{2},c k=\frac{9}{2}.$  

考生若看出当狗 $\rightarrow0$ 时,cos 狗 $-1\cdots-\frac{1}{2}$ 狗2 $,\mathrm{e}^{\psi}-1\sim$ 狗,则能更快速地解决问题,事实 上， $\textcircled{2}$ 是为后面的 $\circled{4}$ 服务的.  

$\textcircled{3}$ 变上限积分型.  

当 $x\rightarrow0$ 时， $f(x)\sim a x^{\,m}\,,a\neq0\,,m$ 为正整数,则 $\int_{0}^{x}f(t)\,\mathrm{d}t\sim\int_{0}^{x}a t^{m}\,\mathrm{d}t.$  

【注1】证 $\operatorname*{lim}_{x\to0}{\frac{\displaystyle\int_{0}^{x}f(t)\,\mathrm{d}t}{\displaystyle\int_{0}^{x}a t^{m}\,\mathrm{d}t}}\,{\frac{\varkappa\,*\,*\,*\,*\,\sharp\,|}{x\to0}}\operatorname*{lim}_{x\to0}{\frac{f(x\,)}{a x^{m}}}=\,1$ ，证毕。如，当 $x\rightarrow0$ 时， $\int_{0}^{x}\left(\mathrm{e}^{\prime}\,^{3}-1\right)\mathrm{d}t\sim\!\int_{0}^{x}t^{3}\,\mathrm{d}t=\left.\frac{1}{4}t^{4}\,\right|_{0}^{x}=\left.\frac{1}{4}x^{4}.$  

【注2】对于命题 $\textcircled{3}$ ，若 $_m$ 为正实数，则要求 $x\to0^{+}$ ，此时，该命题亦成立。  

如，当 $x\to0^{+}$ 时， $\int_{0}^{x}\ln(1+{\sqrt{t^{3}}}\,)\,\mathrm{{d}}t\,\sim\!\int_{0}^{x}t^{\frac{3}{2}}\mathrm{{d}}t=\left.{\frac{2}{5}}t^{\frac{5}{2}}\,\right|_{0}^{x}=\left.{\frac{2}{5}}x^{\frac{5}{2}}.$  

$\circled{4}$ 复合函数与变上限积分型.  

当 $x\to0$ 时， $f(x)\sim a x^{m}\,,g(x)\sim b x^{n}\,,a b\neq0,m\,,n$ 为正整数,则 $\int_{0}^{\mu(x)}f(t)\mathrm{d}t\sim\!\!\int_{0}^{b x^{n}}a t^{m}\,\mathrm{d}t$ 【注1]证令 $F(x)=\!\!\int_{0}^{x}f(t)\,\mathrm{d}t$ ，由 $\textcircled{3}$ 知，当 $x\rightarrow0$ 时， $F(x)\sim\!\int_{0}^{x}a t^{m}\,\mathrm{d}t={\frac{a}{m+1}}x^{m+1}.$ 又由 $\textcircled{2}$ 知当 $x\to0$ 时$\int_{0}^{\mu(x)}f(t)\mathrm{d}t=F\big[g(x)\big]\sim{\frac{a}{m+1}}(b x^{\prime}\,)^{m+1}={\frac{a b^{m+1}}{m+1}}x^{(m+1)n}=\int_{0}^{b x^{\prime}}a t^{m}\,\mathrm{d}t.$ 证毕 如，当 $x\rightarrow0$ 时， $\int_{0}^{2-2\cos\,x}{(\mathrm{e}^{t^{2}}-1)}\,\mathrm{d}t\,\sim\!\int_{0}^{x^{2}}{t^{2}}\,\mathrm{d}t={\frac{1}{3}}t^{3}\left|\,{}_{0}^{x^{2}}\,={\frac{1}{3}}x^{6}\,,$  $\int_{0}^{x^{2}}\left(\mathbf{e}^{t^{3}}-1\right)\mathbf{d}t\,\sim\!\int_{0}^{x^{2}}t^{3}\,\mathrm{d}t={\frac{1}{4}}t^{4}\left|{\mathbf{\Sigma}}_{0}^{x^{2}}={\frac{1}{4}}x^{8}\right.$ （此例中 $g\left(x\right)=x^{2}$ ，属于 $\circledast$ 的特殊情形)。  

【注2】对于命题 $\circledast$ ，若 $m\,,n$ 为正实数，则要求 $x\to0^{+}$ ，此时，该命题亦成立。  

如，当 $x\to0^{+}$ 时， $\int_{0}^{1-\cos x}{\sqrt{\sin\ t^{3}}}\,\mathrm{{d}}t\,\sim\!\int_{0}^{\frac{1}{2}x^{2}}t^{\frac{3}{2}}\mathrm{{d}}t={\frac{2}{5}}t^{\frac{5}{2}}\,\Big|_{0}^{\frac{1}{2}x^{2}}={\frac{2}{5}}\Big({\frac{1}{2}}\Big)^{\frac{5}{2}}x^{5}={\frac{\sqrt{2}}{20}}x^{5}.$  
$\textcircled{5}$ 推广型.  

若 $\operatorname*{lim}_{x\rightarrow0}f(x)=A\neq0,\operatorname*{lim}_{x\rightarrow0}h(x)=\,0$ ,且在 $x\to0$ 时 $,h(x)\neq0$ ，则当 $x\rightarrow0$ 时，  

$$
\int_{0}^{h(x)}f(t)\mathrm{d}t\sim A h(x).
$$  

[注 证  先看一个引理,若 $\operatorname*{lim}_{x\rightarrow0}\frac{f(x)}{g(x)}=1\operatorname*{lim}_{x\rightarrow0}h(x)=0$ ，且在 $x\rightarrow0$ 时 $,h(x)\neq0$ ，则  

$$
\operatorname*{lim}_{x\to0}\frac{\displaystyle\int_{0}^{h(x)}f(t)\mathrm{d}t}{\displaystyle\int_{0}^{h(x)}g(t)\mathrm{d}t}=1.
$$  

证引理：记 $\boldsymbol{h}\left(\boldsymbol{x}\right)=\boldsymbol{u}$ ，则 $\operatorname*{lim}_{x\to0}=0,x\to0$ 时， $\pmb{u}\ne0$  

$$
\operatorname*{lim}_{\displaystyle{x\to0}\;\frac{\displaystyle{\int_{0}^{h(\tau)}{f(t)\,\mathrm{d}t}}}{\displaystyle{\int_{0}^{h(\tau)}{g(t)\,\mathrm{d}t}}}=\operatorname*{lim}_{\displaystyle{u\to0}\;\int_{0}^{u}{g(t)\,\mathrm{d}t}}\frac{\displaystyle{\int_{0}^{u}{f(t)\,\mathrm{d}t}}}{\displaystyle{\int_{0}^{u}{g(t)\,\mathrm{d}t}}}\;\frac{\displaystyle{\ast\ast\ast\ast\ast\ast\ast\ast}\operatorname*{lim}_{u\rightarrow0}{f(u)}}{\displaystyle{\operatorname*{lim}_{u\rightarrow0}\frac{\displaystyle{f(u)}}{\displaystyle{g(u)}}=1},
$$  

引理证毕.  

于是,当 $g(x)=A\neq0,\operatorname*{lim}_{x\rightarrow0}f(x)=A\neq0$ 时,有 $\operatorname*{lim}_{x\to0}{\frac{\displaystyle\int_{0}^{h(x)}f(t)\mathrm{d}t}{\displaystyle\int_{0}^{h(x)}A\mathrm{d}t}}=\ 1$ ，即当 $x\_0$ 时  
$\int_{0}^{h(x)}f(t)\mathrm{d}t\sim A h(x)$ ,证毕.   
如 $,F(x\,)=\!\!\!\int_{0}^{\5x}\,\frac{\sin\,\,t}{t}\mathrm{d}t\,,G(x\,)=\!\!\!\int_{0}^{\sin\,\,x}\left(1+t\,\right)^{\frac{1}{t}}\mathrm{d}t.$ 则当 $x\rightarrow0$ 时$F(x\,)\sim\!\!\int_{0}^{\varsigma_{x}}1\mathrm{d}t=5x\;,G(x\,)\sim\!\!\int_{0}^{\sin\,x}\mathrm{ed}t=\mathrm{esin}\;\;x\,\sim\mathrm{e}x\,,$  

它们是同阶非等价无穷小。  

$\circled{6}$ 若 $\alpha\cdot\beta$ 都是同一自变量变化过程 $x\rightarrow\cdot$ 下的无穷小量，且 $\alpha=o\left(\beta\right)\left(x\rightarrow\bullet\right)$ ，则a. $\alpha+\beta\sim\beta(x\rightarrow\bullet)\,;\mathrm{b},\alpha+\beta$ 与$\beta$ 在$x\rightarrow\bullet$ 时同号.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e03139027cc814c115fc34e731720a0b4bf25e7ce7d196827f7a69f4dd911d36.jpg)  
（3）及时提出极限存在且不为0的因式  

#  $^{2,}$ 洛必达法则  

洛必达法则 $\left\{\begin{array}{l l}{\displaystyle\operatorname*{lim}_{z\to\infty}\frac{f(x)}{g(x)}\mathrm{=}\mathrm{lim}\frac{f^{\prime}(x)}{x\cdots}\mathrm{.}}\\ {\displaystyle\operatorname*{lim}_{z\to\infty}\Biggl\lceil\int_{a}^{\pi}f(t)\mathrm{d}t}\\ {\displaystyle\operatorname*{lim}_{x\to\infty}\Biggl\lceil\int_{a}^{\pi}\varrho(t)\mathrm{d}t\mathrm{=}\mathrm{lim}\frac{f(x)}{x\cdots}\mathrm{.}}\\ {\displaystyle\operatorname*{lim}_{i\in\infty}\int_{a}^{\pi(t)}f(t)\mathrm{d}t}\\ {\displaystyle\operatorname*{lim}_{i\in\cdots}\Biggl\lceil\int_{a}^{\pi(t)}f(t)\mathrm{d}t\mathrm{=}\mathrm{lim}\frac{f[\varphi(x)]\cdot\varphi^{\prime}(x)}{g[\phi(x)]\cdot\psi^{\prime}(x)}\mathrm{.}}\end{array}\right.$  

【注】 考研中,使用洛必达法则要满足三个条件;(1) 当 $x\rightarrow0$ 时,所求极限是 $\frac{0}{0}m$ 型或“88型;(2) 当 $x\rightarrow\bullet$ 时,分子、分母均可导;(3) 极限结果为 $0,c(c\neq0),\infty,$  

# 3.泰勒公式  

(1) 熟记常用公式.  

$\mathbf{e}^{x}=1+x+{\frac{x^{2}}{2!}}+\cdots+{\frac{x^{\,\prime\,}}{n\,!}}+\cdots=\sum_{n=0}^{\infty}\,{\frac{x^{\,\prime\,}}{n\,!}}\,,$   
sin $x=x-{\frac{1}{3!}}x^{3}+\cdots+(-1)^{n}\,{\frac{1}{(2n+1)!}}x^{2n+1}+\cdots=\sum_{n=0}^{\infty}(-1)^{n}\,{\frac{x^{2n+1}}{(2n+1)!}},$   
cos $x=1-{\frac{1}{2!}}x^{2}+\cdots+(-1)^{n}\;{\frac{1}{(2n)!}}x^{2n}+\cdots=\sum_{n=0}^{\infty}(-1)^{n}\;{\frac{x^{2n}}{(2n)!}},$   
$\ln(1+x)=x-{\frac{1}{2}}x^{2}+\cdots+(-1)^{n-1}\,{\frac{x^{\prime}}{n}}+\cdots=\sum_{n=1}^{\infty}(-1)^{n-1}\,{\frac{x^{n}}{n}},\,-\,1<x\leqslant\frac{1}{2}$ 1,   
${\frac{1}{1-x}}=1+x+x^{2}+\cdots+x^{n}+\cdots=\sum_{n=0}^{\infty}x^{n}\,,\mid x\mid<1,$   
${\frac{1}{1+x}}=1-x+x^{2}-\cdots+(-1)^{n}x^{n}+\cdots=\sum_{n=0}^{\infty}(-1)^{n}x^{n}\,,\mid x\mid<1,$   
$(1+x\,)^{\circ}=1+\alpha x+{\frac{\alpha(\alpha-1)}{2}}x^{\,2}+o\,(x^{\,2})(x\,\to0\,,\alpha\,\neq\,0)\,,$   
tan $x=x+\frac{1}{3}x^{3}+o(x^{3})(x\rightarrow0)$   
arcsin $x=x+\frac{1}{6}x^{3}+o(x^{3})(x\rightarrow0)\,,$   
arctan $x=x-\frac{1}{3}x^{3}+o(x^{3})(x\rightarrow0).$  
(2）展开原则.  

$\textcircled{1}\frac{A}{B}$ 型，适用“上下同阶”原则.  

具体来说,如果分母(或分子)是 $_{x}$ 的 $\pmb{k}$ 次幂,则应把分子(或分母)展开到 $_x$ 的k次幂，称为“上下同阶”原则.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/5f67902ec0e03ba14739bf8b74618f9352ea59c21fa5ad369112953fa191cece.jpg)  

# $\widehat{\supseteq}A-B$ 型，适用“幂次最低”原则  

具体来说，即将 $A\,,B$ 分别展开到它们的系数不相等的 $_x$ 的最低次幂为止。  

例1. 6设当 $x\rightarrow0$ 时， $f(x)=\tan\,x-\ln(1+x)$ ）与 $a x^{\flat}$ 等价，则 $\alpha b=$  

【解】应填1.  

当 $x\rightarrow0$ 时，  

$$
\begin{array}{r l r}&{}&{f(x)=\tan x-\ln(1+x)=x+\scriptstyle(0\bullet x^{2})+o(x^{2})-\left[x\displaystyle(-\frac{1}{2}x^{2}\right)+o(x^{2})\right]}\\ &{}&{\to\scriptstyle\frac{\sinh}{2}-\psi\wedge\beta\#\prec\beta\mathbb{R}\pm x^{2}\,\Re\frac{\partial}{\partial\Omega}\notin\pm\;\mathbb{R}\;0,}\\ &{}&{\to\scriptstyle\frac{1}{2}x^{2}+o(x^{2}),\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad}\end{array}
$$  

故$\alpha=\frac{1}{2},b=2$ ,于是 $\alpha b=1$  

4.无穷小比阶  

$$
\operatorname*{lim}_{x\to\infty}{\frac{f(x)}{g(x)}}{\frac{\;{^{\bullet}\!\frac{0}{0}}\!\cdot\!}{\Biggl\{}c\neq0\,,}\;\;
$$  

$\textcircled{1}$ 称$f(x)$ 是$_{g}(x)$ 的高阶无穷小.  

$\textcircled{2}$ 称$f(x)$ 是$_{g}(x)$ 的同阶无穷小（ $c=1$ 时称等价无穷小）.  

$\textcircled{3}$ 称$f(x)$ 是$_{g}(x)$ 的低阶无穷小.  
# 比宇高等数学18洲  

例 1. 7当 $x\,\rightarrow\,0$ 时， $\int_{0}^{x^{2}}{({\bf e}^{\prime}}^{3}-1)\,\mathrm{d}t$ 是 $x^{\,7}$ 的().  

（A）等价无穷小（B）低阶无穷小（C）高阶无穷小（D）同阶但非等价无穷小  

[解】应选(C).  

法一  

$$
\operatorname*{lim}_{x\to0}{\frac{\int_{0}^{x^{2}}{({\bf e}^{t^{3}}-1)}\mathrm{d}t}{x^{7}}}\!=\!\!\operatorname*{lim}_{x\to0}{\frac{2({\bf e}^{x^{6}}-1)}{7x^{5}}}\!=\!\!\operatorname*{lim}_{x\to0}{\frac{2x^{6}}{7x^{5}}}\!=\!0.
$$  

法二由“二、1(1）等价无穷小替换”的结论 $\circled{4}$ ,当 $x\,\rightarrow\,0$ 时， $\int_{0}^{x^{2}}{({\mathrm{e}}^{t^{3}}-1)\,\mathrm{d}t}\sim\int_{0}^{x^{2}}{t^{3}}\,\mathrm{d}t=$ ${\frac{1}{4}}t^{4}\left|{\bf\Sigma}_{0}^{x^{2}}={\frac{1}{4}}x^{8}\right.$ ,为 $x^{\prime}$ 的高阶无穷小.故选(C).  

例 1. 8设tan $x-\ln(1+x)=x$ sin $f(x)$ ,其中 $\mid f(x)\mid<{\frac{\pi}{2}}$ ，则当 $x\rightarrow0$ 时， $f(x)$ 是().  

（A）比 $_{x}$ 高阶的无穷小量(B)比 $_{x}$ 低阶的无穷小量(C)与 $_{x}$ 同阶但不等价的无穷小量（D）与 $_{x}$ 等价的无穷小量  

【解】应选(C).因为tan $x-\ln(1+x)=x$ sin $f(x)$ ，所以  

$$
\operatorname*{lim}_{x\to0}{\frac{\sin\,f(x\,)}{x}}=\operatorname*{lim}_{x\to0}{\frac{\tan\,x-\ln(1+x)}{x^{2}}}\!=\!\operatorname*{lim}_{x\to0}{\frac{{\frac{1}{2}}x^{2}}{x^{2}}}\!=\!{\frac{1}{2}},
$$  

即有  

$$
\operatorname*{lim}_{x\to0}\sin\;f(x)=0.
$$  

注意到 $\mid f(x)\mid<{\frac{\pi}{2}}$ 可知 $\operatorname*{lim}_{x\to0}f(x)=0$ 即 $f(x)$  $x\rightarrow0$ 时的无穷小量,且 $\operatorname*{lim}_{x\to0}{\frac{\sin\,f(x)}{f(x)}}=$ 1,故  

$$
\operatorname*{lim}_{x\to0}{\frac{f(x)}{x}}=\operatorname*{lim}_{x\to0}{\frac{\sin{f(x)}}{x}}={\frac{1}{2}},
$$  

即当 $x\_0$ 时， $f(x)$ 是与 $_{\mathcal{x}}$ 同阶但不等价的无穷小量，选项（C）正确.  

当 $x\,\rightarrow\,0$ 时， $(3+2\tan\,x\,)^{x}-3^{x}$ 是 $3\sin^{2}x+x^{3}\cos{\frac{1}{x}}$ 的（).  

（A）高阶无穷小（B）低阶无穷小（C）等价无穷小（D）同阶但非等价无穷小  

解）应选(D).  

$$
\begin{array}{c}{{\displaystyle{\operatorname*{m}_{\div0}\frac{x^{3}\cos{\frac{1}{x}}}{3\sin^{2}{x}}=\frac{1}{3}\operatorname*{lim}_{x\to0}x\cos{\frac{1}{x}}=0\,,\mathord{\overbrace{\mathbb{M}}}\,\,3\sin^{2}{x}+x^{3}\cos{\frac{1}{x}}\sim3\sin^{2}{x}\sim3x^{\,2}\left(x\to0\right)\,,}}}\end{array}
$$由故  
$$
\operatorname*{lim}_{x\to0}{\frac{(3+2\tan{x})^{x}-3^{x}}{3\sin^{2}{x}+x^{3}\cos{\frac{1}{x}}}}=\operatorname*{lim}_{x\to0}{\frac{3^{x}\left[\left(1+{\frac{2}{3}}\tan{x}\right)^{x}-1\right]}{3x^{2}}}=\operatorname*{lim}_{x\to0}{\frac{\mathrm{e}^{x\ln\left(1+{\frac{2}{3}}\tan{x}\right)}-1}{3x^{2}}}
$$  

$$
\operatorname*{lim}_{x\to0}{\frac{x\ln\!\left(1+{\frac{2}{3}}\tan x\right)}{3{x^{2}}}}=\!\operatorname*{lim}_{x\to0}{\frac{x\,\cdot\,{\frac{2}{3}}\tan x}{3{x^{2}}}}={\frac{2}{9}},
$$  

所以当 $x\,\rightarrow\,0$ 时，它们为同阶但非等价无穷小，故选(D).  

例1. 10 $\operatorname*{lim}_{x\to+\infty}\Bigl(2x\int_{0}^{x}\mathrm{e}^{-t^{2}}\,\mathrm{d}t+\mathrm{e}^{-x^{2}}-\sqrt{\pi}\,x\,\Bigr)=\frac{}{\}\cdot$  

【解】应填0.  

li $\operatorname*{m}_{+\infty}\left(2x\int_{0}^{x}\mathrm{e}^{-t^{2}}\,\mathrm{d}t+\mathrm{e}^{-x^{2}}-\sqrt{\pi}\,x\right)=\operatorname*{lim}_{x\to+\infty}x\left(2\right)_{0}^{x}\mathrm{e}^{-t^{2}}\,\mathrm{d}t-\sqrt{\pi}\,\bigg)=\operatorname*{lim}_{x\to+\infty}\frac{2\!\int_{0}^{x}\mathrm{e}^{-t^{2}}\,\mathrm{d}t-\sqrt{\pi}\,x\,}{\frac{1}{x}}$ ${\frac{\frac{\ast\ast}{\ast}\ast\ast\ast\ast\ast\ast\ast\ast\mid\mid\mathbf{im}\,}{-\ast+\mathbf{\omega}}}{\frac{1}{-{\frac{1}{x^{2}}}}}}=-\operatorname*{lim}_{x\to+\infty}2x^{\,2}\,{\mathrm{e}}^{-x^{2}}=0.$  

例 1. 11 $\operatorname*{lim}_{x\to0}\left[{\frac{1}{\ln(x+{\sqrt{1+x^{2}}}\,)}}-{\frac{1}{\ln(1+x\,)}}\right]={\cfrac{}{\cdot\,}}\quad$  

【解】应填 $-\,{\frac{1}{2}}$  

$$
\begin{array}{r l r}{\lefteqn{\frac{\rightharpoonup}{\ltimes\lnot}\!\operatorname*{lim}_{x\to0}\frac{\ln(1+x)-\ln(x+\sqrt{1+x^{\tau}})}{\ln(x+\sqrt{1+x^{\tau}})\ln(1+x)-x}}}\\ &{}&{\mathrm{=}\ l i m\frac{\ln(1+x)-\ln(x+\sqrt{1+x^{\tau}})}{x^{2}}\ }\\ &{}&{\mathrm{=}\ l i m\frac{\frac{1}{x}\ln(1+x)-\ln(x+\sqrt{1+x^{\tau}})}{x^{2}}}\\ &{}&{\mathrm{\stackrel{(\ast\ast)}{\lnot=}\!\ l i m\frac{\frac{1}{x}\ln\left[1+x-(x+\sqrt{1+x^{\tau}})\right]}{x^{2}}}}\\ &{}&{\mathrm{=}\ l i m\frac{1-\sqrt{1+x^{\tau}}}{x^{2}}\!=\!\!\operatorname*{lim}_{x\to0}\frac{-1}{x^{\tau}}\!=\!-\frac{1}{2}.}\end{array}
$$  

【注 $(\,\star\,)$ 处来自拉格朗日中值定理，即令 $f(u)=\ln u$ ，在 $[1+x\,,x+\sqrt{1+x^{2}}\,]$ 上应用拉格朗日中值定理，有 $\ln(x+{\sqrt{1+x^{2}}}\,)-\ln(1+x\,)=\,{\frac{1}{\hat{\xi}}}\Bigl[(x+{\sqrt{1+x^{2}}}\,)-(1+x\,)\Bigr]\,,$ 其中 $\boldsymbol{\xi}$ 介于 $1+x$ 与 $x+{\sqrt{1+x^{2}}}$ 之间，显然当 $x\rightarrow0$ 时， $1+x$ 与 $x+{\sqrt{1+x^{2}}}$ 都趋于1，于是 $\xi\rightarrow1$ ：  

例 1 12设 $f(x\,)=\left\{\!\!\!\begin{array}{l l}{\mathbf{e}^{\mathbf{x}}\,,}&{x\leqslant0\,,\quad\exists\P\|\operatorname*{lim}_{x\leqslant0}\left[\!\!\left[\int_{-\infty}^{x}f(t\,)\,\mathrm{d}t\right]^{\frac{1}{x-\sin x}}\right.\!\!\!}\\ {x^{2}\,,}&{x>0\,,\quad x\neq0}\end{array}\!\!\!\right.\,.$  
# 比宁高等数学18  

【解】应填 $\mathbf{e}^{2}$  

雞当 $x>0$ 經时 $\int_{-\infty}^{x}f(t)\mathrm{d}t=\int_{-\infty}^{0}\mathrm{e}^{t}\mathrm{d}t+\int_{0}^{x}t^{2}\mathrm{d}t=1+{\frac{1}{3}}x^{3}$ ，于是原式 $=\operatorname*{lim}_{x\to0^{+}}\left(1+{\frac{1}{3}}x^{3}\right)^{\frac{1}{x-\sin x}}=\mathrm{e}^{A}\,.$ 其中 $A=\operatorname*{lim}_{x\rightarrow0^{+}}{\frac{1}{x-\sin x}}\cdot\left(1+{\frac{1}{3}}x^{3}-1\right)=\operatorname*{lim}_{x\rightarrow0^{+}}{\frac{1}{6}}\cdot{\frac{1}{3}}x^{3}=2$ ,故原式 $={\mathrm{e}}^{2}$  

# 三函数极限的存在性  

x >0 .故（-0,x)要拆成 (-∞0,0)与(0,x)两段，  

因为在这两段上 f(x)表达式不同,  

# 1.具体型  

若给出具体函数求极限，但极限式不满足“二、2”的注中提到的使用洛必达法则的三个条件中的任意一个:(1)当 $x\rightarrow\bullet$ 时，所求极限是“ $\frac{0}{0}$ ”型或“ $\mathrel{\stackrel{\infty}{\sim}},$ 型;2)当 $x\rightarrow\bullet$ 时,分子、分母均可导;(3)极限结果为 $0,c(c\neq0),\infty$ ,则洛必达法则失效.可考虑用夹逼准则：若 $\;\;\mathbb{Q}g(x)\leqslant f(x)\leqslant$  $h\left(x\,\right),\ @\operatorname*{lim}_{x\rightarrow.}(x\,)=A\,,\operatorname*{lim}_{x\rightarrow.}h\left(x\,\right)=A$ ，则 $\operatorname*{lim}_{x\to\cdot}f(x)=A$ .这里， $\textcircled{1}$ 中无须验证等号；A可为0，$c(c\neq0),\infty.$  

例 1. 13设 $[x]$ 表示不超过 $_{x}$ 的最大整数，则 $\operatorname*{lim}_{x\to0}\left[{\frac{10}{x}}\right]=\!\!\underbrace{\qquad}_{x\to0}\!\!.$  

【解】应填10.  

$x\rightarrow0$ 时， ${\frac{10}{x}}\!\to\!\infty$ ，对于 $[\infty]$ ,此时想到极限计算的利器一—夹逼准则(当常规求极限的方法，比如等价无穷小替换、泰勒公式、洛必达法则无法使用时，一定要能够想起这个“两边夹击”的重要方法）.  

根据 $x-1<[x]\leqslant x$ ,有  

$$
{\frac{10}{x}}-1<\left[{\frac{10}{x}}\right]\leqslant{\frac{10}{x}},
$$  

于是当 $x>0$ 时， $10-x<x\,\cdot\,{\Bigg[}{\frac{10}{x}}{\Bigg]}\leqslant10$ ;当 $x<0$ 时， $10-x>x\,\cdot\,{\Bigg[}{\frac{10}{x}}{\Bigg]}\geqslant10.$  

可见，无论 $x>0$ ,还是 $x<0$ ,不等式两边均趋于同一极限,故 $\operatorname*{lim}_{x\to0}\left[{\frac{10}{x}}\right]=10$ 费  

例1.14设函数 $f(x)\,{=}\,x-[x]$ 其中 $[x]$ 表示不超过 $_{x}$ 的最大整数，则  

$$
\operatorname*{lim}_{x\to+\infty}{\frac{1}{x}}{\mathord{\int}}_{0}^{x}\,f(t)\,\mathrm{d}t={\underline{{\phantom{x x x x x x x x x x}}}}\cdot
$$  

【解】应填 $\frac{1}{2}$  

当 $x\in[0,1)$ 时， $f(x)\,{=}\,x-\left[{x}\,\right]\,{=}\,x$ ，又由于$f(x+1)=x+1-\left[x+1\right]=x+1-(\left[x\right]+1)=x-\left[x\right]=f(x)\,,$  

故 $f(x)$ 是周期为1的周期函数，其图像如图1-1所示.  
# 第1讲   函数极限与连续  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f55afe21b42e4c0fb450de237233b705895ca34f8048241059b7911fb2c5ccc2.jpg)  
图1-1  

当 $n\leqslant x<n+1$ 时， ${\frac{n}{2}}=\!\!\int_{0}^{n}f(t)\,\mathrm{d}t\leqslant\int_{0}^{x}f(t\,)\,\mathrm{d}t<\int_{0}^{n+1}f(t\,)\,\mathrm{d}t={\frac{n+1}{2}}$ ,于是${\frac{n}{2(n+1)}}=\!{\frac{1}{n+1}}\!\!\int_{0}^{n}f(t)\,\mathrm{d}t<{\frac{1}{x}}{\bigg\int_{0}^{x}}f(t)\,\mathrm{d}t<{\frac{1}{n}}{\bigg\int_{0}^{n+1}}f(t)\,\mathrm{d}t{=}{\frac{n+1}{2n}}.$  

当 $x\rightarrow+\infty$ 时， $n\rightarrow\infty$ ,由夹逼准则,有 $\operatorname*{lim}_{x\to+\infty}{\frac{1}{x}}{\int_{0}^{x}{f(t)\,\mathrm{d}t}}={\frac{1}{2}}.$  

【注】上面两题再次考到了取整函数的两个重要公式:  

(1） $\scriptstyle\sum x\;+\;n\;\]\;=\;[x\;]\;+\;n$ ，其中 $_n$ 为正整数.$(2)x-1<[x]\leqslant x$   
考生要熟悉它们.  

# 2. 抽象型  

若给出抽象函数求极限，可考虑用单调有界准则：若当 $x\rightarrow+\infty$ 时， $f(x)$ 单调增加(减少)且 $f(x)$ 有上界(下界),则 $\operatorname*{lim}_{x\to+\infty}f(x)$ 存在。  

例 1.15（1）证明：当 $x\geqslant1$ 雞时 $\frac{1}{1+x}<\ln\Bigl(1+\frac{1}{x}\Bigr)<\frac{1}{x},$  

（2）设函数 $f(x)$ 在区间 $[1,+\infty)$ 上连续可导，且  

$$
f^{\prime}(x\,)\,{=}\,\frac{1}{1+f^{2}(x\,)}\Biggl[\sqrt{\frac{1}{x}}-\sqrt{\ln\Bigl(1+\frac{1}{x}\Bigr)}\,\Biggr]\,,
$$  

证明： $\operatorname*{lim}_{x\to+\infty}f(x)$ 存在.  

【证]（1）当 $x\geqslant1$ 时，对 $\ln\,t$ 在 $[x\,,x+1]$ 上应用拉格朗日中值定理,有  

$$
\ln(x+1)-\ln\,x={\frac{1}{\xi}},x<\xi<x+1,
$$  

即  

$$
\frac{1}{1+x}<\ln\!\left(1+\frac{1}{x}\right)\!<\!\frac{1}{x}.
$$  

(2)由(1)知， $\sqrt{\frac{1}{x}}-\sqrt{\ln\left(1+\frac{1}{x}\right)}>0$ 又$\frac{1}{1+f^{2}(x)}\!>\!0$ 故$f^{\prime}(x)\!>\!0$ ，于是当 $x\geqslant1$ 时$f(x)$ 严格单调增加,又  

$$
f^{\prime}(x\,)\leqslant{\sqrt{\frac{1}{x}}}-{\sqrt{\ln\!\left(1+{\frac{1}{x}}\right)}}<{\sqrt{\frac{1}{x}}}-{\sqrt{\frac{1}{x+1}}}\,,
$$  

上式两边从1到 $_{x}$ 积分，有  

$$
\begin{array}{l}{{f(x)-f(1)=\displaystyle\int_{1}^{x}{f^{\prime}(t)\mathrm{d}t}\leqslant\int_{1}^{x}\left(\sqrt{\frac{1}{t}}-\sqrt{\frac{1}{t+1}}\right)\mathrm{d}t}}\\ {{\left.\nonumber\,\qquad\qquad<\displaystyle\int_{1}^{+\infty}\left(\sqrt{\frac{1}{t}}-\sqrt{\frac{1}{t+1}}\right)\mathrm{d}t=(2\sqrt{t}-2\sqrt{t+1})\left|\right.^{+\infty}}}\end{array}
$$  
# 陆亨高等数学18洲  

$$
\begin{array}{r l}&{=2\operatorname*{lim}_{t\rightarrow+\infty}(\sqrt{t}-\sqrt{t+1})-(2-2\sqrt{2})}\\ &{=2\operatorname*{lim}_{t\rightarrow+\infty}\frac{-1}{\sqrt{t}+\sqrt{t+1}}-(2-2\sqrt{2})}\\ &{=2(\sqrt{2}-1)\,,}\end{array}
$$  

即  

$$
f(x)<2(\sqrt{2}-1)+f(1),
$$  

故 $f(x)$ 有上界.由单调有界准则，知 $\operatorname*{lim}_{\tau\to+\infty}f(x)$ 存在。  

# 函数极限的应用连续与间断  

# 1.研究位置  

由于一切初等函数在其定义区间内必连续，故只研究两类特殊的点： $\textcircled{1}$ 无定义点（必为间断点）， $\textcircled{2}$ 分段函数的分段点(可能是连续点，也可能是间断点）.  

# 2.连续  

(1)内点处.若 $\operatorname*{lim}_{x\to x_{0}}f(x)=f(x_{0})$ ,其中 $\boldsymbol{x}_{\mathit{\Pi}_{0}}\in\left(a,b\right)$ ，则称 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处连续.  

(2)端点处.设 $x\in[a,b].$ 若$\operatorname*{lim}_{x\to a^{+}}f(x)=f(a)$ ，则称 $f(x)$ 在$x=a$ 处右连续;若 $\operatorname*{lim}_{x\to b^{-}}f(x)=$  $f(b)$ ，则称 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{b}$ 处左连续.  

# 3. 间断  

前提： $f(x)$ 在$\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 左、右两侧均有定义.  

对于 $\mathbb{O}\operatorname*{lim}_{x\to x_{0}^{+}}f(x)\,;\mathbb{O}\operatorname*{lim}_{x\to x_{0}^{-}}f(x)\,;\mathbb{O}f(x_{0}).$  

(1)若 $\textcircled{\scriptsize{1}},\textcircled{\scriptsize{2}}$ 均存在但 $\textcircled{1}$ 不等于 $\textcircled{2}$ ，则 $\boldsymbol{x}=\boldsymbol{x}_{\,0}$ 为跳跃间断点.  

(2)若 $\Phi,\stackrel{\mathcal{O}}{\mathcal{O}}$ 均存在且 $\textcircled{1}$ 等于 $\textcircled{2}$ 但不等于 $\textcircled{3}$ ，则 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{0}}$ 为可去间断点.  

其中（1)（2）组成第一类间断点.  

（3）若 $\textcircled{1}$ ， $\textcircled{2}$ 至少有一个不存在且为无穷大，则 $\boldsymbol{x}=\boldsymbol{x}_{\,0}$ 为无穷间断点.  
（4）若 $\textcircled{1}$ ， $\textcircled{2}$ 不存在且振荡，则 $\boldsymbol{x}=\boldsymbol{x}_{\,0}$ 为振荡间断点.  
其中（3）（4）属于第二类间断点.  

$\int^{3}x\ \sqrt{9-x^{2}t^{2}}\,\mathrm{d}t-9x$ 例 1. 16设在 $x=0$ 的某去心邻域内 $f(x)={\frac{\int\displaylimits_{0}^{\infty}\qquad\qquad\qquad\qquad\quad}{\arctan^{3}x}}$ ，且 $f(0)=a$ ，若 $f(x)$ 在 $x=0$ 处连续，则 $a=-$  

【解】应填 $-\,{\frac{3}{2}}.$  

$\int_{0}^{3}\!x\;\sqrt{9-x^{\,2}t^{\,2}}\,\mathrm{d}t\;\frac{\,\widehat{\ast}\,x\,t=u}{\,}\int_{0}^{3x}\,\sqrt{9-u^{\,2}}\,\mathrm{d}u$  
$$
\operatorname*{lim}_{x\to0}f(x\,)=\operatorname*{lim}_{x\to0}{\frac{\int_{0}^{3x}{\sqrt{9-u^{2}}}\,\mathrm{d}u-9x}{x^{3}}}
$$  

$$
=3\operatorname*{lim}_{x\to0}{\frac{\sqrt{1-x^{\,2}}-1}{x^{\,2}}}\!=\!3\operatorname*{lim}_{x\to0}{\frac{{\frac{1}{2}}(-x^{\,2})}{x^{\,2}}}\!=\!-{\frac{3}{2}}.
$$  

于是当 $\alpha=-\frac{3}{2}$ 时， $\operatorname*{lim}_{x\to0}f(x)=f(0)=-{\frac{3}{2}}$ 即 $f(x)$ 在 ${\boldsymbol x}=0$ 处连续。  

列 1.17函数 $f(x)={\frac{(x^{2}-x)\mid x+1\mid}{\mathrm{e}^{{\frac{1}{x}}}{\Biggl\int}_{1}^{x}t\mid\sin t\mid\mathrm{d}t}}$ 的第一类间断点的个数为(  

(A)0 (B)1 (C)2 (D)3  

解应选(C).  

令$g\left(x\right)=\int_{1}^{x}t\;\mid\;\sin{\;t\;}\mid\;\mathrm{d}t$ ，则 $g(1)=0\,,g(-\,1)=0.$ 又$g^{\prime}(x)=x$ I sin $_{x}$ |,故当 $x\in$  $[0,+\infty)$ 时， $g^{\prime}(x)\geqslant0$ ，当 $x\in(-\infty,0)$ 时， $g^{\prime}(x)\leqslant0$ ,于是 $_{g}(x)$ 在 $(-\infty,+\infty)$ 上只有两个零点 $x=\pm1$ ，故 $f(x)$ 共有三个间断点 $x=0,\pm1$  

在 ${x=0}$ 处，  

$$
\operatorname*{lim}_{x\to0^{-}}f(x\,)=\operatorname*{lim}_{x\to0^{-}}{\frac{(x-1)\mid x+1\mid}{\int_{1}^{x}t\mid\sin t\mid\,\mathrm{d}t}}\cdot\operatorname*{lim}_{x\to0^{-}}{\frac{x}{\mathrm{e}^{\frac{1}{x}}}}={\frac{1}{\int_{0}^{1}t\mid\sin t\mid\,\mathrm{d}t^{x\to0^{-}}}}\operatorname*{lim}_{\mathrm{e}^{\frac{1}{x}}},
$$  

其中 $\operatorname*{lim}_{x\to0^{-}}{\frac{x}{\mathrm{e}^{\frac{1}{x}}}}\,{\frac{-{\frac{1}{x}}=t}{t^{\ast+\infty}}}\operatorname*{lim}_{t\to+\infty}{\frac{\mathrm{e}^{t}}{t}}=-\infty$ ，则 $x=0$ 为第二类无穷间断点.  

在 $x=-1$ 处，  

$$
\operatorname*{lim}_{x\to-1}f(x)=\operatorname*{lim}_{x\to-1}{\frac{x^{2}-x}{\mathrm{e}^{{\frac{1}{x}}}}}\cdot\operatorname*{lim}_{x\to-1}{\frac{|\ x+1\ |}{\int_{1}^{x}t\ |\ \sin{t}\ |\ \mathrm{d}t}}=2\mathbf{e}\cdot\operatorname*{lim}_{x\to-1}{\frac{|\ x+1\ |}{\int_{1}^{x}t\ |\ \sin{t}\ |\ \mathrm{d}t}},
$$  

其中  

$$
\operatorname*{lim}_{x\to(-1)^{+}}{\frac{|\mathbf{\mu}_{x}+1\mid}{\displaystyle\int_{1}^{x}t\mid\sin t\mid\mathrm{d}t}}=\operatorname*{lim}_{x\to(-1)^{+}}{\frac{x+1}{\displaystyle\int_{1}^{x}t\mid\sin t\mid\mathrm{d}t}}
$$  

$$
\frac{\frac{\ast\ast}{\ast}\cdot\left\vert\boldsymbol{\zeta}\cdot\boldsymbol{\mathrm{1}}\right\vert\leq\frac{\left\vert\beta\right\vert\left\vert}{\mathrm{1}\mathrm{1m}}}{\mathrm{~\frac~\left.~\vert~\mathrm{1}~\mathrm{m}~}+\mathrm{~\frac~\vert~\mathrm{1}~\mathrm{sin}~}x\mathrm{~\vert~}}=-\frac{1}{\mathrm{sin}\mathrm{~1}},
$$  

同理可得 $\operatorname*{lim}_{\tau\to(-1)^{-}}{\frac{|\mathbf{\nabla}_{x}+1\mid}{\int_{1}^{x}t\mid\sin t\mid\mathsf{d}t}}={\frac{1}{\sin1}}$ 则 $x=-1$ 为第一类跳跃间断点.  

在 $x=1$ 处，  

$$
\operatorname*{lim}_{x\to1}f(x)=\!\operatorname*{lim}_{x\to1}{\frac{x\mid x+1\mid}{\mathrm{e}^{\frac{1}{x}}}}\cdot\operatorname*{lim}_{x\to1}{\frac{x-1}{\int_{1}^{x}t\mid\sin t\mid\,\mathrm{d}t}}={\frac{2}{\mathrm{e}^{\mathrm{\footnotesize\boldmath~\kappa~}\!+1}}}{\int_{1}^{x}t\mid\sin t\mid\,\mathrm{d}t}
$$  
# 阳宁高等数学18讲  

$$
\frac{\frac{\vert\ast\ast\ast\ast\ast\ast\ast\ast\ast\ast\ast\vert\vert}{\vert}}{\mathrm{e}_{\mathrm{~}^{\ast\rightarrow1}}\mathrm{~}x\vert\mathrm{~}\sin{x}\mathrm{~}\vert}=\frac{2}{\mathrm{e}\cdot\sin{1}},
$$  

则 $x=1$ 为第一类可去间断点.  

综上，函数 $f(x)={\frac{(x^{\,2}-x)\mid x+1\mid}{\mathrm{e}^{{\frac{1}{x}}}{\int}_{1}^{x}t\mid\sin t\mid\mathrm{d}t}}$ 的第一类间断点的个数为 2,应选(C).  

【注】事实上,由第 8 讲“一 $\textcircled{4}"$ 的结论,因 $t\mid$ sin t I 为奇函数,故 $g\left(x\right)=\int_{1}^{x}t\mid\sin t\mid$ dt 为偶函数,只需研究 $x\geqslant0$ 时的性态即可,也就是 $g\left(-1\right){=}g\left(1\right)$  $\pmb{g}(\pmb{x})$ 在 $_{x}=0$ 左右两侧单调性相反.  
# 第2讲G数列极限  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b16be00d7018de83a01b4a1f93c8527353c3f97b74268ed51e321aeefeb3c748.jpg)  
# 张宁高等数学18讲  

# 2.使用  

当 $\operatorname*{lim}_{n\to\infty}x\,,$ ，存在时，  

$\textcircled{1}$ （是常数）常记 $\operatorname*{lim}_{n\to\infty}x_{n}=A\,,$ A是个常数.  

$\textcircled{2}$ (唯一性)A唯一.  

$\textcircled{3}$ (有界性) $\{x_{\textit{n}}\}$ 有界,即 $\exists\,M>0$ ,使 $|\ x_{\ n}\ |\leqslant M$  $\circledast$ （保号性）若 $A>0$ ,则 $n\rightarrow\infty$ 时， $x_{n}>0$ ;若 $n\rightarrow\infty$ 时， $x_{n}\geqslant0$ ，则 $A\geqslant0$  

$\textcircled{5}$ （收敛的充要条件）所有子列 $\{x_{n_{k}}\}$ 均收敛于 $A$  

例 2. 1已知 $a_{n}=\sqrt[n]{n}-\frac{(-1)^{n}}{n}(n=1,2,\cdots)$ ,则 $\{a_{n}\}(\mathrm{~\ensuremath~{~\alpha~}~})$  

（A）有最大值，有最小值（B）有最大值，没有最小值（C）没有最大值，有最小值(D）没有最大值，没有最小值  

因 $\operatorname*{lim}_{n\to\infty}=1,\alpha_{1}=2>1,\alpha_{2}=\!\sqrt{2}-\frac{1}{2}\!<\!1.$ 由于 $\operatorname*{lim}_{n\rightarrow\infty}(a_{n}-a_{1})<0$ ，则3 $N_{1}>0$ 当 $n>N_{1}$ 时， $a_{n}<a_{1}$ .由于 $\operatorname*{lim}_{n\to\infty}(a_{n}-a_{2})>0$ ，则 $\exists\,N_{2}>0$ ，当 $n>N_{2}$ 时， $a_{\scriptscriptstyle\!\,n}>a_{\scriptscriptstyle\!\,2}$ .取 $N\!=\!\operatorname*{max}\left\{N_{1},N_{2}\right\}$ 当 $n>N$ 时， $\boldsymbol{a}_{n}$ 不可能是最大、最小值,而前有限项必存在最大、最小值.  

主)(1) 最值是比较出来的.  

(2) 此题用保号性说明了 $n>N$ 后的项没有资格参与比较，故前有限项必有最大、最小值.  

例 2. 2设正项数列 $\{x_{\textit{n}}\}$ 满足  

$$
x_{\,n+1}+{\frac{1}{x_{\,n}}}<2(n=1,2,\cdots)\,,
$$  

证明 $\operatorname*{lim}_{n\to\infty}x$ ，存在，并计算其值.  

【证】由于 $x_{\scriptscriptstyle\!n}>0(n=1,2,\cdots)$ ,且  

$$
\sqrt{\frac{x_{\mathfrak{n}+1}}{x_{\mathfrak{n}}}}\leqslant\frac{1}{2}\biggl(x_{\mathfrak{n}+1}+\frac{1}{x_{\mathfrak{n}}}\biggr)<1(\mathfrak{n}=1,2,\cdots)\,,
$$  

则 $x_{n+1}<x_{n}$ ,即 $\{x_{\textit{n}}\}$ 单调减少有下界,所以由单调有界准则知， $\operatorname*{lim}_{n\to\infty}x_{n}$ 存在，记为 $A$ ，则 $A\geqslant0$ 如果 $A=0$ ，则令 $n\rightarrow\infty$ ，对题设  

$$
x_{\scriptscriptstyle{n+1}}+\frac{1}{x_{\scriptscriptstyle{n}}}<2(n=1,2,\cdots)
$$  

两边取极限得 $+\infty\leqslant2$ ，矛盾，所以 $A>0$  

令$n\rightarrow\infty$ 对$(\texttt{\textbf{\times}})$ 式取极限得  

$$
\frac{1}{2}\biggl(A+\frac{1}{A}\biggr)=1\,,
$$  

即 $A=1.$ 所以 $\operatorname*{lim}_{n\to\infty}x_{n}=1$  
1.归结原则  

设$f(x)$ 在$\mathring{U}(x_{\circ},\delta)$ 内有定义,则 $\operatorname*{lim}_{x\to x_{0}}f(x)=A$ 存在 $\Leftrightarrow$ 对任何 $\mathring{U}(x_{\circ},\delta)$ 内以 $\scriptstyle{\mathcal{x}}_{0}$ 为极限 的数列 $\smash{\{x_{n}\}(x_{n}\neq x_{0})}$ ，极限 $\operatorname*{lim}_{n\to\infty}f(x_{n})=A$ 存在。  

常考的是:若 $\operatorname*{lim}_{x\to x_{0}}f(x)=A$ ,则当 $\{x_{\textsf{n}}\}$ 以 $\boldsymbol{\mathcal{x}}_{\flat}$ 为极限,且 $x_{\!\;n}\neq x_{\!\;0}$ 时,有 $\operatorname*{lim}_{n\to\infty}f(x_{n})=A$ 如： $\textcircled{1}$ 当 $x\,\rightarrow\,0$ 时，取 $x_{\scriptscriptstyle n}=\!\frac{1}{n}$ ,即若 $\operatorname*{lim}_{x\to0}f(x)=A$ ，则 $\operatorname*{lim}_{n\to\infty}f\left({\frac{1}{n}}\right)=A$  

$\textcircled{2}$ 当 $x\rightarrow+\infty$ 时，取 $x_{n}=n$ ，即若 $\operatorname*{lim}_{x\to+\infty}f(x)=A$ ，则 $\operatorname*{lim}_{n\to\infty}f(n)=A$  $\textcircled{3}$ 当 $x_{n}\rightarrow a$ ,且 $x_{n}\neq a$ 时，若 $\operatorname*{lim}_{x\to a}f(x)=A$ ,则 $\operatorname*{lim}_{n\to\infty}f(x_{n})=A$ ：  

例 2.3 $\operatorname*{lim}_{n\to\infty}{\sqrt{n}}\,({\sqrt[{n}]{n}}-1)=\!\qquad\qquad\quad\cdot$  

【解】应填 0.  

当 $x\rightarrow+\infty$ 时， $\sqrt[x]{x}-1=\mathrm{e}^{\frac{1}{x}\ln x}-1\sim\frac{1}{x}\ln x$ ，于是  

$$
\operatorname*{lim}_{x\to+\infty}{\sqrt{x}}\,({\sqrt[{x}]{x}}-1)=\operatorname*{lim}_{x\to+\infty}{\sqrt{x}}\,\cdot\,{\frac{1}{x}}\mathrm{ln~}x=\operatorname*{lim}_{x\to+\infty}{\frac{1}{\sqrt{x}}}\mathrm{ln~}x
$$  

$$
{\frac{\,{\widehat{\mathcal{F}}}{\sqrt{x^{\prime}}}\,=\,t\,}{\qquad}}\operatorname*{lim}_{t\to+\infty}\,{\frac{2\ln\,t}{t}}\,{\frac{\,{\frac{{\eta\psi}}{\hbar t}}\,{\rlap/2}\,{\dot{x}}\,{\dot{y}}\,{\ddot{y}}\,{\ddot{y}}\,{\ddot{y}}\,{\ddot{y}}\,{\ddot{y}}\,}{\qquad}}\,2\operatorname*{lim}_{t\to+\infty}\,{\frac{1}{t}}\,=0.
$$  

由归结原则， $\operatorname*{lim}_{n\to\infty}{\sqrt{n}}\,({\sqrt[{n}]{n}}-1)=0$  

上述常考的② $^{2,}$ 直接计算法  

例 2 . 4已知 $\frac{a_{n}^{\prime}(x)}{\cos{x}}=\sum_{k=1}^{n}(k\,+\,1)\sin^{k}{x}\;,x\;\in\;\left[0,\frac{\pi}{2}\right),a_{n}(0)\,=0\,,$ 则 $\operatorname*{lim}_{n\rightarrow\infty}(1)\;=\;$  

应填 $\frac{\sin^{2}1}{1-\sin1}$  

由于 $a\textsubscript{n}^{\prime}(x)=\cos\,x\,\cdot\,\sum_{k\,=\,1}^{n}\,(k+1)\sin^{k}x$ $$
\begin{array}{r l}&{\mathbb{H}\mathcal{T}\;\alpha_{n}(x\;)=\cos x\;\times\;\underset{k\;=1}{\overset{.}{\sum}}(k+1)\sin^{\ast}x\;,\mathrm{~}\mathrm{f}\mathrm{}\mathrm{}\mathrm{}\varnothing}\\ &{\quad\quad\alpha_{n}(1)-\alpha_{n}(0)=\biggr\lceil\!\!1_{0}^{\;1}\alpha_{n}^{\prime}(x\;)\!\!\phantom{\frac{1}{\sum}}\!\!\!\!\phantom{}\biggr\rceil x=\biggr\lceil\!\!\frac{1}{0}[2\sin x+3\sin^{2}x+\cdots+(n+1)\sin^{n}x\;\]\!\!\phantom{\frac{1}{\sum}}\!\!\!\right\rfloor\!\!\;(\sin x+\cdots+\sin^{n-1}x)}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=(\sin^{2}x+\sin^{3}x+\cdots+\sin^{n+1}x)\left\vert\!\!\!\right\rceil_{0}^{\;1}=\sin^{2}\!1+\sin^{3}\!1+\cdots+\sin^{n+1}\!\!\!\!\phantom{\frac{1}{\sum}}}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=\sin^{2}1(1+\sin1+\cdots+\sin^{n-1}1)=\sin^{2}1\cdot\frac{1-\sin^{n}1}{1-\sin1}.}\end{array}
$$  
由 $0<\sin1<1,\!a_{n}(1)=\!\frac{\sin^{2}1}{1-\sin1}$  $(1-\sin^{\circ}1)$ ,两边取极限，得 $\operatorname*{lim}_{n\rightarrow\infty}(1)={\frac{\sin^{2}1}{1-\sin1}}$  

3.定义法（“先斩后奏"）  

构造 $\mid x_{\textit{n}}-a$ ，证 $\mid x_{n}-a\mid\to0(n\to\infty){\Rightarrow}\operatorname*{lim}_{n\to\infty}x_{n}=a.$  

例2. 5 设$f(x)$ 满足  

$\begin{array}{r}{\mathbb{O}a\leqslant f(x)\leqslant b\,,x\in\,[a\,,b];}\end{array}$   
 $\textcircled{2}$ 对任给的 $x\,,y\in[a\,,b]$ 有 $\mid f(x\,)-f(y\,)\mid\leqslant{\frac{1}{2}}\mid x-y\mid.$ 又$\{x_{\textit{n}}\}$ 满足 $a\leqslant x_{1}\leqslant b\,,x_{n+1}={\frac{1}{2}}\big[x_{n}+f(x_{n})\big].$   
（1)证明 $f(x)=x$ 在 $[a,b]$ 上有唯一解 $c$ ；  
(2) 证明 $\operatorname*{lim}_{n\to\infty}x_{n}=c$  

【证]（1）先证 $f(x)$ 的连续性. $\forall\,x\,,x_{\scriptscriptstyle0}\in[a\,,\!b]$ 有 $0\ll\mid f(x\,)-f(x\,_{0}\,)\mid\,\leqslant\frac{1}{2}\mid x-x\,_{0}\mid$ 又  

$$
\operatorname*{lim}_{x\to x_{0}}\,{\frac{1}{2}}\mid x-x_{0}\mid=0\,,\qquad\qquad\operatorname*{lim}_{x\to x_{0}}\mid f(x)\mid=0
$$  

故由夹逼准则知 $\operatorname*{lim}_{x\to x_{0}}\mid f(x)-f(x_{0})\mid=0$ ,即 $\operatorname*{lim}_{x\to x_{0}}f(x)=f(x_{0})$ ,即 $f(x)$ 在$[a,b]$ 上连续. 再证 $c$ 的存在性.令 $F(x)=\ f(x)-x\,,x\in[a\,,b]$ ，则 $F(a)=f(a)-a\geqslant0\,,F(b)=$ $f(b)-b\leqslant0$  

当 $F(a)=0$ 时，可取 $c=a$ ；  
当 $F(b)=0$ 时，可取 $c=b$ ；  

当 $F(a)F(b)\neq0$ 时，即 $F(a)F(b)<0$ ，由零点定理知，存在 $c\in(a,b)$ ，使得 $F(c)=0$ 最后证 $c$ 的唯一性.若 $c$ 不唯一，设 $d\in[a,b]$ ，且 $d\neq c$ ，使得 $F(d)=0$ ，则由题设有  

$$
\mid f(c)-f(d)\mid\leqslant\frac{1}{2}\mid c-d\mid,
$$  

但 $f(c)\mathop{=}c\,,f(d)\mathop{=}d$ ，即 $|\ f(c)-f(d)\ |=\mid c-d$ 1，矛盾，于是 $c$ 唯一.  

(2)  

从而  

$$
{\begin{array}{c}{{\displaystyle x_{*1}-c={\frac{1}{2}}\left[x_{*}+f(x_{*})\right]-{\frac{1}{2}}\left[c+f(c)\right]}}\\ {{\displaystyle={\frac{1}{2}}(x_{*}-c)+{\frac{1}{2}}[f(x_{*})-f(c)],}}\\ {{\left|\ {\boldsymbol{x}}_{n+1}-c\ |\leqslant{\frac{1}{2}}\mid x_{n}-c\ |+{\frac{1}{2}}\mid f(x_{*})-f(c)\mid}}\\ {{\leqslant{\frac{1}{2}}\mid x_{n}-c\mid+{\frac{1}{2}}\cdot{\frac{1}{2}}\mid x_{n}-c\mid}}\\ {{\displaystyle={\frac{3}{4}}\mid x_{n}-c\mid,}}\end{array}}
$$  
$0\leqslant\mid x_{n+1}-c\mid\leqslant{\frac{3}{4}}\mid x_{n}-c\mid\leqslant\left({\frac{3}{4}}\right)^{2}\mid x_{n-1}-c\mid\leqslant\cdots\leqslant\left({\frac{3}{4}}\right)^{n}\mid x_{1}-c\mid.$ 而 $\forall\,x_{1}\in[a,b]$ ,都有 $\operatorname*{lim}_{n\to\infty}\!\left({\frac{3}{4}}\right)^{n}\mid x_{1}-c\mid\!=\!0$ ,故由夹逼准则,有 $\operatorname*{lim}_{n\to\infty}x_{n}=c$ ：  

# 4.单调有界准则  

若 $\{x_{\textit{n}}\}$ 单调增加(减少）且有上界(下界),则 $\operatorname*{lim}_{n\to\infty}x_{n}=a$ （存在）。  

# (1)证什么.  

$\textcircled{1}$ 单调是证： $x_{n+1}$ 与 $_{x}$ ，的大小关系. $\textcircled{2}$ 有界是证：3 $\mid M>0$ ，使得 $|\ x_{\ n}\ |\leqslant M$  

(2)怎么证.  

主要有两种证法.  

$\textcircled{1}$ 用已知不等式.   
a. $\forall\,x\geqslant0\,,\sin\,x\leqslant x$ ，如考 $x_{\,n+1}=\sin\,x_{\,n}\leqslant x_{\,n}\,,\{x_{\,n}\}$ 单调减少;  
b. $\forall\,{x}$ $'x\ ,\mathbf{e}^{x}\geq x+1$ ,如考 $x_{\,n+1}={\mathrm{e}}^{\,x_{\,n}}-1\geqslant x_{\,n}\,,\{x_{\,n}\}$ 单调增加;   
c. $\forall\,x>0\,,x-1\geqslant\ln\,x$ ，如考 $x_{\,n+1}=\ln\,x_{\,n}+1\leqslant x_{\,n}\,,\{x_{\,n}\}$ 单调减少；  
d.a, $b>0\,,\sqrt{a b}\leqslant\frac{a+b}{2}$ ，如考 $x_{\,n+1}=\sqrt{x_{\,n}\left(3-x_{\,n}\right)}\leqslant\frac{x_{\,n}+3-x_{\,n}}{2}\,{=}\,\frac{3}{2}\,,\{x_{\,n}\}$ 有上界.  
$\textcircled{2}$ 题设给出条件来推证.  

例 2. 6 设数列 $\{x_{\textit{n}}\}$ 满足 $0<x_{n}<\frac{\pi}{2}$ ,cos $x_{\mathbf{\alpha}_{n+1}}-x_{\mathbf{\alpha}_{n+1}}=\cos\mathbf{\alpha}_{x{\'},n}=1,2,\cdots.$  

(1)证明 $\operatorname*{lim}_{n\to\infty}x$ 存在并求其值；(2) 计算 $\operatorname*{lim}_{n\to\infty}{\frac{x_{\mathbf{\mu}_{n}+1}}{x_{\mathbf{\mu}_{n}}^{2}}}$  

(1)[证]cos xn+1 —— cos $x_{\!\;n}=x_{\!\;n+1}>0$ ,且 $0<x_{\L_{n}}<\frac{\pi}{2}$ ,故有 $0<x_{n+1}<x_{n}$ ,于是 $\{x_{\textit{n}}\}$ 单调减少且有下界， $\operatorname*{lim}_{n\to\infty}x_{n}{\frac{{\#}\#}{\mathrm{i}\mathrm{E}}}a$ .在cos $x_{\ n+1}-x_{\ n+1}=\cos x$ ，两边取极限,有cos $a-a=\cos\,\alpha$ 得 $\alpha=0$ .于是 $\operatorname*{lim}_{n\to\infty}x_{n}=0.$  

$$
\operatorname*{lim}_{n\to\infty}\frac{x_{n+1}}{x_{n}^{2}}=\!\operatorname*{lim}_{n\to\infty}\frac{1-\cos{\,x_{n}\,}}{x_{n}^{2}}\cdot\frac{x_{n+1}}{1-\cos{\,x_{n}\,}}\!=\!\frac{1}{2}\operatorname*{lim}_{n\to\infty}\frac{x_{n+1}}{1-\cos{\,x_{n+1}\,}+x_{n+1}}\!=\!\frac{1}{2}.
$$  

【注】这种命题将函数的具体性质与抽象理论相结合,较好地考查了考生的数学水平,还可  
进一步发挥：  
(1)将单通项 $_{x}$ ，改成双通项 $^{a}$ ”与 $\boldsymbol{b}_{n}$   
设 $0<a_{n}<\frac{\pi}{2},0<b_{n}<\frac{\pi}{2}$ ,cos $a_{n}-a_{n}=\cos b_{n}$ ,且 $\operatorname*{lim}_{n\to\infty}b_{n}=0$ ,则由 cos $a_{n}-\cos b_{n}=a_{n}>$   
0，知 $0<a_{n}<b_{n}$ ，由夹逼准则，得 $\operatorname*{lim}_{n\to\infty}a_{n}=0$ ，且  
$$
\operatorname*{lim}_{n\to\infty}{\frac{a_{n}}{b_{n}^{2}}}=\operatorname*{lim}_{n\to\infty}{\frac{1-\cos b_{n}}{b_{n}^{2}}}\cdot{\frac{a_{n}}{1-\cos b_{n}}}={\frac{1}{2\operatorname*{lim}}}{\frac{a_{n}}{1-\cos a_{n}+a_{n}}}={\frac{1}{2}}.
$$  

与上述例题如出一辙。  

(2）将函数cos $_{x}$ 改成 $\mathbf{e}^{x}$  

设$x_{n}>0,\mathrm{e}^{x_{n}}-x_{n}=\mathrm{e}^{x_{n+1}}$ (或更具迷惑性地写成 $\ln(\mathrm{e}^{x_{n}}-x_{n})=x_{n+1})$ ，则由 $\mathsf{e}^{x_{n}}-\mathsf{e}^{x_{n+1}}=$  $x_{n}>0$ ，知 $x_{n}>x_{n+1}>0,\operatorname*{lim}_{n\to\infty}x_{n}{\frac{\#{\#}}{\#{\#}}}a$ ,于是有 $\mathrm{e}^{a}-\mathrm{e}^{a}=a=0$ ，得 $\operatorname*{lim}_{n\to\infty}x_{n}=0$ ,且  

$$
\operatorname*{lim}_{n\to\infty}\frac{x_{n}^{\,2}}{x_{n+1}}=\!\operatorname*{lim}_{n\to\infty}\frac{x_{n}^{\,2}}{\ln(\mathrm{e}^{x_{n}}-x_{n})}\,{\frac{-\operatorname*{lim}}{\mathrm{\mu}_{n\to\infty}^{x_{n}}-x_{n}-1}}=\!\operatorname*{lim}_{n\to\infty}\frac{x_{n}^{\,2}}{\frac{1}{2}x_{n}^{\,2}}\!=\!2.
$$  

例 2. 7设 $x_{\mathit{1}}=1\,,x_{\mathit{n}}=\!\int_{0}^{1}\operatorname*{min}\{x\,,x_{\mathit{n-1}}\}\,\mathrm{d}x\,,n=2\,,3\,,\cdots$ ，证明 $\operatorname*{lim}_{n\to\infty}x$ ，存在,并求其值.$\stackrel{\triangledown}{\mathbb{E}}|\alpha_{2}\!=\!\!\int_{0}^{1}\!\operatorname*{min}\{x\,,x_{1}\}\,\mathrm{d}x=\!\!\int_{0}^{1}\!\operatorname*{min}\{x\,,1\}\,\mathrm{d}x=\!\!\int_{0}^{1}\!x\,\mathrm{d}x=\!\frac{1}{2}\,\mathrm{d}x\,.$ 故$0<x_{2}<1$  

$$
\begin{array}{l}{{\displaystyle{\underline{{x_{3}}}}=\!\int_{0}^{1}\!\operatorname*{min}\{x\,,x_{2}\}\,{\mathrm{d}}x=\!\int_{0}^{\frac{1}{2}}\operatorname*{min}\!\left\{x\,,\frac{1}{2}\right\}\,{\mathrm{d}}x+\!\int_{\frac{1}{2}}^{1}\operatorname*{min}\!\left\{x\,,\frac{1}{2}\right\}\,{\mathrm{d}}x}\\ {{\displaystyle\qquad=\!\int_{0}^{\frac{1}{2}}x\,{\mathrm{d}}x+\!\int_{\frac{1}{2}}^{1}\frac{1}{2}{\mathrm{d}}x=\!\frac{3}{8}\,,}}\end{array}
$$  

故$0<x_{3}<1.$ 设$x_{\mathit{n-1}}\in\mathit{(0,1)}$ ，则  

$$
\begin{array}{r l}&{\frac{\widehat{x}_{n}}{n}\!=\!\!\int_{0}^{1}\!\operatorname*{min}\{x\;,x_{n-1}\}\,\mathrm{d}x}\\ &{\qquad=\!\!\int_{0}^{x_{n-1}}\!\operatorname*{min}\{x\;,x_{n-1}\}\,\mathrm{d}x+\!\int_{x_{n-1}}^{1}\!\operatorname*{min}\{x\;,x_{n-1}\}\,\mathrm{d}x}\\ &{\qquad=\!\!\int_{0}^{x_{n-1}}\!\!x\,\mathrm{d}x+\!\int_{x_{n-1}}^{1}\!\!x_{n-1}\mathrm{d}x}\\ &{\qquad=\!\!\frac{x_{n-1}^{2}}{2}+\!x_{n-1}(1-x_{n-1})=x_{n-1}-\frac{x_{n-1}^{2}}{2},}\end{array}
$$  

所以 $0<x_{\,n}<1,\{x_{\,n}\}$ 有界.且 $x_{n}=x_{n-1}-{\frac{x_{n-1}^{2}}{2}}<x_{n-1}\,,\,\{x_{n}\}$ 单调减少,由单调有界准则知，  
# 第2讲数列极限  

# 其极限存在.  

记$\operatorname*{lim}_{n\to\infty}x_{n}=A$ ，则有 $A=A-{\frac{A^{2}}{2}}$ ,解得 $A=0$ ，即 $\operatorname*{lim}_{n\to\infty}x_{n}=0$  

】本题计算 $\scriptstyle x\,_{3}$ 是为了使读者容易理解，事实上，由第一数学归纳法， $x_{3}$ 的计算可以不写.  

列 2. 8（1）证明方程 $x=2\ln(1+x\,)$ 在 $(0,+\infty)$ 内有唯一实根 $\boldsymbol{\xi}$ ：  

(2）对于(1)中的 $\boldsymbol{\xi}$ ，任取 $x_{1}>\xi$ ，定义 $x_{\!\;n+1}\!=\!2\mathrm{ln}(1+x_{\!\;n})$  $n=1,2$ ,，证明 $\operatorname*{lim}_{n\to\infty}x$ 存在，并求其值.  

$$
F^{\prime}(x)\,{=}\,1-\frac{2}{1+x}\,{=}\frac{x-1}{1+x},
$$  

令 $F^{\prime}(x)\,{=}\,0$ ，得 $x=1$ 是唯一驻点，且当 $0<x<1$ 时， $F^{\prime}(x)<0$ ；当 $x>1$ 时， $F^{\prime}(x)>0$ 。  

又  

$$
F(0)=0\,,F(1)=1-2\mathrm{ln}\ 2<0\,,
$$  

$$
\operatorname*{lim}_{x\to+\infty}[x-2\ln(1+x)]\!=\!+\infty\!>0\,,
$$  

如图2-1所示，所以 $F(x)$ 在（0，1）内无零点，在 $(1,+\infty)$ 内有唯一零点 $\boldsymbol{\xi}$ ，故原方程在 $(0,+\infty)$ 内有唯一实根 $\boldsymbol{\xi}$  

(2)由 $x_{1}>\xi,F(x_{1})>F(\xi)=0$ ,即  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/d980fe35306728b57659821460c8b3a6db8c168b1dcc2ba36826b2021e79d3bd.jpg)  
图2-1  

$$
x_{1}>2\mathrm{ln}(1+x_{1})\,{=}\,x_{2}>2\mathrm{ln}(1+\xi)=\xi,
$$  

即$x_{1}>x_{2}>\xi$  

假设 $x_{n-1}>x_{n}>\xi$ 成立，则有  

$$
x_{n}>2\mathrm{ln}(1+x_{n})=x_{n+1}>2\mathrm{ln}(1+\xi)=\pmb\xi\,,
$$  

即$x_{n}>x_{n+1}>\xi.$ 于是 $\{x_{n}\}$ 单调减少且有下界 $\boldsymbol{\xi}$  

故 $\operatorname*{lim}_{n\to\infty}x_{n}$ 存在，记为 $^{\,a}$ ，在 $x_{n+1}=2\mathrm{ln}(1+x_{n})$ 两边取极限，有 $a=2\ln(1+a)$ ，由(1)可知 $\alpha=\mathfrak{\xi}$  

读者可画出如图2-2所示的情形，加深理解。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/1279aacbddd5017d950cf1a16bb83f49dadab90c728f168f528fb9ed6ca9fef6.jpg)  
图2-2  
例 2. 9设 $f_{n}\left(x\right)=\cos{x}+\cos^{2}{x}+\cdots+\cos^{n}{x}\,(n=1,2,\cdots).$  

（1）证明：对于每个 $_n$ ，方程 $\widehat{f_{n}(x)}=\!1$ 在 $\left[0,{\frac{\pi}{3}}\right)$ 内有且仅有一个实根 $\boldsymbol{\mathscr{x}}_{n}$  

（2）证明 $\operatorname*{lim}_{n\to\infty}x_{n}$ 存在,并求其值.方程列 $\smash{\{f_{n}(x)=1\}}$   
【证]（1）设函数 $F_{n}\left(x\right)=f_{n}\left(x\right)-1(n=1,2,\cdots)$ ，则 $f_{1}(x)=1$ ，其根为x； $F_{\!\;\!n}\left(0\right)=n-1\geq0\,,$  $f_{2}(x)=1$ ，其根为x； $F_{n}\left(\frac{\pi}{3}\right)\!=\!\frac{\cos\frac{\pi}{3}\Big(1-\cos^{n}\frac{\pi}{3}\Big)}{1-\cos\frac{\pi}{3}}-1\!<\!\frac{\cos\frac{\pi}{3}}{1-\cos\frac{\pi}{3}}\!-1\!=\!0.$ J(x)=1，其根为x;这些根成为数列（x}  

所以由零点定理知， $\boldsymbol{F}_{n}\left(\boldsymbol{x}\right)$ 在 $\left[0,{\frac{\pi}{3}}\right)$ 内至少有一个零点.又因为  

$$
F_{\mathfrak{n}}^{\prime}\left(x\,\right)=-\sin\,x\,(1+2\cos\,x\,+\cdots+n\cos^{\mathfrak{n}-1}x\,)<0\,,x\,\in\,\left(0,\frac{\pi}{3}\right),
$$  

所以 $\boldsymbol{F}_{\!\;\!n}\left(\boldsymbol{x}\right)$ 在 $\left[0,{\frac{\pi}{3}}\right)$ 内严格单调减少,从而 $\boldsymbol{F}_{\!\;\!n}\left(\boldsymbol{x}\right)$ 在 $\left[0,{\frac{\pi}{3}}\right)$ 内有且仅有一个零点,即对于每个 $_n$ 方程 $\scriptstyle f_{\scriptscriptstyle n}(x)\;=\;1$ 在時 $\left[0,{\frac{\pi}{3}}\right)$ 内有且仅有一个实根 $\boldsymbol{x}_{\,\,n}$ ：  

(2）由(1)可知，显然 $x_{1}=0\,,x_{2}\in\big(0\,,\frac{\pi}{3}\big)$ 由于 $\boldsymbol{x}_{\,\,n}$ 是方程 $f_{\scriptscriptstyle n}\left(x\right)\!=\!1$ 在 $\left[0,{\frac{\pi}{3}}\right)$ 内的实根，则 $\smash{\boldsymbol{F}_{\!p}\left(\boldsymbol{x}_{\!p}\right)=0}$ ,且当 $n\geqslant2$ 时，有  

$$
\begin{array}{c}{{F_{n}\left(x_{\mathfrak{n}-1}\right)=\cos\,x_{\,n-1}+\cos^{2}x_{\,n-1}+\cdots+\cos^{n}x_{\,n-1}-1}}\\ {{=\cos^{n}x_{\,n-1}+\!\displaystyle(\!\!\!F_{\,n-1}(x_{\,n-1})\!\!\!\right)\!=\cos^{n}x_{\,n-1}>0.}}\\ {{=0}}\end{array}
$$  

由(1)可知 $\boldsymbol{F}_{\!\;\!n}\left(\boldsymbol{x}\right)$ 在 $\left[0,{\frac{\pi}{3}}\right)$ 内严格单调减少,从而 $x_{\!\;n-1}<x_{\!\;n}$ ,即 $\{x_{\textit{n}}\}$ 是单调增加数列,又由于 $0\leqslant x_{n}<\frac{\pi}{3}$ 所以 $\{x_{\textit{n}}\}$ 收敛.记 $\operatorname*{lim}_{n\to\infty}x_{n}=a$ g==m<g<1  

注意到 $0<x_{2}<x_{n}<\frac{\pi}{3}(n>2)$ ，所以 $0<\cos\,x\,_{n}<(\cos\,x\,_{2})<1$ ,于是由夹逼准则,有limcos" $x_{n}=0$ ，且 $a\in\left(0,\frac{\pi}{3}\right]$ $0<x_{2}<x_{n}<\frac{\pi}{3}\Rightarrow0<x_{2}\leqslant\operatorname*{lim}_{n\to\infty}x_{n}\leqslant\frac{\pi}{3}\Rightarrow0<a\leqslant\frac{\pi}{3}$  

$$
1=f_{n}\left(x_{\,\,n}\right)=\cos\,x_{\,\,n}+\cos^{2}x_{\,\,n}+\cdots+\cos^{n}x_{\,\,n}={\frac{\cos\,x_{\,\,n}\,(1-\cos^{n}x_{\,\,n}\,)}{1-\cos\,x_{\,\,n}}},
$$  

令$n\rightarrow\infty$ ，得  

$$
1={\frac{\cos\,a}{1-\cos\,a}}\,,
$$  

解得cos $a={\frac{1}{2}}$ 因此 $a=\frac{\pi}{3}$ ，即  

$$
\operatorname*{lim}_{n\to\infty}x_{n}={\frac{\pi}{3}}.
$$  
【注】当 $0<q<1$ 且 $\boldsymbol{q}$ 为常数时，必有 $\operatorname*{lim}_{n\to\infty}\!q^{n}=0$ 若 $\pmb q$ 不是常数,即使 $0<q<1$ ,也未必有 $\operatorname*{lim}_{n\to\infty}\!q^{n}=0$ 如 $q=1-{\frac{1}{n}}$ 则 $\operatorname*{lim}_{n\to\infty}\bigl(1-\frac{1}{n}\bigr)^{n}=\mathrm{e}^{\mathrm{}^{\mathrm{i}\underset{n\to\infty}{n\cdot n}(-\frac{1}{n})}}=\mathrm{e}^{-1}\neq0.$  

（1）证明方程 tan $x=x$ 在 $\left(n\,\pi\,,n\,\pi+{\frac{\pi}{2}}\right)$ 内存在实根 $\mathfrak{s}_{n}\,,n=1,2,3,\cdots$  

（2）求极限 $\operatorname*{lim}_{n\rightarrow\infty}(\xi_{n+1}-\xi_{n})$  

（1)[证】令 $f(x\,)=\,\tan\,x-x\,,x\,\in\,\left[n\,\pi\,,n\,\pi+{\frac{\pi}{2}}\right)$  

$n=1,2,3,\cdots,y=\tan x$ 的图像如图2-3所示.因  

$$
f(n\,\uppi)=\tan\,n\,\uppi-n\,\uppi=-\,n\,\uppi<0\,,
$$  

$$
\operatorname*{lim}_{x\to\left(n\pi+{\frac{\pi}{2}}\right)^{-}}(\tan{x}-x)=+\infty>0\,.
$$  

故存在 $x_{n}\in\displaystyle\left(n\,\pi\,,n\,\pi+\frac{\pi}{2}\right)$ ，使得 $f(x_{n})>0.$ ，由零点定理知，存在  

$$
\mathfrak{f}_{n}\,\in\,(n\,\pi,x_{n}\,)\,\subset\,\Big(n\,\pi\,,n\,\pi+\frac{\pi}{2}\Big)\ ,
$$  

使得 $f(\xi_{n})=0$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/664a61549bf049a633e3aa957371ce59202507d4da9e727442ce04af7f6f7587.jpg)  
图2-3  

(2)解】当 $n\rightarrow\infty$ 时，由于 $\xi_{n}\,\in\,\left(n\,\pi\,,n\,\pi+\frac{\pi}{2}\right)$ 则lims,。$+\infty$ 且$\frac{\pi}{2}<\xi_{n+1}-\xi_{n}<\frac{3}{2}\pi$ 有界，又 由a<y<b,c<x<d=  

$$
\begin{array}{r l r}&{}&{\tan(\xi_{n+1}-\xi_{n})=\!\frac{\tan\,\xi_{n+1}-\tan\,\xi_{n}}{1+\tan\,\xi_{n+1}\,\cdot\,\tan\,\xi_{n}}}\\ &{}&{\frac{\#(1)}{1+\xi_{n+1}\,\cdot\,\xi_{n}},\ \ \ }\end{array}
$$  

故$\operatorname*{lim}_{n\rightarrow\infty}\(\xi_{n+1}-\xi_{n})\prod_{n\rightarrow\infty}\frac{\xi_{n+1}-\xi_{n}}{1+\xi_{n+1}\xi_{n}}=0$ ，从而 $\operatorname*{lim}_{n\rightarrow\infty}(\xi_{n+1}-\xi_{n})=\uppi.$  

若 $\mathbb{D}y_{n}\leqslant x_{n}\leqslant z_{n}\,;\mathbb{\varnothing}\operatorname*{lim}_{n\to\infty}y_{n}=\alpha\,,\operatorname*{lim}_{n\to\infty}z_{n}=\alpha$ ,则 $\operatorname*{lim}_{n\to\infty}x_{n}=a$ .这里 $\textcircled{1}$ 中无须验证等号； $\textcircled{2}$ 中 $^{\,a}$ 可为 $0,c\left(c\neq0\right)$ 或 $_\infty$  

(1）证什么.  
 $\textcircled{1}$ 对 $x_{n}$ 放缩： $y_{n}\leqslant x_{n}\leqslant z_{n}$   
$\textcircled{2}$ 取极限.   
(2)怎么证.   
主要有两种证法：  
 $\textcircled{1}$ 用基本放缩方法.  
$\iota\,\bullet\,u_{\mathrm{\scriptsize~min}}\leqslant u_{1}+u_{2}+\cdots+u_{n}\leqslant n\,\bullet\,u_{\mathrm{\scriptsize~max}}\,,$   
当 $u_{i}\geqslant0$ 时， $1\,\bullet\,u_{\textup{m a x}}\leqslant u_{1}+u_{2}+\cdots+u_{n}\leqslant n\,\bullet\,u_{\textup{m a x}}.$  
# 比宇高等数学18讲  

$\textcircled{2}$ 题设给出条件来推证.  

例 2. 11(1)当 $0<x<\frac{\pi}{2}$ 时，证明 $\sin\,x>{\frac{2}{\pi}}x$  

（2）设数列 $\{x_{n}\},\{y_{n}\}$ 满足 $x_{n+1}=\sin\,x_{n}\,,y_{n+1}=y_{n}^{2}\,,n=1,2,3,\cdots,x_{1}=y_{1}={\frac{1}{2}}$ 当 $n\rightarrow\infty$ 时，证明 $y_{n}$ 是比 $_{x}$ ，高阶的无穷小量.  

【证】（1）设 $f(x\,)=\,\sin\,x-{\frac{2x}{\pi}},x\,\in\,\left(0,{\frac{\pi}{2}}\right)$ ，则  

$$
f^{\prime}(x\,)=\,\cos\,x-\frac{2}{\pi},f^{\prime\prime}(x\,)=\,-\sin\,x<0\,,
$$  

所以曲线 $f(x)=\sin x-{\frac{2x}{\pi}}$ 長在 $\left(0,{\frac{\pi}{2}}\right)$ 内是凸的，又 $f(0)=f\Big(\frac{\pi}{2}\Big)=0$ 所以 $f(x)=\sin x-\frac{2x}{\pi}>0$ 即  

$$
\sin\ x>{\frac{2x}{\pi}}.
$$  

（2）首先， $x_{\scriptscriptstyle{n+1}}=\sin\,x_{\scriptscriptstyle{n}}<x_{\scriptscriptstyle{n}}\,,x_{\scriptscriptstyle{n}}>0$ ,由单调有界准则,知 $\operatorname*{lim}_{n\to\infty}\frac{\#\#}{\mathrm{i}\overline{{\mathbb{C}}}^{\#}}a$ 于是 $a=\sin{a}$ ，得$a=0,$  

$y_{n+1}=y_{n}^{2}<y_{n}\,,0<y_{n}\leqslant{\frac{1}{2}}<1$ 由单调有界准则，知 $\operatorname*{lim}_{n\to\infty}y_{n}{\frac{{\frac{{\slash}{\!\!\!+}}{\!\!+}}{\!\!\!-\!\!\!-\!\!\!+}}{{\dot{\imath}}{\overline{{\!{\nabla}}}}{\mathcal{H}}}}b$ 于是 $b={b^{2}}$ 得 $b=0$ （因保号性，舍去 $b=1$  

又由(1),当 $0<x<\frac{\pi}{2}$ 时,有 sin $x>\frac{2}{\pi}x$ ,且 $y_{n+1}=y_{n}^{2}=y_{n}\cdot y_{n}\leqslant\frac{1}{2}y_{n}$ ，于是  

$$
)<\frac{y_{n+1}}{x_{n+1}}=\frac{y_{n}^{2}}{\sin x_{n}}<\frac{\frac{1}{2}y_{n}}{\frac{2x_{n}}{\pi}}=\frac{\pi}{4}\cdot\frac{y_{n}}{x_{n}}<\left(\frac{\pi}{4}\right)^{2}\cdot\frac{y_{n-1}}{x_{n-1}}<\cdots<\left(\frac{\pi}{4}\right)^{n}\cdot\frac{y_{1}}{x_{1}}=\left(\frac{\pi}{4}\right)^{n},
$$  

又$\operatorname*{lim}_{n\rightarrow\infty}\left({\frac{\pi}{4}}\right)^{n}=0$ ,由夹逼准则,有 $\operatorname*{lim}_{n\to\cdots}{\frac{y_{n+1}}{x_{n+1}}}=0$ ,故 $y_{n}$ 是比 $_{x}$ ，高阶的无穷小量.  

考生应熟悉an+1<ka<k²an-)<.<ka 这种连续放缩方法 (压缩映射)  

6.综合题总结  

数列极限的存在性与计算问题可与很多经典知识综合，故常作为压轴题出现在试卷中，考生应多作总结，看看这些综合的点在哪里，打通它们，建立知识结构，便有思路了，比如可作如下总结  

$\textcircled{1}$ 用导数综合.  

$\textcircled{2}$ 用积分综合.  
 $\textcircled{3}$ 用中值定理综合.  
$\circled{4}$ 用方程（列）综合.   
$\circled{5}$ 用区间（列）综合.   
 $\circled{6}$ 用极限综合.  