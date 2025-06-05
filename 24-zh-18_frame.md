

# 第3讲一元函数微分学的概念  

# 知识结构  

分段函数（或含绝对值函数）在分段点  

导数定义（导数在一点的问题）  

特指点 $\boldsymbol{\mathscr{x}}_{0}$ 抽象函数在一点泛指点 $_{x}$  

太复杂的函数 $\begin{array}{l}{f=f_{1}+f_{2}}\\ {f=f_{1}\cdot f_{2}\cdot\dots\cdot f_{n}}\end{array}$ 四则运算中的特殊点求导公式无定义的点  

定义微分可微的充要条件一阶微分形式的不变性  

一导数定义（导数在一点的问题）  

$$
f^{\prime}(x_{0})=\operatorname*{lim}_{\Delta x\to0}{\frac{f(x_{0}+\Delta x)-f(x_{0})}{\Delta x}}=\operatorname*{lim}_{x\to x_{0}}{\frac{f(x_{\l})-f(x_{\l_{0}})}{x-x_{\l_{0}}}}.
$$  

[注 $|(1)f^{\prime}(x_{0})={\frac{\mathbf{d}f}{\mathbf{d}x}}\,{\bigg|}_{x=x_{0}}$ 是指 $f$ 对$_{x}$ 在$\boldsymbol{x}_{\,0}$ 处的（瞬时）变化率.  

(2)左导数 $f_{-}^{\prime}(x_{0})=\operatorname*{lim}_{\Delta x\to0^{-}}\frac{f(x_{0}+\Delta x)-f(x_{0})}{\Delta x},$ 右导数 $f_{+}^{\prime}(x_{0})=\operatorname*{lim}_{\Delta x\to0^{+}}{\frac{f(x_{0}+\Delta x)-f(x_{0})}{\Delta x}}.$  $f^{\prime}(x_{\circ})$ 存在 $\Longleftrightarrow f_{-}^{\prime}(x_{0})=f_{+}^{\prime}(x_{0})=A\,$ (常数).(3)高阶导数 $f^{(n)}(x_{0})=\operatorname*{lim}_{x\to x_{0}}{\frac{f^{(n-1)}(x)-f^{(n-1)}(x_{0})}{x-x_{0}}}(n\geqslant3).$  

$\textcircled{1}$ 分段函数（或含绝对值函数）在分段点.特指点 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ ，  

$\circledcirc$ 抽象函数在一点泛指点 $_{x}$ 太复杂的函数 $\begin{array}{l}{{\displaystyle\bigl\langle f=f_{1}+f_{2}\,,}}\\ {{\displaystyle\bigl\langle f=f_{1}\cdot f_{2}\cdot\dots\,.}}\end{array}$   
 $\textcircled{3}$ 四则运算中的特殊点求导公式无定义的点.  
# 比亨高等数学18涉  

例 3. 1设函数 $f(x)$ 在区间（一1,1）内有定义，且 $\operatorname*{lim}_{x\to0}f(x)=0$ ，则(  

（A）当 $\operatorname*{lim}_{x\to0}{\frac{f(x)}{\sqrt{\left|x\right|}}}=0$ 时， $f(x)$ 在 $\boldsymbol{x}=0$ 处可导(B)当 $\operatorname*{lim}_{x\rightarrow0}{\frac{f(x)}{x^{2}}}=0$ 时， $f(x)$ 在 $x=0$ 处可导  

(C)当 $f(x)$ 在 $x=0$ 处可导时， $\operatorname*{lim}_{x\to0}{\frac{f(x)}{\sqrt{\ x\ }}}=0$ (D）当 $f(x)$ 在 $x=0$ 处可导时， $\operatorname*{lim}_{x\rightarrow0}{\frac{f(x)}{x^{2}}}=0$  

【解】应选(C).  

当 $f(x)$ 在 $x=0$ 处可导时， $f(x)$ 在 $x=0$ 处连续,f(0)=limf(x)= 0,且 $\operatorname*{lim}_{x\to0}{\frac{f(x)-f(0)}{x}}=$  $\operatorname*{lim}_{x\to0}{\frac{f(x)}{x}}$ 存在,设为 $^a$ ，则有  

$$
\operatorname*{lim}_{x\star\!\;^{0}}\frac{f(x\,)}{\sqrt{\left|\,x\,\right|}}=\!\!\operatorname*{lim}_{x\star\!\;^{0}}\frac{f(x\,)}{x}\cdot\frac{x}{\sqrt{\left|\,x\,\right|}}=\!\!\operatorname*{lim}_{x\star\!\;^{0}}\frac{f(x\,)}{x}\cdot\operatorname*{lim}_{x\star\!\;^{0}}\!\frac{x}{\sqrt{\left|\,x\,\right|}}=\!a\,\star\!\;0=\!0.
$$  

对于（A)，(B)，可取反例 $f(x)={\binom{x^{3}\,,\quad x\neq0\,.}{1\,,\quad x=0.}}$ 对于(D),可取反例 $f(x\,)=x$  

例 3. 2已知函数 $f(x\,)=\!\!\left\{\!\!{\frac{x\,,}{n}},\!\!\begin{array}{l l}{{x\leqslant0\,,}}\\ {{\displaystyle{\frac{1}{n}},}}&{{\displaystyle{\frac{1}{n+1}}<x\leqslant{\frac{1}{n}},n=1,2,\cdots,}}\end{array}\!\!\right.$ 则（）.  

$(\mathbf{\nabla}\mathbf{A})x=0$ 是 $f(x)$ 的第一类间断点 $(\boldsymbol{\mathrm{B}})\boldsymbol{x}=0$ 是 $f(x)$ 的第二类间断点 $(\boldsymbol{\mathrm{C}})f(\boldsymbol{\mathit{x}})$ 在 $x=0$ 处连续但不可导 $(\mathrm{D})f(x)$ 在 $x=0$ 处可导  

【解】应选(D).  

$f_{-}^{\prime}(0)=\operatorname*{lim}_{x\to0^{-}}{\frac{f(x\,)-f(0)}{x-0}}=\operatorname*{lim}_{x\to0^{-}}{\frac{x}{x}}=1$ ,这是容易的.但对于 $f_{+}^{\prime}(0)=\operatorname*{lim}_{x\to0^{+}}{\frac{f(x)-f(0)}{x-0}}$ 这是不易的.由题设，当 ${\frac{1}{n+1}}<x\leqslant{\frac{1}{n}}$ 时， $f(x\,)={\frac{1}{n}}$ 故  

$$
1\leqslant{\frac{f(x)}{x}}<{\frac{n+1}{n}}.
$$  

当 $x\to0^{+}$ 时， $n\rightarrow\infty\,,\operatorname*{lim}_{n\rightarrow\infty}{\frac{n+1}{n}}=1$ ，由夹逼准则知 $\operatorname*{lim}_{x\to0^{+}}{\frac{f(x)}{x}}=1$ ,即 $f_{{\scriptscriptstyle+}}^{\prime}(0)=1$ 综上， $f^{\prime}(0)=f_{-}^{\prime}(0)=f_{+}^{\prime}(0)=1.$ 应选(D).  

例 3. 3设 $f(x)$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处可导，则下列命题错误的是(（A）当 $f(x_{0})>0$ 时， $\mid f(x)\mid$ 在 $\boldsymbol{x}_{\,0}$ 处也可导(B)当 $f(x_{\mathit{0}})<0$ 时， $f(x)\mid$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处也可导(C)当 $f(x_{\circ})=0$ ,且 $f^{\prime}(x_{0})=0$ 时， $\{\;\;f(x\,)\;\}$ 在 $\scriptstyle{\boldsymbol{x}}_{\mathrm{~0~}}$ 处不可导(D)当 $f(x_{\circ})=0$ ，且 $f^{\prime}(x_{0})\neq0$ 时， $f(x)\mid$ 在 $\scriptstyle{\boldsymbol{x}}_{0}$ 处不可导  
【解】应选(C).  

记 $\varphi(x)=\mid f(x)\mid$ ，因为 $f(x)$ 在 $\scriptstyle{\boldsymbol{x}}_{\mathrm{~0~}}$ 处可导，所以 $f(x)$ 在 $\boldsymbol{\mathscr{x}}_{\mathrm{~0~}}$ 处必连续，即  

$$
\operatorname*{lim}_{x\to x_{0}}f(x)=f(x_{0}).
$$  

当 $f(x_{\circ})>0$ 时，根据极限的保号性，当 $x\rightarrow x_{\mathrm{~\,~}}$ 时，有 $f(x)>0$ ，即 $\operatorname*{lim}_{x\to x_{0}}\mid f(x)\mid=$  $\operatorname*{lim}_{x\to x_{0}}f(x)$ ，此时  

$$
=\operatorname*{lim}_{x\rightarrow x_{0}}{\frac{\varphi(x)-\varphi(x_{0})}{x-x_{0}}}=\operatorname*{lim}_{x\rightarrow x_{0}}{\frac{\mid f(x)\mid-\mid f(x_{0})\mid}{x-x_{0}}}=\operatorname*{lim}_{x\rightarrow x_{0}}{\frac{f(x)-f(x_{0})}{x-x_{0}}}=f^{\prime}(x_{0})\,.
$$  

（A）正确.  

当 $f(x_{\circ})<0$ 时，同理可得 $\operatorname*{lim}_{x\to x_{0}}\mid f(x)\mid=-\operatorname*{lim}_{x\to x_{0}}f(x)$ ，此时  

(x。) ${\underset{x\rightarrow x_{0}}{=\operatorname*{lim}}}\,{\frac{\varphi\left(x\right)-\varphi\left(x_{0}\right)}{x-x_{0}}}=\operatorname*{lim}_{x\rightarrow x_{0}}{\frac{\mid f(x)\mid-\mid f(x_{0})\mid}{x-x_{0}}}=\operatorname*{lim}_{x\rightarrow x_{0}}{\frac{-f(x)+f(x_{0})}{x-x_{0}}}=-f$ (x。)，(B)正确.  

当 $f(x_{\circ})=0$ 时，有 $f^{\prime}(x_{0})=\operatorname*{lim}_{x\to x_{0}}{\frac{f(x)}{x-x_{0}}}$ ，此时  

$\varphi_{+}^{\prime}(x_{0})=\operatorname*{lim}_{x\to x_{0}^{+}}{\frac{\varphi(x)-\varphi(x_{0})}{x-x_{0}}}=\operatorname*{lim}_{x\to x_{0}^{+}}{\frac{\mid f(x)\mid}{x-x_{0}}}=\operatorname*{lim}_{x\to x_{0}^{+}}\left|{\frac{f(x)}{x-x_{0}}}\right|=\mid f^{\prime}(x_{0})\mid,$ $\varphi_{-}^{\prime}(x_{0})=\operatorname*{lim}_{x\to x_{0}^{-}}{\frac{\varphi(x)-\varphi(x_{0})}{x-x_{0}}}=\operatorname*{lim}_{x\to x_{0}^{-}}{\frac{\mid f(x)\mid}{x-x_{0}}}=-\operatorname*{lim}_{x\to x_{0}^{-}}\left|{\frac{f(x)}{x-x_{0}}}\right|=-\mid f^{\prime}(x_{0})\mid.$  

若$f^{\prime}(x_{0})=0$ ，则 $\varphi_{+}^{\prime}(x_{\,0})\!=\!\varphi_{-}^{\prime}(x_{\,0})\!=\!0$ ,此时 $\varphi(x)=\mid f(x)\mid$ 在$\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处可导，且导数为0. 若$f^{\prime}(x_{0})\neq0$ ，则 $\varphi_{+}^{\prime}(x_{0})\neq\varphi_{-}^{\prime}(x_{0})$ ,此时 $\varphi(x)=\mid f(x)\mid$ 在$\scriptstyle{\boldsymbol{x}}_{\boldsymbol{0}}$ 处不可导.  

综上,选(C).  

例 3. 4若函数 $f(x\,)={\big|}\ln\,x-a x\mid$ 有两个不可导点，求常数 $^{a}$ 的取值范围.  

【解】令 $g\left(x\,\right)=\ln\,x-a x$ ，则 $g^{'}(x)\,{=}\,\frac{1}{x}-a\,,g^{\prime\prime}(x)\,{=}\,{-}\,\frac{1}{x^{\,2}}$ ,由例3.3的(D)可知,函数 $f(x)={\big|}\ln\,x-a x\,{\big|}$ 的不可导点即为使 $g\left(x\right)=0$ 且 $g^{\prime}(x)\neq0$ 的点.  

当 $\alpha\leqslant0$ 时， $g^{\prime}(x)\!=\!\frac{1}{x}\!-\!a>0(x>0)$ ，函数 $g\left(x\right)$ 在其定义域 $(0,+\infty)$ 上单调增加.又 $g\left(0^{+}\right)=-\infty$ ， $g\left(+\infty\right)=+\infty$ ,故当 $a\leqslant0$ 时，函数 $g\left(x\right)$ 只有一个零点.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/dfed28cc0612e18f352dbefe73be227b36ee1d46addeb0d83d98082e8e62ce5e.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c9107852a335c71f887012a0aab662f3cab85b054205046ac12457467afce406.jpg)  

当 $a>0$ 时，令 $g^{\prime}(x)\!=\!0$ ，得函数 $g\left(x\right)$ 的唯一驻点 $x=\!\frac{1}{a}$ 因为 $g^{\prime\prime}\Big(\frac{1}{a}\Big)\!=\!-a^{2}<0$ ，所以 $g\left({\frac{1}{a}}\right)\!=\!-\ln\,a-1$ 是函数 $g\left(x\right)$ 的最大值.由于 $g\left(0^{+}\right)=-\infty$ ， $g\left(+\infty\right)=-\infty$ ,因此当最大值  
# 比宁高等数学18讲  

$g\left(\frac{1}{a}\right)=-\ln\,a-1>0$ ,即 $0<a<\mathrm{e}^{-1}$ 时,函数 $_{g}(x)$ 有两个零点，设为 $x_{1}\in\left(0,\frac{1}{a}\right),x_{2}\in$  $\Bigl(\frac{1}{a},+\infty\Bigr)$ ,显然 $g^{\prime}(x_{1})\neq0$ ， $g^{\prime}(x_{2})\neq0.$ 因此，当 $0\!<\!a\!<\!\mathbf e^{-1}$ 时,函数 $f(x)=\mid\ln\,x-a x\mid$ 有两个不可导点.  

例 3. 5设 $f(x\,)=(\mathrm{e}^{x}-1)(\mathrm{e}^{2x}-2)\cdots(\mathrm{e}^{10x}-10)+\arcsin{\frac{x}{\sqrt{x^{2}-2x+2}}}$ 则 $f^{\prime}(0)=$  

【解】应填 $-\,9!+{\frac{\sqrt{2}}{2}}$  

$$
\begin{array}{c}{{u\left(x\right)=\left(\mathrm{e}^{x}\,-1\right)(\mathrm{e}^{2x}\,-2){\cdots}(\mathrm{e}^{10x}\,-10)\,,}}\\ {{g\left(x\right)=(\mathrm{e}^{2x}\,-2){\cdots}(\mathrm{e}^{10x}\,-10)\,,}}\end{array}
$$  

$$
v\left(x\right)=\arcsin{\frac{x}{\sqrt{x^{\,2}-2x+2}}},
$$  

$$
\begin{array}{r}{u\left(x\right)=\left(\mathbf{e}^{x}-1\right)g\left(x\right),u^{\prime}(x\mathbf{\Sigma})=\mathbf{e}^{x}g\left(x\right)+\left(\mathbf{e}^{x}-1\right)g^{\prime}(x\mathbf{\Sigma}),u^{\prime}(0)=g\left(0\right)=-\mathfrak{g}[.}\end{array}
$$  

又  

$$
v^{\prime}(0)=\!\!\operatorname*{lim}_{x\to0}{\frac{\arcsin{\frac{x}{\sqrt{x^{2}-2x+2}}}-0}{x}}\!=\!\!\operatorname*{lim}_{x\to0}{\frac{1}{\sqrt{x^{2}-2x+2}}}\!=\!{\frac{1}{\sqrt{2}}},
$$  

所以  

$$
f^{\prime}(0)=u^{\prime}(0)+v^{\prime}(0)=-\,9!+{\frac{\sqrt{2}}{2}}.
$$  

例 3. 6已知 $f(x){=}\sqrt[3]{x^{2}}\sin x$ ，则 $f^{\prime}(x)=\underline{{\phantom{\sum_{i=1}^{3}\varepsilon_{\infty}(R^{2}(x))}}}$  

【解】应填 $\left\{\begin{array}{l l}{{\displaystyle\frac{2}{3\,\sqrt[3]{x}}\mathrm{sin}\ x+\sqrt[3]{x^{\ 2}}\mathrm{cos}\ x\ ,\ }}&{{x\not=0,}}\\ {{\displaystyle0\,,}}&{{x=0.}}\end{array}\right.$  

当 $x\neq0$ 时， $f^{\prime}(x)\,{=}\,\frac{2}{3\,\sqrt[3]{x}}\mathrm{sin~}x\,+\sqrt[3]{x^{\frac{2}{}}}\mathrm{cos~}x$ 当 $x=0$ 时，  

$$
f^{\prime}(0)=\operatorname*{lim}_{x\to0}{\frac{f(x\,)-f(0)}{x-0}}=\operatorname*{lim}_{x\to0}{\sqrt[3]{x^{\,2}}}\,\cdot\,{\frac{\sin\,x}{x}}=0.
$$  

所以  

$$
f^{\prime}(x\,)=\!\left\{\!\!\begin{array}{l l}{{{\displaystyle2}\!\!\!\frac{2}{3\,\sqrt[3]{x}}\mathrm{sin}\ x+\sqrt[3]{x^{\,2}}\,\mathrm{cos}\ x\ ,\ }}&{{x\not=0\,,}}\\ {{\displaystyle0\,,\ }}&{{x=0.}}\end{array}\right.
$$  

【注】若 $f^{\prime}(x)=(\sqrt[3]{x^{2}}\sin x\,)^{\prime}\,{=}\,{\frac{2}{3\sqrt[3]{x}}}\mathrm{sin}\,\,x+\sqrt[3]{x^{2}}\cos x$ ,由于该式在 $x=0$ 处无定义,得出 $f^{\prime}(0)$ 不存在,这无疑是错误的.错误产生于 $\sqrt[3]{x^{2}}$ 在 $_{x=0}$ 处不可导,所以乘积的求导法则不适用,这也说明,即使不是分段函数,有时也要用定义求导,而且表达式中部分式子在某点不可导，但整体表达式在该点也可能可导.  
# 微分  

# (1) 定义.  

设函数 $_{y}=f(\l_{x})$ 在点 $_{x}$ 的某邻域内有定义,若对应于自变量的增量 $\Delta x$ ，函  

数的增量 $\Delta y$ 可以表示为 $\Delta y=A\,\Delta x+o\left(\Delta x\,\right)$ ,其中 $A$ 与 $\Delta x$ 无关,则称函数 $y=f(x\,)$ 在点 $_{x}$ 处可微,并把 $A\,\Delta x$ 称为 $_{y=f(x)}$ 在点 $_{\mathcal{x}}$ 处相应于自变量增量 $\Delta x$ 的微分,记作dy 或 $\mathsf{d}[f(x)]$ ，即$\mathsf{d}y=A\,\Delta x$  

# （2）可微的充要条件.  

函数 $y=f(x\,)$ 在点 $_{x}$ 处可微的充分必要条件是 $f(x)$ 在点 $_{x}$ 处可导.此时 $A=f^{\prime}(x)$ ，即$\mathrm{d}y=f^{\prime}(x)\mathrm{d}x$  

# （3）一阶微分形式的不变性  

设 $_y=f(u)$ 可微，则微分 $\mathrm{d}y=f^{\prime}(\,u\,)\,\mathrm{d}u$ ,其中 $\pmb{u}$ 不论是自变量还是中间变量，微分形式保持不变。  

(注 $\mathbf{d}(x^{\,n})=n x^{\,n-1}\mathbf{d}x$ 叫幂的微分; ${\mathsf{d}}x^{\prime\prime}=({\mathsf{d}}x)^{n}$ 叫微分的幂.  

例 3. 7设函数 $y=f(x)$ 在任意点 $_{x}$ 处的增量 $\Delta y={\frac{y\Delta x}{x+{\sqrt{x^{2}+y^{2}}}}}+o(\Delta x)$ ,且 $f(0)=$ 1,则 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 在点 $x=0$ 处的微分 $\mathrm{d}y=(\begin{array}{l l l}{\mathrm{~}}&{}&{}\end{array})$  

(A)0 $(\operatorname{B})\operatorname{d}\!x$ $(\mathrm{C})2\mathrm{d}x$ (D)3dx  

【解】应选(B).  

由 $\Delta y=\frac{y\,\Delta x}{x\,+\,\sqrt{x\,^{2}+y\,^{2}}}+o\left(\Delta x\,\right)$ ，知 $y^{\prime}=\frac{y}{x+\sqrt{x^{2}+y^{2}}}$ ，又 $f(0)=1$ ，可得 $y^{\prime}(0)\!=\!1$ ，进而 $\mathrm{d}y\Bigm|_{x=0}=y^{\prime}(0)\mathrm{d}x=\mathrm{d}x$ ,应选(B).  

例 3. 8 $\operatorname*{lim}_{x\to0}{\frac{\operatorname{d}\!\left({\frac{\sin{\,x\,}}{x}}\right)}{\operatorname{d}\!\left(x^{\,2}\right)}}=\longrightarrow\longrightarrow\quad\cdot$  

【解】应填 $-\,{\frac{1}{6}}$  

$$
\begin{array}{r l}&{\underset{x\rightarrow0}{\mathrm{lim}}\frac{\mathrm{d}\left(\frac{\sin{x}}{x}\right)}{\mathrm{d}\left(x^{2}\right)}=\underset{x\rightarrow0}{\mathrm{lim}}\frac{x\cos{x}-\sin{x}}{2x^{3}}}\\ &{\qquad\qquad\qquad=\underset{x\rightarrow0}{\mathrm{lim}}\frac{\cos{x}\left(x-\tan{x}\right)}{2x^{3}}}\\ &{\qquad\qquad\qquad=-\frac{1}{6}.}\end{array}
$$  
# 第4讲一元函数微分学的计算  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a754da390adfd02cf0f600d16d1a0016d668c37a57159d966bdfa792ac033a01.jpg)  

在分段点用导数定义求导（定义法）在非分段点用导数公式求导（公式法）  

以下求导公式均在其定义域上进行.  
$\textcircled{1}(x^{k})^{\prime}=k x^{k-1}$ (k为任意实数).  

$$
{\mathcal{Q}}(\ln\mid x\mid)^{\prime}={\frac{1}{x}}.
$$  

$\mathfrak{O}(\mathfrak{e}^{x})^{\prime}=\mathfrak{e}^{x}\,;(\alpha^{\,x}\,)^{\prime}=\alpha^{\,x}\ln\,\alpha\,,\alpha>0\,,\alpha\neq1.$ $\circledast(\sin\,x\,)^{\prime}=\cos\,x\,\,;(\cos\,x\,\,)^{\prime}=-\sin\,x\,\,;$ (ta $\mathrm{~n~}x\,\!\mathrm{\})^{\prime}=\sec^{2}x\,\,;(\cot\,x\,)^{\prime}=-\csc^{2}x$  
(sec $x\,)^{\prime}=\sec\,x\tan\,x\ ;(\csc\,x\,)^{\prime}=-\csc\,x\cot\,x\ ;$ $(\ln\mid\cos\,x\;\mid)^{\prime}=-\tan\,x\;;(\ln\;\mid\sin\,x\;\mid)^{\prime}=\cot\,x\;;$ (ln I s $\sec\,x\,+\tan\,x\ \mid\,)^{\prime}=\sec\,x\,;(\ln\ \vert\,\csc\,x\,-\cot\,x\ \mid\,)^{\prime}=\csc\,x\,.$ $\circled{5}$ $(\arctan\,x\,)^{\prime}\,{=}\,{\frac{1}{1+x^{\,^{2}}}},(\operatorname{arccot}\,x\,)^{\prime}\,{=}\,{-}{\frac{1}{1+x^{\,^{2}}}}.$ $\odot(\arcsin\,x\,)^{\prime}=\!{\frac{1}{\sqrt{1-x^{2}}}}$ ;(arccos $x\left.\right\rangle^{\prime}=-\frac{1}{\sqrt{1-x^{2}}}.$  $\mathcal{D}[\ln(x+\sqrt{{x}^{2}+{a}^{2}}\,)]^{\prime}=\frac{1}{\sqrt{{x}^{2}+{a}^{2}}}$ ，常见 $\alpha=1$  $(\ln\mid x+{\sqrt{x^{2}-a^{2}}}\mid)^{\prime}={\frac{1}{\sqrt{x^{2}-a^{2}}}}$ ，常见 $\alpha=1$  

# =复合函数求导  

设 $u=g\left(x\right)$ 在点 $_{x}$ 处可导， $_y=f(u)$ 在点 $u=g\left(x\right)$ 处可导，则$\{f\lbrack g(x)\rbrack\}^{\prime}=f^{\prime}\lbrack g(x)\rbrack g^{\prime}(x),$  

[注 $|\{f[g(x)]\}^{\prime}\!=\!\frac{\mathrm{d}\{f[g(x)]\}}{\mathrm{d}x}$ 而 $f^{\prime}[g(x)]\!=\!\frac{\!\mathrm{d}\{f[g(x)]\}}{\mathrm{d}[g(x)]}$ ,要看清楚求导符号的位置,不要弄错了.  

#  

1 4.1 $f(x)$ 与$_{g}(x)$ 的图像如图4-1所示，设 $u\left(x\,\right){=}f\!\left[g\left(x\,\right)\right]$ ，则 ${\pmb u}^{\prime}(1)=.$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/81fb51c6366dd34d73d97e56df4956cd60a0843bd630f6d2f4646835975cf0d2.jpg)  
图4-1  

# 【解】应填 $\frac{3}{4}$  

由 $\boldsymbol{u}^{\prime}(\boldsymbol{x})=\boldsymbol{f}^{\prime}[\boldsymbol{g}(\boldsymbol{x})]\cdot\boldsymbol{g}^{\prime}(\boldsymbol{x})$ ,有 $\pmb{u}^{\prime}(1)=f^{\prime}\big[\pmb{g}(1)\big]\cdot\pmb{g}^{\prime}(1)$ ,其中$g\left(1\right)=3,g^{\prime}(1)=\stackrel{0-6}{2-0}=-\,3\,,f^{\prime}(3)=\frac{3-4}{6-2}=-\,\frac{1}{4},$ $u^{\prime}(1)=f^{\prime}(3)\bullet g^{\prime}(1)=-\frac{1}{4}\bullet(-3)=\frac{3}{4}.$  
# 陆亨高等数学18游  

# 隐函数求导  

设函数 $_y=y\left(x\right)$ 是由方程 $F(x\,,y\,)\,{=}0$ 确定的可导函数,则有三种方法可求出i导数。  

法一方程 $F(x\,,y\,)=0$ 两边对自变量 $_x$ 求导(注意 $y=y\left(x\right)$ ,即将 $_y$ 看作中间变量),得到一个关于 $y^{'}$ 的方程,解该方程便可求出 $y^{\prime}$  

法二由复合函数求导公式可得  

$$
\begin{array}{r}{\mathsf{d}\{f\lbrack g(x)\rbrack\}=f^{\prime}\lbrack g(x)\rbrack g^{\prime}(x)\mathsf{d}x.}\end{array}
$$  

$(\;\star\;)$ 式就是微分形式的不变性——无论 $\pmb{u}$ 是中间变量还是自变量， $\mathrm{d}y=\ f^{\prime}(u)\mathrm{d}u$ 都成立.  

[注 】 有时会用到二元函数全微分形式的不变性;设 $z=f(u\,,v\,)\,,u=u\left(x\,,y\,\right),v=v(x\,,y\,)\,,$ 如果 $f(u\,,v)\,,u\left(x\,,y\,\right),v(x\,,y)$ 分别有连续偏导数,则复合函数 $\boldsymbol{z}=f(\boldsymbol{u},\boldsymbol{v})$ 在 $(x\,,y\,)$ 处的全微分仍可表示为 $\mathrm{d}z=\frac{\partial z}{\partial u}\mathrm{d}u+\frac{\partial z}{\partial v}\mathrm{d}v$ ,即无论 $u\bullet v$ 是自变量还是中间变量此式总成立,如$z=x y^{2}$ ,则 $\mathsf{d}z=\frac{\partial z}{\partial x}\mathsf{d}x+\frac{\partial z}{\partial y}\mathsf{d}y=y^{2}\,\mathsf{d}x+2x y\,\mathsf{d}y$  

法三由隐函数存在定理可得 ${\frac{\mathrm{d}y}{\mathrm{d}x}}=-{\frac{F_{\mathrm{~r~}}^{\prime}}{F_{\mathrm{~y~}}^{\prime}}}$ 例 4. 2设函数 $y=y\left(x\,\right)$ 由方程 $x^{\,s}=y^{\,s}+\cos\,x^{\,s}$ 所确定，则 $\rule{5ex}{0.2ex}=-$ 【解】应填 $-\,{\frac{y x^{\,s-1}-y^{\,s}\ln\,y+3x^{\,2}\sin\,x^{\,s}}{x^{\,s}\ln\,x-x y^{\,s-1}}}.$  

则  

$$
\frac{\mathrm{d}y}{\mathrm{d}x}=-\frac{F_{x}^{\prime}}{F_{y}^{\prime}}=-\frac{y x^{\,y^{-1}}-y^{\,x}\ln\,y+3x^{\,2}\sin\,x^{\,3}}{x^{\,y}\ln\,x-x y^{\,x^{-1}}}.
$$  

$x\,,\!y$  $F_{x}^{\prime}$  $_y$  $F_{y}^{\prime}$  $_{x}$ 为常数.  

列 4. 3设函数 $_{y=y}(x)$ 由方程 $\cos(x^{2}+y^{2})+\mathbf{e}^{x}-x y^{2}=0$ 所确定，则 $\mathrm{d}y=.$  

[解 应填 $\frac{\mathbf{e}^{x}-\mathbf{y}^{2}-2x\sin(x^{2}+y^{2})}{2y\left[x+\sin(x^{2}+y^{2})\right]}\mathrm{d}x\,.$  

法一　将原方程两边直接对 $_x$ 求导数，注意 $_y$ 是 $_{x}$ 的函数，解方程求出 $y^{\prime}$ 即可。  

$$
-\,(2x+2y\cdot y^{\prime})\sin(x^{\,2}+y^{\,2})+\mathrm{e}^{\,\prime}-y^{\,2}-x\,\cdot\,2y\,\cdot\,y^{\,\prime}=0\,,
$$  

得  

$$
y^{\prime}=\frac{\mathrm{e}^{x}-y^{2}-2x\sin(x^{2}+y^{2})}{2y[x+\sin(x^{2}+y^{2})]},
$$  

故  

$$
\mathrm{d}y=\frac{\mathrm{e}^{x}-y^{2}-2x\sin(x^{2}+y^{2})}{2y\big[x+\sin(x^{2}+y^{2})\big]}\mathrm{d}x\,.
$$  
法二将方程 $\cos(x^{2}+y^{2})+\mathbf{e}^{x}-x y^{2}=0$ 两边同时求微分，得  

$$
-\,(2x\,\mathrm{d}x+2y\,\mathrm{d}y\,)\sin(x^{\,2}+y^{\,2})+\mathrm{e}^{x}\,\mathrm{d}x-y^{\,2}\mathrm{d}x-2x y\,\mathrm{d}y=0\,,
$$  

故  

$$
\mathrm{d}y=\frac{\mathrm{e}^{x}-y^{2}-2x\sin(x^{2}+y^{2})}{2y\big[x+\sin(x^{2}+y^{2})\big]}\mathrm{d}x\,.
$$  

法三公式法.  

令$F(x\,,y)\,{=}\cos(x^{\,2}+y^{\,2})+\mathrm{e}^{x}-x y^{\,2}$ ，则  

$$
\frac{\mathrm{d}y}{\mathrm{d}x}=-\frac{F_{x}^{\prime}}{F_{y}^{\prime}}\,{=}\frac{\mathrm{e}^{x}-y^{2}-2x\sin(x^{\,2}+y^{2})}{2y\big[x\,+\sin(x^{\,2}+y^{\,2})\big]},
$$  

故  

$$
\mathrm{d}y=\frac{\mathrm{e}^{x}-y^{2}-2x\sin(x^{2}+y^{2})}{2y\big[x+\sin(x^{2}+y^{2})\big]}\mathrm{d}x\,.
$$  

例 4. 4设 $_y=y(x)$ 是由方程 $\int_{0}^{y}\mathrm{e}^{-t^{2}}\,\mathrm{d}t=2y-\ln(1+x\,)$ 所确定的二阶可导函数,且$y\left(0\right)=0$ ,则 $\left.y^{\prime\prime}\right|_{x=0}=\underline{{{\mathrm{~\\\\\\\\\\}}}}.$  

【解】应填－1.  

对方程 $\int_{0}^{y}\mathrm{e}^{-t^{2}}\,\mathrm{d}t=2y-\ln(1+x\,)$ 两边关于 $_{x}$ 连续求导两次,得  

$$
\mathrm{e}^{-y^{2}}y^{\prime}=2y^{\prime}-\frac{1}{1+x},
$$  

$$
-\,2y\,\mathrm{e}^{-y^{2}}\,(y^{\prime})^{2}+\mathrm{e}^{-y^{2}}\,y^{\prime\prime}\!=\!2y^{\prime\prime}\!+\!{\frac{1}{(1+x\,)^{2}}}.
$$  

将$x=0\,,y=0$ 代人上式，得 $y^{\prime\prime}{\Big|}_{x=0}=-1$  

# 四反函数求导  

设单调函数 $_y=f(x)$ 可导，且 $f^{\prime}(x)\neq0$ ,则存在反函数 $x=\varphi(y)$ ,且$\frac{\mathrm{d}x}{\mathrm{d}y}=\frac{1}{\frac{\mathrm{d}y}{\mathrm{d}x}}$  

$$
\varphi^{\prime}(y)\mathop{=}\frac{1}{f^{\prime}(x)}.
$$  

在 $y=\ f(\l{x}\,)$ 二阶可导的情况下，记 $f^{\prime}(x)=\,y_{\,x}^{\prime}\,,\varphi^{\prime}(y)=\,x_{\,y}^{\prime}(x_{\,y}^{\prime}\ne0)$ ，则有  

$$
y_{x}^{\prime}{=}{\frac{\mathrm{d}y}{\mathrm{d}x}}={\frac{1}{{\frac{\mathrm{d}x}{\mathrm{d}y}}}}={\frac{1}{x_{y}^{\prime}}},y_{x x}^{\prime\prime}{=}{\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{2}}}={\frac{\mathrm{d}\Bigl({\frac{\mathrm{d}y}{\mathrm{d}x}}\Bigr)}{\mathrm{d}x}}={\frac{\mathrm{d}\Bigl({\frac{1}{x_{y}^{\prime}}}\Bigr)}{\mathrm{d}x}}={\frac{\mathrm{d}\Bigl({\frac{1}{x_{y}^{\prime}}}\Bigr)}{\mathrm{d}y}}\cdot{\frac{1}{x_{y}^{\prime}}}={\frac{-x_{y}^{\prime\prime}}{(x_{y}^{\prime})^{3}}}.
$$  

反过来,则有  

$$
x_{\,y}^{\prime}{=}\frac{1}{y_{\,x}^{\prime}}{,}x_{\,y y}^{\prime\prime}{=}\frac{-y_{\,\,x x}^{\prime\prime}}{(y_{\,x}^{\prime})^{3}}.
$$  

例 4. 5  

设 $y=f(x)=x\!\int_{0}^{2}\!\mathbf{e}^{-(x t)^{2}}\,\mathrm{d}t\,{+}\,x^{2}$ ,其在 $x=0$ 的某邻域内与 $x=g(y)$ 互为反函数，  
# 比亨高肾数学18涉  

则$g^{\prime\prime}(0)=$  

【解】应填 $-\,{\frac{1}{4}}$  

由  

$$
x\int_{0}^{2}\mathrm{e}^{-\left(\boldsymbol{x}t\right)^{2}}\,\mathrm{d}t\,\frac{\displaystyle\gg\boldsymbol{x}t=u}{\displaystyle}\int_{0}^{2x}\mathrm{e}^{-u^{2}}\,\mathrm{d}u\,,
$$  

得  

$$
f(x)=\!\!\int_{0}^{2x}\mathrm{e}^{-u^{2}}\,\mathrm{d}u+x^{2}\,,
$$  

于是 $^{\prime}(x)=2\mathrm{e}^{-4x^{2}}+2x\,,\,f^{\prime\prime}(x)=-\,16x\,\mathrm{e}^{-4x^{2}}+2\,,\,f^{\prime}(0)=2\,,\,f^{\prime\prime}(0)=2$ 且$f(0)=0$ ,故  

$$
g^{\prime\prime}(0)\!=\!\frac{-f^{\prime\prime}(0)}{\left[f^{\prime}(0)\right]^{3}}\!=\!-\frac{1}{4}.
$$  

JRs 五分段函数求导（含绝对值）  

# (1）在分段点用导数定义求导(定义法）.  

# （2）在非分段点用导数公式求导（公式法）.  

例 4. 6已知函数 $f(x)$ 连续且 $\operatorname*{lim}_{x\to0}{\frac{f(x)}{x}}=1,g(x)=\int_{0}^{1}f(x t)\,\mathrm{d}t$ ，求 $g^{\prime}(x)$ 并证明 $g^{\prime}(x)$ 在 $x=0$ 处连续.  

【解】由 $\operatorname*{lim}_{x\to0}{\frac{f(x)}{x}}=1$ ,知 $\operatorname*{lim}_{x\to0}f(x)=0$ ，又 $f(x)$ 在 $x=0$ 处连续,所以 $f(0)=0$ ，从而  

$$
g\left(0\right)=\int_{0}^{1}f(0)\,\mathsf{d}t=0.
$$  

当 $x\neq0$ 时，令 $\boldsymbol{u}=x t$ ，则  

$$
g\left(x\,\right)=\frac{1}{x}{\int_{0}^{x}}f(u)\,\mathrm{d}u\,.
$$  

故  

$$
g\left(x\right)=\mathrel{\left\{\frac{1}{x}\!\!\int_{0}^{x}f(u)\mathrm{d}u\right.},\quad x\not=0,}
$$  

于是  

$$
g^{\prime}(0)=\!\!\operatorname*{lim}_{x\to0}{\frac{g(x)-g(0)}{x-0}}\!=\!\!\operatorname*{lim}_{x\to0}{\frac{\int_{0}^{x}f(u)\mathrm{d}u}{x^{2}}}\!=\!\!\operatorname*{lim}_{x\to0}{\frac{f(x)}{2x}}\!=\!\!{\frac{1}{2}}.
$$  

当 $x\neq0$ 时， $g_{_{\gamma}}^{^{\prime}}(x)=\!\frac{f(x)}{x}-\frac{1}{x^{2}}\!\!\int_{0}^{x}f(u)\,\!\mathrm{d}u.$  

故  

$$
g^{\prime}(x)=\!\left\{\!\!\begin{array}{l l}{\displaystyle{\frac{f(x)}{x}\!-\!\frac{1}{x^{2}}}\!\!\int_{0}^{x}f(u)\mathrm{d}u\,,}&{x\not=0\,,}\\ {\displaystyle{\frac{1}{2}},}&{x=0.}\end{array}\!\!\right.
$$  

因为  

$$
\operatorname*{lim}_{x\to0}g^{\prime}(x\,)=\!\!\operatorname*{lim}_{x\to0}\left[\frac{f(x\,)}{x}-\frac{1}{x^{2}}\right]^{x}f(u\,)\,\mathrm{d}u\right]\!=\!\frac{1}{2}\!=\!g^{\prime}(0)\,,
$$  
所以 $g^{\prime}(x)$ 在 ${x=0}$ 处连续.  

# 六对数求导法  

对于多项相乘、相除、开方、乘方的式子，一般先取对数再求导.设 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$  $y\ne0.$ ，则  

$\textcircled{1}$ 等式两边加绝对值符号后取对数，得 $\ln\mid y\mid=\ln\mid f(x)\mid$ ：  

$\circledcirc$ 两边对自变量 $_x$ 求导(同样注意 $y=f(x\,)$ ，即将 $_y$ 看作中间变量),得  

$$
{\frac{1}{y}}y^{\prime}=[\ln{\mid f(x)\mid}]^{\prime}{\Rightarrow}y^{\prime}=y\big[\ln{\mid f(x)\mid}\big]^{\prime}.
$$  

# 例4.7  

求 $f(x)\,{=}\,x^{\,x}\,(1-x\,)^{1-x}$ 在（0，1）内的最小值.  

【解】取对数，得  

$$
\ln\,f(x\,)=x\ln\,x+(1-x\,)\ln(1-x\,)\,,
$$  

则  

$$
{\begin{array}{c}{{\left[\ln\,f(x)\right]^{\prime}{=}{\frac{1}{f(x)}}f^{\prime}(x)=\ln x+1-\ln(1-x)-(1-x)\cdot{\frac{1}{1-x}}}}\\ {{=\ln x-\ln(1-x)=\ln{\frac{x}{1-x}},}}\\ {{\;{\;{\;f}^{\prime}(x)=}f(x)\ln{\frac{x}{1-x}};}}\end{array}}
$$  

于是  

令 $f^{\prime}(x)\!=\!0$ 愛得 $x=\frac{1}{2}$ 当 $0\!<\!x\!<\!\frac{1}{2}$ 时 $f^{\prime}(x)\!<\!0$  $\frac{1}{2}\!<\!x\!<\!1$ 时 $f^{\prime}(x)\!>\!0.$  $f(x)$  $\left(0,{\frac{1}{2}}\right]$ 内单调减少,在 $\left[{\frac{1}{2}},1\right)$ 内单调增加， $x=\frac{1}{2}$ 为最小值点，且  

$$
f_{\operatorname*{min}}(x)=f\!\left({\frac{1}{2}}\right)\!=\!\left({\frac{1}{2}}\right)^{\frac{1}{2}}\!\left(1-{\frac{1}{2}}\right)^{1-{\frac{1}{2}}}\!=\!{\frac{1}{2}}.
$$  

# 七幂指函数求导法  

对于 $u(x)^{v(x)}\left(u(x)>0,u(x)\right)\ne1)$ ,除了用上面的对数求导法外,还可以先化成指数函数  

$$
u\left(x\,\right)^{v(x)}=\mathrm{e}^{v(x)\ln u(x)}\,,
$$  

然后对 $_{x}$ 求导，得  

$$
\left[u\left(x\right)^{v\left(x\right)}\right]^{\prime}=\left[\mathbf{e}^{v\left(x\right)\ln{u\left(x\right)}}\right]^{\prime}=u\left(x\right)^{v\left(x\right)}\left[v^{\prime}(x)\ln{u\left(x\right)}+v(x)\cdot{\frac{u^{\prime}(x)}{u\left(x\right)}}\right].
$$  

例 4.8已知函数 $f(x)={\binom{x^{2x}\,,}{x\,{\mathrm{e}}^{x}+1\,,}}\quad x\geq0\,,$ 则 $f^{\prime}(x)=\underline{{\phantom{\sum_{i=1}^{3}\varepsilon_{\infty}^{2}}}}$  

【 解 】应填 $\begin{array}{r}{\left\langle2x^{2x}\left(\ln x+1\right),~~~x>0\,,\right.}\\ {\left.\mathrm{e}^{x}\left(x+1\right),~~~x<0.}\end{array}$  
比宁高等数学18讲  

当 $x>0$ 时， $f^{\prime}(x)\!=\!(x^{2x})^{\prime}\!=\!(\,\mathrm{e}^{2x\ln x}\,)^{\prime}\!=\!2x^{2x}\,(\ln x+1)$ ;当 $x<0$ 时， $f^{\prime}(x)\,{=}\,\mathrm{e}^{x}\,(x+1)$ 因为 $\operatorname*{lim}_{x\to0^{+}}{\frac{x^{\,2^{x}}-1}{x}}\!=\!\operatorname*{lim}_{x\to0^{+}}{\frac{\mathrm{e}^{2x\ln x}-1}{x}}\!=\!\operatorname*{lim}_{x\to0^{+}}{\frac{2x\ln x}{x}}\!=\!-\infty$ ，所以 $f^{\prime}(0)$ 不存在.  

综上，  

$$
f^{\prime}(x)={\binom{2x^{2x}\,(\ln\,x+1)\,,\quad x>0\,,}{\mathrm{e}^{x}\,(x+1)\,,\quad\quad x<0.}}
$$  

设函数 $_y=y\left(x\right)$ 由参数方程 $\begin{array}{r}{\left\{x=\varphi\left(t\right),\right.}\\ {y=\psi\left(t\right)}\end{array}$ 确定,且 $\varphi\left(t\right),\psi\left(t\right)$ 均二阶可  

导， $\varphi^{\prime}(t)\neq0$ ,其中 $\boldsymbol{t}$ 是参数，则  

$$
\frac{\mathrm{d}y}{\mathrm{d}x}=\frac{\mathrm{d}y\,/\mathrm{d}t}{\mathrm{d}x\,/\mathrm{d}t}=\frac{\phi^{\prime}(t\,)}{\varphi^{\prime}(t\,)},\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{2}}=\frac{\mathrm{d}\Bigl(\frac{\mathrm{d}y}{\mathrm{d}x}\Bigr)}{\mathrm{d}x}=\frac{\mathrm{d}\Bigl(\frac{\mathrm{d}y}{\mathrm{d}x}\Bigr)\,\Bigl/\mathrm{d}t}{\mathrm{d}x\,/\mathrm{d}t}=\frac{\phi^{\prime\prime}(t\,)\varphi^{\prime}(t)-\phi^{\prime}(t\,)\varphi^{\prime\prime}(t\,)}{\bigl[\varphi^{\prime}(t\,)\bigr]^{3}}.
$$  

$\mathbf{\chi}_{x}=\mathbf{\chi}(t)$ ，例 4. 9设函数 $_y=y\left(x\right)$ 由参数方程 $\biggl\{y=\!\int_{0}^{t^{2}}\ln(1+u)\,\mathrm{d}u$ 确定,其中 $x\left(t\right)$ 是初值问题 $\begin{array}{l}{\displaystyle{\left\{\frac{\mathrm{d}x}{\mathrm{d}t}-2t\,\mathrm{e}^{-x}=0\right.}}\\ {\displaystyle{\left.\left|x\;\right|_{\;t=0}=0}}\end{array}$ 的解，求 $\frac{\mathbf{d}^{2}{\boldsymbol{y}}}{\mathbf{d}{\boldsymbol{x}}^{2}}$  

【解】由 $\frac{\mathrm{d}\boldsymbol{x}}{\mathrm{d}t}-2t\,\mathrm{e}^{-x}=0$ 得 $\mathbf{e}^{x}\,\mathbf{d}x=2t\,\mathbf{d}t$ ,两端积分并由条件 $x\mid_{_{t=0}}=0$ ，得 $\mathbf{e}^{x}=1+t^{2}$ ，即  

$$
x=\ln(1+t^{2}).
$$  

$$
{\frac{\mathrm{d}y}{\mathrm{d}x}}={\frac{\displaystyle{\frac{\mathrm{d}y}{\mathrm{d}t}}}{\displaystyle{\frac{\mathrm{d}x}{\mathrm{d}t}}}}={\frac{\ln(1+t^{2})\,\cdot\,2t}{\displaystyle{\frac{2t}{1+t^{2}}}}}=(1+t^{2})\ln(1+t^{2})\,,
$$  

$$
{\frac{\mathrm{1^{2}}y}{\mathrm{1}x^{2}}}={\frac{\mathrm{d}}{\mathrm{d}x}}\left({\frac{\mathrm{d}y}{\mathrm{d}x}}\right)={\frac{{\frac{\mathrm{d}}{\mathrm{d}t}}{\big[}(1+t^{2})\ln(1+t^{2}){\big]}}{{\frac{\mathrm{d}x}{\mathrm{d}t}}}}={\frac{2t\ln(1+t^{2})+2t}{{\frac{2t}{1+t^{2}}}}}=(1+t^{2})\left[\ln(1+t^{2})\ln(1+t^{2})\right]\,.
$$  

# 九高阶导数  

# (1) 归纳法.  

比如，设 $y=2^{x}$ ，则 $y^{\prime}=2^{x}\ln\,2\,,y^{\prime\prime}=2^{x}\,(\ln\,2)^{2}\,,\cdots,$ 得出通式$y^{(n)}=2^{x}\left(\ln\,2\right)^{n},n=0,1,2,\cdots.$  

例4.10  

已知函数 $f(x)$ 具有任意阶导数，且 $f^{\prime}(x)\mathop{=}\!\left[f(x)\right]^{3}$ ，则当 $_n$ 为大于1的整数  
时， $f(x)$ 的 $_n$ 阶导数 $f^{(n)}(x)=\_$  

$$
f^{\prime}(x\,)=\left[f(x\,)\right]^{3},f^{\prime\prime}(x\,)=3{\left[f(x\,)\right]}^{2}f^{\prime}(x\,)=3{\left[f(x\,)\right]}^{5}\,,
$$  

$$
f^{\prime\prime}(x\,)=3\bullet\,5{\bigl[}\,f(x\,){\bigr]}^{\ast}\,f^{\prime}(x\,)=3\bullet\,5{\bigl[}\,f(x\,){\bigr]}^{\intercal}\,,
$$  

$$
f^{(4)}(x)=3\bullet5\bullet7\big[f(x)\big]^{6}f^{\prime}(x)=3\bullet5\bullet7\big[f(x)\big]^{9}\,,
$$  

由归纳法易知， $f^{(n)}(x)=(2n-1)!!\ [f(x)]^{2n+1}$  

【注】这里 $(2n-1)!!=1\cdot3\cdot5\cdot7\cdot\cdots\cdot(2n-1)$  

例 4. 11已知函数 $f(x)={\frac{x^{2}}{1-x^{2}}}$ ,则 $f^{(n)}(x\,)=\_{}(n=1,2,3\,,\cdots).$  

【解】应填 $\cdot{\frac{n!}{2}}\left[{\frac{1}{(1-x\,)^{n+1}}}+{\frac{(-\,1)^{n}}{(1+x\,)^{n+1}}}\right]$ $f(x\,)\!=\!\frac{x^{2}-1+1}{1-x^{\,^{2}}}\!=\!-1+\!\frac{1}{1-x^{\,^{2}}}\!=\!-1+\frac{1}{2}\!\left(\frac{1}{1-x}+\frac{1}{1+x}\right)\!.$ 又$\left(\!\frac{1}{1-x}\!\right)^{\!\prime}\!=\!\frac{1}{\left(1-x\,\right)^{2}},\!\left(\!\frac{1}{1-x}\!\right)^{\!\prime}\!=\!\frac{2}{\left(1-x\,\right)^{3}},\!\left(\!\frac{1}{1-x}\!\right)^{\!\prime}\!=\!\frac{3\times2}{\left(1-x\,\right)^{4}},$  

于是得到 $\left({\frac{1}{1-x}}\right)^{(n)}={\frac{n!}{(1-x\,)^{n+1}}}$ ,同理得到 $\left({\frac{1}{1+x}}\right)^{(n)}={\frac{(-1)^{n}n!}{(1+x\,)^{n+1}}}.$  

因此  

$$
f^{\left(n\right)}\left(x\right)=\!\frac{n!}{2}\!\left[\!\frac{1}{\left(1-x\,\right)^{n+1}}+\!\frac{\left(-1\right)^{n}}{\left(1+x\,\right)^{n+1}}\!\right].
$$  

【注】常用高阶导数（ $\pmb{n}$ 为正整数): $({\mathrm{e}}^{a x+b})^{(n)}=a^{n}\,{\mathrm{e}}^{a x+b}$  

$$
\mathrm{n}(a x+b)\big]^{(n)}=a^{n}\sin\!\left(\!a x+b+\frac{n\pi}{2}\right),\big[\cos(a x+b)\big]^{(n)}=a^{n}\cos\!\left(\!a x+b+\frac{n\pi}{2}\right),
$$  

$$
[\ln(a x+b)]^{(n)}=(-1)^{n-1}a^{n}\,\,{\frac{(n-1)!}{(a x+b)^{n}}};\left({\frac{1}{a x+b}}\right)^{(n)}=(-1)^{n}a^{n}\,\,{\frac{n!}{(a x+b)^{n+1}}}.
$$  

例 4.12设 $f(x\,,y\,)\,{=}\,\frac{y}{y\,-\,x}\,,n$ 为大于1的整数，则 $\left.{\frac{\partial^{n}f}{\partial x^{n}}}\right|_{(2,1)}=\underbrace{\mathrm{.}}$  

【解】应填 $(-1)^{n+1}\cdot n!$ ：  

视$_y$ 为常数，则  

$$
{\frac{\partial^{\prime}f}{\partial x^{\prime}}}=(-\,y\,)\,\cdot\left({\frac{1}{x\,-\,y}}\right)_{\,{\scriptsize\!\!\!\!\!\!\!\!\!\!\!\!\!}_{x}}^{\,(n)}=(-\,y\,)\,\cdot(-\,1)^{n}\,\cdot\,{\frac{n\,!}{(x\,-\,y\,)^{n+1}}}\,,
$$  

故  

$$
\left.\frac{\partial^{n}f}{\partial x^{n}}\right|_{(2,1)}=(-1)\cdot(-\,1)^{n}\cdot n\,!\ =(-\,1)^{n+1}\cdot n\,!.
$$  

# (2）莱布尼茨公式.  

设$\boldsymbol{u}=\boldsymbol{u}\left(\boldsymbol{x}\ \right),\boldsymbol{v}=\boldsymbol{v}\left(\boldsymbol{x}\ \right)$ 均$_n$ 阶可导，则  

$$
(u\pm v)^{(n)}=u^{(n)}\pm v^{(n)}\,,
$$  
# 比亨高等数学18讲  

$$
\begin{array}{l}{{(u v)^{(n)}=u^{(n)}v+\mathrm{C}_{n}^{1}u^{(n-1)}v^{\prime}+\mathrm{C}_{n}^{2}u^{(n-2)}v^{\prime\prime}+\cdots+\mathrm{C}_{n}^{k}u^{(n-k)}v^{(k)}+\cdots+\mathrm{C}_{n}^{n-1}u^{\prime}v^{(n-1)}-\mathrm{C}_{n}^{k}u^{(n-k)}v^{(k)}}}\\ {{\mathrm{~}}}\\ {{\qquad=\displaystyle\sum_{k=0}^{n}\mathrm{C}_{n}^{k}u^{(n-k)}v^{(k)}.}}\end{array}
$$+uu(n)  

$(\;\star\;)$ 式就是乘积的高阶导数的莱布尼茨公式,其中 ${\boldsymbol{u}}^{(0)}={\boldsymbol{u}}\,,{\boldsymbol{v}}^{(0)}={\boldsymbol{v}}$  

【注】 $\textcircled{1}$ 见到求两个函数乘积的高阶导数,一般用莱布尼茨公式即可,有时要结合“(1)归纳法”中的通式；对于一个函数求高阶导数较困难时，若能转化成两个函数的乘积形式，亦可用莱布尼茨公式。  

$\circledcirc$ 若 $_n$ 不太大,其系数 $\mathrm{C}_{n}^{0}\,,\mathrm{C}_{n}^{1}\,,\mathrm{C}_{n}^{2}\,,\cdots,\mathrm{C}_{n}^{n-1}$ ， $C_{n}^{n}$ 的记忆方法可按下述“三角形”:  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/dae98b0292cdcd02c09cff4ef28350ccc7fc5363447b6989171fd9187c714000.jpg)  

例 4.13设 $f(x)=(x^{3}-1)^{n}$ ，则 $f^{(n)}\left(1\right)=.$  

【解】应填 $3^{n}n!$  

$f(x\,)=(x^{\,3}-1)^{\,n}=(x-1)^{\,n}(x^{\,2}+x+1)^{\,n}$ .由莱布尼茨公式，得  

$$
f^{(n)}\left(x\right)=\sum_{k=0}^{n}\mathsf{C}_{n}^{k}\left[(x-1)^{n}\right]^{(k)}\left[(x^{\,2}+x+1)^{n}\right]^{(n-k)},
$$  

故f"n $\begin{array}{r}{\mathrm{\large(1)}=\mathrm{\large(}\mathrm{\large(}x_{n}^{0}(x-1)^{n}\big[(x^{2}+x+1)^{n}\big]^{(n)}\bigg|_{x=1}+\mathrm{\largeC}_{n}^{1}\big[(x-1)^{n}\big]^{\prime}\big[(x^{2}+x+1)^{n}\big]^{(n-1)}\bigg|_{x=1}+}\\ {\mathrm{\large(}\mathrm{\large(}x-1)^{n}\big]^{((x-1)^{n})^{(n-1)}=n!(x-1)}}\\ {\mathrm{\largeC}_{n}^{n-1}\big[(x-1)^{n}\big]^{(n-1)}\big[(x^{2}+x+1)^{n}\big]^{\prime}\bigg|_{x=1}+\mathrm{\largeC}_{n}^{n}\left[(x-1)^{n}\right]^{(n)}(x^{2}+x+1)^{n}}\end{array}$ 。)” $=3^{n}n!$  

【注】多项式 $P_{n}=(x-x_{0})^{n}$ 的求导规律应当清楚,即 $P_{n}^{(n-1)}=n!\ (x-x_{0})$ ,而 $P_{n}^{(n)}=n!$  

# (3）泰勒展开式.  

$\textcircled{1}$ 任何一个无穷阶可导的函数都可写成  

抽象展开  

$$
y=f(x\,)=\sum_{n\,=\,0}^{\infty}\,\frac{f^{(n)}\left(x_{\,0}\right)}{n\,!}\left(x-x_{\,0}\right)^{\,n},
$$  

或者  

$$
y=f(x\,)=\sum_{n\,=\,0}^{\infty}\,\frac{f^{(n)}(0)}{n\,!}x^{\,n}.
$$  

$\textcircled{2}$ 题目给出一个具体的无穷阶可导函数 ${\mathfrak{y}}=f(x)$ ,可以通过已知公式展开成幂级数.这些已知公式为  

$\mathrm{e}^{x}=\sum_{n=0}^{\infty}{\frac{x^{n}}{n!}}=1+x+{\frac{x^{2}}{2!}}+\cdots+{\frac{x^{n}}{n!}}+\cdots,-\infty<x<+\infty.$ ${\frac{1}{1+x}}=\sum_{n=0}^{\infty}(-1)^{n}x^{n}=1-x+x^{2}-x^{3}+\cdots+(-1)^{n}x^{n}+\cdots,-1<x<1.$  
${\frac{1}{1-x}}=\sum_{n=0}^{\infty}x^{\,n}=1+x+x^{\,2}+\cdots+x^{\,n}+\cdots,-1<x<1.$ $\begin{array}{r l}&{1+x=\displaystyle\sum_{i=1}^{n}(-1)^{+}\frac{x^{*}}{n}=x-\frac{x^{\prime}}{2}+\frac{x^{1}}{3}-\frac{x^{*}}{4}+\dots+(-1)^{*-1}\frac{x^{*}}{n}+\dots,-1}\\ &{x=\displaystyle\sum_{i=1}^{n}(-1)^{*}\frac{x^{\prime*+1}}{(2n+1)!}}\\ &{\phantom{1+\ x=\pm\infty}-x^{\pm}\frac{x^{1}}{3!}+\frac{x^{5}}{5!}\frac{x^{7}}{12}+\dots+(-1)^{*}\frac{x^{\frac{\pi+1}{2}}}{(2n+1)!}+\dots,-\infty<x\leq+\infty,}\\ &{x=\displaystyle\sum_{i=1}^{n}(-1)^{*}\frac{x^{\prime}}{(2n)!}}\\ &{\phantom{1+\ x=\pm\infty}-\frac{x^{\prime}}{2!}+\frac{x^{4}}{4!}\frac{x^{4}}{16}+\dots+(-1)^{*}\frac{x^{\frac{\pi+1}{2}}}{(2n)!}+\dots,-\infty<x<+\infty,}\\ &{\phantom{1+\ x=\pm\infty}+x\displaystyle\sum_{i=1}^{n}x^{\prime}+\dots+\frac{\alpha(\alpha-1)^{*}\dots(\alpha-n+1)}{n!}x^{\prime}+\dots,}\\ &{\phantom{1+\ x=\pm\infty}\ge\left[x\in(-1,1),\ \alpha\in\mathscr{C}_{*}-1\right],}\end{array}$ x≤1.   
sin   
cos $\begin{array}{r l}&{\left\{x\,\in\,(-\,1,1)\,,\quad\alpha\leqslant-\,1,\right.}\\ &{\left\{x\,\in\,(-\,1,1],\quad-\,1<\alpha<0\,,\right.}\\ &{\left.\quad x\,\in\,[-\,1,1]\,,\quad\alpha>0\,,\alpha\,\notin\,{\bf N}_{+}\,,}\\ &{\left.\quad x\,\in\,{\bf R},\quad\quad\quad\alpha\in{\bf N}_{+}.\right.}\end{array}$   
tan $x=x+{\frac{1}{3}}x^{3}+\cdots$   
arcsin $x=x+{\frac{1}{6}}x^{3}+\cdots$   
arctan z由一比较系数 $x=x-{\frac{1}{3}}x^{3}+\cdots$  

$\textcircled{3}$ 函数泰勒展开式的唯一性:无论 $f(x)$ 由何种方法展开,其泰勒展开式具有唯一性.于是我们可以通过比较 $\textcircled{1}$  $\circledcirc$ 中公式的系数，获得 $f^{(n)}\left(x_{\circ},\right)$ 或者 $f^{(n)}\left(0\right)$  

例 4.14设函数 $f(x)={\frac{1+x+x^{2}}{1-x+x^{2}}}$ ,则 $f^{(4)}(0)=\_$  

【解】应填－48.  

$$
\begin{array}{c}{{f(x)=\displaystyle\frac{1+x+x^{2}}{1-x+x^{2}}\!=\!1+\!\frac{2x}{1-x+x^{2}}\!=\!1+\!2x\cdot\frac{1+x}{1+x^{3}}}}\\ {{\mathrm{}}}\\ {{\kappa\beta,\bar{\pi}\!+\!\!\!\!}}\\ {{\displaystyle=\!1+2x+2x^{2}-2x^{4}+o(x^{3})\!\!\!\!}}\end{array}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\
$$  

又$f(x)=\sum_{n=0}^{\infty}{\frac{f^{(n)}(0)}{n!}}x^{n}$ ,由泰勒展开式的唯一性,有 ${\frac{f^{(4)}\left(0\right)}{4!}}x^{4}=-2x^{4}$ ，故  

抽象展开 $f^{(4)}(0)=-2\cdot4!=-48.$  
# 第5讲  

# 一元函数微分学的应用 ( 一)—儿何应用  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/72213ca863a8d957f036e9d49fafac17c980d31546229cd6bfdae2af6749695d.jpg)  
极值点与拐点的重要结论  

铅直渐近线渐近线水平渐近线  

# 研究内容  

斜渐近线  

求区间 $[a,b]$ 上连续函数的最大值和最小值最值（值域）求区间 $(a\,,b\,)$ 内连续函数的最值或者取值范围曲率与曲率半径（仅数学一、数学二）  

# 1.“祖孙三代”  

具体，抽象，①f(x) f,（x）（函数族），f.·f2.... ②f(x),d[f(x)]f(n)(x).d(x²)3f(t)dt.  

# 2.用极限定义函数  

$f(x){=}\!\operatorname*{lim}_{n\to\infty}\!g(n\,,\!x\,)$ 或 $f(x)=\operatorname*{lim}_{t\to x}g(t,x)$   
3.分段函数（含绝对值）  
4.参数方程  

$$
\begin{array}{l}{\displaystyle\mathbb{\oplus}\left\{{\alpha=x\,(t)}\,,\right.}\\ {\displaystyle y=y\,(t).}\\ {\displaystyle\mathbb{\oplus}\left\{x=r\,(\theta)\cos\,\theta\,,\right.}\\ {\displaystyle y=r\,(\theta)\sin\,\theta.}\end{array}
$$  

5. 隐函数 $F(x,y)=0$  

$6.$ 微分方程的解 $y=y(x)$  

$7.$ 偏微分方程的解 $f(x,y)$  
# 阳亨高等数学18讲  

8.级数的和函数 S（x）=αx"（仅数学一、数学三）  

# 研究内容  

# 1.切线、法线、截距  

设$y=y\left(x\right)$ 可导且 $y^{\prime}(x)\neq0$ ,则相关结论见下表.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/93c9fd124bb0a1aa8068f11672b71209a501696fc073e633432230138bf302fe.jpg)  

例5.1  

曲线sin $x y+\ln(y-x)=x\,$ 在点（0,1）处的切线方程为  

【解】应填 $_y=x+1$  

令$f(x\,,y)=\sin\,x y+\ln(y-x\,)-x$ ，则  

$$
f_{_x}^{\prime}\left(0,1\right)=\left(y\cos\,x y+{\frac{-1}{y-x}}-1\right)\Bigm|_{_{(0,1)}}=-1,
$$  

$$
f_{\;y}^{\prime}\left(0,1\right)=\left(x\cos\;x y+{\frac{1}{y-x}}\right)\;{\Big|}_{\;\scriptscriptstyle(0,1)}=1.
$$  

于是， $y^{\prime}\,{\Big|}_{(0,1)}=-{\frac{f_{x}^{\prime}\,(0\,,1)}{f_{y}^{\prime}\,(0\,,1)}}==1$ ,故所求切线方程为 $y=x+1$  

例 5. 2曲线 $\begin{array}{r}{\left\{x=\!\!\int_{0}^{1-t}\mathrm{e}^{-u^{2}}\,\mathrm{d}u\,,\right.}\\ {\left.y=t^{2}\ln(2-t^{2})\right.}\end{array}$ 在点（0,0）处的切线方程为  

【解】应填 $2x-y=0$  

点（0,0）对应于 $t=1$ 因为  

$$
\frac{\mathrm{d}y}{\mathrm{d}t}\bigg\vert_{\mathrm{\boldmath~\tau~}=1}=\bigg[2t\ln(2-t^{2})+t^{2}\cdot\frac{-2t}{2-t^{2}}\bigg]\bigg\vert_{t=1}=-\,2\,,
$$  

$$
\left.{\frac{\mathrm{d}x}{\mathrm{d}t}}\,\right|_{t=1}=-\,\mathrm{e}^{-(1-t)^{2}}\,\bigg|_{\,t=1}=-\,1\,,
$$  

所以切线斜率为  

故所求切线方程为 $y=2x$ ，即 $2x-y=0$  
曲线 $r=1+\cos{\theta}$ 在点 $\left(1+{\frac{\sqrt{2}}{2}},{\frac{\pi}{4}}\right)$ 处的直角坐标系下的切线方程为  

【解】应填 $y=(1-\sqrt{2}\,)x+1+\frac{\sqrt{2}}{2},$  

$$
\begin{array}{l}{{\displaystyle\xi=r\cos\,\theta=\cos\,\theta+\cos^{2}\!\theta\,,}}\\ {{\displaystyle y=r\sin\,\theta=\sin\,\theta+\sin\,\theta\cos\,\theta\,,}}\end{array}
$$  

$$
\frac{\mathrm{d}y}{\mathrm{d}x}\,\Big\vert_{\theta=\frac{\pi}{4}}=\frac{\mathrm{d}y\,/\,\mathrm{d}\theta}{\mathrm{d}x\,/\,\mathrm{d}\theta}\,\Big\vert_{\theta=\frac{\pi}{4}}=\frac{\cos\,\theta+\cos\,2\theta}{-\sin\,\theta-\sin\,2\theta}\,\Big\vert_{\theta=\frac{\pi}{4}}=1-\sqrt{2}\,,
$$  

且 $x\mid_{_{\theta={\frac{\pi}{4}}}}={\frac{\sqrt{2}}{2}}+{\frac{1}{2}}\,,y\mid_{_{\theta={\frac{\pi}{4}}}}={\frac{\sqrt{2}}{2}}+{\frac{1}{2}}$ 则切点为 $\left({\frac{\sqrt{2}}{2}}+{\frac{1}{2}},{\frac{\sqrt{2}}{2}}+{\frac{1}{2}}\right)$ ，于是得切线方程为  

整理得  

$$
\begin{array}{c}{{y-\displaystyle\frac{\sqrt{2}}{2}-\displaystyle\frac{1}{2}=(1-\sqrt{2}\,)\left(x-\displaystyle\frac{\sqrt{2}}{2}-\displaystyle\frac{1}{2}\right),\hfill}}\\ {{y=(1-\sqrt{2}\,)x+1+\displaystyle\frac{\sqrt{2}}{2}.\hfill}}\end{array}
$$  

5.4设 $y=\tan^{n}x\,$ 在 $x=\frac{\pi}{4}$ 处的切线在 $_{x}$ 轴上的截距为 $\scriptstyle{{\mathcal{X}}_{n}}$ ，则 $\operatorname*{lim}_{n\to\infty}y\left(x_{n}\right){=}\frac{}{\,}$  

【解】应填 $\mathrm{e}^{-1}$  

先求 $y=\tan^{n}x\,$ 在点 $M\left({\frac{\pi}{4}},1\right)$ 处的切线方程,由  

$$
y^{\prime}\left({\frac{\pi}{4}}\right)=n\tan^{n-1}x\,\cdot\,\sec^{2}x\,\left|\,_{x\,=\,{\frac{\pi}{4}}}=2n\,,
$$  

得切线方程  

$$
y-1=2n\left(x-{\frac{\pi}{4}}\right).
$$  

在 $_{x}$ 轴上的截距为 $x_{\!\;n}=\!\frac{\pi}{4}-\frac{1}{2n}$ ,故  

$$
\operatorname*{lim}_{n\rightarrow\infty}y\left(x_{\,n}\right)=\operatorname*{lim}_{n\rightarrow\infty}\tan^{n}\left(\frac{\pi}{4}-\frac{1}{2n}\right)\frac{1^{\infty}}{-\mathrm{e}^{\mathrm{A}}}\,\mathrm{e}^{\mathrm{A}}\,,
$$  

其中  

$$
A=\operatorname*{lim}_{n\to\infty}\left[\tan\!\left({\frac{\pi}{4}}-{\frac{1}{2n}}\right)-1\right]=\!\operatorname*{lim}_{n\to\infty}{\frac{\tan\!\left({\frac{\pi}{4}}-{\frac{1}{2n}}\right)-\tan{\frac{\pi}{4}}}{\frac{1}{n}}}
$$  

$$
=-\frac{1}{2}(\tan\,x\,)^{\prime}\,\Big|_{\tiny{\mathbf{\Sigma}_{x}=\frac{\pi}{4}}}=-\,\frac{1}{2}\cdot\frac{1}{\cos^{2}x}\,\Big|_{\tiny{\mathbf{\Sigma}_{x}=\frac{\pi}{4}}}=-\,1.
$$  

故原极限 $={\mathsf{e}}^{-1}$  

2.极值、单调性  

对于函数 $f(x)$ ，若存在点 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 的某个邻域，使得在该邻域内任意一点 $_{x}$ ，均有  

成立，则称点 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 为 $f(x)$ 的极大值点(或极小值点）， $f(x_{\circ})$ 为 $f(x)$ 的极大值(或极小值).  
# 张宇高等数学18讲  

# （1）单调性的判别.  

设函数 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 在 $[a,b]$ 上连续，在 $(a\,,b\,)$ 内可导。  

$\textcircled{1}$ 如果在 $(\alpha\,,b)$ 内 $f^{\prime}(x)\geq0$ ,且等号仅在有限多个点处成立，那么函数 $_{y}=f(\l{x}\,)$ 在 $[a,b]$ 上单调增加;  

$\circledcirc$ 如果在 $(a\,,b\,)$ 内 $f^{\prime}(x)\leqslant0$ ,且等号仅在有限多个点处成立，那么函数 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 在 $[a,b]$ 上单调减少.  

# （2）一阶可导点是极值点的必要条件.  

设 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处可导，且在点 $\scriptstyle{\boldsymbol{x}}_{0}$ 处取得极值，则必有 $f^{\prime}(x_{0})=0$  

# （3）判别极值的第一充分条件.  

设$f(x)$ 在${\boldsymbol{x}}={\boldsymbol{x}}_{\mathit{0}}$ 处连续，且在 $\scriptstyle{\boldsymbol{x}}_{\mathrm{~0~}}$ 的某去心邻域 $U(x_{\scriptscriptstyle0},\delta)$ 内可导.  

$\textcircled{1}$ 若 $x\in(x_{\mathit{0}}-\delta\,,x_{\mathit{0}})$ 时， $f^{\prime}(x)\leq0$ ,而 $x\in(x_{\mathrm{~0~}},x_{\mathrm{~0~}}+\delta\,)$ 时， $f^{\prime}(x)\!>\!0$ ,则 $f(x)$ 在 $x=$  $\scriptstyle{\boldsymbol{x}}_{0}$ 处取得极小值；  

$\circledcirc$ 若 $x\in(x_{\circ}-\delta\,,x_{\circ})$ 时， $f^{\prime}(x)\!>\!0$ ,而 $x\in(x_{\mathit{\mathrm{~0~}}},x_{\mathit{\mathrm{~0~}}}+\delta)$ 时， $f^{\prime}(x)\!<\!0$ ,则 $f(x)$ 在 $_x=$  $\scriptstyle{\boldsymbol{x}}_{\,0}$ 处取得极大值；  

$\textcircled{3}$ 若 $f^{\prime}(x)$ 在 $(\,x\,_{0}-\delta\,,x\,_{0}\,)$ 和 $(x_{\mathit{\Pi}_{0}},x_{\mathit{\Pi}_{0}}+\delta\,)$ 内不变号，则点 $\scriptstyle{\boldsymbol{x}}_{0}$ 不是极值点.  

# （4）判别极值的第二充分条件.  

设$f(x)$ 在$\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处二阶可导，且 $f^{\prime}(x_{0})\,{=}\,0\,,f^{\prime\prime}(x_{0})\neq0.$  $\textcircled{1}$ 若 $f^{\prime\prime}(x_{\,0})<0$ ,则 $f(x)$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处取得极大值； $\circledcirc$ 若 $f^{\prime\prime}(x_{\,0})>0$ ,则 $f(x)$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处取得极小值.上述第二充分条件可以推广为第三充分条件.  

# （5）判别极值的第三充分条件。  

设$f(x)$ 在$x=x_{0}$ 处$_n$ 阶可导，且 $f^{\{m\}}\left(x_{0}\right)=0(m=1,2,\cdots,n-1),f^{\{n\}}\left(x_{0}\right)\neq0(n\geqslant2)$ ,则  $\textcircled{1}$ 当 $_n$ 为偶数且 $f^{\mathbf{\alpha}(n)}\left(x_{\circ}\right)<0$ 时， $f(x)$ 在 $\boldsymbol{\mathscr{x}}_{\mathit{0}}$ 处取得极大值；  

$\circledcirc$ 当 $_n$ 为偶数且 $f^{\mathbf{\alpha}(n)}\left(x_{0}\right)>0$ 时， $f(x)$ 在 $\scriptstyle{\boldsymbol{x}}_{0}$ 处取得极小值.  

例 5. 5设 $f(x\,)=\!\!\operatorname*{lim}_{n\to\infty}\left[\left(1+{\frac{x}{n}}\right)^{n}-\mathbf{e}^{x}\right]$ ，求 $f(x)$ 的极值.  

【解】先考虑 $\operatorname*{lim}_{t\to+\infty}\left[\left(1+{\frac{x}{t}}\right)^{\prime}-\mathrm{e}^{x}\right]$  $r={\frac{1}{t}}$ $\operatorname*{lim}_{t\to+\infty}t\left[\left(1+{\frac{x}{t}}\right)^{\prime}-\operatorname{e}^{x}\right]{\overset{(1+r x)^{{\frac{1}{r}}}-\operatorname{e}^{x}}{r^{+}}}=\operatorname{e}^{x}\operatorname*{lim}_{r\to0^{+}}{\frac{\operatorname{e}^{{\frac{1}{r}}\ln(1+r x)-x}-1}{r}}$ ${\begin{array}{r l}&{=\operatorname{e}_{\;r\to0^{+}}^{x}{\frac{\ln(1+r x\,)-r x}{r^{2}}}=\operatorname{e}_{\;r\to0^{+}}^{x}{\frac{\displaystyle{\frac{x}{1+r x}}-x}{2r}}=x\,\operatorname{e}_{\;r\to0^{+}}^{x}{\frac{-r x}{2r\,(1+r x\,)}}}\\ &{=-{\frac{x^{2}}{2}}\mathbf{e}^{x}\,,}\end{array}}$  

故$f(x)=-{\frac{x^{2}}{2}}\mathbf{e}^{x}$ 又$f^{\prime}(x\,)=-\left({\frac{x^{2}}{2}}+x\right)\mathbf{e}^{x}$ 令$f^{\prime}(x)=0$ 得$x=0$ 或$x=-2$  

又由于 $f^{\prime\prime}(x\,)=-\left(\frac{x^{\,2}}{2}+2x+1\right)\mathbf{e}^{x}\,,f^{\prime\prime}(0)=-1<0\,,f^{\prime\prime}(-\,2)=\mathbf{e}^{-2}>0$ ，从而函数 $f(x)$  
的极大值为 $f(0)=0$ ,极小值为 $f(-2)=-2\mathrm{e}^{-2}$  

例 5. 6设函数 $f(x)=\!\int_{0}^{x}\,\frac{(t+3)(t^{2}-1)}{\mathrm{e}^{t^{2}}\!\sqrt{1+t^{4}}}\mathrm{d}t$ ,则 $f(x)()$  

（A）有1个极大值点，2个极小值点（B）有2个极大值点，1个极小值点（C）有3个极大值点，没有极小值点（D）有3个极小值点，没有极大值点  

【解】应选(A).  

对 $_{x}$ 求导，可得 $f^{\prime}(x)\,{=}\,\frac{(x+3)(\,x^{\,2}-1)}{\mathrm{e}^{x^{2}}\sqrt{1+x^{\,4}}}$ 令 $f^{\prime}(x)=0$ ，得 $f^{\prime}(x)$ 的3个零点 $x_{\textrm{l}}=-3$ ， $x_{\,2}=-1,x_{\,3}=1$ ，即为 $f(x)$ 的3个驻点.  

当 $_x$ 从点 $x_{1}=-3$ 的左侧邻域经过 $\boldsymbol{x}_{\mathrm{~l~}}$ 到其右侧邻域时, $f^{\prime}(x)$ 由负变正,故点 $x_{\textrm{l}}=-3$ 为 $f(x)$ 的极小值点；  

当 $_x$ 从点 $x_{\,2}=-1$ 的左侧邻域经过 $x_{\mathrm{~2~}}$ 到其右侧邻域时， $f^{\prime}(x)$ 由正变负,故点 $x_{\,2}=-1$ 为 $f(x)$ 的极大值点；  

当 $_x$ 从点 $x_{\mathit{3}}=1$ 的左侧邻域经过 $x_{\:3}$ 到其右侧邻域时， $f^{\prime}(x)$ 由负变正,故点 $x_{\mathit{3}}=1$ 为 $f(x)$ 的极小值点.  

综上所述， $f(x)$ 有1个极大值点，2个极小值点，选（A).  

# 3.拐点、凹凸性  

# (1）凹凸性的定义.  

定义1设函数 $f(x)$ 在区间 $I$ 上连续.如果对 $I$ 上任意不同两点 $x_{\mathrm{~l~}},x_{\mathrm{~2~}}$ ，恒有  

$$
f\Big(\frac{x_{\mathrm{~l~}}+x_{\mathrm{~2~}}}{2}\Big)<\frac{f(x_{\mathrm{~l~}})+f(x_{\mathrm{~2~}})}{2}\,,
$$  

则称 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 在 $I$ 上的图形是凹的，如图5-1（a）所示；如果恒有  

$$
f\Big(\frac{x_{\mathrm{~l~}}+x_{\mathrm{~2~}}}{2}\Big)>\frac{f(x_{\mathrm{~l~}})+f(x_{\mathrm{~2~}})}{2}\,,
$$  

则称 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 在 $I$ 上的图形是凸的，如图5-1（b）所示.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f41c961d4dc16b9078e62db095a142e0011c27e61d9280dab7e8fb0da44d116e.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/1cadb26c82022b12ac2495250070137419a1b8032fea39a6a8acf23fe80e30ef.jpg)  
图形上任意弧段位于弦的上方  

$$
{\frac{f(x_{1})+f(x_{2})}{2}}>f{\Big(}{\frac{x_{1}+x_{2}}{2}}{\Big)}
$$  

$$
\frac{f(x_{1})+f(x_{2})}{2}<f\Big(\frac{x_{1}+x_{2}}{2}\Big)
$$  
[注] 事实上,当图形为(凹)时,可以将 $f\Big(\frac{1}{2}x_{1}+\frac{1}{2}x_{2}\Big)\sum_{(>)}\frac{1}{2}f(x_{1})+\frac{1}{2}f(x_{2})$ 更一般地写为  

$f(\lambda_{1}x_{1}+\lambda_{2}x_{2})\leq\lambda_{1}f(x_{1})+\lambda_{2}f(x_{2})$ ,其中 $0<\lambda_{1},\lambda_{2}<1,\lambda_{1}+\lambda_{2}=1$  

定义2设 $f(x)$ 在 $[a,b]$ 上连续,在 $(a,b)$ 内可导，若对 $^{(a,b)}$ 内的任意 $_{x}$ 及 $x_{0}(x\neq x_{0})$ ，均有  

$$
f(x_{0})+f^{\prime}(x_{0})(x-x_{0})\leq\int(x),
$$  

则称 $f(x)$ 在$[a,b]$ 上是凹的. （凸）  

【注】(几何意义） $y=f(x_{0})+f^{\prime}(x_{0})(x-x_{0})$ 是曲线 $_{y=f(x)}$ 在点 $(x_{0},f(x_{0}))$ 处的切线方程,因此 $(\,\star\,)$ 式的几何意义如图 5-2 所示 :若曲线 $y=f(x)(a<x<b)$ 在任意点处的切线（除该点外）总在曲线的下方（上方)，则该曲线是凹（凸）的.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/ea57dfe505dcdaf150212916f17b9cd5e567c935eb9a6060bace7c6120f103c7.jpg)  
图5-2  

(2)拐点定义. 连续曲线的凹弧与凸弧的分界点称为该曲线的拐点，  

（3）凹凸性与拐点的判别 $\textcircled{1}$ 判别凹凸性的充分条件.  
设函数 $f(x)$ 在 $I$ 上二阶可导.  
a.若在 $I$ 上 $f^{\prime\prime}(x)>0$ ，则 $f(x)$ 在 $I$ 上的图形是凹的；  
b.若在 $I$ 上 $f^{\prime\prime}(x)<0$ ，则 $f(x)$ 在 $I$ 上的图形是凸的.  
 $\circledcirc$ 二阶可导点是拐点的必要条件.  

设 $f^{\prime\prime}(x_{0}\,)$ 存在，且点 $(x_{0}\,,f(x_{0}))$ 为曲线上的拐点，则 $f^{\prime\prime}(x_{0})=0$ 【注】事实上，若点 $(x_{0},f(x_{0}))$ ）为曲线 $_y=$  $f(x)$ 上的拐点，则只有以下两种情况： $(1)f^{\prime\prime}(x_{0})\,{=}\,0$ ，如 $\scriptstyle y\;=\;x^{3}$ 在（0，0）处的情形，如图 5-3（a)所示.  

$(2)f^{\prime\prime}(x_{0})$ 不存在，如 $y=\sqrt[3]{x}$ 在(0,0)处的情形,如图 5-3(b) 所示.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/80acaf1872434c0f591f090889ad4a23c9e0d4078f934596bd057c3517b042e3.jpg)  
图5-3  
$\textcircled{3}$ 判别拐点的第一充分条件.  

设 $f(x)$ 在点 ${\boldsymbol{x}}={\boldsymbol{x}}_{0}$ 处连续，在点 $x=x_{\circ}$ 的某去心邻域 $U(x_{\scriptscriptstyle0},\delta)$ 内二阶导数存在，且在该点的左右邻域内 $f^{\prime\prime}(x)$ 变号(无论是由正变负，还是由负变正)，则点 $(x_{0},f(x_{0}))$ 为曲线上的拐点.  

$\circledast$ 判别拐点的第二充分条件.  

设 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{0}$ 处三阶可导，且 $f^{\prime\prime}(x_{0})=0,f^{\prime\prime}(x_{0})\neq0$ ,则 $(x_{0}\,,f(x_{0}))$ 为曲线上的拐点.  

判别拐点的第三充分条件.  

设 $f(x)$ 在 $x_{\circ}$ 处 $_n$ 阶可导，且 $f^{(m)}\left(x_{0}\right)=0(m=2,\cdots,n-1)\,,f^{(n)}\left(x_{0}\right)\neq0(n\geqslant3)$ ,则当 $_n$ 为奇数时， $(x_{0}\,,f(x_{0}))$ 为曲线上的拐点.  

例5.7设 $f(x),g(x)$ 二阶可导， $y=f^{\prime}(x\,)$ 与 $y=g^{\prime\prime}(x\,)$ 在 $[a,b]$ 上的图形分别如图5-4(a)，（b）所示，曲线 $y=f(x\,)$ 和曲线 $y=g\left(x\,\right)$ 的拐点个数分别为 $m\,,n$ ,则（).  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b7b6d45585e9948f0e04e39b3dcb9a4d69622412a771462c6ef8fa8c75b0de52.jpg)  
图5-4  

$(\mathrm{A})m=2,n=2$ $\begin{array}{l}{(\mathrm{B})m=2,n=3}\\ {(\mathrm{D})m=3,n=3}\end{array}$ $(\mathrm{C})m=3\,,n=2$  

【解】应选（A).  

由于 $f(x),g(x)$ 二阶可导，则在拐点处有 $f^{\prime\prime}(x\,)\,{=}\,0\,,g^{\prime\prime}(x\,)\,{=}\,0$ ，且在点 $_{x}$ 处左、右两侧邻域二阶导数变号.由此可知,如图5-5（a）所示,在点 $x_{\mathrm{~l~}}$ 处， $f^{\prime\prime}(x_{1})=0$ ,且 $f^{\prime\prime}(x)$ 在点 $x_{1}$ 处左、右两侧邻域变号 $(\,f^{\prime}(x\,)$ 单调性相反);同理,点 $x_{\mathrm{~2~}}$ 亦满足，故 $m=2$  

如图5-5（b）所示,在点 $x_{\,3}$ 处， $g^{\prime\prime}(\,x_{\,3}\,)=0$ ,且在点 $x_{\:3}$ 处左、右两侧邻域 $g^{\prime\prime}(x)$ 变号；同理，点 $_x$ 4 亦满足.在点 $x_{\textrm{5}}$ 处虽有 $g^{\prime\prime}(x_{5})=0$ ，但点 $x_{\textrm{5}}$ 左、右两侧邻域 $g^{\prime\prime}(x)$ 不变号，故不是拐点，故$n=2$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/d7cd17adb68e62c3a987d238506606334854239a01b6936a8768a7ed2b9af32d.jpg)  
图5-5  

例5.8  

$f(x)=\!\!\left\{{\frac{x^{2}}{4}}+x^{4}\sin{\frac{1}{x}}\right.,$ x≠0，设则( ). $x=0\,,$  

$(\mathrm{A})f^{\prime\prime}(0)>0$ 且 $f(x)$ 在 $x=0$ 的某邻域内的图形是凹的  
松亨高等数学18涉  

(B $3)f^{\prime\prime}(0)<0$ 且 $f(x)$ 在 $x=0$ 的某邻域内的图形是凸的 $(\mathbb{C})f^{\prime\prime}(0)>0$ 但 $f(x)$ 在 $x=0$ 的任意邻域内的图形均无凹凸性(D) $f^{\prime\prime}(0)<0$ 但 $f(x)$ 在 ${\boldsymbol x}=0$ 的任意邻域内的图形均无凹凸性  

【解】应选(C).  

$$
f^{\prime}(x)=\!\!\left\{\!\!\begin{array}{l l}{{\displaystyle\frac{x}{2}+4x^{3}\sin\displaystyle\frac{1}{x}-x^{2}\cos\displaystyle\frac{1}{x}},}&{{x\neq0\,,}}\\ {{\displaystyle0\,,}}&{{x=0\,,}}\end{array}\!\!\right.
$$  

满足 $f^{\prime\prime}(0)\!=\!\frac{1}{2}\!>\!0$ ，但由于 $\operatorname*{lim}_{x\to0}\left(12x^{\,2}\sin{\frac{1}{x}}-6x\cos{\frac{1}{x}}\right)=0$ ,所以在 $x=0$ 的较小去心邻域内， $f^{\prime\prime}(x)$  ${\frac{1}{2}}-\sin{\frac{1}{x}}$ 的符号一致(有正也有负）。例如，取点 $x_{\mathit{n}}=\frac{1}{\mathit{n}\,\pi+\frac{\pi}{2}}$ ，则当 $_{n}$ 为奇数时，由 $\frac{1}{2}-\sin\frac{1}{x_{\,n}}\!=\!\frac{3}{2}$ ，可知 $f^{\prime\prime}(x_{n})>0$ 当 $_n$ 为偶数时，由 $\frac{1}{2}-\sin\frac{1}{x_{\,n}}\!=\!-\frac{1}{2}$ ，可知 $f^{\prime\prime}(x\,,\,)<0$ 因此 $f(x)$ 在 $x=0$ 的任意邻域内的图形均不存在凹凸性.应选(C).  

例 5. 9设函数 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处有二阶导数,则（（A）当 $f(x)$ 在 $\boldsymbol{\mathscr{x}}_{\mathrm{~0~}}$ 的某邻域内单调增加时， $f^{\prime}(x_{0})>0$ (B）当 $f^{\prime}(x_{0})>0$ 时， $f(x)$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 的某邻域内单调增加（C）当曲线 $f(x)$ 在 $\boldsymbol{\mathscr{x}}_{\mathrm{~0~}}$ 的某邻域内是凹的时， $f^{\prime\prime}(x_{\,0})>0$ （D）当 $f^{\prime\prime}(x_{\,0})>0$ 时， $f(x)$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 的某邻域内的图形是凹的  

【解】应选(B).  

对于选项(A),取 $f(x)=x^{3}$ ， $x_{\mathit{0}}=0$ ，则 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 的某邻域内单调增加,但 $f^{\prime}(x_{0})=$ 0,排除(A);  

对于选项(B),由于 $f(x)$ 在 ${\boldsymbol{x}}={\boldsymbol{x}}_{\mathit{0}}$ 处有二阶导数，故 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 处一阶导数连续，即 $\operatorname*{lim}_{x\to x_{0}}f^{\prime}(x)=f^{\prime}(x_{0})>0.$ 由局部保号性知,存在 $\delta>0$ ，当 $x\in U(x\,_{0}\,,\delta\,)$ 时，有 $f^{\prime}(x)>0$ ,于是， $f(x)$ 在 $\boldsymbol{x}_{\mathrm{~0~}}$ 的某邻域内单调增加,选择(B);  

对于选项(C)，取 $f(x\,)=x^{4}$ ， $x_{\textup{0}}=0$ ，则曲线 $f(x)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{0}}$ 的某邻域内是凹的，但 $f^{\prime\prime}(x_{\circ})=0$ ,排除(C);  

对于选项（D），例5.8已经给出了反例，排除（D).  

# 4.极值点与拐点的重要结论  

以下结论均可直接使用，不必证明，  

$\textcircled{1}$ 曲线的可导点不同时为极值点和拐点.不可导点可同时为极值点和拐点. $\circledcirc$ 设多项式函数 $f(x)=(x-a)^{\prime}g(x)(n>1)$ ,且 $g\left(a\right)\neq0$ ,则当 $_n$ 为偶数时， $x=a$ 是 $f(x)$ 的极值点；当 $_n$ 为奇数时，点 $(a\,,0)$ 是 $f(x)$ 的拐点.  
$\textcircled{3}$ 设多项式函数 $f(x\,)=(x\,-a_{1})^{n_{1}}\,(x\,-a_{2}\,)^{n_{2}}\cdots(x\,-a_{k}\,)^{n_{k}}$ ,其中 $n_{i}$ 是正整数， $\boldsymbol{a}_{\:i}$ 是实数且 $\boldsymbol{a}_{\,i}$ 两两不等， $i=1,2,\cdots,k$  

记 $k_{\textrm{l}}$ 为 $n_{i}=1$ 的个数， $k_{\textrm{2}}$ 为 $n_{i}>1$ 且 $\boldsymbol{n}_{\:i}$ 为偶数的个数， $k_{3}$ 为 $n_{i}>1$ 且 $\boldsymbol{n}_{\iota}$ 为奇数的个数，则 $f(x)$ 的极值点个数为 $k_{1}+2k_{2}+k_{3}-1$ ,拐点个数为 $k_{1}+2k_{2}+3k_{3}-2$  

例 5.10设 $f(x)=\mid x\left(1-x\right)\mid$ ，则（ $(\mathbf{\nabla}\mathbf{A})_{\mathcal{X}}=0$ 是 $f(x)$ 的极值点，但点（0，0）不是曲线 $y=f(x\,)$ 的拐点 $(\mathrm{B})_{\mathcal{X}}=0$ 不是 $f(x)$ 的极值点，但点（0,0）是曲线 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 的拐点 $(\mathbf{C})x=0$ 是 $f(x)$ 的极值点，且点（0,0）是曲线 $y=f(x\,)$ 的拐点 $(\ensuremath{\mathrm{D}})_{\mathcal{X}}=0$ 不是 $f(x)$ 的极值点，且点（0,0）不是曲线 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 的拐点  

【解】应选(C).  

因为 $f(x)\!=\!\mid x\left(1\!-\!x\,\right)\mid\,\!\geqslant0,f(0)\!=\!0$ ，所以 $x=0$ 是极值点,因而选项(B)与(D)不正确，而在点 $x=0$ 的邻域内：当 $x<0$ 时， $\begin{array}{r}{f(x)=-x\left(1-x\right)=x^{2}-x\,,f^{\prime}(x\,)=2x-1,f^{\prime\prime}(x\,)=2>0\,;}\end{array}$ 当 $x>0$ 时， $,f(x\,)=x\,(1-x\,)=x-x^{\,2},f^{\prime}(x\,)=1-2x\,,f^{\prime\prime}(x\,)=-2<0.$ 所以点（0,0）是曲线 $y=f(x\,)$ 的拐点.选项(C)正确.  

[注】 由例 5. 10 可看出,不可导点可同时为极值点和拐点.  

例 5. 11设 $f(x)$ 与 $h\left(x\right)$ 在 $\boldsymbol{x}=\boldsymbol{x}_{\,0}$ 的某邻域内可导， $F(x)=\!\!\int_{x_{0}}^{x}f(t)\mathrm{d}t\,,H(x)=$  $\int_{x_{0}}^{x}h\left(t\right)\mathsf{d}t$ ，又设 $f(x_{0})h\left(x_{0}\right)<0,G(x)=F(x)H(x)$ ,则（)  

$(\mathbf{A})x=x_{0}$ 是 $G(x)$ 的极大值点， $(x_{\mathit{\Pi}_{0}},G(x_{\mathit{\Pi}_{0}}))$ 是 $G(x)$ 的拐点 $(\boldsymbol{\mathrm{B}})\boldsymbol{x}=\boldsymbol{x}_{\u{0}}$ 是 $G(x)$ 的极小值点， $(x_{\mathit{\Pi}_{0}},G(x_{\mathit{\Pi}_{0}}))$ 是 $G(x)$ 的拐点 $(\boldsymbol{\mathrm{C}})\boldsymbol{x}=\boldsymbol{x}_{0}$ 是 $G(x)$ 的极大值点， $(\boldsymbol{x}_{\mathit{\Pi}_{0}},\boldsymbol{G}(\boldsymbol{x}_{\mathit{\Pi}_{0}}))$ 不是 $G(x)$ 的拐点 $(\operatorname{D})x=x_{0}$ 是 $G(x)$ 的极小值点， $(x_{\mathit{\Pi}_{0}},G(x_{\mathit{\Pi}_{0}}))$ ）不是 $G(x)$ 的拐点  

【解】应选(C).  

$G(x)=\!F(x)H(x),\!G^{\prime}(x)=\!F^{\prime}(x)H(x)+F(x)H^{\prime}(x),\!G^{\prime}(x_{0})=0.$ $G^{\prime\prime}(x\,)=F^{\prime\prime}(x\,)H(x\,)+2F^{\prime}(x\,)H^{\prime}(x\,)+F(x\,)H^{\prime\prime}(x\,)\,,$ $G^{\prime\prime}(x_{\,0})=2F^{\prime}(x_{\,0})H^{\prime}(x_{\,0})=2f(x_{\,0})h\,(x_{\,0})<0.$  

故 ${\boldsymbol{x}}={\boldsymbol{x}}_{\mathit{0}}$ 是 $G(x)$ 的极大值点.由“二4. $\textcircled{1}$ ”结论知，曲线的可导点不同时为极值点和拐点，故 $(x_{\mathit{\Pi}_{0}},G(x_{\mathit{\Pi}_{0}}))$ 不是 $G(x)$ 的拐点.故选(C).  

例5.12曲线 $y=(x-1)(x-2)^{2}(x-3)^{3}(x-4)^{4}$ 的一个拐点是((A)(1,0)(B)(2,0)(C)(3,0)(D)(4,0)  

【解】应选(C).  

令 $y=f(x\,)=(x-3)^{3}(x-1)(x-2)^{2}(x-4)^{4}=(x-3)^{3}g(x\,)\,,$ 显然 $g\left(3\right)\neq0$ ,且 $n=3$ 是奇数，由“二4. $\circledcirc$ ”可知，点(3,0）是 $f(x)$ 的一个拐点，故选(C).  
【注](1) 由“二 4. $\textcircled{3}$ ”可知， $k_{1}=1,k_{2}=2,k_{3}=1$ ，故 $_{y}=f(\boldsymbol{x})$ 的拐点个数为 $1+2\times2+3\times$ $1-2=6$  

(2）本题的常规解法是：因为 $x=3$ 是方程 $(x-1)(x-2)^{2}(x-3)^{3}(x-4)^{4}=0$ 的三重根，所以它是方程 $y^{\prime\prime}\!=\!0$ 的单根，从而函数 $y=(x-1)(x-2)^{2}(x-3)^{3}(x-4)^{4}$ 的二阶导数在点 $_{x=3}$ 的两侧附近改变正负号,故点(3,0) 是曲线 $y=(x-1)(x-2)^{2}(x-3)^{3}(x-4)^{4}$ 的一个拐点.  

例 5. 13曲线 $f(x)=(x-1)\,^{2}\,(x-3)\,^{3}$ 的拐点个数为(）  

(A)0 (B)1 (C)2 (D)3  

【解】应选(D).  

由“二4. $\textcircled{3}$ ”可知， $k_{1}=0\,,k_{2}=1\,,k_{3}=1$ ,则拐点个数为 $k_{1}+2k_{2}+3k_{3}-2=3$  

【注】（1）本题的常规解法是：由  

$$
\begin{array}{c}{{f^{\prime}(x)=2\left(x\,-1\right)\,\left(x\,-3\right){}^{3}+3\left(x\,-1\right){}^{2}\left(x\,-3\right){}^{2}}}\\ {{{}}}\\ {{=\left(x\,-1\right)\,\left(x\,-3\right){}^{2}\left(5x\,-9\right)\,,}}\end{array}
$$  

易知 $f^{\prime\prime}(x)$ 中必含一次因式 $x\mathrm{~-~}3.$ 另由 $f^{\prime}(1)=f^{\prime}\left({\frac{9}{5}}\right)=f^{\prime}(3)=0$ ,知必存在 $x_{\mathrm{~1~}}\in$  $\left(1,\frac{9}{5}\right),x_{2}\in\left(\frac{9}{5},3\right)$ ，使得 $f^{\prime\prime}(x_{1})=f^{\prime\prime}(x_{2})=0$ ,故可令  

$$
f^{\prime\prime}(x)=k(x-x_{1})(x-x_{2})(x-3)\,,
$$  

其中 $\pmb{k}$ 是不为 0 的常数,由于 $f^{\prime\prime}(x)$ 在 $x=x_{\mathrm{~l~}},x=x_{\mathrm{~2~}},x=3$ 两侧都异号,因此该曲线共有3 个拐点。  

（2）曲线 $y=(x-1)^{2}(x-3)^{2}$ 的极值点个数与拐点个数分别为（  

(A)3,2(B)2,3(C)3,4(D)4,3  

解应选(A).  

由“二 4. $\textcircled{3}$ ”可知 $,k_{1}=0,k_{2}=2,k_{3}=0$ ,于是极值点个数为 $0+2\times2+0-1\,{=}\,3$ ,拐点个数为 $0+2\times2+3\times0-2=2.$ 可直接得出答案.  

# 5.渐近线  

# （1）铅直渐近线.  

若$\operatorname*{lim}_{x\to x_{0}^{+}}f(x)=\infty.$ （或 $\operatorname*{lim}_{x\to x_{0}^{-}}f(x)=\infty)$ ，则 $x=x$ 。为一条铅直渐近线.  

【注】此处的 $\scriptstyle{\mathcal{x}}_{0}$ 一般是函数的无定义点或定义区间的端点。  

# (2)水平渐近线.  

若 $\operatorname*{lim}_{x\to+\infty}f(x)=y_{1}$ ，则 ${\mathfrak{y}}={\mathfrak{y}}_{1}$ 为一条水平渐近线；  
若 $\operatorname*{lim}_{x\to-\infty}f(x)=y_{2}$ ，则 ${\boldsymbol{y}}={\boldsymbol{y}}_{2}$ 为一条水平渐近线；  
若$\operatorname*{lim}_{x\to+\infty}f(x)=\operatorname*{lim}_{x\to-\infty}f(x)=y_{0}$ ，则 ${\mathfrak{y}}={\mathfrak{y}}_{\mathfrak{o}}$ 为一条水平渐近线.  

# (3) 斜渐近线.  

若 $\operatorname*{lim}_{x\to+\infty}{\frac{f(x)}{x}}\!=\!k_{1}\neq0\,,\operatorname*{lim}_{x\to+\infty}\left[f(x)-k_{1}x\right]\!=\!b_{1}$ ,则 $y=k_{1}x+b_{1}$ 是曲线 $_y=f(x)$ 的一条斜渐近线；  

若 $\operatorname*{lim}_{x\to-\infty}{\frac{f(x)}{x}}\!=\!b_{2}\neq0\,,\operatorname*{lim}_{x\to-\infty}\left[f(x)-k_{2}x\right]\!=\!b_{2}$ ，则 $y=k_{2}x+b_{2}$ 是曲线 $_{y}=f(\boldsymbol{x}\,)$ 的一条斜渐近线；  

若 $\operatorname*{lim}_{\rightarrow+\infty}\frac{f(x)}{x}=\operatorname*{lim}_{x\rightarrow-\infty}\frac{f(x)}{x}=\;k\neq0,\operatorname*{lim}_{x\rightarrow+\infty}\left[f(x)-k x\right]=\operatorname*{lim}_{x\rightarrow-\infty}\left[f(x)-k x\right]=\;b,$ 则 $_y=$  $k x+b$ 是曲线 $_{y}=f(x)$ 的一条斜渐近线.  

例 5. 14设 $f(x)$ 在 $(0,+\infty)$ 内可导，且 $f(1)=1,2x f^{\prime}(x)+f(x)+3x=0$ ，求曲线 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 的渐近线.  

【解】由 $2x f^{\prime}(x)+f(x)+3x=0$ ,得一阶线性微分方程 $f^{\prime}(x)+{\frac{1}{2x}}f(x)=-{\frac{3}{2}}$ ，解得  

$$
f(x\,)=\mathrm{e}^{-\!\int_{z}^{\frac{1}{2\pi}\mathrm{d}x}\,\left[\int\left(-\,\frac{3}{2}\right)\,\mathrm{e}^{\int_{z}^{\frac{1}{2x}\mathrm{d}x}\,}\mathrm{d}x\,+\,C\right]\,=\frac{1}{\sqrt{x}}(-\,x^{\frac{3}{2}}+C\,)\;,
$$  

又$f(1)=1$ ，则 $C=2.$ 故  

$$
f(x)=\frac{2-x^{\frac{3}{2}}}{\sqrt{x}}.
$$  

因为 $\operatorname*{lim}_{x\to0^{+}}f(x)=\operatorname*{lim}_{x\to0^{+}}{\frac{2-x^{\frac{3}{2}}}{\sqrt{x}}}=+\infty$ ，故 $x=0$ 是曲线 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 的一条铅直渐近线；又  

$$
\operatorname*{lim}_{x\to+\infty}{\frac{f(x\,)}{x}}=\operatorname*{lim}_{x\to+\infty}{\frac{2-x^{\frac{3}{2}}}{x}}=\operatorname*{lim}_{x\to+\infty}{\frac{2-x^{\frac{3}{2}}}{x{\sqrt{x}}}}=-1,
$$  

$$
\operatorname*{lim}_{x\to+\infty}\left[f(x)-(-x\,)\right]=\operatorname*{lim}_{x\to+\infty}\left({\frac{2-x^{\,{\frac{3}{2}}}}{\sqrt{x}}}+x\right)=\operatorname*{lim}_{x\to+\infty}{\frac{2-x^{\,{\frac{3}{2}}}+x^{\,{\frac{3}{2}}}}{\sqrt{x}}}=0\,,
$$  

故 $y=-x$ 是曲线 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 的一条斜渐近线.  

# 6.最值(值域)  

(1）求区间 $[a,b]$ 上连续函数 $f(x)$ 的最大值 $M$ 和最小值 $_m$  $\textcircled{1}$ 求出 $f(x)$ 在 $(a,b)$ 内的可疑点一—驻点与不可导点，并求出这些可疑点处的函数值； $\circledcirc$ 求出端点处的函数值 $f(\alpha)$ 和 $f(b)$  

$\textcircled{3}$ 比较以上所求得的所有函数值，其中最大者为 $f(x)$ 在 $[a,b]$ 上的最大值 $M$ ,最小者为 $f(x)$ 在 $[a,b]$ 上的最小值 $m$  
【注】有时这类问题也可命制为“求连续函数 $f(x)$ 在区间 $[a,b]$ 上的值域 $[m\,,M]^{\,\ast}$ （2）求区间 $(a\,,b\,)$ 内连续函数 $f(x)$ 的最值或者取值范围.  

$\textcircled{1}$ 求出 $f(x)$ 在 $(a,b)$ 内的可疑点一—驻点与不可导点，并求出这些可疑点处的函数值；$\circledcirc$ 求$(a\,,b\,)$ 两端的单侧极限：若 $a\cdot b$ 为有限常数，则求 $\operatorname*{lim}_{r\to a^{+}}f(x)$ 与$\operatorname{lim}_{..}f(x)$ ;若 $^{a}$ 为一∞， $.r-b^{-}$ 则求 $\operatorname*{lim}_{x\to-\infty}f(x)$ ;若 $b$ 为 $+\infty$ ，则求 $\operatorname*{lim}_{x\to+\infty}f(x)$ .记以上所求左端极限为 $A$ ,右端极限为 $B$  

$\textcircled{3}$ 比较 $\textcircled{1}$ ， $\textcircled{2}$ 所得结果，确定最值或取值范围.  

【注】(1)这类问题有时没有最大值、最小值.  

(2) 重要结论. 若 $f(x)$ 在 $(\alpha\,,b)$ 内可导且 $x=x_{0}\in(a,b)$ 是 $f(x)$ 在 $(a\,,b\,)$ 内的唯一极值点且为极大(小)值点,则 $\boldsymbol{x}=\boldsymbol{x}_{\mathit{0}}$ 也是 $f(x)$ 在 $(a,b)$ 内的最大(小)值点.  

例 5. 15设 $f^{\prime}(x)$ 在区间[0，4]上连续，曲线 ${\boldsymbol{y}}=f^{\prime}({\boldsymbol{x}}\,)$ 与直线 $\scriptstyle x\;=\;0\,,x\;=\;4\,,y\;=\;0$ 围成如图5-6所示的三个区域，其面积分别为 $S_{1}=3\,,S_{2}=4\,,S_{3}=2$ ，且 $f(0)=1$ ，则 $f(x)$ 在[0，4]上的最大值与最小值分别为（).  

$(\mathrm{~A~})\,2\,,-\,3$ $(\mathrm{~B~})\,4\,,-\,3$ (C)2，—2 $(\mathrm{D})4,-2$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/16d4d8924215e21c49d6fa13473db9a5c3a90ad2a46c50107bbeb8f2af51a921.jpg)  
图5-6  

【解】应选(C).  

由图5-6可知， $f^{\prime}(1)\,{=}\,f^{\prime}(3)\,{=}\,0$ ,即函数 $f(x)$ 在区间（0,4）内有两个驻点 $x=1$ 和 $x=3$ ，故 $f(x)$ 在[0,4］上的最大值和最小值只能在 $f(0),f(1),f(3),f(4)$ 中取得.  

由 $f(0)=1$ ,有  

$$
f(1)=f(0)+\int_{0}^{1}f^{\prime}(x\,)\mathrm{d}x=1+(-\,3)=-\,2\,,
$$  

$$
f(3)=f(1)+\int_{1}^{3}f^{\prime}(x\,)\mathrm{d}x=-\,2+4=2,
$$  

$$
f(4)=f(3)+\int_{3}^{4}f^{\prime}(x)\,\mathrm{d}x=2+(-2)=0.
$$  

故最大值为 $f(3)=2$ ，最小值为 $f(1)=-\,2$ ,应选(C).  

例 5. 16设 ${\boldsymbol{y}}={\boldsymbol{y}}\left({\boldsymbol{x}}\right)$ 满足 $y^{\prime}+y=\mathbf{e}^{-x}$ cos $_{x}$ ，且 $y\left(0\right)=0$ ，求 $y\left(x^{2}\right)$ 的值域.  

解 $y=\mathrm{e}^{-\Bigl\lceil\mathrm{d}x}\,\Bigl(\int\!\mathrm{e}^{\int_{x}}\,\mathrm{e}^{-x}\cos\,x\,\mathrm{d}x+C\Bigr)\!=\!\mathrm{e}^{-x}\,(\sin\,x+C)$ 由 $y\left(0\right)=0$ ,知 $C=0$ 故 $y\left(x\right)=$  $\mathrm{e}^{-x}\sin x$ .于是 $y\left(x^{2}\right)=\mathrm{e}^{-x^{2}}\sin{x^{2}}$ ,其在 $(-\infty,+\infty)$ ）内连续，且为偶函数.令 $x^{2}=t\,,g(t)=$  $\mathrm{e}^{-\imath}\sin\,t\,(t\geq0)$ ，则 $g\left(t\right)$ 的值域与 $y\left(x^{2}\right)$ 的值域相同.  

因为 $g^{\prime}(t)=\mathrm{e}^{-t}\,(\cos\,t-\sin\,t$ ），故 $g\left(t\right)$ 的驻点为 $t_{k}=k\,\pi+{\frac{\pi}{4}}(k=0\,,1\,,2\,,\cdots)$ ,于是  

$$
g\left(t_{k}\right)=\mathrm{e}^{-\left(k\pi+\frac{\pi}{4}\right)}\,\sin\!\left(k\,\pi+\frac{\pi}{4}\right)\!=\!\left(-\,1\right)^{k}\,\cdot\frac{\sqrt{2}}{2}\cdot\mathrm{e}^{-\left(k\pi+\frac{\pi}{4}\right)}\,\,,
$$  
其中 $g\left(t_{0}\right),g\left(t_{2}\right),g\left(t_{4}\right),\cdots$ 为正数，最大值为 $g\left(t_{\circ}\right)=\frac{\sqrt{2}}{2}\mathrm{e}^{-\frac{\pi}{4}};g\left(t_{1}\right),g\left(t_{3}\right),\cdots$ 为负数，最小值为 $g\left(t_{1}\right)=-\frac{\sqrt{2}}{2}\mathrm{e}^{-\frac{5}{4}\pi}$  

故 $g\left(t\right)$ 的值域为 $\left[-{\frac{\sqrt{2}}{2}}\mathrm{e}^{-{\frac{5}{4}}\pi},{\frac{\sqrt{2}}{2}}\mathrm{e}^{-{\frac{\pi}{4}}}\right]$ 从而函数 $y\left(x^{2}\right)$ 的值域为 $\left[-{\frac{\sqrt{2}}{2}}\mathrm{e}^{-{\frac{5}{4}}\pi},{\frac{\sqrt{2}}{2}}\mathrm{e}^{-{\frac{\pi}{4}}}\right].$  

【注】 定义在某区间上的连续函数 $_{y}(x)$ ,若有最大值 $M$ 和最小值 $_m$ ，则 $_{y}(x)$ 的值域是 $[m$ ，$M]$  

7.曲率与曲率半径（仅数学一、数学二）  

曲率 $k=\frac{\mid y^{\prime\prime}\mid}{[1+(y^{\prime})^{2}]^{\frac{3}{2}}}$ ，曲率半径 $R=\frac{1}{k}$  

例 5. 17设 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 是由方程 $\int_{0}^{y}\mathrm{e}^{-t^{2}}\,\mathrm{d}t=2y-\ln(1+x\,)$ 所确定的二阶可导函数,则曲线 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 在点（0,0）处的曲率半径为  

【解】应填 $2\sqrt{2}$ ：由例4.4知 $\left.f^{\prime}(0)=y^{\prime}\ \right|_{x=0}=1,f^{\prime\prime}(0)=y^{\prime\prime}\ \right|_{x=0}=-1.$ 故曲率 $k=\frac{\mid y^{\prime\prime}\mid}{\left[1+(y^{\prime})^{2}\right]^{\frac{3}{2}}}=\frac{1}{2\sqrt{2}}$ 曲率半径 $R={\frac{1}{k}}=2{\sqrt{2}}$  
# 第6讲  

# 一元函数微分学的应用 ( 二)中值定理、微分等式与微分不等式  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/6a147911185781a9ab1ab1382cccf74795cb5bd8dd9a8b7ed68c4a0071cc4465.jpg)  

# 一中值定理  

设$f(x)$ 在$[a,b]$ 上连续,则 定理1（有界与最值定理） $m\leqslant f(x)\leqslant M$ ,其中 $m\,,M$ 分别为 $f(x)$ 在 $[a,b]$  
# 第6讲 一元函数微分学的应用(二)一—中值定理、微分等式与微分不等式  

上的最小值与最大值.  

定理2（介值定理）当 $m\leqslant\mu\leqslant M$ 时,存在 $\pmb{\xi}\in[a,b]$ ,使得 $f(\pmb{\xi})=\pmb{\mu}$ ：  

定理3（平均值定理）当 $a<x_{1}<x_{2}<\dots<x_{n}<b$ 时，在 $[x_{1},x_{n}]$ 上至少存在一点 $\boldsymbol{\xi}$ ，使得  

$$
f(\pmb{\xi})=\frac{f(x_{\mathrm{~l~}})+f(x_{\mathrm{~2~}})+\cdots+f(x_{\mathrm{~\!n~}})}{n}.
$$  

定理4（零点定理）当 $f(a)\cdot f(b)<0$ 时,存在 $\xi\in(a,b)$ ,使得 $f(\xi)=0$  

定理5（费马定理）设 $f(x)$ 在点 $\boldsymbol{x}_{\,0}$ 处满足 $\bigoplus\limits_{k\in\mathcal{B}}\frac{\pi}{4}\pi+\beta<1$ 则 $f^{\prime}(x_{\circ})=0$  

定理6（罗尔定理）设 $f(x)$ 满足 $\left<\mathcal{D}(a,b)\right>$ 内可导，则存在 $\xi\in(a\,,b)$ ，使得 $f^{\prime}(\pmb{\xi})=0$  

$$
\left(\mathcal{\ B}_{f}(a)=f(b)\right)
$$  

定理7（拉格朗日中值定理）设 $f(x)$ 满足 $\begin{array}{r}{\left\langle\underline{{\boldsymbol{\osl}}}\left[a,b\right]\underline{{\boldsymbol{\vdash}}}\right\rangle\underline{{\boldsymbol{\sharp}}}\frac{\mathcal{L}}{\mathcal{K}}}\\ {\mathcal{Q}(a,b)\not\approx\overline{{\boldsymbol{\sharp}}}\frac{\log}{\mathcal{Y}}}\end{array}$ 则存在 $\xi\in(a,b)$ ，使得  

$$
f(b)-f(a\,)=f^{\prime}(\,\pm\,)(b-a\,)\,,
$$  

或者写成  

$$
f^{\prime}(\pmb{\xi})=\frac{f(b)-f(a)}{b-a}.
$$  

[注] 若 $\xi\in(a,b)$  $\theta\!=\!\!\frac{\xi-\alpha}{b-\alpha}$ 司 $\xi\!=\!a+\theta(b-a)\,,0\!<\!\theta\!<\!1$ 于是拉格明 日中值定理的变体形式为 $f(b)-f(a)=f^{\prime}\Bigl[a+\theta(b-a)\Bigr](b-a).$  

定理8（柯西中值定理）设 $f(x\,),g(x\,)$ 满足 $\}\textcircled{\cdot}(a,b)$ 内可导，则存在 $\xi\in(a,b)$ ，使得  

$$
\frac{f(b)-f(a)}{g(b)-g(a)}\!=\!\frac{f^{\prime}(\mathfrak{F})}{g^{\prime}(\mathfrak{F})}.
$$  

定理9 (泰勒公式)  

→此公式适用于区间[a,]，常在证明题中使用，如证不等式  

(1）带拉格朗日余项的 $_n$ 阶泰勒公式.  

设函数 $f(x)$ 在含有点 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 的区间 $(a,b)$ 内有 $n+1$ 阶导数,则对于 $x\in[a,b]$ ,有f(x)= $f(x_{0})+f^{\prime}(x_{0})(x-x_{0})+\cdots+\frac{1}{n!}f^{(n)}(x_{0})(x-x_{0})^{n}+\frac{f^{(n+1)}(\hat{\star})}{(n+1)!}(x-x_{0})^{n-1}\,.$ 其中 $\boldsymbol{\xi}$ 介于 $x\cdot x_{\mathit{\Omega}_{0}}$ 之间.  

注】 泰勒公式(一阶为例) 的变体形式为  

$$
)=f(x_{0})+f^{\prime}(x_{0})(x-x_{0})+\frac{f^{\prime}[x_{0}+\theta(x-x_{0})]}{2}(x-x_{0})^{2}(x\neq x_{0}),0<\theta<\pi.
$$  

(2)带佩亚诺余项的 $_n$ 阶泰勒公式，此公武仅适用于 $x=x_{0}$ 及其找的用子新定极 $x=x_{0}$ 处的著设 $f(x)$ 在点 $\boldsymbol{\mathscr{x}}_{\flat}\,_{0}$ 处 $_n$ 阶可导，则存在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 的一个邻域，对于该邻域中的任一点 $_{x}$ ，有  

$$
f(x)=f(x_{0})+f^{\prime}(x_{0})(x-x_{0})+{\frac{1}{2!}}f^{\prime\prime}(x_{0})(x-x_{0})^{2}+\cdots+{\frac{1}{n!}}f^{(n)}(x_{0})(x-x_{0})^{2}
$$  
# 比亨高等数学18涉  

$$
o\left(\,(\,x\,-\,x\,_{0}\,)^{\,n}\,\right).
$$  

定理10（积分中值定理）设 $f(x)$ 在 $[a,b]$ 上连续，则存在 $\xi\in(a,b)$ ，使得  

$$
\int_{a}^{b}f(x\,)\mathrm{d}x=f(\xi)(b-a\,).
$$  

【注】“推广的积分中值定理”：  

设 $f(x),g(x)$ 在 $[a,b]$ 上连续,且 $_{g}(x)$ 在 $[a,b]$ 上不变号,则存在 $\xi\in(a,b)$ ，使得  

$$
\int_{a}^{b}f(x\,)g(x\,)\,\mathrm{d}x=f(\xi)\!\int_{a}^{b}g(x\,)\,\mathrm{d}x\,.
$$  

证若 $g\left(x\right)\equiv0$ ,结论显然成立；  

若 $g\left(x\right)\not\equiv0$ ，由于 $_{g}(x)$ 在 $[a,b]$ 上不变号,不妨设 $g\left(x\right)>0.$ 令  

$$
F(x)=\!\!\int_{a}^{x}f(t)g(t)\mathrm{d}t\,,\!G(x)\!=\!\!\int_{a}^{x}\!\!g(t)\mathrm{d}t\,,
$$  

$[a,b]$ 上应用柯西中值定理, 有 $\frac{F(b)-F(a)}{G(b)-G(a)}\!=\!\frac{F^{\prime}(\pmb{\xi})}{G^{\prime}(\pmb{\xi})}$ 即  

$$
\frac{\displaystyle\int_{a}^{b}f(x)g(x)\,\mathrm{d}x-0}{\displaystyle\int_{a}^{b}g(x)\,\mathrm{d}x-0}=\frac{f(\xi)g(\xi)}{g(\xi)},
$$  

$$
\int_{a}^{b}f(x\,)g(x\,)\,\mathrm{d}x=f(\xi)\!\!\int_{a}^{b}\!g(x\,)\,\mathrm{d}x\,,\hat{\varepsilon}\,\in\,(a\,,b)\,,
$$  

其中 $\int_{a}^{b}g(x)\,\mathrm{d}x>0.$ 同理可得 $g\left(x\right)<0$ 时也成立,得证.  

以下所讲内容均应满足诸定理成立的条件,这均为命题者所考虑，为突出重点，所有条件均默认成立.  

# 1.确定区间  

在数轴上标出所有可能用到的点，确定区间.  

# 2.确定辅助函数  

（1）简单情形：题设 $f(x)$ 即为辅助函数(研究对象）.  

# (2) 复杂情形.  

$\textcircled{1}$ 乘积求导公式 $({u\boldsymbol{v}})^{\prime}={u^{\prime}\boldsymbol{v}}+{u\boldsymbol{v}^{\prime}}$ 的逆用.   
a. $\left[f(x\,)\,f(x\,)\right]^{\prime}=\left[f^{2}(x\,)\right]^{\prime}=2f(x\,)\,\bullet\,f^{\prime}(x\,).$   
见到 $f(x)f^{\prime}(x)$ ，令 $F(x)=f^{2}(x)$   
b$[f(x)\bullet f^{\prime}(x)]^{\prime}\,{=}\,[f^{\prime}(x)]^{2}+f(x)f^{\prime\prime}(x).$   
见到 $[f^{\prime}(x)]^{2}+f(x)f^{\prime\prime}(x)$ ，令 $F(x)=f(x)f^{\prime}(x)$   
$\big[f(x)\,\mathrm{e}^{\varphi(x)}\big]^{\prime}=f^{\prime}(x)\,\mathrm{e}^{\varphi(x)}+f(x)\,\mathrm{e}^{\varphi(x)}\,\ast\varphi^{\prime}(x)=\big[f^{\prime}(x)+f(x)\varphi^{\prime}(x)\big]\mathrm{e}^{\varphi(x)}.$ 见到 $f^{\prime}(x)+f(x)\varphi^{\prime}(x)$ ，令 $F(x)=f(x)\mathbf{e}^{\varphi(x)}$  
【注】常考以下情形.  

$(1)\varphi(x)\!=\!x\!\Rightarrow$ 见到 $f^{\prime}(x)+f(x)$ ，令 $\boldsymbol{F}(\boldsymbol{x})=f(\boldsymbol{x}\,)\,\mathrm{e}^{\boldsymbol{x}}$  $(2)\varphi(x)\mathop{=}-x\Rightarrow$ 见到 $f^{\prime}(x)-f(x)$ ，令 $F(x)=f(x){\mathrm{e}}^{-x}$  $(3)\varphi(x)\!=\!k x\!\Rightarrow$ 见到 $f^{\prime}(x)+k f(x)$ ，令 $F(x)=f(x)\mathbf{e}^{k x}$ (4) $(u v)^{\prime\prime}\!=\!u^{\prime\prime}v+2u^{\prime}v^{\prime}+u v^{\prime\prime}$ 亦有可能考到.  

$\circledcirc$ 商的求导公式 ${\left({\frac{u}{v}}\right)}^{\prime}={\frac{u^{\prime}v-u v^{\prime}}{v^{2}}}$ 的逆用.  
a $\left[{\frac{f(x)}{x}}\right]^{\prime}={\frac{f^{\prime}(x)x-f(x)}{x^{2}}}.$   
见到 $f^{\prime}(x)x-f(x),x\neq0$ 令 $F(x)={\frac{f(x)}{x}}$   
b. $\left[{\frac{f^{\prime}(x\,)}{f(x\,)}}\right]^{\prime}={\frac{f^{\prime\prime}(x\,)\,f(x\,)-\left[f^{\prime}(x\,)\right]^{2}}{f^{2}(x\,)}}.$   
见到 $f^{\prime\prime}(x)\,f(x\,)-\left[f^{\prime}(x\,)\right]^{2},f(x\,)\neq0$ ，令 $F(x)={\frac{f^{\prime}(x)}{f(x)}}$   
 ${\mathfrak{c.}}[\ln\,f(x\,)]^{\prime}={\frac{f^{\prime}(x\,)}{f(x\,)}}$ ，故 ${\big[}\ln\,f(x\,){\big]}^{\prime\prime}={\Bigg[}{\frac{f^{\prime}(x\,)}{f(x\,)}}{\Bigg]}^{\prime}={\frac{f^{\prime\prime}(x\,)\,f(x\,)-{\big[}\,f^{\prime}(x\,){\big]}^{2}}{f^{2}(x\,)}}.$ 见到 $f^{\prime\prime}(x\,)\,f(x\,)-\left[f^{\prime}(x\,)\right]^{2},f(x\,)\neq0$ ,亦可考虑令 $F(x)=\ln\,f(x)$ $\textcircled{3}$ 见到“ $\int_{a}^{b}f(x\,)\,\mathrm{d}x\,^{,\ast}$ 或“ $f(x)$ 在$[a,b]$ 上连续”,可令 $F(x)=\!\int_{a}^{x}f(t)\,\mathrm{d}t\,.$  $\circledast$ 题设给出“ $F(x)^{\,,}$ 或“ $\mathbf{\nabla}_{F}(a\mathbf{\nabla})^{\bullet}$ ，亦可作为提示，令 $F(x\,)$ 为辅助函数.  

# 3.确定使用的定理  

# (1)零点定理.  

常用于找 $f(c\,)=0$ （由 $f(a)>0,f(b)<0$ ，则 $f(c\,)=0)$  

(2)介值定理.  

常用于找 $f(c\,)=\mu$ （由 $f(a\,)=A\,,\,f(b\,)=B\,,A<\mu<B$ ，则 $f(c\,)=\mu$  

(3)费马定理.  

常用于证 $f^{\prime}(\pmb{\xi})\!=\!0$ （若 $f(x)$ 在区间 $I$ 上有最值点 $\boldsymbol{\xi}$ ，并且此最值点 $\boldsymbol{\xi}$ 不是区间 $I$ 的端点而是 $I$ 内部的点，那么点 $\boldsymbol{\xi}$ 必是 $f(x)$ 的一个极值点，且当在点 $\boldsymbol{\xi}$ 处可导时，由费马定理，有 $f^{\prime}(\pmb{\xi})=0)$  

# (4) 罗尔定理.  

常用于  
$\textcircled{1}$ 证$F^{\prime}(\xi)=0$   
$\circledcirc$ 证$F^{(n)}(\xi)=0\,,n\geqslant2.$  

(5）拉格朗日中值定理常用于$\textcircled{1}$ 题设中有 $f$ 与$f^{\prime}$ 的关系或“ $f(b)-f(a)^{*}$ $\circledcirc$ 证$F^{\prime}(\xi)>$ （或 $<\,\!)0$ $\textcircled{3}$ 证$F^{(n)}(\xi)>$ （或 $<\!)0,n\geq2$ $\circled{4}$ 证$F[f^{\prime}(\eta),f^{\prime}(\tau)]\!=\!0.$  $\textcircled{5}f^{\prime}(x)$ 的正负可考到单调性.  
# (6)泰勒公式.  

常用于  

$\textcircled{1}$ 题设中有 $f$ 与 $f^{(n)}$ 的关系， $n\geqslant2$ $\circledcirc$ 证$F^{(n)}(\xi)>(<$ 或$\Rightarrow0\,,n\geqslant2$  $\textcircled{3}f^{\prime\prime}(x)$ 的正负可考到凹凸性.  

# （7）柯西中值定理.  

常用于  

$\textcircled{1}$ 两个具体函数所满足的式子.   
 $\circledcirc$ 一个具体函数与一个抽象函数所满足的式子.  

$\textcircled{3}$ 与拉格朗日中值定理综合.  

# 4.常见的关键点总结  

(1）用题设告之，如 $f(a)\,{=}\,0\,,f^{\prime\prime}(x)>0$ 等。  

# （2）用极限（连续、可导、保号性，算极限）.  

$\textcircled{1}$ 若$f(x)$ 在$\boldsymbol{x}=\boldsymbol{x}_{\mathit{0}}$ 处连续且 $\operatorname*{lim}_{x\to x_{0}}{\frac{f(x)}{x-x_{0}}}=A$ ，则 $f(x_{\,0})\,{=}\,0,f^{\prime}(x_{\,0})\,{=}\,A$ $\circledcirc$ 若$\operatorname*{lim}_{x\to x_{0}^{+}}\frac{f(x)}{x-x_{0}}<0$ ，则 $\exists\,\delta>0$ ,使得 $\forall\;x\;\in\;(x_{\;0}\,,x_{\;0}+\delta\,)$ 时,有 $f(x)<0$ $\textcircled{3}$ 考虑等式两边取极限.  

# (3）用零点、介值定理  

$\textcircled{1}$ 若 $f(a)>0\,,f(b)<0{\Rightarrow}f(c)=0.$  $\circledcirc$ 若 $f(a\,)=A\,,\,f(b)=B\Rightarrow f(c\,)=\mu\,,A\,<\mu<B.$  

（4）用积分（中值定理、保号性、原函数定义，算积分）.  

$\textcircled{1}$ 如$\int_{a}^{b}f(x\,)\,\mathrm{d}x=A$ ，则 $f(\xi)=\frac{\displaystyle\int_{a}^{b}f(x)\mathrm{d}x}{b-a}=\frac{A}{b-a}.$   
$\circledcirc$ 保号性：a.若 $f(x)\geqslant0$ 且不恒等于零， $\alpha<b$ ，则 $\int_{a}^{b}f(x)\,\mathrm{d}x>0$ b.若 $f\!\left(\boldsymbol{x}\,\right)\geq g\!\left(\boldsymbol{x}\,\right)$ ,且不恒等， $a<b$ ,则 $\int_{a}^{b}f(x\mathbf{\nabla})\mathrm{d}x>\int_{a}^{b}g(x\mathbf{\nabla})\mathrm{d}x$ $\circled{3}F(x)=\int_{a}^{x}f(t)\mathrm{d}t.$   
$\circled{4}$ 考虑等式两边算积分.  

# （5）用费马定理.  

可导极值点处 $\Rightarrow f^{\prime}(x_{0})=0$  
# (6）用奇偶性质.  

$f(x)$ 是奇函数且在原点有定义 $\Rightarrow f(0)=0$  $f(x)$ 是可导的偶函数 $\Rightarrow f^{\prime}(0)=0$  

# （7）用几何条件.  

$\textcircled{1}f(x)$ 与 $g\left(x\right)$ 交于点 $^a$ ，则 $F(a)=f(a)-g(a)=0$ $\mathcal{O}f(x)$ 与$g\left(x\right)$ 在点 $^{\,a}$ 处有公切线，则 $F^{\prime}(a)=f^{\prime}(a)-g^{\prime}(a)=0$  $\textcircled{3}f(x)$ 与 $_{g}(\boldsymbol{x})$ 存在相等的最大值.  

# (8）用行列式条件.  

如 $f(x\,)=\left|\!\!\begin{array}{c c c}{{1}}&{{x}}&{{4}}\\ {{}}&{{x+1}}&{{7}}\\ {{3}}&{{3x}}&{{9}}\end{array}\!\!\right|,$ 则 $f(1)=0$  

例 6. 1设函数 $f(x)=x\int_{1}^{0}\mathbf{e}^{-x^{2}t^{2}}\,\mathrm{d}t$ ，则当 $0<a<x<b$ 时，有（  

$$
\begin{array}{r l r}&{\mathrm{(A)}x f(\ensuremath{\boldsymbol{{x}}})>\ensuremath{\boldsymbol{a}}f(\ensuremath{\boldsymbol{\alpha}})\qquad\qquad\qquad}&{\mathrm{(B)}b f(\ensuremath{\boldsymbol{b}})>\ensuremath{\boldsymbol{x}}f(\ensuremath{\boldsymbol{{x}}})}\\ &{\mathrm{(C)}x f(\ensuremath{\boldsymbol{a}})>\ensuremath{\boldsymbol{a}}f(\ensuremath{\boldsymbol{{x}}})\qquad\qquad\qquad}&{\mathrm{(D)}\ensuremath{\boldsymbol{x}}f(\ensuremath{\boldsymbol{b}})>\ensuremath{\boldsymbol{b}}f(\ensuremath{\boldsymbol{{x}}})}\end{array}
$$  

【解】应选(D).  

由  

$$
f(x\,)=\!\!\int_{1}^{0}\!{\mathrm{e}}^{-(x t)^{2}}\,{\mathrm{d}}(x t)\,{\frac{{\,\widehat{\textbf{\textup{q}}}}\,x t=u}{\,}}\!\!\int_{x}^{0}{\mathrm{e}}^{-u^{2}}\,{\mathrm{d}}u\,,
$$  

得 $f(0)=0\,,f^{\prime}(x)=-\,\mathrm{e}^{-x^{2}}$ ， $f^{\prime\prime}(x\,)=2x\,{\mathrm{e}}^{-x^{2}}$ ，当 $x>0$ 时,有  

$$
f(x)<0,f^{\prime}(x)<0,f^{\prime\prime}(x)>0.
$$  

于是，令 $g(x)=x f(x),x>0$ ，则 $g^{\prime}(x)=f(x)+x f^{\prime}(x)<0,g(x)$ ）单调减少，故  $g(b)<g(x)<g(a)$ ，即 $b f(b)<x f(x)<a f(a)$ ,选项(A),(B）错误.  

，则$\begin{array}{r l}&{h^{\prime}(x)\!=\!\frac{x f^{\prime}(x)-f(x)}{x^{2}}\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\cdot\!\frac{i\xi^{\mu}\hat{\theta}_{1}\hat{\theta}\parallel\!\cdot\!\hat{x}\,\hat{y}_{1}^{\mu}}{\sqrt{\xi}\,\hat{\theta}_{1}\hat{x}}\!\stackrel{_{*}\to\,_{*}\hat{y}_{2}^{\mu}}{\le}}\\ &{\quad\quad\quad\!=\!\frac{x f^{\prime}(x)-\big[f(x)-f(0)\big]}{x^{2}}\!=\!\frac{x f^{\prime}(x)-f^{\prime}(\hat{\xi})\,\cdot\,x}{x^{2}}}\\ &{\quad\quad\quad\quad\!=\!\frac{f^{\prime}(x)-f^{\prime}(\hat{\xi})}{x},}\end{array}$  

其中 $0<\xi<x$ .由 $f^{\prime\prime}(x)>0$ ，知 $f^{\prime}(x)$ 单调增加， $f^{\prime}(x)>f^{\prime}(\xi)$ ，则 $h^{\prime}(x)>0,h(x)$ 单调增加，故 $h\left(a\right)<h\left(x\right)<h\left(b\right)$  ${\frac{f(a)}{a}}<{\frac{f(x)}{x}}<{\frac{f(b)}{b}}$ 也即 $a f(x)>x f(a),x f(b)>$  $b f(x)$ ,选项(C）错误，选(D).  

例6.2设 $f(x)$ 在 $[0,\alpha]$ 上可导,且 $f^{\prime}(x)\geq b>0$ ,则对于命题  

$\textcircled{1}$ 当 $f\left({\frac{a}{4}}\right)\geq0$ 时， $\mid f(x)\mid\geqslant\frac{a b}{2},x\,\in\,\left(\frac{3a}{4},a\right)\,;$  $\circledcirc$ 当 $f\left(\frac{3a}{4}\right)\leqslant0$ 时， $\mid f(x)\,\mid\,\geqslant\frac{a b}{2},x\,\in\,\left(0,\frac{a}{4}\right).$  
# 比亨高等数学18涉  

下列说法正确的是(  

(A) $\textcircled{1}$ 正确， $\circledcirc$ 不正确(B) $\textcircled{1}$ 不正确， $\circledcirc$ 正确(C) $\textcircled{1}\textcircled{2}$ 均正确 (D) $\textcircled{1}\textcircled{2}$ 均不正确  

【解】应选(C).  

由拉格朗日中值定理，有  

$$
f\left(\frac{3a}{4}\right)-f\left(\frac{a}{4}\right)=f^{\prime}(\,\pm\,)\,\cdot\,\left(\frac{3a}{4}-\frac{a}{4}\right)=\frac{a}{2}f^{\prime}(\,\pm\,)\geqslant\frac{a b}{2},\frac{a}{4}<\pm\,<\frac{3a}{4},
$$  

故 $f\!\left({\frac{3a}{4}}\right)\!\geq{\frac{a b}{2}}\!+f\!\left({\frac{a}{4}}\right)$ 当 $f\left({\frac{a}{4}}\right)\geqslant0$ 时， $f\left({\frac{3a}{4}}\right)\geq{\frac{a b}{2}}$ 又 $f^{\prime}(x)\geq b>0,f(x)$ 单调增加，于是当 $x\,\in\,\Bigl(\frac{3a}{4},a\Bigr)$ 时， $\mid f(x\,)\mid=f(x\,)\geqslant f\!\left({\frac{3a}{4}}\right)\geqslant{\frac{a b}{2}}.$  

又 $f\left({\frac{a}{4}}\right)\leqslant f\left({\frac{3a}{4}}\right)-{\frac{a b}{2}}$ ,当 $f\Big(\frac{3a}{4}\Big)\leqslant0$ 时， $f\!\left({\frac{a}{4}}\right)\!\leqslant\!-{\frac{a b}{2}}$ 又 $f(x)$ 单调增加,，于是当 $x\in$ $\left(0\,,{\frac{a}{4}}\right)$ 雞时 $f(x)\leqslant f\!\left({\frac{a}{4}}\right)\leqslant\!\!-{\frac{a b}{2}}$ 即$\mid f(x)\mid\geq{\frac{a b}{2}}.$  

例 6. 3设函数 $f(x)$ 在[0,1]上二阶可导,且 $\int_{0}^{1}f(x)\,\mathrm{d}x=0$ ,则(  

(A)当 $f^{\prime}(x)<0$ 时， $f\!\left({\frac{1}{2}}\right)\!<\!0$ (B)当 $f^{\prime\prime}(x)<0$ 时， $f\!\left({\frac{1}{2}}\right)\!<\!0$ (C)当 $f^{\prime}(x)>0$ 时， $f\!\left({\frac{1}{2}}\right)<0$ (D)当 $f^{\prime\prime}(x)>0$ 时， $f\!\left({\frac{1}{2}}\right)\!<\!0$  

【解】应选(D).  

$f(x)$ 在[0，1]上二阶可导，则由带拉格朗日余项的泰勒公式有  

$$
f(x\,)=f\!\left({\frac{1}{2}}\right)+f^{\prime}\!\left({\frac{1}{2}}\right)\left(x-{\frac{1}{2}}\right)+{\frac{1}{2}}f^{\prime\prime}(\star)\left(x-{\frac{1}{2}}\right)^{2},
$$  

其中 $\boldsymbol{\xi}$ 介于 $_{x}$ 与 $\frac{1}{2}$ 之间.又在[0,1] 上取积分得$\int_{0}^{1}f(x\,)\,\mathrm{d}x=\!\!\int_{0}^{1}\!f\!\left({\frac{1}{2}}\right)\mathrm{d}x\,+\!\int_{0}^{1}\!f^{\prime}\!\left({\frac{1}{2}}\right)\left(x\,-\,{\frac{1}{2}}\right)\mathrm{d}x\,+\frac12\!\left\lceil_{0}^{1}f^{\prime\prime}(\xi)\!\left(x\,-\,{\frac{1}{2}}\right)^{2}\mathrm{d}x\,,$ $0=f\Big(\frac{1}{2}\Big)+f^{\prime}\Big(\frac{1}{2}\Big)\bullet\frac{1}{2}\Big(x-\frac{1}{2}\Big)^{2}\Bigm|_{\L_{0}}^{1}+\frac{1}{2}\Big\{_0^{1}f^{\prime\prime}(\mathfrak{s}\,)\Big(x\,-\frac{1}{2}\Big)^{2}\,\mathrm{d}x\,,$ $f\left({\frac{1}{2}}\right)=-{\frac{1}{2}}{\bigg\lceil}_{0}^{1}{\!f^{\prime\prime}(\,{\pmb\xi}\,)}\left(x\,-\frac{1}{2}\right)^{2}\mathrm{d}x\,.$ 与又经提不和不是外用为此处泌上与有生 $\xi=\xi(x)$  

故当 $f^{\prime\prime}(x\,)>0$ 时，有 $f^{\prime\prime}(\xi)>0$ 则 $f\left({\frac{1}{2}}\right)<0.$ 因此选(D).由和：  

例 6. 4设 $f(x)$ 在[2,4]上一阶可导且 $f^{\prime}(\,x\,)\geq M>0$ ， $f(2)>0$ 证明：  

（1）对任意的 $x\in[3,4]$ ，均有 $f(x\,)>M$ （2)存在 $\xi\in\left(3,4\right)$ ，使得 $f(\xi)>M\cdot\frac{\mathrm{e}^{\xi^{-3}}}{\mathrm{e}-1}$  
# 第6讲 一元函数数分学的应用(二)一中值定理、微分等式与微分不等式  

【证](1)在[2,3]上对 $f(x)$ 应用拉格朗日中值定理,有  

$$
f(3)-f(2)=f^{\prime}(\eta)\geqslant M>0\,,
$$  

其中 $\eta\in(2,3)$ .又 $f(2)>0$ ,故  

$$
f(3)=f(2)+f^{\prime}(\eta)>M.
$$  

又在[2,4]上 $f^{\prime}(x)>0,f(x)$ 单调增加,于是对任意的 $x\in[3,4]$ ,均有 $f(x\,)>M$ (2)令 $F(x)\!=\!\!\int_{3}^{x}f(t)\mathrm{d}t\,,\!G(x)\!=\!\mathbf{e}^{x}$ ,在[3,4]上对 $F(x),G(x)$ 应用柯西中值定理,有  

$$
\frac{F(4)-F(3)}{G(4)-G(3)}\,{=}\frac{F^{\prime}(\{\pmb{\xi}\}}{G^{'}(\{\pmb{\xi}\}}},\pmb{\xi}\,\in\,(3,4)\,,
$$  

即  

$$
\frac{\int_{3}^{4}f(x)\mathrm{d}x}{\mathbf{e}^{3}(\mathbf{e}-1)}\,{=}\,\frac{f(\pmb{\xi})}{\mathbf{e}^{\pmb{\xi}}},\pmb{\xi}\,\in\,(3,4).
$$  

又由(1),  

$$
\int_{3}^{4}f(x\,)\,\mathrm{d}x>\int_{3}^{4}\!M\mathrm{d}x=M\,,
$$  

故$\frac{f(\pmb\xi)}{\mathrm{e}^{\xi}}\!>\frac{M}{\mathrm{e}^{3}(\mathrm{e}-1)}$ ,即 $f(\xi)>M\cdot\frac{\mathrm{e}^{\xi^{-3}}}{\mathrm{e}-1}.$  

主 $\xi\in(3,4)$ ，故 $\frac{\mathrm{e}^{\varepsilon-3}}{\mathrm{e}-1}$ 与 1 的大小关系不确定,不能简单认为(1)成立则(2)必成立.  

6. 5设函数 $f(x)$ 在区间[0,2］上具有三阶导数， $f(0)\!=\!0,f(2)\!=\!2$ ,且  

$$
\operatorname*{lim}_{x\to1}{\frac{f(x)-1}{\ln x}}\!=\!1,
$$  

证明：至少存在一点 $\xi\in(0,2)$ ，使得 $f^{{\boldsymbol{\prime\prime}}{\boldsymbol{\prime}}}({\boldsymbol{\xi}})=0$  

【证】由 $\operatorname*{lim}_{x\to1}{\frac{f(x)-1}{\ln x}}=1$ ,得 $\operatorname*{lim}_{x\to1}[f(x\,)-1]=\operatorname*{lim}_{x\to1}{\frac{f(x\,)-1}{\ln\,x}}\bullet\ln\,x=0$ ，故 $\operatorname*{lim}_{x\to1}f(x)=1$  

又$f(x)$ 在$x=1$ 处连续,得 $f(1)=\operatorname*{lim}_{x\to1}f(x)=1$ ,且  

$$
f^{\prime}(1)=\operatorname*{lim}_{x\to1}{\frac{f(x\,)-f(1)}{x-1}}=\operatorname*{lim}_{x\to1}{\frac{f(x\,)-1}{\ln x}}=1.
$$  

由于函数 $f(x)$ 在[0,2]上具有三阶导数,故由拉格朗日中值定理知,存在 $x_{\mathrm{~l~}}\in~(0,1)$  $x_{\mathit{2}}\in(1,2)$ ，使得  

$$
f^{\prime}(x_{1})=\frac{f(1)-f(0)}{1-0}=\frac{1-0}{1-0}=1,f^{\prime}(x_{2})=\frac{f(2)-f(1)}{2-1}=\frac{2-1}{2-1}=1.
$$  

由罗尔定理知,存在 $\pmb{\xi}_{1}\,\in\,(x_{1}\,,1)\,,\pmb{\xi}_{2}\,\in\,(1\,,x_{2}\,)$ ，使得 $f^{\prime\prime}(\xi_{1})=f^{\prime\prime}(\xi_{2})=0.$ ，再由罗尔定理知,存在 $\pmb{\xi}\in(\pmb{\xi}_{1},\pmb{\xi}_{2})\subset(0,2)$ ，使得 $f^{\prime\prime}(\pmb{\xi})=0$  

例 6. 6设函数 $f(x)$ 在[－2,2]上二阶可导且 $|\ f(x\ )\ |\leqslant1$ ，又  
# 比亨高等数学18讲  

${\frac{1}{2}}\bigl[f^{\prime}(0)\bigr]^{2}+\bigl[f(0)\bigr]^{3}>{\frac{3}{2}},$  

证明：存在 $\xi\in(-2,2)$ ，使得 $f^{\prime\prime}({\mathfrak{s}}\,)+3[f({\mathfrak{s}}\,)]^{2}=0$  

【证】构造函数 $F(x)\!=\!\frac{1}{2}\!\left[f^{\prime}(x\,)\right]^{2}+\left[f(x\,)\right]^{3}$ ,则需证存在 $\xi\in(-2,2)$ ，使得 $F^{\prime}(\xi)\!=\!0$ ，$f^{\prime}(\pmb{\xi})\neq0.$  

根据拉格朗日中值定理，存在 $\alpha\,\in\,(-\,2,0)$ ，使得  

$$
\mid f^{\prime}(\alpha)\mid=\frac{\mid f(0)-f(-2)\mid}{0-(-2)}\leqslant\frac{\mid f(0)\mid+\mid f(-2)\mid}{2}\leqslant\frac{1+1}{2}\!=\!1.
$$  

于是， $F(\alpha)=\frac{1}{2}[f^{\prime}(\alpha)]^{2}+[f(\alpha)]^{3}\leqslant\frac{1}{2}+1=\frac{3}{2}.$ 同理，存在 $\beta\in(0,2)$ ，使得 $|\ f^{\prime}(\beta)\ |\!=\!\frac{\mid f(2)-f(0)\mid}{2}\!\leqslant\!1.$ 于是， $F(\beta)=\frac{1}{2}\big[f^{\prime}(\beta)\big]^{2}+\big[f(\beta)\big]^{3}\leqslant\frac{1}{2}+1=\frac{3}{2}.$  

因为 $F(x)$ 在 $[\alpha\,,\beta]$ 上连续,所以 $F(x)$ 在 $[\alpha\,,\beta]$ 上必存在最大值.又 $F(0)={\frac{1}{2}}\bigl[f^{\prime}(0)\bigr]^{2}+$  $[f(0)]^{3}>\frac{3}{2}$ 可见 $F(x)$ 在時 $[\alpha,\beta]$ 上的最大值必在 $(\alpha\,,\beta)$ 内某点 $\pmb{\xi}(\pmb{\xi}\in(\alpha,\beta)\subset(-2,2))$ 处取到，故由费马定理知， $F^{\prime}(\pmb{\xi})=0$ ,即 $f^{\prime}(\pmb{\xi})\,\{f^{\prime\prime}(\pmb{\xi})+3\big[f(\pmb{\xi})\big]^{2}\,\}=\,0.$ 但$f^{\prime}(\pmb{\xi})\neq0$ ,否则 $F(\xi)=$  $\big[f(\pmb{\xi})\big]^{3}>\frac{3}{2}$ 与 $f(x)\mid\leqslant1$ 矛盾.因此， $f^{\prime\prime}({\pmb\xi})+3{\left[{f({\pmb\xi})}\right]}^{2}=0.$  

例 6. 7设 $f(x)=\!\!\int_{0}^{x}\mathbf{e}^{\prime}\,^{2}\,\mathrm{d}t\,,x\,>0.$   
（1）证明 $\int_{0}^{x}{\mathbf{e}^{\prime}}^{2}\,\mathrm{d}t=x f^{\prime}[x\,\cdot\,\theta(x\,)]$ ,且 $\theta(x)$ 唯一，其中 $0<\theta(x)<1$   
(2)求 $\operatorname*{lim}_{x\to0^{+}}\theta(x)$ ：  

（1)【证】对 $f(x)$ 在 $[0,x]$ 上用拉格朗日中值定理，有  

$$
f(x)-f(0)=f^{\prime}\lbrack x\cdot\theta(x)\rbrack\cdot x\,,0<\theta(x)<1,
$$  

即  

$$
\int_{0}^{x}\mathrm{e}^{t^{2}}\,\mathrm{d}t=x\,f^{\prime}\big[x\,\bullet\,\theta(x\,)\big],0<\theta(x\,)<1.
$$  

若另有 $\theta^{\star}(x)$ ，使得 $f(x)-f(0)=f^{\prime}[x\,\cdot\,\theta^{\,\bullet\,}(x\,)]x\,(0<\theta^{\,\bullet\,}(x\,)<1)$ ，则  

$$
f^{\prime}\bigl[x\,*\,\theta(x)\bigr]x-f^{\prime}\bigl[x\,*\,\theta^{\star}\,(x\,)\bigr]x=f^{\prime\prime}(\hat{\varsigma}\,)x\,\bigl[\theta(x\,)-\theta^{\star}\,(x\,)\bigr]x=0\,,
$$  

其中 $\boldsymbol{\xi}$ 介于 $\ x\,\cdot\,\theta\left(x\,\right)$ 与 $x\cdot\theta^{\cdot}\left(x\right)$ 之间，而 $f^{\prime\prime}(x)>0,x>0$ ,故 $\theta\left(x\,\right)=\theta^{\,\cdot}\left(x\,\right)$ .证毕.  

(2)【解】由(1）知， $\int_{0}^{x}\mathsf{e}^{t^{2}}\,\mathrm{d}t=x\,\cdot\,\mathsf{e}^{[x\cdot\theta(x)]^{2}}\,(0<\theta(x\,)<1)$ ,解得  

$$
\theta(x\,)=\frac{1}{x}\cdot{\sqrt{\ln\frac{\displaystyle\int_{0}^{x}{{\bf e}^{t}}^{2}\,\mathrm{d}t}{x}}}\;,
$$  
第6讲 一元函数微分学的应用(二) 一-中值定理、微分等式与微分不等式  

$={\sqrt{\operatorname*{lim}_{x\to0^{+}}{\frac{\int_{0}^{x}\mathrm{e}^{t^{2}}\,\mathrm{d}t-x}{x^{3}}}}}={\sqrt{\operatorname*{lim}_{x\to0^{+}}{\frac{\mathrm{e}^{x^{2}}-1}{3x^{2}}}}}={\frac{\sqrt{3}}{3}}.$  

例6.8设函数 $f(x)$ 在区间[0,1]上连续,且 $a=\!\!\int_{0}^{1}f(x\,)\,\mathrm{d}x\neq0$ ,证明:在区间(0,1)内至少存在不同的两点 $\xi_{1}\,,\xi_{2}$ ,使得  

$$
\frac{1}{f(\mathfrak{f}_{1})}+\frac{1}{f(\mathfrak{f}_{2})}\!=\!\frac{2}{a}.
$$  

【证】令 $F(x)=\ {\frac{1}{a}}{\Biggl\int}_{0}^{x}\,f(t)\,\mathrm{d}t\,,x\,\in\,[0,1]$ ，则 $F(x)$ 在[0,1]上连续,在(0,1）内可导， $F(0)\!=\!0,F(1)\!=\!1.$ 由连续函数的介值定理知,至少存在一点 $\xi\in\mathsf{\Gamma}(0,1)$ 使得 $F(\pmb\xi)=\frac{1}{2}$ ，，即  

$$
\frac{1}{a}{\int_{0}^{\xi}{f(t\,)\mathrm{d}t}}=\frac{1}{2}\,,\pmb{\xi}\,\in\,(0,1).
$$  

由拉格朗日中值定理知，存在 $\pmb{\xi}_{1}\in(0,\pmb{\xi})$ 及 $\xi_{2}\,\in\,(\xi\,,1)$ ，使得  

$$
F^{\prime}(\pmb{\xi}_{1})=\frac{F(\pmb{\xi})-F(0)}{\pmb{\xi}-0}=\frac{\frac{1}{2}-0}{\pmb{\xi}}=\frac{1}{2\pmb{\xi}},
$$  

$$
F^{\prime}(\pmb{\xi}_{2})=\frac{F(1)-F(\pmb{\xi})}{1-\pmb{\xi}}=\frac{1-\frac{1}{2}}{1-\pmb{\xi}}\,=\frac{1}{2(1-\pmb{\xi})}.
$$  

由于 $F^{\prime}(x)\!=\!\frac{1}{a}f(x)$ ,因此  

$$
\begin{array}{r l}&{\frac{1}{f(\hat{\xi}_{1})}\!+\!\frac{1}{f(\hat{\xi}_{2})}\!=\!\frac{1}{a F^{\prime}(\hat{\xi}_{1})}\!+\!\frac{1}{a F^{\prime}(\hat{\xi}_{2})}}\\ &{\qquad\qquad\qquad\qquad\quad\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!=\!\frac{1}{a}\!\left[2\hat{\xi}+2(1-\hat{\xi})\right]}\\ &{\qquad\qquad\qquad\qquad\quad\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!=\!\frac{2}{a}.}\end{array}
$$  

例6.9 设函数 $f(x\,)=$ arctan $_x$ .若 $f(x)=x f^{\prime}(\xi)$ ，则 $\operatorname*{lim}_{x\rightarrow0}\frac{\hat{\xi}^{2}}{x^{2}}=(\qquad).$  

(A)1 $(\mathrm{B})\ \frac{2}{3}$ $({\mathsf{C}})\,{\frac{1}{2}}$ $(\mathrm{D})\ \frac{1}{3}$  

【解】应选(D).  

因为 $f^{\prime}(x)\mathop{=}\!{\frac{1}{1+x^{2}}}$ 且 $f(x)\!=\!x f^{\prime}(\pmb{\xi})$ ,所以当 $x\neq0$ 时，可知 $f^{\prime}(\pmb{\xi})\!=\!\frac{1}{1+\pmb{\xi}^{2}}\!=\!\frac{f(x)}{x}\!=$  
# 限等高等数学18讲  

$\frac{\arctan\,x}{x}$ ,从而 $\hat{\xi}^{2}=\frac{x-\arctan\,x}{\arctan\,x},$ 又当 $x\,\rightarrow\,0$ 时,arctan $x=x-\frac{1}{3}x^{3}+o(x^{3})$ ，故  

$$
\operatorname*{lim}_{x\to0}{\frac{\hat{\xi}^{2}}{x^{2}}}\!=\!\operatorname*{lim}_{x\to0}{\frac{x-\arctan{\,x}}{{x^{2}\arctan{\,x}}}}\!=\!\operatorname*{lim}_{x\to0}{\frac{x-\left[x-{\frac{1}{3}}x^{3}+o\left(x^{3}\right)\right]}{{x^{3}}}}\!=\!{\frac{1}{3}}.
$$  

一微分等式问题（方程的根、函数的零点）  

# 1.理论依据  

# （1）零点定理及其推广.  

设 $f(x)$ 在 $[a,b]$ 上连续,且 $f(a)f(b)<0$ ，则 $f(x\,)=0\,$ 在 $(a,b)$ 内至少有一个根.  

[注 推广的零点定理:若 $f(x)$ 在 $(a\,,b\,)$ 内连续, $\operatorname*{lim}_{x\to a^{+}}f(x)\!=\!\alpha\;,\operatorname*{lim}_{x\to b^{-}}f(x)\!=\!\beta$ ,且 $\alpha\cdot\beta<0$ ，则$f(x)=0$ 在$(a,b)$ 内至少有一个根,这里 $a\cdot b\cdot\alpha\cdot\beta$ 可以是有限数,也可以是无穷大.  

（2）用导数工具研究函数性态.  

(3）罗尔原话(罗尔定理的推论).  

若$f^{(n)}\left(x\right)=0$ 至多有 $k$ 个根，则 $f(x\,)=0$ 至多有 $\boldsymbol{k}+\boldsymbol{n}$ 个根.  

(4）实系数奇次方程 $x^{\,2n+1}+a_{\,1}x^{\,2n}+\cdots+a_{\,2n}x\,+a_{\,2n+1}=0$ 至少有一个实根.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/09cb97d3c85bf930323c1ebe9ce942180569749f3ef9b7a4c25b144a2c649a7e.jpg)  

# （1）证明恒等式.  

（2）函数的零点个数（方程根的个数、曲线交点的个数）.  

$\textcircled{1}$ 至少几个. $\circledcirc$ 至多几个. $\textcircled{3}$ 恰有几个，  

常含参数讨论.  

(1)导数中不含参数,即辅助函数 $f^{\prime}(x)$ 中不含参数，于是研究函数性态的过程中不讨论参数，结果中讨论参数，即根据参数的取值不同，研究曲线与 $_{x}$ 轴的位置关系。  

（2）导数中含参数，即辅助函数 $f^{\prime}(x)$ 中含参数，于是研究函数性态的过程中讨论参数，即根据参数的取值不同，研究曲线不同的性态，从而确定其与 $_x$ 轴的交点个数。  

# (3）方程（列）问题（见第2讲）.  

（4）区间（列）问题（见第2讲）.  

例 6. 10（1）证明：arcsin $\sqrt{x}+\arcsin{\sqrt{1-x}}=\frac{\pi}{2}$  

（2）计算 $\int_{0}^{1}\frac{\arcsin{\sqrt{x}}}{\sqrt{1-x\left(1-x\right)}}\mathrm{d}x$  

(1)[证】记 $f(x\,)=\arcsin{\sqrt{x}}\,+\arcsin{\sqrt{1-x}}$ ，则  
# 第6讲 一元函数做分学的左用(二)一—中值定理、微分等式与微分不等式  

$$
f^{\prime}(x\,)=\!\frac{1}{\sqrt{1-x}}\cdot\frac{1}{2\sqrt{x}}+\frac{1}{\sqrt{1-(1-x)}}\cdot\frac{-1}{2\sqrt{1-x}}\!=\!0,
$$  

即$f(x)$ 恒为常数,又 $f(0)\!=\!\frac{\pi}{2}$ ,故 $f(x\,)=\arcsin{\sqrt{x}}\,+\arcsin{\sqrt{1-x}}={\frac{\pi}{2}}.$  

(2)[解】令 $x=1-t$ ,则  

$$
\int_{0}^{1}\frac{\mathbf{arcsin}\sqrt{x}}{\sqrt{1-x\left(1-x\right)}}\mathrm{d}x=-\int_{1}^{0}\frac{\mathbf{arcsin}\sqrt{1-t}}{\sqrt{1-t\left(1-t\right)}}\mathrm{d}t=\int_{0}^{1}\frac{\mathbf{arcsin}\sqrt{1-t}}{\sqrt{1-t\left(1-t\right)}}\mathrm{d}t\,,
$$  

所以  

$$
\begin{array}{r l}&{\mathbb{P}_{0}^{\lambda}\vec{\mathbf{x}}\!\!\!\perp\!\!\mathbf{\hat{z}}=\frac{1}{2}\!\!\int_{0}^{1}\!\frac{\arcsin\sqrt{x}+\arcsin\sqrt{1-x}}{\sqrt{1-x}\,(1-x)}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! 
$$  

例 6. 11若方程 $x^{\,x}\,(1-x\,)^{\,1-x}=k$ 在区间（0,1）内有且仅有两个不同的实根,求 $\pmb{k}$ 的取值范围.  

【解】令 $f(x)=x^{\prime}\,(1-x\,)^{1-x}\,,0<x$  $0<x<1$ ，则由例4.7可知， $f(x)$ 焗在 $\left(0,{\frac{1}{2}}\right]$ 上单调减少， $\left[{\frac{1}{2}},1\right)$ 上单调增加， $x=\frac{1}{2}$ 为最小值点，且  

$$
f_{\operatorname*{min}}(x)=f{\Bigl(}{\frac{1}{2}}{\Bigr)}={\Bigl(}{\frac{1}{2}}{\Bigr)}^{\frac{1}{2}}\left(1-{\frac{1}{2}}\right)^{1-{\frac{1}{2}}}={\frac{1}{2}}.
$$  

$$
\operatorname*{lim}_{\to^{+}}f(x)=\operatorname*{lim}_{x\to0^{+}}x^{x}\left(1-x\right)^{1-x}=\operatorname*{lim}_{x\to0^{+}}x^{x}=1,\operatorname*{lim}_{x\to1^{-}}f(x)=\operatorname*{lim}_{x\to1^{-}}{x^{x}\left(1-x\right)^{1-x}}=\operatorname*{lim}_{x\to1^{-}}(1-x)^{1-x}
$$  

则由介值定理知，当 $\frac{1}{2}<k<1$ 时，方程在区间 $\left(0,{\frac{1}{2}}\right)\5\left({\frac{1}{2}},1\right)$ 内各有一个实根，即在区间（0,1）内有且仅有两个不同的实根.  

求方程 $\pmb{k}$ arctan $x-x=0$ 的不同实根的个数，其中 $\pmb{k}$ 为参数.  

【解】令 $f(x\,)\,{=}\,k$ arctan $x-x$ ，则 $f(x)$ 是 $(-\infty,+\infty)$ 内的奇函数,且 $f(0)\!=\!0,f^{\prime}(x)\!=$ $\frac{k-1-x^{2}}{1+x^{2}}.$  
# 比宇高等数学18涉  

当 $k-1\leqslant0$ ，即 $k\leqslant1$ 时， $f^{\prime}(x)<0(x\neq0),f(x)$ 在区间 $(-\infty,+\infty)$ 内单调减少，方程 $f(x\,)=0$ 只有一个实根 $x=0$  

当 $k-1>0$ ，即 $k>1$ 时，在区间 $(0,{\sqrt{k-1}}$ ）内， $f^{\prime}(x)>0,f(x)$ 单调增加，在区间 $(\sqrt{k-1}\,,+\infty)$ ）内， $f^{\prime}(x)<0,f(x)$ 单调减少,所以 $f({\sqrt{k-1}}\,)$ 是 $f(x)$ 在 $(0,+\infty)$ 内的最大值，从而 $f(\sqrt{k-1}\,)>f(0)\!=\!0.$ 又因为 $\operatorname*{lim}_{\tau\to+\infty}f(x)=-\infty$ ,所以由连续函数的零点定理知，存在 $\xi\in$  $(\sqrt{k-1}\,,+\infty)$ ，使得 $f(\xi)=\,0$  

由 $f(x)$ 是奇函数及其单调性可知，当 $k>1$ 时，方程 $f(x\,)=0$ 有3个不同的实根  

$$
\begin{array}{r}{x=-\,\pmb{\xi}\,,x=0\,,\pmb{x}=\pmb{\xi}\,,\pmb{\xi}\,\in\,(\sqrt{k-1}\,,+\infty).}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/44d1470a793a9e306f881d050df5e72003f7c9d0f21fc6b8e748e9135197072f.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/57ac6c2841bc64c8c839caeda4019d079dd5d2d9eea9b6a510481c3db17b8593.jpg)  

# 1.用单调性  

(1)若 $\operatorname*{lim}_{x\to a^{+}}F(x)\geq0$ ,且当 $x\in(a\,,b)$ 时 $F^{\prime}(x)\geqslant0$ ，则在 $(a\,,b)$ 内 $F(x)\geqslant0$  

(注】(1）若在 $x=a$ 处$F(x)$ 右连续,则可用 $F(\alpha)$ 代替 $\operatorname*{lim}_{x\to a^{+}}F(x)$  

(2）若当 $\boldsymbol{x}\in(a,b)$ 时， $F^{\prime}(x)>0$ ，则在 $(a,b)$ 内 $F(x)>0$  

(2）若 $\operatorname*{lim}_{x\to b^{-}}F(x)\geq0$ ，且当 $\boldsymbol{x}\in\left(a\,,b\right)$ 时$F^{\prime}(x)\leqslant0$ ,则在 $(\alpha\,,b)$ 内$F(x)\geqslant0$ 费  

【注】（1）若在 ${\boldsymbol{x}}={\boldsymbol{b}}$ 处 $F(x)$ 左连续，则可用 $F(b)$ 代替 $\operatorname*{lim}_{x\to b^{-}}F(x)$  

(2)若当 $\boldsymbol{x}\in(a,b)$ 时， $F^{\prime}(x)<0$ ，则在 $(a,b)$ 内 $F(x)>0$  

上面讲的区间 $(a,b)$ 既可以是有限区间，也可以是无穷区间，  

# 2.用最值  

如果在 $(a,b)$ 内 $F(x)$ 有最小值 $_m$ ，则在 $(\alpha\,,b)$ 内 $F(x)\geqslant m$ .且除这些最小值点外,均有 $F(x)>m$ ：  

对于最大值 $M$ ，有类似的结论.  

# 3.用凹凸性  

如果 $\forall\,x\in I\,,F^{\prime\prime}(x)\geqslant0$ ，则  
# 第6讲 一元函数微分学的应用(二)一中值定理、微分等式与微分不等式  

$\textcircled{1}\forall\,x_{1}\,,x_{2}\in I$ ,有  

$$
\frac{F(x\,_{1})+F(x\,_{2})}{2}\geqslant F\left(\frac{x\,_{1}+x\,_{2}}{2}\right).
$$  

$\circled{2}\,\forall\,x_{\mathrm{~l~}},x_{\mathrm{~2~}}\in I$ ，对 $\forall\,\lambda_{1}\,,\lambda_{2}\,\in\,(0\,,1)$ ，且 $\lambda_{\mathrm{~l~}}+\lambda_{\mathrm{~2~}}\!=\!1$ ,有$\lambda_{1}F(x_{1})+\lambda_{2}F(x_{2})\geqslant F(\lambda_{1}x_{1}+\lambda_{2}x_{2}).$  

$\circled{3}\,\forall\,x\,,x\,_{0}\,\in\,I$ ,且 $\boldsymbol{x}\neq\boldsymbol{x}_{\u{0}}$ ,有 $F(x)>F(x_{0})+F^{\prime}(x_{0})(x-x_{0}).$  

如果 $\forall\,x\in I,F^{\prime\prime}(x)\leqslant0$ ，则有与上面所述相反的不等式.  

# 4.用拉格朗日中值定理  

如果所给题中的 $F(x)$ 在区间 $[a,b]$ 上满足拉格朗日中值定理的条件，并设当 $\boldsymbol{x}\,\in\,(\alpha\,,b)$ 时 $F^{\prime}(x)\geqslant A$ (或 $\leqslant A$ )，则有  

$F(b)-F(a)\geq A(b-a)$ （或 $F(b)-F(a)\leqslant A(b-a\,))$  

# 5.用柯西中值定理  

如果所给题中的 $F(x)$ 与 $G(x)$ 在区间 $[a,b]$ 上满足柯西中值定理的条件，并设当 $x\in$  $(a,b)$ 时 ${\frac{F^{\prime}(x)}{G^{\prime}(x)}}\geq A$ 域 $\leqslant A$ ），则有  

$$
\frac{F(b)-F(a)}{G(b)-G(a)}\geq A(\,\frac{\alpha}{\alpha}\leq A\,).
$$  

# 6.用带有拉格朗日余项的泰勒公式  

如果所给条件为（或能推导出） $F^{\prime\prime}(x)$ 存在且大于0(或小于0),那么常想到使用带有拉格朗日余项的泰勒公式来证明，将 $F(x)$ 在适当的 ${\boldsymbol{x}}={\boldsymbol{x}}_{\mathit{0}}$ 处展开，  

$F(x\,)=F(x_{\circ})+F^{\prime}(x_{\circ})(x-x_{\circ})+{\frac{1}{2}}F^{\prime\prime}({\mathfrak{s}})(x-x_{\circ})^{2}({\mathfrak{s}}\mid x).$ 价于 $_x$ 与 $\scriptstyle{\mathcal{x}}_{0}$ 之间)，  

于是有 $F(x)\geqslant$ （或 $\leqslant)F(x_{0})+F^{\prime}(x_{0})(x-x_{0})$  

例6. 13设 $f(x)=\left(1-{\frac{a}{x}}\right)^{x}$ ,其中 $x>a>0$  

(1)求 $f(x)$ 的水平渐近线；  

（2）证明： $\mathbf{e}^{a}f(x)<1$ （1)【解】由于 $x>0$ ，故只研究 $x\rightarrow+\infty$ 时的情形.  

$$
\operatorname*{lim}_{x\to+\infty}f(x\,)=\operatorname*{lim}_{x\to+\infty}\!\left(1-{\frac{\alpha}{x}}\right)^{x}={\mathrm{e}}^{x\to+\infty^{x\ln\left(1-{\frac{\alpha}{x}}\right)}}={\mathrm{e}}^{x\to+\infty^{x\cdot\left(-{\frac{\alpha}{x}}\right)}}={\mathrm{e}}^{-\alpha}\,,
$$  

故$y=\mathbf{e}^{-a}$ 为$f(x)$ 的水平渐近线.  

(2)[证) $|f(x)=\mathbf{e}^{x\ln\left(1-\frac{a}{x}\right)}$  $x>a>0$ ,其中  

$$
x\ln\!\left(1-{\frac{a}{x}}\right)\!=\!x\ln{\frac{x-a}{x}}=x\left[\ln(x-a\,)-\ln\,x\,\right]\!,
$$  

故  

$$
f^{\prime}(x\,)=\left(1-\frac{a}{x}\right)^{x}\cdot\left[\ln(x-a\,)-\ln x+\frac{x}{x-a}-1\right]
$$  
# 陆亨高等数学18讲  

$$
=\left(1-{\frac{a}{x}}\right)^{x}\left[\ln(x-a)-\ln x+{\frac{a}{x-a}}\right],
$$  

由拉格朗日中值定理，有  

$$
\ln(x-a)-\ln\,x={\frac{1}{\xi}}\cdot(-a\,)\,,x-a<\xi<x\,,
$$  

即$\frac{1}{\xi}<\frac{1}{x-a}$ 于是 ${\frac{1}{\xi}}(-a)>-{\frac{a}{x-a}}.$  

因此 $(\;\star\;)$ 式大于0,即 $f^{\prime}(x)>0,f(x)$ 严格单调增加,因 $f(x)$ 的水平渐近线为 $\scriptstyle y\,=\,\mathbf{e}^{-a}$ ，故$f(x)<\mathrm{e}^{-a}$ ,即 $\mathbf{e}^{a}f(x)<1$ ,证毕.  

例 6. 14证明：当 $0<x<1$ 时， $\frac{x}{2(1+\cos\,x\,)}<\frac{\ln(1+x\,)}{1+\cos\,x}<\frac{2x}{1+\sin\,x}.$  

【证】令 $f(x\,)=\frac{x}{2}-\ln(1+x\,)\,,x\,\in\,[0,1]$ ，则  

$$
f^{\prime}(x)=\frac{1}{2}-\frac{1}{1+x}=\frac{x-1}{2(1+x\,)}<0\,,x\,\in\,(0,1).
$$  

又 $f(0)=0$ ，故 $\frac{x}{2}<\ln(1+x\,)(x\,\in\,(0,1))$ ,又因为 $x\,\in\,\left(0,1\right),1+\cos\,x>0$ ,则  

$$
\frac{x}{2(1+\cos x)}<\frac{\ln(1+x)}{1+\cos x}.
$$  

现比较 $\frac{\ln(1+x)}{1+\cos x}$ 愛和 $\frac{2x}{1+\sin\ x}$ 当 $x\,\in\,(0\,,1)$ 时，cos ${\frac{x}{2}}>\sin{\frac{x}{2}}$ 则  

即  

$$
\begin{array}{r l}&{\left[2\cos\frac{x}{2}\right)^{2}>\left(\cos\frac{x}{2}+\sin\frac{x}{2}\right)^{2}}\\ &{\qquad4\cos^{2}\frac{x}{2}>1+\sin x\,,}\\ &{\qquad2(1+\cos x)>1+\sin x\,,}\\ &{\qquad\frac{1}{2(1+\cos x)}<\frac{1}{1+\sin x}\,,}\\ &{\qquad\ln(1+x)<x\,,\,x\in\{0,1\}\,,}\\ &{\qquad\ln(1+x)<\frac{2x}{1+\sin x}\,.}\end{array}
$$  

故  

因此  

又  

则  

证毕.  

例 6. 15已知 $f(x$ ）为二阶可导的正值函数， $f(0)\,=\,f^{\prime}(0)\,=\,1,f(x\,)f^{\prime\prime}(x\,)\,\geqslant$ $[f^{\prime}(x)]^{2}$ ,则( ).  

$\begin{array}{r l r l}&{\mathrm{(A)}f(2)\leqslant\mathbf{e}^{2}\leqslant\sqrt{f(1)f(3)}\;\;\;\;\;\;\;\;\;\;\;\;}&{\mathrm{(B)}\mathbf{e}^{2}\leqslant f(2)\leqslant\sqrt{f(1)f(3)}}\\ &{\mathrm{(C)}\sqrt{f(1)f(3)}\leqslant\mathbf{e}^{2}\leqslant f(2)\;\;\;\;\;\;\;\;\;\;\;\;}&{\mathrm{(D)}\sqrt{f(1)f(3)}\leqslant f(2)\leqslant\mathbf{e}^{2}}\end{array}$ 【解】应选(B).  
令$g\left(x\right)=\ln\,f(x)$ ，则  
$$
g^{\prime}(x)\!=\!\frac{f^{\prime}(x)}{f(x)},g^{\prime\prime}(x)\!=\!\frac{f(x)f^{\prime\prime}(x)-\left[f^{\prime}(x)\right]^{2}}{\left[f(x)\right]^{2}}\!\geqslant\!0\,,
$$  

故由带拉格朗日余项的泰勒公式，有  

$$
\begin{array}{c}{{g\left(x\right)=g\left(0\right)+g^{\prime}(0)x+\displaystyle\frac{g^{\prime\prime}(\xi)}{2}x^{2}}}\\ {{{}}}\\ {{=\ln\,f(0)+\displaystyle\frac{f^{\prime}(0)}{f(0)}x+\displaystyle\frac{g^{\prime\prime}(\xi)}{2}x^{2}}}\\ {{{}}}\\ {{=x+\displaystyle\frac{g^{\prime\prime}(\xi)}{2}x^{2}\geqslant x\,,}}\end{array}
$$  

其中 $\boldsymbol{\xi}$ 介于 $0\,,x$ 之间，即 $f(x)\geq\mathrm{e}^{x}\,,f(2)\geq\mathrm{e}^{2}$  

又由于 $g^{\prime\prime}(x)\geqslant0$ 有 $\frac{g(x_{1})+g(x_{2})}{2}\geq g\Big(\frac{x_{1}+x_{2}}{2}\Big)$ ，即  

$$
f(x_{1})f(x_{2})\geqslant f^{2}\!\left({\frac{x_{1}+x_{2}}{2}}\right),x_{1},x_{2}\in(-\infty,+\infty).
$$  

令 $x_{\mathrm{~l~}}\!=1,x_{\mathrm{~2~}}\!=3$ ，有 $f(1)f(3)\geqslant f^{2}\left({\frac{1+3}{2}}\right)=f^{2}(2)$ ，即 $f(2)\leqslant{\sqrt{f(1)f(3)}}$ .于是 $\mathbf{e}^{2}\ll f(2)\ll\sqrt{f(1)f(3)}$ ,选(B).  
# 第7讲  

# 一元函数微分学的应用 (三)-物理应用与经济应用  

# 知识结构  

物理应用(仅数学一、数学二)  

-以“A 对 B 的变化率”为核心写 $\frac{\mathrm{d}A}{\mathrm{d}B}$ 的表达式  

经济应用（仅数学三）  

需求函数供给函数  
经济学中常见的函数成本函数收益（人）函数利润函数边际成本  
边际函数与边际分析边际收益边际利润 需求的价格弹性  
弹性函数与弹性分析供给的价格弹性收益的价格弹性  

一物理应用（仅数学一、数学二）  

以“A 对 B 的变化率”为核心,写出 $\frac{\mathrm{d}A}{\mathrm{d}B}$ 的表达式，并依题意进行计算即可，常与相关变化率综合考查.  

例 7. 1一容器的内表面是由曲线 $x=y+\sin\,y\left(0\leqslant y\leqslant{\frac{\pi}{2}}\right)$ (单位:m)绕 $_y$ 轴旋转一周所得的旋转面(见图 7-1).现以 $\frac{\pi}{16}~\mathrm{m^{3}/s}$ 的速率往容器中加水,则当水面高度为 $\frac{\pi}{4}\,\mathrm{~m~}$ 时,水面上升的速率为  

【解】应填 $\frac{1}{(\pi+2\sqrt{2})^{2}}\;\mathrm{m/s}.$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/9909634f2d173ac63d312006b4bc84fc135500a2f686845336ceabaa736a3d20.jpg)  
图7-1  
# 第7讲 一元函数微分学的应用 (三)一—物理应用与经清应用  

设加水 $t$ s 时水面的高度为 $y\textrm{\textmd m}$ ,则此时水的体积为  

$$
V=\pi\!\int_{0}^{y}x^{\:2}\left(u\right)\mathrm{d}u=\pi\!\int_{0}^{y}\left(u+\sin\:u\right)^{2}\!\mathrm{d}u\:,
$$  

故  

$$
\frac{\mathrm{d}V}{\mathrm{d}t}=\frac{\mathrm{d}V}{\mathrm{d}y}\cdot\frac{\mathrm{d}y}{\mathrm{d}t}=\pi(y+\sin\,y\,)^{2}\,\,\frac{\mathrm{d}y}{\mathrm{d}t}\,,
$$  

又$\frac{\mathrm{d}V}{\mathrm{d}t}\!=\!\frac{\pi}{16}\,\,\mathrm{m}^{3}/\mathrm{s}$ ,于是  

$$
\frac{{\mathrm{d}}y}{{\mathrm{d}}t}=\frac{1}{(y+\sin\,y\,)^{2}}\cdot\frac{1}{16},
$$  

故  

$$
\left.\frac{\mathrm{d}y}{\mathrm{d}t}\,\right|_{y=\frac{\pi}{4}}=\frac{1}{\left(\frac{\pi}{4}+\frac{\sqrt{2}}{2}\right)^{2}\,\cdot\,16}=\frac{1}{(\pi+2\sqrt{2}\,)^{2}}(\,\mathrm{m}/\mathrm{s}).
$$  

# 经济应用 (仅数学三  

# 1.经济学中常见的函数  

# (1) 需求函数.  

设某产品的需求量为 $\boldsymbol{Q}$ ，价格为 $\ensuremath{\hat{\mathcal{P}}}$ ,则 $Q\!=\!Q(\mathbf{\chi}_{\!\textbf{\em{p}}})$ 称为需求函数,且 $\boldsymbol{Q}$ 一般为单调减少函数.  

(2) 供给函数.  

设某产品的供给量为 $\boldsymbol{q}$ ,价格为 $\pmb{\hat{P}}$ ,则 $q=q\left(\,p\,\right)$ 称为供给函数,且 $\boldsymbol{q}$ 一般为单调增加函数.  

(3)成本函数.  

设生产产品的总投人为 $C$ ，它由固定成本 $C_{1}$ （常量）和可变成本 $C_{2}(Q)$ 两部分组成，其中 $\boldsymbol{Q}$ 表示产量.成本函数为 $C=C(Q)=C_{1}+C_{2}(Q),$ 称 $\frac{c}{Q}$ 为平均成本,记为 $\bar{C}$ 或 $A C$ ,即  

$$
A C=\overline{{C}}=\frac{C}{Q}=\frac{C_{1}}{Q}+\frac{C_{2}(Q)}{Q}.
$$  

# （4）收益（入）函数.  

设产品售出后所得的收益为 $R$ ，则  

$$
\begin{array}{r}{R=R\left(Q\right)=\rho Q\,,}\end{array}
$$  

其中 $\pmb{\dot{P}}$ 是价格， $\boldsymbol{Q}$ 是销售量.  

# (5)利润函数.  

设收益扣除成本后的利润为 $L$ ，则  

$$
L=L\left(Q\right)=R\left(Q\right)-C(Q)\,,
$$  

其中 $\boldsymbol{Q}$ 为销售量.  

$^{2,}$ 边际函数与边际分析  

在经济学中,若函数 $f(x)$ 可导，则称 $f^{\prime}(x)$ 为 $f(x)$ 的边际函数. $f^{\prime}(x_{\circ})$ 称为 $f(x)$ 在 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$  
# 比亨高等数学18讲  

点的边际值，用边际函数来分析经济量的变化叫边际分析.  

由 $\Delta y\approx{\mathsf{d}y}$ ,即 $f(x_{\circ}+\Delta x\,)-f(x_{\circ})\approx f^{\prime}(x_{\circ})\Delta x$ ,取 $\Delta x=1$ ,得 $f(x_{0}+1)-f(x_{0})\approx$ $f^{\prime}(x_{\circ})$  

于是，边际值 $f^{\prime}(x_{\circ})$ 被解释为在 $\boldsymbol{\mathscr{x}}_{0}$ 点，当 $_{x}$ 改变一个单位时，函数 $f(x)$ 近似(实际问题中，经常略去“近似”二字）改变 $\mid f^{\prime}(x_{\textit{0}})\mid$ 个单位. $f^{\prime}(x_{\circ})$ 的符号反映自变量的改变与因变量的改变是同向还是反向.  

# (1)边际成本.  

设总成本函数为 $C=C(Q)(Q$ 为产量）,则边际成本函数(记为 $M C$ ）为 $M C=C^{\prime}(Q)$  

# (2)边际收益.  

设总收益函数为 $R=R\left(Q\right)\left(Q$ 为销售量),则边际收益函数(记为 $M R$ )为 $M R=R^{\prime}(Q)$  

# (3）边际利润.  

设利润函数为 $L=L\left(Q\right)(Q$ 为销售量），则边际利润函数（记为 $M L$ ）为 $M L=L^{\prime}(Q)$  

# 3.弹性函数与弹性分析  

在经济学中，把因变量对自变量变化的反应的灵敏度，称为弹性或弹性系数.设函数 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 可导，称  

$$
\eta=\!\!\operatorname*{lim}_{\Delta x\to0}\!{\frac{\Delta y}{y}}{\Big/}\,{\frac{\Delta x}{x}}\!\!=\!{\frac{x}{y}}y^{\prime}=\!\!{\frac{x}{f(x\,)}}f^{\prime}(x\,)
$$  

为函数 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 的弹性函数，称  

$$
\eta\Big|_{\l_{x=x_{0}}}=\frac{x_{\l_{0}}}{f(x_{\l_{0}})}f^{\prime}(x_{\l_{0}})
$$  

为函数 $f(x)$ 在 $x_{\mathrm{~0~}}$ 处的(点)弹性.  

$\eta\Big|_{x=x_{0}}$ 表示在 $\scriptstyle{\mathcal{x}}_{0}$ 处，当自变量 $_{x}$ 改变 $1\%$ 时，因变量 $_y$ 将改变 $\mid\!\eta\,\Bigr|_{\,x=x_{0}}\,\Bigr|\,\mathcal{V}_{0}\,=$  $\left|\frac{\hat{x_{0}}}{f(x_{0})}f^{\prime}(x_{0})\right|\,\%.$ 其符号反映自变量 $_{x}$ 与因变量 $_y$ 的改变是同向还是反向.  

用弹性函数来分析经济量的变化叫弹性分析.  

# （1）需求的价格弹性  

$$
\eta_{d}=\frac{E Q}{E\!\!\!/}=\!\frac{\dot{p}}{Q}\,\frac{\mathrm{d}Q}{\mathrm{d}\dot{p}}=\!\frac{\dot{p}}{Q(\dot{p})}Q^{\prime}(\dot{p}\,).
$$  

一般地,需求函数单调减少,故 $Q^{\prime}(p)<0$ ,从而 $\eta_{d}<0$  

其经济意义：当价格为 $\ensuremath{\dot{\boldsymbol{p}}}$ 时,若提价(降价) $1\,\%$ ,则需求量将减少(增加） $1\ \eta_{\ d}\ 1\ \%$  

【注】若题设要求 $\eta_{d}>0$ ，则取 $\eta_{d}=-\frac{\dot{p}}{Q(\dot{p})}Q^{\prime}(\dot{p})$  

# (2）供给的价格弹性.  

$$
\eta_{\ast}=\!\frac{E q}{E\!\phi}\!=\!\frac{\hbar}{q}\,\frac{\mathrm{d}q}{\mathrm{d}\phi}\!=\!\frac{\hbar}{q(\hbar)}q^{\prime}(\hbar).
$$  

一般地,供给函数单调增加,故 $q^{'}(\d a_{\d})>0$ ，从而 $\eta,>0$  
其经济意义：当价格为 $\dot{\boldsymbol{P}}$ 时，若提价(降价） $1\,\%$ ,则供给量将增加(减少) $\eta,\%$  

# （3）收益的价格弹性  

$$
\eta_{r}=\frac{E R}{E\dot{p}}=\frac{\dot{p}}{R}\;\frac{\mathrm{d}R}{\mathrm{d}\dot{p}}=\frac{\dot{p}}{R\left(\dot{p}\right)}R^{\prime}(\dot{p}\right).
$$  

一般地,收益函数单调增加,故 $R^{\prime}(\phi)>0$ ，从而 $\eta_{r}>0$ 其经济意义:当价格为 $\ensuremath{\hat{p}}$ 时,若提价(降价) $1\%$ ,则收益将增加(减少) $\eta,\%$  

例 7. 2设生产某商品的固定成本为60000元,可变成本为20元／件,价格函数为 $\scriptstyle{\hat{p}}\,=$  $60-{\frac{Q}{1\ 000}}(\ p$ 是单价，单位：元； $\boldsymbol{Q}$ 是销量，单位：件).已知产销平衡，求：  

（1）该商品的边际利润函数；  
（2）当 $\ensuremath{\phi}=50$ 元时的边际利润，并解释其经济意义；(3）使得利润最大的单价 $\ensuremath{\hat{P}}$  

[解](1)成本函数 $C(Q)=60~000+20Q$ ，收益函数 $R(Q)=\rho Q=60Q-{\frac{Q^{2}}{1\ 000}}$ ，利润函数 $L(Q)=R(Q)\!-\!C(Q)=-{\frac{Q^{2}}{1\ 000}}\!+\!40Q\!-\!60\ 000$ ，故该商品的边际利润函数 $L^{\prime}(Q)=-\frac{Q}{500}\!+\!40,$ (2)当 $\ensuremath{p}=50$ 元时，销量 $Q=10~000$ （件）， $L^{'}(10\ 000)=20\cdot$ （元）.其经济意义：销售第10001件商品所得的利润为20元.  

(3)令 $L^{\prime}(Q)\!=\!-\frac{Q}{500}\!+\!40\!=\!0$ ，得 $Q=20\ 000$ (件)，且 $L^{\prime\prime}(20~000)<0$ ,故当 $Q\,{=}20\ 000$ 件时利润最大,此时 $\ensuremath{\phi}=40$ （元）.  

例 7. 3设某商品需求量 $\boldsymbol{Q}$ 是价格 $\ensuremath{\hat{P}}$ 的单调减少函数： $Q=Q(\v{r}_{p})$ ,其中需求弹性 $\eta=$ $\frac{2{\phi}^{2}}{192-{\phi}^{2}}>0.$  

(1) 设 $R=R\left(\,p\,\right)$ 为总收益函数，证明 $\frac{\mathrm{d}R}{\mathrm{d}\phi}\!=\!Q(1-\eta)$ ：（2）求当 $\phi=6$ 时，总收益对价格的弹性，并说明其经济意义.  

（1）【证】由题设得 $R\left(\phi\right)=p Q\left(\phi\right)$ .两边对 $\ensuremath{\dot{\boldsymbol{P}}}$ 求导，得  

$$
\frac{\mathrm{d}R}{\mathrm{d}\phi}=Q+\rho\;\frac{\mathrm{d}Q}{\mathrm{d}\phi}=Q\left(1+\frac{\phi}{Q}\;\frac{\mathrm{d}Q}{\mathrm{d}\phi}\right)=Q(1-\eta).
$$  

(2） $\frac{E R}{E\hbar}=\frac{\hbar}{R}\,\frac{\mathrm{d}R}{\mathrm{d}\phi}=\frac{\hbar}{\rho Q}Q(1-\eta)=1-\eta=1-\frac{2\phi^{2}}{192-{p^{2}}}=\frac{192-3\phi^{2}}{192-\rho^{2}}.$ $\frac{E R}{E_{\widehat{P}}}\Big|_{\widehat{\mathbf{\tau}}_{{\widehat{\tau}}={\widehat{\mathbf{\tau}}}}}=\frac{192-3\times6^{2}}{192-6^{2}}=\frac{7}{13}\approx0.\ 54.$  

其经济意义：当 $\phi=6$ 时，若价格上涨 $1\,\%$ ，则总收益将增加 $0.\,54\,\%$  

17.4以 $\phi_{A}\cdot\phi_{B}$ 分别表示 $A\,,B$ 两种商品的价格，设商品 $A$ 的需求函数为  

$$
Q_{A}=500-p_{A}^{2}-p_{A}\phi_{B}+2\phi_{B}^{2}\,,
$$  
张亨高等数学18讲  

则当 $\phi_{A}=10\,,\phi_{B}=20$ 时,商品 A 的需求量对自身价格的弹性 $\eta_{A A}\left(\eta_{A A}>0\right)$ 为【解】应填0.4.  

根据弹性的定义,有  

$$
\eta_{A A}=-\frac{\dot{p}_{A}}{Q_{A}}\cdot\frac{\partial Q_{A}}{\partial\dot{p}_{A}}=-\frac{\dot{p}_{A}}{Q_{A}}\cdot(-\,2\dot{p}_{A}-\dot{p}_{B})=\frac{\dot{p}_{A}(2\dot{p}_{A}+\dot{p}_{B})}{500-\dot{p}_{A}^{2}-\dot{p}_{A}\dot{p}_{B}+2\dot{p}_{B}^{2}},
$$  

故当 $\phi_{A}=10\,,\phi_{B}=20$ 时， $\eta_{A A}=0.4$  
# 第8讲一元函数积分学的概念与性质  

# 知识结构  

“祖孙三代” $\left(\int_{a}^{x}f(t)\mathrm{d}t\,,f(x),f^{\prime}(x)\right)$  $\int_{a}^{x}f(t)\,\mathrm{d}t\,,f(x\,)\,,f^{\prime}(x\,)$ 的的奇偶性、周期性7条关系  

用公式或几何意义  
积分比大小 看正负 用保号性作差基本形（能凑成一） $\begin{array}{l}{\displaystyle\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}f\left(0+\frac{1-0}{n}i\right)\frac{1-0}{n}=\!\!\int_{0}^{1}f(x\,)\,\mathrm{d}x}\\ {\displaystyle\operatorname*{lim}_{n\to\infty}\sum_{i=0}^{n-1}f\left(0+\frac{1-0}{n}i\right)\frac{1-0}{n}=\!\!\int_{0}^{1}f(x\,)\,\mathrm{d}x}\end{array}$ n夹逼准则  
定积分定义 放缩形(凑不成 $\frac{i}{n}$ 放缩后再凑 $\frac{i}{n}$ 变量形 $\operatorname*{lim}_{n\to\infty}\sum_{i\,=\,1}^{n}f\left(0+{\frac{x-0}{n}}i\right){\frac{x-0}{n}}=\!\!\int_{0}^{x}f(t)\,\mathrm{d}t$ 概念   
反常积分的判敛判别  

祖孙三代?f(t)dt,f(x),f'(x))的奇偶性、周期性  

$\textcircled{1}f(x)$ 为可导的奇函数 $\Rightarrow f^{\prime}(x)$ 为偶函数.  
 $\textcircled{2}f(x)$ 为可导的偶函数 $\Rightarrow f^{\prime}(x)$ 为奇函数.  
 $\textcircled{3}f(x)$ 是可导的且以 $T$ 为周期的周期函数 $\Rightarrow f^{\prime}(x)$ 是以 $T$ 为周期的周期函数. $\begin{array}{l}{\displaystyle{\left\{\int_{0}^{x}f\left(t\right)\,\mathrm{d}t\right.}}\\ {\displaystyle{\left.\left\vert\int_{a}^{x}f\left(t\right)\,\mathrm{d}t\right.\right.}}\end{array}$ 为偶函数，  
$\textcircled{4}f(x)$ 为可积的奇函数= 为偶函数 $(a\neq0)$  

注)(1) 若 $f(x)$ 连续，则 $\int_{a}^{x}f(t)\,\mathrm{d}t+C$ 也是偶函数,故 $f(x)$ 的全体原函数均为偶函数,  
# 比亨高等数学18讲  

(2）只需要被积函数可积，即可有变限积分的相关性质.只有被积函数连续时，才谈原函数的相关性质，以下同。  

f(t） dt 为奇函数，$\textcircled{5}f(x)$ 为可积的偶函数 $\Rightarrow$ 2为奇函数，若 $\int_{a}^{x}f(t)\mathrm{d}t=\int_{0}^{x}f(t)\mathrm{d}t$ f(t)dt(a≠0)为非奇非偶函数,若 $\int_{a}^{x}f(t)\mathrm{d}t\neq\int_{0}^{x}f(t)\mathrm{d}t.$  

【注】若 $f(x)$ 连续，则 $f(x)$ 的全体原函数中，只有 $\int_{0}^{x}f(t)\,\mathrm{d}t$ 是奇函数  

$\circled{6}f(x)$ 是可积的且以 $T$ 为周期的周期函数，则 $\int_{0}^{x}f(t)\mathrm{d}t$ 是以 $T$ 为周期的周期函数$\leftrightarrow\!\!\int_{0}^{T}f(x)\mathrm{d}x=\,0.$  

【注】 $\int_{a}^{x}f(t)\,\mathrm{d}t=\int_{0}^{x}f(t)\,\mathrm{d}t+\int_{a}^{0}f(t)\,\mathrm{d}t$ 亦是以 $T$ 为周期的周期函数( $(a\neq0)$  

$\textcircled{7}f(x)$ 是可积的且以 $T$ 为周期的周期函数 $\Rightarrow\!\!\int_{0}^{T}f(x\,)\,\mathrm{d}x=\!\!\int_{a}^{a+T}f(x\,)\,\mathrm{d}x\,,a$ 为任意常数.  

例 8. 1已知函数 $f(x)=\mathbf{e}^{\sin x}+\mathbf{e}^{-\sin x}$ ，则 $f^{{\prime}{\prime}}(\,2\pi)=\_$  

【解】应填0.  

因为 $f(x)$ 为偶函数,则 $f^{\prime\prime}(x)$ 为奇函数,故 $f^{{\boldsymbol\prime}{\boldsymbol\prime}}(0)=0$ ,又因为 $f(x)$ 以 $2\pi$ 为周期,故  

$$
f^{{\dprime}{\dprime}}(2\pi)=f^{{\dprime}{\dprime}}(0)=0.
$$  

例 8. 2设 $f(t)$ 为连续函数， $^a$ 是常数,则下述命题正确的是(（A）若 $f(t)$ 为奇函数，则 $\int_{a}^{x}\mathrm{d}y\int_{0}^{y}f(t)\,\mathrm{d}t$ 是 $_{x}$ 的奇函数(B)若 $f(t)$ 为偶函数，则 $\int_{0}^{x}\mathbf{d}y\int_{a}^{y}f(t)\,\mathrm{d}t$ 是 $_{x}$ 的奇函数(C)若 $f(t)$ 为奇函数,则 $\int_{0}^{x}\mathbf{d}y\int_{y}^{x}f(t)\,\mathrm{d}t$ 是 $_{x}$ 的奇函数(D)若 $f(t)$ 为偶函数，则 $\int_{0}^{x}\mathbf{d}y\int_{0}^{x}f(t)\,\mathrm{d}t$ 是 $_{x}$ 的奇函数  

【解】应选(C).  

设 $F(t)$ 是 $f(t)$ 的一个原函数.对于(C),若 $f(t)$ 是奇函数,则 $f(t)$ 的任一原函数都是偶函数，所以 $F\left(t\right)$ 是偶函数.  

$$
\int_{0}^{x}\mathrm{d}y\int_{y}^{x}f(t)\mathrm{d}t=\!\!\int_{0}^{x}\big[F(x\,)-F(y\,)\big]\mathrm{d}y=\!x F(x\,)-\!\int_{0}^{x}F(y\,)\mathrm{d}y\,,
$$  

因为 $F(x)$ 为偶函数,所以 $x F(x)$ 为 $_{x}$ 的奇函数， $\int_{0}^{x}F(y)\,\mathrm{d}y$ 也是 $_{x}$ 的奇函数,所以 $\int_{0}^{x}\mathrm{d}y\int_{y}^{x}f(t)\mathrm{d}t$  
为 $_{x}$ 的奇函数，(C）正确.  

关于选项(A)，(B)，(D）为什么不正确，解释如下.  

对于(A), $f(t)$ 为奇函数,则 $F(y)=\!\int_{0}^{y}f(t)\mathrm{d}t$ 是 $_y$ 的偶函数，但 $\int_{a}^{x}F(y\,)\,\mathrm{d}y$ 不一定是 $_x$ 的奇函数；  

对于(B), $f(t)$ 为偶函数,则 $F(y)=\int_{a}^{y}f(t)\,\mathrm{d}t$ 不一定是 $_y$ 的奇函数,不再有继续研究的资格了；  

对于(D), $f(t)$ 为偶函数,则 $F(x)\mathop{=}\!\int_{0}^{x}f(t)\,\mathrm{d}t$ 为 $_{x}$ 的奇函数， $\int_{0}^{x}F(x)\,\mathrm{d}y=x\,F(x)$ 为 $_{x}$ 的偶函数.  

例 8. 3设一阶线性齐次微分方程 $y^{\prime}+p\left(x\right)y=0$ 的系数 $_{\phi}(x)$ 是以 $T$ 为周期的连续函数,则“该方程的非零解以 $T$ 为周期”是“ $\int_{0}^{\tau}\pmb{\mathscr{p}}(x)\,\mathrm{d}x=0^{\ast}$ 的().  

（A）充分非必要条件（B）必要非充分条件（C）充分必要条件（D）既非充分也非必要条件  

【解】应选(C).  

$y^{\prime}+p\left(x\right)y=0$ 的非零解为 $y=\!C\,\mathrm{e}^{-\int\!\!p(x)\mathrm{d}x}=\!C\,\mathrm{e}^{-\int_{0}^{x}p(t)\mathrm{d}t}$ ,其中 $C$ 是任意非零常数，于是 $_y$ 以 $T$ 为周期 $\ominus C\mathsf{e}^{-\int_{0}^{x}p(t)\,\mathrm{d}t}$ 以 $T$ 为周期 $\Leftrightarrow\!\!\int_{0}^{x}\!\mathbf{\mathcal{p}}(t)\,\mathrm{d}t$  $T$ 为周期 $\varTheta\!\int_{0}^{T}p\left(x\right)\mathrm{d}x=0.$  

二积分比大小  

1.用公式或几何意义  

设 $F(x)$ 是 $f(x)$ 的一个原函数，则  

$$
\begin{array}{r l}&{\displaystyle\mathbb{\widehat{D}}\displaystyle\int_{a}^{b}f(x)\,\mathrm{d}x=F(b)-F(a),}\\ &{\displaystyle\mathbb{\widehat{D}}\displaystyle\int_{x_{0}}^{x}f^{\prime}(t)\,\mathrm{d}t=f(x)-f(x_{0}),}\\ &{\displaystyle\mathbb{\widehat{D}}\displaystyle\int_{-a}^{a}f(x)\,\mathrm{d}x=\left\langle2\displaystyle\int_{0}^{a}f(x)\,\mathrm{d}x\right.,}\\ &{\displaystyle}\end{array}
$$  

2.用保号性  
 $\textcircled{1}$ 看正负.如 $1\ x\ |\geq0$ ；当 $x\in[\pi,2\pi]$ 时，sin $x\leqslant0$ 等。 $\circledcirc$ 作差. $I_{1}-I_{2}$ ,再换元(常用 $x=\pi\pm t\,,x=\frac{\pi}{2}\pm t\,)$ 读者应熟记下列常用诱导公式.  
# 阳亨高等数学18讲  

$$
\begin{array}{l}{\displaystyle\textcircled{\mathbb{D}}\,\sin(\pi\pm t)=\mp\,\sin t.}\\ {\displaystyle\textcircled{\mathbb{Q}}\,\cos(\pi\pm t)=-\cos t.}\\ {\displaystyle\textcircled{\mathbb{D}}\,\sin\!\left(\frac{\pi}{2}\pm t\right)\!=\!\cos t.}\\ {\displaystyle\textcircled{\mathbb{Q}}\,\cos\!\left(\frac{\pi}{2}\pm t\right)\!=\!\mp\sin t.}\end{array}
$$  

例8. 4已知 $I_{1}=\int_{0}^{1}\,\frac{x}{2(1+\cos\,x)}\mathrm{d}x\,,I_{2}\,=\int_{0}^{1}\,\frac{\ln(1+x)}{1+\cos\,x}\mathrm{d}x\,,I_{3}\,=\int_{0}^{1}\,\frac{2x}{1+\sin\,x}\mathrm{d}x\,,$ 则( ).  

$(\mathbf{A})I_{1}<I_{2}<I_{3}$ $\begin{array}{r}{(\mathrm{B})I_{2}<I_{1}<I_{3}}\\ {(\mathrm{D})I_{3}<I_{2}<I_{1}}\end{array}$ $(\mathrm{C})\,I_{1}<I_{3}<I_{2}$  

【解】应选(A).  
由例6.14得， $I_{1}<I_{2}<I_{3}$ .故选(A).  

例 8. 5设 $I_{\star}=\!\int_{0}^{k\pi}\!\,\!\mathbf{e}^{x^{2}}\sin\,x\,\mathrm{d}x\,(k=1,2,3)$ ，则（  

$(\mathrm{A})I_{1}<I_{2}<I_{3}$ $\begin{array}{r}{(\mathrm{B})I_{3}<I_{2}<I_{1}}\\ {(\mathrm{D})I_{2}<I_{1}<I_{3}}\end{array}$ $(\mathrm{C})I_{2}<I_{3}<I_{1}$  

【解】应选(D).  

首先，由 $I_{\mathit{z}}=I_{\mathit{1}}+\int_{\mathit{\pi}}^{2\pi}\mathrm{e}^{x^{2}}\sin{x}\,\mathrm{d}x$ 及 $\int_{\pi}^{2\pi}\mathrm{e}^{x^{2}}\sin\,x\,\mathrm{d}x<0$ ,可得 $I_{2}<I_{1}$ ：  

其次， $I_{3}=I_{1}+\int_{\pi}^{3\pi}\mathrm{e}^{x^{2}}\sin{x}\,\mathrm{d}x$ ,其中$\begin{array}{r l}&{\int_{\frac{\pi}{\pi}}^{3\pi}\mathrm{e}^{x^{2}}\sin x\,\mathrm{d}x=\!\int_{\frac{\pi}{\pi}}^{2\pi}\!\mathrm{e}^{x^{2}}\sin x\,\mathrm{d}x+\!\int_{\frac{2\pi}{\pi}}^{3\pi}\!\mathrm{e}^{x^{2}}\sin x\,\mathrm{d}x}\\ &{\qquad\qquad\qquad=\!\int_{\frac{\pi}{\pi}}^{2\pi}\!\mathrm{e}^{x^{2}}\sin x\,\mathrm{d}x+\!\int_{\frac{\pi}{\pi}}^{2\pi}\!\mathrm{e}^{(y+\pi)^{2}}\!\sin(y+\pi)\mathrm{d}y}\\ &{\qquad\qquad\qquad=\!\int_{\frac{\pi}{\pi}}^{2\pi}\![\mathrm{e}^{x^{2}}-\mathrm{e}^{(x+\pi)^{2}}]\!\sin x\,\mathrm{d}x>0\,,}\end{array}$  

故 $I_{3}>I_{1}$ ，从而 $I_{2}<I_{1}<I_{3}$ ,故选(D).  

【注】作为选择题，可用几何意义，大致画出 $_y=$  $\mathbf{e}^{x^{2}}$ sin $_{x}$ 在 $[0,3\pi]$ 上的图像,如图 8-1 所示.其中 $0\!<$  $S_{1}<S_{2}<S_{3}$ ，则  

$I_{1}=\int_{0}^{\pi}\!\,\!\mathrm{e}^{x^{2}}\sin\,x\,\mathrm{d}x=S_{1}>0\,,$ $I_{2}=\!\int_{0}^{2\pi}\!\mathrm{e}^{x^{2}}\sin\,x\,\mathrm{d}x=S_{1}+(-\,S_{2})={S_{1}}-S_{2}<0\,.$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/29f95c616ec537d10cc8b83d3eba789bdeb4021861697deedf72d2bc53621b2b.jpg)  
图8-1  

$$
I_{3}=\int_{0}^{3\pi}{\mathrm{e}}^{x^{2}}\sin\,x\,{\mathrm{d}}x=S_{1}+(-\,S_{2})+S_{3}=S_{1}+(S_{3}-S_{2})>S_{1}>0.
$$  

综上所述， $I_{2}<I_{1}<I_{3}$ ，故选(D).  
# 第8讲一元函数和分学的概念与性质  

# 三定积分定义  

有一类数列和的极限计算，可用定积分定义来处理， $1.$ 基本形(能凑成一)  

若数列通项中含下面四种形式：  

$\mathbb{O}\xrightarrow[n]{i},$   
②n +i(an +bi,ab ≠ 0); ③n² +i² ;   
④n² + ni.  

则能凑成 $\frac{i}{n}$ ，比如  

$$
\begin{array}{l}{\displaystyle\mathbb{\ O}n+i=n\left(1+\frac{i}{n}\right),}\\ {\displaystyle\mathbb{\ O}n^{2}+i^{2}=n^{2}\left[1+\left(\frac{i}{n}\right)^{2}\right];}\\ {\displaystyle\mathbb{O}n^{2}+n i=n^{2}\left(1+\frac{i}{n}\right).}\end{array}
$$  

于是可直接用定积分定义  

或  

$$
\begin{array}{r l}&{\displaystyle\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}f\left(0+\frac{1-0}{n}i\right)\frac{1-0}{n}\!=\!\!\int_{0}^{1}f(x\,)\mathrm{d}x\,,}\\ &{\displaystyle\operatorname*{lim}_{n\to\infty}\sum_{i=0}^{n-1}f\left(0+\frac{1-0}{n}i\right)\frac{1-0}{n}\!=\!\!\int_{0}^{1}f(x\,)\mathrm{d}x\,.}\\ &{\displaystyle\sum_{n\to1}\!\!\!i\!\!\!\!\!}\end{array}
$$  

2.放缩形(凑不成-  

(1）夹逼准则.  

如通项中含 ${{n}^{2}}+i$ ，则凑不成 $\frac{i}{n}$ ，这时考虑对通项放缩，用夹逼准则，  

# (2）放缩后再凑 $\frac{i}{n}$  

如通项中含 $\frac{i^{2}+1}{n^{2}}$ ，虽凑不成 $\frac{i}{n}$ ，但放缩为 $\Big(\frac{i}{n}\Big)^{2}<\frac{i^{2}+1}{n^{2}}<\Big(\frac{i+1}{n}\Big)^{2}$ ，则可凑成 $\frac{i}{n}$  

#  $^{3,}$ 变量形  

若通项中含 ${\frac{x}{n}}i$ ，则考虑下面的式子：  
比亨高等数学18洲  

$$
\operatorname*{lim}_{n\to\infty}\sum_{i\mathop{=}1}^{n}f\left(0+{\frac{x-0}{n}}i\right){\frac{x-0}{n}}=\int_{0}^{x}f(t)\,\mathrm{d}t.
$$  

例 8. 6设 $f(x)=x^{2}\,,f\lbrack\varphi(x)\rbrack=-x^{2}+2x+3$ 且 $\varphi(x)\geqslant0$ ，则$\operatorname*{lim}_{n\rightarrow\infty}\frac{1}{n^{3}}\sum_{i=1}^{n}i^{2}\,(n-i)\cdot\frac{1}{n+\varphi\,(x\,)}=0\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,).$  

(A) $\frac{1}{12}$ $(\mathbf{B})\ \frac{1}{6}$ (C) 13 $(\mathrm{D})\ \frac{2}{3}$  

【解】应选(A).  

由题设， $f\!\left[\varphi(x)\right]\!=\!\varphi^{2}(x)\!=\!-x^{2}+2x+3$ ，且 $\varphi\left(x\right)\geqslant0$ ，则  

$$
\varphi(x)\!=\!\sqrt{-x^{2}+2x+3}\,,
$$  

其中 $-x^{2}+2x+3\geq0$ ，即 $(x-3)(x+1)\leqslant0$ ,解得 $-1\leqslant x\leqslant3$ ，此为 $\varphi(x)$ 的定义域.又 $(-\,x^{2}+2x+3)^{\prime}\,{=}\,{-}2x+2{\frac{\Im}{\I C}}\,0$ ,解得 $x=1$ ,故当 $-1\leqslant x<1$ 时，导数大于0；当 $1<$  $x\leqslant3$ 时,导数小于 0.所以 $\varphi(1)=2$ 为最大值， $\varphi(-1)=\varphi(3)=0$ 为最小值,即[0,2]为 $\varphi(x)$ 的值域.  

又  

$\sum_{i=1}^{n}\left({\frac{i}{n}}\right)^{2}\left(1-{\frac{i}{n}}\right){\frac{1}{n+2}}\leqslant{\frac{1}{n^{3}}}\sum_{i=1}^{n}i^{2}\left(n-i\right)\cdot{\frac{1}{n+\varphi\left(x\right)}}\leqslant\sum_{i=1}^{n}\left({\frac{i}{n}}\right)^{2}\left(1-{\frac{i}{n}}\right){\frac{1}{n}}$ ，  

且  

$$
\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}\left({\frac{i}{n}}\right)^{2}\left(1-{\frac{i}{n}}\right){\frac{1}{n}}=\!\int_{0}^{1}\!x^{\,2}\left(1-x\right)\!\,\mathrm{d}x={\frac{1}{12}},
$$  

$$
\operatorname*{lim}_{n\to\infty}{\frac{n}{n+2}}\cdot\sum_{i=1}^{n}\left({\frac{i}{n}}\right)^{2}\left(1-{\frac{i}{n}}\right){\frac{1}{n}}=1\cdot\int_{0}^{1}\!x^{\,2}\left(1-x\right)\!\mathrm{d}x={\frac{1}{12}},
$$  

故由夹逼准则得， $\operatorname*{lim}_{n\rightarrow\infty}\frac{1}{n^{3}}\sum_{i=1}^{n}i^{2}\left(n-i\,\right)\cdot\frac{1}{n+\varphi\left(x\,\right)}=\frac{1}{12}$ ,选(A).  

例8. 7 $\mathfrak{F}\,f(x\,)=\left\{\begin{array}{l l}{\displaystyle\operatorname*{lim}_{n\to\infty}\frac{1}{n}\Big(1+\cos\frac{x}{n}+\cos\frac{2x}{n}+\dotsb+\cos\frac{n-1}{n}x\Big)\,,}&{\;x>0\,,}\\ {\displaystyle\alpha\,,}&{\;x=0\,,}\\ {f(-\,x\,)\,,}&{\;x<0}\end{array}\right.$  

连续，则 $a=-$  

【解】应填1.  

当 $x>0$ 时，  

$$
\begin{array}{l}{{f(x)=\displaystyle\operatorname*{lim}_{n\to\infty}\frac{1}{n}\sum_{i=0}^{n-1}\cos\frac{x}{n}i=\displaystyle\operatorname*{lim}_{n\to\infty}\frac{1}{x}\sum_{i=0}^{n-1}\cos\frac{x}{n}i\cdot\frac{x}{n}}}\\ {{\quad\quad\quad\quad=\displaystyle\frac{1}{x}\!\int_{0}^{x}\cos\,t\,\mathrm{d}t=\!\frac{1}{x}\mathrm{sin}\,\,t\,\left|\,_{0}^{x}=\frac{\sin\,x}{x},}}\end{array}
$$  

当 $x<0$ 时， $f(x\,)=f(-\,x\,)={\frac{\sin(-\,x\,)}{-\,x}}={\frac{\sin\,x}{x}}.$  
综上所述， $\scriptstyle f(x)\,=\,\left<{\frac{\sin\,x}{x}},\right.$ x≠0’故由 $f(x)$ 连续，得 $a=\operatorname*{lim}_{x\to0}{\frac{\sin\,x}{x}}=1$ $x=0$  

例8.8 $\operatorname*{lim}_{n\to\infty}\left[{\frac{n}{n^{2}+1}}+{\frac{n}{n^{2}+1+1}}+{\frac{n}{n^{2}+1+2^{2}}}+\cdots+{\frac{n}{n^{2}+1+(n-1)^{2}}}\right]={\mathrm{-}}$ 【解】应填 $\frac{\pi}{4}$  

原式 $\operatorname*{lim}_{n\to\infty}\sum_{i=0}^{n-1}{\frac{n}{n^{2}+1+i^{2}}}=\operatorname*{lim}_{n\to\infty}\sum_{i=0}^{n-1}{\frac{1}{1+{\frac{i^{2}+1}{n^{2}}}}}\cdot{\frac{1}{n}},$  

因为 ${\frac{i^{2}}{n^{2}}}<{\frac{i^{2}+1}{n^{2}}}<{\frac{(i+1)^{2}}{n^{2}}}$ ，所以 $\displaystyle\frac{1}{1+\frac{(i+1)^{2}}{n^{2}}}<\frac{1}{1+\frac{i^{2}+1}{n^{2}}}<\frac{1}{1+\frac{i^{2}}{n^{2}}}$ 从而$\sum_{i=0}^{n-1}{\frac{1}{1+{\frac{(i+1)^{2}}{n^{2}}}}}\cdot{\frac{1}{n}}<\sum_{i=0}^{n-1}{\frac{1}{1+{\frac{i^{2}+1}{n^{2}}}}}\cdot{\frac{1}{n}}<\sum_{i=0}^{n-1}{\frac{1}{1+{\frac{i^{2}}{n^{2}}}}}\cdot{\frac{1}{n}},$   
其中 $\operatorname*{lim}_{n\to\infty}\sum_{i=0}^{n-1}{\frac{1}{1+{\frac{(i+1)^{2}}{n^{2}}}}}\cdot{\frac{1}{n}}=\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}{\frac{1}{1+{\frac{i^{2}}{n^{2}}}}}\cdot{\frac{1}{n}}=\!\int_{0}^{1}{\frac{\mathrm{d}x}{1+x^{2}}}\!=\!{\frac{\pi}{4}},$ $\operatorname*{lim}_{n\to\infty}\sum_{i=0}^{n-1}\frac{1}{1+\frac{i^{\,2}}{n^{\,2}}}\cdot\frac{1}{n}=\!\int_{0}^{1}\frac{\mathrm{d}x}{1+x^{\,2}}=\frac{\pi}{4}.$ 故 $\operatorname*{lim}_{n\to\infty}\sum_{i\mathop{=}0}^{n-1}\frac{1}{1+\frac{i^{2}+1}{n^{2}}}\cdot\frac{1}{n}\mathop{=}\frac{\pi}{4}$ 即原式 $=\frac{\pi}{4}$  

四反常积分的判敛 $\mathbb{O}{\int_{a}^{+\infty}f(x)\,\mathrm{d}x}$ 叫无穷区间上的反常积分.  

${\mathcal{Q}}{\int}_{a}^{b}f(x)\,\mathrm{d}x$ ，其中 $\operatorname*{lim}_{x\to a^{+}}f(x)=\infty,\!a$ 叫瑕点，此积分叫无界函数的反常积分.  

$^{2,}$ 判别  

$\textcircled{1}$ 判别时要求每个积分有且仅有一个奇点.  

+∞0一0般点：统称为奇点  

$\smash{\lceil\lceil\begin{array}{l l l}{1}&{1}&{\ldots}\end{array}\rfloor0<\phi<1}$ 时，收敛，p≥1时，发散， $\circledcirc$ 尺度 $\left|\int_{1}^{+\infty}{\frac{1}{{x}^{\;\rho}}}\mathrm{d}x\;{\binom{\rlap/p>1}{\rlap/p\leqslant1}}$ 时，收敛，时，发散.  
# 比亨高等数学18洲  

$\circled{3}$ 比较判别法.  

比较准则I设函数 $f(x),g(x)$ 在区间 $[a,+\infty)$ 上连续，且 $0\leqslant f(x)\leqslant g(x)(a\leqslant$  $x<+\infty)$ ，则  

，当 $\int_{a}^{+\infty}g(x)\mathop{}\!\mathrm{d}x$ 收敛时， $\int_{a}^{+\infty}f(x)\,\mathrm{d}x$ 收敛；  
b.当 $\int_{a}^{+\infty}f(x)\,\mathrm{d}x$ 发散时， $\int_{a}^{+\infty}g(x)\mathop{}\!\mathrm{d}x$ 发散.  

比较准则 Ⅱ设函数 $f(x),g(x)$ 在区间 $[a,+\infty)$ 上连续，且 $f(x)\geqslant0,g(x)>0$ ， $\operatorname*{lim}_{x\to+\infty}{\frac{f(x)}{g(x)}}=\lambda$ （有限或 $_\infty$ ），则  

a.当 $\lambda\neq0$ 时， $\int_{a}^{+\infty}f(x)\,\mathrm{d}x$ 与 $\int_{a}^{+\infty}g(x)\mathop{}\!\mathrm{d}x$ 有相同的敛散性;b.当 $\lambda=0$ 时,若 $\int_{a}^{+\infty}g(x)\mathop{}\!\mathrm{d}x$ 收敛，则 $\int_{a}^{+\infty}f(x)\,\mathrm{d}x$ 也收敛；c.当 $\lambda=\infty$ 时,若 $\int_{a}^{+\infty}g(x)\mathop{}\!\mathrm{d}x$ 发散，则 $\int_{a}^{+\infty}f(x)\,\mathrm{d}x$ 也发散  

【注】无界函数的反常积分有类似的准则.  

例8. 9 若反常积分 $\int_{1}^{+\infty}\left(\,\mathrm{e}^{-\cos{\frac{1}{x}}}-\mathrm{e}^{-1}\,\right)x^{\star}\,\mathrm{d}x$ 收敛，则 $\pmb{k}$ 的取值范围是  

【解】应填 $k<1$  

盯着 $x\rightarrow+\infty$ 看，由 $\mathbf{e}^{-\cos\frac{1}{x}}-\mathbf{e}^{-1}=\mathbf{e}^{-1}\left(\mathbf{e}^{-\cos\frac{1}{x}+1}-1\right)$ ,知当 $x\rightarrow+\infty$ 时，  

$$
\begin{array}{r}{\mathrm{e}^{-\cos\frac{1}{x}+1}-1\sim1-\cos\frac{1}{x}\sim\frac{1}{2}\cdot\frac{1}{x^{2}},}\end{array}
$$  

即原反常积分与 $\int_{1}^{+\infty}\frac{1}{x^{2-k}}\mathrm{d}x$ 同敛散，故当 $2-k>1$ ,即 $k<1$ 时,原反常积分收敛.  

例8.10已知 $\alpha>0$ ,则对于反常积分 $\int_{0}^{1}\frac{\ln x}{x^{\prime}}\mathrm{d}x$ 的敛散性的判别,正确的是(  

（A）当 $\alpha\geqslant1$ 时，积分收敛(B)当 $\alpha<1$ 时,积分收敛(C）敛散性与 $\pmb{\alpha}$ 的取值无关，必收敛 (D）敛散性与 $\pmb{\alpha}$ 的取值无关，必发散  

【解】应选(B).当 $\alpha<1$ 时，取充分小的正数 $\boldsymbol\varepsilon$ ，使得 $\alpha+\epsilon<1$ ，由于  

$$
\operatorname*{lim}_{\substack{x\to0^{+}}}\frac{\ln x}{x^{\prime}}\overset{\rightharpoonup}{=}\operatorname*{lim}_{x\to0^{+}}\ln x\,\,\overset{\ln x}{\underset{x\to0^{+}}{=}}\frac{\operatorname*{lim}}{x^{-\varepsilon}}\,\overset{\frac{1}{x}}{=}\underset{x\to0^{+}}{\operatorname*{lim}}\,\frac{\frac{1}{x}}{-\varepsilon x^{-\varepsilon-1}}=\operatorname*{lim}_{x\to0^{+}}\Bigl(-\,\frac{1}{\varepsilon}x^{\ast}\Bigr)\,=0\,,
$$  

故当 $x\to0^{+}$ 时， $\frac{1}{x^{\,a+\epsilon}}$ 是比 $\frac{\ln\,x}{x^{\prime}}$ 高阶的无穷大量,因为当 $\alpha+\varepsilon<1$ 时， $\int_{0}^{1}\frac{1}{x^{\alpha+\epsilon}}\mathrm{d}x$ 收敛，于是 $\int_{0}^{1}\frac{\ln{x}}{x^{\prime}}\mathrm{d}x$ 收敛，选项(B）正确；  
当 $\alpha\geqslant1$ 时，由于 $\operatorname*{lim}_{x\to0^{+}}{\frac{\ln\,x}{x^{\circ}}}\!=\!\infty$ ，故当 $x\to0^{+}$ 时， $\frac{1}{x^{\circ}}$ 是比 $\frac{\ln\,x}{x^{\prime}}$ 低阶的无穷大量，因为当 $\alpha\geqslant1$ 时， $\int_{0}^{1}\frac{1}{x^{\circ}}\mathrm{d}x$ 发散，于是 $\int_{0}^{1}\frac{\ln{x}}{x^{\prime}}\mathrm{d}x$ 发散。Inx是比较判别法  

例 8. 11设 $\pmb{\hat{P}}$ 为常数,若反常积分 $\int_{0}^{1}{\frac{\ln x}{x^{\,p}\left(1-x\right)^{1-p}}}\mathsf{d}x$ 收敛，则 $\pmb{\mathscr{P}}$ 的取值范围是().  

(A)(-1,1) (B $\mathrm{)(-1,2)}\qquad\qquad\mathrm{(C)(-\infty,1)}\qquad\qquad\mathrm{(D)(-\infty,2)}$  

【解】应选(A).  

原反常积分可写为 $\int_{0}^{\frac{1}{2}}\frac{\ln\,x}{x^{\,p}\,(1-x\,)^{1-p}}\mathrm{d}x+\int_{\frac{1}{2}}^{1}\frac{\ln\,x}{x^{\,p}\,(1-x\,)^{1-p}}\mathrm{d}x$ .对任意 $\varepsilon>0$ ,有 $\operatorname*{lim}_{\;x\to0^{+}}{\frac{\;{\ln\,x}\;}{\;{\frac{x^{\,p}\,(1-x\,)^{1-p}}{x^{\,p+\epsilon}}}\,{=}\,{\ln\,x}^{\,\epsilon}\,\cdot\,{\ln\,x}\,=0.\;^{(|\mathrm{\boldmath~8.10~}\#\delta)}\,{\frac{\ln\,x}{x}}\;}}$ >由于 lim(1-x)-²=1 ，故可对  

若 $\int_{0}^{\frac{1}{2}}\frac{1}{x^{p+\epsilon}}\mathrm{d}x$ 收敛,即 $\phi<1$ ,则 $\int_{0}^{\frac{1}{2}}\frac{\ln{x}}{x^{p}(1-x)^{1-p}}\mathrm{d}x$ 也收敛.  

田 $\operatorname*{lim}_{x\to1^{-}}{\frac{\ln x}{\frac{x^{\,\prime}\,(1-x\,)^{1-p}}{(1-x\,)^{-p}}}}=\,-1\neq0$ ,知若 $\int_{\frac{1}{2}}^{1}\frac{1}{(1-x)^{-p}}\mathrm{d}x$ 收敛，,即 $\scriptstyle{\phi\,>-1}$ 司 $\int_{\frac{1}{2}}^{1}\frac{\ln{x}}{x^{\mathfrak{p}}(1-x)^{1-\mathfrak{p}}}\mathrm{d}{x}$  

也收敛.故选(A).  

例 8. 12已知 $\int_{1}^{+\infty}\left[{\frac{2x^{\,3}+a x+1}{x\,(x+2)}}-(2x-4)\right]\mathrm{d}x=b\,,a\,,b$ 为常数,则 $a b=.$ 【解】应填-4ln 3.  

$$
b=\!\!\!\int_{1}^{+\infty}\,\frac{(a+8){x}+1}{x\,(x+2)}\mathrm{d}x\,,
$$  

$(a+8)x+1$ 若$\alpha+8\ne0$ ，则由 $\operatorname*{lim}_{x\to+\infty}{\frac{\overline{{x\left(x+2\right)}}}{\frac{1}{x}}}=a+8$ ，知 $\int_{1}^{+\infty}\,\frac{(a+8)x+1}{x\,(x+2)}\mathrm{d}x$ 发散,与题设矛盾，故 $\alpha=-8$ ,于是  

$$
{\begin{array}{r l}&{b=\!\!{\int_{1}^{+\infty}{\frac{1}{x\,(x+2)}}}\mathrm{d}x}\\ &{\quad=\!{\frac{1}{2}}{\Big\int_{1}^{+\infty}\left({\frac{1}{x}}-{\frac{1}{x+2}}\right)\mathrm{d}x}}\\ &{\quad=\!{\frac{1}{2}}\!\ln{\frac{x}{x+2}}\!\left|_{1}^{+\infty}\!=\!{\frac{1}{2}}\cdot{\Big(}\!-\ln{\frac{1}{3}}{\Big)}\!=\!{\frac{1}{2}}\!\ln3\,,}\end{array}}
$$  

所以 $a b=-4\ln3$  
# 第9讲一元函数积分学的计算  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/24d84dfc9d16d2a621e6d0fb94d78a44f1e0d3dc656ce3bda0f1b0e7f3f00d2c.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/67107bd05b81a5b5e0e352e22379b14edb82d332f0515368adc54efdbb917882.jpg)  
dx =ln I x I+C. x  

${\circledcirc}{\textstyle\int}\mathbf{e}^{x}\,\mathrm{d}x=\mathbf{e}^{x}+C\,;{\displaystyle\int}a^{\,x}\,\mathrm{d}x={\frac{a^{\,\prime}}{\ln\,a}}+C\,,a>0$ 且$\boldsymbol{\alpha}\neq1$   
$\begin{array}{r l}&{\tilde{\exists}\Big\lceil\sin x\mathrm{d}x=-\cos x+C_{1}\Big\rceil\cos x\mathrm{d}x=\sin x+C_{1}}\\ &{\quad\Big\lceil\tan x\mathrm{d}x=-\ln\mid\cos x\mid+C_{1}\Big\lceil\cot x\mathrm{d}x=\ln\mid\sin x\mid+C_{1}}\\ &{\quad\Big\lceil\frac{\mathrm{d}x}{\cos x}=\Big\rceil\mathrm{sec~}x\mathrm{d}x=\ln\mid\sec x+\tan x\mid+C_{1}}\\ &{\quad\Big\lceil\frac{\mathrm{d}x}{\sin x}=\Big\rceil\mathrm{csc~}x\mathrm{d}x=\ln\mid\csc x-\cot x\mid+C_{1}}\\ &{\quad\Big\lceil\sec^{2}x\mathrm{d}x=\tan x+C_{1}\Big\rceil\csc^{2}x\mathrm{d}x=-\cot x+C_{1}}\\ &{\quad\Big\lceil\sec x\mathrm{d}x=\tan x+C_{1}\Big\rceil\csc^{2}x\mathrm{d}x=-\cot x+C_{1}}\\ &{\quad\Big\lceil\sec x\tan x\deg x-\sec x+C_{1}\Big\lceil\csc x\cot x\deg x=-\csc x+C_{1}\Big\rceil}\end{array}$   
$\mathfrak{O}\lefteqn{\left\{\int\frac{1}{1+x^{\,2}}\mathrm{d}x=\arctan\,x+C\,,\right.}}$   
$\begin{array}{r l}&{\ @\left\{\int\frac{1}{\sqrt{1-x^{\,2}}}\mathrm{d}x=\arcsin\,x+C,\right.}\\ &{\qquad\left.\left\|\frac{1}{\sqrt{a^{\,2}-x^{\,2}}}\mathrm{d}x=\arcsin\frac{x}{a}+C(a>0).\right.}\end{array}$   
$\begin{array}{r l}&{\displaystyle\iint\frac{1}{\sqrt{x^{\,2}+a^{\,2}}}\mathrm{d}x=\ln(x+\sqrt{x^{\,2}+a^{\,2}})+C(\,|x|\geqslant\|a=1)\,,}\\ &{\displaystyle\iint\frac{1}{\sqrt{x^{\,2}-a^{\,2}}}\mathrm{d}x=\ln\mid x+\sqrt{x^{\,2}-a^{\,2}}\mid+C(\,|\,x\mid>\,|\,a\,|>0).}\end{array}$   
$\begin{array}{r l}&{\displaystyle\iint\frac{\mathrm{d}x}{\left(x+a\right)\left(x+b\right)}\!=\!\frac{1}{b-a}\mathrm{ln}\left|\frac{x+a}{x+b}\right|\!+C(a\neq b)\,,}\\ &{\displaystyle\iint\frac{1}{x^{2}-a^{2}}\mathrm{d}x=\!\frac{1}{2a}\mathrm{ln}\left|\frac{x-a}{x+a}\right|\!+C\left(\int\frac{1}{a^{2}-x^{2}}\mathrm{d}x=\!\frac{1}{2a}\mathrm{ln}\left|\frac{x+a}{x-a}\right|\!+C\right).}\end{array}$   
$\circledcirc\Biggl(\sqrt{a^{2}-x^{2}}\,\mathrm{d}x=\frac{a^{2}}{2}\arcsin\frac{x}{a}+\frac{x}{2}\sqrt{a^{2}-x^{2}}+C(a>\mid x\mid\geqslant0).$   
$\circledast\displaystyle{\sin^{2}x}\,{\mathrm{d}}x=\frac{x}{2}-\frac{\sin\,2x}{4}+C\left(\sin^{2}x=\frac{1-\cos\,2x}{2}\right)\,;$   
$\int\!\cos^{2}x\mathrm{d}x={\frac{x}{2}}+{\frac{\sin\ 2x}{4}}+C\left(\cos^{2}x={\frac{1+\cos\ 2x}{2}}\right),$   
$\int\!\tan^{2}{x}\mathrm{d}x=\tan\,x-x+C(\tan^{2}{x}=\sec^{2}{x}-1)\,;$  
# 陆宁高等数学18讲  

$$
\int\!\!\cot^{2}x\!\mathrm{d}x=-\cot{x}-x+C(\cot^{2}x=\csc^{2}x-1).
$$  

# 二不定积分的计算  

# 1.凑微分法  

$$
\int\!f{\big[}g(x){\big]}g^{\prime}(x)\mathrm{d}x=\!\!\int\!\!f{\big[}g(x){\big]}\mathrm{d}{\big[}g(x){\big]}\,{\xrightarrow{\,g(x)\,=\,u\,}}\!\int\!f(u)\mathrm{d}u.
$$  

【注】常用的凑微分公式：  

$\textcircled{1}$ 由于 $x\mathrm{d}x=\frac{1}{2}\mathrm{d}(x^{2})$  $\int\!x\,f(x^{\,2})\mathrm{d}x={\frac{1}{2}}\!\int\!f(x^{\,2})\mathrm{d}(x^{\,2})={\frac{1}{2}}\!\int\!f(u)\mathrm{d}u.$  $\circledcirc$ 由于 ${\sqrt{x}}\,\mathrm{d}x={\frac{2}{3}}\mathrm{d}{\Bigl(}\,x^{\,{\frac{3}{2}}}{\Bigr)}\,,{\dddot{\mathfrak{M}}}{\Biggl\int}\,{\sqrt{x}}\,f{\Bigl(}\,x^{\,{\frac{3}{2}}}{\Bigr)}\,\mathrm{d}x={\frac{2}{3}}{\Biggl\int}f{\Bigl(}\,x^{\,{\frac{3}{2}}}{\Bigr)}\,\mathrm{d}{\Bigl(}\,x^{\,{\frac{3}{2}}}{\Bigr)}={\frac{2}{3}}{\Biggl\int}f(u)\,\mathrm{d}u.$  $\textcircled{3}$ 由于 $\frac{\mathrm{d}x}{\sqrt{x}}\!=\!2\mathrm{d}(\sqrt{x}\,)$  $2\mathsf{d}(\sqrt{x}\,)\,,\frac{\mathsf{d}}{\mathsf{d}x}{\bigg\Join}\,\bigg\lceil\frac{f(\sqrt{x}\,)}{\sqrt{x}}\mathsf{d}x=2\bigg\lceil f(\sqrt{x}\,)\mathsf{d}(\sqrt{x}\,)=2\bigg\lceil f(u)\mathsf{d}u.$  $\circledast$ 由于 ${\frac{\mathsf{d}x}{x^{2}}}\!=\!\mathsf{d}\!\left(\!-{\frac{1}{x}}\right)$  ${\frac{1}{x}}\right),{\frac{\star}{\alpha}}\!\int{\frac{f\left(-{\frac{1}{x}}\right)}{{x}^{2}}}\mathrm{d}x=\!\int\!f\left(-{\frac{1}{x}}\right)\mathrm{d}\Bigl(-{\frac{1}{x}}\Bigr)\!=\!\!\int\!f(u)\mathrm{d}u.$  $\circled{5}$ 由于 $\cdot{\frac{1}{x}}\mathrm{d}x=\mathsf{d}(\ln x\,)(x>0)\,,{\frac{\#}{\mathsf{d}x}}{\bigg\[}\,{\frac{f(\ln\,x)}{x}}\mathsf{d}x={\bigg]}f(\ln\,x\,)\mathsf{d}(\ln\,x\,)=\!\int\!f(u\,)\mathsf{d}u.$  $\circled{6}$ 由于 $\mathsf{e}^{x}\mathsf{d}x=\mathsf{d}(\mathsf{e}^{x})$ 故 $\int\!\mathrm{e}^{x}f(\mathrm{e}^{x})\mathrm{d}x=\!\int\!f(\mathrm{e}^{x})\mathrm{d}(\mathrm{e}^{x})=\!\int\!f(u)\mathrm{d}u.$  

$\oslash$ 由于且 $\boldsymbol{\alpha}\neq1$ ，故  

$$
\int\!a^{x}f(a^{x})\,\mathrm{d}x={\frac{1}{\ln\,a}}\!\left[f(a^{x})\,\mathrm{d}(a^{x})={\frac{1}{\ln\,a}}\!\right]f(u)\,\mathrm{d}(u).
$$  

$\circled{8}$ 由于sin $x\mathbf{d}x=\mathbf{d}(-\cos\,x\,)$ ，故  

$$
{\int\!\sin\,x\,f(-\cos\,x\,)\,\mathrm{d}x=\,\biggl\lceil}f(-\cos\,x\,)\,\mathrm{d}(-\cos\,x\,)=\int\!f(u)\,\mathrm{d}u.
$$  

$\circledcirc$ 由于 cos $x{\mathrm{d}}x={\mathrm{d}}(\sin\,x)$ ，故 $\int\!\cos\,x\,f(\sin\,x\,)\,\mathrm{d}x=\int\!f(\sin\,x\,)\,\mathrm{d}(\sin\,x\,)=\int\!f(u\,)\,\mathrm{d}u.$  

$\circledcirc$ 由于 ${\dot{z}}{\frac{\mathrm{d}x}{\cos^{2}x}}=\sec^{2}x\mathrm{d}x=\mathbf{d}(\tan x\,)\,,{\dot{\mathbb{w}}}{\bigg\/}\,{\frac{f(\tan\,x\,)}{\cos^{2}x}}\mathrm{d}x=\int f(\tan\,x\,)\mathrm{d}(\tan\,x\,)=\int f(u\,)\mathrm{d}u.$  $\mathfrak{V}$ 由于 ${\frac{\mathrm{d}x}{\sin^{2}x}}=\csc^{2}x\mathrm{d}x=\mathrm{d}(-\cot\,x\,)$ ，故  

$$
\int{\frac{f(-\cot x)}{\sin^{2}x}}\mathrm{d}x=\!\int\!f(-\cot x)\mathrm{d}(-\cot x)=\!\int\!f(u)\mathrm{d}u.
$$  

$\textcircled{12}$ 由于 ${\frac{1}{1+x^{2}}}\mathbf{d}x=\mathbf{d}$ (arctan $_{x}$ ），故  
${\int\frac{f(\arctan{x})}{1+{x}^{2}}\mathrm{d}x}=\!\int\!f(\arctan{x})\mathrm{d}(\arctan{x})=\!\int\!f(u)\mathrm{d}u.$  $\textcircled{13}$ 由于 ${\frac{1}{\sqrt{1-x^{2}}}}\mathrm{d}x=\mathrm{d}(\arcsin\,x\,)$ ，故${\int\frac{f(\arcsin{x})}{\sqrt{1-x^{2}}}}\mathrm{d}x=\int\!f(\arcsin{x}\,)\mathrm{d}(\arcsin{x}\,)=\int\!f(u\,)\mathrm{d}u.$  

例 9. 1 $\int{\frac{x\ln\,x}{{(x^{\,2}-1)}^{\frac{3}{2}}}}\mathrm{d}x={\underline{{\phantom{\frac{1}{x^{\,2}-1}}}}}\cdot$  

【解】应填 $-{\frac{\ln\,x}{\sqrt{x^{2}-1}}}-\arcsin{\frac{1}{x}}+C.$ $\int\frac{x\ln x}{\left(x^{2}-1\right)^{\frac{3}{2}}}\mathrm{d}x$ $\begin{array}{r l}&{=\!\!\int\!\ln{x}\;\mathrm{d}\!\left(-\frac{1}{\sqrt{{x}^{2}-1}}\right)\!=\!-\frac{\ln{x}}{\sqrt{{x}^{2}-1}}\!+\!\int\!\frac{1}{x\,\sqrt{{x}^{2}-1}}\mathrm{d}{x}}\\ &{=\!-\frac{\ln{x}}{\sqrt{{x}^{2}-1}}\!-\!\int\!\frac{1}{\sqrt{1-\left(\frac{1}{x}\right)^{2}}}\mathrm{d}\!\left(\frac{1}{x}\right)\!=\!-\frac{\ln{x}}{\sqrt{{x}^{2}-1}}\!-\!\arctan\frac{1}{x}+{C}.}\end{array}$  

例9. 2 $\int\!\mathrm{e}^{r^{2}(\sin\theta+\cos\theta)^{2}}\,r^{2}\,(\cos^{2}\!\theta-\sin^{2}\!\theta\,)\,\mathrm{d}\theta=\!\frac{}{\cdot}$  

【解】应填 $\frac{1}{2}{\mathrm{e}}^{r^{2}(\sin\theta+\cos\theta)^{2}}+C$  

由于  

$$
\begin{array}{r l}&{\frac{\mathrm{d}\left[r^{2}\left(\sin\theta+\cos\theta\right)^{2}\right]}{\mathrm{d}\theta}\!=\!r^{2}\cdot2(\sin\theta+\cos\theta)(\cos\theta-\sin\theta)}\\ &{\qquad\qquad\qquad\qquad\qquad\qquad=2r^{2}(\cos^{2}\theta-\sin^{2}\theta)\,,}\end{array}
$$  

即$\operatorname{d}\!\left[r^{2}\,(\sin\theta+\cos\theta\,)^{2}\right]\!=\!2r^{2}\,(\cos^{2}\!\theta-\sin^{2}\!\theta\,)\,\mathsf{d}\theta.$ 于是  

$$
\begin{array}{r l}&{\mathrel{\phantom{=}}:\neg\mathbb{E}\!\!\!\!\to\!\!\!\frac{1}{2}\Big\lbrack\mathbf{e}^{r^{2}(\sin\theta+\cos\theta)^{2}}\cdot2r^{2}\,(\cos^{2}\!\theta-\sin^{2}\!\theta)\,\mathrm{d}\theta}\\ &{\quad\mathrm{\phantom{=}}\:\frac{1}{2}\Big\lbrack\mathbf{e}^{r^{2}(\sin\theta+\cos\theta)^{2}}\,\mathrm{d}\big[r^{2}\,(\sin\theta+\cos\theta)^{2}\big]}\\ &{\quad\mathrm{\phantom{=}}\:\frac{1}{2}\mathbf{e}^{r^{2}(\sin\theta+\cos\theta)^{2}}+C.}\end{array}
$$  

$^{2,}$ 换元法  

$$
\int\!f(x)\mathrm{d}x\,\,\frac{x=g(u)}{\phantom{\bigg[}}\int\!f\big[g(u)\big]\mathrm{d}\big[g(u)\big]=\!\int\!f\big[g(u)\big]g^{\prime}(u)\mathrm{d}u.
$$  
【注】 $\mid(1)_{\mathcal{X}}=g(u)$ 是单调可导函数，且不要忘记计算完后用反函数 $u=g^{-1}(x)$ 回代。（2）常用换元方法：  

$\textcircled{1}$ 三角函数代换一—当被积函数含有如下根式时，可作三角代换，这里 $\alpha>0$ $\begin{array}{r}{\left\{\begin{array}{l l}{\overbrace{a^{2}-x^{2}}^{\sqrt{a^{2}-x^{2}}}\xrightarrow{\ast}x=a\sin t\ ,}&{\mathrm{~|\}t\ |<\frac{\pi}{2},}\\ {\overbrace{\vphantom{a^{2}-a^{2}}\cdots\xrightarrow{\ast}x}^{\sqrt{a^{2}-x^{2}}}\ x=a\tan t\ ,}&{\mathrm{~|\}t\ |<\frac{\pi}{2},}\\ {\phantom{\frac{1}{2}}\cdots\ \xrightarrow{\ast}\ x=a\sin t\ ,}&{\mathrm{~|\!}\frac{\pi}{2}\ x>0\,,}\end{array}\right.}\end{array}$ 则$0<t<\frac{\pi}{2}$ 若 $x<0$ ,则 $\frac{\pi}{2}<t<\pi$  $\circledcirc$ 恒等变形后作三角函数代换一一 当被积函数 中 含有根式 $\sqrt{a x^{2}+b x+c}$ 时，可先化为以下三种形式 $\sqrt{\varphi^{2}(x)+k^{2}}\,,\sqrt{\varphi^{2}(x)-k^{2}}\,,\sqrt{k^{2}-\varphi^{2}(x)}$ ,再作三角函数代换。  

$\textcircled{3}$ 根式代换———当被积函数中含有 ${\sqrt[{n}]{a x+b}}\,,{\sqrt{\frac{a x+b}{c x+d}}}\,,{\sqrt[{2a\,\mathrm{e}^{b x}+c}]{a\,\mathrm{e}^{b x}+c}}$ 等根式时，一般令根式 $\sqrt{\star\,}=t$ (因为很难通过根号内换元的办法凑成平方,所以根号无法去掉)。 对既含有 $\sqrt[n]{a x+b}$ ，也含有 $\sqrt[m]{a x+b}$ 的函数，一般取 $m\,,n$ 的最小公倍数 $\iota$ ，令 $\sqrt[\prime]{a x+b}=t$  

$\circledast$ 倒代换当被积函数中分母的幂次比分子高两次及两次以上时，可作倒代换，$x={\frac{1}{t}}$  

$\circled{5}$ 复杂函数的直接代换———当被积函数中含有 $a^{\,x}$ ， $\mathbf{e}^{\tau}$ ,ln $_{x}$ ,arcsin $_{x}$ ,arctan $_{x}$ 等时，可考虑直接令复杂函数等于 $t$ ，值得指出的是，当 $\ln x$ ,arcsin $_{x}$ ,arctan $_{x}$ 与 $\scriptstyle P_{n}(x)$ 或 $\mathbf{e}^{a x}$ 作乘、除时（其中 $\scriptstyle P_{\scriptscriptstyle n}(x)$ 为 $_{x}$ 的 $_n$ 次多项式），优先考虑分部积分法。  

例 9. 3计算不定积分 $\int\ln\!\left(1+{\sqrt{\frac{1+x}{x}}}\right)\mathrm{d}x\left(x>0\right)$ (7²-1)(1 +1)++通分后代特值【=1，1=-1 【解】令 ${\sqrt{\frac{1+x}{x}}}=t$ ，则 $x={\frac{1}{t^{2}-1}}$ ，于是别得A又$\begin{array}{c}{{\displaystyle\int\!\ln\!\left(1+\sqrt{\frac{1+x}{x}}\right)\mathrm{d}x=\!\left[\ln(1+t)\mathrm{d}\!\left(\frac{1}{t^{2}-1}\right)\!=\!\frac{\ln(1+t)}{t^{2}-1}\!-\!\int\frac{1}{t^{2}-1}\cdot\frac{1}{t+1}\mathrm{d}t.}}\\ {{\displaystyle\int\frac{1}{(t^{2}-1)(t+1)}\mathrm{d}t=\frac{1}{4}\!\left[\left[\frac{1}{t-1}-\frac{1}{t+1}-\frac{2}{(t+1)^{2}}\right]\mathrm{d}t\right.}}\\ {{\displaystyle\left.-\frac{1}{4}\ln(t-1)-\frac{1}{4}\ln(t+1)+\frac{1}{2(t+1)}+C_{1},\right.}}\end{array}$  
$$
\begin{array}{l}{\displaystyle+\sqrt{\frac{1+x}{x}}\left)\,\mathrm{d}x=\frac{\ln(1+t)}{t^{2}-1}+\frac{1}{4}\ln\frac{t+1}{t-1}-\frac{1}{2(t+1)}+C\right.}\\ {\displaystyle\left.=\,x\ln\Bigl(1+\sqrt{\frac{1+x}{x}}\Bigr)+\frac{1}{2}\ln(\sqrt{1+x}+\sqrt{x})-\frac{\sqrt{x}}{2(\sqrt{1+x}+\sqrt{x})}+\frac{1}{2(t+1)}\ln(\sqrt{x}+\sqrt{x})\right\}}\end{array}
$$J1n(1  

例9. 4 $\int{\frac{\mathrm{d}x}{\left(2x^{\,2}+1\right)\,{\sqrt{x^{\,2}+1\,}}}}={\cfrac{\,}{\,}}.$  

【解】应填arctan $\frac{x}{\sqrt{1+x^{2}}}+C$ 。  

令$x=\tan\,u$ ，则 $\mathrm{d}x=\sec^{2}u\,\mathrm{d}u$  

$$
{\begin{array}{r l}&{{\scriptstyle{\left|{\overrightarrow{y}}\right|}}\cdot{\overrightarrow{x}}={\left\lceil{\frac{\mathrm{d}u}{\cos\,u\,\cdot\,(2\tan^{2}u+1)}}\right\rceil}={\left\lceil{\frac{\cos\,u\,\mathrm{d}u}{2\sin^{2}u+\cos^{2}u}}\right\rceil}}\\ &{\scriptstyle\qquad={\left\lceil{\frac{\mathrm{d}(\sin\,u)}{1+\sin^{2}u}}\right\rceil}=\arctan(\sin\,u)+C}\\ &{\scriptstyle\qquad=\arctan{\frac{x}{\sqrt{1+x^{2}}}}+C.}\end{array}}
$$  

例 9. 5求不定积分 $\int{\frac{1}{\sqrt{\mathbf{e}^{x}+1}+{\sqrt{\mathbf{e}^{x}-1}}}}\mathrm{d}x$  

【解】令 $\mathbf{e^{x}}=t$ ，则 $x=\ln{t}\,,\mathrm{d}x=\frac{1}{t}\mathrm{d}t$ ,于是  

$$
\therefore=\!\int\!{\frac{1}{{\sqrt{t+1}}+{\sqrt{t-1}}}}\cdot{\frac{1}{t}}\mathrm{d}t=\!\int{\frac{{\sqrt{t+1}}-{\sqrt{t-1}}}{2}}\cdot{\frac{1}{t}}\mathrm{d}t={\frac{1}{2}}\!\int{\frac{{\sqrt{t+1}}-{\sqrt{t-1}}}{t}}
$$  

$\frac{1}{2}\!\int\frac{\sqrt{t+1}}{t}\mathrm{d}t$ 令$\sqrt{t+1}={\pm}$ ,则  

$\begin{array}{r l}&{\frac{1}{2}\displaystyle\int\frac{\sqrt{t+1}}{t}\mathrm{d}t=\frac{1}{2}\displaystyle\int\frac{u}{u^{2}-1}\cdot2u\,\mathrm{d}u=\int\frac{u^{2}}{u^{2}-1}\mathrm{d}u}\\ &{\qquad\qquad\qquad\qquad=\displaystyle\int\frac{u^{2}-1+1}{u^{2}-1}\mathrm{d}u=u+\frac{1}{2}\mathrm{ln}\left|\frac{u-1}{u+1}\right|+C_{1}}\\ &{\qquad\qquad\qquad=\sqrt{\mathrm{e}^{x}+1}+\frac{1}{2}\mathrm{ln}\,\displaystyle\frac{\sqrt{\mathrm{e}^{x}+1}-1}{\sqrt{\mathrm{e}^{x}+1}+1}+C_{1}.}\end{array}$  

对$\frac{1}{2}\!\int\frac{\sqrt{t-1}}{t}\mathrm{d}t$ 令${\sqrt{t-1}}=\,v$ 同理有 ${\frac{1}{2}}{\bigg\lceil}{\frac{\sqrt{t-1}}{t}}\mathrm{d}t={\sqrt{\mathrm{e}^{x}-1}}-\arctan{\sqrt{\mathrm{e}^{x}-1}}+C_{2}$ 于是  

$={\sqrt{\mathbf{e}^{x}+1}}+{\frac{1}{2}}\ln{\frac{{\sqrt{\mathbf{e}^{x}+1}}-1}{{\sqrt{\mathbf{e}^{x}+1}}+1}}-{\sqrt{\mathbf{e}^{x}-1}}+\arctan{\sqrt{\mathbf{e}^{x}-1}}+C.$  

3.分部积分法  

$$
\int\!u\,\mathrm{d}v=u v-\int\!v\,\mathrm{d}u.
$$  
# 【注】u， $_{v}$ 的选取原则  

#  

相对位置在左边的宜选作 ${\pmb u}$ ，用来求导；相对位置在右边的宜选作 $_{\eqcirc}$ ，用来积分.即 $\textcircled{1}$ 被积函数为 $P_{n}(x)\mathrm{e}^{k x}\,,P_{n}(x)\mathrm{sin}\,a x\,,P_{n}(x)\mathrm{cos}\,a x$ 等形式时，一般来说选取 $\smash{\pmb{u}=\pmb{P}_{\pmb{n}}(\boldsymbol{x})}$ ； $\circledcirc$ 被积函数为 $\mathrm{e}^{a x}\sin{b x}\ ,\mathrm{e}^{a x}\cos{b x}$ 等形式时， ${\pmb u}$ 可以取其中两因子中的任意一个; $\textcircled{3}$ 被积函数为 $P_{n}(x)\ln x\,,P_{n}(x)$ arcsin $_{x}$ ,P, $\scriptstyle{\mathcal{x}}$ )arctan $_{x}$ 等形式时，一般分别选取  

u=Inx， $u=$ arcsin $_{x}$ ，${\boldsymbol{u}}=$ arctan $_{x}$ 例 9. 6 $\int\!\mathrm{e}^{x}\left(\frac{1-x}{1+x^{\,2}}\right)^{2}\mathrm{d}x=\ c\cfrac{\,.}{\,}$ 【解】应填 ${\frac{\mathrm{e}^{x}}{1+x^{2}}}+C$ $\begin{array}{r l}&{\quad\displaystyle\int\mathrm{e}^{x}\left(\frac{1-x}{1+x^{2}}\right)^{2}\mathrm{d}x}\\ &{=\!\!\int\!\mathrm{e}^{x}\cdot\frac{1+x^{2}-2x}{(1+x^{2})^{2}}\mathrm{d}x=\!\int\!\mathrm{e}^{x}\cdot\frac{1}{1+x^{2}}\mathrm{d}x-\!\int\!\mathrm{e}^{x}\cdot\frac{2x}{(1+x^{2})^{2}}\mathrm{d}x}\\ &{=\!\int\!\frac{\mathrm{e}^{x}}{1+x^{2}}\mathrm{d}x+\!\int\!\mathrm{e}^{x}\!\mathrm{d}\big(\frac{1}{1+x^{2}}\big)\!=\!\int\!\frac{\mathrm{e}^{x}}{1+x^{2}}\mathrm{d}x+\!\frac{\mathrm{e}^{x}}{1+x^{2}}\!-\!\int\!\frac{\mathrm{e}^{x}}{1+x^{2}}\mathrm{d}x}\\ &{=\!\frac{\mathrm{e}^{x}}{1+x^{2}}+\!C.}\end{array}$ 注】分部积分法可能创造出积分再现或积分抵消的情形，是积分中常见的情形.  

例 9. 7设 $_n$ 为非负整数，则 $\int_{0}^{1}x^{2}\ln^{n}x\mathrm{d}x=$  

【解】应填 $\frac{(-1)^{n}}{3^{n+1}}n!$  

记  

$$
\begin{array}{l}{\displaystyle\alpha_{n}=\!\!\left\int_{0}^{1}\!\!x^{2}\ln^{n}\!x\;\mathrm{d}x=\!\!\int_{0}^{1}\!\!\ln^{n}\!x\;\mathrm{d}\!\left(\frac{1}{3}x^{3}\right)}\\ {\displaystyle}\\ {\displaystyle}\\ {\displaystyle}\\ {\displaystyle}\end{array}\right.=\!\frac{1}{3}x^{3}\ln^{n}\!x\left[\!\!\begin{array}{l}{1}\\ {0}\end{array}\!\!-\!\int_{0}^{1}\frac{1}{3}x^{3}\star n\ln^{n-1}\!x\cdot\frac{1}{x}\mathrm{d}x\!\!\!}\\ {\displaystyle}\\ {\displaystyle}\\ {\displaystyle}\\ {\displaystyle}\end{array}\right.\operatorname*{lim}_{x^{\prime}=0}\!\!\!\!\int_{0}^{\kappa}x^{=0,\sqrt{\alpha},\beta\setminus0.}}\\ {\displaystyle}\\ {\displaystyle}\end{array}
$$  

于是 $\iota_{n}=-\,\frac{n}{3}a_{n-1}=\Big(-\frac{n}{3}\Big)\,\Big(-\frac{n-1}{3}\Big)\,a_{n-2}=\cdots=\Big(-\frac{n}{3}\Big)\,\Big(-\frac{n-1}{3}\Big)\cdots\Big(-\frac{1}{3}\Big)\,a_{0}\,,$ 又$\alpha_{0}=$ $\int_{0}^{1}x^{\,2}\,\mathrm{d}x={\frac{1}{3}}$ 故$\alpha_{n}=\frac{(-1)^{n}}{3^{n+1}}n!$  

例 9. 8设 $_n$ 为正整数，则 $\int_{0}^{\pi}\!x\,^{2}\cos\,n x\mathrm{d}x=\!\!\!\!\!-\!\!\!\!\!-\!\!\!\!\!\!.$  
【 解】 应填 $(-1)^{n}\;{\frac{2\pi}{n^{2}}}$  

$$
{\begin{array}{r l}{\displaystyle\int_{0}^{\kappa}x^{2}\cos\,n x\mathbf{d}x=\int_{0}^{\kappa}x^{2}\,\mathbf{\mathrm{q}}\left({\frac{\sin n\,x}{n}}\right)={\frac{1}{n}}x^{2}\,\cdot\,{\sin\,n x}\,\left|_{0}^{\kappa}-{\frac{2}{n}}\int_{0}^{\kappa}x\sin\,n x\mathbf{d}x\right.}\\ &{\qquad\qquad\qquad\left.=-{\frac{2}{n}}\right\lceil_{0}^{\kappa}x\left(-{\frac{\cos\,n x}{n}}\right)=-{\frac{2}{n}}\left[x\cdot\left(-{\frac{\cos\,n x}{n}}\right)\,\bigg|_{0}^{\kappa}+{\frac{1}{n}}\right\lceil_{0}^{\kappa}\cos\,n x\right.}\\ &{\qquad\qquad\qquad\left.={\frac{2\pi}{n^{2}}}(-1)^{\kappa}-{\frac{2}{n^{2}}}\right\lceil_{0}^{\kappa}\cos\,n x\mathbf{d}x}\\ &{\qquad\qquad\quad={\frac{2\pi}{n^{2}}}(-1)^{\kappa}-{\frac{2}{n^{2}}}\cdot{\frac{\sin n\,n x}{n}}\left|_{0}^{\kappa}\right.}\\ &{\qquad\qquad\quad\left.=(-1)^{\kappa}{\frac{2\pi}{n^{2}}}.}\end{array}}
$$  

【注】亦可用如下表格法：  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/96d21f98139195281a0a9fe348d0fb4e0e12463466d94359f7cad00b30f46702.jpg)  

则  

$$
\int_{0}^{\kappa}x^{2}\cos\ n x\,\mathrm{d}x=x^{2}\cdot{\frac{1}{n}}\sin\ n x\ {\bigg|}_{\circ}^{\star}+2x\cdot{\frac{1}{n^{2}}}\cos\ n x\ {\bigg|}_{\circ}^{\star}-2\cdot{\frac{1}{n^{3}}}\sin n x\ {\bigg|}_{\circ}^{\star}=(-1)^{n}
$$  

例 9. 9设 $a_{n}=\int_{0}^{2\pi}\mathrm{e}^{-x}$ sin nxdx, $n=1,2,\cdots$ 费  

(1）求 $\alpha_{n}$ 的表达式；  

(2）计算 $\operatorname*{lim}_{n\rightarrow\infty}\biggl(\frac{n\alpha_{\,n}}{1-\mathrm{e}^{-2\pi}}\biggr)^{\,n^{2}}\,.$  

【解】（1）由表格法：  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/8505e07f58a7fe59f99d98a47fcb986da0cd08522423d86d9d9029d6426d1133.jpg)  

得  

于是  

$\int\!\mathrm{e}^{-x}\sin\,n x\mathrm{d}x=-\,{\frac{\mathrm{e}^{-x}}{n}}\cos\,n x\,-\,{\frac{\mathrm{e}^{-x}}{n^{2}}}\sin\,n x\,-\,{\frac{1}{n^{2}}}\!\!\int\!\mathrm{e}^{-x}\sin\,n x\mathrm{d}x\;,$ $\int\!\mathrm{e}^{-x}\sin\,n x\mathrm{d}x\,\,{\frac{\mathrm{(}\ast\,)}{=1+n^{2}}}\,{\frac{n\,\mathrm{e}^{-x}}{1+n^{2}}}\Bigl(\cos\,n x\,+\frac{1}{n}\sin\,n x\Bigr)+C.$ $\begin{array}{l}{{\displaystyle\alpha_{n}=\!\!\!\int_{0}^{\imath\pi}\!\mathrm{e}^{-x}\sin{n x}\mathrm{d}x=-\frac{n\,\mathrm{e}^{-x}}{1+n^{\,\!2}}\Big(\!\cos{n x}+\frac{1}{n}\sin{n x}\Big)\Bigm|_{0}^{2\pi}}}\\ {{\displaystyle=-\frac{n}{1+n^{\,\!2}}\mathrm{e}^{-2\pi}+\frac{n}{1+n^{\,\!2}}\!=\!\frac{n}{1+n^{\,\!2}}(1-\mathrm{e}^{-2\pi}).}}\end{array}$  
阳等高等数学18讲  

(2)  

$\operatorname*{lim}_{n\to\infty}\Bigl(\frac{n a_{n}}{1-\mathrm{e}^{-2\pi}}\Bigr)^{n^{2}}=\!\!\operatorname*{lim}_{n\to\infty}\Bigl(\frac{n^{2}}{1+n^{2}}\Bigr)^{n^{2}}=\mathrm{e}^{n+\infty^{n^{2}\cdot\frac{n^{2}-1-n^{2}}{1+n^{2}}}}=\mathrm{e}^{-1}.$  

注】（\*）处亦可直接套用如下公式：  

$\mathbb{O}\!\int\!\!\operatorname{e}^{a x}\sin b x\,\mathrm{d}x={\frac{\displaystyle{\bigg|}\,{\mathrm{e}}^{a x}\,{\bigg)}^{\prime}\,}{a^{2}+b^{2}}}+C={\frac{a\,{\mathrm{e}}^{a x}\sin b x-b\,{\mathrm{e}}^{a x}\cos b x}{a^{2}+b^{2}}}+C\,;$ $\begin{array}{r}{\mathcal{Q}\Big\lbrack\mathrm{e}^{a x}\cos{b x}\,\mathrm{d}x=\frac{\displaystyle\bigg\rbrack(\mathrm{e}^{a x})^{\prime}\cos{b x}\,\mathrm{\Theta}(\cos{b x}\,\mathrm{)}^{\prime}}{\displaystyle\mathrm{e}^{a x}+b^{2}}+C=\frac{a\,\mathrm{e}^{a x}\cos{b x}+b\,\mathrm{e}^{a x}\sin{b x}}{a^{2}+b^{2}}+C.}\end{array}$ 于 是 有 $\int\!\mathrm{e}^{-x}\sin\,n x\,\mathrm{d}x={\frac{-\,\mathrm{e}^{-x}\sin\,n x-n\,\mathrm{e}^{-x}\cos\,n x}{(-1)^{2}+n^{2}}}+C.$  

4.有理函数的积分  

(1) 定义.  

形如 $\int\displaylimits_{Q_{m}\left(x\right)}^{P_{n}\left(x\right)}\!\mathrm{d}x\left(n<m\right)$ 的积分称为有理函数的积分,其中 $P_{n}(x),Q_{m}(x)$ 分别是 $_x$ 的妳 $_n$ 次多项式和 $m$ 次多项式.  

(2) 思想.  

若$Q_{m}\left(x\right)$ 在实数域内可因式分解,则因式分解后再把 $\frac{P_{n}(x)}{Q_{m}(x)}$ 拆成若干项最简有理分式之和.   
(3)方法.   
 $\textcircled{\mathrm{1}}Q_{m}\left(x\right)$ 的一次单因式 $(a x+b)$ 产生一项 $\frac{A}{a x+b}$   
 $\textcircled{2}Q_{m}\left(x\right)$ 的 $k$ 重一次因式 $(a x+b)^{k}$ 产生 $\pmb{k}$ 项，分别为 ${\frac{A_{1}}{a x+b}},{\frac{A_{2}}{(a x+b)^{2}}},\cdots,{\frac{A_{k}}{(a x+b)^{k}}}.$   
 $\textcircled{3}Q_{m}\left(x\right)$ 的二次单因式 $\phi x^{2}+q x+r$ 产生一项 ${\frac{A x+B}{{\dot{p}}x^{2}+q x+r}}.$  

$\textcircled{4}Q_{m}\left(x\right)$ 的 $k$ 重二次因式 $(p x^{2}+q x+r)^{k}$ 产生 $\pmb{k}$ 项，分别为  

$\frac{A_{1}x+B_{1}}{\beta x^{2}+q x+r},\frac{A_{2}x+B_{2}}{(\ p x^{2}+q x+r)^{2}},\cdots,\frac{A_{k}x+B_{k}}{(p x^{2}+q x+r)^{k}}.$ 列 9.10求 $\int{\frac{x+2}{(2x+1)(x^{2}+x+1)}}\mathrm{d}x$ 费  

【解】设 ${\frac{x+2}{(2x+1)(x^{\,2}+x+1)}}\!=\!{\frac{A}{2x+1}}\!+\!{\frac{B x+D}{x^{\,2}+x+1}}$ 通分后可得$x_{{}}+2=\!A\left(x^{{}^{2}}+x+1\right)+\left(B x+D\right)\!\left(2x+1\right),$  

代特值 $x=-\frac{1}{2},x=0,x=1$ ，得 $A=2,D=0,B=-1$ ，故  
$$
{\begin{array}{r l}&{\left\{-\int\!\!{\Bigl(}{\frac{2}{2x+1}}-{\frac{x}{x^{2}+x+1}}{\Bigr)}\,\mathrm{d}x\right\}}\\ &{\mid=\ln\mid2x+1\mid-\left\lceil{\frac{x}{x^{2}+x+1}}\!\!\!\right\rfloor{\mathrm{d}}x}\\ &{\mid=\ln\mid2x+1\mid-{\frac{1}{2}}{\Bigl\lceil}\,{\frac{(2x+1)-1}{x^{2}+x+1}}{\mathrm{d}}x\,\Bigr\rceil\cdots\mid\,{\mathrm{d}}x\leq{\mathrm{d}}{\mathrm{d}}\cdot{\mathrm{d}}x\mid+}\\ &{\mid=\ln\mid2x+1\mid-{\frac{1}{2}}{\Bigl\lceil}\,{\frac{(2x+1)-1}{x^{2}+x+1}}{\mathrm{d}}x}\\ &{\mid=\ln\mid2x+1\mid-{\frac{1}{2}}{\Bigr\lceil}\,{\frac{\mathrm{d}(x^{2}+x+1)}{x^{2}+x+1}}+{\frac{1}{2}}{\Bigr\rfloor}\,{\frac{\mathrm{d}x}{\left(x+{\frac{1}{2}}\right)^{2}+{\Bigl(}{\frac{\sqrt{3}}{2}}{\Bigr)}^{2}}}}\\ &{\mid=\ln\mid2x+1\mid-{\frac{1}{2}}\ln(x^{2}+x+1)+{\frac{1}{\sqrt{3}}}{\mathrm{artan}}\,{\frac{2x+1}{\sqrt{3}}}+c.}\end{array}}
$$  

# 三定积分的计算  

1.对称区间上的积分问题  

若函数 $f(x)$ 在对称区间 $[-\,\alpha\,,\alpha\,](a>0)$ 上连续，则  

(1) 当 $f(x)$ 为奇函数时， $\int_{-a}^{a}f(x)\,\mathrm{d}x=0$ (2）当 $f(x)$ 为偶函数时， $\int_{-a}^{a}f(x\,)\,\mathrm{d}x=2\!\!\int_{0}^{a}f(x\,)\,\mathrm{d}x\,.$  

注） $\textcircled{1}$ 上述两式常称为“偶倍奇零”.  

$\circledcirc$ 常考“通过平移后”实现“偶倍奇零”  

$$
\int_{-a}^{a}f(x\,)\mathrm{d}x=\!\int_{0}^{a}\!\big[f(x\,)+f(-x\,)\big]\mathrm{d}x\,.
$$  

[注] 上述结论的证明:  

$$
\begin{array}{l}{\displaystyle{\int_{-a}^{a}f(x\,)\,\mathrm{d}x=\frac{1}{2}\!\!\int_{-a}^{a}\left[f(x\,)+f(-\,x\,)\right]\,\mathrm{d}x}}\\ {\displaystyle{\qquad\qquad\qquad\quad=\frac{1}{2}\cdot\,2\!\!\int_{0}^{a}\left[f(x\,)+f(-\,x\,)\right]\,\mathrm{d}x}}\\ {\displaystyle{\qquad\qquad\quad=\!\!\int_{0}^{a}\left[f(x\,)+f(-\,x\,)\right]\,\mathrm{d}x\,.}}\end{array}
$$  

例 9. 11 $I=\!\!\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\,\frac{\sin^{4}x}{1+\mathrm{e}^{-x}}\mathrm{d}x=\!\!\frac{\phantom{\frac{\pi}{2}}}{\phantom{\frac{\pi}{2}}}\!\!\!.$  

【解】应填 $\frac{3\pi}{16}$  

注意到积分区间关于原点对称，则  

$$
I=\!\!\int_{0}^{\frac{\pi}{2}}\!\left[{\frac{\sin^{4}x}{1+\mathrm{e}^{-x}}}+{\frac{\sin^{4}(-x)}{1+\mathrm{e}^{-(-x)}}}\right]\mathrm{d}x=\!\int_{0}^{\frac{\pi}{2}}\!\sin^{4}x\,\mathrm{d}x={\frac{3}{4}}\cdot{\frac{1}{2}}\cdot{\frac{\pi}{2}}={\frac{3\pi}{16}}.
$$  
2.周期性下的积分问题  

设 $f(x)$ 是以 $T$ 为周期的连续函数,即 $f(x+T)=f(x)$ ,则 $\int_{a}^{a+T}f(x\,)\,\mathrm{d}x=\!\!\int_{0}^{T}f(x\,)\,\mathrm{d}x$ 更一般地，有 $\int_{a}^{a+n T}f(x\,)\,\mathrm{d}x=n\!\int_{0}^{T}f(x\,)\,\mathrm{d}x\,.$  

例9.12 $\int_{\frac{\pi}{4}}^{\frac{5\pi}{4}}(1+\cos^{2}x)\,\mathrm{d}x=-\frac{}{\phantom{5\pi}}\cdot$  

【解】应填 $\frac{3\pi}{2}$  

$$
\begin{array}{r l}&{\int_{\frac{\pi}{4}}^{\frac{5\pi}{4}}(1+\cos^{2}x\,)\,\mathrm{d}x=\!\int_{\frac{\pi}{4}}^{\frac{5\pi}{4}}\!1\,\mathrm{d}x+\int_{\frac{\pi}{4}}^{\frac{5\pi}{4}}\cos^{2}x\mathrm{d}x=\pi+\!\int_{-\frac{\pi}{2}}^{\frac{\pi}{2}}\cos^{2}x\mathrm{d}x}\\ &{\qquad\qquad\qquad\qquad=\pi+2\!\int_{0}^{\frac{\pi}{2}}\cos^{2}x\mathrm{d}x=\pi+2\times\frac{1}{2}\times\frac{\pi}{2}\!=\!\frac{3\pi}{2}.}\end{array}
$$  

例9.13函数 $F(x)=\int_{x}^{x+2\pi}f(t)\,\mathrm{d}t$ ,其中 $f(t)\,{=}\,{\mathrm{e}}^{\sin^{2}\!t}\,(1\,{+}\,\sin^{2}\!t\,)\cos\,2\!t$ ，则 $F(x)$ （）  

（A）为正常数(B)为负常数(C）恒为零(D)不是常数  

【解】应选(B).  

由于被积函数连续且以 $\pi$ 为周期( $?2\pi$ 也是周期),故 $F(x\,)\!=\!F(0)\!=\!\!\int_{0}^{2\pi}f(t\,)\,\mathrm{d}t\!=\!2\!\!\int_{0}^{\pi}f(t\,)\,\mathrm{d}t\,,$ 即 $F(x)$ 为常数.由于被积函数是变号的,为确定积分值的符号,可通过分部积分转化为被积函数定号的情形，即  

$$
\begin{array}{r l}&{2\Biggl\int_{0}^{\pi}f(t)\,\mathrm{d}t=\Biggl\int_{0}^{\pi}\!\mathrm{e}^{\sin^{2}t}(1+\sin^{2}t)\,\mathrm{d}(\sin2t)}\\ &{\qquad\qquad=\mathrm{e}^{\sin^{2}t}(1+\sin^{2}t)\sin2t\,\Biggr|_{0}^{\pi}-\Biggl\int_{0}^{\pi}\!\sin2t\,\mathrm{d}\bigl[\mathrm{e}^{\sin^{2}t}(1+\sin^{2}t)\bigr]}\\ &{\qquad\qquad=-\Biggl\int_{0}^{\pi}\!\sin^{2}2t\,\mathrm{e}^{\sin^{2}t}(2+\sin^{2}t)\,\mathrm{d}t<0,}\end{array}
$$  

故 $F(x)$ 为负常数.  

# 3.区间再现下的积分问题  

设以下抽象函数均为连续函数.  

$$
\int_{a}^{b}f(x\,)\mathrm{d}x=\!\int_{a}^{b}f(a+b-x\,)\mathrm{d}x\,.
$$  

$$
\int_{a}^{b}f(x\,)\mathrm{d}x={\frac{1}{2}}{\Bigl\lceil}_{a}^{b}{\bigl[}f(x\,)+f(a+b-x\,){\bigr]}\mathrm{d}x\,.
$$  

$$
\int_{a}^{b}f(x\,)\mathrm{d}x=\!\!\int_{a}^{\frac{a+b}{2}}\!\big[f(x\,)+f(a+b-x\,)\big]\mathrm{d}x\,.
$$  

【注】 $\textcircled{1}$ (1)的证明:令 $x=a+b-t$ ，则  

$$
\int_{a}^{b}f(x\,)\,\mathrm{d}x=\!\!\int_{b}^{a}f(a+b-t)(-\,\mathrm{d}t)=\!\!\int_{a}^{b}f(a+b-t)\,\mathrm{d}t=\!\!\int_{a}^{b}f(a+b-x\,)\,\mathrm{d}x\,.
$$  
# 此结论称为区间再现公式  

$\circledcirc$ 由上述结论，等式两边相加，再除以2，有公式（2）：  

$$
\int_{a}^{b}f(x)\mathrm{d}x={\frac{1}{2}}{\Bigl\lceil}_{a}^{b}{\bigl[}f(x)+f(a+b-x){\bigr]}\mathrm{d}x\,.
$$  

$\textcircled{3}$ 令$F(x)=f(x)+f(a+b-x)$ ，则 $F(a+b-x)=f(a+b-$  

$x)+f(x)=F(x)$ ，故 $F(x)$ 以 $x=\frac{a+b}{2}$ 为对称轴,故又有公式  

$$
\gimel\int_{a}^{b}f(x\,)\,\mathrm{d}x=\!\!\int_{a}^{\frac{a+b}{2}}[f(x\,)+f(a+b-x\,)]\,\mathrm{d}x\,.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f4d5943f078366264ea0ee87a3b81815e80594de7f5a1541737c21da82a13f11.jpg)  

$$
\int_{0}^{\pi}\!x\,f(\sin x\,)\,\mathrm{d}x={\frac{\pi}{2}}{\int_{0}^{\pi}}f(\sin x\,)\,\mathrm{d}x\,.
$$  

【注】由“公式（2)”，有  

$$
\begin{array}{l}{{\displaystyle{\int_{0}^{\pi}}x\,f(\sin x)\,{\mathrm{d}}x=\frac{1}{2}{\displaystyle{\int_{0}^{\pi}}\!\left\{x\,f(\sin x)+(\pi-x)\,f\big[\sin(\pi-x)\big]\right\}}\,{\mathrm{d}}x}}\\ {{\displaystyle{\qquad\qquad\qquad=\frac{1}{2}{\displaystyle{\int_{0}^{\pi}}\!\left[x\,f(\sin x)+\pi f(\sin x)-x\,f(\sin x)\right]}\,{\mathrm{d}}x}}}\\ {{\displaystyle{\qquad\qquad=\frac{\pi}{2}{\displaystyle{\int_{0}^{\pi}}\!f(\sin x)\,{\mathrm{d}}x}\,.}}}\end{array}
$$  

$$
\int_{0}^{\pi}\!x\,f(\sin x\,)\,\mathrm{d}x=\pi\!\int_{0}^{\frac{\pi}{2}}f(\sin x\,)\,\mathrm{d}x\,.
$$  

【注】由“公式 $(3)^{\bullet}$ ，有  

$$
\begin{array}{r l r}{\lefteqn{\int_{0}^{\pi}\!x f(\sin x)\,\mathrm{d}x=\!\!\int_{0}^{\frac{\pi}{2}}\!\left\{x f(\sin x)+(\pi-x)f\big[\sin(\pi-x)\big]\right\}\mathrm{d}x}}\\ &{}&{\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ }\\ &{}&{\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ }\\ &{}&{=\!\!\left\lceil{\frac{\pi}{2}}\!\left(\sin x\right)+\pi f(\sin x)-x f(\sin x)\right\rceil\!\!\right\}\!\mathrm{d}x}\\ &{}&{=\!\!\left\lceil{\frac{\pi}{8}}\!\left(f(\sin x)+\pi f(\sin x)\right)\!\!\right\rceil\!\!\!\!\!\!\!\mathrm{d}x.}\end{array}
$$  

$$
\int_{0}^{\frac{\pi}{2}}f(\sin x\,)\mathrm{d}x=\!\int_{0}^{\frac{\pi}{2}}f(\cos x\,)\mathrm{d}x\,.
$$  

【注】由“公式（1)”，有  

$$
\begin{array}{r l}&{\int_{0}^{\frac{\pi}{2}}f(\sin x)\,\mathrm{d}x\!=\!\displaystyle\int_{0}^{\frac{\pi}{2}}f\left[\sin\!\left(\frac{\pi}{2}-x\right)\right]\mathrm{d}x}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=\!\displaystyle\int_{0}^{\frac{\pi}{2}}f(\cos x)\,\mathrm{d}x\,.}\end{array}
$$  

$$
\int_{0}^{\frac{\pi}{2}}f(\sin x\,,\cos x\,)\,\mathrm{d}x=\!\int_{0}^{\frac{\pi}{2}}f(\cos x\,,\sin x\,)\,\mathrm{d}x\,.
$$  
比亨高等数学18洲  

【注】由“公式 $(1)^{\bullet}$ ,有  

$$
\begin{array}{r l r}{\lefteqn{\int_{0}^{\frac{\pi}{2}}f(\sin x\,,\cos x\,)\,\mathrm{d}x\!=\!\!\int_{0}^{\frac{\pi}{2}}f\left[\sin\!\left(\frac{\pi}{2}-x\right),\cos\!\left(\frac{\pi}{2}-x\right)\right]\,\mathrm{d}x}}\\ &{}&{=\!\!\int_{0}^{\frac{\pi}{2}}f(\cos x\,,\sin x\,)\,\mathrm{d}x\,.}\end{array}
$$  

例9.14 $I=\!\!\int_{0}^{1}\frac{\ln(1+x\,)}{1+x^{2}}\mathrm{d}x=\!\!\!\!\!\!\!\!-\!\!\!\!\!\!\!.$  

【解】应填 $\frac{\pi}{8}\ln\,2$  

令$x=\tan t$ ，则  

$$
\begin{array}{r l}&{I=\!\!\int_{0}^{\frac{\pi}{4}}\!\!\ln(1+\tan\iota)\mathrm{d}t\,\frac{\circledast\,u=\frac{\pi}{4}-t}{\sqrt{\frac{\pi}{6}}\ln\left[1+\tan\!\left(\frac{\pi}{4}-u\right)\right]\,\mathrm{d}u}}\\ &{\quad=\!\!\int_{0}^{\frac{\pi}{4}}\!\!\ln\!\left(1+\frac{1-\tan u}{1+\tan u}\right)\mathrm{d}u=\!\!\int_{0}^{\frac{\pi}{4}}\!\!\ln\frac{2}{1+\tan u}\mathrm{d}u}\\ &{\quad=\!\frac{\pi}{4}\ln2-I\,,}\end{array}
$$  

愛得 $I=\frac{\pi}{8}\ln{2}$  

例 9. 15 $\int_{0}^{\pi}\!x\;\sqrt{\cos^{2}\!x-\cos^{4}\!x}\;\mathrm{d}x=\!\frac{}{\phantom{\frac{1}{\cos^{2}\!(x)+1}}}\!\!\!.$  

【解】应填 $\frac{\pi}{2}$  

$$
\begin{array}{r}{\begin{array}{c}{\displaystyle\int_{0}^{\kappa}x\,\sqrt{\cos^{2}x-\cos^{4}x}\,\mathrm{d}x=\!\!\int_{0}^{\frac{\kappa}{2}}x\,\sqrt{\cos^{2}x\,\cdot\,(1-\cos^{2}x\,)}\,\mathrm{d}x}\\ {\displaystyle=\!\!\int_{0}^{\kappa}x\,\sqrt{(1-\sin^{2}x\,)\cdot\sin^{2}x}\,\mathrm{d}x}\\ {\displaystyle_{0}^{\kappa}\chi(\sin\,x)\mathrm{d}x\,\mathrm{d}\tau_{0}^{\frac{\kappa}{2}}f(\sin x)\mathrm{d}x\quad\overset{}{\iff}=\pi\bigg\lceil_{0}^{\frac{\kappa}{2}}\sqrt{(1-\sin^{2}x\,)\cdot\sin^{2}x}\,\mathrm{d}x}\\ {\displaystyle=\pi\bigg\lceil_{0}^{\frac{\kappa}{2}}\cos\,x\,\cdot\,\sin\,x\,\mathrm{d}x=\pi\cdot\,\frac{1}{2}\sin^{2}x\,\bigg\rceil_{0}^{\frac{\kappa}{2}}=\frac{\pi}{2}.}\end{array}}\end{array}
$$  

4.华里士公式  

$$
\begin{array}{r l}&{\int_{0}^{\frac{\pi}{2}}\sin^{n}x\mathrm{d}x=\!\!\int_{0}^{\frac{\pi}{2}}\cos^{n}x\mathrm{d}x}\\ &{\qquad\qquad=\!\!\left\{\!\!\frac{n-1}{n}\cdot\frac{n-3}{n-2}\cdot\cdots\cdot\frac{2}{3}\cdot1,\quad n\,\,\mathcal{M}\!\right\}\!\!\mathcal{K}\!\!\ne\!\mathbb{1}\,\,\|\!\!\hat{\mathbf{y}}\|_{\mathbb{R}}^{\ne}\!\!\!\right\}\!\!\!\frac{\kappa}{3!}}\\ &{\qquad\qquad\qquad\left|\!\!\frac{n-1}{n}\cdot\frac{n-3}{n-2}\cdot\cdots\cdot\frac{1}{2}\cdot\frac{\pi}{2},\quad n\,\,\mathcal{M}\!\right\}\!\!\mathbb{H}\!\!\right\}\!\!\!\frac{\kappa}{3!}\!\!\!\!\!\Delta\!\!t.}\end{array}
$$  
$\int_{0}^{\pi}\sin^{\pi}x\mathrm{d}x=\left\{\!\!\!\begin{array}{l l}{\displaystyle2\cdot\frac{n-1}{n}\cdot\frac{n-3}{n-2}\cdot\dots\cdot\frac{2}{3}\cdot1,}&{\ n\ \mathcal{k}\mathcal{k}\mp1\ \#\frac{\not\log4}{\not\log4}\frac{\not\log4}{\mathcal{k}\Lambda},}\\ {\displaystyle2\cdot\frac{n-1}{n}\cdot\frac{n-3}{n-2}\cdot\dots\cdot\frac{1}{2}\cdot\frac{\pi}{2},}&{n\ \mathcal{k}\mp\frac{\not\log4}{\mathcal{k}\bot}\frac{\not\log4}{\mathcal{k}}.}\end{array}\right.$  $\int_{0}^{\pi}\cos^{n}x\mathrm{d}x=\!\left\{2\cdot{\frac{n-1}{n}}\cdot{\frac{n-3}{n-2}}\cdot\cdots\cdot{\frac{1}{2}}\cdot{\frac{\pi}{2}},$  $_n$ 为正奇数， $_n$ 为正偶数。  

$$
\int_{0}^{2\pi}\cos^{n}\!x\mathrm{d}x=\!\int_{0}^{2\pi}\!\sin^{n}\!x\mathrm{d}x=\!\left\{4\cdot{\frac{n-1}{n}}\cdot{\frac{n-3}{n-2}}\cdot\cdots\cdot{\frac{1}{2}}\cdot{\frac{\pi}{2}},
$$  

(11)  

例 9. 16设 $f(x)$ 为连续函数, $\int_{0}^{\frac{\pi}{4}}f(2x\,)\mathrm{d}x-f(x\,)\!=\!\cos^{4}x$ ,则 $\int_{0}^{\frac{\pi}{2}}f(x)\mathop{}\!\mathrm{d}x=\!.$  

[解 应填 $\frac{3\pi}{4(\pi-4)}$  

$$
\begin{array}{r l}{\displaystyle\int_{0}^{\frac{\pi}{2}}f(x)\,\mathrm{d}x=\int_{0}^{\frac{\pi}{2}}\left[f(x)+\cos^{4}x\right]\,\mathrm{d}x-\int_{0}^{\frac{\pi}{2}}\cos^{4}x\,\mathrm{d}x}&{}\\ {\displaystyle}&{=\int_{0}^{\frac{\pi}{2}}\left[\displaystyle\int_{0}^{\frac{\pi}{2}}f(2x)\,\mathrm{d}x\right]\,\mathrm{d}x-\frac{3}{4}\cdot\frac{1}{2}\cdot\frac{\pi}{2}}\\ {\displaystyle}&{\frac{\,\Phi\,2\pi-t}{2\,\mathrm{d}x-d t}\int_{0}^{\frac{\pi}{2}}\left[\displaystyle\frac{1}{2}\int_{0}^{\frac{\pi}{2}}f(t)\,\mathrm{d}t\right]\,\mathrm{d}x-\frac{3\pi}{16}}\\ {\displaystyle}&{=\frac{1}{2}\displaystyle\int_{0}^{\frac{\pi}{2}}f(t)\,\mathrm{d}t\cdot\Biggl\int_{0}^{\frac{\pi}{2}}\mathrm{d}x-\frac{3\pi}{16}}\\ {\displaystyle}&{=\frac{\pi}{4}\int_{0}^{\frac{\pi}{2}}f(t)\,\mathrm{d}t-\frac{3\pi}{16},}\end{array}
$$  

$$
\int_{0}^{\frac{\pi}{2}}f(x)\mathrm{d}x=\!\frac{-\frac{3\pi}{16}}{1-\displaystyle\frac{\pi}{4}}\!=\!\frac{3\pi}{4(\pi-4)}.
$$  

例 9.17设数列 $\scriptstyle\left\{a_{n}\right\}$ 的通项 $a_{n}=\!\!\int_{0}^{+\infty}\,\frac{\mathrm{d}x}{(1+x^{2})^{n}},n=2,3,\cdots,$ 计算 $\operatorname*{lim}_{n\to\infty}\left(\frac{a_{n+1}}{a_{n}}\right)^{\ln(1+e^{2n})}.$  

【解】 $a_{\mathfrak{n}}=\!\!\int_{0}^{+\infty}\,\frac{\mathrm{d}x}{(1+x^{\,2})^{n}}\,\frac{\oplus\,x\,=\,\tan\iota}{\int_{0}^{\frac{\mathfrak{n}}{2}}\,\frac{\sec^{2}\!t}{(\sec^{2}\!t\,)^{n}}\mathrm{d}t}=\!\!\int_{0}^{\frac{\mathfrak{n}}{2}}\cos^{2n-2}t\,\mathrm{d}t.$ $\begin{array}{r}{\frac{\alpha_{n+1}}{\alpha_{n}}\!=\!\frac{\displaystyle\int_{0}^{\frac{\kappa}{2}}\cos^{2n}{t}\,\mathrm{d}{t}}{\displaystyle\int_{0}^{\frac{\kappa}{2}}\cos^{2n-2}{t}\,\mathrm{d}{t}}\!=\!\frac{(2n-1)!!}{(2n)!!}\cdot\frac{\pi}{2}\cdot\frac{(2n-2)!!}{(2n-3)!!}\cdot\frac{2}{\pi}\!=\!\frac{2n-1}{2n},}\end{array}$ $\begin{array}{r l r}{\lefteqn{\operatorname*{lim}_{n\to\infty}\biggl(\frac{\alpha_{n+1}}{\alpha_{n}}\biggr)^{\mathrm{\!\!ln(1+\mathrm{e}^{2n})}}=\!\!\operatorname*{lim}_{n\to\infty}\biggl(1-\frac{1}{2n}\biggr)^{\mathrm{\!\!ln(1+\mathrm{e}^{2n})}}}}\\ &{}&\\ &{}&{\qquad=\mathrm{e}^{\mathrm{\!\!\!\min(1+\mathrm{e}^{2n})\cdot\bigl(-\frac{1}{2n}\bigr)}}=\mathrm{e}^{\mathrm{\!\!\!\min{\frac{\ln(1+\mathrm{e}^{2n})}{\ln\mathrm{e}^{2n}}}\cdot\ln\mathrm{e}^{2n}\cdot(-\frac{1}{2n})}}}\end{array}$  

于是  
# 化亨高等数学18讲  

$$
\begin{array}{r l}&{\qquad\operatorname*{lim}\,2n\cdot(-\frac{1}{2n})}\\ &{={\mathrm{e}}^{n\cdots\infty}}\end{array}={\bf e}^{-1}.
$$  

5.定积分分部积分法中的“升阶”“降阶”问题  

例 9. 18设 $f(x\,)=\operatorname*{lim}_{t\to\infty}\!t^{\,2}\sin\,{\frac{\,x\,}{t}}\,\cdot\,\left[g\left(2x+{\frac{1}{t}}\right)-g\left(2x\,\right)\right]$ ，且 $g(x)$ 的一个原函数为 $\ln(x+1)$ ，求 $\int_{0}^{1}f(x)\,\mathrm{d}x$  

【解】由题设知， $f(x\,)=\!\!\operatorname*{lim}_{t\to\infty}{\frac{\sin{\frac{x}{t}}}{\frac{x}{t}}}\cdot x\,\cdot{\frac{g\left(2x+{\frac{1}{t}}\right)-g(2x\,)}{\frac{1}{t}}},$ 由于  

$$
\operatorname*{lim}_{t\to\infty}\frac{\sin\frac{x}{t}}{\frac{x}{t}}=1\,,\operatorname*{lim}_{t\to\infty}\frac{g\left(2x+\frac{1}{t}\right)-g\left(2x\,\right)}{\frac{1}{t}}=g^{\prime}(2x\,)\,,
$$  

故$f(x){=}x g^{\prime}(2x)$ ，则  

$$
\begin{array}{l}{{\displaystyle\int_{0}^{1}\!f(x)\mathrm{d}x=\!\!\int_{0}^{1}\!\!x g^{\prime}(2x)\mathrm{d}x\,\frac{\Phi\,2x=t}{6}{\frac{t}{2}}\!\left[^{2}\!,{\frac{t}{2}}g^{\prime}(t)\cdot\frac{1}{2}\mathrm{d}t=\!\frac{1}{4}\!\right]\!_{0}^{2}\!x\,\mathrm{d}\!\left[g(x)\right]}}\\ {{\displaystyle~~~~~~~~~~~~~~~~=\!\frac{1}{4}\!\left[x g(x)\left|_{0}^{2}-\int_{0}^{2}\!g(x)\mathrm{d}x\right]\!=\!\frac{1}{4}\!\left[x\cdot\frac{1}{1+x}-\ln(x+1)\right]\,\right|_{0}^{2}}}\\ {{\displaystyle~~~~~~~~~~~~~=\!\frac{1}{4}\!\left(\frac{2}{3}-\ln3\right)\!=\!\frac{1}{6}-\frac{1}{4}\mathrm{ln}~3.}}\end{array}
$$  

[注 仔细观察解题过程便可发现,已知的是 $\int\!g(x\,)\,\mathrm{d}x$ ,而起点是 $g^{\prime}(x)$ ,要用分部积分法，将 $g^{\prime}(x)$ 变为 $_{g}(x)$ ,再变为 $\int\!g(x)\,\mathrm{d}x$ ，这叫“降阶”.  

例 9. 19设 $f(x)=\int_{0}^{x}\mathbf{e}^{-t^{2}+2t}\,\mathrm{d}t$ 求 $\int_{0}^{1}(x-1)^{2}\,f(x)\,\mathrm{d}x\,.$  

【解】由题设知， $f(0)=0\,,f^{\prime}(x)=\mathrm{e}^{-x^{2}+2x}$ ,则  

$$
{\begin{array}{r l}&{{\big|}_{\mathfrak{o}}^{1}(x-1)^{2}f(x)\mathrm{d}x={\frac{1}{3}}(x-1)^{3}f(x){\bigg|}_{\mathfrak{o}}^{1}-{\frac{1}{3}}{\bigg|}_{\mathfrak{o}}^{1}(x-1)^{3}f^{\prime}(x)\mathrm{d}x}\\ &{\qquad\qquad\qquad\qquad=-{\frac{1}{3}}{\bigg\lceil}_{\mathfrak{o}}^{1}(x-1)^{3}\mathrm{e}^{-x^{2}+2x}\mathrm{d}x=-{\frac{1}{6}}{\bigg\lceil}_{\mathfrak{o}}^{1}(x-1)^{2}\mathrm{e}^{-(x-1)^{2}+1}\mathrm{d}\big[(x-1)^{2}\mathrm{e}^{-x^{2}+2x}\mathrm{d}x\big]}\\ &{\qquad\qquad\qquad\qquad\qquad\qquad-{\frac{6}{6}}{\bigg\lceil}_{1}^{0}\mathrm{e}^{-t}\mathrm{d}t}\\ &{\qquad\qquad\qquad={\frac{1}{6}}(\mathrm{e}-2).}\end{array}}
$$  

【注 知道了 $f^{\prime}(x)$ 的表达式,便想到用分部积分法,使得 $\int_{0}^{1}(x-1)^{2}f(x)\mathrm{d}x$ 中的 $f(x)$ 作为 $\pmb{u}$ (求导)的身份,出现 $f^{\prime}(x)$ ,这叫“升阶”.  
6.分段函数的定积分  

例 9. 20设 $f(x)={\binom{\mathbf{e}^{-x}\,,}{1+x^{2}\,,}}\quad x\geqslant0\,,\quad\forall\!\!\!\!\parallel\!\!\int_{-2}^{2}f(x-1)\mathrm{d}x=\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\$  

【解】应填 $13-\mathrm{e}^{-1}$  

# 在积分中作变量代换，令 $x-1\,{=}\,t$ ,有  

$$
\begin{array}{l}{\displaystyle\int_{-2}^{2}f(x-1)\mathrm{d}x=\!\!\int_{-3}^{1}f(t)\mathrm{d}t=\!\!\int_{-3}^{0}f(t)\mathrm{d}t+\int_{0}^{1}f(t)\mathrm{d}t}\\ {\displaystyle\qquad\qquad\qquad\qquad=\!\!\int_{-3}^{0}(1+t^{2})\mathrm{d}t+\int_{0}^{1}\!\mathrm{e}^{-t}\,\mathrm{d}t}\\ {\displaystyle\qquad\qquad\qquad=\!\left(t+\frac{t^{3}}{3}\right)\Bigm|_{-3}^{0}-\mathrm{e}^{-t}\Bigm|_{0}^{1}=13-\mathrm{e}^{-1}.}\end{array}
$$  

例 9. 21 $\begin{array}{c}{{\overline{{{\bf\Lambda}}}^{\bullet}\ l{\bf{n}}^{\;4}\ l{\bf{e}}^{x}\ l{\bf{d}}x=\ l}}\\ {{\circ}}\end{array}.$  $\{\mathsf{\Gamma}\}\mathsf{e}^{x}\,\mathsf{J}$ 表示不超过 $\mathbf{e}^{x}$ 的最大整数)  

【解】应填 $\ 5\ln\,2-\ln\,3$  

当 $0\leqslant x\leqslant\ln4$ 时，有 $1\leqslant\mathsf{e}^{x}\leqslant4$ ，以 ${\bf e}^{x}=1,2,3,4$ 来划分 $[0,\ensuremath{\mathrm{ln}}4]$ ，则  

$$
\begin{array}{r l}&{\Vec{\mathfrak{x}}{=}\!\!\int_{0}^{\ln2}\!\big[\mathrm{e}^{x}\big]{\mathrm{d}}x+\int_{\ln2}^{\ln3}\!\big[\mathrm{e}^{x}\big]{\mathrm{d}}x+\int_{\ln3}^{\ln4}\!\big[\mathrm{e}^{x}\big]{\mathrm{d}}x}\\ &{\quad{=}\!\!\int_{0}^{\ln2}\!1{\mathrm{d}}x+\!\int_{\ln2}^{\ln3}\!2{\mathrm{d}}x+\!\int_{\ln3}^{\ln4}\!\!\!\mathrm{d}x}\\ &{\quad{=}\!\!\ln2+2(\ln3-\ln2)+3(\ln4-\ln3)}\\ &{\quad{=}5\!\ln2-\ln3.}\end{array}
$$  

四变限积分的计算  

1.求分段函数的变限积分  

例 9. 22设 $f(x)=\left\{{2x+{\frac{3}{2}}x^{2}},\ -1\leqslant x<0,\right.$ 求函数 $F(x)=\int_{-1}^{x}f(t)\mathrm{d}t$ 的表达式.  

【解】当 $x\in[-1,0)$ 时，  

$$
F(x)=\!\!\int_{-1}^{x}f(t)\,\mathrm{d}t=\!\!\int_{-1}^{x}\!\left(2t+{\frac{3}{2}}t^{2}\right)\mathrm{d}t=\!\left(t^{2}+{\frac{1}{2}}t^{3}\right)\,\left|\,{\frac{\imath}{-1}}={\frac{1}{2}}x^{3}+x^{2}-{\frac{1}{2}};
$$  

当 $x\in[0,1]$ 时，  

$$
\begin{array}{l}{{\displaystyle F(\boldsymbol{x})=\int_{-1}^{\boldsymbol{x}}f(t)\mathrm{d}t=\int_{-1}^{0}f(t)\mathrm{d}t+\int_{0}^{\boldsymbol{x}}f(t)\mathrm{d}t=\left(t^{2}+\frac{1}{2}t^{3}\right)\left.\left|\mathbf{\eta}_{-1}^{0}+\int_{0}^{\boldsymbol{x}}\frac{t\mathrm{e}^{t}}{(\mathrm{e}^{t}+1)^{2}}\mathrm{d}t\right.}}\\ {{\displaystyle\left.\qquad=-\frac{1}{2}+\int_{0}^{\boldsymbol{x}}(-t)\mathrm{d}\biggl(\frac{1}{\mathrm{e}^{t}+1}\biggr)=-\frac{1}{2}-\frac{t}{\mathrm{e}^{t}+1}\right|\mathbf{\eta}_{0}^{x}+\int_{0}^{\boldsymbol{x}}\frac{\mathrm{d}t}{\mathrm{e}^{t}+1}}}\end{array}
$$  
# 比宁高等数学18讲  

$$
\begin{array}{l l}{\displaystyle}&{\displaystyle=-\frac{1}{2}-\frac{x}{\mathrm{e}^{\prime}+1}+\int_{0}^{x}\frac{\mathrm{d}(\mathrm{e}^{\prime})}{\mathrm{e}^{\prime}\,(\mathrm{e}^{\prime}+1)}=-\frac{1}{2}-\frac{x}{\mathrm{e}^{\prime}+1}+\int_{0}^{x}\left(\frac{1}{\mathrm{e}^{\prime}}-\frac{1}{\mathrm{e}^{\prime}+1}\right)\mathrm{d}\mathrm{e}^{\prime}}\\ {\displaystyle}&{\displaystyle=-\frac{1}{2}-\frac{x}{\mathrm{e}^{x}+1}+\ln\frac{\mathrm{e}^{\prime}}{\mathrm{e}^{\prime}+1}\left|\mathbf{\eta}_{0}^{x}=-\frac{1}{2}-\frac{x}{\mathrm{e}^{\prime}+1}+\ln\frac{\mathrm{e}^{x}}{\mathrm{e}^{\prime}+1}-\ln\frac{1}{2},}\end{array}
$$  

$$
\begin{array}{r}{F(x)=\!\!\left\{\!\!\begin{array}{l l}{\!\!\displaystyle\frac{x^{3}}{2}+x^{\,2}-\frac{1}{2},}&{-\,1\leqslant x<0\,,}\\ {\!\!\displaystyle\ln\frac{\mathrm{e}^{x}}{\mathrm{e}^{x}+1}\!-\!\frac{x}{\mathrm{e}^{x}+1}\!+\!\ln\,2\!-\!\frac{1}{2},}&{0\leqslant x\leqslant1.}\end{array}\!\!\right.}\end{array}
$$  

所以  

# 2.直接求导型  

可直接用下述求导公式（I），（Ⅱ）求导的积分称为直接求导型.  

$$
\begin{array}{r l}&{\textrm{(I)}\bigg[\!\!\int_{a}^{\varphi(x)}\!\!f(t)\mathrm{d}t\bigg]_{x}^{\prime}=f\big[\varphi(x)\big]\bullet\varphi^{\prime}(x).}\\ &{\textrm{(I)}\bigg[\!\!\int_{\varphi_{1}(x)}^{\varphi_{2}(x)}\!\!f(t)\mathrm{d}t\bigg]_{x}^{\prime}=f\big[\!\!\int_{\varphi_{2}(x)}\!\!\big]\bullet\varphi_{2}^{\prime}(x)-f\big[\!\!\int_{\varphi_{1}(x)}\!\!\big]\varphi_{1}^{\prime}(x).}\end{array}
$$  

例 9. 23设函数 $f(x)$ 在 $[0,+\infty)$ 内可导， $f(0)=\,0$ ,且其反函数为 $g(x)$ 若 $\int_{0}^{f(x)}g(t)\mathrm{d}t=$ $x^{2}e^{x}$ ,求 $f(x)$  

【解】等式两边对 $_{x}$ 求导,得 $g\big[f(x)\big]f^{\prime}(x)=2x^{x}+x^{\,2}\,{\mathrm{e}}^{x}$ ,而 $g[f(x)]\!=\!x$ ，故$x f^{\prime}(x)=2x\,{\mathrm{e}}^{x}+x^{\,2}\,{\mathrm{e}}^{x}\,.$  

当 $\scriptstyle x\;\neq\;0$ 时， $f^{\prime}(x)=2\mathbf{e}^{x}+x\,\mathbf{e}^{x}$ ,两边对 $_{x}$ 积分得 $f(x)=(x+1)\mathbf{e}^{x}+C$  

由于 $f(x)$ 在 $x=0$ 处右连续，故由  

$$
0=f(0)=\operatorname*{lim}_{x\to0^{+}}f(x)=\operatorname*{lim}_{x\to0^{+}}\bigl[(x+1)\mathbf{e}^{x}+C\bigr],
$$  

得 $C=-1$ ,因此 $f(x)=(x+1)\mathbf{e}^{x}-1(x\geqslant0)$  

【注】部分考生对 $g[f(x)]\!=\!x$ 这一反函数的基本性质不熟悉，导致后续无法化简；积分方程往往都是通过求导转化为微分方程再去求解.另外，本题利用初始条件确定 $c$ 的值的过程值得体会。  

# 3.换元求导型  

先用换元法处理，再用求导公式（I），（Ⅱ）求导的积分称为换元求导型  

例 9. 24设 $f(x)$ 在 $[0,+\infty)$ 内可导， $f(0)=0$ ,其反函数为 $_{g}(x)$ .若  

$$
\int_{x}^{x+f(x)}\!g(t-x\,)\mathrm{d}t=x^{2}\ln(1+x\,)\,,
$$  

求$f(x)$  

【解】令 $\boldsymbol{t}-\boldsymbol{x}=\boldsymbol{u}$ ，则 $\mathsf{d}t=\mathsf{d}u$ ,于是  

$$
\int_{x}^{x+f(x)}\!g\left(t-x\,\right)\!\,\mathrm{d}t=\!\!\int_{0}^{f(x)}g\left(u\,\right)\!\,\mathrm{d}u={x}^{2}\ln(1+x\,).
$$  
将等式 $\int_{0}^{f(x)}g\left(u\right)\mathrm{d}u=x^{2}\ln(1+x)$ 两边对 $_{x}$ 求导,同时注意到 $g[f(x)]\!=\!x$ ,于是有  

$$
x f^{\prime}(x)\,{=}\,2x\ln(1+x)+{\frac{x^{2}}{1+x}}.
$$  

当 $x\neq0$ 时，有 $f^{\prime}(x)=2\mathrm{ln}(1+x)+\frac{x}{1+x}$ ，两边对 $_{x}$ 积分得  

$$
{\begin{array}{r l}&{f(x)=\!\!\left\lceil\left[2\!\ln(1+x)+{\frac{x}{1+x}}\right]\mathrm{d}x\right\rceil\!\leq\!x}\\ &{\qquad=2{\bigl[}\ln(1+x)+x\ln(1+x)-x{\bigr]}+x-\ln(1+x)+C}\\ &{\qquad=\ln(1+x)+2x\ln(1+x)-x+C.}\end{array}}
$$  

可知 $\operatorname*{lim}_{x\to0^{+}}f(x)=C$ ,由于 $f(x)$ 在 ${x=0}$ 处右连续,又 $f(0)=0$ ,解得 $C=0$ ,于是  

$$
f(x)=\ln(1+x)+2x\ln\,(1+x)-x\,(x\geqslant0).
$$  

例 9. 25设 $f(x)$ 在 $(-\infty,+\infty)$ 内非负连续，且  

$$
\int_{0}^{x}t\,f(x^{2})\,f(x^{2}-t^{2})\,\mathrm{d}t=\sin^{2}(x^{2})\,,
$$  

求 $f(x)$ 在 $[0,\pi]$ 上的平均值.  

【解】令 $x^{2}-t^{2}=u$ ，则  

$$
\begin{array}{c}{{{\displaystyle\int_{\L_{0}}^{x}t f(x^{\L_{2}})f(x^{\L_{2}}-t^{\L_{3}})\mathrm{d}t=f(x^{\L_{2}})\left[-\,\frac{1}{2}\!\!\int_{x^{\L_{2}}}^{\L_{0}}f(u)\mathrm{d}u\right]}}}\\ {{{\displaystyle\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\left.\!\!\begin{array}{c}{{\displaystyle-\frac{1}{2}f(x^{\L_{3}})\!\!\int_{\L_{0}}^{x^{\L_{2}}}f(u)\mathrm{d}u}}\end{array}\right]}}}\end{array}
$$  

于是有 $f(x^{2}){\int_{0}^{x^{2}}{f(u)\mathrm{d}u}}=2\mathrm{sin}^{2}(x^{2})$ ，再令 $x^{2}=v$ ,有  

$$
f(v){\int_{0}^{v}f(u)\,\mathrm d u}=2\sin^{2}v.
$$  

又令 $F(v)=\!\int_{0}^{v}\!f(u)\mathrm{d}u$ ,于是  

$$
F(v)F^{\prime}(v)\!=\!2\!\sin^{2}\!v\,,
$$  

上式在 $[0,\pi]$ 上对 $_{\ast}$ 作积分，有  

$$
\int_{0}^{\mathfrak{x}}\!\!F(v)F^{\prime}(v)\mathrm{d}v=\!\!\int_{0}^{\mathfrak{x}}\!\!F(v)\mathrm{d}\!\left[F(v)\right]\!=\!\frac{1}{2}F^{2}(v)\left|\begin{array}{l}{\mathfrak{x}}\\ {\mathfrak{o}}\end{array}\right|_{0}^{\mathfrak{x}}\!=\!2\!\!\int_{0}^{\mathfrak{x}}\!\sin^{2}\!v\mathrm{d}v=\!\pi,
$$  

故 $F(\pi)=\sqrt{2\pi}$ ，则 $f(x)$ 在 $[0,\pi]$ 上的平均值为 ${\frac{1}{\pi}}{\int_{0}^{\kappa}f(x)\,\mathrm{d}x}={\sqrt{\frac{2}{\pi}}}.$  

[注](1) 连续函数 $f(x)$ 的一个原函数表达形式常写为 $F(x)=\!\int_{0}^{x}f(u)\mathrm{d}u$ ,考生须熟知。见到 $f(x)\!\int_{0}^{x}f(u)\!\,\mathrm{d}u$ ，一般令 $F(x)=\int_{0}^{x}f(u)\mathrm{d}u$ ,这样便有 $\scriptstyle F^{\prime}(x)\;=\;f(x)$ ,即得 $F^{\prime}(x)F(x)$ ,于是 $\int\!\!F^{\prime}(x)F(x)\mathrm{d}x=\int\!\!F(x)\mathrm{d}\!\!\left[F(x)\right]={\frac{1}{2}}F^{2}(x)+C.$ 此思路非常重要.(2) 平均值是考研重点.  
# 比亨高等数学18讲  

4.拆分求导型  

需先拆分区间化成若干个积分，再用求导公式（I），（Ⅱ）求导的积分（往往带绝对值）称为拆分求导型.  

例 9. 26设 $|\ x\ |\leqslant1$ ，求积分 $I(x)=\!\!\int_{-1}^{1}\mid t-x\mid\,\mathrm{e}^{2t}\,\mathrm{d}t$ 的最大值.  

【解】由题设知， $I(x)=\!\!\int_{-1}^{1}\mid t-x\mid\,\mathrm{e}^{2t}\,\mathrm{d}t$ (x-t)e²dt (t-x)e²dt dt+ dt  

$$
\begin{array}{r l}&{I^{\prime}(x\,)=\!\!\int_{-1}^{x}\!\mathrm{e}^{2t}\,\mathrm{d}t+x\,\mathrm{e}^{2x}-x\,\mathrm{e}^{2x}-x\,\mathrm{e}^{2x}-\displaystyle\int_{x}^{1}\mathrm{e}^{2t}\,\mathrm{d}t+x\,\mathrm{e}^{2x}=\!\int_{-1}^{x}\mathrm{e}^{2t}\,\mathrm{d}t-\displaystyle\int_{x}^{1}\mathrm{e}^{2t}\,\mathrm{d}t}\\ &{\qquad=\mathrm{e}^{2x}-\displaystyle\frac{1}{2}(\mathrm{e}^{2}+\mathrm{e}^{-2})\,\frac{\phi}{0}\,0,}\end{array}
$$  

得 $x=\frac{1}{2}\ln{\frac{\mathrm{e}^{2}+\mathrm{e}^{-2}}{2}}$ 为唯一驻点， $I^{\prime\prime}(x)\,{=}\,2\mathrm{e}^{2x}>0$ ，故 $x={\frac{1}{2}}\ln{\frac{\mathrm{e}^{2}+\mathrm{e}^{-2}}{2}}$ 为 $I\left(x\right)$ 在[-1,1]上的最小值，最大值只能在端点 $x=-1,x=1$ 处取得.又  

$$
I(-1)=\frac{3}{4}\mathrm{e}^{2}+\frac{1}{4}\mathrm{e}^{-2}\,,I(1)=\frac{1}{4}\mathrm{e}^{2}-\frac{5}{4}\mathrm{e}^{-2}\,,
$$  

所以 $I_{\mathrm{\scriptsize~max}}=I(-1)={\frac{3}{4}}\mathrm{e}^{2}+{\frac{1}{4}}\mathrm{e}^{-2}$  

例 9. 27设函数 $f(x)=\!\int_{0}^{1}\;\mid t^{2}-x^{2}\mid\,\mathrm{d}t\,(x>0)$ ，求 $f^{\prime}(x)$ ,并求 $f(x)$ 的最小值.  

【解】当 $0<x\leqslant1$ 时。 $\begin{array}{l}{\displaystyle,f(\boldsymbol{x}\,)\!=\!\!\int_{0}^{x}\mid t^{2}-x^{2}\mid\mathrm{d}t+\int_{x}^{1}\mid t^{2}-x^{2}\mid\mathrm{d}t}\\ {\displaystyle\qquad\!=\!\!\int_{0}^{x}(x^{2}-t^{2})\mathrm{d}t+\int_{x}^{1}(t^{2}-x^{2})\mathrm{d}t=\frac{4}{3}x^{3}-x^{2}+\frac{1}{3},}\end{array}$  

当 $x>1$ 时，  

$$
f(x)=\!\int_{0}^{1}(x^{2}-t^{2})\,\mathrm{d}t=x^{2}-{\frac{1}{3}}.
$$  

所以  

$$
f(x)=\!\!\left\{\!\!\begin{array}{l l}{{\displaystyle\frac{4}{3}x^{3}-x^{2}+\frac{1}{3},\:}}&{{0<x\leqslant1,\:}}\\ {{\displaystyle x^{2}-\frac{1}{3},\:}}&{{x>1,\:}}\end{array}\right.\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! 
$$  

而  

$$
f_{-}^{\prime}(1)\mathop{=\operatorname*{lim}_{x\to1^{-}}}\frac{\frac{4}{3}x^{3}-x^{2}+\frac{1}{3}-\frac{2}{3}}{x-1}\mathop{=}2,f_{+}^{\prime}(1)\mathop{=\operatorname*{lim}_{x\to1^{+}}}\frac{x^{2}-\frac{1}{3}-\frac{2}{3}}{x-1}\mathop{=}2,
$$  

故  

$$
f^{\prime}(x\,)=\left\{\!\!\!\begin{array}{l l}{4x^{\,2}-2x\,,}&{\;0<x\leqslant1,}\\ {2x\,,}&{\;x>1.}\end{array}\right.
$$  

由 $f^{\prime}(x)=0$ 得唯一驻点 $x=\frac{1}{2}$ 又 $f^{\prime\prime}\Big(\frac{1}{2}\Big)>0$ 从而 $x=\frac{1}{2}$ 为 $f(x)$ 的最小值点，最小值  
为 $f\!\left({\frac{1}{2}}\right)\!={\frac{1}{4}}$  

5.换序型  

积分是一种累次积分(即先算里面一层积分，再算外面一层积分)，一般里面一层积分不易处理，故化为二重积分再交换积分次序，称这种类型的积分为换序型.  

例9.28概 $\operatorname*{lim}_{t\rightarrow0^{+}}\frac{1}{t^{5}}{\int_{0}^{t}\!\mathrm{d}y}{\int_{y}^{t}\frac{\sin(x y)^{2}}{x}\mathrm{d}x}=-\frac{}{\phantom{-}}\cdot$  

[解】应填 $\frac{1}{15}$  

将二重积分交换积分次序，得  

$$
\int_{0}^{t}\!\mathrm{d}y\!\int_{y}^{t}\,\frac{\sin(x y)^{2}}{x}\mathrm{d}x=\!\int_{0}^{t}\,\frac{1}{x}\mathrm{d}x\!\int_{0}^{x}\sin(x y)^{2}\mathrm{d}y.
$$  

记$\int_{0}^{x}\sin(x y)^{2}\,\mathbf{d}y=f(x)$ ，则  

$$
{\begin{array}{l}{\displaystyle\Re_{\mathrm{e}^{-}\!+\!{\frac{1}{\hbar}}}\!\left\langle{\frac{\displaystyle\int_{0}^{t}{\frac{1}{x}}f(x)\,\mathrm{d}x}{t^{5}}}=\!{\frac{\displaystyle\mathrm{lim}}{\displaystyle{\mathrm{r}^{-}\!\!+\!{\frac{1}{\hbar}}}\frac{\displaystyle f(t)}{\displaystyle5t^{4}}}}\!\right.}\\ {\displaystyle\left.-\!\operatorname*{lim}_{t\to0^{+}}{\frac{\displaystyle f(t)}{\displaystyle5t^{5}}}=\!{\frac{\displaystyle\mathrm{lim}{\frac{\displaystyle\int_{0}^{t}{\sin(t y)}^{2}\,\mathrm{d}y}{\displaystyle5t^{5}}}}{\displaystyle\frac{\displaystyle\mathrm{lim}}{\displaystyle5t^{5}}}}\!-\!{\frac{\displaystyle\mathrm{lim}{\frac{\displaystyle\frac{1}{t}\displaystyle\int_{0}^{t}{\sin u^{2}\,\mathrm{d}u}}{\displaystyle\mathrm{lim}^{2}\,\mathrm{d}y}}}{\displaystyle\frac{\displaystyle\mathrm{lim}}{\displaystyle\mathrm{r}^{-}\!\!+\!{\frac{1}{\hbar}}}\!}}}\\ {\displaystyle\left.-\!{\frac{\displaystyle\mathrm{lim}}{\displaystyle{\mathrm{r}^{+}\!\!-\!{\frac{1}{\hbar}}}\!}}{\frac{\displaystyle\int_{0}^{t^{2}}{\sin u^{2}\,\mathrm{d}u}}{\displaystyle5t^{6}}}}=\!{\frac{\displaystyle\mathrm{lim}}{\displaystyle{\mathrm{r}^{+}\!\!-\!{\frac{1}{\hbar^{2}}}}\!}}{\frac{\displaystyle\sin t^{4}\cdot2t}{\displaystyle30t^{5}}}\!-\!{\frac{1}{\displaystyle15}}.}\end{array}}
$$  

# 五反常积分的计算  

在收敛的条件下.  

${\mathfrak{D}}{\int_{a}^{+\infty}}f(x)\mathrm{d}x=F(+\infty)-F(a)$ ,其中 $F(+\infty)$ 是指 $\operatorname*{lim}_{\tau\rightarrow+\infty}F(x)$ ： $\circledcirc$ 若 $^{\,a}$ 为瑕点，则 $\int_{a}^{b}f(x\,)\mathrm{d}x=F(b)-F(a\,)$ ,其中 $F(\alpha)$ 是指 $\operatorname*{lim}_{x\to a^{+}}F(x)$  $\textcircled{3}$ 换元后，有可能实现反常积分与定积分的相互转化.  

例9.29求 $\int_{0}^{1}{\frac{x^{2}\arcsin x}{\sqrt{1-x^{2}}}}\mathrm{d}x$  

【解】由于 $\operatorname*{lim}_{x\to1^{-}}{\frac{x^{2}\arcsin x}{\sqrt{1-x^{2}}}}=+\infty$ ，故 $\int_{0}^{1}{\frac{x^{2}\arcsin x}{\sqrt{1-x^{2}}}}\mathrm{d}x$ 是反常积分.令arcsin $\scriptstyle x\;=t$ ，则 $x=\sin\,t\,,t\in\,\left[0,\frac{\pi}{2}\right)$ ，则  
$$
\begin{array}{r l r}{\lefteqn{\int_{0}^{1}\frac{x^{2}\arcsin x}{\sqrt{1-x^{2}}}\mathrm{d}x=\int_{0}^{\frac{x}{2}}\frac{t\sin^{2}t}{\cos{t}}\cos{t}\,\mathrm{d}t=\int_{0}^{\frac{x}{2}}t\sin^{2}\!t\,\mathrm{d}t}}\\ &{}&{\;\;\;\;\;\;\;\;\;\;\;\;\;=\int_{0}^{\frac{x}{2}}\left(\frac{t}{2}-\frac{t\cos{2t}}{2}\right)\mathrm{d}t=\frac{t^{2}}{4}\left\vert\frac{\frac{x}{2}}{0}-\frac{1}{4}\!\int_{0}^{\frac{x}{2}}t\mathrm{d}(\sin{2t})\right.\quad}\\ &{}&{\;\;\;\;\;\left.=\frac{\pi^{2}}{16}-\frac{t\sin{2t}}{4}\left\vert\frac{\frac{x}{2}}{0}+\frac{1}{4}\right\vert^{\frac{x}{2}}\sin{2t}\mathrm{d}t=\frac{\pi^{2}}{16}-\frac{1}{8}\cos{2t}\left\vert\frac{\frac{x}{2}}{0}=\frac{\pi^{2}}{16}+\frac{1}{4}.\right\vert}\end{array}
$$  

例 9. 30求 $\int_{0}^{+\infty}\,\frac{(1+2t^{2})t^{2}}{(1+t^{2})^{3}}\mathrm{d}t\,.$  

【解】令 $t=\tan\,u$ ，则  

$$
\begin{array}{r l}&{\boxed{\mathbb{H}_{\mathcal{F}}^{-}\mathbb{A}}=\int_{0}^{\frac{\pi}{2}}\frac{\langle\mathbf{sec}^{2}u+\mathbf{tan}^{2}u\rangle\tan^{2}u}{\operatorname{sec}^{6}u}\mathrm{d}(\tan u)}\\ &{\quad=\int_{0}^{\frac{\pi}{2}}\frac{\sec^{2}u\tan^{2}u}{\operatorname{sec}^{4}u}+\tan^{4}u}\\ &{\quad=\int_{0}^{\frac{\pi}{2}}\left(\sin^{2}u+\sin^{4}u\right)\mathrm{d}u}\\ &{\quad=\frac{1}{2}\cdot\frac{\pi}{2}+\frac{3}{4}\cdot\frac{1}{2}\cdot\frac{\pi}{2}}\\ &{\quad=\frac{7\pi}{16}.}\end{array}
$$  
# 一元函数积分学的应用 ( 一)一儿何应用  

# 6知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/59881ea2e3d8b0e21572888d9817453665dd821c4db2bc91165d4c1bd4ef462b.jpg)  
![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/9cca964e7536915f2e8751710fa7b29c655b76a4920f6742434c810eea746057.jpg)  

# 研究对象  

# 1.“祖孙三代”  

抽豕，  
①f(x) f,（x）（函数族），f..f......fn.   
②f'(x),d[f(x)]d(x²)f(n)(x).  
3f(t)dt.  

2.用极限定义函数 $f(x)=\operatorname*{lim}_{n\to\infty}g(n\,,x\,)$ 或 $f(x)=\operatorname*{lim}_{\iota\to x}g(t,x)$  

$$
\begin{array}{l}{\displaystyle\mathbb{\oplus}\left\langle{\alpha=x\left(t\right)},\right.}\\ {\displaystyle y=y\left(t\right).}\\ {\displaystyle\mathbb{\oplus}\left\langle{x=r\left(\theta\right)\cos\theta},\right.}\\ {\displaystyle y=r\left(\theta\right)\sin\theta.}\end{array}
$$  

5.隐函数 $F\left({\boldsymbol{x}}\end{array},{\boldsymbol{y}}\right)=0$  

6.微分方程的解 $y=y\left(x\right)$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/060a511736d20ba45af91d350ee3d8395fe3f698bb06d28e6827c8f1eb071a2e.jpg)  

# 研究内容  

# (1)面积.  

$\textcircled{1}$ 直角坐标系下的面积公式(见图10-1）： $S=\!\!\int_{a}^{b}\mid f(x\,)-g(x\,)\mid\,\mathrm{d}x\,.$  
$\circledcirc$ 极坐标系下的面积公式(见图 10-2):S =]。I r(9)-r(9)| do.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/10266d7cd61b0b422d28d61d48ac39599a6e451b7abd6403a0772f7a76724535.jpg)  
图10-1  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/53af8b902b3b359b6b457f7feae107f299fb36a9d48f42d840738264829994b1.jpg)  
图10-2  

例10.1曲线 $r=1+\cos\,\theta$ 与其在点 $\left(1+{\frac{\sqrt{2}}{2}},{\frac{\pi}{4}}\right)$ 处的切线及 $_{x}$ 轴所围图形面积为  

[解】应填 $\frac{3}{8}(3+\sqrt{2}\,)-\frac{3}{16}\pi$  

由例5.3 可知，曲线 $r=1+\cos\,\theta$  $\left(1+{\frac{\sqrt{2}}{2}},{\frac{\pi}{4}}\right)$ 处的直角坐标系下的切线方程为 $_y=$  $(1-\sqrt{2})x+1+\frac{\sqrt{2}}{2}$ 切点为 $B\left(\frac{\sqrt{2}}{2}+\frac{1}{2},\frac{\sqrt{2}}{2}+\frac{1}{2}\right)$ 则所围图形细图103 示。可知所求图形面积等于大三角形面积减去小曲边三角形面积.接下来在两种坐标系下分别计算 $s_{\star}$ （见图10-4）， $S_{\uparrow}$ （见图10-5).  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e8535967bf0f7959a6f181041b5a4c86889604bd467341b9722cd6d845f2d37f.jpg)  
图10-3  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f8a6485fdb0bdaccee4faf16eab2c42225ea8b980b88f38de59e7ec96ece7d72.jpg)  
图10-4  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/95060ef8b1852e71f3a8866e710ef75bb3621c9aa1ddbc9a106d0337c3551daf.jpg)  
图10-5  

如图10-4 所示，切线方程中令 ${\mathfrak{s}}=0$ 得 $x=2+{\frac{3\,{\sqrt{2}}}{2}}$ 即 $A$ 点坐标为 $\left(2+{\frac{3{\sqrt{2}}}{2}},0\right)$ 而 $B$ 点坐标为 $\left({\frac{\sqrt{2}}{2}}+{\frac{1}{2}},\,{\frac{\sqrt{2}}{2}}+{\frac{1}{2}}\right)$ 作 BC 垂直于 $_{x}$ 轴交于点 $C$ 故  

$$
\begin{array}{r l}&{S_{\star}\!=\!\frac{1}{2}\cdot\mid O A\mid\bullet\mid B C\mid}\\ &{\quad=\!\frac{1}{2}\!\left(2+\frac{3\sqrt{2}}{2}\right)\!\left(\frac{\sqrt{2}}{2}+\frac{1}{2}\right)}\\ &{\quad=\!\frac{10+7\sqrt{2}}{8}.}\end{array}
$$  

如图10-5所示，可得  

$$
S_{\scriptscriptstyle{\1}\!\mathrm{*}}\!=\!\frac{1}{2}\!\!\int_{0}^{\frac{\pi}{4}}\!r^{2}\,\mathrm{d}\theta\!=\!\frac{1}{2}\!\!\int_{0}^{\frac{\pi}{4}}(1+\cos\theta)^{2}\,\mathrm{d}\theta
$$  
# 比宁高等数学18讲  

$$
\begin{array}{r l}&{=\displaystyle\frac{1}{2}\!\int_{0}^{\frac{\pi}{4}}(1+2\cos\theta+\cos^{2}\theta)\,\mathrm{d}\theta}\\ &{=\displaystyle\frac{1}{2}\!\int_{0}^{\frac{\pi}{4}}\!\mathrm{d}\theta+\!\int_{0}^{\frac{\pi}{4}}\!\cos\theta\,\mathrm{d}\theta+\frac{1}{2}\!\int_{0}^{\frac{\pi}{4}}\!\cos^{2}\theta\,\mathrm{d}\theta}\\ &{=\displaystyle\frac{1}{2}\cdot\frac{\pi}{4}+\sin\theta\left|_{0}^{\frac{\pi}{4}}+\left(\frac{1}{4}\theta+\frac{1}{8}\sin2\theta\right)\right|_{0}^{\frac{\pi}{4}}}\\ &{=\displaystyle\frac{1}{8}+\frac{\sqrt{2}}{2}+\frac{3}{16}\pi.}\end{array}
$$  

故$S=S_{\star}-S_{\,\uparrow\!\mathrm{~}}=\frac{3}{8}(3+\sqrt{2}\,)-\frac{3}{16}\pi.$  

例10. 2当 $x\geqslant0$ 时，在曲线 $y=\,{\mathsf{e}}^{-2x}$ 上面作一个台阶曲线，台阶的宽度皆为1(见图10-6).则图中无穷多个阴影部分的面积之和S $=$  

【解】应填 $\frac{\mathbf{e}^{2}+1}{2(\mathbf{e}^{2}-1)}$  

区间 $[k\,,k+1](k=0\,,1\,,2\,,\cdots)$ 上的阴影面积为  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c23de3eec8e4f982858d0660fe9cf0db18b5a3805ac7d4ea85dfe69e98bf34d5.jpg)  
图10-6  

矩形面积K ${\frac{\mathrm{e}^{-2k}}{\mathrm{e}^{-2k}}}-\!\!\left(\!\!{\int_{\star}^{k+1}{\mathrm{e}^{-2x}}\,\mathrm{d}x}\!\!\right)={\mathrm{e}}^{-2k}+{\frac{1}{2}}{\mathrm{e}}^{-2x}\,\left|\,{\star}^{+1}={\mathrm{e}}^{-2k}+{\frac{1}{2}}{\mathrm{e}}^{-2k-2}-{\frac{1}{2}}{\mathrm{e}}^{-2k}=\left({\frac{1}{2}}+{\frac{1}{2\,\mathrm{e}^{2}}}\right){\mathrm{e}}^{-2k}\,{\mathrm{e}}^{-2k}=0$ 曲边梯形的面积$\sum_{k=0}^{\infty}\mathrm{e}^{-2k}=\frac{1}{1-\mathrm{e}^{-2}}$ 故$S=\left({\frac{1}{2}}+{\frac{1}{2\mathrm{e}^{2}}}\right){\frac{1}{1-\mathrm{e}^{-2}}}={\frac{\mathrm{e}^{2}+1}{2\mathrm{e}^{2}}}\cdot{\frac{\mathrm{e}^{2}}{\mathrm{e}^{2}-1}}={\frac{\mathrm{e}^{2}+1}{2(\mathrm{e}^{2}-1)}}.$  

# (2）旋转体体积.  

$\textcircled{1}$ 平面曲线绕定直线旋转.  

设平面曲线 $L:y=f(x\,)\,,a\leqslant x\leqslant b$ ,且 $f(x)$ 可导.  

定直线 $L_{\scriptscriptstyle0}:A x+B y+C=0$ ,且过 $\boldsymbol{L}_{0}$ 的任一条垂线与 $L$ 至多有一个交点，如图10-7所示，则 $L$ 绕 $\scriptstyle{L_{\circ}}$ 旋转一周所得旋转体体积为  

$$
V\mathop{=}\frac{\pi}{(A^{2}+B^{2})^{\frac{3}{2}}}\biggl[^b_{a}x+B f(x\,)+C\]^{2}\mid A f^{\prime}(x\,)-B\mid\,\mathrm{d}x\,.
$$  

特别地,若 $A=C=0,B\neq0$ ,则 $L_{\sun}$ 为$y=0(x$ 轴),如图10-8所示， $L$ 绕$L_{\mathrm{~o~}}$ 旋转一周所得 旋转体体积为  

$$
V=\pi\!\int_{a}^{b}f^{2}(x\,)\,\mathrm{d}x\,.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/54861382a31ffa8f5a52848864860209465b36562d093e7e7ee91e2572af50b7.jpg)  
图10-7  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/5eca78023689b81a0af354a2e431b38a078159acc7e00d68523ed02cb78cc6a7.jpg)  
图10-8  

$\circledcirc$ 平面曲边梯形绕坐标轴旋转.  
设平面曲边梯形 $D=\{(x,y)\mid0\leqslant y\leqslant f(x),0\leqslant a\leqslant x\leqslant b\}$ ,且 $f(x)$ 连续,如图10-9 所示，则 $D$ 绕 $_y$ 轴旋转一周所得旋转体体积为  

$$
V=2\pi\!\!\int_{a}^{b}\!\!x\:\mid\:f(x)\:\mid\:\mathrm{d}x.
$$  

事实上， $\textcircled{1}$ 的公式（b）就是 $D$ 绕 $_{x}$ 轴旋转的情形，不重复写了.  

$\textcircled{3}$ 平面图形 $D=\{\,(r\,,\theta)\;\,|\;\,0\leqslant r\leqslant r\,(\theta)\,,\theta\in\big[\alpha\,,\beta\big]\subset\big[0\,,\pi\big]\}$ ,如图10-10所示,则 $D$ 绕极轴旋转一周所得旋转体体积为  

$$
V={\frac{2}{3}}\pi\!\int_{\alpha}^{\beta}\!r^{3}\,(\theta)\sin\,\theta\mathrm{d}\theta.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/d527e910488703ad211e2dc368995d3d9749fdac07e6ff62c0996cd555ab7756.jpg)  
图10-9  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a89e9d7d8d7a5e4a707fae5c9578d6a46aac17e5a6b2af3f773d413b855f4bf6.jpg)  
图10-10  

[注】 上述公式(a),(b),(c),(d) 均可直接使用,不必证明.  

例 10. 3曲线 $y=\mathbf{e}^{x}\,(0\leqslant x\leqslant1)$ 绕直线 $_y=x$ 旋转一周所得的旋转体的体积 $V=$  

【解】应填 ${\frac{\pi}{2{\sqrt{2}}}}\left[{\frac{1}{3}}(\mathbf{e}-1)^{3}+\mathbf{e}^{2}-{\frac{14}{3}}\right].$  

如图10-11所示， $L$ 为 $y=\mathbf{e}^{x}\left(0\leqslant x\leqslant1\right),L_{0}$ 为 $_{y}=x$ ，即 $x-y=0$ ，故 $A=1,B=-1,C=0.$ 于是由公式(a),有  

$$
\begin{array}{r l}&{V=\cfrac{\pi}{[1^{2}+(-1)^{2}]^{\frac{1}{2}}}\Big[\stackrel{1}{_0}(x-e^{\varepsilon})^{2}(e^{\varepsilon}+1)\mathrm{d}x}\\ &{\quad=\cfrac{\pi}{2\sqrt{2}}\Big[\frac{1}{\mathfrak{s}}(e^{\varepsilon}-x)^{2}(e^{\varepsilon}-1+2)\mathrm{d}x}\\ &{\quad=\cfrac{\pi}{2\sqrt{2}}\Big[\textstyle\frac{1}{\mathfrak{s}}(e^{\varepsilon}-x)^{2}\mathrm{d}(e^{\varepsilon}-x)+2\Big]_{\mathfrak{s}}^{1}(e^{2\varepsilon}-2x e^{\varepsilon}+x^{2})\mathrm{d}x\Big]}\\ &{\quad=\cfrac{\pi}{2\sqrt{2}}\Big[\textstyle\frac{1}{3}(e-1)^{3}-\frac{1}{3}+e^{2}-\frac{13}{3}\Big]}\\ &{\quad=\cfrac{\pi}{2\sqrt{2}}\Big[\textstyle\frac{1}{3}(e-1)^{3}+e^{2}-\frac{14}{3}\Big]\,.}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e3d5610ff4b2b21b22ba97ebd7aec03bc1b9590b9dc86e49060ff7652eb2a073.jpg)  
图10-11  

例10.4  

已知函数 $f(x\,,y\,)$ 满足 $\frac{\partial f(x\;,y\;)}{\partial y}=2(y+1)$ ,且  

$$
f(y\,,y)=(y+1)^{2}-(2-y\,)\ln\,y\,,
$$  

求曲线 $f(x\,,y)=0$ 所围图形绕直线 ${y=-1}$ 旋转一周所得旋转体的体积。  
# 陆亨高等数学18讲  

【解】由 $\frac{\partial f(x\;,y\;)}{\partial y}=2(y+1)$ ，得  

注意积分后不是加上任意常数C  

$$
f(x\,,y)=(y+1)^{2}+g(x\,).
$$  

又$f(y\,,y)=(y+1)^{2}-(2-y)\ln\,y$ ，得  

$$
g\left(y\right)=-\,(2-y\,)\ln\,y\,,
$$  

因此  

$$
f(x\,,y)=(y+1)^{2}-(2-x\,)\ln\,x\,.
$$  

于是,曲线 $f(x\,,y\,)=0$ 的方程为  

$$
(y+1)^{2}=(2-x\,)\ln\,x\,(1\leqslant x\leqslant2).
$$  

其所围图形绕直线 $y=-1$ 旋转一周所得旋转体的体积为  

可得  

【注】求体积也可这样做：  

$L:y=f(x)$ 满足 $[f(x\,)+1]^{2}\!=\!(2-x\,)\ln x\,,1\!\ll\!x\ll2,L_{\circ}:y\!=\!-1,$ 即$0\cdot x+1\cdot y+1=$ O，故 $A=0,B=C=1$ ,则由公式(a)，有  

$$
V=\frac{\pi}{1}\!\int_{1}^{2}[f(x)+1]^{2}\,\mathrm{d}x\,.
$$  

其余过程同上解。  

例10.5设函数 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 满足微分方程 $y^{\prime}+y={\frac{\operatorname{e}^{-x}\cos\ x}{2{\sqrt{\sin\ x}}}}$ 且 $f(\pi)=0$ 求曲线 $_y=$ $f(x)(x\geq0)$ 绕$_{x}$ 轴旋转一周所得旋转体的体积.  

【解】解题干给的一阶线性微分方程，有  

$$
\begin{array}{r l}&{y=\mathrm{e}^{-\int_{p^{\mathrm{d}x}}^{p\mathrm{d}x}}\left(\int_{0}^{\int_{p^{\mathrm{d}x}}^{p\mathrm{d}x}}\!q\,\mathrm{d}x+C\right)}\\ &{\ \ =\mathrm{e}^{-x}\left(\!\int_{0}^{\tau^{x}}\frac{\mathrm{e}^{-x}\cos\,x}{2\,\sqrt{\sin\,x}}\mathrm{d}x+C\right)\!=\mathrm{e}^{-x}\left(\!\int_{0}^{\;\;\mathrm{cos}\;\,x}\!\mathrm{d}x+C\right)}\\ &{\ \ =\mathrm{e}^{-x}\left[\!\int\frac{\mathrm{d}(\sin\,x\,)}{2\,\sqrt{\sin\,x}}\!+C\right]\!=\mathrm{e}^{-x}\left(\!\sqrt{\sin\,x}+C\right),}\end{array}
$$  

又$f(\pi)=\operatorname{e}^{-\pi}\cdot C=0$ ，故 $C=0$ ,得  

$$
f(x)=\mathrm{e}^{-x}{\sqrt{\sin\,x}}\,(x\geqslant0).
$$  

故旋转体体积为  

$$
V=\sum_{n=0}^{\infty}\pi\!\int_{2n\pi}^{(2n+1)\pi}\!\!\!\!\mathrm{e}^{-2x}\sin x\,\mathrm{d}x=\sum_{n=0}^{\infty}\!\pi\left.\frac{\left|\left(\mathrm{e}^{-2x}\,\right)^{\prime}\right.\quad(\sin x\,\,x\,)^{\prime}}{\mathrm{e}^{-2x}}\right|_{2n\pi}^{\infty}
$$  
$$
\begin{array}{r l}&{=\displaystyle\frac{\pi}{5}\sum_{n=0}^{\infty}(-2\sin{x}-\cos{x})\mathrm{e}^{-2x}\left|\frac{(2n+1)\pi}{2n\pi}=\frac{\pi}{5}\sum_{n=0}^{\infty}(\mathrm{e}^{-4n\pi}\cdot\mathrm{e}^{-2\pi}+\mathrm{e}^{-4n\pi})\right.}\\ &{\displaystyle\left.=\frac{\pi(1+\mathrm{e}^{-2\pi})}{5}\sum_{n=0}^{\infty}\mathrm{e}^{-4n\pi}=\frac{\pi(1+\mathrm{e}^{-2\pi})}{5}\cdot\frac{1}{1-\mathrm{e}^{-4\pi}}=\frac{\pi}{5(1-\mathrm{e}^{-2\pi})}.\right.}\end{array}
$$  

例10.6曲线 $_y={\sqrt{x\ }}$ 与 $_{y=x}$ 所围平面有界区域绕直线 $_{y}=x$ 旋转一周所得旋转体的体积为  

[解】应填 ${\frac{\sqrt{2}}{60}}\pi$  

$L:y=\sqrt{x}\;,0\leqslant x\leqslant1.\,L_{\mathit{\circ}}:y=x$ ,即 $x-y=0$ ,故 $A=1,B=-1,C=0.$ 于是由公式(a),有  

$$
\begin{array}{l}{{V=\displaystyle\frac{\pi}{\big[1^{2}+(-1)^{2}\big]^{\frac{1}{2}}}\displaystyle\int_{0}^{1}(x-\sqrt{x}\,)^{2}\left|\frac{1}{2\,\sqrt{x}}-(-1)\right|\mathrm{d}x}}\\ {{\displaystyle\quad=\frac{\pi}{2\,\sqrt{2}}\displaystyle\int_{0}^{1}(x-\sqrt{x}\,)^{2}\cdot\left(\frac{1}{2\,\sqrt{x}}+1\right)\mathrm{d}x}}\\ {{\displaystyle\quad=\frac{\pi}{2\,\sqrt{2}}\displaystyle\int_{0}^{1}\left(x^{2}-\frac{3}{2}x^{\frac{1}{2}}+\frac{\sqrt{x}}{2}\right)\mathrm{d}x}}\\ {{\displaystyle\quad=\frac{\sqrt{2}}{60}\pi.}}\end{array}
$$  

例 10. 7心形线 $r\!=\!2(1\!+\!\cos\theta)$ 和 $\theta\!=\!0\,,\theta\!=\!\frac{\pi}{2}$ 围成的图形绕极轴旋转一周所成旋转体的体积 $V=(\mathrm{~\ensuremath~{~\alpha~}~})$  

(A) ${\sf{20\pi}}$ $(\mathbf{B})40\pi$ (C)80π (D)160π  

【解】应选(A).  

法一由题设得所围平面图形如图10-12所示，又有  

$$
\begin{array}{l}{\left\langle x=2(1+\cos\theta)\cos\theta\,,\right.}\\ {\left.\left|y=2(1+\cos\theta)\sin\theta\,,\right.}\end{array}
$$  

则旋转体的体积为  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a48c4cd978ccdb972a52f164a84e6fdb4576c2da2d736a0052a9d5dd3c86fa0d.jpg)  
图10-12  

$$
\begin{array}{r l}&{V\!=\!\!\displaystyle\int_{0}^{4}\!\pi y^{2}\!\,\mathrm{d}x}\\ &{~~~\!=\!\!\displaystyle\int_{\frac{\pi}{2}}^{0}\!\pi\cdot4(1+\cos\theta)^{2}\sin^{2}\!\theta\cdot2(-\sin\theta-2\sin\theta\cos\,\theta)\,\mathrm{d}\theta}\\ &{~~~\!=\!8\pi\!\bigg\{\!\frac{\pi}{2}\!\,(1+\cos\theta)^{2}\sin^{3}\!\theta(1+2\cos\theta)\,\mathrm{d}\theta}\\ &{~~~\!=\!20\pi.}\end{array}
$$  

法二由公式(d),有  

$$
V=\frac{2\pi}{3}{\int}_{a}^{\beta}r^{3}\,(\theta)\sin\,\theta\mathrm{d}\theta.
$$  
$$
\begin{array}{r l}&{=\displaystyle\frac{16}{3}\pi\!\!\left\lceil_{\circ}^{\frac{\pi}{2}}\sin\theta\cdot(1+\cos\theta)^{3}\mathrm{d}\theta=-\frac{16}{3}\pi\!\!\right\rceil_{\circ}^{\frac{\pi}{2}}(1+\cos\theta)^{3}\mathrm{d}(1+\cos\theta)}\\ &{=\displaystyle-\frac{16}{3}\pi\cdot\frac{1}{4}(1+\cos\theta)^{4}\left\lfloor_{\circ}^{\frac{\pi}{2}}=20\pi.\right\rceil_{\circ}^{\frac{\pi}{2}}}\end{array}
$$  

故选(A).  

# (3)平均值.  

$$
{\overline{{f}}}={\frac{1}{b-a}}{\int_{a}^{b}f(x)\,\mathrm{d}x}.
$$  

例10.8已知函数 $f(x)$ 在 $\left[0,{\frac{3\pi}{2}}\right]$ 上连续,在 $\left(0,\frac{3\pi}{2}\right)$ 内是函数 $\frac{\cos x}{2x-3\pi}$ 的一个原函$f(0)=0$ $f(x)$  

【解】应填 $\frac{1}{3\pi}$  

$f(x)$ 在区间 $\left[0,{\frac{3\pi}{2}}\right]$ 上的平均值为  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/824983ee8bf5514032e83cd40d68e56e7f6fa0d7ef7340eed087d32d5c9afa81.jpg)  

$$
\begin{array}{l}{{\displaystyle{\overline{{f}}=\frac{2}{3\pi}\!\!\int_{0}^{\frac{3\pi}{2}}\!\!f(x\,)\,{\mathrm{d}}x=\!\frac{2}{3\pi}\!\!\int_{0}^{\frac{3\pi}{2}}\!\left(\!\!\int_{0}^{x}\,\frac{\cos\,t}{2t-3\pi}{\mathrm{d}}t\right)\,{\mathrm{d}}x}\ ~}\\ {{\displaystyle~~~=\frac{2}{3\pi}\!\!\int_{0}^{\frac{3\pi}{2}}\!\!\!\mathrm{d}t\!\int_{t}^{\frac{3\pi}{2}}\frac{\cos\,t}{2t-3\pi}{\mathrm{d}}x=-\frac{1}{3\pi}\!\!\int_{0}^{\frac{3\pi}{2}}\!\cos\,t\,{\mathrm{d}}t=\!\frac{1}{3\pi}.}}\end{array}
$$  

# （4）平面曲线的弧长.（仅数学一、数学二）  

$\textcircled{1}$ 若平面光滑曲线由直角坐标方程 $y=y\left(x\right)\left(a\leqslant x\leqslant b\right)$ 给出，则  

$$
s=\!\int_{a}^{b}{\sqrt{1+\left[y^{'}(x)\right]^{2}}}\,\mathrm{d}x\,.
$$  

$\circledcirc$ 若平面光滑曲线由参数方程 $\begin{array}{r}{\left\{x=x\left(t\right),\right.}\\ {\left.\left|y=y\left(t\right)\right.}\end{array}\right.(\alpha\leqslant t\leqslant\beta)$ 给出，则  

$$
s=\!\int_{a}^{\beta}{\sqrt{[x^{\prime}(t)]^{2}+[y^{\prime}(t)]^{2}}}\,\mathrm{d}t.
$$  

$\circled{3}$ 若平面光滑曲线由极坐标方程 $r=r(\theta)(\alpha\leqslant\theta\leqslant\beta)$ 给出，则  

$$
s=\int_{\ a}^{\beta}{\sqrt{\left[r\left(\theta\right)\right]^{2}+\left[r^{^{\prime}}(\theta)\right]^{2}}}\,\mathrm{d}\theta.
$$  

例10.9设非负函数 $_{y}(x)$ 是微分方程 $2y y^{\prime}=\cos x$ 满足条件 $y\left(0\right)=0$ 的解,求曲线 $f_{n}\left(x\right)=n\!\int_{0}^{\frac{x}{n}}y\left(t\right)\mathrm{d}t\left(0\leqslant x\leqslant n\pi\right)$ 的弧长.  

【解】由 $2y y^{\prime}\!=\!\cos x$ 分离变量,得 $2y\,{\mathsf{d}}y=\cos\ x\,{\mathsf{d}}x$ ,两边积分,得 $y^{2}=\sin{x}+C$ ,又 ${\mathfrak{y}}(0)=$ 0，有 $C=0$ ,且 $_{y}(x)$ 非负，故 $y(x)\!=\!\sqrt{\sin{x}\,}.$ 于是  

$$
f_{n}\left(x\right)=n\!\int_{0}^{\frac{x}{n}}{\sqrt{\sin{\,t}}}\,\mathrm{d}t\,,
$$  

$$
f_{n}^{\prime}\left(x\right)=\sqrt{\sin\frac{x}{n}}.
$$  
根据弧长计算公式，得  

$$
\begin{array}{r l}&{s_{n}=\!\!\!\displaystyle\int_{0}^{n_{\pi}}\!\sqrt{1\!+\!\!\big[f_{n}^{\prime}\left(x\right)\big]^{2}}\,{\mathrm{d}}x\,=\!\!\displaystyle\int_{0}^{n_{\pi}}\!\sqrt{1\!+\!\sin\frac{x}{n}}\,{\mathrm{d}}x}\\ &{\quad=\!\!\displaystyle\int_{0}^{n_{\pi}}\!\sqrt{\!\left(\sin\frac{x}{2n}+\cos\frac{x}{2n}\right)^{2}}\,{\mathrm{d}}x\,=\!\!\!\displaystyle\int_{0}^{n_{\pi}}\!\left(\sin\frac{x}{2n}+\cos\frac{x}{2n}\right)\mathrm{d}x}\\ &{\quad\displaystyle\xrightarrow{\diamondsuit\frac{x}{2n}=u}2n\!\int_{0}^{\frac{x}{2}}(\sin u+\cos u\,)\,{\mathrm{d}}u=2n\left(1+1\right)=4n.}\end{array}
$$  

例10.10曲线 $r\theta=1$ 自 $\theta=\frac{3}{4}$ 至 $\theta=\frac{4}{3}$ 一段的弧长为  

【解】应填 ${\frac{5}{12}}+\ln\,{\frac{3}{2}}$   
由 $r\theta=1$ ，有 $r=\frac{1}{\theta}\,,r^{\prime}=-\,\frac{1}{\theta^{2}}$ 故  
$s=\int_{\frac{3}{4}}^{\frac{4}{3}}\sqrt{\frac{1}{\theta^{2}}+\frac{1}{\theta^{4}}}\,\mathrm{d}\theta=\int_{\frac{3}{4}}^{\frac{4}{3}}\frac{1}{\theta^{2}}\sqrt{1+\theta^{2}}\,\mathrm{d}\theta\,\frac{\theta=\tan\,t}{\mathrm{~arctan~}_{\frac{3}{4}}}\,\frac{1}{\tan^{2}\!t}\sqrt{1+\tan^{2}\!t}\sec^{2}\!t\,\mathrm{d}t$   
$=\!\int_{\arctan{\frac{3}{4}}}^{\arctan{\frac{4}{3}}}{\frac{1}{\tan^{2}{t}}}\sec^{3}{t}\,\mathrm{d}t=\!\int_{\arctan{\frac{3}{4}}}^{\arctan{\frac{4}{3}}}{\frac{1}{\sin^{2}{t}\cos{t}}}\mathrm{d}t=\!\int_{\arctan{\frac{3}{4}}}^{\arctan{\frac{4}{3}}}(\sec{t}+\cot{t}\csc{t})\,\mathrm{d}t$ $=(\ln\mid\sec t+\tan t\mid-\csc t){\Bigl\vert}{\begin{array}{l}{={\mathfrak{r}}\tan{\frac{4}{3}}}\\ {{\mathfrak{r}}\tan{\frac{3}{4}}}\end{array}}={\frac{5}{12}}+\ln{\frac{3}{2}}.$  

# (5）旋转曲面的面积(侧面积).(仅数学一、数学二）  

$\textcircled{1}$ 曲线 ${\boldsymbol{y}}={\boldsymbol{y}}\left({\boldsymbol{x}}\right)$ 在区间 $[a,b]$ 上的曲线弧段绕 $_{x}$ 轴旋转一周所得到的旋转曲面的面积  

$$
S=2\uppi\!\int_{\textit{a}}^{b}\mid y\left(x\,\right)\mid\sqrt{1+\left[y^{'}\!\left(x\,\right)\right]^{2}}\,\mathrm{d}x\,.
$$  

$\circledcirc$ 曲线 $x=x\left(t\right),y=y\left(t\right)\left(\alpha\leqslant t\leqslant\beta,x^{\prime}(t)\neq0\right)$ 在区间 $[\alpha\,,\beta]$ 上的曲线弧段绕 $_x$ 轴旋转一周所得到的旋转曲面的面积  

$$
S=2\uppi\int_{a}^{\beta}\mid y\left(t\right)\mid\sqrt{\left[x^{'}(t)\right]^{2}+\left[y^{'}(t)\right]^{2}}\,\mathrm{d}t\,.
$$  

$\textcircled{3}$ 曲线 $r=r(\theta)$ 在区间 $[\alpha\,,\beta]$ 上的曲线弧段绕 $_{x}$ 轴旋转一周所得到的旋转曲面的面积  

$$
S=2\uppi\int_{\circ}^{\beta}\mid r\left(\theta\right)\sin\theta\mid\sqrt{\left[r\left(\theta\right)\right]^{2}+\left[r^{\prime}(\theta\left)\right]^{2}}\,\mathrm{d}\theta.
$$  

例10.11 $D$ 是市曲线 $y=\sqrt{1-x^{\,^{2}}}(0\leqslant x\leqslant1)$  $\begin{array}{c}{{\left\langle x\left(t\right)=\,\cos^{3}t\,,\,\right\rangle}}\\ {{\left\langle y(t)=\,\sin^{3}t\,\right.}}\end{array}$ 的平面区域，求 $D$ 绕 $_{x}$ 轴旋转一周所得旋转体的体积和表面积.  

【解】设 $D$ 绕 $_{x}$ 轴旋转一周所得旋转体的体积为 $V$ ，表面积为 $S$ ，则  

$$
\begin{array}{c}{{\displaystyle V\!=\!\frac{2}{3}\pi-\!\int_{0}^{1}\!\pi y^{2}\left(t\right)\!\mathrm{d}\!\left[x\left(t\right)\right]\!=\!\frac{2}{3}\pi-\!\!\left[\!\!\left[\frac{\circ}{\frac{\pi}{3}}\!\!\right]\!\pi\!\sin^{\ell}t\left(\cos^{3}t\right)^{\prime}\!\!\mathrm{d}t\!\!\}}\\ {{\displaystyle=\!\frac{2}{3}\pi+3\pi\!\int_{0}^{\frac{\pi}{2}}\left(1-\cos^{2}t\right)^{3}\cos^{2}t\mathrm{d}\!\left(\cos t\right)\!\!=\!\frac{2}{3}\pi-\!\frac{16}{105}\pi=\!\frac{18}{35}\pi\,,}}\end{array}
$$  
下限值<上限$$
\begin{array}{r l}&{S=2\pi+\!\!\left(\!\!\int_{0}^{\frac{\pi}{2}}\!\!\left[2\pi y\left(t\right)\sqrt{\left[x^{\prime}(t)\right]^{2}+\left[y^{\prime}(t)\right]^{2}}\,\mathrm{d}t\right.\right.}\\ &{\left.\left.=2\pi+2\pi\!\right]^{\frac{\pi}{2}}\!\!\sin^{3}\!t\,\sqrt{9\cos^{4}\!t\sin^{2}\!t+9\sin^{4}\!t\cos^{2}\!t}\,\mathrm{d}t}\\ &{\left.\left.=2\pi+6\pi\!\right\lceil_{0}^{\frac{\pi}{2}}\!\sin^{4}\!t\cos t\,\mathrm{d}t=\!\frac{16}{5}\pi.\!\right.}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e89581d68e4f22a54edbf0a5662cb7983b9069d6c1965636c7de38e5eb0d1c00.jpg)  

例10.12双纽线 $r^{2}=\alpha^{2}\cos\,2\theta(\alpha>0)$ 绕极轴旋转一周所围成的旋转曲面面积 $S=..$  

【解】应填 $2\pi a^{2}(2-{\sqrt{2}}\,)$  

如图10-13所示，由对称性知，只需计算第一象限的曲线绕 $_{x}$ 轴旋转一周的曲面面积，且 $r=a\,{\sqrt{\cos\,2\theta}}$ ，于是  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/5c88f1b6832b6630c44197d9e1b50f496eea01d2a18a5321ce2087d84db3b5ab.jpg)  
图10-13  

$$
\begin{array}{r l}&{S=2\!\!\int_{0}^{\frac{\pi}{6}}2\pi r\sin\theta\,\sqrt{r^{2}+(r^{\prime})^{2}}\,\mathrm{d}\theta}\\ &{\quad=4\pi a\int_{0}^{\frac{\pi}{6}}\sqrt{\cos2\theta}\,\cdot\sin\theta\,\sqrt{a^{2}\cos2\theta+\left[\frac{a(-2\sin2\theta)}{2\sqrt{\cos2\theta}}\right]^{\frac{\pi}{6}}}d\theta}\\ &{\quad=4\pi a\int_{0}^{\frac{\pi}{6}}\sqrt{\cos2\theta}\,\cdot\sin\theta\,\sqrt{a^{2}\cos2\theta+\frac{a^{2}\sin^{2}2\theta}{\cos2\theta}}\,\mathrm{d}\theta}\\ &{\quad=4\pi a\int_{0}^{\frac{\pi}{6}}\sqrt{\cos2\theta}\,\cdot\sin\theta\,\cdot\frac{a}{\sqrt{\cos2\theta}}\,\mathrm{d}\theta}\\ &{\quad=4\pi a^{2}\!\int_{0}^{\frac{\pi}{6}}\sin\theta\,\mathrm{d}\theta=2\pi a^{2}\,(2-\sqrt{2})\,.}\end{array}
$$  

# （6）“平面上的曲边梯形”的形心坐标公式.（仅数学一、数学二）  

设 $D\!=\!\{\,(x\,,\!y\,)\;|\;0\!\leqslant y\leqslant f(x\,)\,,a\leqslant x\!\leqslant b\,\}\,,f(x\,)$ 在 $[a,b]$ 上连续,如图10-14 所示. $D$ 的形心坐标 $\overline{{x}}\,,\overline{{y}}$ 的计算公式：  

$$
\begin{array}{r l r}&{}&{\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/87b9255445e5e172171ea49e9acd326150e89b2c40cda2aa55f854574c670eee.jpg)  
图10-14  

# 【注】若考题为求质量均匀分布的平面薄片的质心，也就是平面 $\boldsymbol{D}$ 的形心问题.公式如上。  

例10.13设函数 $y=f(x\,)$ 在区间 $[0,\!a]$ 上非负， $f^{\prime\prime}(x)\!>\!0$ ,且 $f(0)=$ 0.有一块质量均匀分布的平板 $D$ ,其占据的区域是曲线 $y=f(x\,)$ 与直线 $_x=$  $^{\,a}$ 以及 $_{x}$ 轴围成的平面图形.用 $\overline{{x}}$ 表示平板 $D$ 的质心的横坐标.证明： $\overline{{x}}>$  ${\frac{2}{3}}a$ （见图10-15）.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/cad0ba04b7eaff30e735d4f88b0ab62cf0dd588e170443819c470eee5dfbdf4c.jpg)  
图10-15  
【证】由 $\overline{{x}}=\frac{\displaystyle\int_{0}^{a}x f(x\,)\mathrm{d}x}{\displaystyle\int_{0}^{a}f(x\,)\mathrm{d}x}>\frac{2}{3}a$ ,将 $^{\,a}$ 变量化为 $_{x}$ 冷 $F(x)\!=\!\!\int_{0}^{x}t\,f(t)\,\mathrm{d}t-{\frac{2x}{3}}\!\!\int_{0}^{x}f(t)\,\mathrm{d}t$ 则有 $F(0)=0$ ，又对任意 $x\in(0,a)$ ,有  

$$
\begin{array}{l}{{\displaystyle F^{\prime}(x)=x f(x)-\frac{2}{3}{\bf\int}_{0}^{x}f(t){\mathrm{d}}t-\frac{2}{3}x f(x)}}\\ {{\displaystyle\qquad\qquad=\frac{1}{3}x f(x)-\frac{2}{3}{\bf\int}_{0}^{x}f(t){\mathrm{d}}t\,,}}\end{array}
$$  

$$
\begin{array}{c}{{F^{\prime\prime}(x)=\displaystyle{\frac{1}{3}}f(x)+\displaystyle{\frac{1}{3}}x f^{\prime}(x)-\displaystyle{\frac{2}{3}}f(x)=\displaystyle{\frac{1}{3}}x f^{\prime}(x)-\displaystyle{\frac{1}{3}}f(x)}}\\ {{=\displaystyle{\frac{1}{3}}x\big[f^{\prime}(x)-f^{\prime}(\xi)\big](0<\xi<x).}}\end{array}
$$  

因为 $f^{\prime\prime}(x)>0$ ,所以 $f^{\prime}(x)>f^{\prime}(\pmb{\xi})$ ，于是 $F^{\prime\prime}(x)>0$ ，从而 $F^{\prime}(x)$ 在区间 $[0,\alpha]$ 上单调增加,因此当 $0<x\leqslant a$ 时，有 $F^{\prime}(x)>F^{\prime}(0)=0\,$  

故 $F(x)$ 在区间 $[0,\alpha]$ 上单调增加， $F(a)>F(0)=0.$ 所以有  

$$
\int_{0}^{a}\!x\,f(x\,)\,\mathrm{d}x-{\frac{2a}{3}}{\bigg\mathrm{\int}}_{0}^{a}\,f(x\,)\,\mathrm{d}x>0
$$  

# （7）平行截面面积为已知的立体体积.（仅数学一、数学二）  

在区间 $[a,b]$ 上,垂直于 $_{x}$ 轴的平面截立体 $\Omega$ 所得到的截面面积为 $_{x}$ 的连续函数S $(x$ ),则 $\Omega$ 的体积为  

$$
V=\!\int_{a}^{b}\!S\,(\,x\,)\,\mathrm{d}x\,.
$$  

例10.14曲线 $y={\sqrt{x\ }}$ 与 $y=x$ 所围平面有界区域绕直线 $_{y}=x$ 旋转一周所得旋转体的体积为  

【解】应填 ${\frac{\sqrt{2}}{60}}\pi.$  

在例10.6中，我们用了一种方法求此问题.这里，我们再从“平行截面面积为已知的立体体积”角度，提供第二种方法进行求解.  

$_y={\sqrt{x\vphantom{\sqrt{x}}}}$ 与 $y=x$ 交于点(0,0)，(1,1),如图10-16所示. ${\mathsf{d}}l=\!\sqrt{2}\,{\mathsf{d}}.x$ ,曲线 $_y={\sqrt{x}}$ 上的点到 $y=x$ 的距离为 $r=\frac{\sqrt{x}-x}{\sqrt{2}}$ 故垂直于 $_{x}$ 轴的平面截  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/4461bfd10c61210cfcd41ccf5d77abb5bc2892f53381755b4773d943b67de19e.jpg)  
图10-16  

该旋转体所得的截面面积为 $S(x)=\!\sqrt{2}\,\pi\!\left({\frac{{\sqrt{x}}\,-x}{\sqrt{2}}}\right)^{2}$ 因此，旋转体体积为  

$$
V=\!\!\int_{0}^{1}\!{\sqrt{2}}\,\pi\!\left({\frac{{\sqrt{x}}-x}{\sqrt{2}}}\right)^{2}\!\mathrm{d}x=\!\!\int_{0}^{1}\!{\frac{\pi}{\sqrt{2}}}(x-2x^{\frac{3}{2}}+x^{2}\,)\,\mathrm{d}x=\!\!{\frac{\sqrt{2}}{60}}\pi.
$$  

【注】事实上 $V=\int_{a}^{b}S(x)\,\mathrm{d}x$ 就是 $V=\int_{a}^{b}\pi f^{2}(x)\mathrm{d}x$ 的一般化.  
# 第11讲  

# 一元函数积分学的应用 ( 二)积分等式与积分不等式  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e8660a6cde6cd7870f1b26f0c81cd1f388e3ffff005df287ba0fe1e26e17c67c.jpg)  

# 一积分等式  

（1）常用积分等式（见第9讲“三、定积分的计算”）.（2）通过证明某特殊积分等式求某特殊积分.  
（3）通过积分法证明积分等式.  
（4）积分形式的中值定理  

例11.1设 $f(x)$ 是连续的偶函数，且是以 $T$ 为周期的周期函数.  

$$
\int_{0}^{n\tau}\!x\,f(x\,)\,\mathrm{d}x={\frac{n^{\,2}\,T}{2}}{\bigg\lbrack}^{\tau}{f(x\,)}\,\mathrm{d}x\,(n=1,2,3,\cdots)\,;
$$  

（2）利用（1）的结论计算 $I=\int_{0}^{n\pi}\!x\ \mid\sin\ x\ \mid\mathrm{d}x$  

(1)[证】 $\int_{0}^{n T}\!x\,f(x\,)\,\mathrm{d}x\,\,\frac{x\,=\,n T-t}{\l}\,n\,T\!\!\int_{0}^{n T}f(t\,)\,\mathrm{d}t-\int_{0}^{n T}\!t\,f(t\,)\,\mathrm{d}t\,,$  

$$
\int_{0}^{n T}\!x\,f(x\,)\mathrm{d}x={\frac{n T}{2}}\!\!\int_{0}^{n T}f(x\,)\mathrm{d}x\,.
$$  

又$f(x+T)=f(x)$ ，则  
$$
\int_{0}^{n T}f(x\,)\mathrm{d}x=n\!\int_{0}^{\tau}f(x\,)\mathrm{d}x\:,
$$  

故  

$$
\int_{0}^{n\tau}\!x\,f(x\,)\,\mathrm{d}x={\frac{n^{2}\,T}{2}}{\bigg\lbrack}^{\tau}\,f(x\,)\,\mathrm{d}x\,(n=1,2,3,\cdots).
$$  

（2)【解】 $1$ sin $_{x}$ |是连续的以 $\pi$ 为周期的偶函数，故  

$$
\begin{array}{l}{\displaystyle{I=\int_{\,\,\,^{\prime}}^{\,n\,\pi}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! 
$$  

例11.2设 $\varphi(x)$ ）是可微函数 $f(x$ ）的反函数，且 $f(1)=0$ ， $\int_{0}^{1}\!x f(x\,)\,\mathrm{d}x\,=1$ ，则$\int_{0}^{1}\left[\int_{0}^{f(x)}\varphi\left(t\right)\mathrm{d}t\right]\mathrm{d}x=\cfrac{\,}{\cdot}$  

【解】应填2.  

$$
\begin{array}{l}{\displaystyle\int_{0}^{1}\left[\displaystyle\int_{0}^{f(x)}\varphi(t)\,\mathrm{d}t\right]\mathrm{d}x=x\displaystyle\int_{0}^{f(x)}\varphi(t)\,\mathrm{d}t\,\left|\displaystyle\int_{0}^{1}-\displaystyle\int_{0}^{1}x\varphi\big[f(x)\big]\star f^{\prime}(x)\,\mathrm{d}x\right.}\\ {\displaystyle\qquad\qquad\qquad\qquad\qquad\left.=-\displaystyle\int_{0}^{1}x^{\,2}\,\star f^{\prime}(x)\,\mathrm{d}x=-\displaystyle\int_{0}^{1}x^{\,2}\,\mathrm{d}\big[f(x)\big]\right.}\\ {\displaystyle\qquad\qquad\qquad\qquad\qquad\left.=-x^{\,2}f(x)\,\Big|_{0}^{1}+2\displaystyle\int_{0}^{1}x\,f(x)\,\mathrm{d}x=2.}\end{array}
$$  

例11.3设 $f(x)$ 在 $\left[0,{\frac{\pi}{2}}\right]$ 上有连续的二阶导数，且 $f(0)\;=\;2,f{\Big(}{\frac{\pi}{2}}{\Big)}=\;1$  $\int_{0}^{\frac{\pi}{2}}f(x\,)\mathrm{e}^{\sin x}\cos\,x\mathrm{d}x=\,2(\mathrm{e}-1)$ .证明：存在 $\varepsilon\in\left(0,\frac{\pi}{2}\right)$ ，使得 $f^{\prime\prime}(\pmb{\xi})<0$  

【证】由推广的积分中值定理知， $\exists\,\eta\in\,\left(0,\frac{\pi}{2}\right)$ ，使得 $f(\eta)\!\int_{0}^{\frac{\pi}{2}}\!\mathrm{e}^{\sin x}\cos\,x\mathrm{d}x=2(\mathrm{e}-1).$ 又$\int_{0}^{\frac{\pi}{2}}\mathrm{e}^{\sin x}\cos\,x\mathrm{d}x=\mathrm{e}^{\sin x}\mid_{0}^{\frac{\pi}{2}}=\mathrm{e}-1$ ，于是 $f(\eta)\cdot(\mathrm{e}-1)=2(\mathrm{e}-1)$ ,即 $\exists\,\eta\in\left(0,\frac{\pi}{2}\right)$ ，使得 $f(\eta)=2.$  

因 $f(0)\!=\!2,f(\eta)\!=\!2,f\!\left({\frac{\pi}{2}}\right)\!=\!1$ 由罗尔定理知，存在 $\xi_{1}\in(0,\eta)$ ，使得 $f^{\prime}(\pmb{\xi}_{1})\!=\!0$ ,又由拉格朗日中值定理知,存在 $\xi_{2}\in\left(\eta,\frac{\pi}{2}\right)$ ，使得  

$$
f^{\prime}(\xi_{2})=\frac{f\left(\frac{\pi}{2}\right)-f(\eta)}{\frac{\pi}{2}-\eta}\!=\!\frac{1-2}{\frac{\pi}{2}-\eta}\!<0\,,
$$  

再由拉格朗日中值定理知，存在 $\hat{\mathsf{\xi}}\in(\hat{\mathsf{\xi}}_{1},\hat{\mathsf{\xi}}_{2})\subset\left(0,\frac{\pi}{2}\right)$ ，使得 $f^{\prime\prime}(\pmb{\xi})=\frac{f^{\prime}(\pmb{\xi}_{2})-f^{\prime}(\pmb{\xi}_{1})}{\pmb{\xi}_{2}-\pmb{\xi}_{1}}<0$  
# 积分不等式  

# （1）用函数的性态  

例11. 4设 $f(x$ ）在 $[a,b]$ 上二阶可导， $f^{\prime}(x)>0,f^{\prime\prime}(x)>0$ （见图11-1),证明：  

$$
{\frac{1}{2}}\bigl[f(a)+f(b)\bigr](b-a)>\int_{a}^{b}f(x)\,\mathrm{d}x.
$$  

【分析】首先将某一限（取上限或下限）变量化，然后移项构造辅 助函数，由辅助函数的单调性来证明不等式，此方法多用于所给条件为“ $f(x)$ 在 $[a,b]$ 上连续”的情形.  

【证】令  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/2d4f11b3be8c0a8150fe16150d9eb8f09a3d1f5a16830b05e995a9e96c583193.jpg)  
图11-1  

$$
F(x)={\frac{1}{2}}{\big[}f(a)+f(x\,){\big]}(x-a\,)-\int_{a}^{x}f(t)\mathrm{d}t\,,
$$  

$$
\begin{array}{l}{{\displaystyle F^{\prime}(x)\!=\!\frac{1}{2}f^{\prime}(x)(x-a)\!+\!\frac{1}{2}\big[f(a)\!+\!f(x)\big]\!-\!f(x)}}\\ {{\displaystyle\qquad=\frac{1}{2}f^{\prime}(x)(x-a)+\!\frac{1}{2}f(a)-\frac{1}{2}f(x)}}\\ {{\displaystyle\qquad=\frac{1}{2}f^{\prime}(x)(x-a)-\frac{1}{2}f^{\prime}(\eta)(\frac{\!\!\!\!\slash\varepsilon\!\!\!\!\slash-\!\!\!\!\slash\varepsilon\!\!\!\!\slash}{x-a})}}\\ {{\displaystyle\qquad=\frac{1}{2}\big[f^{\prime}(x)-f^{\prime}(\eta)\big](x-a)>0(x>a),}}\end{array}
$$  

$$
\widehat{\frac{\star\,}{a_{\ n\rightarrow\frac{x}{11\rightarrow2}}}}
$$  

其中 $\eta\in\mathsf{\Gamma}(a\,,x)$ （见图11-2）.所以 $F(x)$ 严格单调增加,故 $F(b)>F(a)=0$ ,即  

$$
{\frac{1}{2}}\bigl[f(a)+f(b)\bigr](b-a)>\int_{a}^{b}f(x)\mathrm{d}x.
$$  

例11.5证明：当 $0\leqslant a\leqslant1$ 时， $\int_{0}^{a}\left(1-x^{\,2}\right)^{\frac{5}{2}}\mathrm{d}x\geqslant\frac{5a\,\pi}{32}.$  

【证】令 $f(a)=\!\int_{0}^{a}{(1-x^{2})^{\frac{5}{2}}\mathrm{d}x}-\frac{5a\,\uppi}{32}$ 则  

$$
f(0)=0\,.
$$  

f $\displaystyle^{\cdot}(1)=\!\int_{0}^{1}(1-x^{\:2})^{\frac{5}{2}}\mathrm{d}x-\frac{5\pi}{32}\,\frac{\:\not\ln x=\sin\,t}{\:2}\!\int_{0}^{\frac{\pi}{2}}\cos^{6}t\,\mathrm{d}t-\frac{5\pi}{32}=\frac{5}{6}\times\frac{3}{4}\times\frac{1}{2}\times\frac{\pi}{2}-\frac{5}{3}$ =0，且 $f(\alpha)$ 在[0,1]上存在二阶导数.  

$$
f^{\prime}(a)=(1-a^{2})^{\frac{5}{2}}-\frac{5\pi}{32},f^{\prime\prime}(a)=-\,5a\,(1-a^{2})^{\frac{3}{2}}.
$$  

当 $0<a<1$ 时， $f^{\prime\prime}(a)<0$ ，故 $f(a)>0$ .因此，对于任意 $a\in[0,1],f(a)\geqslant0$ ,即  

$\int_{0}^{a}\left(1-x^{\,2}\right)^{\frac{5}{2}}\mathrm{d}x\,\geqslant\frac{5a\,\pi}{32}.$ f(a)在 $0{<}a{<}1$ 上是凸的  
# (2) 处理被积函数.  

$\textcircled{1}$ 已知 $f\!\left(\boldsymbol{x}\,\right)\leqslant g\!\left(\boldsymbol{x}\,\right)$ ，用积分保号性证得 $\int_{a}^{b}f(x)\mathrm{d}x\leqslant\int_{a}^{b}g(x)\mathrm{d}x\,,a<b.$  

例11.6设 $f(x)$ 为正值连续函数且 $f(x)<a\,,a$ 为正常数,则 $\forall\,b\in\mathsf{\Gamma}(0,1)$ ,有(  

$$
\begin{array}{r l r}&{(\mathbf{A})a\displaystyle\int_{0}^{1}\sqrt{f(b x\,)}\,\mathrm{d}x<\sqrt{b}\qquad\qquad}&{(\mathbf{B})a\displaystyle\int_{0}^{1}\sqrt{f(b x\,)}\,\mathrm{d}x<b}\\ &{(\mathbf{C})b\displaystyle\int_{0}^{1}\sqrt{f(b x\,)}\,\mathrm{d}x<\sqrt{a}\qquad\qquad}&{(\mathbf{D})b\displaystyle\int_{0}^{1}\sqrt{f(b x\,)}\,\mathrm{d}x<a}\end{array}
$$  

【解】应选(C).  

$$
\int_{0}^{1}{\sqrt{f(b x)}}\,\mathrm{d}x~{\frac{b x=t}{\mathrm{d}x={\frac{1}{b}}\mathrm{d}t}}{\int_{0}^{b}{\sqrt{f(t)}}\ {\frac{1}{b}}\mathrm{d}t}={\frac{1}{b}}{\int_{0}^{b}{\sqrt{f(t)}}\,\mathrm{d}t}
$$  

$$
<\frac{1}{b}\!\!\int_{0}^{1}\sqrt{f(t)}\,\mathrm{d}t<\frac{1}{b}\!\!\int_{0}^{1}\sqrt{a}\,\mathrm{d}t=\!\!\frac{\sqrt{a}}{b},
$$  

即$b\int_{0}^{1}{\sqrt{f(b x)}}\,\mathrm{d}x<{\sqrt{a}}$ ,选(C).  

# $\circledcirc$ 用拉格朗日中值定理.  

用拉格朗日中值定理处理被积函数 $f(x)$ ,再作不等式，进一步，用积分保号性.此方法多用于所给条件为“ $f(x)$ 一阶可导”且题中有较简单函数值（甚至为0）的题目.  

例 11. 7设 $f(x)$ 在[0,1]上二阶可导， $f(0)=0\,,f^{\prime}(x\,)>0\,,f^{\prime\prime}(x\,)>0$ ，则对于  

$$
M=\!\!\int_{0}^{\frac{1}{2}}f(x\,)\,\mathrm{d}x\,,N=\!\!\int_{\frac{1}{2}}^{1}\left[f(x\,)-f\Big(\frac{1}{2}\Big)\right]\,\mathrm{d}x\,,P=\frac{1}{4}\left[f(1)-f\Big(\frac{1}{2}\Big)\right]\,,
$$  

其大小顺序排列正确的是(  

$$
\begin{array}{r l r}{\mathrm{(A)}N<M<P}&{{}\quad\mathrm{~(~B)~}N<M<N}\\ {\mathrm{(C)}M<P<N}&{{}\quad\mathrm{~(~)~}N<N<P}\end{array}
$$  

【解】应选(D).  

$N=\!\!\int_{\frac{1}{2}}^{1}\left[f(x\,)-f\Big(\frac{1}{2}\Big)\right]\mathrm{d}x\,\,\frac{\Leftrightarrow\,x-\frac{1}{2}=t}{2}\int_{0}^{\frac{1}{2}}\left[f\Big(t+\frac{1}{2}\Big)-f\Big(\frac{1}{2}\Big)\right]\mathrm{d}t\,,^{\frac{1}{2}}\int_{\frac{1}{2}}^{\frac{1}{2}}f\Big(t\Big)\,\Big(f\Big(t+\frac{1}{2}\Big)-f\Big(\frac{1}{2}\Big)\Big)\,\mathrm{d}t\,.$ $N-M=\!\!\int_{0}^{\frac{1}{2}}\left[f\left(x+{\frac{1}{2}}\right)-f\!\left({\frac{1}{2}}\right)-f(x\,)\right]\,\mathrm{d}x\,,$  

其中  

$$
f\left(\boldsymbol{x}+\frac{1}{2}\right)-f\left(\frac{1}{2}\right)=f^{\prime}(\xi_{1})\,\bullet\,\boldsymbol{x}\,,\frac{1}{2}<\hat{\xi}_{1}<\boldsymbol{x}+\frac{1}{2},
$$  

$$
f(x)=f(x)-f(0)=f^{\prime}(\xi_{2})\bullet x\,,0<\widehat{\mathfrak{s}}_{2}<x<\frac{1}{2},
$$  

$\xi_{\scriptscriptstyle1},\xi_{\scriptscriptstyle2}$ 的取值如图11-3（a）所示.则  

$$
\begin{array}{r}{f\Big(x+\displaystyle\frac{1}{2}\Big)-f\Big(\frac{1}{2}\Big)-f(x\,)=f^{\prime}(\star_{1})\,\bullet\,x-f^{\prime}(\star_{2})\,\bullet\,x}\\ {=\big[f^{\prime}(\widehat{\mathfrak{s}}_{1})-f^{\prime}(\widehat{\mathfrak{s}}_{2})\big]\bullet x\,,}\end{array}
$$  
由 $f^{\prime\prime}(x)>0$ ,可知 $f^{\prime}(x)$ 严格单调增加,即 $f^{\prime}(\pmb{\xi}_{1})>f^{\prime}(\pmb{\xi}_{2})$ ,于是 $(\texttt{\textbf{\em x}})$ 式大于0,由积分保号性知， $N-M>0$ ,即 $N>M$ ：  

又由 $f^{\prime\prime}(x)\,{>}\,0$ ，则 $f(x)$ 的图形是凹的， $N$ 表示图11-3(b）中阴影部分的面积，即曲边三角形ABC的面积， $P$ 表示 $\triangle A B C$ 的面积，显然 $N<P$ （其严格证明见例11.4）.  

综上， $M<N<P$ ,选(D).  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/bceb5d116fe3c1c7328d4dae6f3aff755506234ea4d95543d3116c3759d92c28.jpg)  
图11-3  

#  $\textcircled{3}$ 用泰勒公式.  

将 $f(x)$ 展开成泰勒公式，再作不等式，进一步，用积分保号性.此方法多用于所给条件为 $f(x)$ 二阶（或更高阶）可导”且题中有较简单函数值（甚至为0）的题目.  

例 11. 8设 $f(x)$ 二阶可导，且 $f^{\prime\prime}(x)\geqslant0\,,u\left(t\right)$ 为任一连续函数， $a>0$ 证明：  

$$
\frac{1}{a}{\int}_{0}^{a}\,f\big[u\left(t\,\right)\big]\mathrm{d}t\geqslant f\left[\frac{1}{a}{\int}_{0}^{a}u\left(t\,\right)\mathrm{d}t\right].
$$  

【证】由于 $f^{\prime\prime}(x)\geq0$ ,则由泰勒公式,有  

$$
\begin{array}{c}{{f(x)=f(x_{0})+f^{\prime}(x_{0})(x-x_{\circ})+\displaystyle\frac{1}{2}f^{\prime\prime}(\hat{\mathfrak{s}})(x-x_{\circ})^{2}(\hat{\mathfrak{s}}\,\,\hat{\mathfrak{f}}\,\hat{\mathfrak{r}}\,\mathcal{F}_{x_{0}}\,\,\overset{\leftrightarrow}{\mathcal{G}}\,x_{\circ}\,\,\hat{\mathfrak{z}}\,\,x_{\circ})}}\\ {{\geqslant f(x_{0})+f^{\prime}(x_{0})(x-x_{0}),}}\end{array}
$$  

取$x_{\,\,0}=\frac{1}{a}\!\int_{\,\,0}^{a}u\left(t\,\right)\mathrm{d}t\,,x=u\left(t\,\right)$ ，代人上式，则有  

$$
f\Big[u\left(t\right)\Big]\geqslant f\left[\frac{1}{a}\!\!\int_{0}^{a}\!\!u\left(t\right)\mathrm{d}t\right]+f^{\prime}(x\,_{0}\,)\Big[u\left(t\right)-x\,_{0}\Big],
$$  

对上式两端从0到 $^{a}$ 积分，得  

$$
\begin{array}{r l}&{\displaystyle\int_{0}^{a}{f\big[u\left(t\right)\big]\mathrm{d}t}\geqslant a f\left[\frac{1}{a}\!\int_{0}^{a}{u\left(t\right)\mathrm{d}t}\right]+f^{\prime}(x_{0})\underbrace{{\left[\!\int_{0}^{a}\!u\left(t\right)\mathrm{d}t-a x_{0}\right]}}_{=0}=a f\left[\frac{1}{a}\!\int_{0}^{a}\!u\left(t\right)\mathrm{d}t\right]}\\ &{\displaystyle\frac{1}{a}\!\int_{0}^{a}{f\big[u\left(t\right)\big]\mathrm{d}t}\geqslant f\left[\frac{1}{a}\!\int_{0}^{a}\!u\left(t\right)\right]\mathrm{d}t.}\end{array}
$$  

# $\circled{4}$ 用积分法.  

例 11. 9设函数 $f(x)=\!\int_{x}^{x+1}\!\sin\,\mathrm{e}^{\prime}\,\mathrm{d}t\,.$ 证明：  

$(1)\,f(x\,)={\frac{\cos\,\,\mathbf{e}^{x}}{\mathbf{e}^{x}}}-{\frac{\cos\,\,\mathbf{e}^{x+1}}{\mathbf{e}^{x+1}}}-\int_{\mathbf{e}^{x}}^{\mathbf{e}^{x+1}}\,{\frac{1}{u^{2}}}\mathrm{cos}\,\,u\,\mathrm{d}u\,;$ $(\,2\,)\,{\bf e}^{x}\mid f(x\,)\mid\leqslant2.$  
【证】被积函数 sin $\mathbf{e}^{t}$ 比较复杂,无法积分,通过变量代换可将其变得简单些(此时积分区间的上、下限必然会变得复杂些），然后再做下去.  

$$
f(x)\,{\frac{\Leftrightarrow\,{\mathsf{e}}^{\prime}\,=\,u}{\mathsf{e}^{x}}}{\int}_{\mathsf{e}^{\prime}}^{\mathsf{e}^{x+1}}\,{\frac{1}{u}}\sin\,u\,\mathrm{d}u=-{\frac{1}{u}}\cos\,u\,{\Big|}_{\mathsf{e}^{x}}^{\mathsf{e}^{x+1}}-{\int}_{\mathsf{e}^{x}}^{\mathsf{e}^{x+1}}\,{\frac{1}{u^{2}}}\cos\,u\,\mathrm{d}u
$$  

$$
=\frac{\cos\;\mathrm{e}^{x}}{\mathrm{e}^{x}}-\frac{\cos\;\mathrm{e}^{x\,+1}}{\mathrm{e}^{x\,+1}}-\int_{\mathrm{e}^{x}}^{\mathrm{e}^{x\,+1}}\;\frac{1}{u^{2}}\cos\;u\,\mathrm{d}u\,.
$$  

$$
\begin{array}{r l}&{\mid f(x)\mid\leqslant\left\vert\frac{\cos\,\mathrm{e}^{x}}{\mathrm{e}^{x}}\right\vert+\left\vert\frac{\cos\,\mathrm{e}^{x^{+1}}}{\mathrm{e}^{x^{+1}}}\right\vert\!+\!\int_{\mathrm{e}^{x}}^{\mathrm{e}^{x^{+1}}}\left\vert\frac{\cos\,u}{u^{2}}\right\vert\mathrm{d}u}\\ &{\qquad\leqslant\frac{1}{\mathrm{e}^{x}}\!+\!\frac{1}{\mathrm{e}^{x^{+1}}}\!+\!\int_{\mathrm{e}^{x}}^{\mathrm{e}^{x^{+1}}}\frac{1}{u^{2}}\mathrm{d}u=\!\frac{1}{\mathrm{e}^{x}}\!+\!\frac{1}{\mathrm{e}^{x+1}}\!-\!\frac{1}{\mathrm{e}^{x^{+1}}}\!+\!\frac{1}{\mathrm{e}^{x}}\!=\!\frac{2}{\mathrm{e}^{x}},}\end{array}
$$  

即$\mathbf{e}^{x}\ |\ f(x\,)\ |\leqslant2.$  

【注】利用常见不等关系处理被积函数，进一步用积分保号性。其中常见不等关系： $|\,\sin\,x\ |\leqslant1,\ |\ \cos x\ |\leqslant1,\sin\,x\leqslant x\,(x\geqslant0)$ ，闭区间上的连续函数 $f(x)$ 有 $\mid f(x)\mid\leqslant$ M(3M> 0), $\sqrt{a b}\leqslant\frac{a+b}{2}\leqslant\sqrt{\frac{a^{2}+b^{2}}{2}}\,(a\,,b>0)$ 等。  

[例 11, 10]设 $\mid f(x)\mid\leqslant\pi,f^{\prime}(x)\geqslant m>0(a\leqslant x\leqslant b)$ ，证明： $\left|\int_{a}^{b}\sin\ f(x\ s)\mathrm{d}x\ \right|\leqslant{\frac{2}{m}}.$  

【证】当 $a\leqslant x\leqslant b$ 时， $f^{\prime}(x)>0,f(x)$ 在 $[a,b]$ 上严格单调增加,故其存在反函数.记 $t=\;f(x)$ ,其反函数记为 $x=g(t)$ ，又记 $\alpha=f(a),\beta=f(b)$ ，由 $\mid f(x)\mid\leqslant\pi$ ，则 $-\pi\!\leqslant\!\alpha\!<\!\beta\!\leqslant$  $\pi$ ，故  

$$
\int_{a}^{b}\sin\,f(x\,)\mathrm{d}x=\!\int_{a}^{\beta}\!\sin\,t\,\cdot\,g^{\prime}(t\,)\mathrm{d}t\,,
$$  

由于 $f^{\prime}(x)\geq m>0$ ，故 $0<g^{\prime}(t)=\!\frac{1}{f^{\prime}(x)}\leqslant\frac{1}{m}$ ，则  

$$
\left|\int_{a}^{b}\sin\,f(x)\mathrm{d}x\,\right|=\left|\int_{a}^{\mu}\sin\,t\,\cdot\,g^{\prime}(t)\mathrm{d}t\,\right|\leqslant\left|\int_{0}^{\mathfrak{x}}\sin\,t\,\cdot\,g^{\prime}(t)\mathrm{d}t\,\right|\leqslant\frac{1}{m}\!\!\int_{0}^{\mathfrak{x}}\!\sin\,t\,\mathrm{d}t=\frac{2}{m}.
$$  

【注](1) 见到复合函数的积分 $\int\displaylimits^{b}\sin\ f(x)\,\mathrm{d}x$ ，一般要想到换元法，令 $f(x\,)=t$ ,甚至有时(此题不用)令 sin $f(x\,)=t$ .这是考研的重要思路.  

（2）本题还考查了一个重要知识点：反函数的导数.考生需注意.  
# 第12讲一元函数积分学的应用 (三)物理应用与经济应用  

# 知识结构  

物理应用(微元法)(仅数学一、数学二）  

位移大小 ${\begin{array}{r l}&{{\cfrac{\displaystyle\int_{t_{1}}^{t_{2}}\upsilon\left(t\right)\mathrm{d}t}}}\\ &{{\left.\displaystyle\int_{t_{1}}^{t_{2}}\;\left|\;\;\upsilon\left(t\right)\;\right|\;\mathrm{d}t}}\end{array}}\,$   
位移大小与总路程总路程  
变力沿直线做功 $W=\!\int_{a}^{b}\!F(x)\,\mathrm{d}x$   
静水压力 $P=\rho g\!\int_{\,a}^{b}x\,\big[f(x\,)-h\left(x\,\right)\big]\mathrm{d}x$   
细杆质心 $\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\overline{{x}}=\!\!\frac{\displaystyle\int_{a}^{b}\!x\rho\left(x\,\right)\mathrm{d}x}{\displaystyle\int_{a}^{b}\!\rho\left(x\,\right)\mathrm{d}x}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,x\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! $   
求平均量 $\overline{{y}}=\frac{1}{b-a}\!\int_{a}^{b}y\left(x\right)\mathbf{d}x$   
求总量 $Q(t)=Q(t_{0})+\int_{t_{0}}^{t}Q^{\prime}(u\,)\,\mathrm{d}u\,,t>t_{0}$  

经济应用(仅数学三)  

物理应用(微元法)(仅数学一、数学二)  

1.位移大小与总路程  

位移大小： $\int_{t_{1}}^{t_{2}}v\left(t\right)\mathrm{d}t\;,$ 总路程： $\int_{\,t_{1}}^{\,t_{2}}\;\mid v\left(t\right)\mid\,\mathrm{d}t\;,$ 其中 $\boldsymbol{v}(t)$ 为时间 $t_{\textrm{l}}$ 到 $t_{2}$ 上的速度函数.  

例 12 1质点以速度 $v\,{=}\frac{1}{(1+t^{2})(1+t^{\prime}{\,})}(\alpha\geqslant0)\,\mathrm{m}/\mathrm{s}$ 作直线运动，当初速度 $v_{0}=\!\!1\ \mathrm{m/s}$ 时，质点所能走过的最远距离为  

[解】应填 $\frac{\pi}{4}\mathrm{~m~}$  
# 第12讲 一元函数和分学的应用 (三)一物理左用与经清应用  

记速度函数 $v(t)=\frac{1}{(1+t^{2})(1+t^{\circ})}$ ，则所求为  

$$
\int_{0}^{+\infty}v\left(t\right)\mathrm{d}t=\int_{0}^{+\infty}\frac{\mathrm{d}t}{(1+t^{2})(1+t^{\circ})}\,,
$$  

$t={\frac{1}{x}}$ 得到 $\int_{0}^{+\infty}\,{\frac{\mathrm{d}t}{(1+t^{2})(1+t^{*})}}=\int_{+\infty}^{0}\,{\frac{-\,x^{\,a}\,\mathrm{d}x}{(1+x^{\,2})(1+x^{\,a}\,)}}$ 又  

$$
\int_{+\infty}^{\L^{0}}\,\frac{\displaystyle-\,x^{\ l}\,{\mathrm{d}}x}{\displaystyle(1+x^{\ l^{\frac{\l}{2}}})(1+x^{\ l^{\frac{\l}{2}}})}=\!\!\int_{\L^{0}}^{+\infty}\,\frac{t^{\L^{a}}\,{\mathrm{d}}t}{\displaystyle(1+t^{\ l^{\frac{\l}{2}}})(1+t^{\l^{a}})}\,,
$$  

故质点所能走过的最远距离为  

$$
\begin{array}{l}{\displaystyle s=\int_{0}^{+\infty}\frac{\mathrm{d}t}{\left(1+t^{2}\right)\left(1+t^{\prime}\right)}\,{=}\int_{0}^{+\infty}\frac{t^{\prime}\,\mathrm{d}t}{\left(1+t^{2}\right)\left(1+t^{\prime}\right)}\,}\\ {\displaystyle\;\;\;{=}\frac{1}{2}\left[\int_{0}^{+\infty}\frac{\mathrm{d}t}{\left(1+t^{\prime}\right)\left(1+t^{\prime}\right)}+\int_{0}^{+\infty}\frac{t^{\prime}\,\mathrm{d}t}{\left(1+t^{2}\right)\left(1+t^{\prime}\right)}\right]}\\ {\displaystyle\;\;\;{=}\frac{1}{2}\!\int_{0}^{+\infty}\frac{\mathrm{d}t}{1+t^{2}}\,{=}\frac{1}{2}\arctan\,t\left|_{0}^{+\infty}\right.}\\ {\displaystyle\;\;\;\;{=}\frac{\pi}{4}(\mathrm{m}).}\end{array}
$$  

# 2.变力沿直线做功  

设方向沿 $_{x}$ 轴正向的力函数为 $F\left(x\right)\left(a\leqslant x\leqslant b\right)$ ，则物体沿 $_{x}$ 轴从点 $^a$ 移动到点 $^b$ 时，变力 $F(x)$ 所做的功（见图12-1）为  

$$
W=\biggr\int_{\,a}^{b}F\left(\,x\,\right)\mathrm{d}x\,,
$$  

功的元素 $\mathrm{d}W=F\left(\boldsymbol{x}\right)\mathrm{d}\boldsymbol{x}$  

注】常考抽水做功.  

如图12-2所示，将容器中的水全部抽出所做的功为  

$$
W=\rho g\int_{a}^{b}\!x A\,(x\,)\,\mathrm{d}x\,,
$$  

其中 $\rho$ 为水的密度， $_{g}$ 为重力加速度.  

功的元素 $\mathrm{d}W=\rho g x A\left(\boldsymbol{x}\,\right)\mathrm{d}\boldsymbol{x}$ 为位于 $_{x}$ 处厚度为 $\mathtt{d}x$ ，水平截面面积为 $A\left(x\right)$ 的一层水被抽出（路程为 $_{x}$ ）所做的功  

求解这类问题的关键是确定 $_{x}$ 处的水平截面面积 $A\left(x\right)$ ，其余的量都是固定的。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/7c179438e31da50fba605ab1b5c4f66aa65fd535aa05158637a991f11bc24462.jpg)  
图12-1  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/8cd420c7c7c1192edfb0822d6b124e9850c7322a3ddc127ee6f9302569d87330.jpg)  
图12-2  

例 12. 2设曲线 $L:y=$  $x^{2}\left(0\leqslant x\leqslant{\sqrt{\frac{\pi}{4}}}\,\right).$  

（1）求直线 $y\!=\!1$ ，曲线 $L$ 以及 $_y$ 轴围成的平面图形绕 $_y$ 轴旋转一周所得到的旋转体体积 $V$ （2）记曲线 $L$ 绕 $_y$ 轴旋转一周所得到的旋转曲面为 $S$ ，该旋转曲面作为容器盛满水（水的质量密度（单位体积水的重力）等于1),如果将其中的水抽完,求外力做功W.  
# 比亨高等数学18讲  

[解]（1） 如图 12-3 所示,由 $_y=$ tan $x^{2}\left(0\leqslant x\leqslant{\sqrt{\frac{\pi}{4}}}\right)$ ,得到  

$$
x=\sqrt{\arctan\,y\,}\,(0\leqslant y\leqslant1)\,,
$$  

于是  

$$
\begin{array}{l}{{V=\pi\bigg\l\l_{0}^{\uparrow1}\arctan\,y\,\mathrm{d}y=\pi\,y\arctan\,y\biggm\rvert_{\mathrm{~0~}}^{\mathrm{~l~}}-\pi\bigg\l\l_{0}^{\uparrow1}\frac{y}{1+y^{2}}\mathrm{d}y}}\\ {{\mathrm{~}}}\\ {{=\frac{\pi^{2}}{4}-\frac{\pi}{2}\mathrm{ln}(1+y^{2})\Bigm\rvert_{\mathrm{~0~}}^{\mathrm{~1~}}=\frac{\pi^{2}}{4}-\frac{\pi}{2}\mathrm{ln~}2.}}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c4957e0488db1d85388e59ab32b403cf1470e3243cffbf628a4deeede4e0ca79.jpg)  
图12-3  

（2）用微元法. $\mathrm{d}W=\pi x^{2}\,\mathrm{d}y\,\bullet\,(1-y\,)=\pi$ · arctan $y\,{\mathsf{d}}y\,\cdot\,(\,1-y\,)$ ,于是  

$$
W=\pi\!\!\int_{0}^{1}(1-y\,)\arctan\,y\,\mathrm{d}y={\frac{\pi^{2}}{4}}-{\frac{\pi}{2}}\mathrm{ln~}2-\pi\!\!\int_{0}^{1}\!{y\arctan}
$$  

其中  

$$
\begin{array}{r l}&{\displaystyle\int_{0}^{1}y\arctan\,y\,\mathrm{d}y=\frac{y^{2}}{2}\arctan\,y\,\left\vert\mathbf{\eta}_{0}^{1}-\frac{1}{2}\right\vert_{\mathbf{\eta}_{0}}^{1}\frac{y^{2}}{1+y^{2}}\mathrm{d}y}\\ &{\quad\quad\quad\quad\quad\quad\quad=\frac{\pi}{8}-\frac{1}{2}\!\int_{0}^{1}\left(1-\frac{1}{1+y^{2}}\right)\mathrm{d}y}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad=\frac{\pi}{8}-\frac{1}{2}(y-\arctan\,y)\,\Big\vert_{\mathbf{\eta}_{0}}^{1}=\frac{\pi}{4}-\frac{1}{2}.}\end{array}
$$  

将上式计算结果代人 $(\,\star\,)$ 式，得 $W\!=\!\frac{\pi}{2}(1-\ln\,2)$  

【注  由 $y=\tan\,x^{\,2}$ 知，当 $x\geqslant0$ 时， $y^{\prime}=\sec^{2}x^{2}\cdot2x\geqslant0$ ,于是当 $0\leqslant x\leqslant{\sqrt{\frac{\pi}{4}}}$ 时 $_y$ 为单调增加函数， $y^{\prime\prime}\,{=}\,2\sec\,x^{\,2}$ · sec $x^{\,2}$ · tan $x^{\,2}\cdot2x\cdot2x+2s{\mathrm{ec}}^{2}x^{\,2}>0$ ，说明当 $0\leqslant x\leqslant{\sqrt{\frac{\pi}{4}}}$ 时 $_y$ 的图形是凹的.这些求导过程虽不一定要写在答卷上，但作为考生，一定要验算清楚才能画出正确的草图，保证做题的正确性.  

# 3.静水压力  

垂直浸没在水中的平板ABCD（见图12-4）的一侧受到的水压力为 $P\!=\!\!\rho g\!\int_{\,a}^{b}\!x\big[f(x)\!-\!h\left(x\,\right)\big]\mathrm{d}x$ ,其中 $\rho$ 为水的密度， $_{g}$ 为重力加速度.  

压力元素 $\mathrm{d}P=\rho g x\big[f(x)-h\left(x\right)\big]\mathrm{d}x$ ,即图中矩形条所受到的压力. $_x$ 表示水深， $f\!\left(\boldsymbol{x}\right)-h\left(\boldsymbol{x}\right)$ 是矩形条的宽度， ${\mathrm{d}}x$ 是矩形条的高度.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/7926550e35235bffb9a7a3796af622d61a7a9894377abcd8ebf5de5f3d73847d.jpg)  
图12-4  

【注】水压力问题的特点:压强随水的深度的改变而改变,求解这类问题的关键是确定水深 $_{x}$ 处的平板的宽度 $f(x)-h\left(x\right)$  
例 12. 3斜边长为 $2\alpha$ 的等腰直角三角形平板铅直地沉没在水中,且斜边与水面相齐.记重力加速度为 $_{g}$ ,水的密度为 $\rho$ ，则该平板一侧所受的水压力为  

【解】应填 $\frac{1}{3}a^{3}\rho g$  

如图12-5所示，该平板一侧所受的水压力为  

$$
P=\!\int_{0}^{a}2\rho g\,(a-y\,)y\,\mathrm{d}y=2\rho g\!\int_{0}^{a}(a y-y^{\,2}\,)\mathrm{d}y=2\rho g\!\left({\frac{a^{\,3}}{2}}-{\frac{a^{\,3}}{3}}\right)\!={\frac{1}{3}}a^{\,3}\rho g.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c4044f7af4b5e9bcd54e151a35a33dd95621ed1ae241a6eb25a059edba4fe7b4.jpg)  
图12-5  

#  $^{4,}$ 细杆质心  

设直线段上的线密度为 $\rho(x)$ 的细直杆（见图12-6）,则其质心为  

$$
\!\!\!\!\!\!\!\!\!\!\!\!\!\overline{{x}}=\!\frac{\displaystyle{\int_{a}^{b}}x\rho(x)\,\mathrm{d}x}{\displaystyle{\int_{a}^{b}}\rho(x)\,\mathrm{d}x}.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/cb4fd1d9d9489cbeab797a5ab9f7c0288103c4645f818540972def7f8576fde5.jpg)  
图12-6  

例 12. 4设 $L$ 是位于 $_{x}$ 轴的区间 $\left[-{\frac{\pi}{2}},{\frac{\pi}{2}}\right]$ 上的质杆，已知 $L$ 上任一点 $x\in\left[-{\frac{\pi}{2}},{\frac{\pi}{2}}\right]$ 的线密度为 $\rho(x)\,{=}\,1+\sin\,x$ ,则该质杆的质心坐标 ${\overline{{x}}}=$  

【解】应填 $\frac{2}{\pi}$  

$$
{\cfrac{-}{x}}={\cfrac{\int_{-{\frac{\pi}{2}}}^{\frac{\pi}{2}}x\rho\left(x\,\right)\mathrm{d}x}{\int_{-{\frac{\pi}{2}}}^{\frac{\pi}{2}}\rho\left(x\,\right)\mathrm{d}x}}={\cfrac{\int_{-{\frac{\pi}{2}}}^{\frac{\pi}{2}}x\left(1+\sin\,x\,\right)\mathrm{d}x}{\int_{-{\frac{\pi}{2}}}^{\frac{\pi}{2}}\left(1+\sin\,x\,\right)\mathrm{d}x}}={\cfrac{2}{\pi}}.
$$  

$$
\overline{{y}}=\!\frac{1}{b-a}\!\int_{a}^{b}\!y\left(\chi\right)\!\,\mathrm{d}x\,.
$$  
# 比宁高等数学18讲  

例12.5设某公司在 $t$ 时刻的资产为 $f(t)$ ,从0时刻到 $t$ 时刻的平均资产等于 $\frac{f(t)}{t}-t$ 假设 $f(t)$ 连续且 $f(0)=0$ ，则 $f(t)=$  

【解】应填 $-\,2(1+t\,)+2\mathbf{e}^{t}$  

依题设，有 $\frac{f(t)}{t}-t=\frac{1}{t}\!\int_{0}^{t}f(t)\,\mathrm{d}t$ ,即 $f(t)-t^{2}=\!\!\int_{0}^{t}f(t)\,\mathrm{d}t$ ,等式两边求导，得  

$$
f^{\prime}(t)-2t=f(t)\,,
$$  

即  

$$
f^{\prime}(t)-f(t)=2t\,,
$$  

则  

$$
f(t)=\mathrm{e}^{\cdot\Big\lceil(-1)\,\mathsf{d}t}\left[\!\int\!2t\,\mathrm{e}^{\int(-1)\,\mathsf{d}t}\,\mathrm{d}t+C\right]\!=\mathrm{e}^{t}\left(\!\int\!2t\,\star\mathrm{e}^{-t}\,\mathrm{d}t+C\right)
$$  

$$
=\mathrm{e}^{\prime}\Bigl[-2(1+t)\,\mathrm{e}^{-t}+C\Bigr]=-2(1+t)+C\mathrm{e}^{\prime}.
$$  

由 $f(0)=-2+C=0$ ，故 $C=2$ ,得  

$$
f(t)=-\,2(1+t\,)+2\mathrm{e}^{t}.
$$  

# 2.求总量  

$$
Q(t)=Q(t_{0})+\int_{t_{0}}^{t}Q^{\prime}(u\,)\,\mathrm{d}u\,,t>t_{0}.
$$  

例 12. 6已知生产某产品的边际成本为 $C^{\prime}(x)\,{=}\,x^{2}\,{-}\,4x\,+6$ （单位：元/件），边际收益为 $R^{\prime}(x)\!=\!105\!-\!2x$ ，其中 $_{x}$ 为产量.已知没有产品时没有收益，且固定成本为100元.若生产的产品都会售出，求产量为多少时，利润最大，并求出最大利润.  

【解】利润函数为 $L\left(x\,\right){=}R\left(x\,\right){-}\,C(x\,).$ 又  

$$
L^{\prime}(x)=\!R^{\prime}(x)-C^{\prime}(x)\,{=}\,105-2x-(x^{\,2}-4x+6)
$$  

$$
=(11-x\,)(9+x\,)\,,
$$  

令 $L^{\prime}(x)=0$ ，得 $x=11$ （因 $x>0$ ，故 $x=-9$ 舍去），且有  

$$
L^{\prime\prime}(x\,)=2-2x\,,L^{\prime\prime}(11)=-\,20<0\,,
$$  

故 $x=11$ 为 $L\left(x\right)$ 唯一的极大值点，即为最大值点，于是当产量为11件时，利润最大.由题设， $R(0)=0\,,C(0)=100$ ，于是  

$$
\begin{array}{l}{{\cal L\textsubscript{m a x}=\displaystyle{\cal L}\left(11\right)={\cal L}\left(0\right)+\displaystyle{\int_{0}^{11}}{\cal L}^{\prime}(x)\mathsf{d}x=\displaystyle{\cal R}\left(0\right)-{\cal C}(0)+\displaystyle{\int_{0}^{11}}\big[{\cal R}^{\prime}(x)-{\cal C}^{\prime}(x)\big]\mathsf{d}x}}\\ {{\phantom{\displaystyle{\cal L\textsubscript{m a x}=\displaystyle{\cal L}\left(11\right)}}=-100+\displaystyle{\int_{0}^{11}}\left(99+2x-x^{2}\right)\mathsf{d}x}}\\ {{\phantom{\displaystyle{\cal L\textsubscript{m a x}=\displaystyle{\cal L}\left(0\right)}}=-100+\displaystyle{\left(99x+x^{2}-\frac{x^{3}}{3}\right)}\,\bigg\vert\,_{0}^{11}=\frac{1999}{3}(\mp).}}\end{array}
$$  
# 第13讲R多元函数微分学  

# 知识结构  

# 极限  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/df837118912a446af424b58b3ef824007ad34876e92e0d4074456d54f734f977.jpg)  

# 1.极限  

设函数 $f(x\,,y)$ 在区域 $D$ 上有定义， $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0})\in D$ 或为 $D$ 的边界上的一点.如果对于任意给定的 $\varepsilon>0$ ，总存在 $\delta>0$ ，当点 $P(x,y)\in D$ ,且满足 $0<\mid P P_{0}\mid=\sqrt{(x-x_{0})^{2}+(y-y_{0})^{2}}<$  $\delta$ 时，恒有  

$$
\mid f(x\;,y\;)-A\;\mid<\epsilon\;,
$$  

则称常数A 为 $(x\,,y\,)\rightarrow(x\,_{0}\,,y\,_{0})$ 时 $f(x\,,y\,)$ 的极限，记作  

$$
\operatorname*{lim}_{(x,y)\rightarrow(x_{0},y_{0})}f(x\,,y)=A\stackrel{\overrightarrow{\mathbf{g}}\natural}{\longrightarrow}\operatorname*{lim}_{x\rightarrow x_{0}}f(x\,,y)=A\,,
$$  
# 比亨高等数学18涉  

也常记作  

$$
\operatorname*{lim}_{P\rightarrow P_{0}}f(P)=A.
$$  

【注](1)一元极限中 $x\rightarrow x_{\circ}$ 有且仅有两种方式 $(x\rightarrow x_{0}^{-}$ 和 $x\rightarrow x_{0}^{+}$ ),二重极限中 $(x\,,y\,)\to$   
 $(x_{0},y_{0})$ 一般有无穷多种方式。 $\operatorname*{lim}_{(x,y)\to(x_{0},y_{0})}f(x,y)$ 的值不相等或某一路径使极限  
 $\operatorname*{lim}_{(x,y)\to(x_{0},y_{0})}f(x,y)$ 的值不存在，都说明 $\operatorname*{lim}_{(x,y)\to(x_{0},y_{0})}f(x,y)$ 不存在.  
(3)除洛必达法则和单调有界准则外,可照搬一元函数求极限的方法来求二重极限,二重极  

限保持了一元极限的各种性质,如唯一性、局部有界性、局部保号性、运算规则及脱帽法 $\operatorname*{lim}_{(x,y)\rightarrow(x_{0},y_{0})}f(x\,,y)=A\leftrightarrow f(x\,,y)=A+\alpha$ ，其中当 $(x\,,y)\rightarrow(x\,_{0}\,,y_{0})$ 时， $\pmb{\alpha}$ 是无穷小量。  

# 2.连续  

如果 $\operatorname*{lim}_{x\to x_{0}}f(x\,,y)\!=\!f(x\,,\cdot y_{0}\,)$ ,则称函数 $f(x\,,y\,)$ 在点 $(x_{\circ},y_{\circ})$ 处连续.如果 $f(x\,,y\,)$ 在区域$D$ 上每一点都连续,则称 $f(x\,,y\,)$ 在区域 $D$ 上连续.  

# 3.偏导数  

（1）定义.设函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 在点 $(x_{\circ},y_{\circ})$ 处的某邻域内有定义,如果极限  

$$
\operatorname*{lim}_{\Delta x\to0}{\frac{f(x_{\,0}+\Delta x\,,y_{\,0})-f(x_{\,0}\,,y_{\,0})}{\Delta x}}
$$  

存在,则称此极限为函数 $z=f(x\,,y\,)$ 在点 $(x_{\mathrm{~o~}},y_{\mathrm{~o~}})$ 处对 $_{x}$ 的偏导数，记作  

$$
\left.\frac{\partial z}{\partial x}\right|_{x=x_{0}},\left.\frac{\partial f}{\partial x}\right|_{x=x_{0}},z_{x}^{\prime}\left|\mathbf{\eta}_{x}=\mathbf{\eta}_{x_{0}}\right|_{y=\mathbf{\eta}_{0}}\frac{\partial\hat{\mathbf{y}}}{\partial x}\ f_{x}^{\prime}\left(x_{0},y_{0}\right),
$$  

即  

$$
f_{x}^{\prime}(x_{0},y_{0})=\operatorname*{lim}_{\Delta x\to0}\frac{f(x_{0}+\Delta x\,,y_{0})-f(x_{0}\,,y_{0})}{\Delta x}.
$$  

类似地,函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 在点 $(x_{\circ},y_{\circ})$ 处对 $_{\boldsymbol{y}}$ 的偏导数定义为  

$$
f_{\mathfrak{s}}^{\prime}(x_{\mathfrak{s}},y_{\mathfrak{s}})=\!\!\operatorname*{lim}_{\Delta\mathfrak{s}\to0}\frac{f(x_{\mathfrak{s}},y_{\mathfrak{s}}+\Delta{\mathfrak{y}})-f(x_{\mathfrak{s}},y_{\mathfrak{s}})}{\Delta{\mathfrak{y}}}.
$$  

(2）如果 $z=f(\,x\,,y\,)$ 在区域 $D$ 上的每一点 $(x\,,\,y\,)$ 处都有偏导数，一般来说,它们仍是 $_x$ ， $_y$ 的面效,则称为 $f(x\,,y\,)$ 的制等面数,简除谢导数,记作 $\langle\frac{\partial z}{\partial x},\frac{\partial f}{\partial x},f_{x}^{\prime}\left(x\,,y\right),\frac{\partial z}{\partial y},\frac{\partial f}{\partial y},f_{y}^{\prime}\left(x\,,y\right)\rangle,$  

（3）偏导数的几何意义.  

设有二元函数 $z\,=\,f(x\,,y\,)$ ，且 $z_{0}=f(x_{\textrm{0}},y_{0})$ ，则 $f_{x}^{\prime}(x_{0},y_{0})$ 在几何上表示曲线 $\left\{z=f(x\wedge y)\right.$ 在点 $(x_{\circ},y_{\circ},z_{\circ})$ 处的切线对 $_{x}$ 轴的斜率，同理， $f_{\mathrm{~y~}}^{\prime}(x_{\mathrm{~0~}},y_{\mathrm{~0~}})$ 在几何上表示曲线  
$\left\{z=f(x\,,y\,)\,,\right.$ 在点 $(x_{\mathrm{~0~}},y_{\mathrm{~0~}},z_{\mathrm{~0~}})$ 处的切线对 $_y$ 轴的斜率.  

（4）高阶偏导数.  

如果二元函数 $z\!=\!f(x\,,\!y\,)$ 的偏导数 $f_{x}^{\prime}\left(x,y\right)$ 和 $f_{y}^{\prime}\left(x\,,y\right)$ 仍然具有偏导数,则它们的偏导数称为 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 的二阶偏导数，记作  

$$
\frac{\partial^{2}\,z}{{\partial x}^{\,z}}=\frac{\partial}{{\partial x}}\!\left(\frac{{\partial z}}{{\partial x}}\right)\!=f_{{x x}}^{\prime\prime}\left(x\;,y\right)\!=\!z_{{x x}}^{\prime\prime}\;,
$$  

$$
\frac{\partial^{2}z}{\partial x\,\partial y}=\frac{\partial}{\partial y}\Bigl(\frac{\partial z}{\partial x}\Bigr)=f_{x y}^{\prime\prime}\,(x\,\,,y\,)=z_{x y}^{\prime\prime}\,,
$$  

$$
\frac{\partial^{2}\,z}{\partial y^{\,z}}=\frac{\partial}{\partial y}\Big(\frac{\partial z}{\partial y}\Big)=f_{\,y y}^{\prime\prime}\left(\,x\,,y\,\right)=z_{\,y y}^{\prime\prime}\,,
$$  

$$
\frac{\partial^{2}z}{\partial y\partial x}\!=\!\frac{\partial}{\partial x}\!\left(\frac{\partial z}{\partial y}\right)\!=\!f_{y x}^{\prime\prime}\left(x\;,y\right)\!=\!z_{y x}^{\prime\prime}\;,
$$  

其中称 $\frac{\partial^{2}z}{\partial x\,\partial y}$ 与 $\frac{\partial^{2}z}{\partial y\partial x}$ 为二阶混合偏导数.类似地可以定义 $n(n\geqslant3)$ 阶偏导数.  

（5）如果函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 的两个二阶混合偏导数 $\frac{\partial^{2}z}{\partial x\,\partial y}$ 及 $\frac{\partial^{2}z}{\partial y\partial x}$ 都在区域 $D$ 内连续，则在区域 $D$ 内 $\frac{\partial^{2}z}{\partial x\,\partial y}=\frac{\partial^{2}z}{\partial y\,\partial x}$ ,即二阶混合偏导数在连续的条件下与求导的次序无关.  

# 4.全微分  

(1)定义.  

设二元函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 在点 $(\_x\,,\_y)$ 的某邻域内有定义,若 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 的全增量 $\Delta z=$  $f(x+\Delta x\,,y+\Delta y\,)-f(x\,,y\,)$ 可以表示为 $\Delta z=A\,\Delta x+B\,\Delta y+o\,(\rho)$ ,其中 $A\,,B$ 不依赖于 $\Delta x$ ， $\Delta y$ ，而仅与 $x\cdot y$ 有关， $\rho\!=\!\sqrt{(\Delta x\,)^{2}+(\Delta y\,)^{2}}$ ,则称函数 $z=f(\,x\,,y\,)$ 在点 $(x\,,y\,)$ 处可微， $A\Delta x+$  $B\Delta y$ 称为函数 $z=f(x\,,y\,)$ 在点 $(x\,,y\,)$ 处的全微分，记作 ${\tt d}z$ ,即 $\mathrm{d}z=A\,\Delta x+B\,\Delta y$  

（2）若函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 在点 $(x\,,y\,)$ 处可微，则必在点 $(x\,,y\,)$ 处连续.  

（3）可微的必要条件.  

如果函数 $z=f(\,x\,,y\,)$ 在点 $(x\,,y\,)$ 处可微,则该函数在点 $(x\,,y\,)$ 处的两个偏导数都存在,且  

$$
A=\frac{\partial z}{\partial x},B=\frac{\partial z}{\partial y}.
$$  

（4）可微的充分条件.  

如果函数 $z=f(x\,,y\,)$ 的偏导数 $\frac{\partial z}{\partial x},\frac{\partial z}{\partial y}$ 在点 $(x\,,y\,)$ 处连续，则函数在该点可微.  

（5）全微分的形式不变性，  

设 $\boldsymbol{z}=\boldsymbol{f}(\boldsymbol{u}\,,v\,)\,,\boldsymbol{u}=\boldsymbol{u}\left(\boldsymbol{x}\,,y\,\right),v=v\left(\boldsymbol{x}\,,y\,\right)$ ，如果 $f(u\,,v\,)\,,u\,(x\,\,,y\,)\,,v(x\,\,,y\,)$ 分别有连续偏导数，则复合函数 $\boldsymbol{z}=f(\boldsymbol{u}\,,\boldsymbol{v})$ 在 $(x\,,y\,)$ 处的全微分仍可表示为  

$$
\mathrm{d}z=\frac{\partial z}{\partial u}\mathrm{d}u+\frac{\partial z}{\partial v}\mathrm{d}v\,,
$$  
# 比亨高等数学18讲  

即无论 $u\cdot v$ 是自变量还是中间变量，上式总成立.  

【注】 判断函数 $z=f(x\,,y\,)$ 在点 $(x_{0},y_{0})$ 处是否可微，步骤如下：  

$\textcircled{1}$ 写出全增量 $\Delta z=f(x_{\circ}+\Delta x\,,y_{\circ}+\Delta y\,)-f(x_{\circ}\,,y_{\circ})$   
 $\circledcirc$ 写出线性增量 $A\,\Delta x+B\,\Delta y$ ,其中 $A=f_{x}^{\prime}(x_{0},y_{0})\,,B=f_{y}^{\prime}(x_{0},y_{0})\,,$   
 $\textcircled{3}$ 作极限 $\operatorname*{lim}_{\Delta x\to0}{\frac{\Delta z-(A\,\Delta x+B\,\Delta y)}{\sqrt{(\Delta x\,)^{2}+(\Delta y\,)^{2}}}}$ ,若该极限等于 0,则 $z=f(x\,,y)$ 在点 $(x_{0},y_{0})$ 处可微，否则，就不可微.  

# 5.偏导数连续  

对于 $z\!=\!f(x\,,\!y\,)$ ,讨论其在某特殊点 $(x_{0},y_{0})$ （比如二元分段函数的分段点）处偏导数是否连续，是考研的重点.  

[注) (1) 判断函数 $z=f(x\,,y\,)$ 在特殊点 $(x_{0},y_{0})$ 处的偏导数是否连续,步骤如下:  

$\textcircled{1}$ 用定义法求 $f_{x}^{\prime}(x_{0},y_{0}),f_{y}^{\prime}(x_{0},y_{0})$ ； $\circledcirc$ 用公式法求 $f_{x}^{\prime}(x\,,y),f_{y}^{\prime}(x\,,y)$ ； $\textcircled{3}$ 计算 $\operatorname*{lim}_{x\to x_{0}}f_{x}^{\prime}\left(x\;,y\right),\operatorname*{lim}_{x\to x_{0}}f_{y}^{\prime}\left(x\;,y\right),$ 看 $\operatorname*{lim}_{\stackrel{x\to x_{0}}{\mathrm{y}\to\mathrm{y}_{0}}}f_{x}^{\prime}\left(x\,,y\right)=f_{x}^{\prime}\left(x\,_{0}\,,y_{0}\right),\operatorname*{lim}_{\stackrel{x\to x_{0}}{\mathrm{y}\to\mathrm{y}_{0}}}f_{y}^{\prime}\left(x\,,y\right){=}f_{y}^{\prime}\left(x\,_{0}\,,y_{0}\right)$ 是否成立,若成立,则 $z=f(x\,,y\,)$ 在点 $(x_{0},y_{0})$ 处的偏导数是连续的。  

(2)一元函数和多元函数在极限存在、连续、可导、可微的相互关系上,有相同之处,更有相异之处，如图13-1所示（记号 $\rightarrow$ 表示可推出， $+$ 表示不一定推出).  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/7172bec9d534a65436d6cf7c6eb0a0d273d11b3d50840b460fe7da3390ea9cc8.jpg)  
图13-1  

$f(x\,,y)=\!\left\{\!\!{\frac{{\sqrt[{3}]{1+x y}}-1}{{\sqrt{x^{2}+y^{2}}}}}\!\!\right.$ (x,y)≠(0,0),   
例 13. 1函数在点(0,0)处($(\boldsymbol{x}\,,\boldsymbol{y}\,)=(0\,,0)$   
（A）不连续（B）连续但偏导数不存在  

【解】应选(C).  

因为 $\left|{\frac{x y}{\sqrt{x^{2}+y^{2}}}}\right|\leqslant{\frac{{\sqrt{x^{2}+y^{2}}}}{2}}$ 且 $\operatorname*{lim}_{x\rightarrow0}{\frac{\sqrt{x^{2}+y^{2}}}{2}}=0$ ，所以  
$$
\operatorname*{lim}_{\stackrel{x\to0}{y\to0}}f(x\,,y)=\operatorname*{lim}_{\stackrel{x\to0}{y\to0}}{\frac{\sqrt[{3}]{1+x y}-1}{\sqrt{x^{2}+y^{2}}}}=\operatorname*{lim}_{\stackrel{x\to0}{y\to0}}{\frac{x y}{3{\sqrt{x^{2}+y^{2}}}}}=0=f(0,0)\,,
$$  

从而 $f(x\,,y\,)$ 在点（0,0）处连续.因为  

$$
\operatorname*{lim}_{x\to0}\frac{f(x\,,0)-f(0,0)}{x-0}=\!\operatorname*{lim}_{x\to0}\frac{0}{x}=0\,,\operatorname*{lim}_{y\to0}\frac{f(0,y)-f(0,0)}{y-0}\,{\overset{\,\mathrm{dim}\,}{\underset{y\to0}{=}}}\,=\!0\,,
$$  

所以 $f(x\,,y\,)$ 在点（0,0）处存在偏导数,且 $f_{{\,\,x}}^{\prime}\left(0,0\right)=f_{{\,\,y}}^{\prime}\left(0,0\right)=0.$ 因为  

$$
\begin{array}{r l}&{\underset{x\rightarrow0}{\operatorname*{lim}}\frac{f(x\,,y)-f(0,0)-\big[f_{x}^{\prime}(0,0)(x-0)+f_{y}^{\prime}(0,0)(y-0)\big]}{\sqrt{x^{2}+y^{2}}}}\\ &{=\underset{x\rightarrow0}{\operatorname*{lim}}\frac{\sqrt{1+x y}-1}{x^{2}+y^{2}}\frac{\displaystyle\mathrm{lim}}{\underset{y\rightarrow0}{\operatorname*{sup}}\frac{x y}{3(x^{2}+y^{2})}},}\end{array}
$$  

而 $\operatorname*{lim}_{x\to0\atop y=x}{\frac{x y}{3(x^{2}+y^{2})}}\,{=}\operatorname*{lim}_{x\to0}{\frac{x^{2}}{3(x^{2}+x^{2})}}\,{=}\,{\frac{1}{6}}\neq0$ ，所以  

$$
\operatorname*{lim}_{\stackrel{x\to0}{y\to0}}\frac{f(x\,,y)-f(0,0)-\left[f_{x}^{\prime}(0,0)(x-0)+f_{y}^{\prime}(0,0)(y-0)\right]}{\sqrt{x^{2}+y^{2}}}\ne0\,,
$$  

从而函数 $f(x\,,y\,)$ 在点（0,0）处不可微.  

故选(C).  

例13. 2设函数 $f(x\,,y\,)=\!\int_{0}^{x y}\mathrm{e}^{x t^{2}}\,\mathrm{d}t$ ，则 $\left.{\frac{\partial^{2}f}{\partial x\,\partial y}}\right|_{(1,1)}=\underline{{\phantom{\left({1,1}\right)}}}.$  

【解】应填 4e.  

法一  

$$
f_{{\,\,y}}^{\prime}(x\,,y)=x\,\mathrm{e}^{x^{3}y^{2}}\,,f_{{\,\,y}}^{\prime}(x\,,1)=x\,\mathrm{e}^{x^{3}}\,;
$$  

$$
f_{{\mathfrak{s}}x}^{\prime\prime}\left(x\,,1\right)=3x^{\,3}\,{\mathrm{e}}^{x^{\,3}}+{\mathrm{e}}^{x^{\,3}}\,,f_{{\mathfrak{s}}x}^{\prime\prime}\left(1,1\right)=4{\mathfrak{e}}.
$$  

由于 $f(x\,,y\,)$ 的二阶混合偏导数在点（1,1）处是相等的,因此 $f_{x y}^{\prime\prime}\left(1,1\right)=4\mathbf{e}.$  

法二当 $x>0$ 时 $,f(x\,,y)=\!\!\int_{0}^{x y}\!\,{\mathrm{e}}^{x t^{2}}\,{\mathrm{d}}t\,\,{\frac{{\frac{u}{\sqrt{x}}}=t}{u={\sqrt{x}}\,t}}\int_{0}^{x^{\frac{3}{2}}y}{\mathrm{e}}^{u^{2}}\,{\frac{1}{\sqrt{x}}}{\mathrm{d}}u={\frac{1}{\sqrt{x}}}{\int_{0}^{x^{\frac{3}{2}}y}}{\mathrm{e}}^{u^{2}}\,{\mathrm{d}}u\,.$ 得  

$$
f_{x}^{\prime}\left(x\,,y\right)=-\frac{1}{2}x^{-\frac{3}{2}}{\int_{0}^{x^{\frac{3}{2}}y}{\mathrm{e}}^{u^{2}}\,\mathrm{d}u}+\frac{1}{\sqrt{x}}\cdot{\mathrm{e}}^{x^{3}y^{2}}\,\cdot\,\frac{3}{2}x^{\frac{1}{2}}y\,,
$$  

故当 $x=1$ 时，有 $f_{x}^{\prime}\left(1,y\right)=-\,\frac{1}{2}\!\!\int_{0}^{y}\!\,{\mathrm{e}}^{u^{2}}\,\mathrm{d}u+\frac{3}{2}{\mathrm{e}}^{y^{2}}\,\cdot\,y.$ 则  

$$
f_{x y}^{\prime\prime}(1,y)=-{\frac{1}{2}}{\bf e}^{y^{2}}+{\frac{3}{2}}\cdot{\bf e}^{y^{2}}\cdot2y\cdot y+{\frac{3}{2}}{\bf e}^{y^{2}}\cdot1,
$$  

$$
f_{x y}^{\prime\prime}\left(1,1\right)=-\,\frac{1}{2}{\tt e}+3{\tt e}+\frac{3}{2}{\tt e}=4{\tt e}.
$$  

例 13.3  

设$z_{1}=\mid x y\mid,z_{2}=\left\{\frac{x\mid y\mid}{\sqrt{x^{\,2}+y^{\,2}}},(x\,,y)\not=(0,0)\,,\right.$ 则( ).  

$(\mathbf{A})_{\mathcal{Z}_{1}}$ 在点（0,0）处不可微， $z_{2}$ 在点（0,0）处不可微  
# 张宁高等数学18讲  

$(\mathrm{~B~})\,z_{\mathrm{~l~}}$ 在点（0,0）处不可微， $z_{2}$ 在点（0,0）处可微 $(\mathbf{C})\boldsymbol{z}_{1}$ 在点（0,0）处可微， $\scriptstyle z_{2}$ 在点（0,0）处不可微 $(\mathrm{D})\boldsymbol{z}_{1}$ 在点（0,0）处可微， $\boldsymbol{z}_{2}$ 在点（0,0）处可微  

【解】应选(C).  

$$
\begin{array}{l}{\displaystyle\frac{\partial z_{1}}{\partial x}\Big|_{(0,0)}=\operatorname*{lim}_{x\to0}\frac{z_{1}(x\,,0)-z_{1}(0\,,0)}{x-0}=0\,,}\\ {\displaystyle\frac{\partial z_{1}}{\partial y}\Big|_{(0,0)}=\operatorname*{lim}_{y\to0}\frac{z_{1}(0\,,y\,)-z_{1}(0\,,0)}{y-0}=0\,,}\end{array}
$$  

$$
\frac{z_{1}(x\,,y)-z_{1}(0\,,0)-\frac{\partial z_{1}}{\partial x}\Big|_{\stackrel{(0,0)}{\sqrt{\stackrel{()}{\scriptstyle{\it\it~\cdot~\cdot~}}}}}\star x-\frac{\partial z_{1}}{\partial y}\Big|_{\stackrel{(0,0)}{\scriptstyle{\uparrow\,,0)}}}\bullet y}{\sqrt{x^{2}+y^{2}}}=\frac{\mid x y\mid}{\sqrt{x^{2}+y^{2}}}.
$$  

$$
0\leqslant\operatorname*{lim}_{x\to0\atop y\to0}{\frac{\mid x y\mid}{{\sqrt{x^{\,2}+y^{\,2}}}}}\leqslant\operatorname*{lim}_{x\to0\atop y\to0}{\frac{\textstyle{\frac{1}{2}}(x^{\,2}+y^{\,2})}{{\sqrt{x^{\,2}+y^{\,2}}}}}=0\,,
$$  

故$z_{1}$ 在点（0,0）处可微.  

$$
\begin{array}{l}{\displaystyle\frac{\partial z_{2}}{\partial x}\Big|_{(0,0)}=\operatorname*{lim}_{x\to0}\frac{z_{2}(x\,,0)-z_{2}(0\,,0)}{x-0}\!=\!0\,,}\\ {\displaystyle\frac{\partial z_{2}}{\partial y}\Big|_{(0,0)}=\operatorname*{lim}_{y\to0}\frac{z_{2}(0\,,y\,)-z_{2}(0\,,0)}{y-0}=0\,,}\end{array}
$$  

$$
\frac{z_{2}\left(x\,,y\right)-z_{2}\left(0,0\right)-\frac{\partial z_{2}}{\partial x}\Big|_{\stackrel{(0,0)}{x^{2}}}\cdot x-\frac{\partial z_{2}}{\partial y}\Big|_{\stackrel{(0,0)}{\mathrm{(0,0)}}}\cdot y}{\sqrt{x^{2}+y^{2}}}\!=\!\frac{x\,|\,\ y\,\mid}{x^{2}+y^{2}}.
$$  

取$_y=x$ ，则  

$$
\operatorname*{lim}_{\stackrel{x\to0}{y=x}}\frac{x\mid y\mid}{x^{2}+y^{2}}=\!\!\operatorname*{lim}_{x\to0}\frac{x\mid x\mid}{2x^{2}},\operatorname*{lim}_{x\to0^{+}}\frac{x\mid x\mid}{2x^{2}}\!=\!\frac{1}{2},\operatorname*{lim}_{x\to0^{-}}\frac{x\mid x\mid}{2x^{2}}\!=\!-\frac{1}{2},
$$  

极限不存在，故 $z_{2}$ 在点（0，0）处不可微。  

# 复合函数求导法（链式求导规则）  

设 $z=z\left(u\,,v\,\right),u=u\left(x\,,y\,\right),v=v\left(x\,,y\,\right)$ ,写成复合结构图为  

$$
z\!<\!\!\!\!\underbrace{u\!\!\!\!\!\slash}_{\upsilon}\!\!\!\!\!\slash\!\!\!\!\!\!\times\!\!\!\!\!\!\!{x\!\!\!\!\!\!\slash}\!\!\!\!\!\!
$$  

于是  

$$
\frac{\partial z}{\partial x}=\frac{\partial z}{\partial u}\cdot\frac{\partial u}{\partial x}+\frac{\partial z}{\partial v}\cdot\frac{\partial v}{\partial x},
$$  

$$
\frac{\partial z}{\partial y}=\frac{\partial z}{\partial u}\cdot\frac{\partial u}{\partial y}+\frac{\partial z}{\partial v}\cdot\frac{\partial v}{\partial y}.
$$  

[注](1) 全导数:若 $z=\!z\left(u\,,\!v\,\right),u=\!u\left(x\,\right),v=\!v\left(x\,\right)$ ,即 $_z$ 最终只是 $_{x}$ 的函数，则 $\frac{\mathbf{d}{\boldsymbol{z}}}{\mathbf{d}{\boldsymbol{x}}}$ 叫全导数.写成复合结构图为  
$$
z<\quad\quad z\quad
$$  

于是  

$$
{\frac{\mathrm{d}z}{\mathrm{d}x}}={\frac{\partial z}{\partial u}}\cdot{\frac{\mathrm{d}u}{\mathrm{d}x}}+{\frac{\partial z}{\partial v}}\cdot{\frac{\mathrm{d}v}{\mathrm{d}x}}.
$$  

(2)无论 $_z$ 对哪个变量求导,也无论 $_z$ 已经求了几阶导,求导后的新函数仍然具有与原函数完全相同的复合结构.  

例 13. 4  

设 $z=f(x+y\,,x-y\,,x y)$ ,其中 $f$ 具有二阶连续偏导数,求 ${\tt d}z$ 与 $\frac{\partial^{2}z}{\partial x\,\partial y}$  

【解】由于  

$$
\frac{\partial z}{\partial x}=f_{\,1}^{\prime}\!+f_{\,2}^{\prime}\!+g f_{\,3}^{\prime}\,,\frac{\partial z}{\partial y}=f_{\,1}^{\prime}\!-f_{\,2}^{\prime}\!+x\,f_{\,3}^{\prime}\,,
$$  

因此  

$\mathrm{d}z=\frac{\partial z}{\partial x}\mathrm{d}x\,+\frac{\partial z}{\partial y}\mathrm{d}y=(f_{1}^{\prime}+f_{2}^{\prime}+y f_{3}^{\prime}\,)\mathrm{d}x\,+(f_{1}^{\prime}-f_{2}^{\prime}+x f_{3}^{\prime})\mathrm{d}y\,,$ $\begin{array}{c}{{:=f_{11}^{\prime\prime}\bullet1+f_{12}^{\prime\prime}\bullet(-1)+f_{13}^{\prime\prime}\bullet x+f_{21}^{\prime\prime}\bullet1+f_{22}^{\prime\prime}\bullet(-1)+f_{23}^{\prime\prime}\bullet x+f_{3}^{\prime}+}}\\ {{\mathrm{}}}\\ {{y\big[f_{31}^{\prime\prime}\bullet1+f_{32}^{\prime\prime}\bullet(-1)+f_{33}^{\prime\prime}\bullet x\big]}}\\ {{=f_{3}^{\prime}+f_{11}^{\prime\prime}-f_{22}^{\prime\prime}+x y f_{33}^{\prime\prime}+(x+y)f_{13}^{\prime\prime}+(x-y)f_{23}^{\prime\prime}.}}\end{array}$  

例 13. 5  

已知函数 $f(u\,,v)$ 具有二阶连续偏导数， $f(1,1)=2$ 是 $f(u\,,v)$ 的极值， $_z=$  $f[x+y\,,f(x\,,y)]$ ，求 $\left.\frac{\partial^{2}z}{\partial x\,\partial y}\,\right|_{(1,1)},$ 【解】 $\cfrac{\partial z}{\partial x}=f_{1}^{\prime}\big[x+y\,,f(x\,,y)\big]+f_{2}^{\prime}\big[x+y\,,f(x\,,y)\big]\bullet f_{1}^{\prime}(x\,,y)\,,\qquad\qquad_{\!\!\!\int(x,y)}\<\!\!\!\!\!\!\!\int_{y}^{z}\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\int_{z}^{x}\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{x}\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\int_{z}^{z}\!\!\!\!\!\!\!\!\!\!\int_{z}^{y}\!\!\!\!\!\$ $f_{12}^{\prime\prime}(x\,,y\,)\bullet f_{2}^{\prime}\bigl[x+y\,,f(x\,,y\,)\bigr]+f_{1}^{\prime}(x\,,y\,)\,\bigl\{f_{21}^{\prime\prime}\bigl[x+y\,,f(x\,,y\,)\bigr]+f_{22}^{\prime}(x\,,y\,)\,\bigl\{f_{12}^{\prime\prime}\bigl[x+y\,,f(x\,,y\,)\bigr]\bigr\}\,.$ $f_{\;22}^{\prime\prime}[x+y\,,f(x\,,y\,)]\bullet f_{\;2}^{\prime}(x\,,y\,)\,\}.$ >f(1.1)是 f(u,v)的极值 由题意知 $f_{1}^{\prime}(1,1)=0\,,f_{2}^{\prime}(1,1)=0\,,$  

从而  

$$
\frac{\partial^{2}z}{\partial x\,\partial y}\biggm|_{(1,1)}=f_{\,^{11}}^{\prime\prime}(2,2)+f_{\,^{2}}^{\prime}(2,2)f_{\,^{12}}^{\prime\prime}(1,1).
$$  

# 三隐函数求导法  

设以下所给函数的偏导数均连续.  

# 1.一个方程的情形  

设$F(x\,,y\,,z)\!=\!0\,,P_{\scriptscriptstyle0}(x\,_{0}\,,y\,_{\scriptscriptstyle0}\,,z_{0})$ ,若满足 $\textcircled{1}F(P_{\circ})\!=\!0;\!\textcircled{2}F_{\circ}^{\prime}(P_{\circ})\neq0$ ,则在点 $\boldsymbol{P}_{\circ}$ 的某邻 域内可确定 $z=z\left(\boldsymbol{x}\,,\boldsymbol{y}\right)$ ,且有  
# 比宁高等数学18讲  

$$
\frac{\partial z}{\partial x}=-\frac{F_{x}^{\prime}}{F_{z}^{\prime}},\frac{\partial z}{\partial y}=-\frac{F_{y}^{\prime}}{F_{z}^{\prime}}.
$$  

#  $^{2,}$ 方程组的情形  

设 $\begin{array}{r}{\left\langle F\left(\boldsymbol{x}\mathrm{~,~}\boldsymbol{y}\mathrm{~,~}\boldsymbol{z}\right)=0\,,\right.}\\ {\left.G\left(\boldsymbol{x}\mathrm{~,~}\boldsymbol{y}\mathrm{~,~}\boldsymbol{z}\right)=0\,,\right.}\end{array}$ 当满足 $\frac{\partial(F,G)}{\partial(y\,,z\,)}=\left|\frac{\partial F}{\partial y}\quad\frac{\partial F}{\partial z}\right|\neq\,0$ 时，可确定 $\left\{y=y\left(x\right),\right.$ 其复合结构  

图为  

$$
{\frac{\mathrm{d}y}{\mathrm{d}x}}=-{\frac{{\cfrac{\partial(F,G)}{\partial(x,z)}}}{{\cfrac{\partial(F,G)}{\partial(y,z)}}}}=-{\frac{\left|{\cfrac{\partial F}{\partial x}}\ \ {\cfrac{\partial F}{\partial z}}\right|}{\left|{\cfrac{\partial F}{\partial y}}\ \ {\cfrac{\partial F}{\partial z}}\right|}},{\frac{\mathrm{d}z}{\mathrm{d}x}}=-{\frac{{\cfrac{\partial(F,G)}{\partial(y,x)}}}{{\cfrac{\partial(F,G)}{\partial(y,z)}}}}=-{\frac{\left|{\cfrac{\partial G}{\partial z}}\ \ {\cfrac{\partial G}{\partial x}}\right|}{\left|{\cfrac{\partial F}{\partial y}}\ \ {\cfrac{\partial F}{\partial z}}\right|}}.
$$  

例 13. 6若函数 $z=\,z(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 由方程 $\mathrm{e}^{x+2y+3z}+x y z=1$ 确定,则 $\mathrm{d}z\,\Big|_{(0,0)}=-$  

【解】应填 $-\,\frac{1}{3}\mathrm{d}x-\frac{2}{3}\mathrm{d}y$  

先求 $z\left(0,0\right)$ .在原方程中令 $x=0\,,y=0$ 得 $\mathrm{e}^{3z(0,0)}=1$ ，故 $z\left(0,0\right)=0$ 令 $F(x\,,y\,,z)=\mathrm{e}^{x+2y+3z}+x\,y z-1$ ,则由公式法，知  

$$
\begin{array}{r}{\frac{\partial z}{\partial x}\!=\!-\frac{F_{x}^{\prime}}{F_{z}^{\prime}}\!=\!-\frac{\mathrm{e}^{x+2y+3z}\,\cdot\,1+y z}{\mathrm{e}^{x+2y+3z}\,\cdot\,3+x\,y}\,,}\\ {\frac{\partial z}{\partial y}\!=\!-\frac{F_{y}^{\prime}}{F_{z}^{\prime}}\!=\!-\frac{\mathrm{e}^{x+2y+3z}\,\cdot\,2+x\,z}{\mathrm{e}^{x+2y+3z}\,\cdot\,3+x\,y}\,,}\end{array}
$$  

当 $\scriptstyle x\;=\;0\,,y\;=\;0\,,z\;=\;0$ 时， $\frac{\partial z}{\partial x}=-\frac{1}{3},\frac{\partial z}{\partial y}=-\frac{2}{3}$ ，则  

$$
\mathrm{d}z\Big\vert_{(0,0)}=-\frac{1}{3}\mathrm{d}x-\frac{2}{3}\mathrm{d}y.
$$  

【注】 此题还有以下两种解法，一是复合函数求导法,二是利用全微分形式不变性复合函数求导法将方程两端对 $_{x}$ 求偏导数得  

$$
\mathrm{e}^{x+2y+3z}\left(1+3\:\frac{\partial z}{\partial x}\right)+y z+x y\:\frac{\partial z}{\partial x}=0\,,
$$  
令 $\scriptstyle x\;=\;0\,,y\;=\;0\,,z\;=\;0$ 可得 $1+3\left.\frac{\partial z}{\partial x}\right|_{(0,0)}=0$ 即， $\left.\frac{\partial\mathscr{z}}{\partial x}\right|_{(0,0)}=-\,\frac{1}{3}.$ 将方程两端对 $_y$ 求偏导数得  

$$
\mathrm{e}^{x+2y+3z}\left(2+3\,\frac{\partial z}{\partial y}\right)+x z+x y\,\,\frac{\partial z}{\partial y}=0\,,
$$  

令 $\scriptstyle x\;=\;0\,,y\;=\;0\,,z\;=\;0$ 可得 $2+3\left.\frac{\partial z}{\partial y}\right|_{(0,0)}=0$ 即， $\left.\frac{\partial\boldsymbol{z}}{\partial\boldsymbol{y}}\right|_{(0,0)}=-\frac{2}{3}.$  

因此  

$$
\mathrm{d}z\Bigm\lvert_{(0,0)}=\Big(\frac{\partial z}{\partial x}\mathrm{d}x+\frac{\partial z}{\partial y}\mathrm{d}y\Big)\Bigm\lvert_{(0,0)}=-\frac{1}{3}\mathrm{d}x-\frac{2}{3}\mathrm{d}y.
$$  

利用全微分形式不变性对于一元函数： $\mathrm{d}[\varphi(u)]=\varphi^{\prime}(u)\,\mathrm{d}u$  

对于多元函数 $\mathrm{d}\big[\varphi\left(u\,,v\,,w\right)\big]\,{=}\,\frac{\partial\varphi}{\partial u}\mathrm{d}u+\frac{\partial\varphi}{\partial v}\mathrm{d}v+\frac{\partial\varphi}{\partial w}\mathrm{d}w.$  

将原方程两端求全微分得  

$$
\mathrm{e}^{x+2y+3z}\,\mathrm{d}(x+2y+3z)+\mathrm{d}(x y z)=0\,,
$$  

即  

$$
\mathrm{e}^{x+2y+3z}(\mathrm{d}x+2\mathrm{d}y+3\mathrm{d}z)+y z\,\mathrm{d}x+x z\,\mathrm{d}y+x y\,\mathrm{d}z=0
$$  

令$\scriptstyle x\;=\;0\,,y\;=\;0\,,z\;=\;0$ 可得 $\mathrm{d}x+2\mathrm{d}y+3\mathrm{d}z\Big|_{(0,0)}=0$ ，则  

$$
\mathrm{d}z\Big\vert_{(0,0)}=-\frac{1}{3}\mathrm{d}x-\frac{2}{3}\mathrm{d}y.
$$  

综上，公式法、复合函数求导法、利用全微分形式不变性是常用的三种方法。  

例 13. 7设 $y=y\left(x\,\right),z=z\left(x\,\right)$ 是由方程 $z=x f(x+y)$ 和 $F(x\,,y\,,z)\,{=}\,0$ 所确定的函数,其中 $f$ 和 $F$ 分别具有一阶连续导数和一阶连续偏导数,且 $F_{y}^{\prime}+x f^{\prime}F_{z}^{\prime}\ne0$ 求 $\frac{\mathrm{d}{z}}{\mathrm{d}{x}}$  

【解】令 $G(x,y\,,z)=x f(x+y)-z$ ，由公式法，知  

$$
{\frac{\mathrm{d}z}{\mathrm{d}x}}=-{\frac{{\frac{\partial(F,G)}{\partial(y,x)}}}{{\frac{\partial(F,G)}{\partial(y,z)}}}}=-{\frac{\left|{\frac{\partial F}{\partial y}}\ \ {\frac{\partial G}{\partial x}}\right|}{\left|{\frac{\partial F}{\partial y}}\ \ {\frac{\partial F}{\partial z}}\right|}}=-{\frac{\left|F_{y}^{\prime}\ \ \ \ F_{x}^{\prime}\ \ \right|}{\left|F_{y}^{\prime}\ \ \ {\frac{f}{F_{z}^{\prime}}}\right|}}
$$  

【注】本题亦可用下面的方法求解。  

分别在 $z=x f(x+y)$ 和 $F(x\,,y\,,z)=0$ 的两端对 $_{x}$ 求导，得  
$$
\begin{array}{l}{\displaystyle\left\{\frac{\mathrm{d}z}{\mathrm{d}x}=f+x\left(1+\frac{\mathrm{d}y}{\mathrm{d}x}\right)f^{\prime},\right.}\\ {\displaystyle F_{x}^{\prime}+F_{y}^{\prime}\left.\frac{\mathrm{d}y}{\mathrm{d}x}+F_{z}^{\prime}\left.\frac{\mathrm{d}z}{\mathrm{d}x}=0,\right.}\end{array}
$$  

整理后得  

$$
\begin{array}{r}{\{\boldsymbol{-x}\,\boldsymbol{f}^{\prime}\,\frac{\mathrm{d}\boldsymbol{y}}{\mathrm{d}\boldsymbol{x}}+\frac{\mathrm{d}\boldsymbol{z}}{\mathrm{d}\boldsymbol{x}}=\boldsymbol{f}+\boldsymbol{x}\,\boldsymbol{f}^{\prime}\,,\ }\\ {\quad\quad\quad\left|F_{\vphantom{\vphantom{\bigg|}}}^{\prime}\,\frac{\mathrm{d}\boldsymbol{y}}{\mathrm{d}\boldsymbol{x}}+\boldsymbol{F}_{\vphantom{\bigg|}}^{\prime}\,\frac{\mathrm{d}\boldsymbol{z}}{\mathrm{d}\boldsymbol{x}}=-\,\boldsymbol{F}_{\vphantom{\bigg|}}^{\prime}\,,\ }\end{array}
$$  

由此解得  

$$
\frac{\mathrm{d}z}{\mathrm{d}x}\!=\!\frac{(f+x f^{\prime})F_{s}^{\prime}-x f^{\prime}F_{x}^{\prime}}{F_{y}^{\prime}+x f^{\prime}F_{z}^{\prime}}.
$$  

四多元函数的极、最值  

设函数 $z=f(x\,,y\,)$ 在点 $(x_{0},y_{0})$ 的某邻域内有定义,如果在此邻域内都有 $f(x\,,y\,)\leqslant$ $f(x\,_{0}\,,y\,_{0})$ (或 $f(x\,,y)\geqslant f(x_{0}\,,y_{0}))$ ，则称函数 $f(x\,,y\,)$ 在点 $(x_{0},y_{0})$ 处取得极大值(或极 小值).  

极值存在的必要条件  

设函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 在点 $(x_{0},y_{0})$ 处具有偏导数,且在点 $(x_{0},y_{0})$ 处取得极值,则它在该点的偏导数必为零，即  

$$
f_{\;\;x}^{\prime}(x_{\,0}\,,y_{\,0})=0\,,f_{\;\;y}^{\prime}(x_{\,0}\,,y_{\,0})=0.
$$  

【注】偏导数不存在的点也可能是极值点，如 $z=\sqrt{x^{2}+y^{2}}$ 在点(0,0)处的情形： $f_{\mathrm{~},x}^{\prime}\left(0,0\right)$  $f_{y}^{\prime}(0,0)$ 均不存在，但点(0,0)是极小值点.  

3.极值存在的充分条件  

设函数 $z=f(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 在点 $(x_{0},y_{0})$ 的某邻域内连续,且具有一阶及二阶连续偏导数，又 $f_{\;\;x}^{\prime}\,(x_{\,0}\,,\pmb{y}_{\,0})=0\,,f_{\;\;y}^{\prime}\,(x_{\,0}\,,\pmb{y}_{\,0})=0.$ 令  

$$
\begin{array}{r}{f_{\;\;x x}^{\prime\prime}\left(x_{\,\,0},y_{\,0}\right)=A\,,f_{\;\;x y}^{\prime\prime}\left(x_{\,\,0}\,,y_{\,0}\right)=B\,,f_{\;\;y y}^{\prime\prime}\left(x_{\,\,0}\,,y_{\,0}\right)=C\,,}\end{array}
$$  

则  

(1)当 $A C-B^{2}>0$ 时， $f(x\,,y)$ 在点 $(x_{0},y_{0})$ 处取得极值,且当 $A<0$ 时,取得极大值,当 $A>0$ 时,取得极小值;  

（2）当 $A C-B^{2}<0$ 时， $f(x\,,y\,)$ 在点 $(x_{\circ},y_{\circ})$ 处不取得极值；  

(3）当 $A C-B^{2}=0$ 时， $f(x\,,y\,)$ 在点 $(x_{0},y_{0})$ 处是否取得极值不能确定，还需另作讨论（一  
般用定义法).  

4.条件最值与拉格朗日乘数法  

求目标函数 $u=f(\boldsymbol{x}\,,y\,,z\,)$ 在条件 $\begin{array}{c}{{\left\langle\varphi\left(x\mathrm{~,~}y\mathrm{~,~}z\right)=0\,\right|}}\\ {{\left|\psi\left(x\mathrm{~,~}y\mathrm{~,~}z\right)=0\right.}}\end{array}$ 下的最值，则  

（1）构造辅助函数 $F(x\,,y\,,z\,,\lambda\,,\mu)=f(x\,,y\,,z\,)+\lambda\varphi(x\,,y\,,z\,)+\mu\psi(x\,,y\,,z\,)\,;$  

(2)令  

$$
\begin{array}{r l}&{\left\vert F_{x}^{\prime}\!=\!f_{x}^{\prime}\!+\!\lambda\varphi_{\phantom{,}x}^{\prime}\!+\!\mu\psi_{\phantom{,}x}^{\prime}\!=\!0\,,}\\ &{\left\vert F_{y}^{\prime}\!=\!f_{y}^{\prime}\!+\!\lambda\varphi_{\phantom{,}y}^{\prime}\!+\!\mu\psi_{\phantom{,}y}^{\prime}\!=\!0\,,}\\ &{\left\vert F_{z}^{\prime}\!=\!f_{z}^{\prime}\!+\!\lambda\varphi_{\phantom{,}x}^{\prime}\!+\!\mu\psi_{\phantom{,}x}^{\prime}\!=\!0\,,\right.}\\ &{\left.F_{\lambda}^{\prime}\!=\!\varphi\!\left(x\,,y\,,z\right)=0\,,}\\ &{\left.F_{\mu}^{\prime}\!=\!\psi\!\left(x\,,y\,,z\right)=0\,,\right.}\end{array}
$$  

（3）解上述方程组得备选点 $P_{i}\,,i=1,2,3\,,\cdots,n$ ，并求 $f(P_{i})$ ,取其最大值为 $u_{\textrm{m a x}}$ ,最小值为 $u_{\mathrm{\,min}}$ ；  

（4）根据实际问题，必存在最值，所得即为所求。  

5.有界闭区域上连续函数的最值问题  

(1）理论依据一—最大值与最小值定理:在有界闭区域 $D$ 上的多元连续函数，在 $D$ 上一定有最大值和最小值.  

(2）求法.  

$\textcircled{1}$ 根据 $f_{\;x}^{\prime}\left(x\;,y\right),f_{\;y}^{\prime}\left(x\;,y\right)$ 为0或不存在，求出 $D$ 内部的所有可疑点；  
 $\circledcirc$ 用拉格朗日乘数法或代人法求出 $D$ 边界上的所有可疑点；  
 $\textcircled{3}$ 比较以上所有可疑点的函数值大小，取其最小者为最小值，最大者为最大值.  

例 13. 8设函数 $u\left(x\,,y\,\right)$ 在有界闭区域 $D$ 上连续，在 $D$ 的内部具有二阶连续偏导数,且满足 $\frac{\partial^{2}u}{\partial x\,\partial y}\neq0$ 及${\frac{\partial^{2}u}{\partial x^{2}}}+{\frac{\partial^{2}u}{\partial y^{2}}}=0$ ,则（  

$(\mathbf{A})u(x\,,y\,)$ 的最大值和最小值都在 $D$ 的边界上取得 $(\mathrm{\boldmath~B~})\,u\,(\,x\,,y\,)$ 的最大值和最小值都在 $D$ 的内部取得 $(\mathrm{C})u(x\,,y)$ 的最大值在 $D$ 的内部取得，最小值在 $D$ 的边界上取得 $(\mathrm{D})\boldsymbol{u}\left(\boldsymbol{x}\mathrm{~,~}\boldsymbol{y}\right)$ 的最小值在 $D$ 的内部取得，最大值在 $D$ 的边界上取得  

因为 $u\left(x\,,y\right)$ 在有界闭区域 $D$ 上连续，所以 $u\left(x\,,y\right)$ 在 $D$ 上必然有最大值和最小值.假设在内部存在驻点 $(x_{\mathrm{~0~}},y_{\mathrm{~0~}})$ 则 $\frac{\partial u}{\partial x}\Bigm|_{(x_{0},y_{0})}=\frac{\partial u}{\partial y}\Bigm|_{(x_{0},y_{0})}=0$ ，且在点 $(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0})$ 处樂  

$$
A=\!\frac{\partial^{2}u}{\partial x^{2}}\Big|_{(x_{0},\ y_{0})}\,,B=\!\frac{\partial^{2}u}{\partial x\,\partial y}\Big|_{(x_{0},y_{0})}=\!\frac{\partial^{2}u}{\partial y\,\partial x}\Big|_{(x_{0},y_{0})}\,,C=\!\frac{\partial^{2}u}{\partial y^{2}}\Big|_{(x_{0},y_{0})}\,.
$$  

由条件可知 $A C-B^{2}<0$ ，显然 $u\left(x_{\mathrm{~0~}},y_{\mathrm{~0~}}\right)$ 不是极值,当然也不是最值,所以 $u(x\,,y\,)$ 的最大  
# 比亨高等数学18讲  

值点和最小值点必定都在区域 $D$ 的边界上，所以应选(A).  

例 13. 9已知函数 $f(x\,,y\,)$ 在点（0，0）的某邻域内连续，且  

$$
\operatorname*{lim}_{x\to0}\,{\frac{f(x\,,y\,)-a x\,y}{(x^{\,2}+y^{\,2}\,)^{2}}}=1\,,
$$  

其中 $^{\,a}$ 为非零常数,则f(0,0)(  

（A）是极大值（B）是极小值(C）不是极值（D）是否取极值与 $\boldsymbol{a}$ 有关  

【解】应选(C).  

由极限脱帽法，知 $\frac{f(x\:,y\:)-a x y}{(x^{\:2}+y^{2})^{2}}=1+\alpha$ ,其中 $\operatorname*{lim}_{x\rightarrow0}=0$ ,于是有  

$f(x\,,y)=a x y+(x^{2}+y^{2})^{2}+\alpha\,\cdot\,(x^{2}+y^{2})^{2}.$  

故 $f(0,0)=\underset{x\rightarrow0}{\operatorname*{lim}}f(x,y)=0$ ,又在 $y=x$ 上 $,f(x\,,x\,)=\!a x^{\,2}+4x^{\,4}+\alpha\,\cdot\,4x^{\,4}$ ，故当 $\vert\ x\vert$ 充分小时， $f(x\,,x\,)\sim a x^{2}\,,f(x\,,x\,)$ 与 $^{a}$ 同号；在 $y=-x$ 上 $,f(x\,,-x\,)\,{=}\,{-a x^{\,2}}+4x^{\,4}+\alpha\cdot4x^{\,4}$ ，故当 $\vert\boldsymbol{\textbf{\em x}}\vert$ 充分小时， $f(x\,,-\,x\,)\sim(-\,a x^{\,2}\,)\,,f(x\,,-\,x\,)$ 与 $-\ a$ 同号.  

综上，在点（0,0）附近， $f(x\,,y\,)$ 的值有正有负，所以 $f(0,0)=0$ 不是极值.  

例 13. 10设 $\alpha>0\,,b>0$ ，函数 $f(x\;,y)=2\mathrm{ln}\mid x\;\mid+\frac{(x-a)^{2}+b y^{2}}{2x^{2}}$ 在 $x<0$ 时的极小值为2，且 $f_{y y}^{\prime\prime}\left(-1,0\right)=1$  

（1）求 $\alpha\cdot b$ 的值；  

(2）求 $f(x\,,y\,)$ 在$x>0$ 时的极值.  

【解](1) $f_{x}^{\prime}(x\,,y)=\!{\frac{2x^{\,2}+a x-a^{\,2}-b y^{\,2}}{x^{\,3}}},f_{y}^{\prime}(x\,,y\,)=\!{\frac{b y}{x^{\,2}}}.$ 令$\begin{array}{r}{\left\{f_{x}^{\prime}\left(x\wedge y\right)=0\,,\right.}\\ {\left.f_{y}^{\prime}\left(x\wedge y\right)=0\,,\right.}\end{array}$ 得驻点 $(-\,a\,,0\,)\,,\Bigl(\frac{a}{2}\,,0\Bigr)\,.$ 又$f_{x x}^{\prime\prime}\left(x\;,y\right)=-\frac{-2x^{2}-2a x+3a^{2}+3b y^{2}}{x^{4}},f_{x y}^{\prime\prime}\left(x\;,y\right)=\frac{-2b y}{x^{3}},f_{y y}^{\prime\prime}\left(x\;,y\right)=\frac{b}{x^{2}},$  

由 $f_{y y}^{\prime\prime}\left(-1,0\right)=1$ ，知 $b=1$ ，故在点 $(-\,\boldsymbol{a}\,,0)$ 处，  

$$
A=f_{x x}^{\prime\prime}\left(-\,a\,,0\right)=\frac{3}{a^{2}},B=f_{x y}^{\prime\prime}\left(-\,a\,,0\right)=0,C=f_{y y}^{\prime\prime}\left(-\,a\,,0\right)=\frac{1}{a^{2}}.
$$  

由于 $A C-B^{2}=\frac{3}{a^{4}}>0$ 且 $A>0$ ,因此 $f(-\,a\,,0)$ 是函数 $f(x\,,y\,)$ 的极小值,极小值为 $f(-\alpha\,,0)=2\ln\,a+2=2$ ，故 $\alpha=1$  

(2）在点 $\left({\frac{1}{2}},0\right)$ 处，  

$$
A=f_{x x}^{\prime\prime}\left(\frac{1}{2},0\right)\!=\!24\,,B=f_{x y}^{\prime\prime}\left(\frac{1}{2},0\right)\!=\!0\,,C=f_{y y}^{\prime\prime}\left(\frac{1}{2},0\right)\!=\!4.
$$  

由于 $A C-B^{2}=96>0$ ，且 $A>0$ ，因此 $f\left({\frac{1}{2}},0\right)$ 是函数 $f(x\,,y\,)$ 的极小值,极小值为  
$$
f\!\left({\frac{1}{2}},0\right)\!=\!{\frac{1}{2}}-2\ln\,2.
$$  

例13. 11设 $\alpha\cdot b$ 为实数，函数 $f(x\,,y){=}a x^{2}+b y^{2}$ 在点(2,1）处沿方向 $\pmb{l}=\pmb{i}+2\pmb{j}$ 的方向导数最大,最大值为 $4\,\sqrt{5}$  

（1）求 $^{\alpha,b}$ 的值；  
(2）在曲线 $f(x\,,y\,)=4$ 上求一点,使其到直线 $2x+3y-6=0$ 的距离最短.  

[解](1)函数 $f(x\,,y\,)=a x^{2}+b y^{2}$ 在点（2,1）处的梯度为  

$$
\textbf{d}f\Big\vert_{\mathbf{\Phi}_{(2,1)}}=\Big(\frac{\partial f}{\partial x},\frac{\partial f}{\partial y}\Big)\Bigm\vert_{\mathbf{\Phi}_{(2,1)}}=(2a x\cdot,2b y)\Bigm\vert_{\mathbf{\Phi}_{(2,1)}}=(4a\cdot,2b).
$$  

由题设条件知， $\sqrt{(4a)^{2}+(2b)^{2}}=4\sqrt{5}$ 且 $\frac{4a}{1}=\frac{2b}{2}=k>0$ ,解得 $\begin{array}{r}{|a=1\,,}\\ {b=4.}\end{array}$  

(2）由(1)可知， $f(x\,,y\,)\,{=}\,x^{2}+4y^{2}$ ，设 $P\left(x,y\right)$ 为曲线 $x^{2}+4y^{2}=4$ 上任意一点，则点 $P$ 到直线 $2x+3y-6=0$ 的距离一点(xo, Yo) 到直线 Ax+ By + C=0  

$$
d={\frac{\mid2x+3y-6\mid}{\sqrt{13}}}.
$$  

因为求函数 $^{d}$ 的最小值点即求 $d^{2}$ 的最小值点（见注），所以问题可抽象为如下数学模型：  

求目标函数 $d^{2}=\frac{1}{13}(2x+3y-6)^{2}$ 在约束条件 $x^{2}+4y^{2}=4$ 下的最小值.  

作拉格朗日函数 $F(x\,,y\,,\lambda\,)=\frac{1}{13}(2x\,+3y\,-6)^{2}+\lambda\,(x^{\,2}+4y^{\,2}-4)$ ，令  

$$
\left\{\!\!\begin{array}{l}{{\displaystyle F_{\it x}^{\prime}\!=\!\frac{4}{13}(2x+3y-6)+2\lambda x=0\,,}}\\ {{\displaystyle F_{\it y}^{\prime}\!=\!\frac{6}{13}(2x+3y-6)+8\lambda y=0\,,}}\\ {{\displaystyle F_{\it x}^{\prime}\!=\!x^{2}+4y^{2}-4=0.}}\end{array}\right.
$$  

$\lambda=0$ 则原方程组转化为 $\displaystyle{\xi^{2}x+3y-6=0}\,,$ 即为求曲线与直线的交点，事实上，二者并不相交，此时方程组无解.  

若$\lambda\neq0$ ，由 $\textcircled{1}$ ，$\circledcirc$ 得${\frac{\frac{4}{13}}{\frac{6}{13}}}={\frac{-2x}{-8y}},x={\frac{8}{3}}y$ ，代人 $\textcircled{3}$ 式，解得 $x_{1}=\frac{8}{5},y_{1}=\frac{3}{5},x_{2}=-\frac{8}{5}$  $y_{2}=-\frac{3}{5}$ 日  

$$
d\left|_{\mathbf{\Phi}_{(x_{1},y_{1})}}=\!\frac{1}{\sqrt{13}},d\!\;\right|_{\mathbf{\Phi}_{(x_{2},y_{2})}}\!=\!\frac{11}{\sqrt{13}}.
$$  

根据问题的实际意义可知,最短距离一定存在,因此 $\left({\frac{8}{5}},{\frac{3}{5}}\right)$ 即为所求点.  
# 陆宁高等数学18洲  

【注】（1）需先证明直线和曲线不相交，用反证法证明如下.  

设 $\displaystyle{\xi^{2}x+3y-6=0}\,,$ 有解,则 $25y^{2}-36y+20=0$ 有解,这与该方程的判别式 $\Delta\,{=}\,(-36)^{2}-$  

$4\times25\times20<0$ 矛盾，即 $\displaystyle{\xi^{2}x+3y-6=0}\,,$ 无解。  

（2）见到 $\sqrt{u}\ ,\sqrt[3]{u}\ ,u>0$ ，用 $\boldsymbol{u}$ 来求最值.  

(3)见到 $\textbf{\textsf{l u}}|$ ,要知道 $|\textbf{\em u}|=\sqrt{u^{2}}$ ,即用 $u^{2}$ 来求最值.  

(4) 见到 $\boldsymbol{u}_{\u{1}}\,\boldsymbol{u}_{\u{2}}\,\boldsymbol{u}_{\u{3}}$ ，其中 $u_{i}>0,i=1,2,3\,.$ 要想到取对数，写成 $\ln u_{1}+\ln u_{2}+\ln u_{3}$ ，再求最值。(2），(3），（4）三个处理手段均是由于前后两者有相同的单调性，即有相同的最值点，而后者计算起来更方便.  

五偏微分方程（含偏导数的等式）  

(1）已知偏导数(或偏增量）的表达式,求 $z=f\left(.\tau\cdot y\,\right)$  

（2）给出变换，化已知偏微分方程为常微分方程，求 $f(u\,)$  

（3）给出变换，化已知偏微分方程为指定偏微分方程及其反问题.  

例 13.12设函数 $f(x\,,y\,)$ 可微， $f(0,0)\!=\!0\,,\!{\frac{\partial f}{\partial x}}\!=\!-f(x\,,\!y\,)\,,\!{\frac{\partial f}{\partial y}}\!=\!\mathbf{e}^{-x}$ cos $_y$ 求 $f(x\cdot x)$ 在 $[0,+\infty)$ 的部分与 $_{x}$ 轴围成的图形绕 $_{x}$ 轴旋转一周所成的旋转体体积。  

[解]由 ${\frac{\partial f}{\partial y}}=\mathbf{e}^{-x}$ cos $_y$ 得$f(x\,,y)=\mathrm{e}^{-x}\sin\,y+\varphi(x\,)$ ，于是 ${\frac{\partial f}{\partial x}}=-\,\mathrm{e}^{-x}\sin\,y+\varphi^{'}(x\,).$  ${\frac{\partial f}{\partial x}}=-f(x\,,y\,)$ ，故  

$$
-\;\mathrm{e}^{-x}\sin\;y+\varphi^{\prime}(x\,)=-\;\mathrm{e}^{-x}\sin\;y-\varphi(x\,)\,,
$$  

于是有 $\varphi^{\prime}(x)+\varphi(x)\!=\!0$ ,解得 $\varphi\left(x\right){=}C\mathrm{e}^{-x}$ ,即 $f(x\,,y\,)=\mathbf{e}^{-x}\sin\,y+C\,\mathrm{e}^{-x}$ 由$f(0,0)\mathop{=}0$ ,得  $C=0$ ,所以 $f(x\,,y\,)=\mathrm{e}^{-x}\sin\,y$ 于是  

$$
\begin{array}{l}{{\displaystyle{\cal V}=\displaystyle\int_{0}^{+\infty}\pi f^{2}\left(x\ ,x\ \right)\mathrm{d}x\ =\!\!\int_{0}^{+\infty}\pi\mathrm{e}^{-2x}\sin^{2}x\mathrm{d}x\ =\!\displaystyle\int_{0}^{+\infty}\pi\mathrm{e}^{-2x}\ \frac{1-\cos2x}{2}\mathrm{d}x}}\\ {{\displaystyle\ ~~=\frac{\pi}{2}\displaystyle\int_{0}^{+\infty}\mathrm{e}^{-2x}\left(1-\cos\ 2x\ \right)\mathrm{d}x=\frac{\pi}{2}\displaystyle\int_{0}^{+\infty}\mathrm{e}^{-2x}\,\mathrm{d}x-\frac{\pi}{2}\displaystyle\int_{0}^{+\infty}\mathrm{e}^{-2x}\cos\ 2x\mathrm{d}x}}\\ {{\displaystyle\ ~~\frac{u=2x}{4}\,\frac{\pi}{4}-\frac{\pi}{4}\displaystyle\int_{0}^{+\infty}\mathrm{e}^{-u}\cos\ u\,\mathrm{d}u\,,}}\end{array}
$$  

其中  

$$
\begin{array}{r l r}{\lefteqn{\int_{0}^{+\infty}\mathrm{e}^{-u}\cos\,u\,\mathrm{d}u=\left|\frac{\mathrm{e}^{-u}\,)^{\prime}}{\mathrm{e}^{-u}}\,\cos\,u\,\right|^{\prime}}}\\ &{}&{\qquad\qquad\qquad\qquad\qquad\left|\vphantom{\frac{1}{\sin^{2}\,}}\right|_{0}^{+\infty}}\\ &{}&{\qquad\qquad=\frac{1}{2}(-\,\mathrm{e}^{-u}\cos\,u+\mathrm{e}^{-u}\sin\,u)\,\right|_{0}^{+\infty}}\\ &{}&{\qquad\qquad=\frac{1}{2}(-\,\mathrm{e}^{-u}\cos\,u+\mathrm{e}^{-u}\sin\,u)\,\right|_{0}^{+\infty}}\end{array}
$$  
$$
=\!\frac{1}{2}[0-(-1)]\!=\!\frac{1}{2},
$$  

故  

$$
V={\frac{\pi}{4}}-{\frac{\pi}{4}}\cdot{\frac{1}{2}}={\frac{\pi}{8}}.
$$  

】对于数学一的考生，还应熟悉这种命题方法：  

设 $f(x\,,y)$ 可微,其在点 $(x\,,y)$ 处沿方向 $\pmb{l}_{1}=-\pmb{i}$ 的方向导数为 $f(x\,,y)$ ,沿方向 $\pmb{l}_{2}=-\pmb{j}$ 的方向导数为一 $\mathsf{e}^{-x}$ cos $_y$ ,就是题设中的条件: ${\frac{\partial f}{\partial x}}\,{=}\,{-}f(x\,,y)$ ， ${\frac{\partial f}{\partial y}}\!=\!\mathbf{e}^{-x}\cos\,y$ ,当然更为复杂的命题方法，见例17.10.  

例13.13设函数 $f(u)$  $(0,+\infty)$ 内可导。 $z=x f\Big(\frac{y}{x}\Big)+y$ 满足关系式 $x\ {\frac{\partial z}{\partial x}}-y\ {\frac{\partial z}{\partial y}}=$ $\displaystyle2\,z$ ,且 $f(1)=1$ 考研真题还考过/（√x+1)  

（1）求 $f(x)$ 的表达式；  

（2）求曲线 $y=f(x)$ 的所有渐近线.  

$$
{\frac{\partial z}{\partial x}}=f(u)+x f^{\prime}(u)\,\bullet\,\left(-\,{\frac{y}{x^{2}}}\right)=f(u)-{\frac{y}{x}}f^{\prime}(u)\,,
$$  

$$
{\frac{\partial z}{\partial y}}=x f^{\prime}(u)\cdot{\frac{1}{x}}+1=f^{\prime}(u)+1,
$$  

代人 $x\ {\frac{\partial z}{\partial x}}-y\ {\frac{\partial z}{\partial y}}=2z$ ，得  

$$
x f(u)-y f^{\prime}(u)-y f^{\prime}(u)-y=2x f(u)+2y\,,
$$  

即$2y f^{\prime}(u)+x f(u)+3y=0$ ,方程两边同时除以 $_{2y}$ ,得 $f^{\prime}(u)+\frac{1}{2\,\frac{y}{x}}f(u)+\frac{3}{2}=0$ ,即  

$$
f^{\prime}(u)+\frac{1}{2u}f(u)=-\frac{3}{2}.
$$  

由例5.14可知， $f(x)\!=\!{\frac{1}{\sqrt{x}}}(2-x^{\frac{3}{2}})$  

（2）由例5.14可知， $x=0$ 是曲线 $_{y=f(x)}$ 的铅直渐近线, $y=-x$ 是曲线 $_y=f(x)$ 的斜渐近线.  

例 13.14设 $z=z(\boldsymbol{x}\,,\boldsymbol{y}\,)$ 有二阶连续偏导数,用变换 $u=x-2y\,,v=x+a y$ 可把方程 $6\,\frac{\partial^{2}z}{{\partial x}^{\,2}}+\frac{\partial^{2}z}{\partial x\,\partial y}-\frac{\partial^{2}z}{\partial y^{\,2}}=0$ 化简为 $\frac{\partial^{2}z}{\partial u\partial v}\!=\!0$ ，求常数 $^{\,a}$  

由复合函数求导法得  
$$
\frac{\partial{z}}{\partial x}=\frac{\partial{z}}{\partial u}\cdot\frac{\partial{u}}{\partial x}+\frac{\partial{z}}{\partial v}\cdot\frac{\partial{v}}{\partial x}=\frac{\partial{z}}{\partial u}+\frac{\partial{z}}{\partial v},
$$  

$$
\frac{\partial z}{\partial y}=\frac{\partial z}{\partial u}\cdot\frac{\partial u}{\partial y}+\frac{\partial z}{\partial v}\cdot\frac{\partial v}{\partial y}=-\,2\,\frac{\partial z}{\partial u}+a\,\,\frac{\partial z}{\partial v},
$$  

$$
\begin{array}{r l}&{\quad_{3/2}-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}-_{3/2},}\\ &{\Bar{\Bar{\Bar{p}}_{1}}=-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}-_{3/2},}\\ &{\Bar{\Bar{\Bar{p}}_{1}}=-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad_{3/2}-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}-_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}-_{3/2},}\\ &{\quad_{3/2},\quad_{3/2},}\\ &{\Bar{\Bar{\Bar{p}}_{1}}=-_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}+_{3/2},}\\ &{\quad-_{3/2},\quad_{3/2},\quad_{3/2}-_{3/2},\quad_{3/2}+_{
$$  

$6\,{\frac{\partial^{2}z}{{\partial x}^{\,2}}}+{\frac{\partial^{2}z}{\partial x\,\partial y}}-{\frac{\partial^{2}z}{\partial y^{\,2}}}=0$ ，得 $(10+5a\,)\,\frac{\partial^{2}z}{\partial u\,\partial v}+(6+a-a^{2}\,)\,\frac{\partial^{2}z}{\partial v^{2}}=0.$ 当 $\displaystyle{\big\{}_{a^{2}-a-6=0}^{10+5a\neq0},}$ 即， $\alpha=3$ 时 $\frac{\partial^{2}z}{\partial u\partial v}\!=\!0$  
# 第14讲  

# 二重积分  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/63c69c0aecfb1781f3e4c3ca99bffc2f4ccc388d97bab0987c21f9e06e39b0d9.jpg)  

# 1.和式极限  

$$
\iint_{D}f(x\,,y\,)\,\mathrm{d}\sigma=\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}\sum_{j=1}^{n}f\left(a+{\frac{b-a}{n}}i\,,c+{\frac{d-c}{n}}j\right)\cdot{\frac{b-a}{n}}\cdot{\frac{d-c}{n}},
$$  

其中 $D=\{(x\,,y)\mid a\leqslant x\leqslant b\,,c\leqslant y\leqslant d\}$  

$$
\begin{array}{l l}{\displaystyle\frac{\mathrm{i}\mathrm{\boldmath~\li~}_{+,1}}{\mathrm{i}2}}&{\displaystyle\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}\sum_{j=1}^{n}\,\displaystyle\frac{n}{(n+i)\,(n^{2}+j^{\frac{\prime}{2}})}=(\mathrm{\boldmath~\lambda~}).}\\ {\displaystyle)\int_{0}^{1}\!\mathrm{d}x\int_{0}^{x}\,\displaystyle\frac{1}{(1+x\,)(1+y^{2})}\mathrm{d}y}&{(\mathrm{B})\displaystyle\int_{0}^{1}\!\mathrm{d}x\int_{0}^{x}\,\displaystyle\frac{1}{(1+x\,)(1+y)}\mathrm{d}y}\\ {\displaystyle)\int_{0}^{1}\!\mathrm{d}x\int_{0}^{1}\displaystyle\frac{1}{(1+x\,)(1+y)}\mathrm{d}y}&{(\mathrm{D})\displaystyle\int_{0}^{1}\!\mathrm{d}x\int_{0}^{1}\displaystyle\frac{1}{(1+x\,)(1+y^{2})}\mathrm{d}y}\end{array}
$$  

【解】应选(D).  

设 $D=\{(x\,,y\,)\mid\,0\leqslant x\leqslant1,0\leqslant y\leqslant1\}$ ，记 $f(x\,,y)\,{=}\,\frac{1}{(1+x\,)(1+y^{2})}.$  

用直线 $\boldsymbol{x}=\boldsymbol{x}_{i}=\frac{i}{n}(i=0,1,2,\cdots,n)$ 与 $y=y_{j}=\frac{j}{n}(j=0,1,2,\cdots,n)$ 将 $D$ 分成 $n^{\,^{2}}$ 等份，则和式  
# 比宁高等数学18涉  

$$
{\frac{1}{(1+x_{i})(1+y_{j}^{2})}}\cdot{\frac{1}{n^{2}}}=\sum_{i=1}^{n}\sum_{j=1\atop i=1}^{n}{\frac{1}{\left(1+{\frac{i}{n}}\right)\left(1+{\frac{j^{2}}{n^{2}}}\right)}}\cdot{\frac{1}{n^{2}}}=\sum_{i=1}^{n}\sum_{j=1}^{n}{\frac{n}{(n+i)(n^{2}+j)}}
$$  

是函数 $f(x\,,y\,)$ 在 $D$ 上的一个二重积分的和式，所以  

$$
\therefore{=}\!\!\int\!_{\!\!\!\!D}{\frac{1}{(1+x)(1+y^{2})}}{\mathrm d}x{\mathrm d}y=\!\!\int_{\!\!0}^{1}\!{\mathrm d}x\!\int_{\!\!0}^{1}{\frac{1}{(1+x)(1+y^{2})}}{\mathrm d}y\,,
$$  

故应选(D).  

【注 题目出成了选择题,答案写成了积分的形式,给了考生提示。只不过,这并不是最后答案,最后答案应该为 ${\frac{\pi}{4}}\ln2.$ 也就是说,此题如果出成填空题：  

$$
\operatorname*{lim}_{n\to\infty}\sum_{i\mathop{=1}}^{n}\sum_{j\mathop{=1}}^{n}\,\frac{n}{(n+i)(n^{2}+j^{2})}=.
$$  

估计做出来的人会更少.  

2.普通对称性  

$\textcircled{1}$ 若 $D$ 关于 $_y$ 轴对称,则  

$$
\iint_{D}f(x\,,y\,)\,\mathrm{d}\sigma=\left\{\!\!\!\begin{array}{l l}{\displaystyle2\!\!\iint_{D_{1}}f(x\,,y)\mathrm{d}\sigma\,,}&{\,f(x\,,y)=f(-\,x\,,y)\,,}\\ {\displaystyle\ D_{1}}&{\,}\\ {0\,,}&{\,f(x\,,y)=-\,f(-\,x\,,y\,)\,,}\end{array}\!\!\right.
$$  

其中 $D_{1}$ 是 $D$ 在 $_y$ 轴右侧的部分.  

【注】若 $D$ 关于 $x=a(a\neq0)$ 对称，则  

$$
\begin{array}{r}{\underset{^{D}}{\iint}f(x\,,y\,)\,\mathrm{d}\sigma=\!\!\left\{\!\!\begin{array}{l l}{2\!\!\!\iint_{^{\textstyle f}}f(x\,,y\,)\,\mathrm{d}\sigma\,,}&{f(x\,,y\,)=f(2a-x\,,y\,)\,,}\\ {\!\!\!D_{1}}&{}\\ {0\,,}&{f(x\,,y\,)=-\,f(2a-x\,,y\,)\,,}\end{array}\!\!\right.\,}\end{array}
$$  

其中 $D_{1}$ 是 $D$ 在 $_{x}=a$ 右侧的部分.  

$\circledcirc$ 若 $D$ 关于 $_{x}$ 轴对称,则  

$$
\iint_{_{D}}f(x\,,y\,)\,\mathrm{d}\sigma=\left\{\!\!\!\begin{array}{l l}{2\!\!\!\iint_{_{D}}f(x\,,y)\mathrm{d}\sigma\,,}&{\,f(x\,,y)=f(x\,,-\,y\,)\,,}\\ {\!\!\!D_{1}}&{}\\ {0\,,}&{\,f(x\,,y)=-\,f(x\,,-\,y\,)\,,}\end{array}\right.
$$  

其中 $D_{\l^{1}}$ 是 $D$ 在 $_{x}$ 轴上侧的部分.  

注1若 $D$ 关于 $y=a(a\neq0)$ 对称,则  

$$
\underset{^{D}}{\iint}f(x\,,y)\,\mathrm{d}\sigma=\left\{\!\!\!\left\{\begin{array}{l l}{2{\displaystyle\!\!\iint}f(x\,,y)\,\mathrm{d}\sigma\,,,}&{f(x\,,,y)=f(x\,,2a-y)\,,}\\ {\!\!\!D_{1}}&{}\\ {\!\!\!0\,,}&{f(x\,,y)=-\,f(x\,,2a-y)\,,}\end{array}\right.\,
$$  

其中 $D_{1}$ 是 $D$ 在 $_{y}=a$ 上侧的部分.  
$\textcircled{3}$ 若 $D$ 关于原点对称，则  

$$
\underset{^D_{D}}{\iint}f(x\,,y)\,\mathrm{d}\sigma=\left\{\begin{array}{l l}{2\!\!\iint_{J}f(x\,,y)\,\mathrm{d}\sigma\,,}&{f(x\,,y)=f(-\,x\,,-\,y)\,,}\\ {\quad D_{1}}&{}\\ {0\,,}&{f(x\,,y)=-\,f(-\,x\,,-\,y)\,,}\end{array}\right.
$$  

其中 $D_{1}$ 是 $D$ 关于原点对称的半个部分.  

$\circled{4}$ 若 $D$ 关于 $_{y}=x$ 对称，则  

$$
\begin{array}{r}{\underset{_{D}}{\iint}f(x\,,y\,)\,\mathrm{d}\sigma=\times\overset{\displaystyle2\!\!\iint_{f}f(x\,,y)\,\mathrm{d}\sigma\,,}{\overset{\displaystyle}{\operatorname*{D}}}\,\,\,\frac{f(x\,,y\,)=f(y\,,x\,)\,,}{}\;\;}\\ {0\,,\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;f(x\,,y\,)=-\,f(y\,,x\,)\,,}\end{array}
$$  

其中 $D_{1}$ 是 $D$ 关于 ${\boldsymbol{y}}={\boldsymbol{x}}$ 对称的半个部分.  

在直角坐标系中，若将 $D$ 中的 $x\cdot y$ 对调后， $D$ 不变，则有  

$$
I=\!\!\!\int_{\stackrel{D}{D}}f(x\,,y\,)\mathrm{d}x\mathrm{d}y=\!\!\!\int_{\stackrel{D}{D}}f(y\,,x\,)\mathrm{d}x\mathrm{d}y.
$$  

】在直角坐标系中，若 $f(x\,,y)+f(y\,,x\,)=a$ ，则  

$$
I={\frac{1}{2}}\!\!\!\iint_{D}\!\!\!\!\!\int(f(x\,,y)+f(y\,,x\,)\!\!\!\,\big]\mathrm{d}x\mathrm{d}y\,\,={\frac{1}{2}}\!\!\!\!\iint_{D}\mathrm{d}x\mathrm{d}y={\frac{a}{2}}S_{D}.
$$  

14.2 设区域 $D=\{(x\,,y\,)\mid x^{2}+y^{2}\leqslant1\}$ ，则 $\iint_{D}(\sin\,x+\cos\,y\,)^{2}\,\mathrm{d}\sigma=_{.}$  

解}应填 $\pmb{\pi}$  

$$
\begin{array}{r l}&{\mathrel{\mathop:}=\iint(\sin^{2}x+\cos^{2}y+2\sin x\cos\ y)\mathrm{d}\sigma}\\ &{\mathrel{\mathop:}=\iint(\sin^{2}x+\cos^{2}y)\mathrm{d}\sigma=\!\!\!\iint(\sin^{2}y+\cos^{2}x)\mathrm{d}\sigma}\\ &{\mathrel{\mathop:}=\frac{1}{2}\!\!\!\iint[(\sin^{2}x+\cos^{2}y)+(\sin^{2}y+\cos^{2}x)]\mathrm{d}\sigma}\\ &{\mathrel{\mathop:}=\frac{1}{2}\!\!\!\iint\!\!2\mathrm{d}\sigma=\pi\cdot1^{2}=\pi.}\end{array}
$$  

# (1）用对称性.  

# (2）用保号性.  

设平面闭区域 $D_{i}(i=1,2,3,4)$ 是由  

$$
L_{1}:x^{2}+y^{2}=1,L_{2}:x^{2}+y^{2}=2,
$$  

$$
L_{3}:x^{2}+2y^{2}=2,L_{4}:2x^{2}+y^{2}=2
$$  
围成的平面区域，记  

$$
I_{i}=\!\!\!\int_{{D_{i}}}\!\left(1-x^{\,2}-{\frac{1}{2}}y^{\,2}\right)\mathrm{d}x\mathrm{d}y\,,
$$  

则$\operatorname*{max}\{I_{1}\,,I_{2}\,,I_{3}\,,I_{4}\}=(\qquad),$  

$(\mathbf{A})I_{1}$ $\left(\operatorname{B}\right)I_{2}$ (C)I 3 (D) I 4  

【解】应选(D).  

曲线 $L_{i}(i=1,2,3,4)$ 如图14-1所示.记被积函数为 $f(x\,,y\,)=1-\left(x^{2}+{\frac{1}{2}}y^{2}\right)$ ,由于 $L_{\downarrow}$  $2x^{2}+y^{2}=2$ ，则 $D_{\downarrow}$ 内部为 $x^{2}+\frac{y^{2}}{2}<1$ ，于是 $D_{4}$ 内部有 $f(x\,,y)>0$ ，而 $D_{+}$ 外部有$f(x\,,y)<0.$  

$\textcircled{1}$ 比较 $I_{\mathrm{~l~}}$ 与 $I_{4}$ ：  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/4f2c403c8b06a5be8567a303bccd120dc1518a83ce1aa4cb55542cc0af421c71.jpg)  
图14-1  

$$
\begin{array}{l}{I_{4}=\!\!\!\iint f(x\,,y)\,\mathrm{d}x\mathrm{d}y=\!\!\!\!\underbrace{\left[\!\!\!\!\int f(x\,,y)\,\mathrm{d}x\mathrm{d}y+\underbrace{\left[\!\!\!\!\int_{D_{4}}f(x\,,y)\,\mathrm{d}x\mathrm{d}y\right.\!\!\!\mathrm{d}x}_{D_{4}-D_{1}}\!\!\!\!\int_{0}f(x\,,y)\,\mathrm{d}x\mathrm{d}y\right.\!\!\!\!}}\\ {\quad=I_{1}+\displaystyle\iint_{D_{4}-D_{1}}f(x\,,y)\,\mathrm{d}x\mathrm{d}y>I_{1}.}\end{array}
$$  

$\circledcirc$ 比较 $I_{2}$ 与 $I_{\ast}$ ：  

$$
\begin{array}{r l}&{I_{2}=\underset{{D_{2}}}{\iint}f(x\,,y)\,\mathrm{d}x\mathrm{d}y=\underset{{D_{4}}}{\iint}f(x\,,y)\,\mathrm{d}x\mathrm{d}y+\underset{{D_{2}}-{D_{4}}}{\iint}f(x\,,y)\,\mathrm{d}x\mathrm{d}y}\\ &{\quad=I_{4}+\underset{{D_{2}}-{D_{4}}}{\iint}f(x\,,y)\,\mathrm{d}x\mathrm{d}y<I_{4}.}\end{array}
$$  

$\textcircled{3}$ 比较 $I_{3}$ 与 $I_{4}$ .如图14-2所示，将 $D_{3}\cdot D_{4}$ 中互不重合的部分分别记为 $D_{31}\,,D_{32}\,,D_{41}\,,D_{42}$ ，则  

$$
\begin{array}{l}{I_{3}=\displaystyle\iint f(x\,,y\,)\,{\mathrm{d}}x{\mathrm{d}}y+\displaystyle\iint f(x\,,y\,)\,{\mathrm{d}}x{\mathrm{d}}y+\displaystyle\iint f(x\,,y\,)\,{\mathrm{d}}x{\mathrm{d}}y}\\ {-\displaystyle\iint f(x\,,y\,)\,{\mathrm{d}}x{\mathrm{d}}y+\displaystyle\iint f(x\,,y\,)\,{\mathrm{d}}x{\mathrm{d}}y+\displaystyle\iint f(x\,,y\,)\,{\mathrm{d}}x{\mathrm{d}}y}\\ {\displaystyle\int_{\mathbb{}_{3}}{\mathrm{d}}_{1}}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/94b167640846a09902f17b30a76e7a484bf758c25b517ff7a873e04de0e19a4b.jpg)  
图14-2  

所以 $\operatorname*{max}\{I_{1}\,,I_{2}\,,I_{3}\,,I_{4}\}=I_{4}$ ,即应选(D).  

例14.4设 $J_{\it{i}}=\iint_{\it{D_{i}}}\sqrt[3]{\it{x}-y}\,\mathrm{d}x\mathrm{d}y\,(i=1,2,3)$ ,其中 $D_{1}=\{(x\,,y)\mid0\!\leqslant\!x\!\leqslant\!1,0\!\leqslant\!y\!\leqslant\!1\}$ ，$D_{2}=\{\,(x\,,y)\,\mid\,0\leqslant x\leqslant1,0\leqslant y\leqslant\sqrt{x}\,\}\,,D_{3}=\{\,(x\,,y)\,\mid\,0\leqslant x\leqslant1,x\leqslant2\,\}$ ,则( ). $(\mathrm{A})J_{1}<J_{2}<J_{3}$ $\begin{array}{r}{(\mathrm{B})J_{3}<J_{1}<J_{2}}\\ {(\mathrm{D})J_{2}<J_{1}<J_{3}}\end{array}$ $(\mathrm{C})J_{2}<J_{3}<J_{\mathrm{~l~}}$  

【解】应选(B).  

如图14-3（a）所示， $D_{\mathrm{~l~}}$ 被直线 $y\ =x$ 分成 $D_{\scriptscriptstyle{11}}$ 和 $D_{\scriptscriptstyle{12}}$ 两部分，故 $\iint_{_{D_{1}}}{\sqrt[3]{x-y}}\,\mathrm{d}x\mathrm{d}y\;=$  $\iint_{D_{11}+D_{12}}\sqrt[3]{x-y}\,\mathrm{d}x\mathrm{d}y$ ,由于 $\sqrt[3]{x-y}=-\sqrt[3]{y-x}$ ,故由普通对称性，有 $J_{\textrm{l}}\!=\!\!\iint_{\mathbf{\Omega}_{D_{\textrm{l}}}}\!\!\!\sqrt[3]{x-y}\,\mathrm{d}x\,\mathrm{d}y=0.$  
如图14-3(b）所示，作辅助线 ${\boldsymbol{y}}={\boldsymbol{x}}^{\,2}$ ，将 $D_{2}$ 分为 $D_{21}$ 和 $D_{22}$ 两部分，由普通对称性知， $\iint_{D_{21}}^{3}\!\!\sqrt[3]{x-y}\,\mathrm{d}x\mathrm{d}y=0$ 而在 $D_{22}$ 上， $\sqrt[3]{x-y}\geq0$ ,由保号性知，  

$$
J_{\mathit{z}}=\!\!\!\int_{\mathit{\Pi}_{D_{2}}}^{\mathit{3}}\!\!\!\sqrt{x-y}\;\mathrm{d}x\;\mathrm{d}y=\!\!\underbrace{\!\!\iint_{\mathit{\Pi}_{D_{2}}}^{\mathit{3}}\!\!\!\sqrt{x-y}\;\mathrm{d}x\;\mathrm{d}y}_{\mathit{\Pi}_{\mathrm{2}\mathrm{2}}}>0.
$$  

如图14-3（c）所示，作辅助线 $y={\sqrt{x\,}}$ ，将 $D_{3}$ 分为 $D_{31}$ 和 $D_{32}$ 两部分，由普通对称性知， $\iint_{32}\sqrt[3]{x-y}\,\mathrm{d}x\mathrm{d}y=0.$ 而在 $D_{31}$ 上， $\sqrt[3]{x-y}\leqslant0$ ,由保号性知，  

$$
J_{\mathbf{\varepsilon}_{3}}=\!\!\!\int_{\mathbf{\varepsilon}_{D_{3}}}^{\mathbf{\varepsilon}_{3}}\!\!\!\sqrt{x-y}\:\mathrm{d}x\:\mathrm{d}y=\!\!\!\int_{\mathbf{\varepsilon}_{D_{31}}}^{\mathbf{\varepsilon}_{3}}\!\!\!\sqrt{x-y}\:\mathrm{d}x\:\mathrm{d}y<0.
$$  

综上， ${J_{3}}<{J_{1}}<{J_{2}}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/0660a327b9a8c4d36e3150456d8a76cff9c7cf4db64d962e7708efdfe9d64cc6.jpg)  
图14-3  

# 5.二重积分中值定理  

设函数 $f(x\,,y\,)$ 在闭区域 $D$ 上连续， $\sigma$ 是 $D$ 的面积,则在 $D$ 上至少存在一点 $(\xi,\eta)$ ,使得  

$$
\iint_{D}f(\boldsymbol{x}\,,y\,)\,\mathrm{d}\sigma=f(\boldsymbol{\xi}\,,\eta)\sigma\,.
$$  

例14.5设  

$$
D_{t}=\{\,(x\,,y\,)\,\mid\,2x^{\,2}+3y^{\,2}\leqslant6t\,\}\,(t>0)\,,
$$  

$$
f(x\,,y)=\!\!\left\{\!\!{\frac{\sqrt[3]{1-x\,y}}{\mathrm{e}^{x y}-1}}\,,\,\,(x\,,y)\neq(0\,,0)\,,\,
$$  

为连续函数，令 $F(t)=\underset{\b{D}_{t}}{\iint}f(x\,,y\,)\,\mathrm{d}x\mathrm{d}y$ ，则 $F^{\prime}.\left(0\right)=.$  

【 解】应填 $-\,{\frac{{\sqrt{6}}\,\pi}{3}}$ 积分区域 $\boldsymbol{D}_{\boldsymbol{\epsilon}}$ 的面积为 $A=\sqrt{6}\,\pi t$ .因为 $f(x\,,y\,)$ 为连续函数，所以  

$$
=f(0,0)=\operatorname*{lim}_{(x,y)\to(0,0)}f(x\,,y)=\operatorname*{lim}_{(x,y)\to(0,0)}{\frac{\sqrt[{3}]{1-x y}-1}{\mathrm{e}^{x y}-1}}=\operatorname*{lim}_{(x,y)\to(0,0)}{\frac{-{\frac{1}{3}}x y}{x y}}=-{\frac{1}{3}}.
$$  

由二重积分中值定理,存在 $(\xi,\eta)\in D_{\prime}$ ，使得  
# 张等高等数学18班  

$$
F(t)=\!\!\!\int_{D_{t}}\!\!\!f(x\,,y\,)\mathrm{d}x\mathrm{d}y=\!\sqrt{6}\,\pi t\,f(\xi\,,\eta).
$$  

于是，  

$$
\begin{array}{l}{{F_{+}^{\prime}\,\left(0\right)=\displaystyle\operatorname*{lim}_{t\rightarrow0^{+}}\frac{F(t)-F(0)}{t-0}=\displaystyle\operatorname*{lim}_{t\rightarrow0^{+}}\frac{\sqrt{6}\,\pi t\,f(\xi\,,\eta)}{t}=\operatorname*{lim}_{t\rightarrow0^{+}}\sqrt{6}\,\pi\,f(\xi\,,\eta)}}\\ {{\qquad\qquad=\sqrt{6}\,\pi\,f(0,0)=-\displaystyle\frac{\sqrt{6}\,\pi}{3}.}}\end{array}
$$  

【注】此题的被积函数命制成具体函数，但 $\iint_{\mathbb{D}_{t}}f(x\,,y\,)\,\mathrm{d}\sigma$ 难以计算，故考虑利用二重积分中值定理来处理.同理，若被积函数命制成抽象函数，也可以考虑利用二重积分中值定理来处理.如  

设 $f(x\,,y\,)$ 具有二阶连续偏导数，  

$$
D_{t}=\left\{(x\;,y\,)\;\left|\;\right.\right.\circ\leqslant x\leqslant t\,,0\leqslant y\leqslant t\,\right\},
$$  

令$F(t)=\underset{\^{D_{t}}}{\iint}f_{_{x y}}^{\prime\prime}(x\mathrm{~,~}y)\,\mathrm{d}x\mathrm{d}y$ ，求 $F_{\mathrm{~+~}}^{\prime}(0)$  

解  

$$
F_{+}^{\prime}(0)=\operatorname*{lim}_{t\rightarrow0^{+}}\frac{F(t)-F(0)}{t-0}\!=\!\operatorname*{lim}_{t\rightarrow0^{+}}\frac{\displaystyle\iint f_{x y}^{\prime\prime}(x\,,y)\,\mathrm{d}x\mathrm{d}y}{t}\,}\\ {\frac{\sec^{\prime}\!+\!\Re\tilde{\kappa}\Re\equiv\displaystyle\operatorname*{lim}_{t\rightarrow0^{+}}\frac{f_{x y}^{\prime\prime}(\hat{\xi}\,,\eta)\,\cdot\,t^{2}}{t}\!-\!\operatorname*{lim}_{t\rightarrow0^{+}}\!t\cdot f_{x y}^{\prime\prime}(\hat{\xi}\,,\eta)}{\displaystyle t\rightarrow0^{+}}=\!0.}\end{array}
$$  

# 6. 周期性  

若化为累次积分后，一元积分有用周期性的机会，则可化简计算.  

刚 14. 0 =,π,π, $I=\iint_{_{D}}1$ cos 【解】 $I\!=\!\!\!\int_{0}^{\pi}\!\mathrm{d}x\!\int_{0}^{\pi}\mid\cos\,(x+y)\mid\mathrm{d}y$ ,注意到|cos $(a+y)|$ 是|cos $_{y\mathrm{~}}\vert$ 的水平平移，cos $_y$ —的周期为 $\pi$ ，故 $\int_{0}^{\pi}1$ cos $(x+y)\mid\mathrm{d}y=\int_{0}^{\pi}\mid$ cos $y\ |\ \deg=2$ ,于是 $I=\int_{0}^{\pi}\!2\mathrm{d}x=2\pi$  

【注】（1）充分利用被积函数的性质，得出了此题如此简捷精彩的解法，可见基本功的重要性.（2）（仅数学一）若将问题升维至三重积分，设  

$I=\coprod_{a}\mid$ cos $\mid(x+y+z)\mid\,\mathrm{d}v\,,\varOmega=\mid(\,x\,,y\,,z\,)\mid\,0\leqslant x\leqslant\pi\,,0\leqslant y\leqslant\pi\,,0\leqslant z\leqslant\pi\}\,,$ 计算 $\boldsymbol{I}$ ,方法完全一样.  

$$
I=\!\!\int_{0}^{\pi}\!\mathrm{d}x\!\int_{0}^{\pi}\!\mathrm{d}y\!\int_{0}^{\pi}\mid\cos\ (x+y+z)\mid\mathrm{d}z.
$$  

注意到|cos $(a+z)|$ 是|cos $_z$ 一的水平平移，故  

$$
\int_{0}^{\pi}\mid\cos\;(x+y+z)\mid\mathrm{d}z=\!\!\int_{0}^{\pi}\mid\cos\;z\mid\,\mathrm{d}z=2\,,I=\!\!\int_{0}^{\pi}\!\!\mathrm{d}x\!\int_{0}^{\pi}\!\!2\mathrm{d}y=2\pi^{2}.
$$  
# 计算  

1.直角坐标系下的计算法  

在直角坐标系下，按照积分次序的不同，一般将二重积分的计算分为两种情况。  

$\underset{D}{\iint}f(x\,,y)\mathrm{d}\pmb{\sigma}=\!\int_{a}^{b}\mathrm{d}x\!\int_{\varphi_{1}(x)}^{\varphi_{2}(x)}f(x\,,y)\mathrm{d}y$ ,其中 $D$ 如图14-4(a）所示，为 $X$ 型区域： $\varphi_{1}(x)\leqslant$ $y\leqslant\varphi_{2}(x),a\leqslant x\leqslant b\,;$  

$\underset{D}{\iint}f(x\,,y\,)\,\mathrm{d}\sigma=\!\!\!\int_{c}^{d}\mathrm{d}y\!\!\int_{\psi_{1}(y)}^{\psi_{2}(y)}f(x\,,y\,)\,\mathrm{d}x$ 其中 $D$ 如图14-4(b）所示,为 $Y$ 型区域： $\psi_{1}(y)\leqslant$ $x\leqslant\psi_{2}(y)\,,c\leqslant y\leqslant d$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b0f5a38877c351a0bcc6200963c3eb038189476cfcc8337e3bc8f75b82e23678.jpg)  
图14-4  

【注】下限须小于上限.  

$^{2,}$ 极坐标系下的计算法  

在极坐标系下，按照积分区域与极点位置关系的不同，一般将二重积分的计算分为三种情况，如图14-5所示。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b33964c1363326696d2e3370e2dcbe3c3bdf1f9fe05fb487f43e7275438d9a76.jpg)  
图14-5  

(1 $\iiint_{D}f(x,y)\,\mathrm{d}\sigma=\int_{\alpha}^{\beta}\!\mathrm{d}\theta{\int_{\,r_{1}(\theta)}^{r_{2}(\theta)}f(r\cos\ \theta,r\sin\ \theta)}\,r\mathrm{d}r\mathrm{(}\ \$ 极点 $O$ 在区域 $D$ 外部,如图 14-5(a)所示)；(2) $\iiint_{D}f(x\,,y)\,\mathrm{d}\sigma=\int_{\alpha}^{\beta}\!\mathrm{d}\theta{\int_{0}^{r(\theta)}f(r\cos\theta,r\sin\theta)\,r\,\mathrm{d}r}\,\mathrm{d}\theta$ （极点 $O$ 在区域 $D$ 边界上,如图14-5(b) 所示)；（3） $\iiint_{D}f(x,y)\,\mathrm{d}\sigma=\int_{0}^{2\pi}\!\mathrm{d}\theta{\int_{0}^{r(\theta)}f(r\cos\ \theta,r\sin\ \theta)r\mathrm{d}r}\mathrm{(}$ 极点 $O$ 在区域 $D$ 内部，如图14-5(c)所示).  
【注】极坐标系与直角坐标系选择的一般原则：  

一般来说，给出一个二重积分.  

$\textcircled{1}$ 看被积函数是否为 $f(x^{2}+y^{2}),f\Big(\frac{y}{x}\Big)\,,f\Big(\frac{x}{y}\Big)$ 等形式;  
 $\circledcirc$ 看积分区域是否为圆或者圆的一部分.  
如果 $\textcircled{1}$ ， $\circledcirc$ 至少满足其中之一，那么优先选用极坐标系.否则，就优先考虑直角坐标系。  

# 3.极坐标系与直角坐标系的互相转化  

一是用好 $\begin{array}{r}{|x=r\cos\,\theta\,,\ }\\ {|y=r\sin\,\theta\,}\end{array}$ 这个公式；二是画出积分区域 $D$ 的图形，做好上、下限的转化，  

【注】(1)关于积分区域 $D$  

图形变换直角系方程给出关于积分区域 $D$ 极坐标方程给出参数方程给出动区域（含其他参数）  

# (2) 关于被积函数 $f(x\,,y\,)$  

分段函数（含绝对值）最大、最小值函数取整函数符号函数关于被积函数f(x,y)抽象函数复合函数 $f(u),u\mathop{\zeta^{x}}_{y}$ 偏导函数 $f_{\scriptscriptstyle{x y}}^{\prime\prime}(x,y)$  

（3）换元法  

二重积分亦有如定积分一脉相承的换元法,有时很有用,现介绍于此,供参考,若能够用上，可直接使用，不必证明。  

先回顾一元函数积分换元法，见“ $\textcircled{1}$ ”，再看二重积分换元法，见“ $\textcircled{2}"$ $\mathbb{D}\!\!\int_{a}^{b}f(x\left)\,\mathrm{d}x\,\,\frac{x=\varphi(t)}{\phantom{b}}\!\int_{a}^{\beta}f\big[\varphi(t)\big]\varphi^{\prime}(t)\,\mathrm{d}t.$   
a. $f(x)\rightarrow f{\bigl[}\varphi(t){\bigr]}$ $\int_{a}^{b}\rightarrow\int_{a}^{\beta}$ $\therefore\mathrm{d}x\rightarrow\varphi^{\prime}(t)\mathrm{d}t$   
注意： $x=\varphi(t)$ 单调，存在一阶连续导数.  
$\mathcal{Q}\underset{b_{x y}}{\iint}f(x\,,y)\,\mathrm{d}x\mathrm{d}y\ \frac{\,x=x\left(u,v\right)}{y=y\left(u,v\right)}\left\iint_{x_{u v}}f\Big[x\left(u\,,v\right),y\left(u\,,v\right)\Big]\left|\frac{\partial(x\,,y)}{\partial(u\,,v)}\right|\,\mathrm{d}u\mathrm{d}v.$   
a. $f(x\,,y)\rightarrow f{\bigl[}x\,(u\,,v)\,,y\,(u\,,v){\bigr]},$   
$\mathsf{b}.\iint\displaylimits_{\Sigma_{x y}}\to\iint\displaylimits_{u v}\$   
C$.\;\mathrm{d}x\mathrm{d}y\rightarrow\bigg|\frac{\partial(x\,,y\,)}{\partial(u\,,\nu)}\bigg|\,\mathrm{d}u\mathrm{d}v.$   
注意：其中 $\left\{x=x\left(u\,,v\right),\right.$ 是 $(x\,,y\,)$ 面到 $(\boldsymbol{u}\,,\boldsymbol{v})$ 面的一对一映射， $x=x(u\,,v)\,,y\,\!\Rightarrow\!(u\,,v)$ 存  
在一阶连续偏导数。 $\left|\frac{\partial(x\,,y\,)}{\partial(u\,,v\,)}=\left|\frac{\partial x}{\partial u}\quad\frac{\partial x}{\partial v}\right|\neq0.$   
另外，令 $\begin{array}{r}{{\left\langle x=r\cos\theta\,,\right.}}\\ {{\left.y=r\sin\theta\,,\right.}}\end{array}$ 则$\iint_{x_{y}}f(x\,,y\,)\,\mathrm{d}x\,\mathrm{d}y=\!\!\!\!\iint_{r_{\theta}}f(r\cos\theta\,,r\sin\theta\,)\left|\begin{array}{l l}{\displaystyle\left|\frac{\partial x}{\partial r}\&{\frac{\partial x}{\partial\theta}}\\ {\displaystyle\left|\frac{\partial y}{\partial r}\&{\frac{\partial y}{\partial\theta}}\right|}\end{array}\right|\mathrm{d}r\mathrm{d}\theta$ $\left.=\!\!\!\iint_{r\phi}f(r\cos\theta,r\sin\theta)\left|\begin{array}{l l}{\left|\cos\theta\right.}&{-r\sin\theta}\\ {\left|\sin\theta\right.}&{\left.r\cos\theta\right|}\end{array}\right|\,\right|\,\mathrm{d}r\mathrm{d}\theta\,\!=\!\!\!\iint_{r\phi}f(r\cos\theta,r\sin\theta)\,r\,\mathrm{d}r\mathrm{d}\theta.$  
这就是直角坐标系到极坐标系的换元过程  

还有一个三重积分的换元法（仅数学一），与上述中“ $\textcircled{1}$  $\circledcirc$ ”一脉相承，写在后面的第18讲的三重积分处，供参考.  

例 14. 7设 $D$ 为曲线 $\begin{array}{l}{\displaystyle{x=\cos^{3}t\,,}}\\ {\displaystyle{y=\sin^{3}t}}\end{array}$ 与坐标轴所围有界区域在第一象限的部分，则  

$$
\iint_{D}(\sqrt{x}-\sqrt{y}+1)\,\mathrm{d}\sigma=-\frac{\,}{}\cdot
$$  

解】应填 $\frac{3\pi}{32}$  

如图14-6所示， $D$ 关于 $y=x$ 对称，则  

$$
\iint_{D}(\sqrt{x}-\sqrt{y\,}\,)\,\mathrm{d}\sigma=\!\!\int_{D}(\sqrt{y\,}-\sqrt{x\,}\,)\,\mathrm{d}\sigma\,,
$$  

故  

$$
\underset{D}{\iint}(\sqrt{x}-\sqrt{y}\,)\,\mathrm{d}\sigma=\frac{1}{2}\underset{D}{\iint}(\sqrt{x}-\sqrt{y}\,+\sqrt{y}-\sqrt{x}\,)\,\mathrm{d}\sigma=0\,,
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/eefbe2720f7ab840e8979698d5160bd4d1d0074f5eb62a141bd855e239853fff.jpg)  
图14-6  
比亨高等数学18洲  

$$
\begin{array}{l}{{\mathfrak{c}}_{=}\displaystyle\!\!\int\!\!\mathrm{d}\sigma=\!\!\!\int_{0}^{1}\!\mathrm{d}x\!\left\lbrack\!\!\begin{array}{l}{{f^{(x)}\,\mathrm{d}y}}\\ {{0}}\end{array}\!\!\right\rbrack=\!\!\int_{0}^{1}\!\!\!\int(x)\!\mathrm{d}x=\!\!\!\int_{0}^{1}\!\!\!\int(t)\,\mathrm{d}x\!\!\!\!\!}}\\ {{\phantom{m}}_{=}\!\!\!\int_{\frac{x}{2}}^{0}\!\sin^{3}t\,\mathrm{d}(\cos^{3}t)=\!\!\!\int_{\frac{x}{2}}^{0}\!\!\sin^{3}t\,\cdot\,3\cos^{2}t\,\cdot\,(-\sin t)\,\mathrm{d}t}\\ {{\phantom{m}}_{=}\displaystyle3\!\!\left\lbrack\!\frac{\dot{\pi}}{0}\sin^{4}t\,(1-\sin^{2}t)\,\mathrm{d}t}\\ {{\phantom{m}}_{=}\displaystyle3\cdot\left(\frac{3}{4}\cdot\frac{1}{2}\cdot\frac{\pi}{2}-\frac{5}{6}\cdot\frac{3}{4}\cdot\frac{1}{2}\cdot\frac{\pi}{2}\right)\!\!-\!\frac{3\pi}{32}.}\end{array}
$$  

例 14. 8设平面区域 $D=\{(x\;,y\;)\;|\;{-}1<x<1,-1<y<1\}$ ， $[x]$ 表示不超过 $_{x}$ 的最大整数,则 $\|\!\!\int_{\cal D}\!\!\operatorname*{max}\{[x\,]\,,y\,\}\,\mathrm{d}x\mathrm{d}y=\!\!\!\phantom{.}$  

【解】应填 $\frac{1}{2}$  

依题意， $,[x\,]=\Bigl\{{-1,\quad-1<x<0}\,,\quad$ 进而  $\begin{array}{r}{\operatorname*{max}\{[x\,],y\}=\Big\{\!\!y\,,\quad\!-1\!<x<0\,,-1\!<y<1}\\ {0\,,\quad0\leqslant x<1,-1\!<y<0.}\end{array}$ 或 $0\leqslant x<1,0\leqslant y<1$ ，  
因此，原式 $=\!\!\int_{-1}^{\circ}\!\mathrm{d}x\int_{-1}^{1}y\,\mathrm{d}y+\int_{0}^{1}\!\mathrm{d}x\int_{0}^{1}\!y\,\mathrm{d}y={\frac{1}{2}}.$  

例 14. 9设 $f(t)=\iint\displaylimits_{x^{2}+y^{2}\leqslant t^{2}}x\left[1+\frac{f(\sqrt{x^{2}+y^{2}})}{x^{2}+y^{2}}\right]\mathrm{d}x\mathrm{d}y$ ,其中 $x\geqslant0,y\geqslant0,t>0$ ：  

（1）求 $f(t)$ 的表达式；  

（2）求极限 $\operatorname*{lim}_{x\to0^{+}}{\frac{f(x)}{\displaystyle\int_{0}^{x}(\mathbf{e}-\mathbf{e}^{\cos\iota})\,\mathrm{d}t}}$  

$$
\begin{array}{l}{{\displaystyle(1)\,f(t)=\iint_{x^{2}+y^{2}<t^{2}}x\left[1+\frac{f(\sqrt{x^{2}+y^{2}}\,)}{x^{2}+y^{2}}\right]\mathrm{d}x\mathrm{d}y=\int_{0}^{\frac{x}{2}}\mathrm{d}\theta{\displaystyle\int_{0}^{t}r\cos\theta\left[1+\frac{f(r)}{r^{2}}\right]}\cdot r\mathrm{d}x\mathrm{d}y=}}\\ {{\displaystyle=\int_{0}^{\frac{x}{2}}\cos\,\theta\mathrm{d}\theta{\displaystyle\int_{0}^{t}[r^{2}+f(r)]\mathrm{d}r=\frac{t^{3}}{3}+\displaystyle\int_{0}^{t}f(r)\mathrm{d}r\,},}}\end{array}
$$  

即$f(t)=\frac{t^{3}}{3}+\int_{0}^{t}f(r)\mathrm{d}r$ ,且 $f(0)=0$  

上式两端对 $t$ 求导，得 $f^{\prime}(t)=t^{2}+f(t)$ ,即 $f^{\prime}(t)-f(t)=t^{2}$ ,解得  

$$
f(t)=2\mathbf{e}^{\prime}-t^{2}-2t-2(t>0)
$$  

$$
\begin{array}{r l}&{\underset{x\to0^{+}}{\operatorname*{lim}}\,\frac{f(x\,)}{\displaystyle\int_{0}^{x}\left(\mathbf{e}-\mathbf{e}^{\cos\iota}\right)\mathsf{d}t}=\underset{x\to0^{+}}{\operatorname*{lim}}\,\frac{2\mathbf{e}^{x}-x^{2}-2x-2}{\displaystyle\int_{0}^{x}\left(\mathbf{e}-\mathbf{e}^{\cos\iota}\right)\mathsf{d}t}}\\ &{\qquad\qquad\qquad\qquad\qquad\qquad\qquad=\underset{x\to0^{+}}{\operatorname*{lim}}\,\frac{2\mathbf{e}^{x}-2x-2}{\displaystyle\int_{0}^{x}-\mathbf{e}^{\cos x}}=\frac{2}{\mathbf{e}}\operatorname*{lim}_{x\to0^{+}}\frac{\mathbf{e}^{x}-x-1}{1-\mathbf{e}^{\cos x-1}}}\end{array}
$$  
$$
=\frac{2}{{\tt e}_{\tau\rightarrow0}}\operatorname*{lim}_{=}\frac{1+x+\frac{1}{2}x^{2}+o\left(x^{2}\right)-x-1}{1-\cos x}=\frac{2}{{\tt e}}.
$$  

例 14. 10设  

$$
D=\left\{(x\,,y)\,\mid\,4x^{\,2}+y^{\,2}<1\,,x\,\geqslant0\,,y\geqslant0\right\},
$$  

则积分 $I=\!\!\!\iint_{_D}(1-12x^{\,2}-y^{\,2}\,)\,\mathrm{d}x\mathrm{d}y=\!\!\!\!\!\!\!-\!\!\!\!\!\!\!-\!\!\!\!\!\!\!-\!\!\!\!\!\!\!\!-\!\!\!\!\!\!\!\!-\!\!\!\!\!\!\!\!\int_{_D}}.$  

解】应填0.  

$$
\begin{array}{l}{\displaystyle I=\!\!\int_{\,0}^{\frac{\pi}{2}}\!\mathrm{d}\theta\!\int_{\,0}^{1}(1-r^{2}-2r^{2}\cos^{2}\theta)\left.\frac{r}{2}\mathrm{d}r\right.\quad\left|\frac{\phi\!\gamma}{\hat{c}\!\gamma}\!\!\!}&{\left.\frac{\phi\!\gamma}{\hat{c}\!\theta}\right|}\\ {\displaystyle\quad=\!\frac{1}{2}\!\!\int_{\,0}^{\frac{\pi}{2}}\!\mathrm{d}\theta\!\int_{\,0}^{1}(1-r^{2})r\,\mathrm{d}r-\!\int_{\,0}^{\frac{\pi}{2}}\!\cos^{2}\theta\mathrm{d}\theta\!\int_{\,0}^{1}\!r^{3}\,\mathrm{d}r=\!\frac{\pi}{16}-\frac{\pi}{16}=0.}\end{array}
$$  

例 14. 11设有界区域 $D$ 是由圆 $x^{2}+y^{2}=1$ 和直线 $y=x$ 以及 $_{x}$ 轴所围图形在第一象限的部分，计算二重积分 $\iint_{D}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!(x^{+}\!\!\!+\!\!\!y)^{2}\left(x^{\,2}-y^{\,2}\,\right)\mathrm{d}x\mathrm{d}y.$  

法一在极坐标系中，区域 $D$ 可表示为  

$$
\left\{(r\,,\theta)\ |\ 0\leqslant r\leqslant1,0\leqslant\theta\leqslant\frac{\pi}{4}\right\}\,,
$$  

所以  

$\iint_{n}\mathbf{e}^{(x+y)^{2}}\,(x^{\,2}-y^{\,2})\,\mathrm{d}x\mathrm{d}y=\int_{0}^{\frac{x}{4}}\mathrm{d}\theta\int_{0}^{1}\mathbf{e}^{r^{2}(\sin\theta+\cos\theta)^{2}}{r^{\,3}}\,(\cos^{2}\!\theta-\sin^{2}\!\theta\,)\,\mathrm{d}r$ D$\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\$ $:\frac{1}{2}\!\int_{0}^{1}r\,\left[\mathrm{e}^{r^{2}(\sin\theta+\cos\theta)^{2}}\left|\frac{\star}{0}\right]\mathrm{d}r=\frac{1}{2}\!\int_{0}^{1}r\,(\mathrm{e}^{2r^{2}}-\mathrm{e}^{r^{2}}\,)\mathrm{d}r=\frac{(\mathrm{e}-1)^{2}}{8}.$  

法二 $\begin{array}{r}{\binom{u=x-y}{v=x+y},\qquad\qquad\qquad\qquad\qquad\qquad}\\ {\quad\quad v=x+y\,,}\end{array}$ 因为 $D$  $\Biggl\{x=\frac{u+v}2,\atop(u\,,v)\in\,{\cal D}_{u v}$ ，所以$y={\frac{v-u}{2}}$ $\begin{array}{r l}&{\displaystyle\iint_{0}\!\!\mathrm{e}^{(x+y)^{2}}\,(x^{2}-y^{2})\,\mathrm{d}x\,\mathrm{d}y=\!\!\iint_{0}\,\frac{1}{2}\,\mathrm{e}^{\mathrm{v}^{2}}\,u\upsilon\,\mathrm{d}u\,\mathrm{d}v=\frac{1}{2}\!\!\int_{0}^{1}\!u\,\mathrm{d}u\!\int_{u}^{\sqrt{2-u^{2}}}\!\!\mathrm{e}^{\mathrm{v}^{2}}\,v\,\mathrm{d}v}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=\frac{1}{4}\!\!\int_{0}^{1}(\mathrm{e}^{2-u^{2}}-\mathrm{e}^{u^{2}}\,)u\mathrm{d}u=\frac{(\mathrm{e}-1)^{2}}{8}.}\end{array}$  
# 第15讲微分方程  

一阶微分方程的求解  

能写成 ${\frac{1}{y^{\prime}}}=f\!\left({\frac{x}{y}}\right)$ 能写成 $y^{\prime}+p\left(x\,\right)y=q\left(x\,\right)$ 能写成 $y^{\prime}+\phi(x\,)y=q(x\,)y^{n}(n\neq0,1)$ (伯努利方程)(仅数学一) 能写成 $y^{\prime\prime}=f(\v{r},\v{y}^{\prime})$   
二阶可降阶微分方程的求解（仅数学一、数学二）能写成 $y^{\prime\prime}=f(\,y\,,y^{\prime})$ 能写成 $y^{\prime\prime}+\phi y^{\prime}+q y=f(x)$ 能写成 $y^{\prime\prime}+p y^{\prime}+q y=f_{1}(x\,)+f_{2}(x\,)$   
高阶常系数线性微分方程的求解能写成 $x^{\,2}y^{\prime\prime}+p x y^{\,\prime}+q y=\,f(x\,)$ (欧拉方程)(仅数学一)  $_n$ 阶常系数齐次线性微分方程的解用求导公式逆用来换元  
用换元法求解微分方程用自变量、因变量或 $x\cdot y$ 地位互换来换元用极限、导数或积分等式建方程用曲线切线斜率用两曲线 $f(x)$ 与 $_{g}(x)$ 的公切线斜率用截距 用面积用体积   
应用题用几何应用建方程用平均值用弧长(仅数学一、数学二)用侧面积(仅数学一、数学二)用曲率(仅数学一、数学二)用形心(仅数学一、数学二) 用变化率建方程  

齐次差分方程的通解差分方程(仅数学三）非齐次差分方程的解  
# 含有未知函数 $y=y\left(x\,\right)$ 的导数或微分的方程叫微分方程，  

一一阶微分方程的求解  

若是“ $y^{\prime\,,}$ 或“ $\mathrm{d}y=\cdots\mathrm{d}x$ ”，则  

1.可分离变量型（或可换元化为它）  
 $\textcircled{1}$ 能写成 $y^{\prime}=f(x)\cdot g(y)$   
分离变量写成 $\frac{\mathrm{d}y}{g\left(y\,\right)}=f(x\,)\mathrm{d}x$ ,两边同时积分 $\int\frac{\mathrm{d}y}{g\left(y\,\right)}=\int f(x\,)\,\mathrm{d}x\,.$  

$\circledcirc$ 能写成 $y^{\prime}=f(a x+b y+c)$  

令 $u=a x+b y+c$ ，则 $u^{\prime}=a+b f(\,u\,)$ ，分离变量写成 $\frac{\mathrm{d}u}{a+b f(u)}=\mathrm{d}x$ ，两边同时积分$\int_{a+b f(u)}\!=\!\int\!\mathrm{d}x\,.$  

2. 齐次型  

$\textcircled{1}$ 能写成 $y^{\prime}=f\left({\frac{y}{x}}\right)$  

令 ${\frac{y}{x}}=u$ ,换元后分离变量，即 $y=u x\;,{\frac{\mathrm{d}y}{\mathrm{d}x}}=u\,+\,x\;\,{\frac{\mathrm{d}u}{\mathrm{d}x}}$ ，原方程化为 $x\ {\frac{\mathrm{d}u}{\mathrm{d}x}}+u=f(\,u\,)$ ， $\frac{\mathrm{d}u}{f(u)-u}\!=\!\frac{\mathrm{d}x}{x}$ ，两边同时积分 $\int\frac{\mathrm{d}u}{f(u)-u}=\int\frac{\mathrm{d}x}{x}$  

$\circledcirc$ 能写成 ${\frac{1}{y^{\prime}}}=f\!\left({\frac{x}{y}}\right)$  

令$\frac{x}{y}=u$ ,换元后分离变量,即 $x=u y\,,{\frac{\mathrm{d}x}{\mathrm{d}y}}=u+y\,{\frac{\mathrm{d}u}{\mathrm{d}y}}$ ，原方程化为 $y\,{\frac{\mathrm{d}u}{\mathrm{d}y}}+u=\,f(u),{\frac{\mathrm{d}u}{f(u)-u}}=$  $\frac{\mathrm{d}{\boldsymbol{y}}}{\boldsymbol{y}}$ ，两边同时积分 $\int\frac{\mathrm{d}u}{f(u)-u}=\int\frac{\mathrm{d}y}{y}$  

：一阶线性型（或可换元化为它）  

$\textcircled{1}$ 能写成 $y^{\prime}+p(x)y=q(x)$ ，则  

$$
y=\mathrm{e}^{-\left\lceil{\hat{\boldsymbol{r}}^{(\boldsymbol{x})\uppercase{\romannumeral1}}}\right\rceil}\mathrm{e}^{\int_{\mathbf{\}}\!\!\int_{\mathbf{\}}\!\!\int_{\mathbf{\}}\!\!\left({\boldsymbol{x}}\right)\mathrm{d}\boldsymbol{x}}\,\cdot\,q\left({\boldsymbol{x}}\right)\mathrm{d}{\boldsymbol{x}}\,+C\right].
$$  

[注]由于 $\int\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\$ 与 $\int\!q\left(\boldsymbol{x}\right)\mathrm{e}^{\int_{0}^{\int_{\mathbb{D}^{(\chi)}}\!\mathrm{d}\boldsymbol{x}}}\,\mathrm{d}\boldsymbol{x}$ 均应理解为某一不含任意常数的原函数,故公式法亦可写成 $y=\mathrm{e}^{-\int_{x_{0}}^{x}{\dot{p}(t)\mathrm{d}t}}\left[\int_{x_{0}}^{x}{\boldsymbol{q}(t)\mathrm{e}^{\int_{x_{0}}^{t}{\dot{p}(s)\mathrm{d}s}}\mathrm{d}t}+C\right]$ ，这里的 $\scriptstyle x\,_{0}$ 在题设未提出定值要求时，可按方便解题的原则来取。此写法在研究解的性质时颇为有用。  
# 限等高等数学18讲  

$\circledcirc$ 能写成 $y^{\prime}+\phi(x)y=q(x)y^{\prime}(n\neq0,1)$ (伯努利方程)(仅数学一).  

a.先变形为 $y^{-n}\cdot y^{\prime}+p(x)y^{1-n}=q(x)$  

b.令 $z=y^{1-n}$ ,得 ${\frac{\mathrm{d}z}{\mathrm{d}x}}=(1-n\,)\,y\,^{-n}\ {\frac{\mathrm{d}y}{\mathrm{d}x}}$ 则${\frac{1}{1-n}}\,{\frac{\mathrm{d}z}{\mathrm{d}x}}+p\,(x\,)z=q\,(x\,)$  

c.解此一阶线性微分方程即可.  

例 15. 1微分方程 $x+y y^{\prime}=y-x y^{\prime}$ 的通解为  

【解】应填arctan ${\frac{y}{x}}+{\frac{1}{2}}\mathrm{ln}(x^{2}+y^{2})=C$ ,其中 $C$ 为任意常数.  

由题中所给的微分方程，可得  

$$
y^{\prime}=\frac{y-x}{y+x}=\frac{\frac{y}{x}-1}{\frac{y}{x}+1},
$$  

${\frac{y}{x}}=u$ .则 ${\frac{\mathrm{{d}}y}{\mathrm{{d}}x}}=u+x\ {\frac{\mathrm{{d}}u}{\mathrm{{d}}x}}$ ,代人上述方程并分离变量得  

$$
\frac{1+u}{1+u^{2}}\mathrm{d}u=-\,\frac{1}{x}\mathrm{d}x\:,
$$  

两边积分得  

则微分方程的通解为 arctan ${\frac{y}{x}}+{\frac{1}{2}}\mathrm{ln}(x^{2}+y^{2})=C$ ,其中 $c$ 为任意常数.  

例 15. 2设 $f(x)$ 在 $[0,+\infty)$ 上连续且有水平渐近线 $y=b\neq0$ ，则（（A）当 $a>0$ 时， $y^{\prime}+a y=f(x\,)$ 的任意解都满足 $\operatorname*{lim}_{r\to+\infty}y\left(x\right)={\frac{b}{a}}$ (B)当 $\alpha>0$ 时， $y^{\prime}+a y=f(x)$ 的任意解都满足 $\operatorname*{lim}_{x\to+\cdots}y\left(x\right)={\frac{a}{b}}$ (C)当 $a<0$ 时， $y^{\prime}+a y=f(x)$ 的任意解都满足 $\operatorname*{lim}_{\tau\to+\infty}y\left(x\right)={\frac{b}{a}}$ (D)当 $a<0$ 时， $y^{\prime}+a y=f(x\,)$ 的任意解都满足 $\operatorname*{lim}_{\tau\to+}y\left(x\right)=\frac{a}{b}$  

【解】应选(A).  

$y^{\prime}+a y=f(x)$ 的通解公式为 $y\left(x\,\right)=\mathrm{e}^{-a x}\,\left[\int_{0}^{x}\mathrm{e}^{a t}f(t\,)\,\mathrm{d}t+C\right],C$ 为任意常数。当 $a>0$ 时，  

$$
\operatorname*{lim}_{\substack{x\to+\infty}}y(x)=\operatorname*{lim}_{x\to+\infty}\frac{\int_{0}^{x}\mathrm{e}^{u t}f(t)\mathrm{d}t+C}{\mathrm{e}^{u x}}\frac{\#\mathcal{U}\mathrm{i}\xi\mathrm{i}\xi\mathrm{i}\mathbb{M}}{\mathrm{e}^{u x}}\operatorname*{lim}_{x\to+\infty}\frac{\mathrm{e}^{u x}f(x\,)}{\alpha\,\mathrm{e}^{u x}}\!=\!\operatorname*{lim}_{x\to+\infty}\frac{f(x\,)}{\alpha}\!=\!\frac{b}{\alpha}.
$$  

当 $a<0$ 时，在通解公式中令 $C=-\int_{\,0}^{+\infty}\mathbf{e}^{a t}f(t)\,\mathrm{d}t$ ，则  
$$
\begin{array}{l}{{{y}_{0}}\left(x\right)={\mathrm{e}^{-a x}}\left[{\displaystyle\int_{0}^{x}{\mathrm{e}^{u t}}f(t)\,\mathrm{d}t}-{\displaystyle\int_{0}^{+\infty}{\mathrm{e}^{u t}}f(t)\,\mathrm{d}t}\right]}\\ {{\qquad=-\,{\mathrm{e}^{-a x}}\displaystyle\int_{x}^{+\infty}{\mathrm{e}^{u t}}f(t)\,\mathrm{d}t}\,,}\end{array}
$$  

1$\operatorname*{im}_{\substack{*+\infty}}y_{0}(x)=-\operatorname*{lim}_{x\to+\infty}\frac{\int_{x}^{+\infty}\mathrm{e}^{a t}f(t)\mathrm{d}t}{\mathrm{e}^{a x}}\,\frac{\#\Re\Re\Re\Re\Re\mathrm{d}\mathrm{}\mathrm{d}\mathrm{}}{x^{+}+\infty}-\operatorname*{lim}_{x\to+\infty}\frac{-\mathrm{e}^{a x}f(x)}{\alpha\,\mathrm{e}^{a x}}=\operatorname*{lim}_{x\to+\infty}\frac{f(x)}{a}=\frac{b}{a}.$   
x  
若$C\not\to-\int_{0}^{+\infty}\mathrm{e}^{a t}f(t)\mathrm{d}t$ ，令 $C=-\int_{0}^{+\infty}{\mathrm{e}}^{a t}f(t)\,\mathrm{d}t+k\,,k\neq0$ ，则  

$$
y(x)=\frac{-\displaystyle\int_{x}^{+\infty}\mathrm{e}^{u t}f(t)\mathrm{d}t+k}{\mathrm{e}^{u x}},
$$  

$$
\operatorname*{lim}_{x\to+\infty}y\left(x\right)\frac{\left(\ast\right)}{x++\infty}\operatorname*{lim}_{x\to+\infty}\frac{-\int_{x}^{+\infty}\mathrm{e}^{a t}f(t)\,\mathrm{d}t}{\mathrm{e}^{a x}}+\operatorname*{lim}_{x\to+\infty}\frac{k}{\mathrm{e}^{a x}}\!=\!\frac{b}{a}+\infty\!=\!\infty.
$$  

综上所述,当 $a>0$ 时,任意解均满足 $\operatorname*{lim}_{x\to+\infty}y\left(x\right)={\frac{b}{a}}$  

$a<0$ 时，只有一个解 $_{y_{0}}(x)$ 满足 $\operatorname*{lim}_{x\to+\infty}y\left(x\right)={\frac{b}{a}}$ 选（A).  

$(\,\star\,)$ 处不可以直接使用洛必达法则，因为极限不是 $\big<\frac{0}{0}\,,\big>$ 型。  

（仅数学一）求微分方程 $y^{\prime}\cos\;y=(1+\cos\;x\sin\;y\,)\sin\;y\ |$ 的通解。  

作适当代换 $z=\sin{y}$ 便可化为伯努利方程，解之.  

令$z=\sin{y}$ 则${\frac{\mathrm{d}z}{\mathrm{d}x}}=\cos\ y\ {\frac{\mathrm{d}y}{\mathrm{d}x}}$  

代人原方程,得伯努利方程 ${\frac{\mathrm{d}z}{\mathrm{d}x}}-z=z^{2}\cos\,x$ ,两边同时除以 $z^{2}$ 得$z^{-2}\;\frac{\mathrm{d}z}{\mathrm{d}x}-z^{-1}=\cos\,x$ 再令 $\pmb{z}^{-1}=\pmb{u}$ 则 $z^{-2}\;\frac{\mathrm{d}z}{\mathrm{d}x}=-\,\frac{\mathrm{d}u}{\mathrm{d}x}$ ,代人上述方程，得 ${\frac{\mathrm{d}u}{\mathrm{d}x}}+u=-\cos\,x$  

解此一阶线性微分方程，得  

$$
u=\mathrm{e}^{-\Big\lceil\mathrm{d}x}\left(-\int\cos\,x\,\star\,\mathrm{e}^{\int\!\!\mathrm{d}x}\,\mathrm{d}x+C_{1}\right)\!=\!-\,\frac{1}{2}(\cos\,x\,+\sin\,x\,)+C_{1}\,\mathrm{e}^{-x}\,,
$$  

将$u=\frac{1}{z}\,,z=\sin\,y$ 代人上式，得 $\frac{1}{\sin\,y}=-\frac{1}{2}(\cos\,x+\sin\,x\,)+C_{1}\,\mathrm{e}^{-x}.$  

所以原方程的通解为 ${\frac{2}{\sin\,y}}+\cos\,x+\sin\,x=C\mathrm{e}^{-x}$ ,其中 $C$ 为任意常数.  

二阶可降阶微分方程的求解(仅数学一 数学二)  

若是“ $y^{\prime\prime}$ ,则  
1.能写成 $y^{\prime\prime}=f(x\cdot y^{\prime})$  

$\textcircled{1}$ 缺 $_y$ ，令 $y^{\prime}=p\,,y^{\prime\prime}=p^{\prime}$ ,则原方程变为一阶方程 ${\frac{\mathrm{d}{\boldsymbol{p}}}{\mathrm{d}x}}=f({\boldsymbol{x}}\ ,{\boldsymbol{p}})$ ；  

$\textcircled{2}$ 若求得其通解为 $\boldsymbol{p}=\varphi\left(\boldsymbol{\chi}\,,C_{1}\right)$ ），即 $y^{\prime}=\varphi\left(x\mathrm{~},C_{1}\right)$ ,则原方程的通解为  

$$
y=\!\int\!\varphi\left(x\;,\!C_{1}\right)\!\,\mathrm{d}x+C_{2}.
$$  

$^{2,}$ 能写成y"=f（y"）  

$\textcircled{1}$ 缺 $_{x}$ 令 $y^{\prime}=\;\dot{p}\,,y^{\prime\prime}=\;\frac{\mathrm{d}\dot{p}}{\mathrm{d}x}=\;\frac{\mathrm{d}\dot{p}}{\mathrm{d}y}\cdot\frac{\mathrm{d}y}{\mathrm{d}x}=\;\frac{\mathrm{d}\dot{p}}{\mathrm{d}y}\cdot\dot{p}$ ，则原方程变为一阶方程 $\ p\ {\frac{\mathrm{d}p}{\mathrm{d}y}}=f(y\,,p)$ $\textcircled{2}$ 若求得其通解为 $\boldsymbol{\phi}=\varphi(y\,,\boldsymbol{C}_{1})$ ，则由 $\displaystyle p={\frac{\mathrm{d}y}{\mathrm{d}x}}$ 愛得 $\frac{\mathrm{d}y}{\mathrm{d}x}=\varphi(y\,,\!C_{1})$ ，分离变量得  

$$
\frac{\,\mathrm{d}y}{\,\varphi\,(\,y\,,C_{1}\,)}=\,\mathrm{d}x\,;
$$  

$\textcircled{3}$ 两边积分得 $\int\frac{\mathrm{d}y}{\varphi\left(y\,,C_{1}\right)}=x+C_{2}$ ，即可求得原方程的通解.  

例15. 4求微分方程 $y^{\prime\prime}[x+(y^{\prime})^{2}]\,{=}\,y^{\prime}$ 满足初始条件 $y\left(1\right)=y^{\prime}(1)=1$ 的特解。  

【解】所给方程缺 $y$ ，令 $y^{\prime}=p$ ，则 $y^{\prime\prime}={p^{\prime}}$ ，原方程化为  

$$
\begin{array}{r l}&{\dot{p}^{\prime}(x+\dot{p}^{2})=\rho\,,}\\ &{\frac{\mathrm{d}\dot{p}}{\mathrm{d}x}(x+\dot{p}^{2})=\rho\,,}\\ &{\dot{p}\;\frac{\mathrm{d}x}{\mathrm{d}\dot{p}}=x+\dot{p}^{2}\,,}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad x^{\prime}-\frac{1}{\dot{p}}x=\dot{p}\,,}\end{array}
$$  

即  

由通解公式得  

$$
x=\mathrm{e}^{\int_{\frac{1}{p}}^{\frac{1}{p}}\!\mathrm{d}\boldsymbol{\hat{p}}}\left(\int\!\mathrm{e}^{-\left\int_{\frac{1}{p}}^{\frac{1}{p}}\!\mathrm{d}\boldsymbol{\hat{p}}}\,\star\,\boldsymbol{\hat{p}}\,\mathrm{d}\boldsymbol{\hat{p}}+C_{1}\right)\!=\!\boldsymbol{\hat{p}}\,(\boldsymbol{\hat{p}}+C_{1})=\boldsymbol{\hat{p}}^{2}+C_{1}\boldsymbol{\hat{p}}.
$$  

由 $\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;$ ，得 $C_{1}=0$ ，故 ${\boldsymbol{p}}^{2}={\boldsymbol{x}}$ 由 $y^{\prime}(1)=1$ 知，应取 $\scriptstyle{p={\sqrt{x}}}$ ,即  

$$
{\frac{\mathrm{d}y}{\mathrm{d}x}}={\sqrt{x\,}}\,,
$$  

解得 $y=\frac{2}{3}x^{\frac{3}{2}}+C_{2}.$ 又由 $y\left(1\right)=1$ ，得 $C_{2}=\frac{1}{3}$ ，故所求特解为  

$$
y={\frac{2}{3}}x^{\frac{3}{2}}+{\frac{1}{3}}.
$$  
【注  方程 $\!\,{\dot{p}}^{\prime}(x+p^{2})=p$ 亦可用全微分法来做，移项可得  

$$
\phi\,{\mathrm{d}}x-x\,{\mathrm{d}}p=p^{2}\,{\mathrm{d}}p
$$  

即  

$$
{\frac{p\,{\mathrm{d}}x\,-x\,{\mathrm{d}}\,p}{p^{2}}}={\mathrm{d}}p\,,
$$  

$$
\mathsf{d}\Big(\frac{x}{\mathscr{p}}\Big)\!=\!\mathsf{d}\mathscr{p}
$$  

于是有 $\frac{x}{\d{\phi}}=\pmb{\mathscr{p}}+\pmb{C}_{1}$  

15.5 求微分方程 $2y\,^{2}y^{\prime\prime}\!=\!\left[1+(y\,^{\prime})^{2}\right]^{2}(x\geqslant1)$ 满足 $y\,\Big|_{\,x=3}=2\,,y^{\prime}\,\Big|_{\,x=3}=1$ 的特解  

【解】这是缺 $_{x}$ 的二阶微分方程，令 $y^{\prime}=\phi\,,y^{\prime\prime}={\frac{\mathrm{d}{\dot{p}}}{\mathrm{d}x}}={\dot{p}}\ {\frac{\mathrm{d}{\dot{p}}}{\mathrm{d}y}}$ ,所给方程化为  

$$
2y^{\,2}\,\phi\;{\frac{\mathrm{d}\phi}{\mathrm{d}y}}=(1+p^{\,2}\,)^{\,2}\,,
$$  

分离变量，得  

$$
\frac{2\phi\,\mathrm{d}\phi}{(1+\phi^{2})^{2}}=\frac{\mathrm{d}y}{y^{2}}\,,
$$  

两边积分得  

$$
\frac{1}{1+{\pmb{\rho}}^{2}}\!=\!\frac{1}{y}+C_{1}=\!\frac{1+C_{1}y}{y},
$$  

$$
1+{\dot{p}}^{2}=\!\frac{y}{1+C_{1}y},\!\dot{p}^{2}=\!\frac{(1-C_{1})y-1}{1+C_{1}y}.
$$  

初始条件为 $y\Bigm|_{x=3}=2\,,p\Bigm|_{x=3}=y^{\prime}\Bigm|_{x=3}=1.$ 将 $y=2\,,\,p=1$ 代人，得  

$$
1\!=\!\frac{2(1-C_{1})-1}{1+2C_{1}},
$$  

所以 $C_{1}=0\,,\,p^{2}=y-1$ ，则  

$$
\frac{\mathrm{d}y}{\mathrm{d}x}\!=\!\!{\sqrt{y-1}}\,,
$$  

再分离变量,得  

$$
\frac{\mathrm{d}y}{\sqrt{y-1}}=\mathrm{d}x\ ,2\sqrt{y-1}=x+C_{2}.
$$  

以 $x=3,y=2$ 代人得 $C_{2}=-1,2\sqrt{y-1}=x-1(x\geqslant1)$ ，所以  

$$
y=\frac{1}{4}(x-1)^{2}+1(x\geqslant1).
$$  
# 陆亨高管数学18讲  

1.能写成  

写 $\lambda^{2}+p\lambda+q=0\Rightarrow\lambda_{1}\,,\lambda_{2}\Rightarrow$ 写齐次方程的通解，$\Rightarrow$ 写出通解. 设特解 $y^{\star}\Rightarrow$ 代回方程，求待定系数 $\Rightarrow$ 特解  

2. 能写成y"+py'+qy=f（x）+f（x ）  

写 $\lambda^{2}+\rho\lambda+q=0\Rightarrow$ 齐次方程的通解，  

$\begin{array}{r}{\left|y^{\prime\prime}+p y^{\prime}+q y=f_{1}\left(x\,\right)\right.}\\ {\left.\left|y^{\prime\prime}+p y^{\prime}+q y=f_{2}\left(x\,\right)\right.}\end{array}$ ,写特解 $y_{1}^{\cdot}\rightarrow y_{1}^{\cdot}+y_{2}^{\cdot}$ $\Rightarrow$ 写出通解. 拆自由项为特解,写特解  

注)(1) 齐次线性微分方程的通解.  

$\textcircled{1}$ 若 $\pmb{{\cal P}}^{2}-4q>0$ ，设 $\lambda_{1},\lambda_{2}$ 是特征方程的两个不相等的实根,即 $\lambda_{1}\neq\lambda_{2}$ ,可得其通解为  

$$
y=C_{1}\,\mathrm{e}^{\lambda_{1}\tau}+C_{2}\,\mathrm{e}^{\lambda_{2}\tau}\,.
$$  

$\circledcirc$ 若 $\pmb{\mathscr{p}}^{2}-4q=0$ ，设 $\lambda_{\mathrm{~l~}}\!=\!\lambda_{\mathrm{~2~}}\!=\!\lambda$ 是特征方程的两个相等的实根,即二重根,可得其通解为$\boldsymbol{y}=(C_{1}+C_{2}\boldsymbol{x}\,)\,\mathrm{e}^{\lambda\boldsymbol{x}}\,.$  

$\textcircled{3}$ 若 $\pmb{\mathscr{p}}^{2}-4\ q<0$ ，设 $\alpha\pm\beta$ i是特征方程的一对共轭复根，可得其通解为  

$$
y=\mathrm{e}^{\alpha x}\,(C_{\mathrm{}1}\cos\,\beta x+C_{\mathrm{}2}\sin\,\beta x\,).
$$  

（2）非齐次线性微分方程的特解。  

对于 $y^{\prime\prime}+\phi y^{\prime}+q y=f(x)$ ,考研要求会解以下两种情况：  

$\textcircled{1}$ 当自由项 $f(x)=P_{n}(x)\mathbf{e}^{\alpha x}$ 时，特解要设为 $y^{\cdot}=\mathrm{e}^{\prime\tau}Q_{n}\left(x\,\right)x^{k}$ ，其中  

$\alpha\neq\lambda_{1},\alpha\neq\lambda_{2}\,,$  

$\alpha=\lambda_{1}=\lambda_{2}$  

$\circledcirc$ 当自由项 $f(x\,)=\mathrm{e}^{\alpha x}\left[P_{\mathrm{\Phi}_{m}}(x\,)\cos\,\beta x\,+P_{\mathrm{\Phi}_{n}}(x\,)\sin\,\beta x\,\right]$ 时，特解要设为  

$$
y^{\,\bullet}\,=\mathrm{e}^{a\scriptscriptstyle{r}}\,\left[Q_{l}^{\scriptscriptstyle{(1)}}\left(x\,\right)\cos\,\beta x\,+Q_{l}^{\scriptscriptstyle{(2)}}\left(x\,\right)\sin\,\beta x\,\right]x^{\,}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/ec44b1f2445b3ce092e6b2e2fae4bfc4ea65b7a7c19d4c46b7b49fbc2b093090.jpg)  
(3）微分算子法.  

$\textcircled{1}$ 算子记号.  

约定： $;\mathrm{D}\!=\!{\frac{\mathrm{d}}{\mathrm{d}x}},\mathrm{D}y=\!{\frac{\mathrm{d}y}{\mathrm{d}x}},\mathrm{D}^{2}\!=\!{\frac{\mathrm{d}^{2}}{\mathrm{d}x^{\,2}}},\mathrm{D}^{2}\,y=\!{\frac{\mathrm{d}^{2}\,y}{\mathrm{d}x^{\,2}}}$ ，于是微分方程 $y^{\prime\prime}+\phi y^{\prime}+q y=f(x\,)$ 即可写成 $(\mathbf{D}^{2}+\hbar\mathbf{D}+\mathbfit{q})y=f(x)$ ,进一步记 $\mathrm{D}^{2}+p\mathrm{D}\!+\!q=\!F(\mathrm{D})$ ,称为算子多项式,它满足普通多项式的运算规则，如因式分解等，则上述微分方程即可写成 $F(\mathrm{D})y=f(x)$ ，此时它的一个特解为 $y^{\cdot}=\!\frac{1}{F(\mathrm{D})}f(x)$  

$\circledcirc$ 算子性质.  

约定：“D”表示求导，如Dsin $x=\cos x\cdot^{1}\frac{1}{\mathrm{D}},$ 表示积分，如 $\frac{1}{\mathrm{D}}\sin{x}=-\cos{x}$ （取 $C=0$ ）.a. ${\frac{1}{F(\mathrm{D})}}\mathbf{e}^{\alpha}$ 型。  
若 $\left.F(\mathrm{D})\,\right|_{\mathrm{D}=\sigma}\neq0$ ,有 $y^{\star}=\!\frac{1}{F(\mathrm{D})}\mathrm{e}^{a x}=\!\frac{1}{F(\mathrm{D})\,\bigg|_{\mathrm{\scriptsize~D}=a}}\mathrm{e}^{a x}\,.$   
若$F(\mathrm{D})\left|_{\mathrm{D}=\alpha}=0\right.$ ，而 $\left.F^{\prime}(\mathrm{D})\,\right|_{\mathrm{D}=\alpha}\neq0$ 有$y^{\star}=\!\frac{1}{F(\mathrm{D})}\mathrm{e}^{a x}=\displaystyle x\left.\frac{1}{F^{\prime}(\mathrm{D})\,\right|_{\mathrm{\scriptsize~D}=a}}\mathrm{e}^{a x}\,.$   
若 $F(\mathrm{D})\Big|_{\mathrm{D}=\mathfrak{a}}=0,F^{\prime}(\mathrm{D})\Big|_{\mathrm{D}=\mathfrak{a}}=0$ ，而 $\left.F^{\prime\prime}(\mathrm{D})\,\right|_{\mathrm{D}=\alpha}\neq0$ ，有  
$y^{\star}=\!\frac{1}{F(\mathrm{D})}\mathrm{e}^{\alpha x}=\!x^{2}\left.\frac{1}{F^{\prime\prime}(\mathrm{D})\,\right|_{\mathrm{\scriptsize~D}=\alpha}}\mathrm{e}^{\alpha x}\,.$  

注例1 已知 $y^{\prime\prime}+y^{\prime}-2y=2$ ，求 $_y\cdot$ 解 $y^{\ast}=\frac{1}{\mathrm{D}^{2}+\mathrm{D}-2}2\mathrm{e}^{\circ}\,$ ，由 $(\mathrm{D}^{2}+\mathrm{D}-2)\bigg\vert_{\mathrm{D}=0}\neq0$ ，得$y^{\star}=\frac{1}{(\mathrm{D}^{2}+\mathrm{D}-2)\Bigm|_{\mathrm{D}=0}}2\mathrm{e}^{0x}=\frac{1}{-2}\cdot2=-1.$  

注例2 已知 $y^{\prime\prime}+y^{\prime}-2y=\mathbf{e}^{x}$ ，求 $_y\cdot$ 解 $\cdot=\frac{1}{\bf D}^{2}+{\bf D}-2}{\bf e}^{x}\,,\,\rlap{/}\mathrm{i}\,({\bf D}^{2}+{\bf D}-2)\,\bigg|_{{\bf D}-1}=0\,,({\bf D}^{2}+{\bf D}-2)^{\prime}\,\bigg|_{{\bf D}-1}\neq0\,,$ 得$y^{\star}=x\ \frac{1}{\left(\mathrm{D}^{2}+\mathrm{D}-2\right)^{\prime}\Big|_{\mathrm{\scriptsize~D}=1}}\mathrm{e}^{x}=x\cdot\frac{1}{3}\mathrm{e}^{x}=\frac{1}{3}x\,\mathrm{e}^{x}\,.$  

注例3 已知 $y^{\prime\prime}-2y^{\prime}+y=\mathbf{e}^{x}$ ，求 $_y\cdot$  

解 $y^{\cdot}=\frac{1}{\mathrm{D}^{2}-2\mathrm{D}+1}\mathrm{e}^{x}$ ，由$(\mathrm{D}^{2}-2\mathrm{D}+1)\Bigm|_{\mathrm{D}=1}=0\,,(\mathrm{D}^{2}-2\mathrm{D}+1)^{\prime}\Bigm|_{\mathrm{D}=1}=0\,,(\mathrm{D}^{2}-2\mathrm{D}+1)^{\prime\prime}\Bigm|_{\mathrm{D}=1}\neq0\,,$  
得  

$$
\boldsymbol{y}^{\star}=\boldsymbol{x}^{2}\;\frac{1}{(\mathrm{D}^{2}-2\mathrm{D}+1)^{\prime\prime}\Big|_{\mathrm{D}=1}}\boldsymbol{\mathrm{e}}^{x}=\boldsymbol{x}^{2}\cdot\frac{1}{2}\boldsymbol{\mathrm{e}}^{x}=\frac{1}{2}\boldsymbol{x}^{2}\,\boldsymbol{\mathrm{e}}^{x}\,.
$$  

b$\frac{1}{F(\mathrm{D}^{2})}{\cos\beta x}$ 或${\frac{1}{F(\mathrm{D}^{2})}}\sin\beta x$ 型(这里要特别约定, $F({\mathrm{D}}^{2})$ 是$\mathrm{D}^{2}$ 及常数构成的算子多项 式，即 $\begin{array}{r}{F(\mathrm{D}^{2})=\mathrm{D}^{2}+q\,)}\end{array}$  

若$\left.F(\mathrm{D}^{2})\,\right|_{\mathrm{D}=\beta\mathrm{i}}\neq0$ ，有 ${_y}\cdot=\frac{1}{F(\mathrm{D}^{2})}$ “$\beta x=\frac{1}{F(\mathrm{D}^{2})\Bigm|_{\mathrm{D}=\beta\mathrm{i}}}\cos\beta x\ ,$ $y^{\star}=\!\frac{1}{F(\mathrm{D}^{2})}\!\sin\beta x=\!\frac{1}{F(\mathrm{D}^{2})\,\Big|_{\mathrm{\scriptsize~D}=\beta\mathrm{i}}}\!\sin\beta x\,.$  

若 $F(\mathrm{D}^{2})\bigg|_{\mathrm{D}=\beta\mathrm{i}}=0$ ，有 $y^{\star}=\frac{1}{F(\mathrm{D}^{2})}\mathrm{cos}\;\beta x=x\;\frac{1}{\left[F(\mathrm{D}^{2})\right]^{\prime}}\mathrm{cos}\;\beta x\;,$  

$$
y^{\,\bullet}=\!\frac{1}{F(\mathrm{D}^{2})}\mathrm{sin}\;\beta x=x\;\frac{1}{\left[F(\mathrm{D}^{2})\right]^{\prime}}\mathrm{sin}\;\beta x\,.
$$  

若为 $\displaystyle\frac{1}{F(\mathrm{D})}\!\cos{\beta x}$ 或 $\frac{1}{F(\mathrm{D)}}\sin{\beta x}$ 型,其处理办法参考注例 6.  

注例4 已知 $y^{\prime\prime}-y=\sin\,x$ ，求 $y^{\cdot}$  

解 $\boldsymbol{y}^{\cdot}=\frac{1}{\mathrm{D}^{2}-1}\sin\,\boldsymbol{x}$ ，由 $(\mathrm{D}^{2}-1)\Big|_{\mathrm{D}=\mathrm{i}}\neq0$ ，得  

$$
y^{\star}=\frac{1}{(\mathrm{D}^{2}-1)\,\Big|_{\mathrm{\scriptsize~D=i}}}\sin\,x=-\,\frac{1}{2}\sin\,x\,.
$$  

注例5 已知 $y^{\prime\prime}+4y=\sin2x$ ，求 $_y\cdot$  

解 $y^{\cdot}=\frac{1}{\mathrm{D}^{2}+4}\sin2x$ ，由 $(\mathrm{D}^{2}+4)\Big|_{\mathrm{D}=2\mathrm{i}}=0$ ，得$y^{\star}=x\ \frac{1}{\left(\mathrm{D}^{2}+4\right)^{\prime}}\mathrm{sin}\ 2x=x\ \frac{1}{2\mathrm{D}}\mathrm{sin}\ 2x=\frac{1}{2}x\,\cdot\,\frac{1}{\mathrm{D}}\mathrm{sin}\ 2x=-\,\frac{1}{4}x\cos\ 2x\,.$  

注例6 已知 $y^{\prime\prime}-3y^{\prime}+2y=-{\frac{1}{2}}\mathrm{cos}\ 2x$ ，求 $_y\cdot$  

解$y^{\star}=\frac{1}{\mathrm{D}^{2}-3\mathrm{D}+2}\Bigl(-\,\frac{1}{2}\cos\,2x\,\Bigr)$ 此为 $\frac{1}{F(\mathrm{D})}$ cos $\beta x$ 型,此时遵循“先代 $\beta\mathrm{i}$ 到$\mathrm{D}^{2}$ ,然后再 处理”的方法.即  

$$
{\begin{array}{r l}&{y^{\ast}={\cfrac{1}{\mathrm{D}^{2}-3\mathrm{D}+2}}{\left(-{\frac{1}{2}}\cos2x\ }={\cfrac{1}{-4-3\mathrm{D}+2}}{\left(-{\frac{1}{2}}\cos2x\ \right)}={\cfrac{1}{2}}\cdot{\frac{1}{3\mathrm{D}+2}}{\left(-{\frac{1}{2}}\cos2x\ \right)}={\cfrac{1}{2}}\cdot{\frac{1}{3\mathrm{D}+2}}}\\ &{\qquad={\cfrac{1}{2}}\cdot{\frac{3\mathrm{D}-2}{9\mathrm{D}^{2}-4}}\cos2x={\cfrac{1}{2}}\cdot{\frac{3\mathrm{D}-2}{-40}}\cos2x=-{\cfrac{1}{80}}(3\mathrm{D}-2)\cos2x}\\ &{\qquad=-{\cfrac{1}{80}}(3\mathrm{D}\cos2x-2\cos2x\ )=-{\cfrac{1}{80}}(-6\sin2x-2\cos2x\ )}\end{array}}
$$  
$=\!{\frac{1}{40}}(3\sin\,2x+\cos\,2x).$   
 $\mathrm{c.}\,{\frac{1}{F(\mathrm{D})}}(x^{k}+a_{1}x^{k-1}+\cdots+a_{k-1}x+a_{k})$ 型。  
$y^{\star}=\frac{1}{F(\mathrm{D})}(x^{k}+a_{1}x^{k-1}+\cdots+a_{k-1}x+a_{k})=Q_{k}(\mathrm{D})(x^{k}+a_{1}x^{k-1}+\cdots+a_{k-1}x).$ r+ak).   
这里 $Q_{k}\left(\mathbf{D}\right)$ 是将 $\frac{1}{F(\mathrm{D})}$ 展开为(常借助 ${\frac{1}{1-x}}\!=\!1\!+\!x+x^{2}+\cdots+x^{k}+\cdots)$ 形式上的泰勒级  
数，即 $\frac{1}{F(\mathrm{D})}\!=\!b_{0}+b_{1}\mathrm{D}+b_{2}\mathrm{D}^{2}+\cdots+b_{k}\mathrm{D}^{k}+\cdots.$ ,取该展开式到 $\mathrm{D}^{\star}$ 项的一个多项式.  

注例7 已知 $y^{\prime\prime}+y^{\prime}=x^{2}+1$ ，求 $_y\cdot$  

解  

$$
y^{\cdot}=\frac{1}{\mathrm{D}^{2}+\mathrm{D}}(x^{\,2}+1)=\frac{1}{\mathrm{D}}\cdot\frac{1}{1+\mathrm{D}}(x^{\,2}+1)\,,
$$  

下面将 $\frac{1}{1+\mathrm{D}}$ 作D的2次展开：  

$$
\frac{1}{1+\mathrm{D}}\,{=}\,1-\mathrm{D}+\mathrm{D}^{2}+\cdots,
$$  

于是  

$$
{\begin{array}{r l}&{y^{\star}={\frac{1}{\mathrm{D}}}\cdot(1-\mathrm{D}+\mathrm{D}^{2})(x^{2}+1)=\left({\frac{1}{\mathrm{D}}}-1+\mathrm{D}\right)(x^{2}+1)}\\ &{\quad={\cfrac{1}{\mathrm{D}}}(x^{2}+1)-(x^{2}+1)+\mathrm{D}(x^{2}+1)}\\ &{\quad={\cfrac{1}{3}}x^{3}+x-x^{2}-1+2x={\cfrac{1}{3}}x^{3}-x^{2}+3x-1.}\end{array}}
$$  

d $\frac{1}{F(\mathrm{D})}\mathbf{e}^{a x}v(x)$ 型。  

$y^{\star}=\frac{1}{F(\mathrm{D})}\mathrm{e}^{\alpha x}v(x)=\mathrm{e}^{\alpha x}\,\cdot\,\frac{1}{F(\mathrm{D}+\alpha)}v(x\,)$ ，这里 $_{v}(x)$ 是实函数。  

注例8已知 $y^{\prime\prime}+4y^{\prime}+5y=\mathrm{e}^{-2x}\sin\,x$ ，求 $y^{\,\cdot}$  

$$
{\begin{array}{r l}&{y^{\ast}={\cfrac{1}{\mathrm{D}^{2}+4\mathrm{D}+5}}{\mathrm{e}}^{-2x}\sin x={\mathrm{e}}^{-2x}\,\cdot{\cfrac{1}{(\mathrm{D}-2)^{2}+4(\mathrm{D}-2)+5}}{\sin}~x}\\ &{\quad={\mathrm{e}}^{-2x}\,\cdot{\cfrac{1}{\mathrm{D}^{2}+1}}{\sin}~x={\mathrm{e}}^{-2x}\,\cdot x\,\,{\cfrac{1}{(\mathrm{D}^{2}+1)^{\prime}}}{\sin}~x}\\ &{\quad={\mathrm{e}}^{-2x}\,\cdot x\,\,{\cfrac{1}{2\mathrm{D}}}{\sin}\,x={\cfrac{1}{2}}{\mathrm{e}}^{-2x}\,\cdot x\,(-\cos\,x)=-{\cfrac{1}{2}}x{\mathrm{e}}^{-2x}\cos\,x.}\end{array}}
$$  

注例9 已知 $y^{\prime\prime}-3y^{\prime}+2y=2x\mathbf{e}^{x}$ ，求 $_y\cdot$  

$$
y^{\star}=\frac{1}{\mathrm{D}^{2}-3\mathrm{D}+2}2x\,\mathrm{e}^{x}=2\mathrm{e}^{x}\,\cdot\frac{1}{(\mathrm{D}+1)^{2}-3(\mathrm{D}+1)+2}x=2\mathrm{e}^{x}\,\cdot\frac{1}{\mathrm{D}^{2}-\mathrm{D}}x
$$  
# 比宁高等数学18洲  

$$
\begin{array}{r l}&{\displaystyle=2\mathbf{e}^{\boldsymbol{r}}\,\cdot\,\frac{1}{\ensuremath Ḋ \mathbf Ḋ \nabla Ḍ Ḍ }\cdot\frac{1}{\ensuremath Ḋ \mathbf Ḋ \nabla Ḍ Ḍ -1}x=2\mathbf{e}^{\boldsymbol{r}}\,\cdot\,\frac{1}{\ensuremath Ḋ \mathbf Ḋ \nabla Ḍ Ḍ }\cdot\left(-\ensuremath{\mathbf Ḋ \nabla Ḍ }\right)x=2\mathbf{e}^{\boldsymbol{r}}\,\cdot\,\left(-\ensuremath{\frac{1}{\ensuremath Ḋ \mathbf Ḋ \nabla Ḍ Ḍ }}-1\right)x}\\ &{\displaystyle=2\mathbf{e}^{\boldsymbol{r}}\,\cdot\,\left(-\,\frac{1}{2}x^{\mathit{2}}-x\right)\!=\!-x\left(x+2\right)\mathbf{e}^{\boldsymbol{x}}.}\end{array}
$$  

例15. 6微分方程 $y^{\prime\prime}-y=\sin\,x$ 在 $(-\infty,+\infty)$ ）上有界的解为  

【解】应填 $y=-{\frac{1}{2}}\sin\,x$  

由注例4,知 $y^{\cdot}=-\,{\frac{1}{2}}\sin\,x$ ，又由 $y^{\prime\prime}-y=0$ 知 $\lambda^{2}-1=0$ ，解得 $\lambda=\pm1$ ,即  

$$
y_{\star i\Im}=C_{1}\,\mathrm{e}^{x}+C_{2}\,\mathrm{e}^{-x}\,,
$$  

于是该微分方程的通解为  

$$
y=C_{1}\,\mathrm{e}^{\boldsymbol{r}}+C_{2}\,\mathrm{e}^{-\boldsymbol{x}}-\frac{1}{2}\mathrm{sin}\,\,x\,,
$$  

由题意，只有 $C_{1}=\ C_{2}=\ 0$ 时， $y=-\,{\frac{1}{2}}\sin\,x$ 在 $(-\infty,+\infty$ ）上有界，故有界的解只有$y=\,-\,{\frac{1}{2}}\sin\,x\,.$  

3. 能写成²y"+pry+qy=f（x）（欧拉方程）（仅数学一)  $\textcircled{1}$ 当 $x>0$ 时令 $x=\mathbf{e}^{t}$  $t=\ln{x}$  ${\frac{\mathrm{d}t}{\mathrm{d}x}}\!=\!{\frac{1}{x}}$ 于是  

$$
={\frac{\mathrm{d}y}{\mathrm{d}t}}\cdot{\frac{\mathrm{d}t}{\mathrm{d}x}}={\frac{1}{x}}\,{\frac{\mathrm{d}y}{\mathrm{d}t}}\,,{\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{2}}}={\frac{\mathrm{d}}{\mathrm{d}x}}{\bigg(}{\frac{1}{x}}\,{\frac{\mathrm{d}y}{\mathrm{d}t}}{\bigg)}=-{\frac{1}{x^{2}}}\,{\frac{\mathrm{d}y}{\mathrm{d}t}}+{\frac{1}{x}}\,{\frac{\mathrm{d}}{\mathrm{d}x}}{\bigg(}{\frac{\mathrm{d}y}{\mathrm{d}t}}{\bigg)}=-{\frac{1}{x^{2}}}\,{\frac{\mathrm{d}y}{\mathrm{d}t}}+{\frac{1}{x^{2}}}\,{\frac{\mathrm{d}^{2}y}{\mathrm{d}x}}={\frac{1}{x^{2}}}\,{\frac{\mathrm{d}}{\mathrm{d}x}}{\bigg(}{\frac{\mathrm{d}y}{\mathrm{d}x}}{\bigg)}
$$  

方程化为  

$$
\frac{\mathrm{d}^{2}y}{\mathrm{d}t^{2}}+\left(\phi-1\right)\frac{\mathrm{d}y}{\mathrm{d}t}+q y=f(\mathrm{e}^{\prime}\,)\,,
$$  

即可求解（最后结果别忘了用 $t=\ln{x}$ 回代成 $_{x}$ 的函数).  

$\circledcirc$ 当 $x<0$ 时，令 $x=-\,{\mathbf e}^{\prime}$ ,同理可得.  

4.n阶常系数齐次线性微分方程的解  

$\textcircled{1}$ 若 $\lambda$ 为单实根,写 $C\,\mathbf{e}^{\lambda,\tau}$ ；  

$\circledcirc$ 若$\lambda$ 为$\pmb{k}$ 重实根，写  

$$
(C_{1}+C_{2}x+C_{3}x^{2}+\cdots+C_{k}x^{k-1})\,{\mathrm{e}}^{\lambda x}\;;
$$  

$\textcircled{3}$ 若$\lambda$ 为单复根 $\alpha\pm\beta\mathrm{i}$ ，写  

$$
\mathrm{e}^{\alpha\tau}\left(C_{1}\cos\beta x+C_{2}\sin\beta x\right);
$$  

$\circled{4}$ 若 $\lambda$ 为二重复根 $\alpha\pm\beta\mathrm{i}$ ,写  

$$
\mathbf{e}^{a x}\,(C_{\mathrm{}1}\cos\beta x+C_{\mathrm{}2}\sin\beta x+C_{\mathrm{}3}x\cos\beta x+C_{\mathrm{}4}x\sin\beta x\,).
$$  
注】（1）如果解中含特解 $\mathbf{e}^{\lambda x}$ ，则 $\lambda$ 至少为单实根：  

(2）如果解中含特解 $x^{k-1}e^{\lambda x}$ ，则 $\lambda$ 至少为 $\pmb{k}$ 重实根;   
(3）如果解中含特解 $\mathbf{e}^{\alpha x}\cos{\beta x}$ 或$\mathbf{e}^{\alpha x}$ sin $\beta x$ ，则 $\alpha\pm\beta\mathrm{i}$ 至少为单复根;   
（4）如果解中含特解 $\mathbf{e}^{\alpha x}\boldsymbol{x}$ cos $\beta x$ 或 $\mathbf{e}^{\alpha,\tau}\boldsymbol{x}$ sin $_{\beta x}$ ，则 $\alpha\pm\beta\mathrm{i}$ 至少为二重复根.  

如， $y^{\dprime}-y=0$ ,有 $\lambda^{\,3}-1\!=\!0$ ,即 $(\lambda-1)(\lambda^{2}+\lambda+1)=0$ ,解得 $\lambda_{\textrm{l}}\!=\!1,\!\lambda_{\textrm{2,3}}\!=\!-\frac{1}{2}\pm\frac{\sqrt{3}}{2}\mathrm{i}$ 故  

$$
y_{\star\ddot{\bf s}}=C_{1}\mathrm{e}^{x}+\mathrm{e}^{-{\frac{1}{2}}x}\left(C_{2}\cos{\frac{\sqrt{3}}{2}}x+C_{3}\sin{\frac{\sqrt{3}}{2}}x\right),
$$  

其中 $C_{1}\,,C_{2}\,,C_{3}$ 为任意常数.  

例 15. 7设 $_y=y\left(x\right)$ 为可导函数,且满足 $y\left(0\right)=2$  $\frac{\mathrm{d}y}{\mathrm{d}x}+y\left(x\right)=\!\!\int_{0}^{x}2y\left(t\,\right)\mathrm{d}t+\mathbf{e}^{x}$ ,则$y\left(x\right)=\underline{{\phantom{\left(x\right)}}}.$  

由题设知 $y\left(0\right)=2,\frac{\mathrm{d}y}{\mathrm{d}x}=-\,y\left(x\,\right)+\int_{0}^{x}2y\left(t\,\right)\mathrm{d}t\,+\mathrm{e}^{x}$ ，右边对 $_{x}$ 可导，所以 $\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{2}}$ 存在，于是可得  

$$
y^{\prime\prime}+y^{\prime}-2y=\mathbf{e}^{x}\,,
$$  

$$
y^{\prime}(0)=-1.
$$  

微分方程 $(\,\star\,)$ 对应的齐次方程的特征方程为  

$$
\lambda^{2}+\lambda-2=(\lambda-1)(\lambda+2)=0\,,
$$  

解得特征根 $\lambda_{\mathrm{~l~}}\!=\!-\,2\,,\!\lambda_{\mathrm{~2~}}\!=\!1$ ,则对应齐次方程的通解为 $Y\!=\!C_{1}\,\mathbf{e}^{-2\boldsymbol{r}}+C_{2}\,\mathbf{e}^{\boldsymbol{x}}$  

设微分方程 $(\,\star\,)$ 的特解为  

$$
y^{\cdot}=A x\;\mathbf{e}^{x}\;,
$$  

代人 $(\,\star\,)$ 式解得 $A={\frac{1}{3}}$ ，从而 $y^{\cdot}={\frac{1}{3}}x\mathbf{e}^{x}$ .故微分方程的通解为  

$$
y=C_{1}\,{\mathrm{e}}^{-2x}+C_{2}\,{\mathrm{e}}^{x}+{\frac{1}{3}}x{\mathrm{e}}^{x}.
$$  

由初始条件 $y(0)\!=\!2,y^{\prime}(0)\!=\!-1$ ，可得 $C_{1}=\frac{10}{9},C_{2}=\frac{8}{9}$ ,故特解为  

$$
y\left(x\right)=\frac{10}{9}\mathbf{e}^{-2x}+\frac{8}{9}\mathbf{e}^{x}+\frac{1}{3}x\mathbf{e}^{x}.
$$  

求微分方程 $y^{\prime\prime}+4y^{\prime}+5y=\mathrm{e}^{-2x}\sin\,x$ 的通解.  

【解】对应齐次方程的特征方程 $\lambda^{2}+4\lambda+5\!=\!0$ 有一对共轭复根 $\lambda_{\textrm{1,2}}\,{=}\,{-}2\pm\mathrm{i}$ ,故对应齐次方程的通解为 $Y=\mathrm{e}^{-2x}\,(C_{1}\cos\,x+C_{2}\sin\,x\,)$ .下面求微分方程的特解.  

法一原方程的自由项 $f(x\,)=\mathbf{e}^{-2x}\sin\,x=\mathbf{e}^{-2x}\,(0\,\bullet\,\cos\,x\,+1\,\bullet\,\sin\,x\,)$ ，故设特解为  

$$
y^{\,^{\star}}=\mathrm{e}^{-2x}\,(A\cos\,x+B\sin\,x\,)x
$$  
比宁高等数学18讲  

代回原方程，解得 $A=-\frac{1}{2},B=0$ ，故  

$$
y^{\,^{\star}}=-\,{\frac{1}{2}}x\mathrm{e}^{-2x}\cos\,x\,.
$$  

# 法二用微分算子法求特解.  

由三2注例8,可得 $y^{\cdot}=-\,{\frac{1}{2}}x\,\mathrm{e}^{-2x}$ cos $_{x}$  

于是所求通解为 $y=\mathrm{e}^{-2x}\,(C_{1}\cos\,x\,+C_{2}\sin\,x\,)-\frac{1}{2}x\mathrm{e}^{-2x}$ cos $_{x}$ ,其中 $C_{1}\,,C_{2}$ 为任意常数。  

例 15. 9设 $f(x)$ 是 $(-\infty,+\infty)$ ）上的连续函数，  

$$
y\left(x\right)=\!\!\int_{0}^{x}{\mathrm{e}}^{\prime}\,{\mathrm{d}}t{\int_{0}^{x-t}f(u\,)\,\mathrm{d}u\,(-\infty<x<+\infty)}.
$$  

（1）证明： ${\boldsymbol{y}}={\boldsymbol{y}}\left({\boldsymbol{x}}\right)$ 是微分方程 $y^{\prime\prime}-y^{\prime}=f(x)$ 满足初始条件 $y(0)\,{=}\,0\,,y^{\prime}(0)\,{=}\,0$ 的解；  
（2）求微分方程 $y^{\prime\prime}-y^{\prime}=f(x\,)$ 的通解.  

(1)[证]法一记 $F(t)\mathop{=}\!\!\int_{0}^{t}f(u)\mathop{}\!\!\mathrm{d}u$ ,则 $F^{\prime}(t)=f(t)$ ,且 $y\left(x\right){=}\!\int_{0}^{x}\mathbf{e}^{\prime}F(x-t\,)\mathrm{d}t.$ 对积分 作变量代换 $\scriptstyle v\;=\;x\;-\;t$ ，得  

$$
y\left(x\right)=\!\!\int_{0}^{x}{\mathrm{e}^{x-\nu}}F\left(v\right)\mathrm{d}v={\mathrm{e}^{x}}\int_{0}^{x}{\mathrm{e}^{-\nu}}F\left(v\right)\mathrm{d}v\,,
$$  

$$
y^{\prime}(x\,)=\mathbf{e}^{x}{\int}_{0}^{x}\,\mathbf{e}^{-\nu}F(\,\upsilon\,)\,\mathrm{d}\upsilon+\mathbf{e}^{x}\,\bullet\,\mathbf{e}^{-x}F(\,x\,)=y(x\,)+F(x\,)\,,
$$  

$$
y^{\prime\prime}(x\,)={y^{\prime}(x\,)}+F^{\prime}(x\,)={y^{\prime}(x\,)}+f(x\,)\,,
$$  

所以 $y^{\prime\prime}(x\,)-y^{\prime}(x\,)=f(x\,)$ ,且 $y(0)\,{=}\,0\,,y^{\prime}(0)\,{=}\,0$  

法二  

$$
\begin{array}{l}{{\displaystyle y\left(x\right)=\int_{0}^{x}{\bf e}^{\prime}\,{\mathrm{d}}t{\displaystyle\int_{0}^{x-t}f(u\,)\,\mathrm{d}}u=\int_{0}^{x}{\mathrm{d}}u\Biggl\int_{0}^{x-u}{\mathrm{e}^{\prime}f(u\,)\,\mathrm{d}}t\ ~}}\\ {{\displaystyle~~~~~~~~=\int_{0}^{x}\left({\mathrm{e}}^{x-u}-1\right)f(u\,)\,\mathrm{d}u={\mathrm{e}}^{x}\int_{0}^{x}{\mathrm{e}}^{-u}f(u\,)\,\mathrm{d}u-\int_{0}^{x}f(u\,)\,\mathrm{d}u\,,}}\end{array}
$$  

$$
y^{\prime}(x\,)=\mathbf{e}^{x}{\biggl\lbrack}_{0}^{x}\,\mathbf{e}^{-u}f(u\,)\,\mathrm{d}u+\mathbf{e}^{x}\,\cdot\,\mathbf{e}^{-x}f(x\,)-f(x\,)=\mathbf{e}^{x}{\biggl\lbrack}_{0}^{x}\,\mathbf{e}^{-u}f(u\,)\,\mathrm{d}u\,,
$$  

$$
y^{\prime\prime}(x\,)=\mathbf{e}^{x}{\biggl\lbrack}_{0}^{x}\,\mathbf{e}^{-u}f(u\,)\,\mathrm{d}u+\mathbf{e}^{x}\,\cdot\,\mathbf{e}^{-x}f(x\,)=\mathbf{e}^{x}{\biggl\rbrack}_{0}^{x}\,\mathbf{e}^{-u}f(u\,)\,\mathrm{d}u+f(x\,),
$$  

则  

$$
y^{\prime\prime}(x)-y^{\prime}(x)=f(x)\,.
$$  

且  

$$
y(0)\!=\!0,\!y^{\prime}(0)\!=\!0.
$$  

（2）【解】根据上述结果， $y\left(x\right)=\!\!\int_{0}^{x}{\mathrm{e}^{\prime}}\,{\mathrm{d}t}\!\int_{0}^{x-t}f(u)\,{\mathrm{d}u}$ 是微分方程 $y^{\prime\prime}\!-\!y^{\prime}\!=\!f(x)$ 的一个特解.因为特征方程 $\lambda^{2}-\lambda=0$ 的根为 $\lambda_{\scriptscriptstyle1}\!=\!0\,,\!\lambda_{\scriptscriptstyle2}\!=\!1$ ，所以齐次方程 $y^{\prime\prime}\!-\!y^{\prime}\!=\!0$ 的通解为 $Y{=}C_{1}+C_{2}\,\mathbf{e}^{x}$ 根据二阶非齐次线性微分方程通解的结构,可知 $y^{\prime\prime}-y^{\prime}=f(x)$ 的通解为  

$$
y=C_{1}+C_{2}\,\mathbf{e}^{\prime}+\int_{0}^{x}\mathbf{e}^{\prime}\,\mathrm{d}t\int_{0}^{x-t}f(u\,)\,\mathrm{d}u\,(C_{1}\,,C_{2}
$$  

例 15. 10（仅数学一）欧拉方程 $x^{\,2}\;{\frac{\mathrm{d}^{2}\,y}{\mathrm{d}x^{\,2}}}+4x\;{\frac{\mathrm{d}y}{\mathrm{d}x}}+2y=0(x>0)$ 的通解为  
【解】应填 $y=\frac{C_{1}}{x}+\frac{C_{2}}{x^{\;2}}$ ，其中 $C_{1}\,,C_{2}$ 为任意常数.  

由题设， $x>0$ ，令 $\boldsymbol{x}=\mathbf{e}^{t}$ ，则  

$$
{\frac{\mathrm{d}y}{\mathrm{d}x}}={\frac{\mathrm{d}y}{\mathrm{d}t}}\cdot{\frac{\mathrm{d}t}{\mathrm{d}x}}={\frac{1}{x}}\,{\frac{\mathrm{d}y}{\mathrm{d}t}}\,,
$$  

$$
\frac{\mathrm{d}^{2}y}{\mathrm{d}x^{\,2}}=-\frac{1}{x^{\,2}}\,\frac{\mathrm{d}y}{\mathrm{d}t}+\frac{1}{x}\,\frac{\mathrm{d}^{2}y}{\mathrm{d}t^{\,2}}\cdot\frac{\mathrm{d}t}{\mathrm{d}x}=\frac{1}{x^{\,2}}\Big(\frac{\mathrm{d}^{2}y}{\mathrm{d}t^{\,2}}-\frac{\mathrm{d}y}{\mathrm{d}t}\Big)\;,
$$  

代人原方程，得 $\frac{\mathrm{d}^{2}y}{\mathrm{d}t^{2}}+3\ \frac{\mathrm{d}y}{\mathrm{d}t}+2y=0$ ,解此方程得通解为  

$y=C_{1}\,{\mathrm{e}}^{-t}+C_{2}\,{\mathrm{e}}^{-2t}={\frac{C_{1}}{x}}+{\frac{C_{2}}{x^{\,2}}}(C_{1}\,,C_{2}\,$  

[例 15. 11]以 $y_{1}=t\,\mathrm{e}^{\prime}\,,y_{2}=\sin\,2t$ 为两个特解的四阶常系数齐次线性微分方程为（)  

$$
\begin{array}{r l}&{(\mathrm{A})y^{(4)}-2y^{w}+5y^{\prime\prime}-8y^{\prime}+4y=0}\\ &{(\mathrm{B})y^{(4)}-2y^{w}+5y^{\prime\prime}+8y^{\prime}+4y=0}\\ &{(\mathrm{C})y^{(4)}+2y^{w}+5y^{\prime\prime}-8y^{\prime}+4y=0}\\ &{(\mathrm{D})y^{(4)}-2y^{w}-5y^{\prime\prime}-8y^{\prime}+4y=0}\end{array}
$$  

【解】应选(A).  

由 $y_{\mathrm{~l~}}\!=\!t\,\mathrm{e}^{t}$ 可知 $\lambda=1$ 至少为二重根，由 $y_{2}=\sin2t$ 可知 $\lambda=\pm\,2\mathrm{i}$ 至少是单复根,故所求方程对应的特征方程的根为 $\lambda_{\textrm{1}}\!=\!\lambda_{\textrm{2}}\!=\!1\,,\!\lambda_{\textrm{3}}\!=\!2\mathrm{i}\,,\!\lambda_{\textrm{4}}\!=\!-\,2\mathrm{i}.$ 其特征方程为  

$$
(\lambda-1)^{2}(\lambda^{2}+4)=\lambda^{4}-2\lambda^{3}+5\lambda^{2}-8\lambda+4=0.
$$  

故所求微分方程为 $y^{(4)}-2y^{m}+5y^{\prime\prime}-8y^{\prime}+4y=0$  

# 四用换元法求解微分方程  

$1.$ 用求导公式逆用来换元  

2.用自变量、因变量或x，y地位互换来换元  

例15.12微分方程cos $y\cdot y^{\prime}-\sin\;y=\mathrm{e}^{x}$ 的通解为  

【解】应填sin $y=\mathbf{e}^{x}\left(x+C\right)$ ，其中 $C$ 为任意常数. $u=\sin\ y$ ，则cos ${\boldsymbol{y}}\cdot{\boldsymbol{y}}^{\prime}={\boldsymbol{u}}^{\prime}$ ,代人方程，得到一阶线性微分方程 $u^{'}-u=\mathbf{e}^{x}$ .故  

$$
u=\mathrm{e}^{\int_{0}^{\mathrm{d}x}\,\left(\int\mathrm{e}^{x}\,\cdot\,\mathrm{e}^{-\int_{0}^{\mathrm{d}x}}\,\mathrm{d}x\,+C\right)}\,=\mathrm{e}^{x}\,(x\,+C)\,,
$$  

即sin $y=\mathbf{e}^{x}\left(x+C\right)$ 为所求通解，其中 $C$ 为任意常数.  

例15.13(1)将 $_x=x\left(y\right)$ 的微分方程 $\frac{\mathrm{d}^{2}x}{\mathrm{d}y^{2}}+(y+\sin\,x\,)\left(\frac{\mathrm{d}x}{\mathrm{d}y}\right)^{3}=0$ 化成 $y=y\left(x\,\right)$ 的微分方程，并求出满足初始条件 $x\left(0\right)=0\,,x^{\,^{\prime}}(0)=\frac{2}{3}$ 的特解 $_{y}(x)$ ；  
# 比亨高等数学18讲  

（2）利用(1）的结论,求由曲线 $x=x\left(y\right)$ ,直线 $y=y\left(\pi\right)$ 及 $_y$ 轴围成的平面图形 $D$ 绕 $_y$ 轴旋转一周而成的旋转体的体积 $V$  

[解](1)利用 $\frac{\mathrm{d}x}{\mathrm{d}y}=\frac{1}{y^{\prime}}$ 及 ${\frac{\operatorname{d}^{2}x}{\operatorname{d}y^{2}}}=-{\frac{y^{\prime\prime}}{(y^{\prime})^{3}}}$ ,可将 $\frac{\mathrm{d}^{2}x}{\mathrm{d}y^{2}}+(y+\sin\,x\,)\left(\frac{\mathrm{d}x}{\mathrm{d}y}\right)^{3}=0$ 化成 $y^{\prime\prime}-y=$ sin $_x$ ,解此常系数非齐次线性微分方程得  

$$
y=C_{1}\,\mathrm{e}^{x}+C_{2}\,\mathrm{e}^{-x}-{\frac{1}{2}}\mathrm{sin}\ x\,.
$$  

又 $x\left(0\right)=0\,,x^{\,^{\prime}}(0)=\frac{2}{3}$ ，可知  

$$
\begin{array}{c}{{y\left(0\right)=C_{1}+C_{2}=0\,,}}\\ {{{}}}\\ {{y^{\prime}(0)=C_{1}-C_{2}-\displaystyle\frac{1}{2}=\displaystyle\frac{3}{2},}}\end{array}
$$  

可得 $C_{1}=1,C_{2}=-1$ ,特解为  

$$
y(x)=\mathrm{e}^{x}-\mathrm{e}^{-x}-{\frac{1}{2}}\mathrm{sin}\ x\,.
$$  

（2）由于 ${\mathsf{y}}^{\prime}(x)\!=\!{\mathsf{e}}^{x}+{\mathsf{e}}^{-x}-{\frac{1}{2}}{\mathsf{c}}$ OS $x>0$ ，因此 $y=y\left(x\right)$ 单调增加，且 $y\left(0\right)=0$ ,故它在第一象限内的图形及平面图形 $D$ 如图15-1所示.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b7660f0ecc449950f2a95942c803fb8f0ca2bec85c628faa420d8a4173f84a2d.jpg)  

>矩形 OABC 绕 y轴$=\uppi^{3}\left(\mathrm{e}^{\pi}-\mathrm{e}^{-\pi}\right)-2\uppi\displaystyle\int_{0}^{\pi}\!x\left(\mathrm{e}^{\imath}-\mathrm{e}^{-\imath}-\frac{1}{2}\sin\,x\right)\mathrm{d}x$ 转体周而成的旋 T $\begin{array}{l}{\displaystyle=\pi^{3}\,(\mathrm{e}^{\star}-\mathrm{e}^{-\pi})-2\pi\Big\lceil_{0}^{\star}\mathrm{zd}\Big(\mathrm{e}^{\tau}+\mathrm{e}^{-x}+\frac{1}{2}\mathrm{cos}\ x\Big)}\\ {\displaystyle=\pi^{3}\,(\mathrm{e}^{\star}-\mathrm{e}^{-\pi})-2\pi\Big[\Big(\mathrm{e}^{\tau}+\mathrm{e}^{-x}+\frac{1}{2}\cos x\Big)x\Big\rceil_{0}^{\star}-\Big\lceil_{0}^{\star}\Big(\mathrm{e}^{\tau}+\mathrm{e}^{-\tau}+\frac{1}{2}\cos x\Big)\,\mathrm{d}x\Big]}\\ {\displaystyle=\pi^{3}\,(\mathrm{e}^{\star}-\mathrm{e}^{-\pi})-2\pi^{2}\,\Big(\mathrm{e}^{\star}+\mathrm{e}^{-x}-\frac{1}{2}\Big)+2\pi\Big(\mathrm{e}^{\tau}-\mathrm{e}^{-x}+\frac{1}{2}\sin x\Big)\Big\mid_{0}^{\star}}\\ {\displaystyle=\pi^{3}\,(\mathrm{e}^{\star}-\mathrm{e}^{-x})-2\pi^{2}\,\Big(\mathrm{e}^{\star}+\mathrm{e}^{-\pi}-\frac{1}{2}\Big)+2\pi(\mathrm{e}^{\star}-\mathrm{e}^{-\tau})}\\ {\displaystyle=(\pi^{3}+2\pi)\,(\mathrm{e}^{\star}-\mathrm{e}^{-\pi})-2\pi^{2}\,(\mathrm{e}^{\tau}+\mathrm{e}^{-\pi})+\pi^{2}.}\end{array}$ 1  

# 五应用题  

$^{1,}$ 用极限、导数或积分等式建方程  
#  $^{2,}$ 用几何应用建方程  

# （1）用曲线切线斜率.  

$$
k=f^{\prime}(x_{0})=\tan\alpha.
$$  

（2）用两曲线 $f(x)$ 与 $g\left(x\right)$ 的公切线斜率.  

$$
f^{\prime}(x_{0})=g^{\prime}(x_{0}).
$$  

(3) 用截距.  

如，令 $X=Y$ ,建等式(方程).  

(4)用面积.  

$$
\int_{a}^{b}f(x)\,\mathrm{d}x.
$$  

(5) 用体积.  

$$
V_{\scriptstyle\!\displaystyle{r}}=\!\!\int_{\,\!\!a}^{b}\pi f^{2}\left(\chi\right)\!\mathrm{d}x\,,V_{\scriptstyle\!\displaystyle{y}}=\!\!\int_{\,\!a}^{b}2\pi x\,\mid\,f(x\,)\,\mid\,\mathrm{d}x.
$$  

(6)用平均值.  

$$
{\overline{{f}}}={\frac{1}{b-a}}{\int_{a}^{b}f(x)\mathrm{d}x}=f({\pmb{\xi}}).
$$  

（7）用弧长.（仅数学一、数学二）  

$$
s=\!\int_{a}^{b}\sqrt{1+(y_{x}^{\prime})^{2}}\,\mathrm{d}x.
$$  

（8）用侧面积.（仅数学一、数学二）  

$$
S=\!\int_{a}^{b}2\pi\mid y\left(x\right)\mid\sqrt{1+\left(y_{x}^{'}\right)^{2}}\,\mathrm{d}x.
$$  

（9）用曲率.（仅数学一、数学二）  

$$
k=\frac{\mid y^{\prime\prime}\mid}{\left[1+(y^{\prime})^{2}\right]^{\frac{3}{2}}}.
$$  

（10）用形心.（仅数学一、数学二）  

$$
{\overline{{x}}}={\frac{\displaystyle\iint_{x\,{\mathrm{d}}\sigma}}{\displaystyle\iint_{\,{\mathrm{}}D}\!\!\!\!\mathrm{d}\sigma}},{\overline{{y}}}={\frac{\displaystyle\iint_{y\,{\mathrm{d}}\sigma}}{\displaystyle\iint_{\,{\mathrm{}}D}\!\!\!\!\mathrm{d}\sigma}}.
$$  

例15.14设 $f(u\,,v\,)$ 具有连续偏导数,且满足 $f_{\;\;u}^{\prime}(u\,,v)+f_{\;\;v}^{\prime}(u\,,v)=u v$ ，则函数 $_y=$ $\mathsf{e}^{-2x}f(x\,,\boldsymbol{x}\,)$ 满足条件 $y\,{\Big|}_{x\,=\,0}=1$ 的表达式为  

[解]应填 $y=\left({\frac{x^{3}}{3}}+1\right)\mathrm{e}^{-2x}$  
阳宁高等数学18讲  

$$
y^{\prime}=-2\mathrm{e}^{-2x}f(x\,,x\,)+\mathrm{e}^{-2x}f_{\;\;u}^{\prime}(x\,,x\,)+\mathrm{e}^{-2x}f_{\;\;v}^{\prime}(x\,,x\,)=-\,2y+x^{2}\,\mathrm{e}^{-2x}\;,
$$  

因此， $_y$ 满足一阶线性微分方程 $y^{\prime}+2y=x^{2}\,\mathrm{e}^{-2x}$ ,其通解为  

$$
y=\mathrm{e}^{-\!\int\!2\mathrm{d}x}\left(\int\!x^{\,2}\,\mathrm{e}^{-2x}\,\mathrm{e}^{\int\!2\mathrm{d}x}\,\mathrm{d}x\,+C\right)\!=\!\left({\frac{x^{\,3}}{3}}+C\right)\mathrm{e}^{-2x}\,.
$$  

由 $y\,{\Big|}_{x=0}=1$ ,得 $C=1$ ,所以 $y=\left({\frac{x^{3}}{3}}+1\right)\mathrm{e}^{-2x}$  

例 15 15设 $\phi\left(x\right)$ 连续， $y_{1}\cdot y_{2}$ 是二阶齐次线性微分方程  

$$
y^{\prime\prime}+\frac{\sqrt{1-x^{2}}}{x}y^{\prime}+p(x\,)y=0(0<x<1)
$$  

的两个线性无关解，记 $f(x)=y_{1}y_{2}^{\prime}-y_{2}y_{1}^{\prime}$  

（1）求 $f(x)$ 满足的一阶微分方程；  

（2）求 $f(x)$ 的表达式  

【解】（1）由题意得  

$$
\begin{array}{c}{{f^{\prime}(x\,)=(y_{1}y_{2}^{\prime}\!-\!y_{2}y_{1}^{\prime})^{\prime}={y_{1}^{\prime}y_{2}^{\prime}\!+\!y_{1}y_{2}^{\prime\prime}\!-\!y_{2}^{\prime}y_{1}^{\prime}\!-\!y_{2}y_{1}^{\prime\prime}\!\!=\!\!y_{1}y_{2}^{\prime\prime}\!-\!y_{2}y_{1}^{\prime\prime}}}}\\ {{\mathrm{}}}\\ {{=y_{1}\left[\!-\!{\frac{\sqrt{1-x^{2}}}{x}}{y_{2}^{\prime}}\!-\!p\left(x\,)y_{2}\right]\!-\!y_{2}\left[\!-\!{\frac{\sqrt{1-x^{2}}}{x}}{y_{1}^{\prime}}\!-\!p\left(x\,\right)y_{1}\right]}}\\ {{\mathrm{}}}\\ {{=\!-\!{\frac{\sqrt{1-x^{2}}}{x}}(y_{1}y_{2}^{\prime}\!-\!y_{2}y_{1}^{\prime})=\!-\!{\frac{\sqrt{1-x^{2}}}{x}}f(x\,),}}\end{array}
$$  

故 $f(x)$ 满足的一阶微分方程为  

$$
f^{\prime}(x)+\frac{\sqrt{1-x^{2}}}{x}f(x)=0.
$$  

$$
\begin{array}{l}{\displaystyle\int\frac{\sqrt{1-x^{2}}}{x}\mathrm{d}x=\int\frac{\cos^{2}t}{\sin{t}}\mathrm{d}t=\int\frac{1-\sin^{2}t}{\sin{t}}\mathrm{d}t=\int\csc{t}\,\mathrm{d}t\,-\int\sin{t}\,\mathrm{d}t}\\ {\displaystyle\qquad\qquad=\ln{\,\vert\,\csc{t-\cot{t}}\,\,\vert+\cos{t}+C_{2}=\ln{\bigg\vert\frac{1}{x}-\frac{\sqrt{1-x^{2}}}{x}\bigg\vert+\sqrt{1-x^{2}}}}\,,}\\ {\displaystyle\qquad\qquad=\ln{\frac{1-\sqrt{1-x^{2}}}{x}}+\sqrt{1-x^{2}}+C_{2}\,,}\end{array}
$$  

故  

$$
f(x)=C_{1}\mathrm{e}^{-\sqrt{\frac{\sqrt{1-x^{2}}}{x}}\mathrm{d}x}=C_{1}\mathrm{e}^{-\left(\mathrm{i}\frac{\mathrm{i}-\sqrt{1-x^{2}}+\sqrt{1-x^{2}}+C_{2}}{x}\right)}=\frac{C x\,\mathrm{e}^{-\sqrt{1-x^{2}}}}{1-\sqrt{1-x^{2}}}(0<x<1)\,,
$$  

其中 $C$ 是任意常数.  

例15.16 已知函数 $f(x),g(x)$ 满足方程 $f^{\prime}(x)\,{-}\,g(x)\,{=}\,\,\mathrm{e}^{x}$ 及$g^{\prime}(x)-f(x)=0,f(0)=$  $g(0)=\,0$ ，计算 $\int_{0}^{1}\!\mathrm{e}^{-x^{2}}\,\big[f^{\prime}(x\,)-2x g^{\prime}(x\,)\big]\mathrm{d}x\,.$  
【解】由 $f^{\prime}(x)-g(x)=\mathbf{e}^{x}\,,g^{\prime}(x)=f(x)$ ,得  

$$
g^{\prime\prime}(x)-g(x)={\sf e}^{x}\,,
$$  

解此二阶微分方程，得  

$$
g\left(x\right)=C_{1}\,\mathrm{e}^{x}+C_{2}\,\mathrm{e}^{-x}+\frac{1}{2}x\,\mathrm{e}^{x}.
$$  

由 $g^{\prime}(0)=f(0)=g(0)=0$ ,得 $C_{1}=-\frac{1}{4},C_{2}=\frac{1}{4}$ ，故  

$$
g\left(x\right)=-\,\frac{1}{4}(\,\mathrm{e}^{x}-\mathrm{e}^{-x}\,)+\frac{1}{2}x\,\mathrm{e}^{x}\,,
$$  

$$
f(x)={\frac{1}{4}}(\mathbf{e}^{x}-\mathbf{e}^{-x}\,)+{\frac{1}{2}}x\,\mathbf{e}^{x}.
$$  

故  

$$
\begin{array}{r l}&{\quad\mathrm{e}^{-x^{2}}\big[f^{\prime}(x)-2x g^{\prime}(x)\big]\!=\!\mathrm{e}^{-x^{2}}\big[f^{\prime}(x)-2x f(x)\big]}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad=\mathrm{e}^{-x^{2}}f^{\prime}(x)+\mathrm{e}^{-x^{2}}(-2x)f(x)=\big[\mathrm{e}^{-x^{2}}f(x)\big]^{\prime},}\\ &{\bigg[\!\bigg]_{0}^{1}\mathrm{e}^{-x^{2}}\big[f^{\prime}(x)-2x g^{\prime}(x)\big]\!\mathrm{d}x=\mathrm{e}^{-x^{2}}f(x)\bigg|_{0}^{1}}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad=\mathrm{e}^{-1}f(1)-f(0)=\mathrm{e}^{-1}\Big(\displaystyle\frac{\mathrm{e}-\mathrm{e}^{-1}}{4}+\displaystyle\frac{1}{2}\mathrm{e}\Big)}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad=\frac{3}{4}-\displaystyle\frac{1}{4\mathrm{e}^{2}}.}\end{array}
$$又  

例15.17已知 $f(x y)=y f(x)+x f(y)$ 对任意正实数 $x\cdot y$ 均成立,且 $f^{\prime}(1)={\mathfrak{e}}$ ，求 $f(x y)$ 的极小值.  

【解】对式子 $f(x y)=y f(x)+x f(y)(x\,,y>0)$ ，令 $x=1$ ,则 $f(y)=y f(1)+f(y)$ ,即$f(1)=0$  

又当 $x>0$ 时，  

$$
{\begin{array}{r l}&{f^{\prime}(x)={\frac{\operatorname{lim}_{x}f(x+\Delta x)-f(x)}{\Delta x}}}\\ &{\qquad={\frac{f}{\sin\alpha}}{\frac{f}{\sin\alpha}}\left[\frac{x\left(1+{\frac{\Delta x}{x}}\right)}{\Delta x}\right]-f(x)}\\ &{\qquad={\frac{x f\left(1+{\frac{\Delta x}{x}}\right)+\left(1+{\frac{\Delta x}{x}}\right)f(x)-f(x)}{\sin\alpha}}}\\ &{\qquad={\frac{\operatorname{lim}_{x}\alpha f\left(1+{\frac{\Delta x}{x}}\right)+\left(1+{\frac{\Delta x}{x}}\right)(f(x)-f(x))}{\Delta x}}}\\ &{\qquad={\frac{\operatorname{lim}_{x}\alpha}{\sin\alpha}}-{\frac{\operatorname{lim}_{x}\alpha}{x}}+{\frac{f(x)}{x}}}\\ &{\qquad=f^{\prime}(1)+{\frac{f(x)}{x}}=\mathrm{e}+{\frac{f(x)}{x}},}\end{array}}
$$  

即$f^{\prime}(x)+\left(-{\frac{1}{x}}\right)f(x)=\mathbf{e}$ ，于是  
# 比宁高等数学18讲  

$$
f(x\,)=\mathrm{e}^{-\int\left(-{\frac{1}{x}}\right)\,\mathrm{d}x}\,\left[\int\!\mathrm{e}^{\int\left(-{\frac{1}{x}}\right)\,\mathrm{d}x}\,\mathrm{ed}x+C\right]\!={x\left(\,\mathrm{eln}\;x+C\right)}.
$$  

由 $f(1)=0$ ,有 $C=0$ ，即 $f(x\,)=\exp\ln\,x$  

故$f(x y)\mathop{=}\exp\ln(x y)$ ，令 $x y=u$ ，则有  

$$
f(u\,)=\mathsf{e}u\ln\,u\,,f^{\prime}(u\,)=\mathsf{e}(\ln\,u+1)\,\frac{\sideset{}{'}}{\rightharpoondown}0\,,
$$  

解得 $u=\mathrm{e}^{-1}\,,f^{\prime\prime}(u\,)={\frac{\mathrm{e}}{u}}\,,f^{\prime\prime}(\,\mathrm{e}^{-1}\,)=\mathrm{e}^{2}>0$ ，于是 $f(u\,)$ 的极小值为 $f({\ e}^{-1})=-1$ ,即 $f(x y)$ 的极小值为－1.  

# 3.用变化率建方程  

例 15. 18设一个地区人口的增长率与当时的人口总数成正比， $N(t)$ 表示在 $\boldsymbol{t}$ 时刻该地区的人口总量， $\boldsymbol{N}_{0}$ 是初始时刻 $\scriptstyle t\,=\,0$ 时的人口数，比例为 $r\!-\!b N(t)(r\!-\!b N(t)\!>\!0)$ ，求 $N(t)$ 的表达式.  

【解】由题设，  

$$
\frac{\mathrm{d}\big[N(t)\big]}{\mathrm{d}t}=\big[r-b N(t)\big]N(t)\,,
$$  

分离变量得  

$$
\frac{\mathrm{d}\big[N(t)\big]}{\big[r-b N(t)\big]N(t)}=\mathrm{d}t\,,
$$  

由待定系数法，得  

$$
\frac{1}{\left[r-b N(t)\right]N(t)}=\frac{A}{r-b N(t)}+\frac{B}{N(t)},
$$  

即  

$$
1=A N(t)+B\big[r-b N(t)\big],
$$  

令 $N(t)=0$ 得 $B={\frac{1}{r}}$ 令 $N(t)=\frac{r}{b}$ 得 $A={\frac{b}{r}}$ 即  

$$
\frac{1}{r}\left[\frac{1}{N(t)}+\frac{b}{r-b N(t)}\right]{\bf d}\Big[N(t)\Big]={\bf d}t\,,
$$  

两边积分得  

即  

$$
\begin{array}{c}{{\displaystyle{\ln N(t)-\ln[r-b N(t)]=r t+C_{1}}\cdot}}\\ {{\displaystyle{\frac{N(t)}{r-b N(t)}=C\mathrm{e}^{\prime t}}\,,}}\end{array}
$$  

代人初始条件 $N(t)\left|_{t=0}=N_{\mathrm{0}}\right.$ 得 $C=\frac{N_{\circ}}{r-b N_{\circ}}$ 整理得  

$$
N(t)=\frac{r}{b+\left(\frac{r}{N_{\circ}}-b\right)\mathrm{e}^{-r t}}.
$$  

【注】常称为人口增长问题.  
例 15.19在 $_{x}O y$ 平面上，设 $\mid P Q\mid=1$ ,初始时刻 $P$ 在原点， $\boldsymbol{Q}$ 在(1,0)点,若 $P$ 点沿着 $_y$ 轴的正方向移动,且 $\boldsymbol{Q}$ 点的运动方向始终指向 $P$ 点，求 $\boldsymbol{Q}$ 点的运动轨迹.  

【解】如图15-2所示,当 $P$ 点沿着 $_y$ 轴向上移动时,记 $\boldsymbol{Q}$ 点的轨迹形成曲线 $y=y\left(x\right)$ ．并设曲线上 $\boldsymbol{Q}$ 点的坐标为 $(x\,,y\,)\,,P$ 点坐标为(0,Y)，由$\mid P Q\mid=1$ ,得 >Y>y，故取负值  

由题意知， $Q P$ 的方向就是曲线 $y=y\left(x\right)$ 在 $(x\,,y\,)$ 点的切线方向，故  

$$
{\frac{\mathrm{d}y}{\mathrm{d}x}}={\frac{y-Y}{x}}=-{\frac{\sqrt{1-x^{2}}}{x}},
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f11f2f1b2df65083b1c887c69e064c0fe7693281d88ff3907873fb4c9b43bce2.jpg)  
图15-2  

两边积分得  

>亦可令x=sin1，其 $y=-\int\frac{\sqrt{1-x^{2}}}{x}\mathrm{d}x\,.$ 具体过程见例 15.15令$x=\cos\ t$ ，则  

$$
{\begin{array}{r l}&{y=-{\int}{\frac{{\sqrt{1-x^{2}}}}{x}}\mathrm{d}x={\int}{\frac{\sin^{2}t}{\cos t}}\mathrm{d}t={\int}{\frac{1-\cos^{2}t}{\cos t}}\mathrm{d}t}\\ &{\;\;={\Bigg\lceil}{\mathrm{sec~}}t\,\mathrm{d}t-{\int}\cos\,t\,\mathrm{d}t}\\ &{\;\;=\ln\;{\mid}\;\mathrm{sec~}t+\tan\,t\,\mid-\sin t+C}\\ &{\;\;=\ln\;{\Bigg\vert}{\frac{1}{x}}+{\frac{{\sqrt{1-x^{2}}}}{x}}{\Bigg\vert}-{\sqrt{1-x^{2}}}+C}\\ &{\;\;=\ln{\frac{1+{\sqrt{1-x^{2}}}}{x}}-{\sqrt{1-x^{2}}}+C.}\end{array}}
$$  

由 $x=1$ 时， ${y=0}$ ，可得 $C=0$ 故 $\boldsymbol{Q}$ 点的轨迹方程为  

$$
y=\ln{\frac{1+{\sqrt{1-x^{2}}}}{x}}-{\sqrt{1-x^{2}}}.
$$  

【注]这种曲线叫曳物线,又叫追踪曲线,这是因为当 $P$ 沿已知路径逃跑时,追踪者 $\boldsymbol{\mathsf{\Pi}}_{\alpha}$ 从某点出发，盯住 $P$ 追赶，则追踪者 $\boldsymbol{Q}$ 跑过的路线就是曳物线.  

例15.20（仅数学三）已知生产某产品的固定成本为 $a\left(a>0\right)$ ，生产 $_{x}$ 个单位的边际成本与平均成本之差为 ${\frac{x}{a}}-{\frac{a}{x}}$ ,且当产量的数值等于 $^{\,a}$ 时,相应的总成本为 $2\alpha$ ,则总成本 $C$ 与产量 $_{x}$ 的函数关系式为  

【解】应填 $C(x)=\frac{1}{\alpha}x^{2}+a$ ：由题意，得 ${\frac{\mathrm{d}[C(x\,)]}{\mathrm{d}x}}-{\frac{C(x\,)}{x}}={\frac{x}{a}}-{\frac{a}{x}},$ $C(\l,x)=\mathrm{e}^{-\left[\left(-\frac{1}{x}\right)\,\mathrm{d}x\,\left[\int\left(\frac{x}{a}-\frac{a}{x}\right)\mathrm{e}^{\int\left(-\frac{1}{x}\right)\,\mathrm{d}x}\,\mathrm{d}x\right.+C_{0}\right]}$  

故  
# 阳亨高等数学18讲  

$$
{\begin{array}{r l}&{=\operatorname{e}^{\ln x}\left[\!\!\left[\left({\frac{x}{a}}-{\frac{a}{x}}\right)\operatorname{e}^{-\ln x}\mathrm{d}x+C_{0}\right]\!={x}\left[\!\!\left[{\frac{1}{a}}-{\frac{a}{x^{2}}}\right)\mathrm{d}x+C_{0}\right]\!\right]}\\ &{={x}\left({\frac{x}{a}}+{\frac{a}{x}}+C_{0}\right)\!={\frac{1}{a}}{x}^{2}+a+C_{0}{x}\,,}\end{array}}
$$  

又由题设， $C(a)=2a$ ，得 $C_{0}=0$ ，于是 $C(x)=\frac{1}{a}x^{2}+a$  

一阶常系数线性差分方程的一般形式为  

$$
y_{t+1}+a y_{t}=f(t)\,,
$$  

其中 $f(t)$ 为已知函数， $^a$ 为非零常数.  

当 $f(t)\equiv0$ 时，方程 $\textcircled{1}$ 变为  

$$
y_{t+1}+\alpha y_{t}=0\,,
$$  

我们称 $f(t)\not\equiv0$ 时的 $\textcircled{1}$ 为一阶常系数非齐次线性差分方程， $\circledcirc$ 为其对应的一阶常系数齐次线性差分方程.  

1.齐次差分方程的通解  

通过迭代，并由数学归纳法可得 $\circledcirc$ 的通解为  

$$
y_{c}(t)\!=\!C\cdot(-\alpha)^{\prime}\,,
$$  

这里 $C$ 为任意常数.  

# 2.非齐次差分方程的解  

定理1  若 $y_{t}^{\star}$ 是非齐次差分方程 $\textcircled{1}$ 的一个特解， $_{y_{c}}(t)$ 是齐次差分方程 $\textcircled{2}$ 的通解,则非齐次差分方程 $\textcircled{1}$ 的通解为  

$$
y_{t}=y_{c}(t)+y_{t}^{\cdot}\,.
$$  

定理2若 ${\overline{{y}}}_{\ell}$ 与 $\tilde{y}_{\t}$ 分别是差分方程  

$$
y_{t+1}+a y_{t}=f_{1}(t)
$$  

和  

$$
y_{t+1}+\alpha y_{t}=f_{2}\left(t\right)
$$  

的解，则  

$$
\boldsymbol{y}_{t}=\overline{{\boldsymbol{y}}}_{t}+\tilde{\boldsymbol{y}}_{t}
$$  

是差分方程  

$$
y_{t+1}+a y_{t}=f_{1}(t)+f_{2}(t)
$$  

的解。  

非齐次差分方程 $\textcircled{1}$ 的特解 $y_{t}^{\star}$ 形式的设定见下表。  
![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/23d164fa57fac0456a2788b672a9325ba25d80a138b59f684741ca88cd4ceeb8.jpg)  

例15.21若某线性差分方程的通解为 $y_{\iota}=2^{\iota-1}\left(2C+t\right)$  $C$ 为任意常数），则该差分方程为  

【解】应填 $y_{t+1}-2y_{t}=2^{t}$  

由于线性差分方程的通解为  

故该差分方程为一阶非齐次线性差分方程，且 $Y_{\iota}=C\,\cdot\,2^{\iota}$ 为相应的齐次差分方程的通解，而  $y_{t}^{\cdot}=t\cdot2^{t-1}$ 为所求差分方程（非齐次线性差分方程）的一个特解，故可设所求差分方程为  

$$
y_{t+1}-2y_{t}=f(t).\quad
$$  

将特解 $y_{t}^{\star}=t\cdot2^{t-1}$ 代人，得 $f(t)=2^{t}$ ,故所求差分方程为 $y_{t+1}-2y_{t}=2^{t}$ ：  

例15. 22求方程满足给定条件的特解：  

$$
y_{t+1}+4y_{t}=17\cos{\frac{\pi}{2}}t\,,y_{0}=1.
$$  

【解】对应的齐次差分方程的通解为  

$$
y_{c}(t)=C(-4)^{t}.
$$  

由于  

$$
\begin{array}{r l}&{D=\left|\begin{array}{l l l}{4+\cos{\frac{\pi}{2}}}&&{\sin{\frac{\pi}{2}}}\\ &{}&\\ {-\sin{\frac{\pi}{2}}}&{4+\cos{\frac{\pi}{2}}}\end{array}\right|}\\ &{~~~=\left|\begin{array}{l l}{4}&{1}\\ {-1}&{4}\end{array}\right|=17\neq0\,,}\end{array}
$$  

故非齐次差分方程应具有特解形式为  

$$
y_{i}^{\star}=B_{\scriptscriptstyle0}\cos\,\frac{\pi}{2}t+B_{\scriptscriptstyle1}\sin\,\frac{\pi}{2}t.
$$  

代人原方程后可求得 $B_{0}=4\,,B_{1}=1.$ 于是，原方程的通解为  

$$
y_{\prime}=C(-4)^{\prime}+4\cos{\frac{\pi}{2}}t+\sin{\frac{\pi}{2}}t.
$$  

代人定解条件 ${y_{0}=1}$ ，得 $C=-3$ ,即得所求特解为  

$$
y_{\prime}=-3(-4)^{t}+4\cos{\frac{\pi}{2}}t+\sin{\frac{\pi}{2}}t.
$$  
# 无穷级数 (仪数学一、数学三)  

# 知识结构  

定义与S,  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c1cc371980956709519b0a5a195829b17da16d62b0cf583a01874f24ca2ab3b8.jpg)  
# 求和问题  

# 直接套公式  

用先积后导或先导后积求和函数用所给微分方程求和函数建立微分方程并求和函数综合题  

傅里叶级数（仅数学一）  

周期为2L的傅里叶级数  

狄利克雷收敛定理  
正弦级数和余弦级数  
只在[0，]上有定义的函数的正弦级数和余弦级数展开  

# 数项级数的判敛  

#  $^{1,}$ 定义与 S,  

$\mathbb{O}\sum_{n=1}^{\infty}u_{n}=u_{1}+u_{2}+\cdots+u_{n}+\cdots$ 叫无穷级数.  
$\circled{2}S_{n}=u_{1}+u_{2}+\cdots+u_{n}$ 叫级数的前 $_n$ 项和.   
 $\textcircled{3}\sum_{n=1}^{\infty}u_{n}$ 收敛 $\Theta\operatorname*{lim}_{n\to\infty}S_{n}$ 存在。  
 $\textcircled{4}\sum_{n=1}^{\infty}u_{n}$ 收敛 $\Rightarrow\operatorname*{lim}_{\varphi\,\dots\infty}u_{n}=0$  $\mathfrak{O}\sum_{n=1}^{\infty}(u_{n+1}-u_{n})$ 收敛 $\ \leftrightarrow\operatorname*{lim}_{n\to\infty}u_{n}$ 存在.  

【注]证 $S_{n}=(u_{2}-u_{1})+(u_{3}-u_{2})+\cdots+(u_{n+1}-u_{n})=u_{n+1}-u_{1}\,,$ 故 $\sum_{n=1}^{\infty}(u_{n+1}-u_{n})$ 收敛 $\varTheta\operatorname*{lim}_{n\to\infty}S$ 存在 $\ \Leftrightarrow\operatorname*{lim}_{n\rightarrow\infty}u$ ，存在。  

# 2.判敛法  

(1）正项级数 $\sum_{n\mathop{=}1}^{\infty}u_{n}\,,u_{n}\geqslant0.$  

$\textcircled{1}$ 基本定理.  
 $\sum_{n=1}^{\infty}u_{n}$ 收敛 $\Leftrightarrow\{S_{n}\}$ 有界。  
 $\circledcirc$ 比较判别法.  
给出两个正项级数 $\sum_{n=1}^{\infty}u_{n}$ 和 $\sum_{n=1}^{\infty}v_{n}$ ,如果从某项起有 $u_{n}\leqslant v_{n}$ 成立，则  
# 比亨高等数学18  

a.若 $\sum_{n=1}^{\infty}v_{n}$ 收敛，则 $\sum_{n=1}^{\infty}u_{n}$ 也收敛.   
b.若 $\sum_{n=1}^{\infty}u_{n}$ 发散,则 $\sum_{n=1}^{\infty}v_{n}$ 也发散.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/60cd0397d7b5a46d42fdcc0e657c5e971a85c79db3b13e15408bb31e9cb2d100.jpg)  

【注】(1)比较判别法及其极限形式实质上是跟“别人”比,故需要找到合适的尺度,（2）三个重要的尺度.  

$\textcircled{1}$ 等比级数 $\sum_{n=1}^{\infty}a q^{n-1}{\Bigg\vert}{\overline{{=}}}{\frac{a}{1-q}}$  $|q\,|<1$ ，[发散， $|q|\geqslant1$   
 $\textcircled{2}\textcircled{>}$ 级数 $\sum_{n=1}^{\infty}{\frac{1}{n^{p}}}\,\cdotp$ 收敛， $\mathcal{P}>1$ ，发散， $\mathcal{p}\leqslant1$   
 $\textcircled{3}$ 广义 $\pmb{\mathscr{p}}$ 级数 $\sum_{n=2}^{\infty}{\frac{1}{n\left(\ln\,n\right)^{p}}}\left\lbrace{\begin{array}{l}{\qquad1}\\ {\qquad n\left(\ln\,n\right)^{p}}\end{array}}\right\rbrace$ 收敛， $\phi>1$ ，发散， $\mathcal{p}\leqslant1$  $<1$ ，收敛，  
 $\circledast$ 比值判别法（达朗贝尔）， $\operatorname*{lim}_{n\rightarrow\infty}\frac{u_{n+1}}{u_{n}}=\rho\,\,\bigg\{\,\>\,1\,\,}\\ {\,=1\,,}$ ，发散，失效.   
 $\textcircled{5}$ 根值判别法(柯西), $|\operatorname*{lim}_{n\rightarrow\infty}\;\sqrt[n]{u_{\,n}}=\rho\,\left\{\begin{array}{l l}{<1}\\ {>1}\\ {=1\,,}\end{array}\right.$ ，收敛，，发散，失效. 和八圳叫汁（域西）  

设 $\sum_{n=1}^{\infty}u_{n}$ 为正项级数,若存在 $[1,+\infty)$ ）上单调减少的非负连续函数 $f(x)$ ，使得 $u_{n}=f(n)$ ，则级数 $\sum_{n=1}^{\infty}u_{n}$ 与反常积分 $\int_{1}^{+\infty}f(x)\mathrm{d}x$ 的敛散性相同.  
(2）交错级数 $\sum_{n\,=\,1}^{\infty}(-\,1\,)^{n-1}\,u_{\,n}\,,u_{\,n}>0.$ 莱布尼茨判别法： $\mathbb{\textregistered}_{n\rightarrow\infty}u_{n}=0\,;\mathcal{Q}u_{n}\geqslant u_{n+1}$ ,则级数收敛.  

【注]（1)若 $u_{n}=f(n)$ ，且 $f(\,\cdot\,)$ 可导，则可连续化为 $f(x)$ ,通过 $f^{\prime}(x)$ 的正负，判别 ${\pmb u}$ 的增 减性。  
(2) 莱布尼茨判别法只是充分条件,不是必要条件.  
例如交错级数 $\sum_{n=1}^{\infty}(-1)^{n}u_{n}=\sum_{n=1}^{\infty}\frac{1+(-1)^{n}\cdot\cdot2}{2^{n}}$ 的各项依次为 $-{\frac{1}{2}},{\frac{3}{2^{2}}},-{\frac{1}{2^{3}}},{\frac{3}{2^{4}}},-{\frac{1}{2^{5}}},\cdots,$ 可知 $u_{n}=\frac{2+(-1)^{n}}{2^{n}}$ ，有  
$u_{n+1}-u_{n}=\frac{2+(-1)^{n+1}-4-2\cdot(-1)^{n}}{2^{n+1}}=\frac{-2+3\cdot(-1)^{n+1}}{2^{n+1}}.$  

当 $^n$ 为偶数时, $u_{n+1}-u_{n}=-\frac{5}{2^{n+1}}<0$ ,当 $_n$ 为奇数时, $u_{n+1}-u_{n}=\frac{1}{2^{n+1}}>0$ ,不满足 $\circledcirc$ ，但交错级数 $\sum_{n=1}^{\infty}{\frac{1+(-1)^{\textit{n}}\cdot2}{2^{\textit{n}}}}=\sum_{n=1}^{\infty}{\frac{1}{2^{n}}}+\sum_{n=1}^{\infty}{\frac{(-1)^{\textit{n}}}{2^{n-1}}}$ 为两个收敛级数之和，故交错级数收敛.  

(3)任意项级数 $\sum_{n=1}^{\infty}u_{n}\,,u_{n}$ 符号无限制.  

若$\sum_{n=1}^{\infty}\mid u_{n}\mid$ 收敛，则称 $\sum_{n=1}^{\infty}u_{n}$ 绝对收敛;若 $\sum_{n=1}^{\infty}\left|\,u_{n}\,\right\vert$ 发散， $\sum_{n=1}^{\infty}u_{n}$ 收敛，则称 $\sum_{n=1}^{\infty}u_{n}$ 条件收敛.  

[注](1) 若 $\sum_{n=1}^{\infty}\mid u_{n}\mid$ 收敛( 即任意项级数 $\sum_{n=1}^{\infty}u\,,$ 绝对收敛),则 $\sum_{n=1}^{\infty}u_{n}$ 必收敛。  
(2)若 $\sum_{n=1}^{\infty}u_{n}\,,\sum_{n=1}^{\infty}v_{n}$ 均绝对收效,则 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 绝对收效。  
证因为 $\sum_{n=1}^{\infty}u_{n}\,,\sum_{n=1}^{\infty}v_{n}$ 均绝对收敛,且 $0\leqslant|\,\boldsymbol{u}_{n}\pm\boldsymbol{v}_{n}\,|\leqslant|\,\boldsymbol{u}_{n}\,|+|\,\boldsymbol{v}_{n}\,|$ ，所以 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 绝对收敛。  
(3)若 $\sum_{n=1}^{\infty}u_{n}$ 绝对收敛， $\sum_{n=1}^{\infty}v_{n}$ 条件收敛,则 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 条件收敛。  

证由于 $\sum_{n=1}^{\infty}u_{n}$ 绝对收敛， $\sum_{n=1}^{\infty}v_{n}$ 条件收敛,故 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 必收敛.假设 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 绝对收敛，而 $\sum_{n=1}^{\infty}u_{n}$ 。绝对收敛，那么 $\sum_{n=1}^{\infty}v_{n}$ 必绝对收敛，这与 $\sum_{n=1}^{\infty}v,$ 条件收敛矛盾，所以 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 条件收敛。  
(4) 若 $\sum_{n=1}^{\infty}u_{n}\,,\sum_{n=1}^{\infty}v_{n}$ 均条件收敛,则 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 收敛(可能绝对收敛,也可能条件收敛).。证因为 $\sum_{n=1}^{\infty}u_{n}\,,\sum_{n=1}^{\infty}v_{n}$ 均条件收效,所以 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 必收效。  
 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 可能绝对收敛,如 $\sum_{n=1}^{\infty}u_{n}=\sum_{n=1}^{\infty}(-1)^{n}\:\frac{1}{n}\,,\sum_{n=1}^{\infty}v_{n}=\sum_{n=1}^{\infty}\left[\frac{1}{n^{2}}-(-1)^{n}\:\frac{1}{n}\right]$ 均条件$\sum_{n=1}^{\infty}(u_{n}+v_{n})=\sum_{n=1}^{\infty}{\frac{1}{n^{2}}}$   
 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 也可能条件收敛,如 $\sum_{n=1}^{\infty}u_{n}=\sum_{n=1}^{\infty}\,(-\,1)^{\,n}\,\,{\frac{1}{n}}\,,\,\sum_{n=1}^{\infty}v_{n}=\sum_{n=1}^{\infty}\,(-\,1)^{\,n}\,\,{\frac{1}{\sqrt{n}}}$ 均条件收效，而 $\sum_{n=1}^{\infty}(u_{n}+v_{n})=\sum_{n=1}^{\infty}(-1)\,^{n}\Big(\frac{1}{n}+\frac{1}{\sqrt{n}}\Big)$ 条件收效。  

（5）一般说来,如果级数 $\sum_{n=1}^{\infty}\mid u_{n}\mid$ 发散,我们不能断定级数 $\sum_{n=1}^{\infty}u_{n}$ 也发散.但是,如果我们用比值判别法或根值判别法根据 $\operatorname*{lim}_{n\to\infty}\left|\frac{u_{n+1}}{u_{n}}\right|=\rho>1$ 或 $\operatorname*{lim}_{n\to\infty}{\sqrt[{n}]{|u_{n}|}}=\rho>1$ 判定级数 $\sum_{n=1}^{\infty}\mid u_{n}\mid$ 发散,那么我们可以断定级数 $\sum_{n=1}^{\infty}u_{n}$ 也必定发散.这是因为从 $\rho>1$ 可推知 $\mid u_{n}\mid\nrightarrow0\ (n\rightarrow\infty)$ ，从而 $u_{n}\neq0(n\rightarrow\infty)$ ,因此级数 $\sum_{n=1}^{\infty}u_{n}$ 是发散的。  

例如,级数 $\sum_{n=1}^{\infty}(-1)^{n}\ {\frac{1}{2^{n}}}{\Big(}1+{\frac{1}{n}}{\Big)}$ ，若记 $u_{n}=\frac{1}{2^{n}}\Big(1+\frac{1}{n}\Big)^{\ i}$ ，有 $\operatorname*{lim}_{n\to\infty}\,\sqrt[n]{u_{n}}=\operatorname*{lim}_{n\to\infty}\,\frac{1}{2}\Big(1+\frac{1}{n}\Big)^{n}=$  $\frac{\mathbf{e}}{2}>1$ ，可知 $u_{n}\neq0(n\rightarrow\infty)$ ,则原级数 $\sum_{n=1}^{\infty}(-1)^{n}\,{\frac{1}{2^{n}}}{\Big(}1+{\frac{1}{n}}{\Big)}^{n^{2}}$ 发散。  

(6)交错 $\pmb{\hat{P}}$ 级数 $\sum_{n=1}^{\infty}(-1)^{n-1}\,{\frac{1}{n^{p}}}\,\cdotp$ 绝对收敛， $\phi>1$ ，条件收敛， $0<p\leqslant1$  

# 3.常用结论  

$\textcircled{1}$ 若 $\sum_{n=1}^{\infty}u_{n}$ 收敛，则 $\sum_{n=1}^{\infty}\mid u_{n}\mid$ 不定(例如 $\sum_{n\,=\,1}^{\infty}(-\,1)^{n}\ \frac{1}{n}$ 收敛，但 $\sum_{n\mathop{=}1}^{\infty}\,\frac{1}{n}$ 发散)。  

$\left(u_{n}\geqslant0\right)$ 时， $\sum_{n=1}^{\infty}u_{\textit{n}}^{2}$ 收敛 $\operatorname*{lim}_{n\to\infty}u_{n}=0$ ，从某项起， $u_{n}<1,u_{n}^{2}<u_{n})$  $\circledcirc$ 设 $\sum_{n=1}^{\infty}u_{n}$ 收效，则 $\left|\,u_{\,n}\right|$ 任意时。 $\sum_{n=1}^{\infty}u_{\;n}^{2}$ 不定<例如 $\sum_{n\,=\,1}^{\infty}\,(-\,1\,)^{n}\;{\frac{1}{\sqrt{n}}}$ 收敛，但 $\sum_{n=1}^{\infty}{\frac{1}{n}}$ 发散)。  
$\left(u_{n}\right)\geqslant0$ 时， $\sum_{n\mathop{=}1}^{\infty}u_{n}u_{n+1}$ 收敛 $\left(u_{n}u_{n+1}\leqslant\frac{u_{n}^{2}+u_{n+1}^{2}}{2}\right)$  $\textcircled{3}$ 设 $\sum_{n=1}^{\infty}u_{n}$ 收敛，则 $\boldsymbol{u}_{n}$ 任意时， $\sum_{n\mathop{=}1}^{\infty}u_{n}u_{n+1}$ 不定（例如 $u_{\,n}=(-\,1)^{\,n}\;\frac{1}{\sqrt{n}}$ $u_{n}u_{n+1}=(-1)^{n}\;\frac{1}{\sqrt{n}}(-1)^{n+1}\;\frac{1}{\sqrt{n+1}}=-\frac{1}{\sqrt{n\left(n+1\right)}}\,,$ 级数发散)。  

$\circledast$ 设 $\sum_{n=1}^{\infty}u_{n}$ 收敛，则 $\sum_{n=1}^{\infty}{(-1)^{n}u_{n}}$ 不定(例如 $\sum_{n=1}^{\infty}{(-1)^{n}}\ {\frac{1}{n}}$ 收敛，但 $\sum_{n=1}^{\infty}{\frac{1}{n}}$ 发散)。  
 $\textcircled{5}$ 设 $\sum_{n=1}^{\infty}u_{n}$ 收敛，则 $\sum_{n=1}^{\infty}(-1)^{n}~\frac{u_{n}}{n}$ 不定(例如 $\sum_{n\,=\,2}^{\infty}(-\,1\,)^{n}\ \frac{1}{\ln\,n}$ 收敛，但 $\sum_{n=2}^{\infty}{\frac{1}{n\ln n}}$ 发散). $\left(u_{n}\geqslant0\right)$ 时， $\sum_{n=1}^{\infty}u_{2n}\,,\sum_{n=1}^{\infty}u_{2n-1}$ 均收敛，  
 $\circled{6}$ 设 $\sum_{n=1}^{\infty}u_{n}$ 收敛，则 $\boldsymbol{u}_{n}$ 任意时， $\sum_{n=1}^{\infty}u_{2n}\,,\sum_{n=1}^{\infty}u_{2n-1}$ 不定(例如 $1-{\frac{1}{2}}+{\frac{1}{3}}-{\frac{1}{4}}+{\frac{1}{5}}-$  ${\frac{1}{6}}+\cdots=\,\sum_{n\,=\,1}^{\infty}\,(-\,1)^{n-1}\,\,{\frac{1}{n}}$ 收敛，但是其奇数项和与偶数项和都发散).$\oslash$ 设$\sum_{n=1}^{\infty}u_{n}$ 收敛，则 $\sum_{n=1}^{\infty}(u_{2n-1}+u_{2n})$ 收敛.（收敛级数任意加括号所得的新级数仍收敛,且   
和不变，但反过来推要增加 $\operatorname*{lim}_{n\to\infty}u_{n}=0$ 的条件,即 $\sum_{n=1}^{\infty}(u_{2n-1}+u_{2n})$ 收敛且 $\operatorname*{lim}_{n\to\infty}u_{n}=0$ 则 $\sum_{n=1}^{\infty}u_{n}$ 收  
敛.因 $S_{2n}=\,(u_{1}+u_{2})+(u_{3}+u_{4})+\cdots+(u_{2n-1}+u_{2n})\,,\operatorname*{lim}_{n\to\infty}S_{2n}=\,S$ 存在， $S_{2n+1}=S_{2n}+u_{2n+1}$   
 $\operatorname*{lim}_{n\rightarrow\infty}S_{2n+1}=S+\operatorname*{lim}_{n\rightarrow\infty}{u_{2n+1}}=S$ ,即可得 $\sum_{n=1}^{\infty}u_{n}$ 收敛.） $\circled{8}$ 设 $\sum_{n=1}^{\infty}u\,,$ ，收敛，则 $\sum_{n=1}^{\infty}(u_{2n-1}-u_{2n})$ 不定。  

(例如 $u_{1}+u_{2}+u_{3}+u_{4}+u_{5}+u_{6}+\cdots=1-{\frac{1}{2}}+{\frac{1}{3}}-{\frac{1}{4}}+{\frac{1}{5}}-{\frac{1}{6}}+\cdots$ 收放，但 $\left(1+{\frac{1}{2}}\right)+\qquad$  $\left({\frac{1}{3}}+{\frac{1}{4}}\right)+\left({\frac{1}{5}}+{\frac{1}{6}}\right)+\cdots$ 发散。）  

$\begin{array}{r}{\left\{\displaystyle\sum_{n=1}^{\infty}\left(u_{n}+u_{n+1}\right)\right.}\\ {\displaystyle\left.\left\lfloor\sum_{n=1}^{\infty}\left(u_{n}-u_{n+1}\right)\right.\right.}\end{array}$ 收敛， $\sum_{n=1}^{\infty}u_{n}+\sum_{n=1}^{\infty}u_{n+1}$ 收敛，  
$\circledcirc$ 设$\sum_{n=1}^{\infty}u_{n}$ 收敛，则 收敛， $\sum_{n=1}^{\infty}u_{n}-\sum_{n=1}^{\infty}u_{n+1}$ 收敛.  
 $\circledcirc$ 若 $\sum_{n=1}^{\infty}\left|\,u_{n}\,\right\vert$ 收敛，则 $\sum_{n=1}^{\infty}u_{n}$ 收敛;若 $\sum_{n=1}^{\infty}u_{n}$ 发散,则 $\sum_{n=1}^{\infty}\left|\,u_{n}\,\right|$ 发散。  
$\mathfrak{V}$ 若莊 $\sum_{n=1}^{\infty}u_{n}^{2}$ 收敛，则 $\sum_{n=1}^{\infty}\,\frac{u_{\,n}}{n}$ 绝对收敛 $\biggl(\left|\frac{u_{n}}{n}\right|\leqslant\frac{1}{2}\Big(u_{n}^{2}+\frac{1}{n^{2}}\Big)\biggr)$  
$\textcircled{12}$ 设$\alpha\,,b\,,c$ 为非零常数,且 $a u_{n}+b v_{n}+c w_{n}=0$ ,则在 $\sum_{n=1}^{\infty}u_{n}\,,\sum_{n=1}^{\infty}v_{n}$ 和$\sum_{n=1}^{\infty}w_{n}$ 中只要有两个 级数是收敛的，另一个必收敛. $\textcircled{13}$ 若 $\sum_{n=1}^{\infty}u_{n}$ 收敛， $\sum_{n=1}^{\infty}v_{n}$ 收敛，则 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 收敛。 $\circledast$ 若 $\sum_{n=1}^{\infty}u_{\textit{n}}$ 收敛， $\sum_{n=1}^{\infty}v_{n}$ 发散，则 $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 发散。{un≥0,Un≥0时， $\sum_{n=1}^{\infty}(u_{n}+v_{n})$ 发散，$\textcircled{15}$ 若$\sum_{n=1}^{\infty}u_{\textit{n}}$ 发散， $\sum_{n=1}^{\infty}v_{n}$ 发散，则  $\left\lfloor u_{n}\,,v_{n}\right\rfloor$ 任意时， $\sum_{n=1}^{\infty}(u_{n}\pm v_{n})$ 不定。（见 $\circled{6}$ ）$\textcircled{16}$ 若莊 $\sum_{n=1}^{\infty}u_{n}$ 收敛， $\sum_{n=1}^{\infty}v_{n}$ 收敛，则  $\left(u_{n}\right)\geqslant0\,,v_{n}\geqslant0$ 时， $\sum_{n\mathop{=}1}^{\infty}u_{n}v_{n}$ 收敛 $\left(u_{\scriptscriptstyle n}v_{\scriptscriptstyle n}\leqslant\frac{u_{\scriptscriptstyle n}^{2}+v_{\scriptscriptstyle n}^{2}}{2}\right)$  $\boldsymbol{u}_{\u{n}}$ 任意， $v_{n}\geqslant0$ 时 $\sum_{n\,=\,1}^{\infty}\;\mid u_{\,n}\,\mid\,\cdot\,v_{\,n}$ 收敛 $\left(\operatorname*{lim}_{n\to\infty}\frac{\mid u_{n}\mid\bullet v_{n}}{v_{n}}=\operatorname*{lim}_{n\to\infty}\mid u_{n}\mid=0\right)\,,$  $\left\vert\boldsymbol{u}_{n}\right\vert$ 任意， $\boldsymbol{v}_{n}$ 任意时， $\sum_{n=1}^{\infty}u_{n}v_{n}$ 不定。（见 $\textcircled{3}$ ）  

熟练掌握以上结论，手上的招数多了，考试时解决相关选择题便游刃有余了.  

例 16. 1设 $\sum_{n=1}^{\infty}u_{n}$ 收敛， $\sum_{n=1}^{\infty}v_{n}$ 收敛，则().  
(A)若 $\sum_{n=1}^{\infty}u_{\{n\}}^{2}$ 收敛，则 $\sum_{n=1}^{\infty}\,\frac{u_{\,n}}{n}$ 收敛 (B) $\sum_{n=1}^{\infty}u_{n}v_{n}$ 收敛 (C) $\sum_{n=1}^{\infty}(u_{2n-1}+u_{2n})$ 和$\sum_{n=1}^{\infty}(u_{2n-1}-u_{2n})$ 均收敛 (D $)\sum_{n=1}^{\infty}{(-1)^{n}}\ {\frac{u_{n}}{n}}$ 收敛 【解】应选(A).  

答案见上面“3.常用结论”，（A）对应 $\textcircled{1]}$ ，(B）对应 $\textcircled{16}$ ，（C）对应 $\textcircled{7}$ ， $\circled{8}$ ,(D）对应 $\circled{5}$ 例 16.2]设 $\{\,u_{\textit{n}}\}$ 是单调增加的有界数列,则下列级数中收敛的是().  

(A) $\sum_{n=1}^{\infty}\,{\frac{u_{\,n}}{n}}$ $\begin{array}{l}{{\displaystyle(\mathrm{{B}})\sum_{n=1}^{\infty}(-1)^{n}\ \frac{1}{u_{n}}}}\\ {{\displaystyle(\mathrm{{D}})\sum_{n=1}^{\infty}\big(u_{n+1}^{2}-u_{n}^{2}\big)}}\end{array}$ (C) $\sum_{n=1}^{\infty}\left(1-\frac{u_{n}}{u_{n+1}}\right)$  

【解】应选(D).  
因为 $\left\{\,u_{\textit{n}}\right\}$ 是单调增加的有界数列，所以 $\left\lbrace u_{n}\right\rbrace$ 收敛，从而 $\smash{\{u_{n}^{2}\}}$ 收敛。  

因为 $\sum_{k\,=\,1}^{n}\,(\,u_{\,k+1}^{\,2}-u_{\,k}^{\,2}\,)=u_{\,n+1}^{\,2}-u_{\,1}^{\,2}$ ,所以  

$$
\operatorname*{lim}_{n\rightarrow\infty}\sum_{k\,=\,1}^{n}\,(\,u_{\,k+1}^{\,2}-u_{\,k}^{\,2}\,)=\operatorname*{lim}_{n\rightarrow\infty}(\,u_{\,n+1}^{\,2}-u_{\,1}^{\,2}\,)
$$  
存在，即 $\sum_{n=1}^{\infty}(u_{n+1}^{2}-u_{n}^{2})$ 收敛.应选(D).  

【注】本题也可利用排除法得到正确答案.  

取 $u_{n}\!=\!1\!-\!\frac{1}{n}$ 司 $\left\lbrace u_{n}\right\rbrace$ 是单调增加的有界数列，且 $\operatorname*{lim}_{n\to\infty}u_{n}=1.$ 这时 $\sum_{n=1}^{\infty}{\frac{u_{n}}{n}}\not\equiv\sum_{n=1}^{\infty}(-1)^{n}\,{\frac{1}{u_{n}}}$ 均发散，故可排除选项(A),(B).  

取$u_{n}=-\frac{1}{n}$ 则$\left\lbrace u_{n}\right\rbrace$ 是单调增加的有界数列，且 $1\!-\!\frac{u_{n}}{u_{n+1}}\!=\!-\frac{1}{n}.$ 这时 $\sum_{n=1}^{\infty}\left(1-\frac{u_{n}}{u_{n+1}}\right)$ 发散，故 可排除选项(C).  

综上可知,应选(D).  

例 16. 3下列级数中发散的是(  

$\sum_{n=1}^{\infty}\operatorname{e}^{\sin n-n}$ $(\mathrm{B})\sum_{n=2}^{\infty}\,\frac{\ln\,n}{n^{2}}$ $(\mathbb{C})\sum_{n=2}^{\infty}{\frac{(-1)^{n}}{n-\ln n}}$ 8(-1)” (A） (D)M n=2 √n +(- 1)"  

[解】应选(D).  

对于(A),记 $u_{n}=\mathrm{e}^{\sin n-n}$ .由于 $\operatorname*{lim}_{n\to\infty}\,{\sqrt[{n_{n}}]{u_{n}}}=\operatorname*{lim}_{n\to\infty}\mathrm{e}^{\frac{\sin n-n}{n}}=\mathrm{e}^{n\cdot\infty}^{({\frac{\sin n}{n}}-1)}=\mathrm{e}^{-1}<1$ ,故由根值判别法可知，（A）收敛.  

对于(B)，设 $f_{1}\left(x\right)=\frac{\ln{x}}{x^{2}}$ 则  

$$
f_{1}^{\prime}(x)\!=\!\frac{1-2\mathrm{ln}\;x}{x^{3}},
$$  

当 $x\geqslant2$ 时， $f_{\mathrm{~1~}}^{\prime}(x)<0$ ，即 $f_{\mathrm{~1~}}(\boldsymbol{x})$ 在 $[2,+\infty)$ 上非负且单调减少，且  

$$
\int_{2}^{+\infty}{\frac{\ln\,x}{{x}^{\,2}}}\mathrm{d}x=\!\int_{2}^{+\infty}\!\ln\,x\,\mathrm{d}\!\left(-\,{\frac{1}{x}}\right)\!=\!-{\frac{\ln\,x}{x}}\,{\Big|}_{2}^{+\infty}+\int_{2}^{+\infty}\,{\frac{1}{{x}^{\,2}}}\mathrm{d}x={\frac{\ln\,2+1}{2}},
$$  

故由正项级数的积分判别法知，（B）收敛.  

对于(C),这是交错级数，记 $u_{n}=\frac{1}{n-\ln n}$ 设 $f_{\mathit{2}}\left(\mathit{x}\right){=}\mathit{x}\left-\ln\mathit{x}$ 则 $f_{2}^{\prime}(x)\!=\!1\!-\!\frac{1}{x}$ 当 $x\geqslant2$ 时， $f_{2}^{\prime}(x)>0$ ，即 $f_{2}(x)$ 在 $[2,+\infty)$ 上单调增加,于是 $\frac{1}{f_{2}(x)}$ 在 $[2,+\infty)$ 上非负且单调减少，故 $u_{n}\geqslant u_{n+1}\,(n=2,3\,,\cdots)$ ，且 $\operatorname*{lim}_{n\to\infty}{\frac{1}{n-\ln n}}=0$ ，故由莱布尼茨判别法知，（C）收敛.  

对于(D),这是交带级数,记 $u_{n}=\frac{1}{\sqrt{n}+(-1)^{n}}$ ，显然不满足条件 $u_{n}\geqslant u_{n+1}$ ,故不能直接利用莱布尼茨判别法.但由于  

$$
{\frac{(-1)^{n}}{\sqrt{n}+(-1)^{n}}}={\frac{(-1)^{n}[\sqrt{n}-(-1)^{n}]}{n-1}}=(-1)^{n}\,{\frac{\sqrt{n}}{n-1}}-{\frac{1}{n-1}},
$$  

可知原级数可表示为一个交错级数 $\sum_{n=2}^{\infty}(-1)^{n}~\frac{\sqrt{n}}{n-1}$ 与一个发散的调和级数 $\sum_{n=2}^{\infty}\,\frac{1}{n-1}$ 之差.利  
张等高等数学18讲  

用莱布尼茨判别法容易验证级数 $\sum_{n\,=\,2}^{\infty}(-\,1\,)^{n}\;{\frac{\sqrt{n}}{n\,-\,1}}$ 收敛.因此，（D）发散.  

例16. 4已知级数 $\sum_{n\,=\,1}^{\infty}(-\,1)^{\,n}\,n\,\,{\sqrt{n}}\tan\,\,{\frac{1}{n^{\,a}}}$ 绝对收敛，级数 $\sum_{n=1}^{\infty}\ \frac{(-1)^{n}}{n^{3-\alpha}}$ 条件收敛，则( ）.  

$(\mathbf{A})0<\alpha\leqslant\frac{1}{2}$ $\begin{array}{l}{(\mathrm{B})1<\alpha<\frac{5}{2}}\\ {(\mathrm{D})\,\frac{5}{2}<\alpha<3}\end{array}$ $(\mathrm{C})1<\alpha<3$  

[解】应选(D).  

设$u_{n}=(-1)^{n}n\sqrt{n}\tan{\frac{1}{n^{\circ}}}$ ，则当 $n\rightarrow\infty$ 时， $\mid u_{n}\mid\sim\frac{1}{n^{\alpha-\frac{3}{2}}}$ ，故 $\sum_{n\mathop{=}1}^{\infty}\mid u_{n}\mid\ H\ H_{n}\mid\ \frac{\infty}{n-1}\ \frac{1}{n^{a-\frac{3}{2}}}$ 的敛散 性相同，因为 $\sum_{n\,=\,1}^{\infty}(-\,1)^{\,n}n\,{\sqrt{n}}\tan{\frac{1}{n^{\,a}}}$ 绝对收敛,所以 $\alpha-\frac{3}{2}>1$ ，即 $\alpha>\frac{5}{2}.$ 而由 $\sum_{n=1}^{\infty}{\frac{(-1)^{n}}{n^{3-a}}}$ 条件收敛可知 $0<3-\alpha\leqslant1$ ,即 $2\leqslant\alpha<3$ ：  

若使两个结论都成立，只有 $\frac{5}{2}<\alpha<3$ ,故选(D).  

例 16. 5若 $\sum_{n=1}^{\infty}n u_{n}$ 绝对收敛， $\sum_{n=1}^{\infty}\,\frac{v_{n}}{n}$ 条件收敛，则().(A) $\sum_{n=1}^{\infty}u_{n}v_{n}$ 条件收敛 (B) $\sum_{n=1}^{\infty}u_{n}v_{n}$ 绝对收敛 (C) $\sum_{n=1}^{\infty}(u_{n}+v_{n})$ 收敛 $\mathrm{(D)}\sum_{n=1}^{\infty}\mathrm{(}u_{n}+v_{n}\mathrm{)}$ 发散  

【解】应选(B).由$\sum_{n=1}^{\infty}\,\frac{v_{n}}{n}$ 条件收敛知， $\operatorname*{lim}_{n\to\infty}{\frac{v_{n}}{n}}=0$ ，故当 $_n$ 充分大时， $\left|\frac{v_{n}}{n}\right|\!<\!1$ ，所以  

$$
\left|\begin{array}{l}{u_{n}v_{n}}\end{array}\right|=\left|n u_{n}\,\cdot\,\frac{v_{n}}{n}\right|<\left|\begin{array}{l}{n u_{n}}\end{array}\right|,
$$  

由于 $\sum_{n=1}^{\infty}n u\,,$ ，绝对收敛，所以 $\sum_{n=1}^{\infty}u_{n}v_{n}$ 绝对收敛,故选项(B）正确,选项（A）不正确.  

由 $\sum_{n=1}^{\infty}n u_{n}$ 绝对收敛， $\operatorname*{lim}_{n\rightarrow\infty}{\frac{\mid u_{n}\mid}{\mid n u_{n}\mid}}\!=\!0$ ，可知 $\sum_{n=1}^{\infty}u_{n}$ 也绝对收敛;但 $\sum_{n=1}^{\infty}{\frac{v_{n}}{n}}$ 条件收敛， $\sum_{n=1}^{\infty}v_{n}$ 的敛散性不确定.例如，若 $v_{n}=\left(-1\right){}^{n}$ 则 $\sum_{n=1}^{\infty}\ {\frac{v_{n}}{n}}$ 条件收敛，但 $\sum_{n=1}^{\infty}v_{n}$ 发散.若 $v_{n}=\frac{(-1)^{n}}{\ln(n+1)}$ ，则 $\sum_{n=1}^{\infty}{\frac{v_{n}}{n}}$ 条件收敛，但 $\sum_{n=1}^{\infty}v_{n}$ 收敛.故选项(C),(D)都不正确.  

例 16. 6设数列 $\{x_{n}\}$ 满足 $\sin^{2}x_{\textsf{n}}\sin\,x_{\textsf{n+1}}+2\sin\,x_{\textsf{n+1}}=1\,,x_{\textsf{0}}={\frac{\pi}{6}}$ ，证明：  

(1）级数 $\sum_{n\,=\,0}^{\infty}(\sin\,x_{\,n+1}-\sin\,x_{\,n}\,)$ ）收敛；  
(2) lim sin $_{x}$ ，存在,且其极限值 $c$ 是方程 $x^{\,3}+2x-1=0$ 的唯一正根.  

[证](1)sin $x_{n+1}=\frac{1}{\sin^{2}x_{n}+2},x_{0}=\frac{\pi}{6}$ 故sin $x_{1}=\frac{4}{9},0<\sin\,x_{n}<\frac{1}{2},n=1,2,\cdots,$ $\begin{array}{r l}{\mid\sin x_{n+1}-\sin x_{n}\mid=\left|\frac{1}{\sin^{2}x_{n}+2}-\frac{1}{\sin^{2}x_{n-1}+2}\right|}&{}\\ &{\quad=\frac{\mid\sin^{2}x_{n-1}-\sin^{2}x_{n}\mid}{(\sin^{2}x_{n}+2)(\sin^{2}x_{n-1}+2)}}\\ &{\quad<\frac{\sin x_{n}+\sin x_{n-1}\mid}{4}\sin x_{n}-\sin x_{n-1}\mid}\\ &{\quad<\frac{1}{4}\mid\sin x_{n}-\sin x_{n-1}\mid<\cdots}\\ &{\quad<\left(\frac{1}{4}\right)^{\ast}\mid\sin x_{1}-\sin x_{0}\mid=\left(\frac{1}{4}\right)^{\ast}\cdot\frac{1}{18},}\end{array}$  

由于 $\sum_{n=0}^{\infty}\left({\frac{1}{4}}\right)^{n}$ 收敛，故根据正项级数的比较判别法知， $\sum_{n=0}^{\infty}\ |$ sin $x_{\!\;n+1}\,-\,\sin\;x_{\!\;n}$ 丨收敛，即 $\sum_{n\mathop{=}0}^{\infty}(\sin\,x_{\ n+1}-\sin\,x_{\ n})$ 绝对收敛，所以 $\sum_{n\mathop{=}0}^{\infty}(\sin\,x_{\,n+1}-\sin\,x_{\,n})$ 收敛，  

(2) $\sum_{n=0}^{\infty}(\sin\,x_{\,n+1}-\sin\,x_{\,n})$ 的前 $_n$ 项和 $\begin{array}{r l}&{S_{n}=\sin\,x_{1}-\sin\,x_{0}+\sin\,x_{2}-\sin\,x_{1}+\dots+\sin\,x_{n+1}-\sin\,x_{n}}\\ &{\quad=\sin\,x_{n+1}-\sin\,x_{0}\,,}\end{array}$  

由(1)知 $\operatorname*{lim}_{n\to\infty}S_{n}$ 存在,故limsin $x_{n+1}\frac{4\pi}{i e x}c$ ，由题设，有 $c^{3}+2c=1.$ 令 $f(x\,)\,{=}\,x^{3}+2x-1,x>$ 0，则 $f^{\prime}(x)\!=\!3x^{2}+2\!>\!0\,,f(x)$ 单调增加,又 $f(0)=-1<0\,,f(+\infty)>0$ ，故 $c$ 是方程 $x^{\,3}+$  $2x-1=0$ 的唯一正根.  

级数的收敛域1.有关概念  

# (1）函数项级数.  

设函数列 $\{u_{n}\left(x\right)\}$ 定义在区间 $I$ 上，称  

$$
u_{1}\left(x\,\right)+u_{2}\left(x\,\right)+u_{3}\left(x\,\right)+\cdots+u_{n}\left(x\,\right)+\cdots
$$  

为定义在区间 $I$ 上的函数项级数，记为 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ ，当 $_{\mathcal{x}}$ 取确定的值 $\boldsymbol{x}_{\mathit{\Pi}_{0}}$ 时， $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 成为常数项级数 $\sum_{n=1}^{\infty}u_{n}(x_{0})$  

(2)幂级数.  

若 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的一般项 $u_{\scriptscriptstyle n}\left(\boldsymbol{x}\right)$ 是 $_n$ 次幂函数，则称 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 为幂级数,它是一种特殊且常  
比宁高等数学18讲  

用的函数项级数，其一般形式为  

$$
\sum_{n=\alpha_{n}}^{\infty}(x-x_{0})^{n}=\alpha_{0}+\alpha_{1}(x-x_{0})+\alpha_{2}(x-x_{0})^{2}+\cdots+\alpha_{n}(x-x_{0})^{n}+\cdots,
$$  

7=0 其标准形式为 $\sum_{\eta\,=\,0}^{\infty}\alpha_{\,n}x^{\,n}=\alpha_{\,0}+\alpha_{\,1}x+\alpha_{\,2}x^{\,2}+\cdots+\alpha_{\,n}x^{\,n}+\cdots,$ 其中常数 $\alpha_{0}\,,\alpha_{1}\,,\cdots,\alpha_{n}\,,\cdots$ 为幂级数的系数.  

（3）收敛点与发散点  

若给定 $x_{\mathit{0}}\in I$ ,有 $\sum_{n=1}^{\infty}u_{n}(x_{0})$ 收敛,则称点 $x_{\circ}$ 为级数 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的收敛点;若给定 $x_{0}\in I$ ,有$\sum_{n=1}^{\infty}u_{n}(x_{0})$ 发散,则称点 $\boldsymbol{\mathcal{x}}_{\mathit{0}}$ 为级数 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的发散点.  

# (4）收敛域.  

函数项级数 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的所有收敛点的集合称为它的收敛域.  

$^{2,}$ 具体型问题(1）对于不缺项幂级数 $\sum_{n\mathop{=}0}^{\infty}\alpha_{n}x^{n}$  $\textcircled{1}$ 收敛半径的求法.  

若$\operatorname*{lim}_{n\to\infty}\left|{\frac{a_{n+1}}{a_{n}}}\right|=\rho$ ，则 $\sum_{n=0}^{\infty}a_{n}x^{n}$ 的收敛半径 $R$ 的表达式为 $R=\left\{\begin{array}{l l}{1}&{\rho\neq0\,,\,+\infty\,,}\\ {\rho}&{\rho=0\,,}\\ {0\,,}&{\rho=+\infty.}\end{array}\right.$  $\circledcirc$ 收敛区间与收敛域  

区间 $(-R\,,R\,)$ 为幂级数 $\sum_{n\mathop{=}0}^{\infty}a_{n}x^{n}$ 的收敛区间;单独考查幂级数在 $x=\pm R$ 处的敛散性就可 以确定其收敛域为 $(-R\,,R\,)$ 或$-\,R\,,R\,.$ ）或 $(-R,R]$ 或$[-R,R]$  

(2）对于缺项幂级数或一般函数项级数 $\sum u_{n}(x)$  

$\textcircled{1}$ 加绝对值，即写成 $\sum\mid u_{n}(x)\mid$   
 $\circledcirc$ 用正项级数的比值（或根值）判别法.  
令 $\operatorname*{lim}_{n\to\infty}{\frac{\mid u_{n+1}(x)\mid}{\mid u_{n}(x)\mid}}$ （或 $\operatorname*{lim}_{n\to\infty}^{n}\!\sqrt{\mid u_{n}\left(x\mid\right)\mid}\,<1$ ，求出收敛区间 $(a,b)$  $\textcircled{3}$ 单独讨论 $x=a\,,x=b$ 时 $\sum u_{n}\left(x\right)$ 的敛散性，从而确定收敛域.例16. 7 求幂级数 $\sum_{n=2}^{\infty}\frac{\frac{1}{2^{n}}+(-1)^{n}\cdot\frac{1}{3^{n}}}{n}(x-1)^{n}$ 的收敛域. 【解】令 $u_{n}=\frac{\frac{1}{2^{n}}+(-1)^{n}\cdot\frac{1}{3^{n}}}{n}$ 则  
$$
\rho=\operatorname*{lim}_{n\to\infty}\left|{\frac{u_{n+1}}{u_{n}}}\right|=\operatorname*{lim}_{n\to\infty}{\frac{\left({\frac{1}{2}}\right)^{n+1}+\left(-{\frac{1}{3}}\right)^{n+1}}{\left({\frac{1}{2}}\right)^{n}+\left(-{\frac{1}{3}}\right)^{n}}}\cdot{\frac{n}{n+1}}={\frac{1}{2}},
$$  

故$R=\frac{1}{\rho}=2$ ,由 $-2<x\mathrm{~--~}1<2$ ,得 $x\in(-1,3)$  

当 $x=-1$ 时，  

$$
\begin{array}{l}{\displaystyle\sum_{n=2}^{\infty}\,\frac{\displaystyle\frac1{2^{n}}+(-1)^{n}\cdot\frac1{3^{n}}}{n}(-\,2)^{n}=\displaystyle\sum_{n=2}^{\infty}\,\frac{(-\,1)^{n}+\left(\frac23\right)^{n}}{n}}\\ {\displaystyle=\sum_{n=2}^{\infty}(-\,1)^{n}\cdot\frac1{n}+\sum_{n=2}^{\infty}\,\frac1n\cdot\left(\frac23\right)^{n},}\end{array}
$$  

其中级数 $\sum_{n=2}^{\infty}(-1)^{n}\cdot{\frac{1}{n}}$ 收敛，又 $n\geqslant2$ 雞时 $\frac{1}{n}\cdot\left(\frac{2}{3}\right)^{n}<\left(\frac{2}{3}\right)$ ",故由正项级数的比较判别法可知，级数 $\sum_{n=2}^{\infty}{\frac{1}{n}}\cdot\left({\frac{2}{3}}\right)^{n}$ 收敛，故 $x=-1$ 为收敛点；  

当 $x=3$ 时，  

$$
\begin{array}{l}{\displaystyle\sum_{n=2}^{\infty}\,\frac{\displaystyle\frac1{2^{n}}+(-1)^{n}\cdot\frac1{3^{n}}}{n}\cdot2^{n}=\sum_{n=2}^{\infty}\,\frac{\displaystyle1+\left(-\,\frac23\right)^{n}}{n}}\\ {\displaystyle=\sum_{n=2}^{\infty}\,\frac{\displaystyle1}{n}+\sum_{n=2}^{\infty}(-1)^{n}\cdot\frac1n\cdot\left(\frac23\right)^{n},}\end{array}
$$  

其中级数 $\sum_{n\mathop{=}2}^{\infty}\,\frac{1}{n}$ 发散，级数 $\sum_{n=2}^{\infty}{(-1)^{n}}\,\cdot\,{\frac{1}{n}}\,\cdot\,{\left({\frac{2}{3}}\right)^{n}}$ 绝对收敛，故 $_x=3$ 为发散点.  

综上,收敛域为[一1,3).  

例 16. 8幂级数 $\sum_{n=1}^{\infty}3^{n}x^{2n+1}$ 的收敛域为  

[解】应填 $\left(-{\frac{1}{\sqrt{3}}},{\frac{1}{\sqrt{3}}}\right)$  

此级数缺少偶次幂的项.因为  

$$
\operatorname*{lim}_{n\rightarrow\infty}\left|\,\frac{u_{n+1}\left(x\,\right)}{u_{n}\left(x\,\right)}\,\right|{=}\!\!\operatorname*{lim}_{n\rightarrow\infty}\left|\,\frac{3^{n+1}\,x^{\,2n+3}}{3^{n}x^{\,2n+1}}\,\right|\!=\!3x^{\,2}\,,
$$  

所以当 $3x^{2}<1$ ,即 $\mid x\mid<\frac{1}{\sqrt{3}}$ 时,级数绝对收敛;当 $3x^{2}>1$ ,即 $\mid x\mid>\frac{1}{\sqrt{3}}$ 时,级数发散.故级数的收敛半径为 $R=\frac{1}{\sqrt{3}}.$ 当 $x=\pm{\frac{1}{\sqrt{3}}}$ 时,级数成为 $\pm\sum_{n=1}^{\infty}{\frac{1}{\sqrt{3}}}$ 显然发做。  

因此，形级数的收敛域为 $\left(-{\frac{1}{\sqrt{3}}},{\frac{1}{\sqrt{3}}}\right)$  

例 16. 9已知级数 $\sum_{n=1}^{\infty}\,{\frac{n\,!}{n^{\,n}}}\mathrm{e}^{-n x}$ 的收敛域为 $(a,+\infty)$ ，则 $a=$  
【解】应填一1.  

因为  

$$
\operatorname*{lim}_{n\to\infty}\left|{\frac{\;(n+1)\,!}{(n+1)^{n+1}}}\mathrm{e}^{-(n+1)x}\,\cdot\,{\frac{\;n^{\,n}\;}{n\,!}}\mathrm{e}^{n x}\;\bigg|\,{\frac{\mathrm{lim}}{n+\infty}}\bigg|\left({\frac{n}{n+1}}\right)^{n}\mathrm{e}^{-x}\;\bigg|=\mathrm{e}^{-x-1}\,,
$$  

所以当 $\mathrm{e}^{-x-1}<1$ ,即 $x>-1$ 时,级数收敛，当 $\mathrm{e}^{-x-1}>1$ ,即 $x<-1$ 时级数发散,所以 $a=-1$  

【注】（1）当 $x=-1$ 时， $\frac{u_{\mathsf{\Gamma}_{n+1}}}{u_{\mathsf{\Gamma}_{n}}}=\frac{\mathsf{e}}{\left(1+\frac{1}{n}\right)^{n}}$ ，分母单调增加，,且 $\left(1+{\frac{1}{n}}\right)^{\,n}\,\rightarrow\,\mathrm{e}(n\,\rightarrow\infty)$ ，故 $\left(1+{\frac{1}{n}}\right)^{n}<\mathrm{e}$ 故 $\frac{u_{n+1}}{u_{n}}>1.$ 由比值判别法知,当 $x=-1$ 时级数发散。  

（2）对于一般函数项级数的收敛域，可以不是对称区间，也没有“收敛半径”这一概念。  

# 3.抽象型问题  

（1）阿贝尔定理.  

当幂级数 $\sum_{n=0}^{\infty}a_{n}x^{n}$ 在点 $x=x_{1}(x_{1}\neq0$ ）处收敛时，对于满足 $\lvert x\rvert<\lvert x_{1}\rvert$ 的一切 $_{x}$ ，幂级数绝对收敛；当幂级数 $\sum_{n=0}^{\infty}a_{n}x^{n}$ 在点 $x=\,x_{2}(x_{2}\neq0)$ 处发散时，对于满足 $|x|>|x_{2}|$ 的一切 $_{x}$ ,幂级数发散.  

(2) 结论1.  

根据阿贝尔定理，已知 $\sum_{n=0}^{\infty}a_{n}\left(x-x_{0}\right)^{n}$ 在某点 $x_{\mathrm{~l~}}(x_{\mathrm{~l~}}\neq x_{\mathrm{~o~}})$ ）的敛散性,确定该幂级数的收敛半径可分为以下三种情况.  

$\textcircled{1}$ 若在 $x_{\mathrm{~l~}}$ 处收敛,则收敛半径 $R\geqslant|x_{1}-x_{0}|$ $\circledcirc$ 若在 $\boldsymbol{x}_{\mathrm{~l~}}$ 处发散,则收敛半径 $R\leqslant|\boldsymbol{x}_{1}-\boldsymbol{x}_{0}|$  $\textcircled{3}$ 若在 $x_{\mathrm{~l~}}$ 处条件收敛，则 $R=|\boldsymbol{x}_{1}-\boldsymbol{x}_{0}|$ .【重要考点】  

(3)结论2.  

已知 $\sum a_{n}(x-x_{1})^{n}$ 的敛散性,要求讨论 $\sum b_{n}(x-x_{2})^{n}$ 的敛散性. $\textcircled{1}(x-x_{\mathrm{~l~}})^{n}$ 与 $(x-x_{\mathit{\mathrm{~2~}}})^{m}$ 的转化一般通过初等变形来完成，包括a.“平移”收敛区间；b.提出或者乘以因式 $(x-x_{\circ})^{k}$ 等。  

$\mathcal{O}a_{n}$ 与 $b_{n}$ 的转化一般通过微积分变形来完成，包括a.对级数逐项求导；b.对级数逐项积分等.  
 $\textcircled{3}$ 以下三种情况，级数的收敛半径不变，收敛域要具体问题具体分析.  

a.对级数提出或者乘以因式 $(x-x_{\circ})^{k}$ ，或者作平移等，收敛半径不变 b.对级数逐项求导，收敛半径不变，收敛域可能缩小.c.对级数逐项积分，收敛半径不变，收敛域可能扩大.  

例 16.10若 $\sum_{n=0}^{\infty}a_{n}\left(2x-3\right)^{n}$ 在 $x=-1$ 处条件收敛，则 $\sum_{n\,=\,0}^{\infty}a_{\,n}\,\cdot\,4^{n}$ 与 $\sum_{n\mathop{=}0}^{\infty}a_{n}\cdot6^{n}$ 的敛散性  
为().  

（A）收敛,收敛(B)收敛,发散(C）发散,收敛(D）发散,发散  

【解】应选(B).  

级数 $\sum_{n=0}^{\infty}a_{n}\left(x-x_{0}\right)^{n}$ 在 $x_{\mathrm{~l~}}(\neq\boldsymbol{x}_{\intercal}$ ）处条件收敛,可知收敛半径 $R=\mid x_{1}-x_{0}\mid$ .因级数 $\sum_{n=0}^{\infty}\alpha_{n}\,(2x-3)^{n}=\,\sum_{n=0}^{\infty}\alpha_{n}\,\cdot2^{n}\left(x-{\frac{3}{2}}\right)^{n}$ 在 $x=-1$ 处条件收敛，故收敛半径 $R=\left|\begin{array}{l}{-1-\frac{3}{2}}\right|=\frac{5}{2}.$ 由 $-\,{\frac{5}{2}}<x-{\frac{3}{2}}<{\frac{5}{2}}$ ,得收敛区间为 $-1<x<4$ ,如图16-1所示.  

$$
\frac{1}{-1}\frac{1}{\frac{3}{2}}\frac{1}{\frac{9}{4}\frac{9}{2}}
$$  

图16-1  

取 $x=\frac{7}{2}\in(-1,4)$ ，此时 $\sum_{n=0}^{\infty}\alpha_{n}\,(2x-3)^{n}=\sum_{n=0}^{\infty}\alpha_{n}\,\cdot\,4^{n}$ 收敛；  

取 $x=\frac{9}{2}\in(-\infty,-1)\cup(4,+\infty)$ ，此时 $\sum_{n=0}^{\infty}\alpha_{n}\,(\,2x-3\,)^{n}=\sum_{n=0}^{\infty}\alpha_{n}\,\cdot\,6^{n}$ 发散.应选(B).  

（1）函数展开 $f(x)=\sum a_{n}x^{n}$  

（2）积分展开 $\int_{a}^{b}f(x)\,\mathrm{d}x=\sum a_{n}\,{\frac{b^{n+1}-a^{n+1}}{n+1}}.$  

(3）导数展开 ${\frac{\mathsf{d}[\,f(x\,)\,]}{\mathsf{d}x}}=\sum n\alpha_{n}x^{n-1}$  

（4）无穷小比阶，当 $x\,\rightarrow\,0$ 时， $f(x)=\sum a_{n}x^{n}$ 的无穷小比阶问题.  

（1）先积后导 $f(x)=\left[\!\!\int f(x\,)\mathrm{d}x\right]^{\prime}$ （2）先导后积 $f(x)=f(x_{0})+\int_{x_{0}}^{x}f^{\prime}(t)\mathrm{d}t.$ （3）重要展开公式  
# 阳亨高肾数学18洲  

$$
\textstyle(1)f(x)=\sum a_{n}x^{n}.
$$  

11将函数 $f(x)=\arctan{\frac{1-2x}{1+2x}}$ 展开成 $_{x}$ 的幂级数,并求级数 $\sum_{n=0}^{\infty}{\frac{(-1)^{n}}{2n+1}}$ 的和.  

【解】因为 $f^{\prime}(x\,)=-\,\frac{2}{1+4{x}^{\,2}}=-\,2\sum_{n\,=\,0}^{\infty}\,(-\,1)^{n}\,4^{n}{x}^{\,2n}\,,x\,\in\,\left(-\,\frac{1}{2},\frac{1}{2}\right)$ 且  

所以  

$$
\begin{array}{l}{\displaystyle f(\boldsymbol{x}\,)=f(0)\,{+}\!\!\!\int_{0}^{x}f^{\prime}(t\,)\,\mathrm{d}t=\!\frac{\pi}{4}-2\!\!\int_{0}^{x}\,\left[\sum_{n=0}^{\infty}(-1)^{n}\,\mathrm{d}^{n}t^{2n}\right]\,\mathrm{d}t}\\ {\displaystyle\,\,\,\quad\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,\,=\frac{\pi}{4}-2\sum_{n=0}^{\infty}\,\frac{(-1)^{n}\,\mathrm{d}^{n}x^{2n+1}}{2n+1}\,,\boldsymbol{x}\,\in\,\left(-\,\frac{1}{2},\frac{1}{2}\right).}\end{array}
$$  

因为级数 $\sum_{n=0}^{\infty}{\frac{(-1)^{n}}{2n+1}}$ 收敛，函数 $f(x)$ 在 $x=\frac{1}{2}$ 处连续，所以  

$$
f(x\,)=\frac{\pi}{4}-2\sum_{n=0}^{\infty}\,\frac{(-\,1)^{n}4^{n}x^{\,2n+1}}{2n+1},x\,\in\,\left(-\,\frac{1}{2},\frac{1}{2}\right].
$$  

令$x=\frac{1}{2}$ ，得 $f\left({\frac{1}{2}}\right)={\frac{\pi}{4}}-2\sum_{n=0}^{\infty}\,{\frac{(-1)^{n}\,4^{n}}{2n+1}}\cdot{\frac{1}{2^{2n+1}}}.$ 由于 $f\!\left({\frac{1}{2}}\right)\!=\!0$ ,所以 $\sum_{n=0}^{\infty}\,{\frac{(-1)^{n}}{2n+1}}={\frac{\pi}{4}}.$  

注](1) 级数 $\sum_{n=0}^{\infty}{\frac{(-1)^{n}}{2n+1}}$ 的和也可用其他方式求得，如：  

考虑 $S(x)=\!\!\sum_{n=0}^{\infty}\,{\frac{(-1)^{n}x^{2n+1}}{2n+1}},x\,\in\,[-1,1]\,.$ 则  

$$
S^{\prime}(x)=\!\!\sum_{n=0}^{\infty}(-1)^{n}x^{2n}=\!\frac{1}{1+x^{2}},x\,\in\,(-1,1)\,,
$$  

且 $S(0)=0$ ，所以  

$$
S(x\,)=S(0)+\!\!\int_{0}^{x}S^{\prime}(t\,)\,\mathrm{d}t=\!\!\int_{0}^{x}\,{\frac{1}{1+{t^{\prime}}}}\mathrm{d}t=\arctan\,x\,,x\,\in\,[-1,1],
$$  

故  

$$
\sum_{n=0}^{\infty}{\frac{(-1)^{n}}{2n+1}}=S(1)=\arctan1={\frac{\pi}{4}}.
$$  

(2) 小结.  

$\mathfrak{D}\ln(1+x)=\sum_{n=1}^{\infty}(-1)^{n-1}\,\cdot\,\frac{x^{n}}{n},-1<x\leqslant1.$ $\mathcal{\Omega}\geq\frac{1}{2}\mathrm{ln}(1+x)=\!\!\sum_{n=1}^{\infty}(-\,1)^{n-1}\,\cdot\,\frac{x^{n}}{2n},-\,1\,\!<\!x\leqslant\!1.$ ③arctan $x=\sum_{n=0}^{\infty}\,(-\,1)^{n}\cdot{\frac{x^{\,2n+1}}{2n+1}},-\,1\leqslant x\leqslant1.$  
$\mathbb{G}\mathrm{e}^{x}=\!\sum_{n=0}^{\infty}\frac{x^{n}}{n!},-\infty<x<+\infty.$ $\odot\frac{\mathfrak{e}^{x}+\mathfrak{e}^{-x}}{2}\!=\!\!\sum_{n=0}^{\infty}\frac{x^{2n}}{\left(2n\right)!},-\infty\!<\!x<\!+\infty.$ ${\widehat{\Theta}}\cos\,x=\!\!\sum_{n=0}^{\infty}(-1)^{n}\cdot{\frac{x^{2n}}{(2n)!}},-\infty<x<+\infty.$ $\mathcal{D}\,\frac{\mathsf{e}^{x}-\mathsf{e}^{-x}}{2}\!=\!\!\sum_{n=0}^{\infty}\,\frac{x^{\,2n+1}}{(2n+1)!},-\infty\!<\!x<\!+\infty.$ $\circledast\sin\,x=\sum_{n\,=\,0}^{\infty}\,(-\,1)^{n}\,\cdot\,{\frac{x^{\,2n+1}}{(2n+1)\,!}},-\,\infty<x<+\,\infty.$  

常用上述8个公式来考一些简单的数项级数的和，如 $\sum_{n=0}^{\infty}{\frac{1}{(2n)!}}={\frac{\mathbf{e}+\mathbf{e}^{-1}}{2}}$ ，再如$\begin{array}{c}{{\displaystyle\sum_{n=0}^{\infty}(-1)^{n}\cdot\frac{2n+2}{(2n+1)!}\!=\!\!\sum_{n=0}^{\infty}(-1)^{n}\;\frac{2n+1}{(2n+1)!}\!+\!\!\sum_{n=0}^{\infty}(-1)^{n}\;\frac{1}{(2n+1)!}}}\\ {{\displaystyle\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad\qquad1}}\end{array}$ =cos 1+sin 1.  

(2) $\int_{a}^{b}f(x\,)\,\mathrm{d}x=\sum a_{n}\,{\frac{b^{n+1}-a^{n+1}}{n+1}}\,.$ （展开后积分即可）.  

(1) $x\in[-1,1)$ ，写出 $\ln(1-x)$ 的麦克劳林展开式；  

(2）已知 $\sum_{n=1}^{\infty}{\frac{1}{n^{2}}}\!=\!{\frac{\pi^{2}}{6}}$ ，求 $\int_{0}^{1}{\frac{\ln(1-x)}{x}}\mathrm{d}x$ 的值.   
[解] $(1)\ln(1-x)=-\sum_{n=1}^{\infty}{\frac{x^{n}}{n}},x\,\in\,[-1,1).$   
（2） $\int_{0}^{1}{\frac{\ln(1-x)}{x}}\mathrm{d}x=\!\!\int_{0}^{1}\!\left(-\sum_{n=1}^{\infty}{\frac{x^{n-1}}{n}}\right)\mathrm{d}x=-\!\sum_{n=1}^{\infty}\!\int_{0}^{1}{\frac{x^{n-1}}{n}}\mathrm{d}x=-\!\sum_{n=1}^{\infty}{\frac{1}{n^{2}}}\!=\!-{\frac{\pi^{2}}{6}}.$ (3) ${\frac{\mathsf{d}[\,f(x\,)\,]}{\mathsf{d}x}}=\sum n\alpha_{n}x^{\,n-1}$ (展开后求导即可)。  

3将 ${\frac{\mathsf{d}}{\mathsf{d}x}}\left({\frac{\cos\,x-1}{x}}\right)$ 展开，并求 $\sum_{n=1}^{\infty}(-1)^{n}\,\cdot\,{\frac{2n-1}{(2n)!}}\cdot\,\left({\frac{\pi}{2}}\right)^{2n}.$  

【解】由于 ${\frac{\cos x-1}{x}}\!=\!\!\sum_{n=1}^{\infty}(-1)^{n}\cdot{\frac{x^{2n-1}}{(2n)!}}$ ，等式两边同时对 $_{x}$ 求导，得$\frac{\mathsf{d}\Bigl(\frac{\cos{\it\theta}x-1}{x}\Bigr)}{\mathsf{d}x}=\frac{-x\sin{x}-\cos{x}+1}{x^{2}}=\sum_{n=1}^{\infty}(-1)^{n}\cdot\frac{(2n-1)x^{2n-2}}{(2n)!}.$  
陆宁高等数学18讲  

令$x={\frac{\pi}{2}}$ ,有 $;\frac{-\,\frac{\pi}{2}+1}{\left(\frac{\pi}{2}\right)^{2}}=\!\!\sum_{n=1}^{\infty}(-\,1)^{n}\cdot\frac{2n-1}{(2n)\,!}\cdot\left(\frac{\pi}{2}\right)^{2n-2}$ ，故 $\sum_{n\,=\,1}^{\infty}(-\,1)^{\ast}\,\cdot\,{\frac{2n-1}{(2n\,)\,!}}\cdot\left({\frac{\pi}{2}}\right)^{2n}=1-{\frac{\pi}{2}}.$  

(4)当 $x\rightarrow0$ 时， $f(x)=\sum a_{n}x^{n}$ 的无穷小比阶问题。  

例 16. 10设 $f(x\,)=\!\!\int_{0}^{\sin x}\sin(t^{2}\,)\,\mathrm{d}t\,,g\,(x\,)=\sum_{n=1}^{\infty}\,\frac{x^{\,2n+1}}{n^{n}+2}$ 当 $x\ \rightarrow\ 0$ 时， $f(x)$ 是 $_{g}(x)$ 的().  

（A）高阶无穷小（B）低阶无穷小（C）等价无穷小（D）同阶非等价无穷小  

[解 应选(C)。  
 $g\left(x\right)=\!\!\sum_{n=1}^{\infty}{\frac{x^{2n+1}}{n^{2}+2}}\!=\!{\frac{x^{3}}{3}}\!+\!{\frac{x^{5}}{6}}\!+\!\cdots\!\sim{\frac{x^{3}}{3}}(x\to0)$ ，于是$\operatorname*{lim}_{x\to0}{\frac{f(x)}{g(x)}}=\operatorname*{lim}_{x\to0}{\frac{\int_{0}^{\sin x}\sin(t^{2})\,\mathrm{d}t}{{\frac{x^{3}}{3}}}}=\operatorname*{lim}_{x\to0}{\frac{\sin(\sin^{2}x)\,\cdot\,\cos\,x}{x^{2}}}=\operatorname*{lim}_{x\to0}{\frac{\sin^{2}x}{x^{2}}}=1.$  

【注 当 $x\rightarrow0$ 时,用 $\sin(\sin^{2}x)\sim\sin^{2}x\sim x^{2}$ 较简单,也可将 $\sin(\sin^{2}x)$ 直接展开,较麻烦，但第一项仍为 $x^{2}$ ，虽然后面的展开项不同了，但最终结果不变。  

四求和问题1.直接套公式  

例 16. 15求幂级数 $\sum_{n=1}^{\infty}{\frac{(-1)^{n-1}}{n\,(2n-1)}}x^{2n}$ 的收敛域及和函数.  

【解】记 $u_{n}\left(x\right)=\frac{(-1)^{n-1}}{n\left(2n-1\right)}x^{2n}$ ，由 $\operatorname*{lim}_{n\rightarrow\infty}\left|\,\frac{u_{n+1}\left(x\,\right)}{u_{n}\left(x\,\right)}\,\right|\!=\!x^{\,2}<1$ ，得 $-1<x<1$ 当 $x=\pm1$ 时， $\sum_{n=1}^{\infty}\,{\frac{(-1)^{n-1}}{n\,(2n-1)}}x^{2n}=\sum_{n=1}^{\infty}\,{\frac{(-1)^{n-1}}{n\,(2n-1)}}$ 收敛，于是收敛域为[一1,1].  

$$
\begin{array}{c}{{S(x\,)=\displaystyle\sum_{n=1}^{\infty}\,\displaystyle\frac{(-1)^{n-1}}{n\,(2n-1)}x^{\,2n}=\displaystyle\sum_{n=1}^{\infty}\left(\frac{2}{2n-1}-\frac{1}{n}\right)(-1)^{n-1}x^{\,2n}}}\\ {{=2\displaystyle\sum_{n=1}^{\infty}\,\displaystyle\frac{(-1)^{n-1}}{2n-1}x^{\,2n}-\displaystyle\sum_{n=1}^{\infty}\,\displaystyle\frac{(-1)^{n-1}}{n}x^{\,2n}}}\end{array}
$$  
$$
{\begin{array}{l}{\displaystyle=2x\sum_{n=1}^{\infty}\,{\frac{(-1)^{n-1}}{2n-1}}x^{2n-1}-\sum_{n=1}^{\infty}\,{\frac{(-1)^{n-1}}{n}}x^{2n}\,}\\ {\displaystyle=2x\arctan\,x-\ln(1+x^{2})\,,-1\leqslant x\leqslant1}\end{array}}
$$  

例16.16设级数 $\sum_{n=1}^{\infty}\alpha_{n}x^{n}$ 的系数 $^{a}$ ，满足关系式 $a_{n}={\frac{a_{n-1}}{n}}+1-{\frac{1}{n}},n=2,3\,,\cdots,a_{1}=2\,,$ 则当 $\mid x\mid<1$ 时,级数 $\sum_{n\mathop{=}1}^{\infty}a_{n}x^{n}$ 的和函数 $S(x)=$  

【解】应填 ${\frac{x}{1-x}}+\mathbf{e}^{x}-1$  

$$
\begin{array}{c}{{a_{n}-1=\displaystyle\frac{1}{n}(a_{n-1}-1)=\displaystyle\frac{1}{n}\cdot\frac{1}{n-1}(a_{n-2}-1)}}\\ {{=\displaystyle\frac{1}{n}\cdot\frac{1}{n-1}\cdot\cdots\cdot\frac{1}{2}(a_{1}-1)=\displaystyle\frac{1}{n!},}}\end{array}
$$  

故 $a_{n}=1+{\frac{1}{n!}}$ ，于是当 $\mid x\mid<1$ 时，  

$$
S(x\,)=\sum_{n=1}^{\infty}\alpha_{n}x^{n}=\sum_{n=1}^{\infty}x^{\,n}+\sum_{n=1}^{\infty}{\frac{x^{\,n}}{n\,!}}\,{=}{\frac{x}{1-x}}+{\mathrm{e}}^{x}\,-1.
$$  

例16. 17求幂级数 $\sum_{n=1}^{\infty}\,{\frac{n^{2}}{n!}}x^{\,n}$ 的收敛域及和函数。  

【解】令 $a_{n}={\frac{n^{2}}{n!}}$ ,则 $\operatorname*{lim}_{n\to\infty}{\frac{a_{\,n+1}}{a_{\,n}}}=\operatorname*{lim}_{n\to\infty}{\frac{(n+1)^{2}}{(n+1)!}}\cdot{\frac{n!}{n^{2}}}=0$ ,故幂级数的收敛域为 $(-\infty,+\infty)$ ：令$S(x)=\sum_{n=1}^{\infty}\,\frac{n^{2}}{n!}x^{\,n}(-\infty<x<+\infty)$ ，则  

$$
\begin{array}{l}{\displaystyle S(\boldsymbol{x})=\sum_{n=1}^{\infty}\,\frac{n}{(n-1)!}\boldsymbol{x}^{\intercal}=\sum_{n=1}^{\infty}\,\frac{n-1+1}{(n-1)!}\boldsymbol{x}^{\intercal}}\\ {\displaystyle=\sum_{n=2}^{\infty}\,\frac{1}{(n-2)!}\boldsymbol{x}^{\intercal}+\sum_{n=1}^{\infty}\,\frac{1}{(n-1)!}\boldsymbol{x}^{\intercal}}\\ {\displaystyle=\boldsymbol{x}^{\intercal}\mathrm{e}^{\intercal}+\boldsymbol{x}\,\mathrm{e}^{\intercal}.}\end{array}
$$  

2.用先积后导或先导后积求和函数  

(1) $\sum(a n+b)x^{a n}$ 先积后导. (2) $\sum{\frac{x^{\alpha n}}{a n+b}}$ 先导后积. $\sum\frac{c n^{2}+d n+e}{a n+b}x^{a n}\,{\overset{\underset{\mathrm{HF}}{}}{=}}\sum_{(1)}+\sum_{(2)}.$  

例 16. 18设 $u_{n}\left(x\right)=\mathrm{e}^{-n x}+{\frac{x^{n+1}}{n\left(n+1\right)}}(n=1,2,\cdots)$ ，求级数 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的收敛域及和函数.  

【解】因为 $\operatorname*{lim}_{n\to\infty}\,{\frac{n(n+1)}{(n+1)(n+2)}}=1$ ，所以幂级数 $\sum_{n=1}^{\infty}\,\frac{x^{n+1}}{n\,(n+1)}$ 的收敛半径为1.因为  
比亨高等数学18讲  

$\sum_{n=1}^{\infty}\frac{1}{n\left(n+1\right)},\sum_{n=1}^{\infty}\frac{(-1)^{n+1}}{n\left(n+1\right)}$ 均收敛，所以 $\sum_{n=1}^{\infty}{\frac{x^{n+1}}{n\left(n+1\right)}}$ 的收敛域为[-1,1].又因为级数 $\sum_{n=1}^{\infty}\mathrm{e}^{-n x}$ 的收敛域为 $(0,+\infty)$ ,所以级数 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的收敛域为(0,1].  

当 $x\,\in\,(0\,,1]$ 时， $\sum_{n=1}^{\infty}\mathrm{e}^{-n x}={\frac{\mathrm{e}^{-x}}{1-\mathrm{e}^{-x}}}={\frac{1}{\mathrm{e}^{x}-1}}.$ 记 $S(x)=\!\!\sum_{n=1}^{\infty}{\frac{x^{n+1}}{n\left(n+1\right)}}$ 当 $x\,\in\,(0\,,1)$ 时，  

$$
S^{\prime}(x\,)\,{=}\!\sum_{n\,{=}\,1}^{\infty}\,\frac{x^{n}}{n}\,{=}\,{-}\ln(1-x\,)\,,
$$  

于是  

$$
\begin{array}{l}{\displaystyle S(\boldsymbol{x})=\!\int_{0}^{x}\!S^{\prime}(t)\,\mathrm{d}t+S(0)=-\!\int_{0}^{x}\!\ln(1-t)\,\mathrm{d}t=-\,t\ln(1-t)\,\Big|_{0}^{x}+\int_{0}^{x}t\cdot\frac{-1}{1-t}\,\mathrm{d}t}\\ {\displaystyle\qquad=-\,x\ln(1-x)+\!\int_{0}^{x}\,\frac{1-t-1}{1-t}\mathrm{d}t=-\,x\ln(1-x)+\!\int_{0}^{x}\Big(1-\frac{1}{1-t}\Big)\,\mathrm{d}t}\\ {\displaystyle\qquad=-\,r\ln(1-r)+\,r+1\!\ln(1-r)=(1-r)\ln(1-r)+\,r\cdot\,c\,\in\,(0.1)}\end{array}
$$  

当 $x=1$ 时， $S(1)=\!\!\sum_{n=1}^{\infty}\frac{x^{n+1}}{n(n+1)}\,\Bigr|_{\!\!\!\!\!\!_{x=1}}=\!\!\!\sum_{n=1}^{\infty}\frac{1}{n(n+1)}=1.$  

综上可知,级数 $\sum_{n=1}^{\infty}u_{n}\left(x\right)$ 的和函数  

$$
T(x\,)=\!\!\left\{\!\!\begin{array}{l l}{\displaystyle\frac{1}{\mathrm{e}^{x}\,-1}+x+(1-x\,)\ln\,(1-x\,)\,,}&{x\,\in\,(0,1)\,,}\\ {\displaystyle\frac{\mathbf{e}}{\mathrm{e}-1},}&{x=1.}\end{array}\!\!\right.
$$  

注 还可以根据和函数 $s(x)$ 的连续性来求 S(1),即  

$$
\begin{array}{l}{{S(1)=\underset{x\rightarrow1^{-}}{\operatorname*{lim}}S(x)=\underset{x\rightarrow1^{-}}{\operatorname*{lim}}\big[(1-x)\mathrm{ln}(1-x)+x\,\big]}}\\ {{\qquad\qquad\qquad\qquad=\underset{x\rightarrow1^{-}}{\operatorname*{lim}}(1-x)\mathrm{ln}(1-x)+1\underset{t\rightarrow0^{+}}{\operatorname*{lim}}t\mathrm{ln}\;t+1=1.}}\end{array}
$$  

# 3.用所给微分方程求和函数  

步骤：（1）求所给级数满足的微分方程的通解（有时命制为验证级数满足某微分方程，再求 其通解，事实上均是给出了微分方程）；  

（2）一般要根据初始条件定 $C_{1}$ ， $C_{2}$ 或求 $x=x_{0}$ 时的数项级数的和(比如 $x=\frac{1}{2},1$ 等)。  

例 16. 19已知幂级数 $\sum_{n=1}^{\infty}a_{2n}x^{2n}$ 的收敛域为[—1,1],其和函数 $S(x)$ 满足方程 $x S^{\prime}(x)-$  $S(x)=\frac{x^{2}}{1+x^{2}}$ ，求：  
$(1)S(x)$ 的解析式；  

$(2)S(x)$ 在 ${x=0}$ 处的 $_n$ 阶导数 $S^{(n)}\left(0\right)$  

（3）数项级数 $\sum_{n=1}^{\infty}\,\frac{a\,_{2n}}{n}$ 的和.  

[解] $(1)x S^{\prime}(x)\!-\!S(x)\!=\!\!\frac{x^{2}}{1+x^{2}}$ 可化为 $S^{\prime}(x)-\frac{1}{x}S(x)\!=\!\frac{x}{1+x^{2}}$ ,这是一阶线性微分方程,其通解为  

$$
S(x\,)=\mathrm{e}^{\int_{x}^{\frac{1}{x}\mathrm{d}x}\,\left[\int\frac{x}{1+x^{\,2}}\mathrm{e}^{\int\left(-\frac{1}{x}\right)\,\mathrm{d}x}\,\mathrm{d}x\,+C\right]}\,=x\,(\arctan\,x\,+C).
$$  

由于 $S(x)=\sum_{n=1}^{\infty}a_{2n}x^{2n}$ 为偶函数,故 $C=0$ 于是， $S(x\,)=x$ arctan $x\;,-\,1\leqslant x\leqslant1$ ：  

（2）由基本公式 ${\frac{1}{1+x}}=\sum_{n=0}^{\infty}{(-1)^{n}x^{n}(-1<x<1)}$ ,得  

$$
{\frac{1}{1+x^{2}}}=\sum_{n=0}^{\infty}\,(-\,1)^{n}x^{\,2n}\,(-\,1<x<1)\,,
$$  

$$
=\sum_{n\,=\,0}^{\infty}\,{\frac{(-\,1)^{n}}{2n+1}}x^{\,2n+2}=\sum_{n\,=\,1}^{\infty}\,{\frac{(-\,1)^{n-1}}{2n-1}}x^{\,2n}\,(-\,1\leqslant x\leqslant1).
$$  

由于 $S(x)=\sum_{n\,=\,1}^{\infty}\alpha_{2n}x^{\,2n}(-1\leqslant x\leqslant1)$ ，故 $\alpha_{2n-1}=0\,,\alpha_{2n}=\frac{(-1)^{n-1}}{2n-1}(n=1,2,\cdots)$ .于是$S^{(2n-1)}\left(0\right)=\alpha_{2n-1}\cdot\left(2n-1\right)!=0\,,S^{(2n)}\left(0\right)=\alpha_{2n}\cdot\left(2n\right)!=\frac{\left(-1\right)^{n-1}\left(2n\right)!}{2n-1}\,,$  

即  

$$
S^{(n)}(0)=\!\!\left\{\!\!\frac{0\,,}{2k-1}\!\!\!\!\slash(2k)!}\!\!\!\right\},\quad n=2k-1,\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad
$$  

（3）由（2）知， $S(x)=x$ arcta $\mathrm{~n~}\,x\,=\,\sum_{n\,=\,1}^{\infty}\alpha_{\,2n}{x^{\,2n}}\,=\sum_{n\,=\,1}^{\infty}\,\frac{(-1)^{n-1}}{2n-1}x^{\,2n}(-\,1\leqslant x\leqslant1)\,,\alpha_{\,2n}\,=$ ${\frac{(-1)^{n-1}}{2n-1}}.$ 故  

$$
\begin{array}{c}{{\displaystyle\sum_{n=1}^{\infty}\frac{\alpha_{2n}}{n}=\sum_{n=1}^{\infty}\frac{(-1)^{n-1}}{n\,(2n-1)}=2\sum_{n=1}^{\infty}\frac{(-1)^{n-1}}{2n\,(2n-1)}=2\sum_{n=1}^{\infty}\frac{(-1)^{n-1}}{2n-1}-\sum_{n=1}^{\infty}\frac{(-1)^{n-1}}{n}}}\\ {{\displaystyle=2S\left(1\right)-\ln\,2=\frac{\pi}{2}-\ln\,2.}}\end{array}
$$  

4.建立微分方程并求和函数  

步骤：(1)求 $y^{\prime}$ (或 $y^{\prime},y^{\prime\prime})$ ,根据所给 $a_{n}\cdot a_{n+1}\,,a_{n-1}$ 的关系式建立微分方程；  

（2）求微分方程的通解；  

（3）将通解展开并合并成 $\sum a_{n}x^{n}$ 即可求得 $^{\,a}$ ，的表达式.  
例16. 20设数列 $\{a_{n}\}$ 满足 $\alpha_{1}=1\,,(n+1)\alpha_{n+1}=\left(n+\frac{1}{2}\right)\alpha_{n}$ ,证明：当 $\mid x\mid<1$ 时，幂级数 $\sum_{n=1}^{\infty}a_{n}x^{n}$ 收敛,并求其和函数.  

【解】由条件可知， $\scriptstyle a_{n}\ {\neq}\ 0$ ，且  

$$
\operatorname*{lim}_{n\to\infty}{\frac{\mid a_{n+1}\mid}{\mid a_{n}\mid}}=\operatorname*{lim}_{n\to\infty}{\frac{n+{\frac{1}{2}}}{n+1}}=1,
$$  

所以幂级数 $\sum_{n=1}^{\infty}a_{n}x^{n}$ 的收敛半径为1,从而当 $\mid x\mid<1$ 时,幂级数 $\sum_{n\mathop{=}1}^{\infty}a_{n}x^{n}$ 收敛.  

当 $\mid x\mid<1$ 时，设 $S\left(x\right)=\sum_{n=1}^{\infty}a_{n}x^{n}$ ，逐项求导得  

$$
\begin{array}{l}{{S^{\prime}(x)=\displaystyle\sum_{n=1}^{\infty}\!n\alpha_{n}x^{n-1}\hfill}}\\ {{\displaystyle\qquad\qquad=1+\sum_{n=1}^{\infty}(n+1)\alpha_{n+1}x^{n}\hfill}}\\ {{\displaystyle\qquad\qquad=1+\sum_{n=1}^{\infty}\!n\alpha_{n}x^{n}+\frac{1}{2}\sum_{n=1}^{\infty}\!\alpha_{n}x^{n}\hfill}}\\ {{\displaystyle\qquad\qquad=1+x S^{\prime}(x)+\frac{1}{2}S(x)\hfill,}}\end{array}
$$  

所以  

$$
S^{\prime}(x)-\frac{1}{2(1-x\,)}S(x\,)=\frac{1}{1-x}.
$$  

根据一阶线性微分方程的通解公式得  

$$
S\left(x\right)=\mathrm{e}^{\int_{2\left(1-x\right)}^{\frac{\mathrm{d}x}{2\left(1-x\right)}}\left[C+\int\mathrm{e}^{-\left\lceil\frac{\mathrm{d}x}{2\left(1-x\right)}\right.}\right.\cdot\left.\frac{1}{1-x}\mathrm{d}x\right]=\frac{C}{\sqrt{1-x}}-2.
$$  

由题设知 $S(0)=0$ ，得 $C=2$ ，所以 $S(x)=2\Bigl(\frac{1}{\sqrt{1-x}}-1\Bigr)\;,\;|\;x\;|<1.$  

# 5. 综合题  

例16.21 设函数 ${\boldsymbol{y}}=f({\boldsymbol{x}}\,)$ 满足 $y^{\prime\prime}+2y^{\prime}+5y=0$ ，且 $f(0)\,{=}\,1,f^{\prime}(0)\,{=}\,{-}1$  

(1)求 $f(x)$ 的表达式；  

(2)设 $\alpha_{n}=\int_{n\pi}^{+\infty}f(x)\,\mathrm{d}x$ ，求 $\sum_{n=1}^{\infty}\alpha_{n}\,.$  

【解]（1）由特征方程 $r^{2}+2r+5=0$ 得微分方程的通解为 $y=\mathbf{e}^{-x}\left(C_{1}\cos\,2x+C_{2}\sin\,2x\,\right)$ 由 $f(0)\,{=}\,1,f^{\prime}(0)\,{=}\,{-}1$ ,得 $C_{1}=1,C_{2}=0$ ,即 $f(x)=\mathrm{e}^{-x}\cos\,2x$  

（2）由（1）可知  

$$
a_{n}=\!\!\int_{\,n\,}^{+\infty}\!\mathrm{e}^{-x}\cos\,2x\,\mathrm{d}x=\!\left.{\frac{{\bigl|}\,(\mathrm{e}^{-x}\,)^{\prime}\quad(\cos\,2x\,)^{\prime}\,{\bigr|}}{\mathrm{e}^{-x}}}\,\right|_{n\,{\mathrm{x}}}+\!\!\left.{\frac{\cos\,2x}{\,(-1)^{2}+2^{2}}}\,\right|_{n\,{\mathrm{x}}}
$$  
$$
\begin{array}{l}{{=\displaystyle\frac{1}{5}(-\,\mathrm{e}^{-x}\cos\,2x+2\mathrm{e}^{-x}\sin\,2x\,)\left\vert_{\phantom{-}{}_{n\pi}}^{\phantom{+\infty}}\right.}}\\ {{\ \ \ \ \ \ \left.=\frac{1}{5}[0-(-\,\mathrm{e}^{-n\pi})]\,{=}\,\frac{1}{5}\mathrm{e}^{-n\pi}\,,\ }}\end{array}
$$  

故$\cdot\sum_{n=1}^{\infty}a_{n}=\frac{\mathrm{e}^{-\pi}}{5(1-\mathrm{e}^{-\pi})}=\frac{1}{5(\mathrm{e}^{\pi}-1)}.$  

例 16.22设 $a_{\scriptscriptstyle\,n}=\!\!\int_{0}^{1}\!x^{\,2}\ln^{n}\!x\mathrm{d}x\,,n=0,1,2,\cdots\!.$  

（1）求 $\alpha_{n}$ 的表达式；  

(2) 计算 $\sum_{n=0}^{\infty}\,\frac{a_{n}}{n!}$  

【解】（1）由例9.7知， $a_{\,n}=\frac{(-1)^{n}}{3^{n+1}}n\!\!\mid,n=0,1,2,\cdots\!.$ (2) $\)\sum_{n=0}^{\infty}{\frac{a_{n}}{n\,!}}=\sum_{n=0}^{\infty}{\frac{(-\,1)^{n}}{3^{n+1}}}={\frac{1}{3}}\sum_{n=0}^{\infty}\left(-\,{\frac{1}{3}}\right)^{n}={\frac{1}{3}}\cdot{\frac{1}{1+{\frac{1}{3}}}}={\frac{1}{4}}.$ 例 16.23设 $a_{\,n}=\!\!\int_{\,0}^{n\,\pi}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!$  

(1)求 $\alpha_{n}$ 的表达式；  

(2)计算 $\sum_{n=1}^{\infty}\,\frac{a_{n}}{3^{n}\,\cdot\,\pi}.$  

【解】（1）由例11.1知， $\alpha_{\!\;n}=n^{2}\pi\,,n=1,2,\cdots$   
(2） $\sum_{n=1}^{\infty}\,{\frac{a_{n}}{3^{n}\,\cdot\,\pi}}=\sum_{n=1}^{\infty}n^{2}\,\Big({\frac{1}{3}}\Big)^{n}\,.$   
当 $\mid x\mid<1$ 时，令 $S(x)=\sum_{n=1}^{\infty}n^{2}\bullet x^{n}=x\sum_{n=1}^{\infty}n^{2}x^{n-1}=x S_{1}(x)$ ,其中  

$$
S_{1}(x)=\left[\int\!\!S_{1}(x\,)\,\mathrm{d}x\right]^{\prime}=\Big(\sum_{n=1}^{\infty}\!n x^{\,n}\Big)^{\prime}\,.
$$  

再令 $\sum_{n=1}^{\infty}n x^{n}=x\sum_{n=1}^{\infty}n x^{n-1}=x S_{2}(x)$ ,其中  

故  

$$
\begin{array}{c}{{S_{2}(x\,)=\displaystyle\left[\!\!\displaystyle\int_{S_{2}(x\,){\mathrm{d}}x}\!\!\!\right]^{\prime}=\!\left(\displaystyle\sum_{n=1}^{\infty}x^{\,\prime}\,\right)^{\prime}=\!\left(\displaystyle\frac{x}{1-x}\right)^{\prime}=\!\frac{1}{(1-x\,)^{2}}.}}\\ {{S_{1}(x\,)=\displaystyle\left[\!\!\!x\,\,\displaystyle\frac{1}{(1-x\,)^{2}}\right]^{\prime}=\!\frac{1+x}{(1-x\,)^{3}},}}\end{array}
$$  

于是  

$$
S(x)=\frac{x+x^{2}}{(1-x)^{3}},\mathrm{{E}}\sum_{n=1}^{\infty}\,\frac{a_{n}}{3^{n}\bullet\pi}=S\Bigl(\frac{1}{3}\Bigr)\!=\!\frac{3}{2}.
$$  

例16.24设 $a_{\,n}=\!\!\int_{0}^{+\infty}\!x^{\,n}\,\mathrm{e}^{-x}\,\mathrm{d}x\,,n=0,1,2,\cdots\!.$  

（1）求 $^{a}$ ，的表达式；  
# 陆宁高等数学18讲  

（2）计算 $\sum_{n=1}^{\infty}\,\frac{n^{2}}{a_{n}},$  

$$
\begin{array}{l}{{(1){\alpha}_{n}}=\displaystyle\int_{0}^{+\infty}x^{n}\,{\mathrm{e}}^{-x}\,{\mathrm{d}}x=\displaystyle\int_{0}^{+\infty}x^{n}\,{\mathrm{d}}(-\,{\mathrm{e}}^{-x}\,)=-\,{\mathrm{e}}^{-x}\,\star x^{n}\,{\bigg|}_{0}^{+\infty}+\displaystyle\int_{0}^{+\infty}{\mathrm{e}}^{-x}\,\cdot\,n{x}^{n-1}\,{\mathrm{d}}x}\\ {{\ }}\\ {{\ }=n{\displaystyle\int_{0}^{+\infty}x^{n-1}{\mathrm{e}}^{-x}\,{\mathrm{d}}x=n{\alpha}_{n-1}\,,n=1,2,\cdots,}}\end{array}
$$  

故$\alpha_{n}=n\alpha_{n-1}=n\,(n-1)\alpha_{n-2}=\cdots=n\,(n-1)\,\bullet\,\cdots\,\bullet\,1=n\,!.$ (2)令 $S(x\,)=\sum_{n=1}^{\infty}\,\frac{n^{2}}{n!}x^{\,n}(-\infty<x<+\infty)$ ，由例16.17知  

$$
S(x)=x^{2}\,\mathrm{e}^{x}+x\,\mathrm{e}^{x}\,,
$$  

$$
\sum_{n=1}^{\infty}\,{\frac{n^{2}}{a_{n}}}=\sum_{n=1}^{\infty}\,{\frac{n^{2}}{n\,!}}=S(1)=2\mathrm{e}.
$$  

.25设 $\alpha_{n}=\!\!\int_{0}^{1}\!x\,^{n}\!\sqrt{1-x^{\,^{2}}}\,\mathrm{d}x\ ,b_{n}=\!\!\int_{0}^{\frac{x}{2}}\!\sin^{n}\!t\,\mathrm{d}t\,,n=1,2,\cdots,$ 计算 $\sum_{n=1}^{\infty}(-1)^{n}\,{\frac{a_{n}}{b_{n}}}.$ $a_{n}\xrightarrow{x=\sin t}\int_{0}^{\frac{x}{2}}\sin^{n}t\cos^{2}t\,\mathrm{d}t=\int_{0}^{\frac{x}{2}}\sin^{n}t\,(1-\sin^{2}t\,)\,\mathrm{d}t=b_{n}-b_{n+2}.$  

由华里士公式,知 $b_{n+2}=\frac{n+1}{n+2}b,$ ，故 $a_{n}=b_{n}-\frac{n+1}{n+2}b_{n}=\frac{1}{n+2}b_{n}$ .于是  

$$
\sum_{n\,=\,1}^{\infty}\,(-\,1)^{n}\,{\frac{a_{n}}{b_{n}}}=\sum_{n\,=\,1}^{\infty}\,(-\,1)^{n}\,\cdot\,{\frac{1}{n\,+\,2}}.
$$  

当 $\mid x\mid<1$ 时，令 $S(x)=\sum_{n=1}^{\infty}(-1)^{n}\;\frac{x^{n+2}}{n+2}$ ，则  

$$
\begin{array}{c}{{S^{\prime}(x)=\displaystyle\sum_{n=1}^{\infty}(-1)^{n}\cdot x^{n+1}=x\sum_{n=1}^{\infty}(-{x})^{n}}}\\ {{={x}\cdot{\frac{-x}{1+x}}=-{\displaystyle\frac{x^{2}}{1+x}}.}}\end{array}
$$  

于是  

$$
\begin{array}{l}{\displaystyle S(\boldsymbol{x})=S(0)+\int_{0}^{x}\left(-\,\frac{t^{2}}{1+t}\right)\mathrm{d}t=\int_{0}^{x}\,\frac{1-t^{2}-1}{1+t}\mathrm{d}t}\\ {\displaystyle\qquad=\int_{0}^{x}\,(1-t)\mathrm{d}t-\int_{0}^{x}\,\frac{1}{1+t}\mathrm{d}t}\\ {\displaystyle\qquad=x-\frac{x^{2}}{2}-\ln(1+x).}\end{array}
$$  

由于当 $x=1$ 时，根据莱布尼茨判别法，知 $\sum_{n\mathop{=}1}^{\infty}(-1)^{n}\cdot{\frac{1}{n+2}}$ 收敛，故  

$$
\sum_{n=1}^{\infty}(-1)^{n}\ {\frac{a_{n}}{b_{n}}}=\operatorname*{lim}_{x\to1^{-}}S(x\,)={\frac{1}{2}}-\ln\,2.
$$  

例 16. 26设 $\scriptstyle\alpha_{n}(x)$ 满足  

$$
\langle{\bf\Pi}_{n}^{\prime}(x)-\frac{n}{(1+x)\ln(1+x)}a_{n}(x)+\ln^{n}(1+x)=0,x>0,n=1,2,\cdots,a_{n}(1)=0
$$  
(1)求 $\alpha_{\,n}\left(\boldsymbol{x}\right)$ 的表达式；  

（2）判别 $\sum_{n=1}^{\infty}\int_{0}^{1}a_{n}\left(x\right)\mathrm{d}x$ 的敛散性.  

【解】（1）所给方程为 $a_{\;n}^{\prime}\left(x\right)-\frac{n}{\left(1+x\right)\ln(1+x\,)}a_{n}\left(x\right)=-\mathrm{ln}^{n}\left(1+x\right)$ ，令  

$$
\;\;\phi_{\,n}(x)=-\,{\frac{n}{(1+x\,)\ln(1+x\,)}}\,,
$$  

则  

$$
\begin{array}{r}{\mathrm{e}^{-\Big\lceil p_{n}(x)\mathrm{d}x}=\mathrm{e}^{n\left\lceil\frac{\mathrm{d}x}{(1+x)\ln(1+x)}\right\rceil}=\mathrm{e}^{n\left\lceil\frac{\mathrm{d}(\ln(1+x)]}{\ln(1+x)}\right\rceil}=\mathrm{e}^{n\ln\left\lbrack\ln(1+x)\right\rbrack}=\ln^{n}(1+x).}\end{array}
$$  

同理 $\mathrm{e}^{\left\{p_{n}(x)\mathrm{d}x\right.}}=\frac{1}{\ln^{n}{(1+x)}}$ ，由一阶线性微分方程的通解公式，有  

$$
a_{n}\left(x\right)=\ln^{n}\left(1+x\right)\left\{\int{\frac{1}{\ln^{n}\left(1+x\right)}}\cdot\left[-\ln^{n}\left(1+x\right)\right]\!\mathrm{d}x+C\right\}
$$  

$$
=\ln^{n}{(1+x)(-x+C)}
$$  

又由 $a_{\scriptscriptstyle n}\left(1\right)=0$ ，得 $C=1$ ，于是 $a_{\,n}\left(x\right)=\left(1-x\,\right)\ln^{n}\left(1+x\,\right),x>0.$  

$\begin{array}{c}{\displaystyle{\sum_{n=1}^{\infty}\biggr\int_{0}^{1}\!\alpha_{n}\left(x\right)\mathrm{d}x=\sum_{n=1}^{\infty}\biggr\int_{0}^{1}(1-x\,)\mathrm{ln}^{n}\left(1+x\right)\mathrm{d}x\,\,\,\rlap/y\,\exists\mathbb{E}\,\mathbb{H}\,\mathbb{H}\left\lbrace\frac{\xi\pi}{2}\mathbb{H}\,\mathbb{H}\left.\ln\left(1+x\right)\right.}}\\ {\displaystyle{\int_{0}^{1}(1-x\,)\mathrm{ln}^{n}\left(1+x\,\right)\mathrm{d}x\,\leqslant\!\!\int_{0}^{1}\!\left(1-x\,\right)x^{n}\,\mathrm{d}x=\!\!\int_{0}^{1}\!\left(x^{n}-x^{n+1}\right)\mathrm{d}x}}\\ {\displaystyle{\left.=\frac{1}{n+1}-\frac{1}{n+2}\!=\!\frac{1}{\left(n+1\right)\left(n+2\right)}.}}\end{array}$  $\ln(1+x)<x$ ，知  

因为 $\sum_{n=1}^{\infty}{\frac{1}{(n+1)(n+2)}}$ 收敛,故根据正项级数的比较判别法,有 $\sum_{n=1}^{\infty}\int_{0}^{1}a_{n}\left(x\right)\mathrm{d}x$ 收敛.  

五傅里叶级数(仅数学  

1.周期为27的傅里叶级数  

设函数 $f(x)$ 是周期为 2L的周期函数，且在 $[-l,l]$ 上可积，则称  

$$
\alpha_{n}=\frac{1}{l}{\int_{-l}^{l}}f(x\,)\cos\frac{n\,\pi}{l}x\,\mathrm{d}x\,(n=0,1,2,\cdots)\,,
$$  

$$
b_{n}={\frac{1}{l}}{\binom{l}{-l}}\,f(x\,)\sin{\frac{n\,\pi}{l}}x\,\mathrm{d}x\,(n=1\,,2\,,3\,,\cdots)
$$  

为 $f(x)$ 的以 2L为周期的傅里叶系数，称级数  

$$
{\frac{a_{\,0}}{2}}+\sum_{n\,=\,1}^{\infty}\left(a_{\,n}\cos{\frac{n\,\pi}{l}}x+b_{\,n}\sin{\frac{n\,\pi}{l}}x\right)
$$  

为 $f(x)$ 的以2L为周期的傅里叶级数，记作  

$$
f(x\,)\sim{\frac{a_{0}}{2}}+\sum_{n\,=\,1}^{\infty}\left(a_{\,n}\cos{\frac{n\,\pi}{l}}x+b_{\,n}\sin{\frac{n\,\pi}{l}}x\right).
$$  
# 比亨高等数学18讲  

2.狄利克雷收敛定理  

设 $f(x)$ 是以 2L为周期的可积函数，如果在 $[-l,l]$ 上 $f(x)$ 满足：  

$\textcircled{1}$ 连续或只有有限个第一类间断点；  

$\circledcirc$ 至多只有有限个极值点.  

则$f(x)$ 的傅里叶级数在 $[-l,l]$ 上处处收敛.记其和函数为 $S\left(x\right)$ ，则  

$$
S(x)=\left\{\frac{f(x)}{2},\quad x\neq\frac{\sqrt[]{4}\pm\frac{\sqrt[]{2}}{2}}{2}\right.
$$  

$^{3,}$ 正弦级数和余弦级数  

$$
f(x\,)\sim{\frac{a_{0}}{2}}+\sum_{n=1}^{\infty}\left(a_{\,n}\cos\,{\frac{n\,\pi x}{l}}+b_{\,n}\sin\,{\frac{n\,\pi x}{l}}\right),
$$  

$$
\begin{array}{l}{\displaystyle\left\langle a_{0}=\frac{1}{l}\right\rangle_{-l}^{l}f(x~)\,\mathrm{d}x~,}\\ {\displaystyle\left\langle a_{n}=\frac{1}{l}\right\rangle_{-l}^{l}f(x~)\cos{\frac{n\pi x}{l}}\mathrm{d}x~,n=1,2,\cdots,}\\ {\displaystyle b_{n}=\frac{1}{l}\right\rangle_{-l}^{l}f(x~)\sin{\frac{n\pi x}{l}}\mathrm{d}x~,n=1,2,\cdots.}\end{array}
$$  

$\textcircled{1}$ 当 $f(x)$ 为奇函数时，其展开式是正弦级数  

$$
f(x)\sim\sum_{n=1}^{\infty}b_{n}\sin\frac{n\pi x}{l},b_{n}=\frac{2}{l}\bigg\lbrack_{0}^{l}f(x)\sin\frac{n\pi x}{l}\mathrm{d}x\,,n=1,2,\cdots\!.
$$  

$\circledcirc$ 当 $f(x)$ 为偶函数时，其展开式是余弦级数  

$$
f(x\,)\sim{\frac{a_{0}}{2}}+\sum_{n\,=\,1}^{\infty}a_{n}\cos\,{\frac{n\,\pi x}{l}},
$$  

$$
a_{0}=\cfrac{2}{l}\int_{0}^{l}f(x\,)\,\mathrm{d}x\,\,,a_{n}=\cfrac{2}{l}\int_{0}^{l}f(x\,)\cos\,\,\cfrac{n\pi x}{l}\,\mathrm{d}x\,\,,n=1,2,\cdots.
$$  

# 4.只在[0，1]上有定义的函数的正弦级数和余弦级数展开  

若 $f(x)$ 是定义在[0,]上的函数，首先用周期延拓，使其扩展为定义在 $(-\infty,+\infty)$ 上的周期函数 $F(x)$ .在得到 $F(x)$ 的傅里叶级数展开式后，再将其自变量限制在[0，]上，就得到 $f(x)$ 在 $[0,l]$ 上的傅里叶级数展开式.《全国硕士研究生招生考试数学考试大纲》中只要求周期奇延拓和周期偶延拓.  

# （1）周期奇延拓与正弦级数展开  

$\textcircled{1}$ 周期奇延拓.设 $f(x)$ 定义在[0,]上，令  
$$
F(x\,)=\mathrel{\left\{\!\!\!\begin{array}{l l}{f(x\,)\,,}&{0<x\leqslant l\,,}\\ {-\,f(-\,x\,)\,,}&{-\,l\leqslant x<0\,,}\\ {0\,,}&{x=0\,,}\end{array}\right.}
$$  

再令 $F(x)$ 为以 2L为周期的周期函数.  

$\circledcirc$ 正弦级数展开.  

$$
f(x\,)=\sum_{n\,=\,1}^{\infty}b_{n}\sin\frac{n\pi}{l}x\,,x\,\in\,[0,l],
$$  

$$
b_{n}=\frac{2}{l}{\int_{0}^{l}f(x)\sin\frac{n\pi}{l}x}\,\mathrm{d}x\,(n=1,2,3,\cdots).
$$  

# （2）周期偶延拓与余弦级数展开。  

$\textcircled{1}$ 周期偶延拓.  

设 $f(x)$ 定义在 $[0,l]$ 上，令  

$$
F(x\,)=\left\langle{f(x\,)}\,,\begin{array}{l l}{{}}&{{0\leqslant x\leqslant l\,,}}\\ {{}}&{{-\,l\leqslant x<0\,,}}\end{array}\right.
$$  

再令 $F(x)$ 为以2L为周期的周期函数.  

$\circledcirc$ 余弦级数展开.  

$$
f(x\,)=\frac{a_{0}}{2}+\sum_{n\,=\,1}^{\infty}a_{n}\cos\frac{n\,\pi}{l}x\,,x\,\in\,[0,l],
$$  

$$
a_{n}=\frac{2}{l}\bigg\lceil_{0}^{l}f(x\,)\cos\frac{n\pi}{l}x\,\mathrm{d}x\,(n=0,1,2,\cdots).
$$  

例 16. 27设  

$$
f(x\,)=\left|x\,-\frac{1}{2}\right|,b_{n}=2\!\!\int_{0}^{1}\!f(x\,)\sin\,n\pi x\,\mathrm{d}x\,(n=1,2,\cdots).
$$  

令$S(x)=\sum_{n=1}^{\infty}b_{n}\sin{n\pi x}$ ,则 $S\left(-\,\frac{9}{4}\right)=(\mathrm{~\small~\displaystyle~\begin{array}{~}{~\right)~}$  

(A) $\frac{3}{4}$ $(\mathbf{B})\ {\frac{1}{4}}$ $\mathrm{(C)}-{\frac{1}{4}}\qquad\qquad\ \mathrm{(D)}-{\frac{3}{4}}$  

[解]应选(C).  

由题意知 $S(x)$ 是 $f(x)(0\leqslant x\leqslant1)$ 周期为2的正弦级数展开式，根据狄利克雷收敛定理，得  

$$
S\left(-\,\frac{9}{4}\right)=S\left(-\,\frac{1}{4}\right)=-\,S\left(\frac{1}{4}\right)=-\,f\Bigl(\frac{1}{4}\Bigr)=-\,\frac{1}{4}.
$$  

选(C).  

例16. 28证明 $\sum_{n=1}^{\infty}{\frac{(-1)^{n-1}\cos\,n x}{n^{2}}}\!=\!{\frac{\pi^{2}}{12}}\!-\!{\frac{x^{\,2}}{4}},-\pi\!\leqslant\!x\!\leqslant\!\pi$ ,并求数项级数 $\sum_{n=1}^{\infty}{\frac{(-1)^{n-1}}{n^{2}}}$ 的和。  

【解】记 $f(x)=x^{2},x\in[-\pi,\!\pi]$ ,将 $f(x)=x^{2}$ 在 $[-\pi,\pi]$ 上展开成余弦级数,则 $\boldsymbol{b}_{n}=0$ ，且  
张宁高等数学18讲  

$a_{\,0}={\frac{2}{\pi}}{\int_{\,0}^{\pi}}x^{\,2}\,\mathrm{d}x={\frac{2}{3}}\pi^{2}\,,$ $a_{n}={\frac{2}{\pi}}{\bigg\l\int_{0}}^{\pi}x^{2}\cos\,n x\,\mathrm{d}x={\frac{2}{\pi}}\cdot(-\,1)^{n}\ {\frac{2\pi}{n^{2}}}=4\cdot{\frac{(-\,1)^{n}}{n^{2}}}(n=1,2,\cdots)\,,$  

故其傅里叶级数展开式为 $x^{\,2}=\frac{\pi^{2}}{3}+4\sum_{n\,=\,1}^{\infty}\,\frac{(-\,1\,)^{n}}{n^{\,2}}{\cos\,n}x\;,\;-\,\pi\leqslant x\leqslant\pi$ ,即  

$$
\sum_{n=1}^{\infty}{\frac{(-1)^{n-1}\cos\,n x}{n^{2}}}={\frac{\pi^{2}}{12}}-{\frac{x^{2}}{4}},
$$  

令 $x=0$ ,有 $\sum_{n=1}^{\infty}{\frac{(-1)^{n-1}}{n^{2}}}\!=\!{\frac{\pi^{2}}{12}}$  
# 第17讲  

# 多元函数积分学的预备知识(仅数学一 )  

# 知识结构  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/bdae491a065412c6b75154d69c90417bd44eac3899096cebb8b6142f6952a1bf.jpg)  
设$\begin{array}{r}{\pmb{a}=(a_{\lrcorner}\,,a_{\lrcorner}\,,a_{\lrcorner}\,)\,,\pmb{b}=(b_{\lrcorner}\,,b_{\lrcorner}\,,b_{\lrcorner}\,)\,,\pmb{c}=(c_{\b{c}}\,,c_{\b{y}}\,,c_{\b{z}}\,)\,,\pmb{a}\,,\pmb{b}\,,\pmb{c}}\end{array}$ 均为非零向量.  

（1）数量积（内积、点积）及其应用.  

$$
\begin{array}{r}{\mathbb{\backslash}a\,\bullet\,b=(a_{x}\,,\alpha_{y}\,,\alpha_{z}\,)\,\bullet\,(b_{x}\,,b_{y}\,,b_{z}\,)=\alpha_{x}b_{x}+a_{y}b_{y}+a_{z}b_{z}.}\end{array}
$$  

$\circled{2}\pmb{a}\cdot\pmb{b}=\lvert\pmb{a}\rvert\rvert\lvert\pmb{b}\rvert\cos\theta$ ，则  

其中 $\theta$ 为 $\pmb{a}\setminus\pmb{b}$ 的夹角.  

${\textcircled{3}}\mathrm{{Pr}}_{\mathrm{{i}}\bullet a}={\frac{a\cdot b}{\mid b\mid}}={\frac{a_{\mathit{r}}b_{\mathit{x}}+a_{\mathit{y}}b_{\mathit{y}}+a_{\mathit{z}}b_{\mathit{z}}}{{\sqrt{b_{\mathit{x}}^{2}+b_{\mathit{y}}^{\mathit{2}}+b_{\mathit{z}}^{\mathit{2}}}}}}$ 称为 $\pmb{a}$ 在 $\pmb{b}$ 上的投影.  

$\begin{array}{r}{\mathbb{\textregistered}\pmb{a}\,\perp\pmb{b}{\Longleftrightarrow}\pmb{a}_{s}\pmb{b}_{s}+\pmb{a}_{s}\pmb{b}_{s}+\pmb{a}_{\ast}\pmb{b}_{s}=0.}\end{array}$  

（2）向量积（外积、叉积）及其应用.  

$\mathbb{O}\pmb{a}\times\pmb{b}=\left|{\begin{array}{c c c}{i}&{j}&{k}\\ {a_{x}}&{a_{y}}&{a_{z}}\\ {b_{x}}&{b_{y}}&{b_{z}}\end{array}}\right|$ 其中 $|\,\pmb{a}\times\pmb{b}\,|=|\,\pmb{a}\,|\,\mid\,\pmb{b}\,|\,\sin\,\theta(\theta$ 为 $^{a,b}$ 的夹角),用右手规则确定  

方向(转向角不超过 $\pi$ )  

$$
\mathcal{Q}\pmb{a}\textit{/}/\mathbf{\nabla}b\Longleftrightarrow\frac{a_{\mathbf{\nabla}x}}{b_{x}}=\frac{a_{\mathbf{\nabla}y}}{b_{y}}=\frac{a_{\mathbf{\nabla}z}}{b_{z}}.
$$  

(3）混合积及其应用.  

$\langle{\mathbb J}[\,{\pmb a}\,{\pmb b}\,{\pmb c}\,]=({\pmb a}\times{\pmb b}\,)\,\cdot\,{\pmb c}=\left|{\pmb\ b}_{\pmb\mathscr{s}}\quad{\pmb b}_{\pmb\mathscr{s}}\quad{\pmb b}_{\mathscr{s}}\right.\,\Big|\,.$  $\textcircled{1}\textcircled{2}\textcircled{6}\textcircled{2}\textcircled{4}\textcircled{2}\textcircled{6}$ 三向量共面.  

（4）向量的方向角和方向余弦  

$\textcircled{1}$ 非零向量 $\pmb{a}$ 与 $_{x}$ 轴、 $_y$ 轴和 $_z$ 轴正向的夹角 $\alpha\,\,,\beta\,,\gamma$ 称为 $\pmb{a}$ 的方向角.  

$\circledcirc$  $\pmb{\alpha}$ cos $\u_{3}\,\beta\,,\cos\ u\mathrm{~,~}$  $\boldsymbol{\gamma}$ 称为 $\pmb{a}$ 的方向余弦,且 cos $\alpha=\frac{a_{x}}{|\textbf{\em a}|}$ .cos $\beta=\frac{a_{\,y}}{|\textbf{\em a}|}$ cos $\gamma=\frac{a_{z}}{|\textbf{\em a}|}$  $\odot a^{\circ}\!=\!{\frac{a}{\,|\,a\,|\,}}=(\cos\,\alpha\,,\cos\,\beta\,,\cos\,\gamma\,)$ 称为向量 $\pmb{a}$ 的单位向量（表示方向的向量）.  

$\circledast$ 任意向量 $r=x i+y j+z k=(r\cos\alpha\,,r\cos\beta,r\cos\gamma)=r(\cos\alpha\,,\cos\beta,r\cos\gamma),$  $\beta$ ,cos),其中cos $\pmb{\alpha}$ ,cos $\beta$ ,cos $\boldsymbol{\gamma}$ 为 $\pmb{r}$ 的方向余弦， $^r$ 为 $\pmb{r}$ 的模.  
# 1.平面  

以下假设平面的法向量 $\pmb{n}=(A\,,B\,,C)$  

$\textcircled{1}$ 一般式： $\begin{array}{r}{A x+B y+C z+D=0,}\end{array}$   
 $\circledcirc$ 点法式： $A\,(x-x_{\mathit{0}}\,)+B\,(y-y_{\mathit{0}}\,)+C\,(z-z_{\mathit{0}}\,)=0.$   
 $\textcircled{3}$ 三点式： ${\left|\begin{array}{l l l}{x-x_{1}}&{y-y_{1}}&{z-z_{1}}\\ {x-x_{2}}&{y-y_{2}}&{z-z_{2}}\\ {x-x_{3}}&{y-y_{3}}&{z-z_{3}}\end{array}\right|}=0($ 平面过不共线的三点 $P_{i}\left(x_{i}\,,y_{i}\,,z_{i}\,\right),i=1,2,3)$ ：  

$\circledast$ 截距式： $\frac{x}{a}+\frac{y}{b}+\frac{z}{c}=1$ 平面耐过 $\left(a\,,0\,,0\right),\left(0\,,b\,,0\right),\left(0\,,0\,,c\right)$ 三点).  

$\circled{5}$ 平面束方程.  

设$\pi_{i}:\!A_{i}x+B_{i}y+C_{i}z+D_{i}=0\,,i=1,2.$   
过 $L$ ： $\begin{array}{c}{{\beta_{1}x+B_{1}y+C_{1}z+D_{1}=0\,,}}\\ {{\mathrm{\large~|}_{A_{2}x}+B_{2}y+C_{2}z+D_{2}=0\,.}}\end{array}$ 的平面束方程为 $A_{1}x+B_{1}y+C_{1}z+D_{1}+\lambda\,(A_{2}x+B_{2}y+C_{2}z+D_{2})=0$ （不含 $\pi_{2}$ )， $A_{2}x+B_{2}y+C_{2}z+D_{2}+\lambda\,(A_{1}x+B_{1}y+C_{1}z+D_{1})=0$ （不含 $\pi_{1}$ ).  

# 2.直线  

以下假设直线的方向向量 $\pmb{\tau}=(l,m\,,n\,)$  

$\textcircled{1}$ 一般式： $\left\{\begin{array}{l l}{\displaystyle A_{1}x+B_{1}y+C_{1}z+D_{1}=0\,,}\\ {\displaystyle A_{2}x+B_{2}y+C_{2}z+D_{2}=0\,,}\end{array}\right.$ ,其中  

$\pmb{n}_{\mathrm{~1~}}\,\tilde{\chi}\,\pmb{n}_{\mathrm{~2~}}$  

【注】其几何背景很直观,是两个平面的交线,且该直线的方向向量 $\pmb{\tau}=\pmb{n}_{1}\times\pmb{n}_{2}$  

$\circledcirc$ 点向式： $\frac{x-x_{\mathit{0}}}{\mathit{l}}\,{=}\,\frac{y-y_{\mathit{0}}}{m}\,{=}\,\frac{z-z_{\mathit{0}}}{n}.$ $\lvert x=x_{\mathrm{~o~}}+l t$   
 $\textcircled{3}$ 参数式 $.\ensuremath{\left\{y=y_{0}+m t\,,M(x_{0},y_{0},z_{0})\right.}}$ 为直线上的已知点，t 为参数.=zo+nt，  

$\circled{4}$ 两点式： ${\frac{x-x_{1}}{x_{2}-x_{1}}}\!=\!{\frac{y-y_{1}}{y_{2}-y_{1}}}\!=\!{\frac{z-z_{1}}{z_{2}-z_{1}}}$ （直线过不同的两点 $P_{i}\left(x_{i}\,,y_{i}\,,z_{i}\,\right),i=1,2)$  
比宁高等数学18讲3. 位置关系  

# （1）点到直线的距离  

点$M_{1}(x_{1},y_{1},z_{1})$ 到直线 $L$ $\frac{x-x_{\mathit{0}}}{m}\!=\!\frac{y-y_{\mathit{0}}}{n}\!=\!\frac{z-z_{\mathit{0}}}{\mathit{\hbar}}$ 的距离  

$$
d=\frac{|\textbf{\em s}\times\overrightarrow{M_{1}M}\mid}{|\textbf{\em s}|}=\frac{\left|\begin{array}{c c c}{i}&{j}&{k}\\ {m}&{n}&{\phi}\\ {x_{0}-x_{1}}&{y_{0}-y_{1}}&{z_{0}-z_{1}}\end{array}\right|}{\sqrt{m^{2}+n^{2}+p^{2}}},
$$  

其中向量 $\dot{\overline{{M_{1}M}}}=(x_{0}-x_{1},y_{0}-y_{1},z_{0}-z_{1})\,,M=(x_{0}\,,y_{0}\,,z_{0})\,,s=(m\,,n\,,\phi).$  

【注】更为简单的是平面的情形：设在二维平面上直线 $L$ 的方程为 $A x+B y+C\,{=}\,0$ ，点 $P$ 的坐标为 $(x_{0},y_{0})$ ，则点 $P$ 到直线 $L$ 的距离公式为 $d={\frac{\mid A x_{\,0}+B y_{\,0}+C\mid}{\sqrt{A^{2}+B^{2}}}}$  

# （2）点到平面的距离。  

点 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 到平面 $\begin{array}{r}{A x+B y+C z+D=0}\end{array}$ 的距离 $d={\frac{\mid A x_{\,0}+B y_{\,0}+C z_{\,0}+D\mid}{{\sqrt{A^{2}+B^{2}+C^{2}}}}}.$  

# (3）直线与直线.  

设 $\pmb{\tau}_{1}=(l_{1}\,,m_{1}\,,n_{1})\,,\pmb{\tau}_{2}=(l_{2}\,,m_{2}\,,n_{2})$ 分别为直线 $L_{\mathrm{~l~}},L_{\mathrm{~2~}}$ 的方向向量.  
$\begin{array}{r}{\textcircled{1}L_{1}\perp L_{2}\overleftrightarrow{\boldsymbol{\tau}}_{1}\perp\boldsymbol{\tau}_{2}\overleftrightarrow{\boldsymbol{\cup}}l_{1}l_{2}+m_{1}m_{2}+n_{1}n_{2}=0.}\end{array}$   
$\circled{2}L_{1}$ /$L_{2}\{\rightleftarrows\pmb{\tau}_{1}\ /\mid\pmb{\tau}_{2}\ominus\frac{l_{1}}{l_{2}}=\frac{m_{\mathrm{~l~}}}{m_{\mathrm{~2~}}}\!=\!\frac{n_{\mathrm{~l~}}}{n_{\mathrm{~2~}}}.$   
 $\textcircled{3}$ 直线 $L_{1}\,,L_{2}$ 的夹角 $\theta=$ arcos $\frac{\mid\pmb{\tau}_{1}\cdot\pmb{\tau}_{2}\mid}{\mid\pmb{\tau}_{1}\mid\mid\pmb{\tau}_{2}\mid}$ 其中 $\theta=\,\mathrm{min}\{(\,\widehat{\tau_{1},\tau_{2}}\,\,)\,,\pi-(\,\widehat{\tau_{1},\tau_{2}}\,\,)\}\in\,\left[0,\!\frac{\pi}{2}\right].$  

（4）平面与平面.  

设平面 $\pi_{\mathrm{~l~}},\pi_{\mathrm{~2~}}$ 的法向量分别为 $\pmb{n}_{1}=(A_{1}\,,B_{1}\,,C_{1}\,)\,,\pmb{n}_{2}=(A_{2}\,,B_{2}\,,C_{2}\,).$ $\begin{array}{r}{\mathbb{D}{\pmb\pi}_{1}\perp{\pmb\pi}_{2}\!\leftrightarrow\!{\pmb n}_{1}\perp{\pmb n}_{2}\!\leftrightarrow\!{\pmb A}_{1}{\pmb A}_{2}+{\pmb B}_{1}{\pmb B}_{2}+{\pmb C}_{1}{\pmb C}_{2}=0.}\end{array}$ ②$\pi_{1}\textit{}//\ \pi_{2}\Longleftrightarrow\!\pmb{n}_{1}\textit{}//\ \pmb{n}_{2}\Longleftrightarrow\frac{A_{1}}{A_{2}}=\frac{B_{1}}{B_{2}}=\frac{C_{1}}{C_{2}}.$  $\textcircled{3}$ 平面 $\pi_{1},\pi_{2}$ 的夹角 $\theta=$ arccos $\frac{\mid n_{1}\cdot n_{2}\mid}{\mid n_{1}\mid\mid n_{2}\mid}$ 其中 $\theta=\operatorname*{min}\{(\widehat{\textbf{\em n}_{1}\,,\pmb{n}_{2}}\,)\,,\pi-(\widehat{\textbf{\em n}_{1}\,,\pmb{n}_{2}}\,)\}\,\in$ $\left[0,{\frac{\pi}{2}}\right].$  

# （5）平面与直线.  

设直线 $L$ 的方向向量为 $\pmb{\tau}=(l,m\,,n\,)$ ，平面 $\pi$ 的法向量为 $\pmb{n}=(A\,,B\,,C)$   
$\mathbb{O}L\ \perp\pi\Longleftrightarrow\pmb{\tau}\ //\ \pmb{n}\Longleftrightarrow\frac{l}{A}=\frac{m}{B}=\frac{n}{C}.$   
$\circled{2}L~//~\pi\Longleftrightarrow\tau\perp n\Longleftrightarrow A l+B m+C n=0.$  
$\textcircled{3}$ 直线 $L$ 与平面 $\pi$ 的夹角 $\theta=\arcsin{\frac{\mid\tau\cdot n\mid}{\mid\tau\mid\mid n\mid}}$ 其中 $\theta=\left.\left|\,\frac{\pi}{2}-(\widehat{\pmb{\tau}}\,,\!{\pmb{n}}\,)\,\right|\in\,\left[0,\!\frac{\pi}{2}\right].$  

例 17. 1设有直线 $L_{\mathrm{~l~}}$  ${\frac{x-1}{1}}\!=\!{\frac{y-5}{-2}}\!=\!{\frac{z+8}{1}}$  $L_{2}:{\binom{x-y}{2y+z=3}},$ 则 $L_{\parallel}$ 与 $L_{\mathrm{~2~}}$ 的夹角为  

(A) $\frac{\pi}{6}$ (B) $\frac{\pi}{4}$ (C) $\frac{\pi}{3}$ $(\mathrm{D})\,\frac{\pi}{2}$  

【解】应选(C):  

直线 $L_{\textrm{l}}$ 的方向向量为 $\pmb{n}_{1}=(1,-2,1)$ ，直线 $L_{\mathrm{~2~}}$ 的方向向量为  

$$
\begin{array}{r}{\pmb{n}_{\,2}=\left|\begin{array}{c c c}{i}&{j}&{k}\\ {1}&{-\,1}&{0}\\ {0}&{2}&{1}\end{array}\right|=-i-j+2k\,,}\end{array}
$$  

从而直线 $L_{\mathrm{~l~}}$  $L_{2}$ 的夹角 $\varphi$ 的余弦为 cos $\varphi={\frac{\mid\pmb{n}_{1}\cdot\pmb{n}_{2}\mid}{\mid\pmb{n}_{1}\mid\mid\pmb{n}_{2}\mid}}={\frac{3}{\sqrt{6}\,\cdot\sqrt{6}}}={\frac{1}{2}}$ 因此 $\varphi=\frac{\pi}{3}$ 空间曲线的切线与法平面(1）用参数方程给出曲线： $\begin{array}{l}{\displaystyle\left\{x=x\left(t\right),\right.}\\ {\displaystyle\left\{y=y\left(t\right),t\,\in\,I.\right.}\\ {\displaystyle\left.z=z\left(t\right),\right.}\end{array}$  

其中 $x\left(t\right),y\left(t\right),z\left(t\right)$ 在 $I$ 上可导,且三个导数不同时为0,则曲线在 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 处的切向量 $\pmb{\tau}=(x^{\prime}(t_{0}),y^{\prime}(t_{0}),z^{\prime}(t_{0}))$  

切线方程 ${\frac{x-x_{0}}{x^{\prime}(t_{0})}}\,{=}{\frac{y-y_{0}}{y^{\prime}(t_{0})}}\,{=}{\frac{z-z_{0}}{z^{\prime}(t_{0})}}$ 法平面方程： $x^{\prime}(t_{0})(x-x_{0})+y^{\prime}(t_{0})(y-y_{0})+z^{\prime}(t_{0})(z-z_{0})=0.$  

$\begin{array}{l}{\left\langle F(x\mathbin{,}y\mathbin{,}z)=0\right.}\\ {\left.G(x\mathbin{,}y\mathbin{,}z)=0\right.}\end{array}$ ，  
（2）用方程组给出曲线：  
当 $\frac{\partial(F,G)}{\partial(y\,,z)}=\left|\frac{\partial F}{\partial y}\quad\frac{\partial F}{\partial z}\right|\neq0$ 时，可确定 $\left\{\begin{array}{l l}{x=x\,\,,}\\ {y=y\left(x\,\right),}\\ {z=z\left(x\,\right).}\end{array}\right.$   
取$\begin{array}{r}{\boldsymbol{\tau}=\left|\begin{array}{c c c}{i}&{j}&{k}\\ {F_{x}^{\prime}}&{F_{y}^{\prime}}&{F_{z}^{\prime}}\\ {G_{x}^{\prime}}&{G_{y}^{\prime}}&{G_{z}^{\prime}}\end{array}\right|_{P_{0}}=(A\,,B\,,C).}\end{array}$   
切线方程： $\frac{x-x_{\mathit{0}}}{A}\,{=}\,\frac{y-y_{\mathit{0}}}{B}\,{=}\,\frac{z-z_{\mathit{0}}}{C}$   
法平面方程： $A\,(x-x_{\mathit{\circ}}\,)+B\,(y-y_{\mathit{\circ}}\,)+C\,(z-z_{\mathit{\circ}}\,)=0.$  
例17.2设函数 $z\,=\,f(x\,,y\,)$ 在点（0,0）附近有定义，且 $f_{{\,\,\,x}}^{\prime}\left(0,0\right)\,=3$ ，则曲线 $\begin{array}{l}{{\ f=f(x\cdot y)\,,}}\\ {{\,}}\\ {{y=0}}\end{array}$ 在点 $(0,0,f(0,0))$ 处的法平面方程为  

【解】应填 $x+3z-3f(0,0)=0$ 曲线 $\left\{z=f(x\,,y\,)\,,\right.$ 可写成参数式： $\displaystyle\left\{{\begin{array}{l}{x=t\,,}\\ {y=0\,,}\\ {z=f(t\,,0)}\end{array}}\right.$ 则，  

$$
\begin{array}{r}{\pmb{\tau}=(x_{\iota}^{\prime},y_{\iota}^{\prime},z_{\iota}^{\prime})\Bigm|_{\iota=0}=(1,0,f_{\iota}^{\prime}(0,0))=(1,0,3).}\end{array}
$$  

故所求法平面方程为 $x+3z-3f(0,0)=0$  

（1）用隐式方程给出曲面： $F(x\,,y\,,z)=0$ ，其中 $F$ 的一阶偏导数连续。  

其在 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 处的法向量 $\boldsymbol{n}=\left(\boldsymbol{F}_{\boldsymbol{x}}^{\prime}\;\Big|_{\boldsymbol{P}_{0}}\,,\boldsymbol{F}_{\boldsymbol{y}}^{\prime}\;\Big|_{\boldsymbol{P}_{0}}\,,\boldsymbol{F}_{\boldsymbol{z}}^{\prime}\;\Big|_{\boldsymbol{P}_{0}}\right).$ 切平面方程 $|F_{x}^{\prime}\;\biggr|_{P_{0}}\bullet(x-x_{0})+F_{y}^{\prime}\;\biggr|_{P_{0}}\bullet(y-y_{0})+F_{z}^{\prime}\;\biggr|_{P_{0}}\bullet(z-z_{0})=0.$ 法线方程： $\frac{x-x_{\,0}}{F_{x}^{\prime}\mid_{_{P_{0}}}}\,{=}\frac{y-y_{\,0}}{F_{y}^{\prime}\mid_{_{P_{0}}}}\,{=}\frac{z-z_{\,0}}{F_{z}^{\prime}\mid_{_{P_{0}}}},$  

# (2）用显式函数给出曲面： $z=f(x\,,y\,){\Rightarrow}f(x\,,y\,)-z=0$ ，其中 $f$ 的一阶偏导数连续.  

其在 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 处的法向量 $\pmb{n}=(f_{\mathrm{~}x}^{\prime}(x_{0}\,,\pmb{y}_{\mathrm{~}})\,,f_{\mathrm{~}y}^{\prime}(x_{0}\,,\pmb{y}_{\mathrm{~}})\,,-1).$ 此法向量方向向下.  
切平面方程 $:f_{\mathfrak{x}}^{\prime}(x_{0},y_{0})(x-x_{0})+f_{\mathfrak{x}}^{\prime}(x_{0},y_{0})(y-y_{0})-(z-z_{0})=0.$ 法线方程： $\frac{x-x_{0}}{f_{\;x}^{\prime}(x_{0},y_{0})}=\frac{y-y_{0}}{f_{\;y}^{\prime}(x_{0},y_{0})}=\frac{z-z_{0}}{-1}.$  

例17.3曲面 $\mathbf e^{\frac{x}{2}}+\mathbf e^{\frac{y}{2}}=4$ 在点 $(\ln\,2\,,\ln\,2\,,1)$ 处的切平面方程为  

【解】应填 $\begin{array}{r}{x+y-(2\ln\,2)z=0}\end{array}$ 令$F(x,y\,,z)=\mathrm{e}^{\frac{x}{z}}+\mathrm{e}^{\frac{y}{z}}-4$ ,则 $F_{x}^{\prime}\!=\frac{1}{z}\mathrm{e}^{\frac{x}{z}}\,,F_{y}^{\prime}\!=\frac{1}{z}\mathrm{e}^{\frac{y}{z}}\,,F_{z}^{\prime}\!=\,-\frac{x}{z^{2}}\mathrm{e}^{\frac{x}{z}}\!-\!\frac{y}{z^{2}}\mathrm{e}^{\frac{y}{z}}$ $\begin{array}{r}{\mathrm{e}^{\frac{x}{z}}+\mathrm{e}^{\frac{y}{z}}=}\end{array}$ 4在点 $(\ln{2},\ln{2},1)$ 处的法向量为  

$$
{\pmb n}=\left(\frac{1}{z}\mathrm{e}^{\frac{x}{z}}\,,\frac{1}{z}\mathrm{e}^{\frac{z}{z}}\,,-\frac{x}{z^{2}}\mathrm{e}^{\frac{x}{z}}-\frac{y}{z^{2}}\mathrm{e}^{\frac{z}{z}}\right)\bigg|_{\{{\mathrm{In}\:2,\ln\:2,1}\}}=(2,2,-4\ln\:2).
$$  

于是在点 $(\ln{2},\ln{2},1)$ 处的切平面方程为  

$$
2(x-\ln2)+2(y-\ln2)-4\ln\,2(z-1)=0\,,
$$  

即$x+y-(2\ln\,2)z=0$  

例17.4设 $f$ 可微,则曲面 $\mathrm{e}^{2x-z}=f(\pi y-\sqrt{2}\,z\,)$ 是(  
（A）旋转抛物面(B)双叶双曲面  

(C)单叶双曲面(D)柱面  

【解】应选(D).  

定直线L  

设 $F=f(\pi y-\sqrt{2}\,z)-\mathrm{e}^{2x-z}$ ,则曲面上任一点处的法向量为  

$$
\pmb{n}=(-\,2\mathrm{e}^{2x-z}\,,\pi f^{\prime}\,,-\sqrt{2}\,f^{\prime}+\mathrm{e}^{2x-z}\,).
$$  

设某定向量 $\pmb{\tau}=(a\,,\!b\,,\!c\,)(a\,,\!b\,,\!c$ 不同时为零）与 $\pmb{n}$ 垂直，即  

$$
\begin{array}{r}{\pmb{n}\,\cdot\,(\alpha\,,b\,,c\,)=-\,2a\,\mathrm{e}^{2x-z}+\pi b f^{\prime}+(-\sqrt{2}\,f^{\prime}+\mathrm{e}^{2x-z}\,)c\equiv0\,,}\end{array}
$$  

解得 $a=\frac{c}{2},b=\frac{\sqrt{2}}{\pi}c$ ，令 $c=1$ ,则 $a={\frac{1}{2}},b={\frac{\sqrt{2}}{\pi}}$ ,这样曲面上任一点处的法向量 $\pmb{n}$ 均与定向量$\left({\frac{1}{2}},{\frac{\sqrt{2}}{\pi}},1\right)$ 垂直,这说明该曲面是柱面.  

# 五空间曲线在坐标面上的投影  

以求空间曲线 $\boldsymbol{\Gamma}$ 在 $x\,O y$ 面上的投影曲线为例.将 ${\boldsymbol{r}}$  $\mathrel{\mathop:}\left\{\!\!\begin{array}{l}{{F\left(x\,,y\,,z\right)=0\,,}}\\ {{G\left(x\,,y\,,z\right)=0}}\end{array}\right.$ 中的 $_z$ 消去，得到 $\varphi(x\,,\!y\,)=0$ ，则曲线 $\boldsymbol{\Gamma}$ 在 $x\,O y$ 面上的投影曲线包含于曲线 $\left\{\begin{array}{l}{\varphi\left(x\wedge y\right)=0\,,}\\ {z=0.}\end{array}\right.$  

曲线 $\boldsymbol{\Gamma}$ 在其他平面上的投影曲线可类似求得.  

# 六旋转曲面：曲线厂绕一条定直线旋转一周所形成的曲面  

曲线 $\boldsymbol{\Gamma}$ ： $\begin{array}{l}{\left\langle F\left(x\,,y\,,z\right)=0\,,\right.}\\ {\left.G\left(x\,,y\,,z\right)=0\right.}\end{array}$ 绕直线 $L$ ： $\frac{x-x_{0}}{m}\!=\!\frac{y-y_{0}}{n}\!=\!\frac{z-z_{0}}{\beta}$ 旋转一周形成  

一个旋转曲面，旋转曲面方程的求法如下.  

如图17-1所示，设 $M_{0}(x_{0}\,,y_{0}\,,z_{0})$ ，方向向量 $\pmb{s}=(m,n\,,p\,).$ 在母线 $\boldsymbol{\Gamma}$ 上任取一点 $M_{1}(x_{1},y_{1},z_{1})$ ，则过 $M_{1}$ 的纬圆上的任意一点 $P(x\,,y\,,z)$ 满足条件  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/802c8887ab4b960ce33732579124753e8458b467fae8a1ac3c54d78489a0032d.jpg)  

即  

$$
\begin{array}{r}{\overrightarrow{M_{1}P}\perp s\cdot\vert\overrightarrow{M_{0}P}\vert=\vert\overrightarrow{M_{0}M_{1}}\vert\:,\qquad\qquad\qquad\qquad\:\:\:\:\tilde{M}_{0}}\\ {\left\vert\overset{\quad,\quad}{\sim}(x-x_{1})+n(y-y_{1})+\beta(z-z_{1})=0,\qquad\qquad\qquad\qquad\qquad\quad\:\:\right\vert}\\ {\left\vert(x-x_{0})^{2}+(y-y_{0})^{2}+(z-z_{0})^{2}=(x_{1}-x_{0})^{2}+(y_{1}-y_{0})^{2}+(z_{1}-z_{0})^{2}\right\vert}\end{array}
$$  

与方程 $F(x_{1}\,,y_{1}\,,z_{1})=\,0$ 和 $G(\mathbf{\psi}_{x_{1}},\mathbf{\psi}_{y_{1}}\,,\mathbf{\psi}_{z_{1}})=\,0$ 联立消去 $x_{\mathrm{~1~}},y_{\mathrm{~1~}},z_{\mathrm{~1~}}$ ,便可得到旋转曲面的方程.  

注】常考曲线 $\boldsymbol{\Gamma}$  $\scriptstyle{\begin{array}{l}{F(x\,,y\,,z)\;=0\,,}\\ {G(x\,,y\,,z)\;=0}\end{array}}$ 绕 $_z$ 轴旋转一周而成的旋转曲面的方程  
如图 17-2 所示,在曲线 $\boldsymbol{r}$ 上任取一点 $M_{1}(x_{1},y_{1},z_{1})$ ，则过点 $M_{1}$ 的纬圆上的任意一点 $P(x,y,z)$ 满足条件 $|\overrightarrow{O P}|=\ |\overrightarrow{O M_{1}}|$ 和 $z=z_{1}$ ,即$x^{2}+y^{2}+z^{2}=x_{1}^{2}+y_{1}^{2}+z_{1}^{2}$ 且$z=z_{1}$ ，得  

$$
x^{2}+y^{2}=x_{1}^{2}+y_{1}^{2}.
$$  

$\left(F\left(x_{1},y_{1},z\right)=0\right)$  

从方程组 $\xi(x_{1},y_{1},z)=0$ ，中消去 $x_{1}$ 和 $y_{1}$ ,便得到旋转曲面的$x^{2}+y^{2}=x_{1}^{2}+y_{1}^{2}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a45b4b8f0ee6e3b7c0e0c8febb56076fb62468e1910893641ea974c992448d92.jpg)  
图17-2  

方程。  

如果能从方程组 $\begin{array}{r}{\left\langle F(x\,,y\,,z)=\,0\,,\right.}\\ {\left.G(x\,,y\,,z)=\,0\right.}\end{array}$ 中解出 $x=f_{1}(z)$ 和 $y=f_{2}(z)$ ,则旋转曲面的方程为  

$$
x^{2}+y^{2}=[f_{1}(z)]^{2}+[f_{2}(z)]^{2}.
$$  

同理， $\boldsymbol{r}$ 绕 $_y$ 轴旋转一周而成的旋转曲面的方程为 $x^{2}+z^{2}=[f_{3}(y)]^{2}+[f_{4}(y)]^{2}\,;\Gamma$ 绕 $_{x}$ 轴旋转一周而成的旋转曲面的方程为 $y^{2}+z^{2}=[f_{\textsf{s}}(x)]^{2}+[f_{\textsf{6}}(x)]^{2}$ .若记得住这些公式，可直接套用.  

例17.5设 $\Sigma_{1}$ 是由过点 $(0,-1,1)$ 与点（0，0，0）的直线 $L$ 绕 $\mathcal{Z}$ 轴旋转一周所得的旋转曲面位于 $z\geqslant0$ 的部分， $\Sigma_{2}$ 的方程为 $z^{2}=2x$ ，则 $\Sigma_{\scriptscriptstyle1}$ 与 $\Sigma_{2}$ 的交线 $\boldsymbol{\Gamma}$ 在 $_{x}O y$ 面上的投影曲线方程为  

【解】应填 $\scriptstyle{\begin{array}{l}{x^{2}+y^{2}=2x}\\ {z=0.}\end{array}}$ 直线 $L$ 的两点式方程为 ${\frac{x}{0}}={\frac{y+1}{1}}={\frac{z-1}{-1}}$ 参数方程为 $\begin{array}{r}{\left\{x=0\,,\right.}\\ {\left.y=-1+t\,,t\right.}\\ {\left.z=1-t\,,\right.}\end{array}$ 为参数，即 $\displaystyle{\begin{array}{l}{x=0\,,}\\ {y=-\,z}\end{array}}$ 由六的注，得 $\Sigma_{1}$ 的方程为 $x^{2}+y^{2}=0^{2}+(-z\,)^{2}=z^{2}$ ，也即 $z=\sqrt{x^{2}+y^{2}}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f9965c5d926cc6026d56354f033f58a25fd9559a10458a3307ded0413bd6633f.jpg)  
图17-3  

将 $\begin{array}{c}{{z=\sqrt{x^{2}+y^{2}}}}\\ {{\mathrm{}}}\\ {{z^{2}=2x}}\end{array}$ 中的 $_z$ 消去，得 $x^{2}+y^{2}=2x$ ,即得到投影曲线方程为 $\displaystyle{\xi^{2}+y^{2}=2x}$ 曲线 $\boldsymbol{\Gamma}$ 和其在 $x O y$ 面上的投影如图17-3所示.  

例17.6直线 $L$  $\begin{array}{r}{\left\langle x-y+2z-1=0\,,\right.}\\ {\left.x-3y-2z+1=0\right.}\end{array}$  $_y$ 轴旋转一周所形成的曲面方程为  

【解】应填 $4x^{2}-17y^{2}+4z^{2}+2y-1=0.$  

如图17-4所示，在直线 $L$ 上任取一点 $M_{1}(x_{1},y_{1},z_{1})$ ，则过点 $M_{\sun}$ 的纬圆上的任一点 $P\left(\boldsymbol{\mathscr{x}}\,,\boldsymbol{\mathscr{y}}\,,z\right)$ 满足条件 $|\overrightarrow{O M_{1}}|=|\overrightarrow{O P}|$ ，且${y=y_{1}}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/43ac27cf144d7d7edc9c5ba637374e9e0ff606e0406ccd1633d004490367d3a3.jpg)  
图17-4  
于是由 $x^{2}+y^{2}+z^{2}=x_{1}^{2}+y_{1}^{2}+z_{1}^{2}$ ,得 $x^{2}+z^{2}=x_{1}^{2}+z_{1}^{2}$  

由 $L$ 的方程解出 $x_{1}=2y_{1}\,,z_{1}=-\frac{1}{2}(y_{1}-1)$ ,即 $x_{1}=2y\,,z_{1}=-\frac{1}{2}(y-1)$ .于是旋转曲面方程为  

$$
x^{2}+z^{2}=(2y)^{2}+\left[-\,{\frac{1}{2}}(y-1)\right]^{2},\mathbb{R}[\![\ 4\,x^{2}-17y^{2}+4z^{2}+2y-1=0.
$$  

【注】由六的注，根据 $L$ 的方程 $\begin{array}{r}{\left\{x-y+2z-1=0\,,\right.}\\ {\left.x-3y-2z+1=0\right.}\end{array}$ 解得 $\left\{x=2y\,,\right.$ 于是直接得 $L$ 绕 $_y$ 轴旋转一周所形成的曲面方程为 $x^{2}+z^{2}=(2y)^{2}+\left[-{\frac{1}{2}}(y-1)\right]^{2}$ ，即$4x^{2}-17y^{2}+4z^{2}+2y-1=0.$  

# 七场论初步  

# 1.方向导数  

定义设三元函数 $u=u\left(\boldsymbol{x}\,,y\,,z\,\right)$ 在点 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 的某空间邻域 $U\subset\mathbf{R}^{3}$ 内有定义，$\iota$ 为从点 $\boldsymbol{P}_{\circ}$ 出发的射线， $P\left(\boldsymbol{x},\boldsymbol{y}\,,z\right)$ 为$l$ 上且在 $U$ 内的任一点，则  

$$
\begin{array}{c}{{\left[x\,-x\,_{0}=\Delta x=t\cos\,\alpha\;,\right.}}\\ {{\left.y\,-y_{\,0}=\Delta y=t\cos\,\beta\,,\right.}}\\ {{\left.z\,-z_{\,0}=\Delta z=t\cos\,\gamma.\right.}}\end{array}
$$  

以 $t=\sqrt{(\Delta x)^{2}+(\Delta y)^{2}+(\Delta z)^{2}}$ 表示 $P$ 与 $\scriptstyle P_{\mathrm{~0~}}$ 之间的距离，如图17-5所示，若极限  

$$
\begin{array}{l}{{\displaystyle\operatorname*{lim}_{\iota\rightarrow0^{+}}\frac{u(P)-u(P_{0})}{t}}}\\ {{=\displaystyle\operatorname*{lim}_{\iota\rightarrow0^{+}}\frac{u(x_{0}+t\cos\alpha,y_{0}+t\cos\beta,z_{0}+t\cos\gamma)-u(x_{0},y_{0},z_{0})}{t}}}\end{array}
$$  

存在，则称此极限为函数 $u\!=\!u\!\left(\boldsymbol{x}\,,y\,,z\,\right)$ 在点 $\scriptstyle P_{\ o}$ 处沿方向 $\iota$ 的方向导数，记作 $\left.\frac{\partial u}{\partial l}\ \right|_{P_{0}}.$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/3d0154a0f9d8fdd925306161860aef326553a3a7894e1838abca45efeec52544.jpg)  
图17-5  

定理(方向导数的计算公式）设三元函数 $u\!=\!u\!\left(\boldsymbol{x},\boldsymbol{y}\,,z\right)$ 在点 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 处可微分，则 $u=u\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\right)$ 在点 $\boldsymbol{P}_{\circ}$ 处沿任一方向 $\iota$ 的方向导数都存在，且  

$$
\left.\frac{\partial u}{\partial l}\,\right|_{\;P_{0}}=u_{x}^{\prime}\,(P_{\circ})\cos\,\alpha\,+u_{y}^{\prime}\,(P_{\circ})\cos\,\beta+u_{z}^{\prime}\,(P_{\circ})\cos\,\gamma\,,
$$  

其中cos $\alpha$ ,cos $\beta\,,\mathtt{c o}$ s $\gamma$ 为方向 $\iota$ 的方向余弦.  

【注】二元函数 $f(x\,,y\,)$ 的情况与三元函数类似。  
# 张宁高等数学18讲  

# 2.梯度  

定义设三元函数 $u=u\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,\right)$ 在点 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 处具有一阶连续偏导数,则定义  

$$
{\bf g r a d}\;u\;\Big|_{{\bf\epsilon}_{0}}=(u_{x}^{\;^{\prime}}(P_{\;0}\,)\,,u_{y}^{\;^{\prime}}(P_{\;0}\,)\,,u_{z}^{\;^{\prime}}(P_{\;0}\,)\,)
$$  

为函数 $u=u\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,\right)$ 在点 $\boldsymbol{P}_{0}$ 处的梯度.  

3.方向导数与梯度的关系  

由方向导数的计算公式 $\left.\times\frac{\partial u}{\partial l}\right|_{P_{0}}=\left.u_{x}^{\prime}(P_{0}\,)\cos\alpha+u_{y}^{\prime}(P_{0}\,)\cos\beta+u_{z}^{\prime}(P_{0}\,)\cos\gamma$ 与梯度的定义  

$$
\begin{array}{r l}&{\frac{\partial u}{\partial l}\bigg|_{P_{0}}=(u_{x}^{\prime}(P_{0})\,,u_{y}^{\prime}(P_{0})\,,u_{z}^{\prime}(P_{0})\,)\bullet\,(\cos\,\alpha\,,\cos\,\beta\,,\cos\,\gamma)=\bf{g r a d}\,\,u\bigg|_{P_{0}}\bullet l^{\circ}}\\ &{\qquad\quad=\biggr|\,{\bf g r a d}\,\,u\bigg|_{P_{0}}\;\bigg|\,\mid\,l^{\circ}\,\mid\,\cos\,\theta=\biggr|\,{\bf g r a d}\,\,u\bigg|_{P_{0}}\;\bigg|\,\cos\,\theta\,,}\end{array}
$$可得到  

其中 $\theta$ 为grad $u\mid_{P_{0}}$ 与 $l^{\circ}$ 的夹角,当 cos $\theta=1$ 时， $\frac{\partial u}{\partial l}\bigg|_{P_{\varrho}}$ 有最大值.  

于是有重要结论：函数在某点处的梯度是一个向量，它的方向与取得最大方向导数的方向一致，而它的模为方向导数的最大值  

$$
|\,\mathbf{grad}\;u\;|\!=\!\sqrt{(u_{x}^{\prime}\,)^{2}+(u_{y}^{\prime}\,)^{2}+(u_{z}^{\prime}\,)^{2}}.
$$  

# 4.散度  

定义设向量场 $A\left(x\,,y\,,z\,\right)=P\left(x\,,y\,,z\,\right)\,\!i+Q\left(x\,,y\,,z\,\right)\,\!j+R\left(x\,,y\,,z\,\right)k$ ，则  

$A=\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z}$  

叫作向量场A的散度.  

注）（1）考小题时，直接套公式即可，  

（2）稍作解释:div A表示场在 $(x,y,z)$ 处源头的强弱程度，若div ${\bf A}=0$ 在场内处处成立，则称 A 为无源场.  

# 5.旋度  

定义设向量场 ${\bf A}\left(x\,,y\,,z\,\right)=P\left(x\,,y\,,z\,\right)\!i+Q\!\left(x\,,y\,,z\,\right)\!j+R\left(x\,,y\,,z\,\right){k}$ ，则  

$$
\mathbf{rot}\;\mathbf{A}=\left|{\frac{i}{\partial x}}\quad{\frac{j}{\partial y}}\quad{\frac{k}{\partial z}}\right|
$$  

叫作向量场A的旋度.  
【注】(1)考小题时,直接套公式即可.  

(2) 稍作解释;rot $\pmb{A}$ 表示场在 $(x,y,z)$ 处最大旋转趋势的度量,若 rot $\mathbf{A}=\mathbf{0}$ 在场内处处成立，则称 A 为无旋场.  

例 17. 7函数 $f(x\,,y\,,z)=x^{\,2}y+z^{2}$ 在点（1,2,0）处沿向量 $\pmb{n}=(1,2,2)$ 的方向导数为).  

(A)12 (B)6 (C)4 (D)2  

【解】应选(D).  

因为函数可微分，且  

$$
\frac{\partial f}{\partial x}\bigg\vert_{(1,2,0)}=2x y\bigg\vert_{(1,2,0)}=4\,,\frac{\partial f}{\partial y}\bigg\vert_{(1,2,0)}=x^{2}\bigg\vert_{(1,2,0)}=1\,,\frac{\partial f}{\partial z}\bigg\vert_{(1,2,0)}=2z\,\bigg\vert_{(1,2,0)}=0\,,
$$  

与 $\pmb{n}$ 同方向的单位向量为 ${\frac{n}{\mid n\mid}}=\left({\frac{1}{3}},{\frac{2}{3}},{\frac{2}{3}}\right)$ ，所以所求方向导数为  

$$
\left.\frac{\partial f}{\partial\pmb{n}}\right\rvert_{(1,2,0)}=4\times\frac{1}{3}+1\times\frac{2}{3}+0\times\frac{2}{3}=2.
$$  

例17.8已知二元函数  

$$
f(x\,,y)=\!\left\{\!x+y+\!\frac{x^{\,3}y}{x^{\,4}+y^{\,2}},\!\begin{array}{l l}{(x\,,y)\neq(0\,,0)\,,}\\ {\quad}&{(x\,,y)=(0\,,0)\,,}\end{array}\right.
$$  

则$f(x\,,y\,)$ 在点(0,0)处( ).  

（A）可微，且沿 $\pmb{l}=(\cos\alpha$ ,cos $\beta$ ）的方向导数存在（B）可微，但沿 $\pmb{l}=(\cos\alpha$ ,cos $\beta$ ）的方向导数不存在（C）不可微，但沿 $\pmb{l}=(\cos\alpha$ ,cos $\beta$ ）的方向导数存在（D）不可微，且沿 $\pmb{l}=(\cos\alpha$ ,cos $\beta$ ）的方向导数不存在  

【解】应选(C).  

由于故  

$f_{x}^{\prime}\left(0,0\right)=\operatorname*{lim}_{x\to0}\frac{f(x\,,0)-f(0,0)}{x-0}=1,f_{y}^{\prime}\left(0,0\right)=\operatorname*{lim}_{y\to0}\frac{f(0,y)-f(0,0)}{y-0}=1,$ $\Delta f-(\Delta x+\Delta y)=\frac{(\Delta x)^{3}\Delta y}{(\Delta x)^{4}+(\Delta y)^{2}}.$  

取路径 $\Delta y=(\Delta x)^{2}$ ，则  

$$
\operatorname*{lim}_{3x^{-\infty}(3x)^{2}}\frac{(\Delta x\,)^{3}\Delta y}{(\Delta x\,)^{4}+(\Delta y\,)^{2}}\bullet\frac{1}{\sqrt{(\Delta x\,)^{2}+(\Delta y\,)^{2}}}\mathop{=\operatorname*{lim}}_{\Delta x\,\to\,0}\frac{(\Delta x\,)^{5}}{2(\Delta x\,)^{4}\bullet\mid\Delta x\mid\sqrt{1+(\Delta x\,)^{2}}}\neq
$$  

故 $f(x\,,y\,)$ 在点（0，0）处不可微，需用定义求方向导数.  

令$\Delta x=\rho\cos\,\alpha\,,\Delta y=\rho\cos\,\beta$ ，则 $\rho=\sqrt{(\Delta x\,)^{2}+(\Delta y\,)^{2}}$ ,从而  

$$
\left.\frac{\partial f}{\partial l}\,\right|_{(0,0)}=\operatorname*{lim}_{\rho\to0^{+}}\frac{f(\Delta x\,,\Delta y\,)-f(0\,,0)}{\rho}
$$  
$$
\begin{array}{r l}&{=\underset{\rho\to0^{+}\;}{\operatorname*{lim}}\ \frac{1}{\rho}\Big(\rho\cos\alpha+\rho\cos\beta+\frac{\rho^{4}\cos^{3}\alpha\cos\beta}{\rho^{4}\cos^{4}\alpha+\rho^{2}\cos^{2}\beta}\Big)}\\ &{=\cos\alpha+\cos\beta.}\end{array}
$$  

故方向导数存在，选(C).  

例 17. 9（1）已知直线 $L$ 是直线  

$$
\begin{array}{l}{{\(2x-z-3=0\,,}}\\ {{\qquad y-2z+4=0}}\end{array}
$$  

在平面 $x+y-z=5$ 上的投影方程,求 $L$ 的表达式；  

(2）求函数 $f(x\,,y\,,z)=\cos^{2}x y+{\frac{y}{z^{2}}}$ 在点 $P\left(0,-1,1\right)$ 处沿直线 $L$ 的方向导数.  

【解】（1）设过直线 $L$ 的平面束方程为 $(2x-z-3)+\lambda\,(y-2z+4)=0$ ，即  

$$
2x+\lambda y-(2\lambda+1)z+4\lambda-3=0
$$  

其中 $\lambda$ 为待定常数.此平面与平面 $x+y-z=5$ 垂直的条件是  

$$
2\bullet1+\lambda\,\cdot\,1-(2\lambda+1)\,\bullet\,(-\,1)=0\,,
$$  

解得 $\lambda=-1$ ，故直线 $L$ 为  

$$
\begin{array}{l}{\left\langle2x-y+z-7=0\,,\right.}\\ {\left.\quad x+y-z=5.\right.}\end{array}
$$  

（2）由(1)知，直线 $L$ 的方向向量为 ${\begin{array}{l l l}{\left|{\begin{array}{l l l}{i}&{j}&{k}\\ {2}&{-1}&{1}\\ {1}&{1}&{-1}\end{array}}\right|}=3j+3k}$ ，取 $\pmb{\tau}=(0,\!1,\!1)$ 即可，其方向余弦  

$$
(\cos\,\alpha\,,\cos\,\beta\,,\cos\,\gamma\,)=\pm\,{\frac{\tau}{\mid\tau\mid}}=\pm\left(0\,,{\frac{1}{\sqrt{2}}},{\frac{1}{\sqrt{2}}}\right).
$$  

在点 $P\left(0,-1,1\right)$ 处， $f_{x}^{\prime}\,{=}\,0\,,f_{y}^{\prime}\,{=}\,1,f_{z}^{\prime}\,{=}\,2$ ，从而得  

$$
{\frac{\partial f}{\partial\tau}}\biggr\rvert_{\scriptscriptstyle P}=\pm\left(0\times0+1\times{\frac{1}{\sqrt{2}}}+2\times{\frac{1}{\sqrt{2}}}\right)\!=\pm{\frac{3}{\sqrt{2}}}=\pm\,{\frac{3}{2}}\sqrt{2}.
$$  

例17.10已知函数 $z=f(\,x\,,y\,)$ 可微，其在点 $P_{\scriptscriptstyle0}\!\:(1,2)$ 处沿从 $\boldsymbol{P}_{\circ}$ 到 $P_{\scriptscriptstyle1}(2,3)$ 的方向的方向导数为 $2\,\sqrt{2}$ ，沿从 $\boldsymbol{P}_{\scriptscriptstyle0}$ 到 $P_{\mathrm{~}2}\left(1\right.$ ，0）的方向的方向导数为一3，则 $_z$ 在点 $\scriptstyle P_{\mathrm{~o~}}$ 处的最大方向导数为  

【解】应填 $\sqrt{10}$  

如图17-6所示 $,l_{1}=\overrightarrow{P_{\circ}P_{1}}=\left(1,1\right),l_{2}=\overrightarrow{P_{\circ}P_{\circ}}=\left(0\,,\,-\,2\right)$ ，且$l_{1}^{\circ}\!=\;(\cos\,\alpha_{1}\,,\cos\,\beta_{!}\,)=\;\left(\frac{1}{\sqrt{2}},\!\frac{1}{\sqrt{2}}\right),$ $\begin{array}{r}{~l_{\mathrm{\Lambda}^{2}}^{\circ}\!=~\!(\cos\alpha_{2}\,,\cos\beta_{2})=~(0\,,-1).}\end{array}$  

由方向导数计算公式，有$\left.\frac{\partial f}{\partial x}\,\right|_{r_{0}}\cdot\frac{1}{\sqrt{2}}+\frac{\partial f}{\partial y}\,\right|_{r_{0}}\cdot\frac{1}{\sqrt{2}}=\;2\sqrt{2}\;,$ $\left.\frac{\partial f}{\partial x}\,\right|_{r_{0}}\cdot\,0+\frac{\partial f}{\partial y}\,\right|_{r_{0}}\cdot\,\left(-\,1\right)=\,-\,3\,,$ 解得 $z_{x}^{\prime}(P_{0})=1,z_{y}^{\prime}(P_{0})=\,3$ ，故 $_z$ 在点 $\boldsymbol{P}_{0}$ 处的最大方向导数为  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/9ba91c83cf55a75f8ae548fc04175679b998955f2136f1b2b051c16e5d49d7b2.jpg)  
图17-6  
$$
\Bigl|\,{\bf g r a d}\,z\,\Bigr|_{\,_{P_{0}}}\,\Bigr|=\,\sqrt{\bigl[z_{\,x}^{\prime}\,(P_{0}\,)\bigr]^{2}+\bigl[z_{\,y}^{\prime}\,(P_{0}\,)\bigr]^{2}}=\,\sqrt{10}\,.
$$  

【注】本题的问题可作如下推广:设 $z=\ f(\boldsymbol{x}\,,\boldsymbol{y})$ 可微，记任意一点 $P_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0})$ ,从 $\scriptstyle P_{\circ}$ 出发,沿两条不共线的方向 $\pmb{l}_{1}^{\circ}\,{=}~(\cos\,\pmb{\alpha}_{1}\,,\cos\,\beta_{1}\,)$ 与 $l_{2}^{\circ}\,{=}\,\left(\cos\,\alpha_{2}\,,\cos\,\beta_{2}\right)$ ）的方向导数分别为  

$$
\begin{array}{l}{\displaystyle\left\{\frac{\partial f}{\partial l_{1}^{\circ}}\bigg|_{P_{0}}=\frac{\partial f}{\partial x}\bigg|_{P_{0}}\cdot\cos\alpha_{1}+\frac{\partial f}{\partial y}\bigg|_{P_{0}}\cdot\cos\beta_{1}\,,\right.}\\ {\displaystyle\left.\left|\frac{\partial f}{\partial l_{2}^{\circ}}\right|_{P_{0}}=\frac{\partial f}{\partial x}\bigg|_{P_{0}}\cdot\cos\alpha_{2}+\frac{\partial f}{\partial y}\bigg|_{P_{0}}\cdot\cos\beta_{2}\,,}\end{array}
$$  

$\left|\cos\alpha_{1}\right|\cos\beta_{1}\r\neq0,$  

(1) 若 $\left.\frac{\partial f}{\partial l_{1}^{\circ}}\right|_{P_{0}},\left.\frac{\partial f}{\partial l_{2}^{\circ}}\right|_{P_{0}}$ 不全为 0,则该非齐次方程组有唯一解,如例 17. 10 的解答过程。  

(2) 若 $\left.\frac{\partial f}{\partial l_{1}^{\circ}}\right|_{P_{0}}=\frac{\partial f}{\partial l_{2}^{\circ}}\right|_{P_{0}}=\ 0$ ,则该齐次方程组只有零解,即 $\left.\frac{\partial f}{\partial x}\right|_{P_{0}}=\frac{\partial f}{\partial y}\right|_{P_{0}}\;=\;0$ ，故 $\mathsf{d}f\,\big|\,{\boldsymbol{r}}_{\!\circ}\,=\,\frac{\partial f}{\partial x}\bigg|_{\,{\boldsymbol{P}}_{0}}\,\mathrm{d}x\,+\!\frac{\partial f}{\partial y}\bigg|_{\,{\boldsymbol{P}}_{0}}\,\mathrm{d}y=\,0.$ 電由 $\scriptstyle P_{\circ}$ 的任患性，有 $\mathsf{d}f=\,0$ ,故 $f(x\,,y)$ 为一常效  

设$\ F(x\,,y\,,z)=\,x y i-y z j+z x k$ ,则 $\mathrm{\bfrot}\;{\cal F}(\mathrm{\o{1}}\,,\mathrm{1}\,,0)=\mathrm{\underline{{~\underline{{~\bf~\\}~}~}}}$  

【解】应填 $\pmb{i}-\pmb{k}$ ：  

记三元向量函数 $\pmb{F}(\boldsymbol{x}\,,\boldsymbol{y}\,,z)=\,(P\,,Q\,,R\,)$ ，则  

$$
\mathrm{rot}\;F(x\,,y\,,z)=\;\left|\frac{i}{\partial x}\begin{array}{c c c}{{j}}&{{k}}\\ {{\partial}}&{{\partial}}&{{\partial}}\\ {{\partial}_{x}}&{{\partial}_{y}}&{{\partial}_{z}}\\ {{P}}&{{Q}}&{{R}}\end{array}\right|,
$$  

这里 $P=\,x y\,,Q=\,-\,y z\,,R=\,z x$ ，于是  

$$
\mathsf{r o t}\;F(1,1,0)=\;\left|\frac{i}{\partial x}\right.\quad\frac{j}{\partial y}\quad\frac{\partial}{\partial z}\left|\qquad}&{=\left.(y i-z j-x k)\,\right|_{(1,1,0)}=\left.i-k.
$$  
# 第18讲G多元函数积分学（仅数学一）  

# 知识结构  

适用场合计算方法适用场合计算方法概念 做功  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a27e2dd28c3c167042e04b50944943846f429ed950448b58d2f087c46c8d041e.jpg)  
基本方法一投二代三计算（化为定积分）  

第二型曲线积分  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/3f084b1a1b550e4870d5bf4222025fd0f636a9e45e58965bf3ddeda9fc8c1ad3.jpg)  

# 第二型曲面积分  

两类曲面积分的关系  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b49db165ab57f89fe9ebd490c5a626a309eb2e6d95aca8a377e395f402fd6137.jpg)  
# 三重积分  

# 1.概念与对称性  

# (1) 概念.  

（x，y,z）du$=\varlimsup_{n\rightarrow\infty}\sum_{i=1}^{n}\sum_{j=1}^{n}\sum_{k=1}^{n}g\left(a+\frac{b-a}{n}i\,,c+\frac{d-c}{n}j\,,e+\frac{f-e}{n}k\right)\cdot\frac{b-a}{n}\cdot\frac{d-c}{n}\cdot\frac{f-e}{n},$  

其中 $\Omega=\{\,(x\,,y\,,z)\;\,|\;\,a\leqslant x\leqslant b\,,c\leqslant y\leqslant d\,,e\leqslant z\leqslant f\}$  

例18.1 $\operatorname*{lim}_{n\to\infty}{\frac{\pi}{2n^{5}}}\sum_{i=1}^{n}\sum_{j\,=1}^{n}\sum_{k\,=\,1}^{n}i^{2}\sin{\frac{\pi j}{2n}}\cos{\frac{k}{n}}={\cfrac{\quad}{\cdot}}$  

【解】应填 ${\frac{1}{3}}\sin\,1$ $\begin{array}{r l}&{\displaystyle\operatorname*{lim}_{n\to\infty}\frac{\pi}{2n^{5}}\sum_{i=1}^{n}\sum_{j=1}^{n}\sum_{k=1}^{n}i^{2}\sin\frac{\pi j}{2n}\cos\frac{k}{n}=\frac{\pi}{2}\operatorname*{lim}_{n\to\infty}\sum_{i=1}^{n}\sum_{j=1}^{n}\sum_{k=1}^{n}\left(\frac{i}{n}\right)^{2}\sin\frac{\pi j}{2n}\cos\frac{k}{n}\cdot\frac{1}{n}\cdot\frac{1}{n}\cdot}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=\frac{\pi}{2}\bigg\lceil_{0}^{1}x^{2}\,\mathrm{d}x\bigg\lceil_{0}^{1}\sin\!\left(\frac{\pi}{2}y\right)\mathrm{d}y\bigg\rceil_{0}^{1}\cos\,z\,\mathrm{d}z}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=\frac{\pi}{2}\cdot\frac{1}{3}\cdot\frac{2}{\pi}\cdot\sin1=\frac{1}{3}\sin1.}\end{array}$ n  

# (2)对称性.  

分析方法与二重积分完全一样.  

#  $\textcircled{1}$ 普通对称性.  

假设 $\Omega$ 关于 $_{x O z}$ 面对称，则  

$$
\underset{a}{\iint}f(x\,,y\,,z)\,\mathrm{d}v=\left\{\!\!\!\begin{array}{l l}{2\iiint f(x\,,y\,,z)\mathrm{d}v\,,}&{f(x\,,y\,,z)=f(x\,,-\,y\,,z)\,,}\\ {\qquad\quad\,\,\,\,}\\ {0\,,}&{f(x\,,y\,,z)=-\,f(x\,,-\,y\,,z)\,,}\end{array}\right.
$$  

其中 $\Omega_{1}$ 是 $\Omega$ 在 $_{x O z}$ 面右边的部分.  

关于其他坐标面对称的情况与此类似.  

# $\circledcirc$ 轮换对称性.  

在直角坐标系下，若把 $_{x}$ 与 $_y$ 对调后， $\Omega$ 不变，则  

$$
\underset{0}{\iint}f(x\,,y\,,z)\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z=\underset{0}{\iiint}f(y\,,x\,,z)\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z\,,
$$  

这就是轮换对称性.关于其他情况与此类似.  

如$\begin{array}{l}{\itOmega=\ \{(x\,,y\,,z)\ \mid\ x^{\:2}\ +\ y^{\:2}\ +\ z^{2}\ \leqslant R^{2}\}}\end{array}$ ，则 $\iint_{\Omega}f(x)\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z\;=\;\iiint_{\Omega}f(y)\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z\;=$  $\iiint_{\Omega}f(z)\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z$ 可以化简计算.  
# 2.计算  

# （1）直角坐标系.  

$\textcircled{1}$ 先一后二法(先 $_z$ 后$_{x y}$ 法，也叫投影穿线法）.  

a.适用场合.  

$\Omega$ 有下曲面 $z=z_{1}(x\,,y)$ 、上曲面 $z=z_{2}(x\cdot y)$ ,无侧面或侧面为柱面，如图18-1所示.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/2f3e1c29ac3bb9947b592e6417c942270653c1875eca2493d9516b30c1a9d03a.jpg)  
图18-1  

b.计算方法.  

如图18-2所示,有 $\underset{a}{\iint}f(x\,,y\,,z\,)\,\mathrm{d}v=\underset{b_{\prime}}{\iint}\mathrm{d}\sigma{\int_{z_{1}(x\,,y)}^{z_{2}(x\,,y)}f(x\,,y\,,z\,)\,\mathrm{d}z}.$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/38d8c278434135a48a47e309c34df6b820945cbe05881d917375bf8a0a0865bf.jpg)  
图18-2  

$\circledcirc$ 先二后一法(先 $_{x y}$ 后 $_z$ 法，也叫定限截面法).  

a.适用场合.  

$\Omega$ 是旋转体，其旋转曲面方程为 $\Sigma:z=z\left(\boldsymbol{\mathscr{x}}\,,\boldsymbol{\mathscr{y}}\,\right)$ ，如图18-3所示，  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c09a87ca58d19930adaf4e5c2ebe2799ade6321eac1d5aa981b66eaa17f05b25.jpg)  
图18-3  
b.计算方法.  

如图18-4所示，有 $\iiint_{\Omega}f(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,)\,{\mathrm{d}}\boldsymbol{v}=\int_{\,a}^{b}{\mathrm{d}}z\!\!\\!\int_{\,b_{\,}}f(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,)\,{\mathrm{d}}\sigma.$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/94ee270e3fb7c1a3dab609b10a0de9aca00d0a2ccfd721a167b4075e45fbe3f0.jpg)  
图18-4  

# （2）柱面坐标系 $=$ 极坐标下二重积分与定积分.  

在直角坐标系的计算中，如若 $\iint\mathrm{d}\sigma$ 适用于极坐标系，则令 $\begin{array}{r}{\left\langle x=r\cos\,\theta\,,\right.}\\ {\left.y=r\sin\,\theta\,,\right.}\end{array}$ 便有$\iiint_{0}f(x\,,y\,,z\,)\,\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z=\iiint_{0}f(\,r\cos\,\theta\,,r\sin\,\theta\,,z\,)\,r\,\mathrm{d}r\,\mathrm{d}\theta\mathrm{d}z\,,$  

此种计算方法称为柱面坐标系下三重积分的计算.  

# （3）球面坐标系.  

$\textcircled{1}$ 适用场合.  

a.被积函数中含 $\begin{array}{c}{{\left\langle f(x^{2}+y^{2}+z^{2})\,,\right.}}\\ {{\left.f(x^{2}+y^{2}).\right.}}\end{array}$ 球或球的部分，  
b.积分区域为锥或锥的部分.  
 $\circledcirc$ 计算方法.  

$$
\begin{array}{r}{\left\{x=r\sin\,\varphi\cos\,\theta\,,\right.}\\ {\left.y=r\sin\,\varphi\sin\,\theta\,,\right.}\\ {\left.z=r\cos\,\varphi\,,\right.\,}\end{array}
$$  

则$\mathrm{d}v=r^{2}$ sin pd0dpdr.且  

先碰到 $\Omega$ ,记 $\theta_{1}$ ，a.过 $_z$ 轴的半平面与 $x O z$ 面正向夹角为 $\theta$ （取值范围[0,2π]）后离开 $\Omega$ ,记 $\boldsymbol{\theta}_{2}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/7bc275215c01958d7e35f2fbbc653db232283e06d8f6e9dde79dc350ce7db6b7.jpg)  
先碰到 $\Omega$ ，记 $\varphi_{1}(\theta)$ ，b.顶点在原点，以 $_z$ 轴为中心轴的圆锥面半顶角为 $\varphi$ （取值范围 $[0,\pi];$ 后离开 $\Omega$ ,记 $\varphi_{2}(\theta)$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/76c04957b1532e69a75e2194ff4e7b332a6c30913671b1e77115794909f92a0f.jpg)  

先碰到 $\Omega$ ，记 $r_{1}\,(\varphi,\theta)$ ，c.从原点出发画一条射线为 $_r$ （取值范围[0，十∞））后离开 $\Omega$ ，记 $r_{2}(\varphi,\theta)$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/df22f6151f47882c5df74991873f58cde8f49d8c738539db57f59e8871d8a938.jpg)  

# 于是  

$$
\begin{array}{r l}&{\displaystyle\iiint f(x\,,y\,,z)\,\mathrm{d}v=\iiint f(r\sin\,\varphi\cos\,\theta\,,r\sin\,\varphi\sin\,\theta,r\cos\,\varphi)\,r^{2}\sin\,\varphi\mathrm{d}r\,\mathrm{d}\varphi\mathrm{d}\theta}\\ &{\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad\quad=\displaystyle\int_{\theta_{1}}^{\theta_{2}}\mathrm{d}\theta\!\!\int_{\varphi_{1}(\theta)}^{\varphi_{2}(\theta)}\mathrm{d}\varphi\!\!\int_{r_{1}(\varphi,\theta)}^{r_{2}(\varphi,\theta)}f(r\sin\,\varphi\cos\,\theta,r\sin\,\varphi\sin\,\theta,r\cos\,\varphi)r^{2}\sin\,\varphi\mathrm{d}r.}\end{array}
$$  

【注】（1）关于积分区域 $\Omega$  

这是考试的难点所在,考生需将附录中的常见空间图形认真研究,多画多练,方能提高画图能力.  

(2)关于被积函数 $f(x,y,z)$  

由于积分区域 $\Omega$ 较复杂，因此被积函数一般较为简单，以利于题目的命制与求解，  

$$
\begin{array}{r l}&{\displaystyle\iiint f(x\,,y\,,z)\,{\mathrm{d}}x\,{\mathrm{d}}y\,{\mathrm{d}}z}\\ &{\displaystyle\frac{a_{x,v}}{a_{x,v}}}\\ &{\displaystyle\frac{x=x\,(u\,,v\,,w)}{z=z(u\,,v,w)}\,\sqrt[]{\int f\left[x\,(u\,,v\,,w)\,,y\,(u\,,v\,,w)\,,z\,(u\,,v\,,w)\,\right]\left|\frac{\partial(x\,,,y\,,z)}{\partial(u\,,,v\,,w)}\,\right|}\,{\mathrm{d}}u\,{\mathrm{d}}v\,{\mathrm{d}}^{\prime}}\\ &{\displaystyle\mathbb{D}\,\int f(x\,,y\,,z)\to f[x\,(u\,,v\,,w)\,,y\,(u\,,v\,,w)\,,z\,(u\,,v\,,w)\,],}\\ &{\displaystyle\mathbb{D}\,\prod_{a_{x,v}}\,\cdots\prod_{a_{x,w}}^{\prime}\,.}\end{array}
$$w.  
$$
\textcircled{3}\ \mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z\cdots\biggm\lvert\frac{\partial(x\,,y\,,z)}{\partial(u\,,v\,,w)}\biggm\rvert\mathrm{d}u\,\mathrm{d}v\,\mathrm{d}w.
$$  

其中  

$\displaystyle\left\{{\begin{array}{l}{x=x\left(u\,,v\,,w\right)}\\ {y=y\left(u\,,v\,,w\right)}\\ {z=z\left(u\,,v\,,w\right)}\end{array}}\right.$ ，a。,是空间 $(x,y,z)$ 到空间 $(\mathbf{\Omega}_{u},v\,,w)$ 的一一映射;  

b. ${\boldsymbol x}={\boldsymbol x}\left({\boldsymbol u},{\boldsymbol v},{\boldsymbol w}\right)$ ， $y=y\left(u\,,v\,,w\right),z=z\left(u\,,v\,,w\right)$ 有一阶连续偏导数,且  

$$
\frac{\partial(x\,,y\,,z)}{\partial(u\,,v\,,w)}=\left|\frac{\partial_{x}}{\partial u}\,\,\,\,\frac{\partial x}{\partial v}\,\,\,\,\frac{\partial x}{\partial w}\right|\neq0.
$$  

$$
\underset{a_{x y}}{\iint}f(x\,,y\,,z)\,{\mathrm{d}}x\,{\mathrm{d}}y\,{\mathrm{d}}z=\underset{a_{r\ell}}{\iint}f(r\cos\theta\,,r\sin\theta\,,z)\,\bigg|\,\frac{\partial(x\,,y\,,z)}{\partial(r\,,\theta\,,z)}\,\bigg|\,{\mathrm{d}}r\,{\mathrm{d}}\theta\,{\mathrm{d}}z
$$  

这就是直角坐标系到柱面坐标系的换元过程.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/6bfc9cf23618f75a80a0caf9878df9306843a13bb2d7c2b5afa4b5f2998749eb.jpg)  
- f(rsin pcos θ ,rsin p sin θ ,rcos g) 一38 /dr d0 dq sin p cos θ——rsin psin θ  rcos p cos θf(rsin pcos0 ,rsinp sinθ,rcosp)·sin psinθ  rsin pcosθ rcos @sin 0 drd0 dp 0r0g cos 0-rsin p f(rsin pcos 0 ,rsin psin ,rcos p )rsin pdrdodp.  

这就是直角坐标系到球面坐标系的换元过程。  

例18.2设 $\pmb{\Omega}$ 是由平面 $x+y+z=1$ 与三个坐标平面所围成的空间区域,则 $\iiint_{0}(x+2y+$ $3z\,)\,\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z=-$  

【解】应填 $\frac{1}{4}$  

法一积分区域如图18-5（a）所示.由轮换对称性知，  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/df93d45a645a7777f0ede6677543b68fca47652576fce11eed9c4f8c09fe2a7d.jpg)  
(a)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c5dae7497b596c2b6f786d55548b18b845ce102671f425b7c0081a2ba5c8f644.jpg)  
(b)   
图18-5  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/3c0a4047710d421463da6b26c698523e08f449c88fab64100c7192721337e4e0.jpg)  

则  

$$
\begin{array}{r}{I=\underset{a}{\iint}x\,\mathrm{d}v=\underset{a}{\iint}y\,\mathrm{d}v=\underset{a}{\iint}z\,\mathrm{d}v\,,\quad}\\ {I=\underset{a}{\iint}(x+2y+3z\,)\,\mathrm{d}v=6\underset{a}{\iint}z\,\mathrm{d}v.}\end{array}
$$  

记 $\Omega:0\leqslant z\leqslant1,(x\,,y\,)\in D(z\,)\,,D(z\,)$ 是过 $_z$ 轴上[0,1]中任一点 $_z$ 作垂直于 $_z$ 轴的平面愛截 $\Omega$ 所得平面区域[平移到 $_{x O y}$ 平面上,见图18-565),其而积为 $\frac{1}{2}(1-z)^{2}$ 、于是由先二后一法(定限截面法),得  

$$
\begin{array}{l}{\displaystyle\iint_{0}z\,\mathrm{d}v=\!\int_{0}^{1}z\,\mathrm{d}z\,\iint_{0}\mathrm{d}x\,\mathrm{d}y=\!\int_{0}^{1}\,\frac{1}{2}(1-z)^{2}\,z\,\mathrm{d}z}\\ {\displaystyle\qquad\qquad=\!\int_{0}^{1}\,\frac{1}{2}(z-2z^{2}+z^{3})\,\mathrm{d}z}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/847aadd4f9189154f3c999a5acd635d8cee2bf06ce859a564679b314f9ae8ba4.jpg)  
$$
=\!\frac{1}{2}\Big(\frac{1}{2}z^{2}-\frac{2}{3}z^{3}+\frac{1}{4}z^{4}\Big)\Bigm|_{0}^{1}=\frac{1}{24},
$$  

因此 $I=6\times{\frac{1}{24}}={\frac{1}{4}}$  

法二同法一,有 $I=6\iiint_{\vphantom{\nabla^{2}}^{\infty}}\!\!\!\!\mathrm{d}\boldsymbol{v}\,,$  

记 $\begin{array}{r}{\varOmega:0\leqslant z\leqslant1-x-y\,,(x\,,y)\in D_{x y}\,,D_{x y}=\{(x\,,y)\mid\,0\leqslant x\leqslant1,0\leqslant y\leqslant1-}\end{array}$ x)，如图18-5（c）所示.于是由先一后二法（投影穿线法）,得  

$$
\begin{array}{r l}{\lefteqn{\frac{\iint_{\boldsymbol{a}}\mathbf{\,d}\boldsymbol{v}}{a}=\sum_{p_{x_{y}}}\left(\int_{0}^{1-x-y}\boldsymbol{z}\,\mathrm{d}z\right)\,\mathrm{d}x\,\mathrm{d}y=\iint_{x_{y}}\frac{1}{2}(1-x-y)^{2}\,\mathrm{d}x\,\mathrm{d}y}}\\ &{=\frac{1}{2}\bigg\Updownarrow_{\boldsymbol{a}}^{1}\mathrm{d}x\bigg\Updownarrow_{\boldsymbol{a}}^{1-x}(1-x-y)^{2}\,\mathrm{d}y}\\ &{=\frac{1}{2}\bigg\Updownarrow_{\boldsymbol{a}}^{1}\bigg[-\frac{1}{3}(1-x-y)^{3}\bigg\rvert_{y=0}^{y-1-x}\bigg]\,\mathrm{d}x}\\ &{=\frac{1}{6}\bigg\Updownarrow_{\boldsymbol{a}}^{1}(1-x)^{3}\,\mathrm{d}x=\frac{1}{24},}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/12fbf75b35a3c128d9e89f12be6ece13e6dd2243146d5428faa4a9678a2a91d9.jpg)  

因此 $I=6\times{\frac{1}{24}}\,\mathrm{=}\,{\frac{1}{4}}$  

例18.3设 $\Omega$ 是由圆柱面 $x^{2}+(y-1)^{2}=1$ ,旋转抛物面 $8z=x^{2}+y^{2}$ 以及平面 $z=0$ 所围成的区域,则 $I=\iint_{a}{\sqrt{x^{\,2}+y^{\,2}}}\,\mathrm{d}v={}-$  

【解】应填 $\frac{64}{75}$  

如图18-6所示，用先一后二法（投影穿线法），即  

$$
\begin{array}{r l}&{I=\!\!\!\displaystyle\iint\!\mathrm{d}\sigma\!\!\int_{0}^{\frac{x^{2}+y^{2}}{8}}\sqrt{x^{2}+y^{2}}\,\mathrm{d}z}\\ &{\quad\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! 
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/647585cc0cc40b04131e4a5640210dede936910dabc3a562e35a8ccfc6645107.jpg)  
图18-6  

例18.4计算 $I=\!\!\!\!\prod_{a}^{\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\$ ,其中 $\Omega:\sqrt{x^{2}+y^{2}}\leqslant z\leqslant1$  

【解】如图18-7所示，积分区域 $\Omega$ 被球面 $x^{2}+y^{2}+z^{2}=1$ 剖分成上下两部分，分别记为 $\Omega_{1}\,,\Omega_{2}$ ，故  

$$
\begin{array}{l}{I=\iint_{0}^{\infty}(1-\sqrt{x^{2}+y^{2}+z^{2}})\,\mathrm{d}x\mathrm{d}y\,\mathrm{d}z\,+}\\ {\displaystyle\iint_{0}^{\infty}(\sqrt{x^{2}+y^{2}+z^{2}}-1)\,\mathrm{d}x\mathrm{d}y\,\mathrm{d}z\,\frac{\mathrm{i}\Xi\mathcal{H}}{-}\,I_{1}+I_{2}.}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b653049072609451189d46ec173245870729162ee28d01dab559eb82b9bdc3da.jpg)  
图18-7  
对于 $I_{\mathrm{~l~}}$ 和 $I_{z}$ 均采用球面坐标计算，有  

$$
\begin{array}{l}{{I_{1}=\displaystyle\int_{0}^{2\pi}\!\mathrm{d}\theta\displaystyle\int_{0}^{\frac{\pi}{4}}\mathrm{d}\varphi\displaystyle\int_{0}^{1}(1-r)\,r^{2}\sin\,\varphi\mathrm{d}r\ }}\\ {{\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ }}\\ {{\ \ \ \ \ \ \ =2\pi\displaystyle\int_{0}^{\frac{\pi}{4}}\sin\,\varphi\mathrm{d}\varphi\displaystyle\int_{0}^{1}(1-r)\,r^{2}\,\mathrm{d}r=\frac{\pi}{12}(2-\sqrt{2}\,)\,,}}\end{array}
$$  

$$
\begin{array}{r l}&{I_{\mathit{z}}=\displaystyle\int_{0}^{2\pi}\!\mathrm{d}\theta\displaystyle\int_{0}^{\frac{\pi}{4}}\!\mathrm{d}\varphi\displaystyle\int_{1}^{\frac{1}{\cos{\varphi}}}\!(r-1)r^{2}\sin{\varphi}\mathrm{d}r}\\ &{\quad=2\pi\displaystyle\int_{0}^{\frac{\pi}{4}}\sin{\varphi}\mathrm{d}\varphi\displaystyle\int_{1}^{\frac{1}{\cos{\varphi}}}(r-1)r^{2}\,\mathrm{d}r}\\ &{\quad=2\pi\displaystyle\int_{0}^{\frac{\pi}{4}}\!\left(\frac{1}{4\cos^{4}{\varphi}}-\frac{1}{3\cos^{3}{\varphi}}+\frac{1}{12}\right)\sin{\varphi}\mathrm{d}\varphi=\frac{\pi}{12}(3\sqrt{2}-4).}\end{array}
$$  

因田此 $I=I_{1}+I_{2}=\frac{\pi}{12}(2-\sqrt{2}\,)+\frac{\pi}{12}(3\sqrt{2}-4)=\frac{\pi}{6}(\sqrt{2}-1).$  

例18.5设 $\boldsymbol{\Sigma}$ 为任意闭曲面，  

$$
I=\underset{{\Sigma_{\#}},\ldots}{\iint}\left(x-\frac{1}{3}x^{3}\right)\mathrm{d}y\,\mathrm{d}z-\frac{4}{3}y^{3}\mathrm{d}z\,\mathrm{d}x+\left(3y-\frac{1}{3}z^{3}\right)\mathrm{d}x\,\mathrm{d}y.
$$  

（1）证明 $\pmb{\Sigma}$ 为椭球面 $x^{2}+4y^{2}+z^{2}=1$ 时， $I$ 达到最大值；  

（2）求 $I$ 的最大值.  

（1)【证】根据高斯公式， $I=\!\!\!\!\prod_{a}^{\prime}(1-x^{2}-4y^{2}-z^{2}\,)\,\mathrm{d}x\mathrm{d}y\,\mathrm{d}z$ ,其中 $\Omega$ 为 $\boldsymbol{\Sigma}$ 所围的空间区域.为使 $I$ 最大,要求 $\Omega$ 是使得 $1-x^{2}-4y^{2}-z^{2}\geqslant0$ 的最大空间区域,即  

$$
\mathcal{\Omega}=\{(x\mathbin{,}y\,,z\,)\ |\ 1-x^{2}-4y^{2}-z^{2}\geqslant0\}
$$  

$\boldsymbol{\Sigma}$ 为 $\Omega$ 的表面,即为椭球面 $x^{2}+4y^{2}+z^{2}=1$ 时， $I$ 最大.  

(2)【解】令  

$$
\begin{array}{l}{{\displaystyle{\Biggl\{}x=r\sin\varphi\cos\,\theta\,,}}}\\ {{\displaystyle{\Biggl\{}y=\frac{1}{2}r\sin\varphi\sin\,\theta\,,}}}\\ {{\displaystyle{\Biggl\{}z=r\cos\,\varphi\,,}}}\end{array}
$$  

于是  

$$
\begin{array}{r}{J=\!\frac{\partial(x\,,\ y\,,z)}{\partial(r\,,\theta\,,\varphi)}\!=\!\left|\frac{\partial x}{\partial r}\right.\quad\!\frac{\partial x}{\partial\theta}\quad\!\frac{\partial x}{\partial\varphi}\!\right|=\!\frac{1}{2}r^{2}\sin\varphi\,,}\\ {\left|\frac{\partial z}{\partial r}\quad\!\frac{\partial z}{\partial\theta}\quad\!\frac{\partial z}{\partial\varphi}\right|=\!\frac{1}{2}r^{2}\sin\varphi\,,}\end{array}
$$  

则  

$$
\begin{array}{r}{I_{\mathrm{\,max}}=\iiint\quad(1-x^{\,2}-4y^{\,2}-z^{\,2}\,)\,\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z}\\ {=\displaystyle\int_{0}^{2\pi}\!\mathrm{d}\theta\!\int_{0}^{\pi}\!\mathrm{d}\varphi\!\int_{0}^{1}(1-r^{\,2})\,\,\frac{1}{2}r^{\,2}\sin\varphi\,\mathrm{d}r=\frac{4\pi}{15}.}\end{array}
$$  
# 第一型曲线积分  

# 1.概念与对称性  

# (1)概念.  

第一型曲线积分的被积函数 $f(x\,,y\,)$ （或 $f(x,y,z))$ 定义在平面曲线 $L$ (或空间曲线 $\boldsymbol{r}$ 上.其物理背景是以 $f(x\,,y\,)$ (或 $f(x\,,y\,,z\,))$ 为线密度的平面（或空间）物质曲杆的质量.与前面类似,我们仍然可以用“分割、近似、求和、取极限”的方法与步骤写出第一型曲线积分  

$$
\int_{L}f(x\,,y\,)\,\mathrm{d}s\,(\,{\overrightarrow{\mathfrak{p}}}{\overrightarrow{\mathsf{X}}}\!\!\!\int_{r}f(x\,,y\,,z\,)\,\mathrm{d}s\,).
$$  

但事实上,如果仅理解到此,还是不够的.不妨把定积分和第一型曲线积分放在一起做个对比,加深我们对概念的理解.定积分定义在“直线段”上,而第一型曲线积分定义在“曲线段”上，如图18-8、图18-9所示,由于 $f(x\,,y\,)$ 定义在 $L:y=y\left(x\right)$ 上，故边界方程 $L$ 可代人被积函数，从而化简计算。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/7f7e1260cbf8707ee52a3071d9c780b16f593c954c8600001045a5f522f129c8.jpg)  
图18-8  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/84c0f0441756e18e9612140967ca563e213f8bb17f11efda93c0938030cf1bfe.jpg)  
图18-9  

# (2)对称性.  

分析方法与二重积分、三重积分完全一样.  

#  $\textcircled{1}$ 普通对称性.  

假设 $\boldsymbol{\Gamma}$ 关于 $_{x O z}$ 面对称，则  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/c8bf6a3f2650eb93cff0aa9470b29aa57840dc688f8531db0b5c66123cd482eb.jpg)  

$$
\int_{r}f(x\,,y\,,z\,)\,{\mathrm{d}}s=\left\{\!\!\!\begin{array}{l l}{{2\displaystyle\int_{r_{1}}f(x\,,y\,,z\,){\mathrm{d}}s\,,}}&{{f(x\,,y\,,z\,)=f(x\,,-\,y\,,z\,)\,,}}\\ {{\:}}&{{f(x\,,y\,,z\,)=-\,f(x\,,-\,y\,,z\,)\,,}}\end{array}\ \right.
$$  

其中 $\boldsymbol{{\Gamma}}_{1}$ 是 $\boldsymbol{\Gamma}$ 在 $x O z$ 面右边的部分.  

关于其他坐标面对称的情况与此类似.  

# $\circledcirc$ 轮换对称性.  

若把 $\boldsymbol{x}$ 与 $_y$ 对调后， $\boldsymbol{\Gamma}$ 不变，则 $\int_{\cal P}f(x\,,\!y\,,\!z\,)\,\mathrm{d}s=\!\int_{\cal P}f(y\,,\!x\,,\!z\,)\,\mathrm{d}s$ ，这就是轮换对称性.  

关于其他情况与此类似.  
# 2.计算  

由于第一型曲线积分就是由定积分推广而来的，因此计算第一型曲线积分的基本方法就是将其化为定积分.口诀为“一投二代三计算”  

(1) 空间情形.  

$\rho_{x}=\!x(t)$ ，若空间曲线 $\boldsymbol{r}$ 由参数式<=y(t)， $(\alpha\leqslant t\leqslant\beta)$ ）给出，则(2=x(t)  

$$
\begin{array}{r}{\mathrm{d}s=\sqrt{\big[{\boldsymbol x}^{\prime}(t)\big]^{2}+\big[{\boldsymbol y}^{\prime}(t)\big]^{2}+\big[{\boldsymbol z}^{\prime}(t)\big]^{2}}\,\mathrm{d}t\,,}\end{array}
$$  

且  

$$
-i\Tilde{\beta}\underset{a^{\prime}\int\int\left[x\left(t\right),y\left(t\right),z\left(t\right)\right]\sqrt{\left[x^{\prime}\left(t\right)\right]^{2}+\left[y^{\prime}\left(t\right)\right]^{2}+\left[z^{\prime}\left(t\right)\right]^{2}}}{\left[\stackrel{-\left\langle t\right\rangle}{=}\right]^{2}}{\frac{\mathrm{d}}{\mathrm{d}t}}i\pi.
$$  

$\textcircled{1}$ 若平面曲线 $L$ 由$y=y\left(x\right)\left(a\leqslant x\leqslant b\right)$ ）给出，则 $\mathrm{d}s={\sqrt{1+\left[y^{\prime}(x)\right]^{2}}}\,\mathrm{d}x$ ，且  

$$
\begin{array}{r l r}{\lefteqn{\int_{L}\!\!\!\frac{f(x\,,y\,)\,\mathrm{d}s}{\lefteqn{\int_{a}^{b}\!\!f\big[x\,,y\,(x\,)\big]\,\sqrt{1+\big[y^{'}(x\,)\big]^{2}}\,\mathrm{d}x}}}}\\ &{}&{=\!\!\!\int_{a}^{b}\!\!\!f\big[x\,,y(x\,)\big]\,\sqrt{1+\big[y^{'}(x\,)\big]^{2}}\,\mathrm{d}x.}\end{array}
$$  

$\circledcirc$ 若平面曲线 $L$ 由参数式 $\begin{array}{r}{\left\{x=x\left(t\right),\right.}\\ {\left.\left|y=y\left(t\right)\right.\right.}\end{array}$ 给出,则 $\mathrm{d}s={\sqrt{\left[x^{\prime}(t)\right]^{2}+\left[y^{\prime}(t)\right]^{2}}}\,\mathrm{d}t$ ，  

$$
\begin{array}{r l r}{\lefteqn{\int_{L}\!\!\!\frac{f(x,y)\,\mathrm{d}s}{\sqrt{\int_{a}^{\beta}}f\left[x\left(t\right),y\left(t\right)\right]\,\sqrt{\left[x^{'}(t)\right]^{2}+\left[y^{'}(t)\right]^{2}}\,\mathrm{d}t.}}}\end{array}
$$  

$\circled{3}$ 若平面曲线 $L$ 由极坐标形式 $r=r(\theta)(\alpha\leqslant\theta\leqslant\beta)$ 给出,则 $\mathbf{d}s={\sqrt{[r(\theta)]^{2}+[r^{\prime}(\theta)]^{2}}}\,\mathbf{d}\theta$ ，且  

$$
\begin{array}{r l r}{\lefteqn{\int_{L}\!\!\!f(x\,,y)\mathrm{d}s\!\!\!\!\!}}&{{}\geq\!i\!\!\!\!+\!\!\!\frac{s}{\!\!\!\!\!}}&{}\\ {\lefteqn{=\!\!\!\!\!\int_{s}^{\beta}\!\!\!\!f\big[r(\theta)\cos\theta\,,r(\theta)\sin\theta\big]\,\sqrt{\big[r(\theta)\big]^{2}+\big[r^{\prime}(\theta)\big]^{2}}\,\mathrm{d}\theta.}}\end{array}
$$  

例18.6  

设 $\pmb{T}$ 是空间圆周 $\begin{array}{l}{{\left\langle x^{\,2}+y^{\,2}+z^{\,2}=1\right.}}\\ {{\left.\vphantom{\left(x^{\,2}+y^{\,2}+z^{\,2}\right)}\left\langle x+y^{\,2}+z=0\,\right.\right.}}\end{array}$ 则中 $\mathbf{\Sigma}_{r}(x^{2}+y^{2})\mathop{\mathbf{d}s}=\underline{{\mathbf{\tilde{\Pi}}}}$  

【解】应填 $\frac{4}{3}\pi$  

由轮换对称性知 $\oint_{r}x^{\,2}\,\mathbf{d}s=\oint_{r}y^{\,2}\,\mathbf{d}s=\oint_{r}z^{\,2}\,\mathbf{d}s$ ,于是  
$$
\begin{array}{r l}&{\quad\displaystyle\oint_{r}(x^{\:2}+y^{\:2})\,\mathrm{d}s=\!\!\oint_{r}x^{\:2}\,\mathrm{d}s+\!\!\oint_{r}y^{\:2}\,\mathrm{d}s}\\ &{=2\displaystyle\oint_{r}x^{\:2}\,\mathrm{d}s=\frac{2}{3}\left(\!\oint_{r}x^{\:2}\,\mathrm{d}s+\!\oint_{r}y^{\:2}\,\mathrm{d}s+\!\oint_{r}z^{\:2}\,\mathrm{d}s\,\right)}\\ &{=\frac{2}{3}\displaystyle\oint_{r}(x^{\:2}+y^{\:2}+z^{\:2})\,\mathrm{d}s\,\frac{\:(\mathbf{\nabla}\cdot\mathbf{\nabla})}{3}\frac{2}{3}\oint_{r}1\,\mathrm{d}s=\frac{2}{3}\times2\pi\times1\,\!=\!\frac{4}{3}\pi.}\end{array}
$$  

【注 $1(\star)$ 处来自边界方程 $x^{2}+y^{2}+z^{2}=1$ ,可直接代入被积函数,从而化简计算,  

例18.7 设$\boldsymbol{\Gamma}$ 是空间圆周 $\begin{array}{l}{\displaystyle{x^{\,2}+y^{\,2}+z^{\,2}=a^{\,2}}}\\ {\displaystyle{x+y+z=\frac{3}{2}a\,,}}\end{array}$ 则(2yx+2xx +2xy)ds =  

【解】应填 $\frac{5}{4}\pi a^{3}$  

如图18-10所示，球心（0,0,0）到平面 $x+y+z=\frac{3a}{2}$ 的距离为  

$$
d={\frac{\bigg|0+0+0-{\frac{3a}{2}}\bigg|}{\sqrt{1^{2}+1^{2}+1^{2}}}}={\frac{\sqrt{3}}{2}}a\,.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/9192aaa0ec29a96d67b29a62accd8f821014ac1909f2f438e032dfdd4096d526.jpg)  
图18-10  

圆$\boldsymbol{\Gamma}$ $\displaystyle{\int_{\lfloor x+y+z={\frac{3}{2}}a}^{x^{2}+y^{2}+z^{2}={\mathit{a}}^{2}}}$ $r={\sqrt{a^{2}-\left({\frac{{\sqrt{3}}\,a}{2}}\right)^{2}}}={\frac{a}{2}}$ ，圆 $\boldsymbol{\Gamma}$ 的周长为 $2\pi r=\pi a$ ,于是 $\begin{array}{r l}&{~~~~\oint_{r}(2y z+2z x+2x y)\mathrm{d}s}\\ &{=\!\!\!\oint_{r}\!\left[(x+y+z)^{2}-(x^{2}+y^{2}+z^{2})\right]\!\mathrm{d}s}\\ &{\overset{(\ast)}{=}\!\!\oint_{r}\left[\left(\frac{3a}{2}\right)^{2}-a^{2}\right]\mathrm{d}s=\!\frac{5a^{2}}{4}\!\!\oint_{r}\!1\mathrm{d}s=\!\frac{5}{4}a^{2}\cdot\pi a=\!\frac{5}{4}\pi a^{3}.}\end{array}$  

【注 $1(\ast)$ 处来自边界方程 $x+y+z=\frac{3}{2}a\,,x^{2}+y^{2}+z^{2}=a^{2}$ ,可直接代入被积函数,从而化简计算.  

例18.8设 $L:x^{2}+y^{2}=-2y$ ,则 $I=\oint_{L}{\sqrt{x^{2}+y^{2}}}\,\mathrm{d}s=}-$  

【解】应填 8.  

本题不宜用直角坐标直接计算.  

将曲线方程用极坐标表示： $r=-\,2\sin\,\theta\,(-\,\pi\leqslant\theta\leqslant0)$ ，则$x=r\cos\,\theta\,,y=r\sin\,\theta\,,\mathrm{d}s=\sqrt{\left[r\,(\theta\,)\right]^{2}+\left[r^{\prime}(\theta\,)\right]^{2}}\,\mathrm{d}\theta=2\mathrm{d}\theta.$  

故  

$$
I=\!\!\int_{-{\pi}}^{0}(-\,2\sin\,\theta\,)\,\cdot\,2{\mathsf{d}}\theta=-\,4\!\int_{-{\pi}}^{0}\!\sin\,\theta\,{\mathsf{d}}\theta=8.
$$  
# 第一型曲面积分  

# 1.概念与对称性  

# (1) 概念.  

第一型曲面积分的被积函数 $f(x\,,y\,,z)$ 定义在空间曲面 $\pmb{\Sigma}$ 上，其物理背景是以 $f(x\,,y\,,z)$ 为面密度的空间物质曲面的质量.与前面类似，我们可以用“分割、近似、求和、取极限”的方法与步骤写出第一型曲面积分  

$$
\iint_{\Sigma}f(x\,,y\,,z\,)\,\mathrm{d}S.
$$  

如前所述，仅理解到此是不够的,不妨把二重积分和第一型曲面积分放在一起做个对比,加深我们对概念的理解。  

二重积分定义在“二维平面”上，而第一型曲面积分则定义在“空间曲面”上，如图18-11、图18-12所示。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e8a6c670ba95474d8b7b7b72ab15ce23768daa3f37e73bc847911e54b6aaa8a9.jpg)  
图18-11  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/eda7ce39338476309327150cfda76ca92135bf0795eb6acaf039bdcd39b35b71.jpg)  
三维曲面域图18-12  

由于 $f(x\,,y\,,z\,)$ 定义在 $\Sigma$ ： $z=z\left(x\,,y\,\right)$ 上,故边界方程 $\boldsymbol{\Sigma}$ 可代人 $f(x\,,y\,,z\,)$ ,从而化简计算.  

(2)对称性.  

分析方法与二重积分、三重积分和第一型曲线积分完全一样.  

#  $\textcircled{1}$ 普通对称性.  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/480779ac336e6e9ff4ab465f517ce3c71438faebfcef220f8568e99717b1c1df.jpg)  

假设 $\boldsymbol{\Sigma}$ 关于 $_{x O z}$ 面对称，则  

$$
\iint_{\mathbb{Z}}f(x\,,y\,,z)\,\mathrm{d}S=\left\{\!\!\!\begin{array}{l l}{2\!\!\!\iint_{f}f(x\,,y\,,z)\,\mathrm{d}S\,,}&{\ f(x\,,y\,,z)=f(x\,,-\,y\,,z)\,,}\\ {\overline{{\Sigma}}_{1}}&{}\\ {0\,,}&{\ f(x\,,y\,,z)=-\,f(x\,,-\,y\,,z)\,,}\end{array}\right.
$$  

其中 $\Sigma_{1}$ 是 $\boldsymbol{\Sigma}$ 在 $_{x O z}$ 面右边的部分.  

关于其他坐标面对称的情况与此类似.  

# $\circledcirc$ 轮换对称性.  

当 $\Sigma\!:\!z=z(x\,,\!y\,)$ 为单值函数时,若把 $_{x}$ 与 $_y$ 对调后， $\scriptstyle{\frac{1}{2}}$ 不变,则 $\underset{\Sigma}{\iint}f(x,y,z)\mathrm{d}S=\underset{z}{\iint}f(y,x,z)\mathrm{d}S\,,$  

# 这就是轮换对称性  

关于其他情况与此类似.  
# 2.计算  

由于第一型曲面积分就是由二重积分推广而来的,因此计算第一型曲面积分的基本方法就是将其化为二重积分.口诀为“一投二代三计算”  

无论空间曲面 $\pmb{\Sigma}$ 是由显式方程 $z=z\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ 还是隐式方程 $F(x\,,y\,,z)\!=\!0$ 给出的，我们都需要做三件事(无逻辑上的先后顺序,哪件事情最利于解题就先做哪件)：  

$\textcircled{1}$ 一投：将 $\pmb{\Sigma}$ 投影到某一平面（比如 $_{x O y}$ 面)上 $\Rightarrow$ 投影区域为 $D$ （比如 $D_{x y}$  

$\circledcirc$ 二代：将 $\boldsymbol{z}=\boldsymbol{z}\left(\boldsymbol{\mathscr{x}}\,,\boldsymbol{y}\right)$ 或 $F(x\,,y\,,z)=0$ 代人 $f(x\,,y\,,z\,)$  $\textcircled{3}$ 三计算：计算 $z_{\textrm{x}}^{\prime},z_{\textrm{y}}^{\prime}$ ,得 $\mathrm{d}S=\sqrt{1+(z_{\it x}^{\prime})^{2}+(z_{\it y}^{\prime})^{2}}\,\mathrm{d}x\mathrm{d}y.$  

这就把第一型曲面积分化成二重积分（如化成关于 $x\cdot y$ 的二重积分），得到  

$$
\begin{array}{r l}&{\underset{\Sigma}{\iint}\underset{\Sigma}{\underbrace{f(x,y,z)\mathrm{d}S}}\;\frac{\mathrm{d}S}{\mathrm{d}t}}\\ &{=\underset{D_{x y}}{\iint}f\big[x,y,z(x,y)\big]\,\sqrt{1+(z_{x}^{\prime})^{2}+(z_{y}^{\prime})^{2}}\,\mathrm{d}x\,\mathrm{d}y.}\end{array}
$$  

化成关于其他变量的二重积分与此类似.  

（注】常和代数与几何垂直关系、投影、旋转、距离、切平面、轨迹等结合出题.  

例 18. 9设曲面 $\,\,\Sigma\colon\mid x\mid+\mid y\mid+\mid z\mid=1$ ，则 $\oiint_{\Sigma}(\boldsymbol{x}+|\boldsymbol{y}\rvert\,)\,\mathrm{d}S=_{-}$  

【解】应填 ${\frac{4}{3}}{\sqrt{3}}$  

曲面 $\pmb{\Sigma}$ 对称于 $^{y O z}$ 平面， $_{x}$ 为关于 $_{x}$ 的奇函数,所以 $\oint_{\Sigma}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\Sigma}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\$ 又因 $\pmb{\Sigma}$ 关于 $x,y,z$ 轮换对称，所以  

$$
\oiint_{\Sigma}\mid y\mid\ d S=\oiint_{\Sigma}\mid z\mid\ d S=\oiint_{\Sigma}\mid x\mid\ d S\,,
$$  

$$
\begin{array}{r l}&{\oiint\mid y\mid\ d S=\frac{1}{3}\oiint\left(\mid x\mid+\mid y\mid+\mid z\mid\right)\mathrm{d}S=\frac{1}{3}\oiint\mathrm{d}S}\\ &{\quad\quad\quad\quad\quad=\frac{1}{3}\times A_{z}\,,}\end{array}
$$  

其中 $A_{z}$ 为 $\pmb{\Sigma}$ 的面积.而 $\pmb{\Sigma}$ 为8块同样的等边三角形,每块等边三角形的边长为 $\sqrt{2}$ ,所以  

$$
A_{z}=8\times\frac{1}{2}\times(\sqrt{2}\,)^{2}\times\sin\frac{\pi}{3}=4\sqrt{3}\,,
$$  

所以 $\bigoplus_{z}\mid y\mid\mathrm{d}S={\frac{4}{3}}{\sqrt{3}}$ ,从而原式 $={\frac{4}{3}}{\sqrt{3}}$  

例 18. 10求 $I=\iint_{\Sigma}z\,\mathrm{d}S$ ,其中 $\pmb{\Sigma}$ 为柱面 $\ x^{2}+y^{2}=R^{2}$ 被 $\scriptstyle x\;=\;0\,,y\;=\;0\,,z\;=\;0$ 及 $\relax z=\!1$ 所截的第一卦限部分，如图18-13所示.  
[解 $^{1}$ 选择向 $_{x O z}$ 面投影，由曲面方程得  

$$
y=\sqrt{R^{2}-x^{2}}\,,
$$  

$$
\begin{array}{r l}&{\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\mathrm{d}S=\sqrt{1+(y_{\,\,\,x}^{\prime})^{2}+(y_{\,\,\,\varepsilon}^{\prime})^{2}}\,\mathrm{d}x\,\mathrm{d}z}\\ &{\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!=\sqrt{1+\left(\frac{-2x}{2\,\sqrt{R^{2}-x^{2}}}\right)^{2}+0^{2}}\,\mathrm{d}x\mathrm{d}z}\\ &{\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\!\!\,\!\!\!\,\!\!\!\!\!\!\!\!\!\!\!\! 
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/14fb496b358f346c4b4371ac464dffbaf11970b7941b65b62adea7240a1e6fcd.jpg)  
图18-13  

故 $I=\!\!\!\int_{\frac{z}{z}}\!\mathrm{d}S=\!\!\!\int_{{D_{x}}}{\frac{R z}{\sqrt{R^{2}-x^{2}}}}\mathrm{d}x\mathrm{d}z$ ,其中 $D_{\mathit{x z}}=\{\,(x\,,z\,)\,\mid\,0\leqslant x\leqslant R\,,0\leqslant z\leqslant1\,\}$ ，即  

$$
I=\!\!\!\int_{\frac{z}{z}}\!\!\!\!\!\int z\,\mathrm{d}S=\!\!\!\!\int_{0}^{R}\mathrm{d}x\!\!\int_{0}^{1}\frac{z}{\sqrt{R^{2}-x^{2}}}\mathrm{d}z=\frac{\pi}{4}R.
$$  

【注】（1)由于 $\pmb{\Sigma}$ 在 $_{x O y}$ 面上的投影仅为一条曲线,若选择向 $_{x O y}$ 面投影,则投影区域的面积为 0,于是 $I=\iint_{\frac{\pi}{2}}\mathrm{d}S=0,$ .这是错误的,因为投影点不能重合.  

(2) 以下常考:  

柱面 $x^{2}+y^{2}=a^{2}$ 的 $\mathrm{d}S={\frac{a}{\sqrt{a^{2}-x^{2}}}}\mathrm{d}x\mathrm{d}z$ 球面 $x^{2}+y^{2}+z^{2}=a^{2}$ 的 $\mathrm{d}S={\frac{a}{\sqrt{a^{2}-x^{2}-y^{2}}}}\mathrm{d}x\mathrm{d}y$ 锥面 $z=\sqrt{x^{2}+y^{2}}$ 的 $\mathrm{d}S=\!\sqrt{2}\,\mathrm{d}x\,\mathrm{d}y$  

例18.11设 $P$ 为椭球面 $S:x^{2}+y^{2}+z^{2}-y z=1$ 上的动点，若 $S$ 在点 $P$ 处的切平面与 $_{x}O y$ 而垂直,求点 $P$ 的轨迹 $C.$ 并计算曲面积分 $I\!=\!\!\!\iint_{\frac{}{2}}\!\frac{(x+\!\sqrt{3}\,)\mid y-2z\mid}{\sqrt{4+y^{2}+z^{2}-4y\,z}}\mathrm{d}S$ 其中 $\boldsymbol{\Sigma}$ 是怖球面 $S$ 位于曲线 $C$ 上方的部分.  

【解】设点 $P$ 的坐标为 $(x,y,z)$ ,椭球面 $S:x^{2}+y^{2}+z^{2}-y z=1$ 在点 $P$ 处的法向量是 $\pmb{n}=(2x\:,2y-z\:,2z-y\:)$ ，  

$_{x O y}$ 面的法向量是 $\pmb{k}=(0,0,1)$  

$s$ 在点 $P$ 处的切平面与 $_{x O y}$ 面垂直的充分必要条件是  

$$
\begin{array}{r}{n\cdot k=2z-y=0.}\end{array}
$$  

所以点 $P$ 的轨迹 $C$ 的方程为  

即  

$$
\begin{array}{r l}&{2z-y=0\,,}\\ &{x^{\,2}+y^{\,2}+z^{\,2}-y z=1\,,}\\ &{\qquad\int\!\!2z-y=0\,,}\\ &{\qquad\left\lbrace x^{\,2}+\frac{3}{4}y^{\,2}=1.\right.}\end{array}
$$  
# 比宁高等数学18讲  

取 $D=\left\{(x\,,y\,)\left|\,x^{\,2}+{\frac{3}{4}}y^{\,2}\leqslant1\right.\right\}$ ，记曲面 $\Sigma$ 的方程为 $z=z\left(x\,,y\,\right),(x\,,y\,)\,\in\,D$  

由于  

$$
\sqrt{1+\left(\frac{\partial\,z}{\partial\,x}\right)^{2}+\left(\frac{\partial\,z}{\partial\,y}\right)^{2}}=\sqrt{1+\left(\frac{2\,x}{y\,-\,2z}\right)^{2}+\left(\frac{2\,y\,-\,z}{y\,-\,2z}\right)^{2}}=\frac{\sqrt{4+y^{2}+z^{2}-4\,y z}}{\mid y-2z\mid}\,,
$$  

因此  

$$
I=\!\!\!\int_{0}\frac{(x+\sqrt{3})\mid y-2z\mid}{\sqrt{4+y^{2}+z^{2}-4y z}}\cdot\frac{\sqrt{4+y^{2}+z^{2}-4y z}}{\mid y-2z\mid}\!\!\,\mathrm{d}x\,\mathrm{d}y=\!\!\!\int_{D}(x+\sqrt{3}\,)\!\!\,\mathrm{d}x\,\mathrm{d}y.
$$  

又因为 $\iint_{D}x\mathrm{d}x\mathrm{d}y=0\,,\!\!\!\iint_{D}{\sqrt{3}}\,\mathrm{d}x\mathrm{d}y=2\pi$ ，所以  

$$
I=\iint_{D}(x+\sqrt{3}\,)\,\mathrm{d}x\,\mathrm{d}y=2\pi.
$$  

# 四第二型曲线积分  

# 1.概念 做功  

第二型曲线积分的被积函数 $\pmb{F}(x\,,\!y\,)=P(x\,,\!y\,)\pmb{i}\,+\pmb{Q}(x\,,\!y\,)\,\pmb{j}$ （或 $\pmb{F}(x\,,\!y\,,\!z\,)=P(x\,,\!y\,,\!z\,)\,\!i+$  $Q(x\,,y\,,z)\,j+R\,(x\,,y\,,z\,)\,k\,)$ 定义在平面有向曲线 $L$ （或空间有向曲线 $\boldsymbol{\Gamma}$ ）上，其物理背景是变力 $\pmb{F}(x\cdot y)$ （或 $\scriptstyle{\cal{F}}(x\,,y\,,z\,))$ 在平面曲线 $L$ （或空间曲线 $\boldsymbol{\Gamma}$ ）上从起点移动到终点所做的总功：  

$$
\int_{r}P\left(x\,,y\,,z\,\right)\mathbf{d}x\,+Q(x\,,y\,,z\,)\mathbf{d}y+R\left(x\,,y\,,z\,\right)\mathbf{d}z\,).
$$  

由此可以看出，前面所学的定积分、二重积分、三重积分、第一型曲线积分和第一型曲面积分有着完全一致的背景，都是一个数量函数在定义区域上计算几何量（面积、体积等），但是第二型曲线积分与之不同，它是一个向量函数沿有向曲线的积分（无几何量可言），所以有些性质和计算方法是不一样的，一定要加以对比，理解它们的区别和联系，不要用错或者用混.  

$\int_{L}(P\,,Q)\,\bullet\,(\,\mathrm{d}x\,\,,\mathrm{d}y\,)=\int_{L}P\,\mathrm{d}x\,+Q\mathrm{d}y\,,$  

$$
\int_{P}(P\,,Q\,,R\,)\,\bullet\,(\,\mathrm{d}x\,\,,\mathrm{d}y\,\,,\mathrm{d}z\,)=\int_{P}P\,\mathrm{d}x\,+Q\,\mathrm{d}y\,+R\,\mathrm{d}z.
$$  

# 2.计算  

# （1）基本方法一投二代三计算（化为定积分）.  

如果平面有向曲线 $L$ 由参数方程 $\begin{array}{r}{\binom{x-x\left(t\right)}{\left(t:\alpha\rightarrow\beta\right)}\left(t:\alpha\rightarrow\beta\right)}\end{array}$ 给出，其中 $t=\alpha$ 对应着起点 $A\,,t=$  $\beta$ 对应着终点 $.B$ ,则可以将平面第二型曲线积分化为定积分：  

$$
\int_{L}P(x\,,y)\mathrm{d}x+Q(x\,,y)\mathrm{d}y=\int_{0}^{\beta}\{P\big[x\,(t)\,,y(t)\big]x^{\prime}(t)+Q\big[x\,(t)\,,y(t)\big]y^{\prime}(t)\}\;\mathrm{d}t\,,
$$  

这里的 $\alpha\cdot\beta$ 谁大谁小无关紧要，关键是分别和起点与终点对应，  
例 18. 12已知 $L$ 是以A(1,0),B(0,1)及 $C(-1,0)$ 为顶点的三角形的正向边界曲线，则$\oint_{L}\mathrm{~\ensuremath{~\vert~}\,}y\;\mathrm{~\ensuremath{~\vert~}~d}x+\mathrm{~\ensuremath{~\vert~}~}x\;\mathrm{~\ensuremath~{~\vert~}~d}y=\cfrac{\mathrm{~\ensuremath~{~\vert~}~}\,}{\ensuremath{\mathrm{~\ensuremath~{~\vert~}~}}}\cdot$  

【解】应填一1.  

由于被积表达式含有绝对值符号，故设法去掉绝对值符号.  

如图18-14所示，对于分段光滑的闭曲线 ${\cal L}=\!\overline{{{A B}}}+\!\overline{{{B C}}}+\!\overline{{{C A}}}$ ，光滑段的方程依次为  

$\overline{{A B}}:y=1-x\,,x=1$ 与 $x=0$ 分别对应于 AB 段的起点与终点；  
 $\overline{{B C}}:\!y=1+x\!\;,x=0$ 与 $x=-1$ 分别对应于 BC 段的起点与终点;  
$\overline{{C A}}:y=0\,,x=-\,1$ 与$x=1$ 分别对应于 $C A$ 段的起点与终点.  

故  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/ad5df1753f44e6b01860bc6f8dde9d2636d93d2a2a34c2dcb3f719b0047d5250.jpg)  
图18-14  

$$
{\begin{array}{r l}&{{\underset{\mathbf{\theta}}{\sim}}{\simeq}{\biggl\lbrack}{\frac{\mid y\mid}{\lambda B}}\mid y\mid\,\mathrm{d}x+\mid x\mid\,\mathrm{d}y+{\biggl\lbrack}{\frac{\mid y\mid}{\lambda C}}\mid y\mid\,\mathrm{d}x+\mid x\mid\,\mathrm{d}y+{\biggl\lbrack}{\frac{\mid y\mid}{c A}}\mid y\mid\,\mathrm{d}x+\mid x\mid\,\mathrm{d}y{\mathrm{~\AA~}}}\\ &{\ ={\Biggl\lbrack}_{1}^{0}{\bigl\lbrack}(1-x)+x\,(-1){\bigr\rbrack}\mathrm{d}x+{\Biggl\rbrack}_{0}^{-1}{\bigl\lbrack}(1+x)+(-x){\bigr\rbrack}\mathrm{d}x+0}\\ &{\ =(x-x^{2}){\biggl\vert}_{1}^{0}+x{\biggl\vert}_{0}^{-1}=-1.}\end{array}}
$$  

(2) 格林公式.  

设平面有界闭区域 $D$ 由分段光滑曲线 $L$ 围成， $P(x\,,y\,)\,,Q(x\,,y\,)$ 在 $D$ 上具有一阶连续偏导  

$$
\oint_{L}\!P(x\,,y)\,\mathrm{d}x+Q(x\,,,y\,)\,\mathrm{d}y=\!\!\!\!\int_{D}\!\left({\frac{\partial Q}{\partial x}}-{\frac{\partial P}{\partial y}}\right)\,\mathrm{d}\sigma.
$$  

（如图18-15所示，所谓 $L$ 取正向，是指当一个人沿着 $L$ 的这个方向前进时，左手始终在 $L$ 所围成的 $D$ 内.）  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f2f2b2e0b6ac4b6a149ef4277ec4b9e69fc96f01147b3fbfefa3d89afa9fd6d8.jpg)  
图18-15  

#  $\textcircled{1}$ 曲线封闭且无奇点在其内部，直接用格林公式  

若给的是封闭曲线的曲线积分 $\oint_{L}P\,\mathrm{d}x+Q\,\mathrm{d}y$ ,可以验算 $P$ 和 $\boldsymbol{Q}$ 是否满足“在该封闭曲线所包围的区域 $D$ 内， $P$ 和 $\boldsymbol{Q}$ 具有一阶连续偏导数”.若满足，则可用格林公式  

$$
\oint_{L}P\,\mathrm{d}x+Q\,\mathrm{d}y=\!\!\!\int_{D}\!\left({\frac{\partial Q}{\partial x}}-{\frac{\partial P}{\partial y}}\right)\,\mathrm{d}\sigma
$$  

计算之.这里要求 $L$ 为 $D$ 的边界，且正向，  

例18.13求 $\oint_{L}(y\,-\,\mathrm{e}^{x}\,)\,\mathrm{d}x\,+(3x\,+\,\mathrm{e}^{y}\,)\,\mathrm{d}y\,,L\,{:}x\,^{2}\,+\,y^{2}\,=$ >看不清楚 $L$ 是什么曲线， $\sqrt{x^{2}+y^{2}}-x$ 正向一周.化成极坐标就看清楚了。【解 $L:r^{2}=r-r\cos{\theta}.$ ，约去仅原点成立的 $r=0$ ，得 $r=1-$ cOS $\theta$ ，此为心形线，如图18-16所示.  

用格林公式，其中 $D$ 为心形线围成的区域，  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/6c852c225944e83f0b3b1f3ecf95dd00f2a497181199218a878affdb60b5f1a5.jpg)  
图18-16  
$$
{\begin{array}{r l}&{{\bar{\mathbb{S}}}{\overline{{\!{\Big[}}}}{\Big(}{\frac{\partial Q}{\partial x}}-{\frac{\partial P}{\partial y}}{\Big)}\,\mathrm{d}x\,\mathrm{d}y=\!\!{\underset{{\boldsymbol D}}{\iint}}2\mathrm{d}x\,\mathrm{d}y}\\ &{\quad=2{\overset{{\int}^{2\pi}}{\!\!\!\mathrm{d}}}\theta{\overset{{\int}^{1-\cos\theta}}{\!\!\!\mathrm{\partial}}}r\,\mathrm{d}r=\!\!{\Big[}_{0}^{2\pi}\!\left(1-\cos\theta\,\mathrm{}\right)^{2}\mathrm{d}\theta}\\ &{\quad=4{\displaystyle\int}_{0}^{2\pi}\sin^{4}{\frac{\theta}{2}}\mathrm{d}\theta=16{\displaystyle\int}_{0}^{{\frac{\pi}{2}}}\sin^{4}t\,\mathrm{d}t=16\cdot{\frac{3}{4}}\cdot{\frac{1}{2}}\cdot{\frac{\pi}{2}}=3\pi.}\end{array}}
$$  

$\circledcirc$ 曲线封闭但有奇点在其内部,且除奇点外 $\frac{\partial Q}{\partial x}\equiv\frac{\partial P}{\partial y}$ ,则换路径.（一般令分母等于常数作为路径，路径的起点和终点无需与原路径重合.）  

若给的是封闭曲线的曲线积分 $\oint_{L}P\,\mathrm{d}x+Q\,\mathrm{d}y$ ,满足条件：在 $D$ 内除了奇点外， $P$ 和 $\boldsymbol{Q}$ 具有一阶连续偏导数，并且除奇点外，均有 $\frac{\partial Q}{\partial x}\equiv\frac{\partial P}{\partial y}$ 则可以换一条封闭曲线 $L_{\textrm{l}}$ 代替 $L$ ，它全在 $D$ 内，并能将奇点包含在 $L_{\textrm{l}}$ 的内部.则有公式  

$$
\oint_{L}{P}\,\mathrm{d}x+Q\,\mathrm{d}y\,\frac{\mathrm{~(~*~)~}}{\mathrm{~\int~}}\oint_{L_{1}}P\,\mathrm{d}x+Q\,\mathrm{d}y.
$$  

这里要求 $L_{\mathrm{~l~}}$ 与 $L$ 的方向相同.如果后者容易计算，就可达到目的.  

【注 $1(\star)$ 处是这样来的：如图18-17所示，若 $L$ 所围区域 $D$ 内有奇点 $\pmb q$ ，则用 $L_{\mathrm{~l~}}$ “挖去”它，并记挖去奇点后的阴影区域为 $D^{\prime}$ ，于是  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e4e0fd7dff0bd67683031ef2c75a602f92166dd8f72151183cf96f10309fcd10.jpg)  
图18-17  

$$
\begin{array}{r l}{\lefteqn{\oint_{L}P\,\mathrm{d}x+Q\,\mathrm{d}y=\oint_{L+L_{1}^{-}}P\,\mathrm{d}x+Q\,\mathrm{d}y-\oint_{L_{1}^{-}}P\,\mathrm{d}x+Q\,\mathrm{d}y}}\\ &{=\biggr\|\left(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y}\right)\,\mathrm{d}\sigma+\oint_{L_{1}}P\,\mathrm{d}x+Q\,\mathrm{d}y}\\ &{=\oint_{L_{1}}P\,\mathrm{d}x+Q\,\mathrm{d}y.}\end{array}
$$  

例18.14设 $D=\{(x\,,y\,)\mid x^{2}+y^{2}\leqslant4\}\,,\partial l$ 为 $D$ 的正向边界,则  

$\int_{\mathcal{D}_{D}}\,\frac{({x\,\mathrm{e}^{x^{2}+4y^{2}}+y\,})\,\mathrm{d}x+(4y\,\mathrm{e}^{x^{2}+4y^{2}}-x\,)\,\mathrm{d}y}{x^{2}+4y^{2}}=\frac{\,\mathrm{~\cdot~}\,}{\mathrm{~\cdot~}\,}.$ 【解】应填一 $\pi$  

经计算有  

$$
\frac{\partial}{\partial x}\Big(\frac{4y\,\mathrm{e}^{x^{2}+4y^{2}}-x}{x^{2}+4y^{2}}\Big)\!=\!\frac{8x y\,(x^{2}+4y^{2}-1)\,\mathrm{e}^{x^{2}+4y^{2}}+x^{2}-4y^{2}}{(x^{2}+4y^{2})^{2}}\!=\!\frac{\partial}{\partial y}\Big(\frac{x\,\mathrm{e}^{x^{2}+4y^{2}}+y}{x^{2}+4y^{2}}\Big)\,,
$$  

但是这里不能用格林公式，因为在 $D$ 内的点 $O(0,0)$ 处， ${}^{P,Q}$ 均不连续.故在 $D$ 内作一曲线 $L$  $x^{2}+4y^{2}=1$ ,取逆时针方向，从而  

$$
\int_{\partial D}\frac{({x\,{\mathrm{e}}^{\,\tau^{2}+4{\mathrm{y}}^{2}}}+{y\,\mathrm{d}}x+(4{y\,{\mathrm{e}}^{\,\tau^{2}+4{\mathrm{y}}^{2}}}-x)\,\mathrm{d}{\mathrm{y}}}{x^{\,2}+4{y}^{2}}=\int_{L}\frac{({x\,{\mathrm{e}}^{\,\tau^{2}+4{\mathrm{y}}^{2}}}+{y})\,\mathrm{d}x+(4{y}{\mathrm{e}}^{\tau^{2}+4{\mathrm{y}}^{2}}-x)\,\mathrm{d}{\mathrm{y}}}{x^{\,2}+4{y}^{2}}=\int_{\partial D}\frac{({x\,{\mathrm{e}}^{\,\tau^{2}+4{\mathrm{y}}^{2}}}+{y})\,\mathrm{d}{\mathrm{y}}}{x^{\,2}+4{y}^{2}}=\int_{\partial D}\frac{({y\,{\mathrm{e}}^{\,\tau^{2}+4{\mathrm{y}}^{2}}}-x)\,\mathrm{d}{\mathrm{y}}}{y}\,\mathrm{d}{\mathrm{y}}.
$$  
$$
\begin{array}{r l}&{=\displaystyle\int_{L}\left(\mathrm{e}x+y\right)\mathrm{d}x+\left(4\mathrm{e}y-x\right)\mathrm{d}y}\\ &{=\displaystyle\iint_{x^{2}+4y^{2}\leqslant1}(-2)\mathrm{d}x\mathrm{d}y}\\ &{=-\,\pi.}\end{array}
$$  

$\circled{3}$ 非封闭曲线且 $\frac{\partial Q}{\partial x}\equiv\frac{\partial P}{\partial y}$ ,则换路径.（换简单路径,路径的起点和终点需与原路径重合.）如果不是封闭曲线的曲线积分 $\int_{L_{1}}P\,\mathrm{d}x+Q\,\mathrm{d}y\,.$ （其中 $L_{\mathrm{~l~}}$ ：一条从 $A$ 到 $B$ 的路径)，可以验算 ${}^{P,Q}$ 是否满足“在某单连通区域内具有一阶连续偏导数并且 $\frac{\partial P}{\partial y}\equiv\frac{\partial Q}{\partial x},$ 若是，则可在该连通区域内另取一条从 $A$ 到 $B$ 的路径(例如边与坐标轴平行的折线），使得该积分容易计算以代替原路径而计算之,即 $\int_{L_{1}}\frac{\d(\star)}{\d t}\int_{L_{2}}$  

$(\,\star\,)$ 处是这样的;由于 $\frac{\partial P}{\partial y}\equiv\frac{\partial Q}{\partial x}$ 则在 $D$ 内（见图18-18）沿任意分段光滑闭曲线 $L$ 都有 $\oint_{L}P{\,\mathrm{d}}x+Q{\,\mathrm{d}}y=0$ ，故 $\oint_{L_{1}+L_{0}}=0\,\oint_{L_{2}+L_{0}}=0$ ,于是 $\int_{L_{1}^{\cdot}}=\int_{L_{2}^{\cdot}}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/133b748025627e9c3518b7caf9a4b3ea0199eed0443b8a9561df5a0f062b2217.jpg)  

例18.15设 $L$ 从点 $A\left(-\,\frac{\pi}{2},0\right)$ 沿曲线 $y=\cos x$ 到点 $B\left({\frac{\pi}{2}},0\right)$ ，则$\int_{L}\frac{(x-y)\ensuremath{\mathrm{d}}x+(x+y)\ensuremath{\mathrm{d}}y}{x^{2}+y^{2}}=\frac{\phantom{x}}{\phantom{x}}\cdot$  

【解】应填 $-\pi$ 直接用 $y=\cos x$ 代人计算非常困难.记  

$$
P=\frac{x-y}{x^{2}+y^{2}},Q=\frac{x+y}{x^{2}+y^{2}},
$$  

经过计算,可知  

$$
\frac{\partial P}{\partial y}\equiv\frac{\partial Q}{\partial x}\!=\!\frac{y^{2}-x^{2}-2x y}{(x^{2}+y^{2})^{2}},(x\,,\!y\,)\ne(0,\!0)\,,
$$  

这里将点（0,0）去掉，是因为在该点处 $P\,{,}Q$ 及其一阶偏导数都不存在,当然谈不上偏导数相等.  

由“ $\textcircled{3}$ ”推知，在不包含（0，0）的单连通区域内，该曲线积分与路径无关，取一条从 $A$ 到 $B$ 的上半圆弧 $L_{\textrm{l}}$ （见图18-19），  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/3c6ba0d4ff01360da748b51b9a52ec4a55ef416aa19e3144efe0bc2852d23219.jpg)  
图18-19  

从而可使原积分中的分母消去，有  

$$
\begin{array}{l}{\displaystyle\overrightarrow{\mathfrak{x}}\!\!\!\!\slash=\!\!\!\int_{L_{1}}\frac{(x-y)\mathrm{d}x+(x+y)\mathrm{d}y}{x^{2}+y^{2}}}\\ {\displaystyle\quad=\!\!\int_{\mathfrak{x}}^{0}\!\!\left[(\cos t-\sin t)(-\sin t)+(\cos t+\sin t)\cos t\right]\!\!\mathrm{d}t}\end{array}
$$  
$$
=\!\int_{\pi}^{\eta}\!\mathrm{d}t=-\,\pi.
$$  

【注】（1）如果 $L_{\mathrm{~1~}}$ 中参数 $t$ 取为从 $t=-\pi$ 到 $t\!=\!0($ 或 $t=\pi$ 到 $t\!=\!2\pi.$ ).虽然起点、终点仍为 A, $B$ ,但实际上取的是下半圆弧,这种 $L_{\sun}$ 与 $L$ 围成的区域内含有点 $O$ ,不是一个单连通区域,路径无关定理不适用.  

(2)还可这样命题： $L$ 为沿摆线 $x\!=\!t\!-\!\sin t\!-\!\pi,y\!=\!1\!-\!\cos t$ 从$t=$ 0到 $t=2\pi$ 的弧段，如图18-20所示.由于 $\frac{\partial P}{\partial y}\equiv\frac{\partial Q}{\partial x}$ ，换路径 $L_{\scriptscriptstyle1}$  $\begin{array}{l}{{\displaystyle|x=\pi\mathrm{cos}\,\,t\,,}}\\ {{\displaystyle|y=\pi\sin\,t\,,}}\end{array}$ 从 $\pi$ 到 0,于是  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/0b4d3ea532c59db14f29282857e847b58ee1cc9979e25b827e76bd5827821b92.jpg)  
图18-20  

$$
\begin{array}{l}{{\displaystyle{\hat{\imath}}\!=\!\frac{1}{\pi^{2}}\!\!\int_{L_{1}}\!\!(x-y){\mathrm{d}}x+(x+y)\,{\mathrm{d}}y}\ ~}\\ {{\displaystyle{\mathrm{}}=\!\frac{1}{\pi^{2}}\!\!\int_{\mathfrak{n}}^{0}\!\!(\pi{\cos}\,t-\pi{\sin}\,t)\,{\mathrm{d}}(\pi{\cos}\,t)+(\pi{\cos}\,t+\pi{\sin}\,t)\,{\mathrm{d}}(\pi{\sin}\,t)}\ ~}\\ {{\displaystyle{=}\!-\pi.}}\end{array}
$$  

$\circledast$ 非封闭曲线且 ${\frac{\partial Q}{\partial x}}\neq{\frac{\partial P}{\partial y}}$ 可补线使其封闭（加线减线）.  

如果不是封闭曲线的曲线积分,可以考虑补一条线 $C_{B A}$ ,使 $L_{A B}+C_{\scriptscriptstyle{B A}}$ 构成一封闭曲线，并且使其包围的区域为一单连通区域 $D$ ，在 $D$ 上 $P\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ 和 $Q(x\,,y\,)$ 具有一阶连续偏导数,则有  

$$
\begin{array}{r l}&{\bigg\int_{{L_{_{B R}}}}P\,\mathrm{d}x\,+Q\mathrm{d}y=\!\!\!\int_{{L_{_{A B}}}}P\,\mathrm{d}x\,+Q\mathrm{d}y\,+\!\!\int_{{c_{_{B A}}}}P\,\mathrm{d}x\,+Q\mathrm{d}y\,-\!\!\int_{{c_{_{B A}}}}P\,\mathrm{d}x\,+Q\mathrm{d}y}\\ &{\qquad\qquad\qquad\qquad=\!\!\oint_{{L_{}}}P\,\mathrm{d}x\,+Q\mathrm{d}y\,-\!\!\int_{{c_{_{B A}}}}P\,\mathrm{d}x\,+Q\mathrm{d}y}\\ &{\qquad\qquad\qquad\qquad=\!\pm\!\!\iint\!\!\left(\frac{\partial Q}{\partial x}-\frac{\partial P}{\partial y}\right)\mathrm{d}\sigma\,+\!\!\!\int_{{c_{_{A B}}}}P\,\mathrm{d}x\,+Q\mathrm{d}y\,,}\end{array}
$$  

其中 $L=L_{\ A B}+C_{\ B A}$ ，公式中的“ $\pm^{\,,}$ 号由 $L$ 的方向而定.若 $L$ 为正向则取正号，若 $L$ 为负向则取负号. $C_{A B}$ 为 $C_{B A}$ 的反向弧.如果上式右边的二重积分和 $\int_{C_{A B}}$ 容易计算的话,那么就可利用上述转换方法计算原积分 $\int_{L_{A B}}$  

例 18. 16求 $\int_{L}\bigl[\mathrm{e}^{x}\sin y-b(x+y\,)\bigr]\mathrm{d}x+(\mathrm{e}^{x}\cos y-a x\,)\mathrm{d}y$ ,其中 $^{a,b}$ 为常数， $L$ 为沿上半圆弧 $y={\sqrt{2a x-x^{\mathit{2}}}}$ 从 $A\left(2a\,,0\right)$ 到 $O(0,0)$ 的曲线段.  

【解】添一条线段 $L_{1}:y=0$ 从点 $O$ 到 $A$ ，使得 $L$ 与 $L_{\mathrm{~l~}}$ 构成封闭曲线,可用格林公式,而 $\int_{L_{1}}$ 较$\int_{L}$ 容易计算.  
$$
\begin{array}{r l r}{\lefteqn{\int_{\mathbb{H}^{\ast}\overrightarrow{\bf x}\"=\oint_{L+L_{1}}}-\int_{L_{1}}}}\\ &{}&{\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;\;=\iint_{0}\left({\mathrm{e}}^{x}\cos\,y-a-{\mathrm{e}}^{x}\cos\,y+b\,)\,\mathrm{d}x\,\mathrm{d}y-\!\!\int_{0}^{2a}\left(-\,b x\,\right)\!\mathrm{d}x\,,}\end{array}
$$  

其中 $D$ 为 $L_{\mathrm{~1~}}$ 与 $L$ 围成的区域(如图18-21所示,为半径等于 $^a$ 的半圆),其面积等于 $\frac{1}{2}\pi a^{2}$ ,于是  

$$
\begin{array}{l}{{=(b-a\,)\ \displaystyle\frac{1}{2}\pi a^{\,2}+2b a^{\,2}}}\\ {{{}}}\\ {{=\left(\displaystyle\frac{\pi}{2}+2\right)b a^{\,2}-\displaystyle\frac{1}{2}\pi a^{\,3}.}}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/26006ab0677899bfd83b85c13d74b3ad8f62a2f32b50d2bbb87cd50037ebd820.jpg)  
图18-21  

【注】本题还可以这样做：将原式分成两部分，  

$$
\int_{L}[\mathrm{e}^{x}\sin y-b(x+y)]\mathrm{d}x+(\mathrm{e}^{x}\cos y-a x)\mathrm{d}y
$$  

$$
=\!\int_{L}\!\mathrm{e}^{x}\sin y\,\mathrm{d}x+\mathrm{e}^{x}\cos y\,\mathrm{d}y-\!\!\int_{L}\!\!b(x+y)\mathrm{d}x+a x\,\mathrm{d}y.
$$  

第一部分满足路径无关条件,可以改取 $y=0$ 从点 $\scriptstyle A\,(2a\,,0)$ 到点 $O(0,0)$ ,于是知该积分为 0.第二部分可取圆弧的参数式 $x=\,a+a\cos{t}\,,y=\,a\sin{t}$ ，从 $\scriptstyle t\;=\;0$ 到 $t=\,\pi$ ，于是  

$$
-\!\int_{L}\!b(x+y)\mathrm{d}x+a x\,\mathrm{d}y
$$  

$$
\begin{array}{l}{{\displaystyle{=}\displaystyle{\int_{0}^{\pi}}[b a^{2}(1+\cos t+\sin t)\sin t-a^{3}(1+\cos t)\cos t]\mathrm{d}t}}\\ {{\displaystyle{=}\,\left(\frac{\pi}{2}+2\right)b a^{2}-\frac{1}{2}\pi a^{3}.}}\end{array}
$$  

#  $\textcircled{5}$ 积分与路径无关问题.  

设在单连通区域 $D$ 内 ${}^{P,Q}$ 具有一阶连续偏导数，则下述6个命题等价.  

a. $\int_{L_{A B}}{P(x\,,y)\mathrm{d}x}+Q(x\,,y)\mathrm{d}y$ 与路径无关.   
b.沿 $D$ 内任意分段光滑闭曲线 $L$ 都有 $\oint_{L}P{\,\mathrm{d}}x+Q{\,\mathrm{d}}y=\,0.$ c. $P{\mathrm{d}}x+Q{\mathrm{d}}y$ 为某二元函数 ${\boldsymbol{u}}({\boldsymbol{x}}\,,{\boldsymbol{y}})$ 的全微分.   
d. $P\,{\mathrm{d}}x+Q\,{\mathrm{d}}y=\,0$ 为全微分方程.   
e. $P i+Q j$ 为某二元函数 $u(x\,,y)$ 的梯度.   
f. ${\frac{\partial P}{\partial y}}\equiv{\frac{\partial Q}{\partial x}}\,$ 在$D$ 内处处成立.  

[注】“c,d,e”中所涉及的 ${\boldsymbol{u}}({\boldsymbol{x}}\,,{\boldsymbol{y}})$ 称为 $P\mathtt{d}x+Q\mathtt{d}y$ 的原函数,若存在一个原函数 ${\pmb u}({\pmb x}\,,{\pmb y})$ ，则 $u(x,y)+C$ 也是原函数.  
一般说来，“f”是解题的关键点.  

若荘 $P\,{\mathcal{\Omega}}$ 已知，则考正问题：“验证 $\frac{\partial P}{\partial y}\equiv\frac{\partial Q}{\partial x}$ ,即“f”成立，则“a,b,c,d,e”成立”.“a至e”成立，再求$\int_{L}$ 或$\boldsymbol{u}$  

若 $P\,{\mathcal{\,\Omega}}$ 中含有未知函数(或未知参数),则考反问题：“已知‘a,b,c,d,e’其中任一命题成立,则有成立,即 $\frac{\partial P}{\partial y}\equiv\frac{\partial Q}{\partial x},$ 用此式子求出未知量，再进一步求 $\int_{L}$  ${\pmb u}$  

接下来,如何求 $\boldsymbol{u}$ ？  

法一用可变终点 $(x\,,y)$ 的曲线积分求出 $u(x\,,y)$ ：  

$$
u(x\,,y)=\int_{(x_{0},y_{0})}^{(x\,,y)}P(x\,,y)\mathrm{d}x+Q(x\,,y)\mathrm{d}y\,,
$$  

其中 $(x_{\circ},y_{\circ})$ 为 $D$ 内任意取定的一点， $(x\,,y\,)$ 为动点，则此式即为要求的一个 $u(x\,,y\,)$ .不过在使用此方法前，必须先验证在所述单连通区域内是否满足与路径无关的充要条件 $\frac{\partial Q}{\partial x}\equiv\frac{\partial P}{\partial y}$ 不满足时这种 $u\left(x\,,y\,\right)$ 是不存在的,更谈不上用曲线积分求 $u(x\,,y)$  

至于这个可变终点 $(x\,,y\,)$ 的曲线积分如何计算？一种方法是找一条认为是方便的从点 $(x_{0},y_{0})$ 到变点 $(x\,,y\,)$ 的全在 $D$ 内的路径计算.另一种方法是按折线 $(x_{\,0}\,,y_{\,0})\rightarrow(x\,,y_{\,0})\rightarrow$  $(x\,,y\,)$ （见图18-22）或按折线 $(x_{\,0}\,,y_{\,0}\,)\rightarrow(x_{\,0}\,,y\,)\rightarrow(x\,,y\,)$ （见图18-23）计算.计算公式分别如下：  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/8f9755eaaae723e0fca518cb0ae2dec2dc39557444ac4e507cbdda50cff8688e.jpg)  
图18-22  
图18-23  

$$
u(x\,,y)=\!\int_{x_{0}}^{x}P(x\,,y_{0})\,\mathrm{d}x+\int_{y_{0}}^{y}Q(x\,,y)\,\mathrm{d}y
$$  

或  

$$
u(x\,,y)=\!\int_{x_{0}}^{x}P(x\,,y)\mathrm{d}x+\int_{y_{0}}^{y}Q(x_{0}\,,y\,)\mathrm{d}y.
$$  

这里要求折线的路径应在 $D$ 内.  

以上公式得出的 $u\left(x\,,y\right)$ 再加任意常数 $C$ 就得到了所有原函数.  

法二用凑微分法写出d $\left[{u}(x,y)\right]$ (当然这需要一些技巧），在积分与路径无关条件下，有  

$$
\int_{L_{A B}}P\,\mathrm{d}x\,+Q\,\mathrm{d}y=\!\int_{L_{A B}}\!\mathrm{d}\!\left[u\left(x\,,y\right)\right]\!=u\left(x\,,y\right)\bigg|_{A}^{\,\,B}=u\left(B\right)-u\left(A\right).
$$  

例18.17设曲线积分 $\int_{L}F(x\,,y)(y\,\mathrm{d}x+x\mathrm{d}y)$ 与路径无关,由方程 $F(x\,,y)\,{=}0$ 所确定的隐函数 ${\boldsymbol{y}}={\boldsymbol{y}}\left({\boldsymbol{x}}\right)$ 的图形过点(1,2),则方程 $F(x\,,y)=0$ 所确定的曲线表达式为  

【解】应填 $x y=2$  
令 $P=y F(x\,,y)\,,Q=x F(x\,,y)$ ，由积分与路径无关，有 $\frac{\partial P}{\partial y}\!=\!\frac{\partial Q}{\partial x}$ ，又  

$$
\frac{\partial P}{\partial y}=F+y\;\frac{\partial F}{\partial y},\frac{\partial Q}{\partial x}=F+x\;\frac{\partial F}{\partial x},
$$  

于是 $y\,{\frac{\partial F}{\partial y}}\!=\!x\,{\frac{\partial F}{\partial x}}$ 即 $\frac{F_{x}^{\prime}}{F_{y}^{\prime}}\!=\!\frac{y}{x}$ 又方程 $F(x\,,y\,)\,{=}\,0$ 确定了一个 $_y=y\left(x\right)$ 的隐函数,由隐函数的求导法则可得， $\frac{\mathrm{d}y}{\mathrm{d}x}\!=\!-\!\frac{F_{x}^{\prime}}{F_{y}^{\prime}}\!=\!-\!\frac{y}{x}$ 从而 $\mid\!\!\operatorname{ln}\mid y\mid\!\!=\,-\!\!\ln\mid x\mid\!\!+\!\!\ln C_{1}$ 即 $x y=C$ ，利用条件 $\boldsymbol{y}\mid_{\mathbf{\Omega}_{x=1}}=$ 2,得 $C=2$ ,故所求的曲线为 $x y=2$  

例18.18设函数 $f(x),g(x)$ 二阶导数连续， $f(0)\,{=}\,0\,,g(0)\,{=}\,0$ ,且对于平面上任一简单闭曲线 $L$ ,均有  

$$
\oint_{L}\Bigl[y^{2}f(x\,)+2y\,\mathrm{e}^{x}+2y g^{\prime}(x\,)\Bigr]\mathrm{d}x+2\bigl[y g\,(x\,)+f(x\,)\bigr]\mathrm{d}y=0.
$$  

(1)求 $f(x),g(x)$ 的表达式；  

（2）设 $L_{1}$ 为任一条从点（0,0）到点（1,1）的曲线，计算  

$\int_{{L}_{1}}\Bigl[{\bf{y}}^{2}f(x)+2y{\bf{e}}^{x}+2y{g}(x\,)\Bigr]{\bf{d}}x+2\bigl[{\bf{y}}{g}(x\,)+f(x\,)\bigr]{\bf{d}}y.$ 【解】 (1) 记 $P\left(x\,,y\,\right)=y^{2}\,f(x\,)+2y\,\mathrm{e}^{x}+2y g\left(x\,\right),$ $Q(x\,,y)=2\bigl[y g(x\,)+f(x\,)\bigr].$  

由题意知， $\frac{\partial Q}{\partial x}\!=\!\frac{\partial P}{\partial y}$ ，即  

整理得  

$$
\begin{array}{r l}&{2\big[y g^{\prime}(x)+f^{\prime}(x)\big]\!=\!2y f(x\,)+2\mathrm{e}^{x}+2g(x\,)\,,}\\ &{\,\,y\big[g^{\prime}(x\,)-f(x\,)\big]\!=\!-\big[f^{\prime}(x\,)-g(x\,)-\mathrm{e}^{x}\big]\,,}\end{array}
$$  

比较等式两边 $_y$ 的同次幂系数，有  

$$
\begin{array}{r}{\left\vert g^{\prime}(x)-f(x)=0\,,\right.}\\ {\left.\left(f^{\prime}(x)-g(x)-\mathbf{e}^{x}=0.\right)\right.}\end{array}
$$  

由 $\textcircled{1}$ 式，有 $f^{\prime}(x)=g^{\prime\prime}(x)$ ，代人 $\circledcirc$ 式，得  

$$
g^{\prime\prime}(x\,)-g(x\,)=\mathrm{e}^{x}\,,
$$  

解得  

$$
g\left(x\right)=C_{1}\,\mathrm{e}^{x}+C_{2}\,\mathrm{e}^{-x}+{\frac{1}{2}}x\,\mathrm{e}^{x}\,,
$$  

于是  

$$
f(x)=g^{\prime}(x\,)=\left(C_{1}+{\frac{1}{2}}\right)\,\mathrm{e}^{x}-C_{2}\,\mathrm{e}^{-x}+{\frac{1}{2}}x\,\mathrm{e}^{x}.
$$  

又$g(0)\!=\!0,f(0)\!=\!0$ ，故  

$$
\begin{array}{l}{{\displaystyle{C_{1}+C_{2}=0\,,}}}\\ {{\displaystyle{C_{1}+\frac{1}{2}-C_{2}=0\,,}}}\end{array}
$$  

解得 $C_{1}=-\frac{1}{4},C_{2}=\frac{1}{4}$ ，故  
$$
\begin{array}{c}{{f(x)=\displaystyle\frac{1}{4}({\bf e}^{x}-{\bf e}^{-x})+\frac{1}{2}x\,{\bf e}^{x}\,,}}\\ {{\,}}\\ {{g\left(x\right)=-\displaystyle\frac{1}{4}({\bf e}^{x}-{\bf e}^{-x})+\displaystyle\frac{1}{2}x\,{\bf e}^{x}.}}\end{array}
$$  

（2）用折线法.如图18-24所示，沿折线 $(0,0)\rightarrow(1,0)\rightarrow(1,1)$ ，有原式 $\begin{array}{r l}&{\mathbf{\dot{s}}\!\!=\!\!\int_{0,0}^{1.1}\!\left[y^{2}f(x)+2y\mathbf{e}^{x}+2y g(x)\right]\!\mathrm{d}x+2\!\left[y g(x)+f(x)\right]\!\mathrm{d}y}\\ &{\quad\!=\!2\!\left[\!\frac{1}{0}\!\left[\Im g(1)+f(1)\right]\!\mathrm{d}y}\\ &{\quad\!=\!2\left[\!\frac{1}{2}g(1)+f(1)\right]\!\right]\!\mathrm{d}{x}}\\ &{\quad\!=\!\frac{1}{4}(7\mathbf{e}-\mathbf{e}^{-1}).}\end{array}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/bbcceec340886f5b22ef5fc5fce9ba1aa2771c057c028e248cc95c9f1331ca4f.jpg)  
图18-24  

例 18. 19验证表达式 $\frac{y\,{\mathrm{d}}x}{3x^{\,2}-2x y+3y^{\,2}}-\frac{x\,{\mathrm{d}}y}{3x^{\,2}-2x y+3y^{\,2}}$ 在不含原点的任意单连通区域内是某函数 $u(x\cdot y)$ 的全微分,并在 $x>0$ 区域内求函数 $u(x\,,y\,)$ ：  

【解】记 $P\left(x\mid,y\right)=\frac{y}{3x^{2}-2x y+3y^{2}},Q(x\,,y\,)=\frac{-x}{3x^{2}-2x y+3y^{2}}$ 则 $\cfrac{\partial Q}{\partial x}=\cfrac{-\left(3x^{2}-2x y+3y^{2}\right)+x\left(6x-2y\right)}{\left(3x^{2}-2x y+3y^{2}\right)^{2}}=\cfrac{3x^{2}-3y^{2}}{\left(3x^{2}-2x y+3y^{2}\right)^{2}}=\cfrac{\partial P}{\partial y}\,,\left(x\,,y\,;\,x^{2}\right)\,.$ ≠（0，0)，故$\frac{y\,\mathrm{d}x}{3x^{\,2}-2x y+3y^{\,2}}-\frac{x\,\mathrm{d}y}{3x^{\,2}-2x y+3y^{\,2}}$ 在不含原点的任意单连通区  

如图18-25所示，取 $(x_{\mathit{\Phi}_{0}},y_{0})=(1,0)$ 作为积分路径的起点，沿折线 $\left(1,0\right)\to\left(x\,,0\right)\to\left(x\,,y\right)$ ，有  

$$
\begin{array}{l}{\displaystyle u\left(x,y\right)=\int_{1}^{\infty}{P\left(x,0\right)\mathrm{d}x}+\int_{0}^{\infty}{Q(x,y)\mathrm{d}y}+C_{1}}\\ {\displaystyle\qquad\qquad=\int_{1}^{\infty}{0\mathrm{d}x}-\int_{0}^{\infty}{\frac{x}{3x^{2}-2x y+3y^{2}}\mathrm{d}y}+C_{1}}\\ {\displaystyle\qquad=-\frac{x}{3}\int_{0}^{\infty}{\frac{\mathrm{d}y}{\left(y-\frac{1}{3}x\right)^{2}+\frac{8}{9}x^{2}}}+C_{1}}\\ {\displaystyle\qquad=-\frac{1}{2\sqrt{2}}\mathrm{arcta\,}\frac{3y-x}{2\sqrt{2}x}-\frac{1}{2\sqrt{2}}\mathrm{arcta\,}\frac{1}{2\sqrt{2}}+C_{1}}\\ {\displaystyle\qquad=-\frac{1}{2\sqrt{2}}\mathrm{arcta\,}\frac{3y-x}{2\sqrt{2}x}+C(x>0)\,,}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/586b1c03a4ca996a6591921881d2ddfb73f93d25069edb0a1c7053542640cb63.jpg)  
图18-25  

其中 $C=C_{1}-\frac{1}{2\sqrt{2}}$ arctan $\frac{1}{2{\sqrt{2}}}$ 为任意常数.  

【注】加任意常数 $c$ 是为了求出全部满足题意的 ${\pmb u}({\pmb x}\setminus{\pmb y})$ ，下一题加 $c$ 也是这个原因。  
例 18. 20确定常数 $\lambda$ ,使在右半平面 $x>0$ 上的向量  

$$
\pmb{A}(x\,,y)=2x y\,(x^{\,4}+y^{\,2})^{\lambda}i-x^{\,2}(x^{\,4}+y^{\,2})^{\lambda}j
$$  

为某二元函数 $u(x\,,y)$ 的梯度,并求 ${\boldsymbol{u}}({\boldsymbol{x}}\,,{\boldsymbol{y}}\,)$  

【解】令  

$$
P(x\,,y)=2x y\,(x^{4}+y^{2})^{\lambda}\,,Q(x\,,y)=-\,x^{2}(x^{4}+y^{2})^{\lambda}.
$$  

由题意知 $\frac{\partial Q}{\partial x}\!=\!\frac{\partial P}{\partial y}$ ，则  

$$
4x\,(x^{\,4}+y^{\,2})^{\lambda}\,(\lambda+1)=0.
$$  

因为 $x>0$ ,于是推知当且仅当 $\lambda=-1$ 时，所给向量场是梯度场.  

在 $x>0$ 的半平面内任取一点，例如(1,0）作为积分路径的起点，沿折线 $(1,0)\rightarrow(_{x}\,,0)\rightarrow$  $(x\,,y\,)$ ,有  

$$
\begin{array}{r l}&{u\left(x\ ,y\right)=\!\!\int_{0}^{\infty}\frac{\!\!\!2x\,y}{x^{4}}\,\frac{\!\!2x\,y\,{\mathrm{d}}x\,-\,x^{\,2}\,{\mathrm{d}}y}{x^{\,4}\,+\,y^{\,2}}+C}\\ &{\qquad\qquad\qquad=\!\!\int_{1}^{x}\frac{2x\,\cdot\,0}{x^{\,4}\,+\,0^{2}}{\mathrm{d}}x\,-\!\!\int_{0}^{y}\frac{\!\!\!x^{\,2}}{x^{\,4}\,+\,y^{\,2}}{\mathrm{d}}y+C}\\ &{\qquad\qquad\qquad=\!\,-\arctan\frac{y}{x^{\,2}}+C\,,}\end{array}
$$  

其中 $c$ 为任意常数.  

# (3） 两类曲线积分的关系.  

$$
\int_{L}P\,\mathrm{d}x+Q\,\mathrm{d}y=\int_{L}\left(P\cos\,\alpha+Q\cos\,\beta\right)\mathrm{d}s\,,
$$  

其中(cos $\pmb{\alpha}$ ,cos $_{\beta}$ ）为 $L$ 上点 $(x\,,y)$ 处与 $L$ 同向的单位切向量.  

例18.21设 $L$ 是从点 $A\left(1,-1\right)$ 沿曲线 $x^{2}+y^{2}=-2y\,(y\geqslant-1)$ 到点 $B(-1,-1)$ 的有向曲线， $f(x)$ 是连续函数,计算  

$$
I=\!\int_{L}\!x\left[f(x\,)+1\right]\!\mathrm{d}y-\frac{y^{2}\big[f(x\,)+1\big]+2y f(x\,)}{\sqrt{1-x^{\,^{2}}}}\mathrm{d}x.
$$  

【解】法一 $L:y=\sqrt{1-x^{2}}-1(x$ 从1变到-1), ${\mathrm{d}}y={\frac{-x}{\sqrt{1-x^{\,2}}}}{\mathrm{d}}x\ ,L$ 的弧长微元为  

$$
\begin{array}{l}{\displaystyle\mathrm{d}s=\sqrt{(\mathrm{d}x\,)^{2}+(\mathrm{d}y\,)^{2}}}\\ {\displaystyle\quad=\sqrt{(\mathrm{d}x\,)^{2}+\left(\frac{\displaystyle-x}{\displaystyle\sqrt{1-x^{\,2}}}\mathrm{d}x\,\right)^{2}}}\\ {\displaystyle\quad=\frac{\sqrt{(\mathrm{d}x\,)^{2}}}{\sqrt{1-x^{\,2}}}\,\mathrm{-}\frac{\,\mathrm{d}x}{\displaystyle\sqrt{1-x^{\,2}}}.}\end{array}
$$  

有向曲线 $L$ 在点 $(x\,,y)$ 处的切向量为 $\pmb{T}=(\cos\alpha\,,\cos\beta)$ ，其中  

$$
\cos\alpha={\frac{\mathrm{d}x}{\mathrm{d}s}}=-{\sqrt{1-x^{\mathit{\,2}}}}\,,
$$  
于是  

$$
\begin{array}{r l}&{\tilde{l}=\int_{\tilde{\mathcal{X}}}\tilde{c}(\zeta\alpha+1)\tilde{\log}-\frac{\tilde{\gamma}^{\prime}(\zeta\alpha)}{\sqrt{1-x^{\prime}}}+\frac{1}{1+\tilde{\gamma}^{\prime}}\tilde{c}(\zeta\alpha)_{d\alpha}}\\ &{=\int_{\tilde{\mathcal{X}}}\Big[\frac{\tilde{\gamma}}{1-\tilde{\gamma}^{\prime}}\frac{\tilde{\gamma}^{\prime}\tilde{\gamma}(\zeta\alpha)+1}{\sqrt{1-x^{\prime}}}+\frac{1}{\tilde{\gamma}^{\prime}}\tilde{c}(\zeta\alpha)_{d\alpha}+x\tilde{\gamma}(\zeta\alpha+1)\log{\tilde{\Big|}}\tilde{d}\alpha}\\ &{=\int_{\tilde{\mathcal{X}}}\Big[\frac{\tilde{\gamma}^{\prime}\tilde{\gamma}(\zeta\alpha)+1}{\sqrt{1-x^{\prime}}}+\frac{1}{\sqrt{2}\tilde{\gamma}(\alpha)}\cdot(-\sqrt{1-x^{\prime}})+x\tilde{\gamma}(\zeta\alpha)+1\tilde{\gamma}\alpha\Big]\tilde{\gamma}\alpha}\\ &{=\int_{\tilde{\mathcal{X}}}[\tilde{\alpha}^{+}+\tilde{\gamma}^{+}\beta\gamma(\zeta\alpha)+x^{+}\tilde{\gamma}^{\prime}]\tilde{\alpha}}\\ &{=\int_{\tilde{\mathcal{X}}}(\zeta\alpha^{+}\gamma^{*})\tilde{\beta}\alpha-\int_{(\zeta\beta)}\tilde{\gamma}\tilde{\beta}\alpha}\\ &{=-\tilde{\gamma}\frac{\tilde{\gamma}}{\tilde{\gamma}}(\sqrt{1-x^{\prime}}-1)\frac{1}{\sqrt{1-x^{\prime}}}\tilde{\alpha}}\\ &{=-\tilde{\gamma}\frac{1}{\sqrt{1-\tilde{\gamma}^{\prime}}}\tilde{1}\alpha-\frac{1}{\sqrt{1-x^{\prime}}}\Big)\tilde{\alpha}}\\ &{=-4\tilde{\alpha}\coth{x}\bigg[\frac{1}{\sqrt{1-x^{\prime}}}}\end{array}
$$  

这里，将 $_{x}$ 视为参数时，由于 $_{x}$ 从1变到 $-1(x$ 从大变到小)，故在求有向曲线 $L$ 的切向量时， $\mathrm{d}x<0$ ，从而  

$$
\mathrm{d}s=\,{\sqrt{(\mathrm{d}x\,)^{2}+(\mathrm{d}y\,)^{2}}}=\,{\frac{\sqrt{(\mathrm{d}x\,)^{2}}}{\sqrt{1-x^{2}}}}={\frac{-\mathrm{d}x}{\sqrt{1-x^{2}}}},
$$  

而在将对弧长的曲线积分 $\int_{L}(-\,2y\,)\,\mathrm{d}s$ 化为定积分时，由于定积分的积分下限小于积分上限，故此时 $\mathrm{d}x>0$ ,从而  

$$
\mathrm{d}s=\sqrt{1+\Bigl(\frac{\mathrm{d}y}{\mathrm{d}x}\Bigr)^{2}}\,\mathrm{d}x=\frac{1}{\sqrt{1-x^{\,2}}}\mathrm{d}x\,.
$$  

法二有向曲线 $L$ 的参数方程为 $\begin{array}{r}{\Big\{x=\cos\,t\,,\ \ \ }\\ {\quad y=-1+\sin\,t}\end{array}(t$ 从0变到 $\pi),L$ 的弧长微元为  

$$
\begin{array}{r}{\mathrm{d}s=\sqrt{(-\sin\,t\,\mathrm{d}t\,)^{2}+(\cos\,t\,\mathrm{d}t\,)^{2}}=\mathrm{d}t\,.}\end{array}
$$  

有向曲线 $L$ 在点 $(x\,,y\,)$ 处的切向量为 $\pmb{T}=(\cos\alpha\,,\cos\beta)$ ,其中  

$$
{\frac{\alpha=\!{\frac{\mathrm{d}x}{\mathrm{d}s}}}{\mathrm{d}s}}=-\sin\,t=-1-y=-\,{\sqrt{1-x^{\,^{2}}}}\,,
$$  

于是  
$$
\begin{array}{r l}&{I=\!\int_{x}\!\!\!x\!\left[f(x)+1\right]\!\!\mathrm{d}y-\frac{y^{\prime}\left[f(x)+1\right]+2y f(x)}{\sqrt{1-x^{\prime}}}\mathrm{d}x}\\ &{\quad=\!\int_{x}\!\left\langle-\frac{y^{\prime}\left[f(x)+1\right]+2y f(x)}{\sqrt{1-x^{\prime}}}\cos\,a+x\left[f(x)+1\right]\!\cos\beta\right\rangle\!d s}\\ &{\quad=\!\int_{x}\!\left\langle-\frac{y^{\prime}\left[f(x)+1\right]+2y f(x)}{\sqrt{1-x^{\prime}}}\cdot(-\sqrt{1-x^{\prime}})+x[f(x)+1]\cdot x\right\rangle\!d s}\\ &{\quad=\!\int_{x}\!\left\lbrack(x^{\prime}+y^{\prime}+2y)f(x)+x^{\prime}+y^{\prime}\right\rbrack\!d s}\\ &{\quad=\!\int_{x}\!\left(x^{\prime}+y^{\prime}\right)\!\mathrm{d}s=\!\int_{x}\!\left(-2y\right)\!\mathrm{d}s}\\ &{\quad=\!\int_{x}^{\prime}\!\left(1-\sin t\right)\!\mathrm{d}t}\\ &{\quad=2\pi^{-4}.}\end{array}
$$  

【注】(1)对有向曲线 $L$ $\begin{array}{r}{\left\{x=x\left(t\right),\right.}\\ {\left.\quad y=y\left(t\right),\right.}\end{array}$ 起点对应参数 $t=\alpha$ ,终点对应参数 $t=\beta$ ，若 $\alpha<\beta$ ，则 $\pmb{\tau}=(x_{\mathrm{~}}^{\prime},y_{\mathrm{~}}^{\prime})$ 是与 $L$ 同向的切向量，而若 $\alpha>\beta$ ，则 $\pmb{\tau}=-(x_{\iota}^{\prime},y_{\iota}^{\prime})$ 是与 $L$ 同向的切向量. (2)本题中 $f(x)$ 只是连续函数,未提供可导的条件,故若考虑加线补成封闭区域,然后用格林公式,是行不通的.  

(4）空间问题.  

（一投二代三计算 $\textcircled{1}$ 直接计算  

用斯托克斯（Stokes）公式  

# a.一投二代三计算.  

$\rho_{x}=\!x\left(t\right)$ ，设 $\Gamma,\left\{y=y\left(t\right),t:\alpha\rightarrow\beta\right\}$ ,则有 $\scriptstyle(z\,=\,z\,(\,t\,)$ ，$\int_{r}P\,\mathrm{d}x+Q\,\mathrm{d}y+R\,\mathrm{d}z$ $\int_{a}^{\beta}\{P\big[x(t),y(t),z(t)\big]x^{\prime}(t)+Q\big[x(t),y(t),z(t)\big]y^{\prime}(t)+R\big[x(t),y(t),z(t)\big]z^{\prime}(t)\}\,\mathrm{d}t,$ )d.  

# b.用斯托克斯公式.  

设 $\Omega$ 为某空间区域， $\boldsymbol{\Sigma}$ 为 $\Omega$ 内的分片光滑有向曲面片， $\boldsymbol{\Gamma}$ 为逐段光滑的 $\pmb{\Sigma}$ 的边界，它的方向与 $\boldsymbol{\Sigma}$ 的法向量成右手系，函数 $P\left(x\,,y\,,z\,\right),Q\left(x\,,y\,,z\,\right)$ 与 $R\left(\,x\,,y\,,z\,\right)$ 在 $\Omega$ 内具有连续的一阶偏导数,则有斯托克斯公式：  

$\oint_{r}P\,{\mathrm{d}}x+Q\,{\mathrm{d}}y+R\,{\mathrm{d}}z=\iint_{\Sigma}{\left[\begin{array}{l l l}{{\mathrm{d}}y\,{\mathrm{d}}z}&{{\mathrm{d}}z\,{\mathrm{d}}x}&{{\mathrm{d}}x\,{\mathrm{d}}y}\\ {{\cfrac{\partial}{\partial{\boldsymbol{x}}}}}&{{\cfrac{\partial}{\partial y}}}&{{\cfrac{\partial}{\partial z}}}\\ {P}&{Q}&{R}\end{array}\right]}$ （此为第二型曲面积分形式）  
dS（此为第一型曲面积分形式），  

其中 $\pmb{n}^{\circ}=(\cos\alpha$ ,cos $\beta$ ,cos）为 $\Sigma$ 的单位外法线向量.  

【注】可以证明(这里不证),公式的成立与绷在 $\pmb{T}$ 上的曲面大小、形状无关，如图18-26所示,有 $f_{r}=\int\limits_{z_{1}}^{\theta}=\int\limits_{z_{2}}^{\theta}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/ca00a422842e40bc5577312dd39556b1eee7e1822bb5178e12e558e8c935ca7e.jpg)  
图18-26  

例18.22已知 $\pmb{\Sigma}$ 为曲面 $4x^{\,2}+y^{\,2}+z^{\,2}=1(x\geqslant0,y\geqslant0,z\geqslant0)$ 的上侧（见图18-27）， $L$ 为 $\pmb{\Sigma}$ 的边界曲线，其正向与 $\boldsymbol{\Sigma}$ 的正法向量满足右手法则，计算曲线积分  

$$
I=\!\!\oint_{L}\,(y z^{2}-\cos\,z\,)\,\mathrm{d}x\,+2x z^{2}\,\mathrm{d}y+(2x y z+x\sin\,z\,)\,\mathrm{d}z.
$$  

【解】法一一投二代三计算.记  

$L_{x}:{\binom{y^{2}+z^{2}=1,}{x=0,}}$ 方向为 $(0,\!1,\!0)\!\rightarrow(0,\!0,\!1)$ ：$L_{y}:\left\lbrack\!\!\begin{array}{l}{4x^{\,2}+z^{\,2}=1\!\,,}\\ {y=0\,,}\end{array}\!\!\right.\!\!\slash\!\!\!\dot{y}\,|\!\!\rtimes\!\!\!\slash y(0,0,1)\to\left(\frac{1}{2},0,0\right)\!\!\right);$  $L_{z}:\left\{_{z=0,}^{4x^{2}+y^{2}=1},\right.$ 方向为 $\left(\frac{1}{2},0,0\right)\rightarrow\left(0,1,0\right)$  

因为  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/5928ad52b68dcf61c82661796d09dc8eca0ee4792f144a13f03fcbcbbe464c0b.jpg)  
图18-27  

$$
\begin{array}{l}{\displaystyle I_{x}=\biggr\int_{L_{y}}\left(y z^{2}-\cos\,z\right)\mathrm{d}x\,+\left.2x z^{2}\mathrm{d}y\,+\left(2x y z+x\sin\,z\right)\mathrm{d}z=\int_{L_{z}}0\mathrm{d}y\,+\left(y z\right)\mathrm{d}z\right|_{z}}\\ {\displaystyle I_{y}=\biggr\int_{L_{y}}\left(y z^{2}-\cos\,z\right)\mathrm{d}x\,+\left.2x z^{2}\mathrm{d}y\,+\left(2x y z+x\sin\,z\right)\mathrm{d}z}\\ {\displaystyle=\biggr\int_{L_{y}}\left(-\cos\,z\right)\mathrm{d}x\,+x\sin\,z\mathrm{d}z}\\ {\displaystyle=\biggr\int_{L_{y}}\mathrm{d}(-x\cos\,z)}\\ {\displaystyle=-\,x\cos\,z\biggr\rvert_{\mathrm{top,\mathrm{p}}}^{\left(\frac{1}{2},0,0\right)}=-\frac{1}{2},}\end{array}
$$  

$$
\begin{array}{l}{{I_{z}=\nonumber\int_{{L_{z}}}\left(y z^{2}-\cos\,z\,\right)\mathrm{d}x\,+2x\,z^{2}\mathrm{d}y\,+(2x\,y z+x\sin\,z\,)\mathrm{d}z}}\\ {{\mathrm{}\quad=-\displaystyle\int_{{L_{z}}}\mathrm{d}x=-\,x\,\left|\begin{array}{l}{{\scriptscriptstyle{(0.1,0)}}}\\ {{\scriptscriptstyle{({\frac{1}{2}},0,0)}}}\end{array}\right|={\frac{1}{2}}\,,}}\end{array}
$$  

所以  

$$
I=I_{s}+I_{s}+I_{z}=0-\frac{1}{2}+\frac{1}{2}=0.
$$  
# 法二根据斯托克斯公式，得  

$$
\begin{array}{r l}&{I=\!\!\oint_{L}\!\!(y z^{2}-\cos z)\mathbf{d}x+2x z^{2}\mathbf{d}y+(2x y z+x\sin z)\mathbf{d}z}\\ &{\quad=\!\!\!\iint_{z}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\frac{\,\!\!\!\,\!\!\!\,\!\!\!\,\,\!\!\!\!\,\!\!\!\,\,\!\!\!\!\,\!\!\!\,\,\!\!\!\!\,\!\!\!\,\,\!\!\!\,\,\!\!\!\,\,\!\!\!\,\,\!\!\,\,\!\!\!\,\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\!\!\,\,\,\!\!\,\,\!\!\,\,\,\!\!\,\,\,\!\!\,\!\,\,\,\!\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\,\!\,\,\,\!\!\, 
$$  

记$D=\{(x\,,y)\mid4x^{2}+y^{2}\leqslant1,x\geqslant0,y\geqslant0\}$ ,则 $\Sigma\,_{:}\,z=\sqrt{1-4x^{\,2}-y^{\,2}}\,,(x\,,y)\in\,{\cal D}.$ 因为 $\pmb{\Sigma}$ 上侧为正，所以  

$$
\begin{array}{r l}&{I=\biggr\iint_{D}\left(2x\,\sqrt{1-4x^{\,2}-y^{\,2}}\,\,\frac{\partial z}{\partial x}+1-4x^{\,2}-y^{\,2}\right)\mathrm{d}x\,\mathrm{d}y}\\ &{\quad=\biggr\iint_{D}(1-12x^{\,2}-y^{\,2})\mathrm{d}x\mathrm{d}y.}\end{array}
$$  

由例14.10知， $I=\!\!\!\int_{\stackrel{D}{D}}(1-12x^{2}-y^{2}\,)\,\mathrm{d}x\mathrm{d}y=0.$  

#  $\circledcirc$ 换路径再计算.（若rot ${\pmb F}={\pmb0}$ （无旋场），可换路径）  

设 $\pmb{F}=P i+Q j+R\pmb{k}$ ，其中 ${\cal P}\,,{\cal Q}\,,{\cal R}$ 具有一阶连续偏导数.若rot ${\pmb F}={\pmb0}$ ，则可换路径积分.  

[注)“四 2(2) 的 $\circledcirc$  $\textcircled{3}"$ 与“四 2(4) 的 $\circledcirc$ ”为什么可以换路径？平面上的 $\frac{\partial Q}{\partial x}\equiv\frac{\partial P}{\partial y}$ 与空间上的rot $\pmb{F}=0$ ，均是指所给场无旋，无旋场中积分与路径无关，于是可“换路径”.为什么无旋场积分与路径无关呢？可以这样理解并记忆:在重力场中,你手上拿着一个风车,若只有重力作用，风车是不会旋转的，这就是“无旋”，重力场是无旋场，重力场中做功与路径无关，这样通俗理解就容易记住了.  

例18.23设 $\boldsymbol{r}$ 是圆柱螺线 $\scriptstyle x\;=\;\cos\;\theta\;,y\;=\;\sin\;\theta\;,z\;=\theta$ ,从点A(1,0,0)到点 $B(1,0,2\pi)$ ，则$J=\int_{r}(x^{2}-y z)\mathrm{d}x+(y^{2}-z x\,)\mathrm{d}y+(z^{2}-x y\,)\mathrm{d}z={\cfrac{\cdot}{\mathrm{~\textit~{~\,~}~}}}.$ 【解】应填 ${\frac{8}{3}}\pi^{3}$  

由于  

$$
\left|\begin{array}{c c c}{{i}}&{{j}}&{{k}}\\ {{\displaystyle\frac{\partial}{\partial x}}}&{{\displaystyle\frac{\partial}{\partial y}}}&{{\displaystyle\frac{\partial}{\partial z}}}\\ {{x^{\,2}-y z}}&{{y^{\,2}-z x}}&{{z^{\,2}-x y}}\end{array}\right|={\bf0}\,,
$$  

因此全空间内曲线积分与路径无关，将 $\boldsymbol{r}$ 换为直线段 $\overline{{A B}}\,{:}\,x=1,y=0\,,z$ 从0到 $2\pi$ ，则  

$$
J=\!\int_{{\overline{{A B}}}}\!z^{2}\,\mathrm{d}z=\!\int_{\,0}^{2\pi}\!z^{2}\,\mathrm{d}z={\overline{{\frac{8}{3}}}}\pi^{3}.
$$  
# 五第二型曲面积分  

# 1. 概念通量  

第二型曲面积分的被积函数 ${\cal F}(x\,,y\,,z\,)={\cal P}(z\,,y\,,z\,)i+{\cal Q}(x\,,y\,,z\,)j+{\cal R}(x\,,y\,,z\,)k$ 定义在光滑的空间有向曲面 $\boldsymbol{\Sigma}$ 上,其物理背景是向量函数 $\scriptstyle{\cal{F}}({\it{x}}\cdot{\mathrm{y}}\,,z\,)$ 通过曲面 $\boldsymbol{\Sigma}$ 的通量：  

$$
\underset{\Sigma}{\iint}P(x\,,y\,,z\,)\ensuremath{\mathrm{d}}y\,\ensuremath{\mathrm{d}}z+Q(x\,,y\,,z\,)\ensuremath{\mathrm{d}}z\,\ensuremath{\mathrm{d}}x\,+R(x\,,y\,,z\,)\ensuremath{\mathrm{d}}x\,\ensuremath{\mathrm{d}}y.
$$  

由此可以看出，第二型曲面积分是一个向量函数通过某有向曲面的通量（无几何量可言），要加强和前面所学积分的横向对比，理解它们的区别和联系，不要用错或者用混了.  

$$
\iint_{\frac{1}{z}}(P\,,Q\,,R)\,\bullet\,(\mathrm{d}y\,\mathrm{d}z\,,\mathrm{d}z\,\mathrm{d}x\,\,,\mathrm{d}x\,\mathrm{d}y\,)=\!\!\!\!\!\!\iint_{\frac{1}{z}}\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\mathrm{d}y\,\mathrm{d}z+Q\,\mathrm{d}z\,\mathrm{d}x\,+R\,\mathrm{d}x\,\mathrm{d}y.
$$  

# 2.计算  

(1）基本方法一一投二代三计算(化为二重积分).  

$\textcircled{1}$ 拆成三个积分（如果有的话），一个一个做：  

$$
\begin{array}{r l}&{\quad\displaystyle\iint_{\mathbb{\Sigma}}P(\boldsymbol{x}\,,\boldsymbol{y}\,,\boldsymbol{z})\,{\mathrm{d}}\boldsymbol{y}\,{\mathrm{d}}\boldsymbol{z}+Q(\boldsymbol{x}\,,\boldsymbol{y}\,,\boldsymbol{z})\,{\mathrm{d}}\boldsymbol{z}\,{\mathrm{d}}\boldsymbol{x}+R(\boldsymbol{x}\,,\boldsymbol{y}\,,\boldsymbol{z})\,{\mathrm{d}}\boldsymbol{x}\,{\mathrm{d}}\boldsymbol{y}}\\ &{=\displaystyle\iint_{\mathbb{\Sigma}}P(\boldsymbol{x}\,,\boldsymbol{y}\,,\boldsymbol{z})\,{\mathrm{d}}\boldsymbol{y}\,{\mathrm{d}}\boldsymbol{z}+\displaystyle\iint_{\mathbb{\Sigma}}Q(\boldsymbol{x}\,,\boldsymbol{y}\,,\boldsymbol{z})\,{\mathrm{d}}\boldsymbol{z}\,{\mathrm{d}}\boldsymbol{x}+\displaystyle\iint_{\mathbb{\Sigma}}R(\boldsymbol{x}\,,\boldsymbol{y}\,,\boldsymbol{z})\,{\mathrm{d}}\boldsymbol{x}{\mathrm{d}}\boldsymbol{y}\,.}\end{array}
$$  

$\circledcirc$ 分别投影到相应的坐标面上.  

例如对于 $\iint_{\Sigma}^{}\!\!\!\!\!\!\!\!\!\!\!\!\int_{R}^{}(\chi\,,y\,,z\,)\,\mathrm{d}x\mathrm{d}y$ ,将曲面 $\boldsymbol{\Sigma}$ 投影到 $x\,O y$ 平面上去.  

a.若 $\pmb{\Sigma}$ 在 $_{x}O y$ 平面上的投影为一条线，即 $\pmb{\Sigma}$ 垂直于 $_{x O y}$ 平面，则此积分为零，  

b.若不是“a”的情形，且 $\boldsymbol{\Sigma}$ 上存在两点，它们在 $_{x}O y$ 平面上的投影点重合，则应将 $\pmb{\Sigma}$ 剖分成若干个曲面片，使对于每一曲面片上的点投影到 $_{x}O y$ 平面上的投影点不重合.  

c.假设已如此剖分好了，不妨将剖分之后的曲面片仍记为 $\boldsymbol{\Sigma}$ .此时将 $\boldsymbol{\Sigma}$ 的方程写成 $_z=$  $z\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ 的形式(只有投影到 $_{x}O y$ 平面上投影点不重合时， $\boldsymbol{\Sigma}$ 的方程才能写成 $z=z\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right).$  

$\textcircled{3}$ 一投二代三计算.  

a.一投：确定出 $\boldsymbol{\Sigma}$ 在 $x\,O y$ 平面上的投影域 $D_{x y}$ b.二代：将 $z=z\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ 代人 $R\left(\,x\,,y\,,z\,\right)$ ：c.三计算：将dxdy写成 $\pm\deg\deg\boldsymbol{y}$ .其中“ $\pm$ ”号是这样选取的：  

当cos $\gamma>0$ ，即 $\boldsymbol{\Sigma}$ 的法向量与 $_z$ 轴交角为锐角,亦即当 $\pmb{\Sigma}$ 的指定侧为上侧时，取“ $+^{\bullet}$  

当cos $\gamma<0$ ,即 $\Sigma$ 的法向量与 $_z$ 轴交角为钝角,亦即当 $\Sigma$ 的指定侧为下侧时，取“-”于是便得  

$$
\iint_{\Sigma}R\left(\boldsymbol{x}\,,y\,,z\right)\mathrm{d}x\,\mathrm{d}y=\pm\iint_{\Sigma_{x y}}R\left[\boldsymbol{x}\,,y\,,z(\boldsymbol{x}\,,y\,)\right]\mathrm{d}x\,\mathrm{d}y.
$$  
【注】必须注意,上式等号左边是第二型曲面积分， $\iint_{\Sigma}$ 表明了这件事,其中 drdy 为有向曲面微元在 $x\,O y$ 平面上的投影分量;等式右边是 $_{x O y}$ 平面上的二重积分, $\iint_{p_{x y}}\mathrm{~d~}p_{x z}=\rho_{y z}\mathrm{~d~}p_{x y}$ 表明了这件事,其中dordy 为二重积分的面积微元, $R$ 中的 $_z$ 已用 $\pmb{\Sigma}$ 的方程 $_{z}=_{z}(x,y)$ 代入了，它是 $x\cdot y$ 的函数.两个 dxdy 虽然写法一样,但其意义不一样.  

对于其他两个第二型曲面积分的计算类似,请读者参照“ $\circledcirc$  $\textcircled{3}$ ”两条自行写出。  

$\circledast$ 计算已转化成的二重积分.  

例 18. 24设直线 $L$ 过点 $A\left(-1,0,1\right)$ 与 $B\left(0,0,0\right),L$ 绕 $_z$ 轴旋转一周得曲面 $\scriptstyle\sum_{\circ}$ ,计算 $I=$  $\frac{\mathbf{e}^{z}}{\sqrt{x^{\,2}+y^{\,2}}}\mathrm{d}x\,\mathrm{d}y$ ,其中 $\Sigma$ 是由 $\Sigma_{\scriptscriptstyle0}\,,z=1\,,z=2$ 所围有界闭区域的边界曲面，取外侧.  

解】直线 $L$ 的两点式方程为  

$$
{\frac{x+1}{1}}={\frac{y}{0}}={\frac{z-1}{-1}},
$$  

可得其参数方程为  

$$
\begin{array}{r}{\left\{x=-1+t\,,\right.}\\ {\left.\psi=0\,,\right.}\\ {z=1-t\,,\right.}\end{array}
$$  

$|\!\!\begin{array}{c}{{x=-\,z\,,}}\\ {{y=0.}}\end{array}\!\!$  

由第17讲六中的注，有 $\scriptstyle\sum_{0}$ 的方程为 $x^{2}+y^{2}=z^{2}+0=z^{2}$ 如图18-28所示,记 $\Sigma=\Sigma_{1}+\Sigma_{2}+\Sigma_{3}$ ,其中 $\Sigma_{1}:z=1,x^{2}+y^{2}\leqslant1$ $\Sigma_{\scriptscriptstyle2\;:}z=2,x^{\scriptscriptstyle2}+y^{\scriptscriptstyle2}\leqslant4\,;\Sigma_{\scriptscriptstyle3\;:}z=\sqrt{x^{\scriptscriptstyle2}+y^{\scriptscriptstyle2}}\,,1\leqslant z\leqslant2$ 则  

$$
I=\oiint_{z}=\iint_{z_{1}}+\iint_{z_{2}}+\iint_{z_{3}},
$$  

$$
\iint_{\Sigma_{1}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int\displaylimits_{\Sigma_{1}}\;\!\!\!\!\!\!\!\!\!\!-\iint\displaylimits_{\Sigma_{1}}\frac{\mathrm{e}^{1}}{\sqrt{x^{2}+y^{2}}}\mathrm{d}x\,\mathrm{d}y=-\,\mathrm{e}\!\!\int\displaylimits_{0}^{2\pi}\!\mathrm{d}\theta{\int\displaylimits_{0}^{1}\frac{1}{r}\,\cdot\,r\,\mathrm{d}r}=-\,2\pi\mathrm{e}\,,
$$  

$$
\iint_{\Sigma_{2}}\!\!\!\!\!\int_{D_{2}}\!\!\!\!\!\int_{\Sigma}\!\frac{{\mathrm{e}}^{2}}{\sqrt{x^{2}+y^{2}}}{\mathrm{d}}x\,{\mathrm{d}}y={\mathrm{e}}^{2}\!\!\int_{0}^{2\pi}\!\mathrm{d}\theta{\!\!\int_{\,0}^{2}\,{\frac{1}{r}}\cdot r\,{\mathrm{d}}r}=4\pi{\mathrm{e}}^{2}\,,
$$  

$$
\iint_{\Sigma_{3}}-\iint_{\Sigma_{3}}\frac{\mathrm{e}^{\sqrt{x^{2}+y^{2}}}}{\sqrt{x^{2}+y^{2}}}\mathrm{d}x\,\mathrm{d}y=-\!\int_{0}^{2\pi}\!\mathrm{d}\theta\!\!\int_{1}^{2}\frac{\mathrm{e}^{r}}{r}\cdot r\,\mathrm{d}r=-\,2\pi(\mathrm{e}^{2}-\mathrm{e})\,,
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/dda90b6a3d50265e6c2c6a67a37b762eaa30e60e00c0b88506c99549351634d1.jpg)  
图18-28  

其中 $D_{1}\!=\!\{\,(x\,,y\,)\mid x^{2}+y^{2}\!\leqslant\!1\,\}\,,D_{2}\!=\!\{\,(x\,,y\,)\mid x^{2}+y^{2}\!\leqslant\!4\,\}\,,D_{3}\!=\!\{\,(x\,,y\,)\}\,.$ )|1≤x²+y²≤$43$ .故 $I=-\,2\uppi\mathrm{e}+4\uppi\mathrm{e}^{2}-2\uppi(\mathrm{e}^{2}-\mathrm{e})=2\uppi\mathrm{e}^{2}$  
阳亨高等数学18讲  

# （2）转换投影法.  

若 $\boldsymbol{\Sigma}$ 投影到 $x O y$ 平面上不是一条线，并且 $\Sigma$ 上任意两点到 $x O y$ 平面上的投影点不重合，则可将 $\boldsymbol{z}$ 投影到 $_{x O y}$ 平面，设投影域为 $D_{\scriptscriptstyle\textsl{x y}}$ ，曲面方程写成 $z=z\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ 的形式，则有  

$\begin{array}{r l}&{\quad\displaystyle\iint_{\mathbb{Z}}P\left(x\,,y\,,z\,\right)\!\mathrm{d}y\,\mathrm{d}z+Q(x\,,y\,,z\,)\,\mathrm{d}z\,\mathrm{d}x+R(x\,,y\,,z\,)\,\mathrm{d}\mathrm{ad}y}\\ &{=\pm\displaystyle\iint_{b_{x}}\left\lbrace P\left[x\,,y\,,z\left(x\,,y\right)\right]\!\left(-\frac{\partial z}{\partial x}\right)\!+Q\!\left[x\,,y\,,z\left(x\,,y\right)\right]\!\left(-\frac{\partial z}{\partial y}\right)\!+R\left[x\,,y\,,z\left(x\,,y\right)\right]\!\right\rbrace}\end{array}$ ) drdy, 其中“ $\pm$ ”的选取与“（1)”所述相同.当 $\scriptstyle{\sum}$ 为上侧时.取“ $^{+}$ ”当 $\boldsymbol{\Sigma}$ 为下侧时.取“一”  

类似地,若 $\boldsymbol{\Sigma}$ 投影到 $y O z$ 平面上不是一条线，并且 $\Sigma$ 上任意两点到 $y O z$ 平面上的投影点不$D_{y z}$ $x=x\,(\,y\,,z\,)$  

重合,投影域为,曲面方程写成的形式,则有$\begin{array}{r l}&{\quad\displaystyle\iint_{\mathbb T}(x\,,y\,,z)\,{\mathrm{d}}y\,{\mathrm{d}}z+Q(x\,,y\,,z)\,{\mathrm{d}}z\,{\mathrm{d}}x+R(x\,,y\,,z)\,{\mathrm{d}}x{\mathrm{d}}y}\\ &{=\pm\displaystyle\iint_{\mathbb N_{\mathrm{w}}}\Bigl\{P\bigl[x\,(y\,,z)\,,y\,,z\bigr]+Q\bigl[x(\,y\,,z\,)\,,y\,,z\bigr]\Bigl(-\frac{\partial x}{\partial y}\Bigr)+R\bigl[x(\,y\,,z\,)\,,y\,,z\bigr]\Bigl(-\frac{\partial x}{\partial z}\Bigr)}\end{array}$ dydz,   
其中，当 $\Sigma$ 为前侧时取“ $+^{\bullet}$ ；当 $\Sigma$ 为后侧时取“-”  

若 $\boldsymbol{\Sigma}$ 投影到 ${\mathfrak{z}}O x$ 平面上不是一条线，并且 $\Sigma$ 上任意两点到 $z O x$ 平面上的投影点不重合，投影域为 $D_{\ast\boldsymbol{\tau}}$ ,曲面方程写成 $y=y\left(z\,,x\,\right)$ 的形式，则有$\begin{array}{r l}&{\quad\displaystyle\iint_{\mathbb T}(x\,,y\,,z)\,{\mathrm{d}}y\,{\mathrm{d}}z+Q(x\,,y\,,z)\,{\mathrm{d}}z\,{\mathrm{d}}x+R(x\,,y\,,z)\,{\mathrm{d}}x{\mathrm{d}}y}\\ &{=\pm\displaystyle\iint_{v_{\tau}}\Bigl\langle P\bigl[x\,,y(z\,,x)\,,z\bigr]\Bigl(-\frac{\partial y}{\partial x}\Bigr)+Q\bigl[x\,,y(z\,,x)\,,z\Bigr]+R\bigl[x\,,y(z\,,x)\,,z\bigr]\Bigl(-\frac{\partial y}{\partial z}\Bigr)}\end{array}$ Ldedr, 其中,当 $\Sigma$ 为右侧时取“ $+^{\bullet}$ ;当 $\Sigma$ 为左侧时取“-”  

【注】上述公式,例如其中第1个,若 $\boldsymbol{\Sigma}$ 的一部分 $\Sigma_{1}$ 垂直于 $_{x O y}$ 平面，则 $\pmb{\Sigma}_{1}$ 到 $_{x O y}$ 平面上的投影为一条线，此时 $\Sigma_{1}$ 的方程不能写成 $z=z\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ 的形式，故无法用这个公式计算 $\Sigma_{1}$ 上的第二型曲面积分.对此 $\Sigma_{1}$ 应改投到其他坐标面上计算，或用“（1）”的方法分成若干个积分计算.  

例 18.25设 $\boldsymbol{\Sigma}$ 为曲面 $z=\sqrt{x^{\,2}+y^{\,2}}\,(1\leqslant x^{\,2}+y^{\,2}\leqslant4)$ 的下侧， $f(x)$ 是连续函数,计算 $I=\!\!\!\iint_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\int_{\frac{1}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! $ 以【解】曲面 $\Sigma$  $_{x}O y$ 平面上的投影域为 $D=\{(x\,,y\,)\;\mid\;1\leqslant x^{\,2}+y^{\,2}\leqslant4\}$ 因为 $\frac{\partial\boldsymbol{z}}{\partial\boldsymbol{x}}=$  ${\frac{x}{\sqrt{x^{\,2}+y^{\,2}}}},{\frac{\partial z}{\partial y}}={\frac{y}{\sqrt{x^{\,2}+y^{\,2}}}}$ ，且 $\Sigma$ 取下侧，所以$\begin{array}{r l}&{I=\!\!\!\!\!\!\int_{0}^{\infty}\!\!\!\!\!\!\Big[\chi\,f(x y)+2x-y\Big]{\mathrm{d}}y\,{\mathrm{d}}z+\big[y\,f(x y)+2y+x\,\big]{\mathrm{d}}z\,{\mathrm{d}}x+\big[z\,f(x y)+z\big]{\mathrm{d}}x}\\ &{\quad=-\!\!\!\!\!\int_{0}^{\infty}\!\!\!\!\!\Big\{-\frac{x}{\sqrt{x^{\,2}+y^{\,2}}}\big[x\,f(x y)+2x-y\big]-\frac{y}{\sqrt{x^{\,2}+y^{\,2}}}\big[y\,f(x y)+2y+x\big]+}\end{array}$ dy  
$$
\begin{array}{r l}&{\mathrel{\phantom{=}}\left[f(x y)+1\right]\sqrt{x^{2}+y^{2}}\,\Biggr\}\,\mathrm{d}x\mathrm{d}y}\\ &{=\biggr\Updownarrow\!\!\int_{0}^{\infty}\!\!\!\!\int_{0}^{\infty}\!\!\!\!\!\int_{0}^{\infty}\!\!\!\!\!\!\int_{0}^{\infty}\!\!\!\!\!\!\int_{0}^{\infty}\!\!\!\!\!\!\int_{\mathbb{Z}}\mathrm{d}x\mathrm{d}y}\\ &{=\int_{0}^{\infty}\!\!\!\!\!\mathrm{d}\theta\int_{1}^{2}r^{2}\mathrm{d}r}\\ &{=\frac{14\pi}{3}.}\end{array}
$$  

# (3）高斯公式.  

设空间有界闭区域 $\Omega$ 由有向分片光滑闭曲面 $\Sigma$ 围成， $P(x\,,y\,,z)\,,Q(x\,,y\,,z\,)\,,R\,(x\,,y\,,z\,)$ 在 $\Omega$ 上具有一阶连续偏导数,其中 $\scriptstyle{\Sigma}$ 取外侧，则有公式  

$$
\iint_{\Sigma}P\,\mathrm{d}y\,\mathrm{d}z+Q\,\mathrm{d}z\,\mathrm{d}x\,+R\,\mathrm{d}x\,\mathrm{d}y=\iint_{\partial\Sigma}\left({\frac{\partial P}{\partial x}}+{\frac{\partial Q}{\partial y}}+{\frac{\partial R}{\partial z}}\right)\mathrm{d}v.
$$  

#  $\textcircled{1}$ 封闭曲面且内部无奇点，直接用高斯公式。  

例 18.26计算  

$$
I=\oiint_{\Sigma}\mid x\,y\,\mid\,z^{2}\,\mathrm{d}x\,\mathrm{d}y+\mid x\,\mid\,y^{2}\,z\,\mathrm{d}y\,\mathrm{d}z\,,
$$  

其中 $\boldsymbol{\Sigma}$ 为 $z=x^{2}+y^{2}$ 与 $z=1$ 所围区域 $\Omega$ 的表面，方向向外.  

【解】由题,如图18-29所示,则  

$$
\begin{array}{r l}{\frac{\partial\mathbb{E}}{\partial t}\mathbb{H},I=\displaystyle\frac{\iint}{\frac{\partial\mathbf{v}}{\partial t}}\mid\boldsymbol{x}\boldsymbol{y}\mid\boldsymbol{z}^{2}\,\mathrm{d}\boldsymbol{x}\mathrm{d}\boldsymbol{y}+\displaystyle\frac{\bigoplus}{2}\mid\boldsymbol{x}\mid\boldsymbol{y}^{2}\,\mathrm{z}\mathrm{d}\boldsymbol{y}\mathrm{d}\boldsymbol{z}\frac{\mathrm{~i\delta\boldsymbol{z}~}}{r}I_{1}+I_{z}}\\ {I_{1}\xrightarrow[\delta\hat{\mathcal{H}}]{\mathcal{H}}}&{\Bigg[\frac{\partial\boldsymbol{y}}{\partial t}}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/4bbfbdc730c1459986bbdca7183e3121eaf5fb511e8d9d04def3ec8193d5dfe9.jpg)  
图18-29  

故  

$I_{2}$ 不能用高斯公式,因 ${\frac{\partial}{\partial x}}(\mid x\mid y^{2}z)$ 在 ${\boldsymbol x}=0$ 处不存在.将 $\scriptstyle{\Sigma}$ 分成两块  

$$
\begin{array}{c}{\displaystyle\iint\mid x\mid\,y^{2}\,z\,{\mathrm d}y\,{\mathrm d}z=0\,,}\\ {\displaystyle\iint\mid x\mid\,y^{2}\,z\,{\mathrm d}y\,{\mathrm d}z\;\frac{\#\varepsilon\,{\mathrm d}\hat{\varepsilon}}{\Im\Re\xi\pm\displaystyle\int_{z}^{}}\left\{\begin{array}{c}{\displaystyle1\;,}\\ {\displaystyle x}\end{array}\right.\,\mid\,y^{2}\,z\left(-\,\frac{\partial z}{\partial x}\right){\mathrm d}x{\mathrm d}y}\end{array}
$$  
$$
=-\iint_{x^{2}+y^{2}\leqslant1}\mid x\mid y^{2}(x^{2}+y^{2})\bullet(-\,2x\,)\,\mathrm{d}x\mathrm{d}y=0.
$$  

故$I={\frac{1}{4}}.$  

$\circledcirc$ 封闭曲面、有奇点在其内部，且除奇点外div $\pmb{F}=~0$ ,可换个面积分.(边界无需与原曲面重合）  

【注】为什么可以换个面积分？div ${\pmb F}\!=\!0$ 是指所给场无源，于是通过任何封闭曲面（且无奇点在其内部）的通量为0.如图18-30所示，由于 $\iint_{\Sigma+\Sigma_{1}^{-}}=0$ ，于是 $\iint_{\Sigma}=-\iint_{\Sigma_{1}^{-}}=\iint_{\Sigma_{1}}(\Sigma)$ 与 $\Sigma_{1}$ 同向)。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/2f15fff187f4b67ccb0f9c12fa8490ff8626e39d58cfaceb06473a483aea659f.jpg)  
图18-30  

有时虽然所给的曲面是一张封闭曲面，法向量指的也是外侧，但“在 $\Sigma$ 所包围的有界闭区域 $\Omega$ 的内部有奇点,但除奇点外 ${\cal P}\,,{\cal Q}\,,{\cal R}$ 具有连续的一阶偏导数,且满足 $\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z}\equiv0^{\ast}$ .此时，可以作一封闭曲面 $\Sigma_{1}\subset\Omega$ ，将上述使偏导数不连续的点都包含在 $\boldsymbol{\Sigma}_{1}$ 的内部， $\Sigma_{1}$ 的法向量指向它所包围的有界区域的外侧，则有公式  

$$
\oiint_{\Sigma}P\,\mathrm{d}y\,\mathrm{d}z+Q\mathrm{d}z\,\mathrm{d}x+R\,\mathrm{d}x\,\mathrm{d}y=\oiint_{\Sigma_{1}}P\,\mathrm{d}y\,\mathrm{d}z+Q\mathrm{d}z\,\mathrm{d}x\,+R\,\mathrm{d}x\,\mathrm{d}y.
$$  

如果后一积分比前一积分容易计算，就达到化难为易的目的了，  

例18.27 设$\Sigma$ 是椭球面 ${\frac{x^{2}}{a^{2}}}+{\frac{y^{2}}{b^{2}}}+{\frac{z^{2}}{c^{2}}}=1$ ，法向量指向外侧，则 $\oint_{\Sigma}{\frac{x\,{\mathrm{d}}y\,{\mathrm{d}}z+y\,{\mathrm{d}}z\,{\mathrm{d}}x+z\,{\mathrm{d}}x\,{\mathrm{d}}y}{(x^{\,2}+y^{\,2}+z^{\,2})^{3/2}}}={\cfrac{\cdot}{\mathrm{~\hbar~}}}.$ $4\pi$  

经计算有  

但是这里不能用高斯公式，因为在 $\Sigma$ 内部的点 $O(0,0,0)$ 处， $P\,,Q\,,R$ 都不连续.故在 $\boldsymbol{\Sigma}$ 内部作一球面  

$$
\Sigma_{1}:\!x^{\,2}+y^{\,2}+z^{\,2}=r^{2}\,(r>0)\,,
$$  

它的法向量指向球面外侧，于是有  

$$
\begin{array}{r l}&{\quad\oint_{\frac{\pi}{2}}\frac{x\,\mathrm{d}y\,\mathrm{d}z+y\,\mathrm{d}z\,\mathrm{d}x+z\,\mathrm{d}x\,\mathrm{d}y}{(x^{\,2}+y^{\,2}+z^{\,2})^{3/2}}}\\ &{=\oint_{\frac{\pi}{2}}\frac{x\,\mathrm{d}y\,\mathrm{d}z+y\,\mathrm{d}z\,\mathrm{d}x+z\,\mathrm{d}x\,\mathrm{d}y}{(x^{\,2}+y^{\,2}+z^{\,2})^{3/2}}}\\ &{=\displaystyle\frac{1}{r^{\,3}}\!\!\oint_{\frac{\pi}{2}}\!\!\mathrm{d}y\,\mathrm{d}z+y\,\mathrm{d}z\,\mathrm{d}x+z\,\mathrm{d}x\mathrm{d}y}\end{array}
$$  
$$
{\frac{\mathit{\Omega}({\bf\mu}\ast{\bf\Lambda})}{r^{3}}}{\frac{\mathrm{\Large1}}{a_{1}}}{\mathrm{\Large\iint}}3{\mathrm{d}}v={\frac{1}{r^{3}}}\cdot3\cdot{\frac{4}{3}}\pi r^{3}=4\pi\,,
$$  

其中（\*）处来自高斯公式， $\Omega_{1}$ 为 $\Sigma_{1}$ 所包围的闭球域  

$\textcircled{3}$ 非封闭曲面，且div $\boldsymbol{F}=0$ ，可换个面积分.（边界需与原曲面重合）  

【注】为什么可以换个面积分？div $\pmb{F}=0$ 是指所给场无源，于是通过任何封闭曲面（且无奇点在其内部）的通量为0，如图18-31所示.由于 $\iint_{_{!}^{+}}=0$ 于是 $\iint_{\Sigma_{1}}\iint_{\Sigma_{2}}\iiint_{\Sigma_{1}}(\Sigma_{1}\$ 与 $\Sigma_{2}^{-}$ 同向）。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/28879ff850da0424d92b690ebd01cf65350096b8a5475a4975d6b1bffe680b64.jpg)  
图18-31  

例 18. 28设 $\boldsymbol{\Sigma}$ 为锥面 $z=\sqrt{x^{2}+y^{2}}\,(0\leqslant z\leqslant H)$ 的下侧，则 $\iint_{\Sigma}\!\!\!\mathrm{d}y\,\mathrm{d}z+2\mathrm{d}z\,\mathrm{d}x+3\mathrm{d}x\mathrm{d}y=$  

【解】应填- $-\,3\pi H^{2}$  $\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z}\!=\!0$ ,无源场，换面为 $\boldsymbol{\Sigma}_{1}$  $:z=H\,(x^{2}+y^{2}\leqslant H^{2})$ 的下侧（见图18-32）.  

$\circled{4}$ 非封闭曲面，且div $\pmb{F}\neq0$ ,补面使其封闭(加面减面）.  

若 $\boldsymbol{\Sigma}$ 不是封闭曲面，但是如果补上一张曲面 $\Sigma_{1}$ 并配以相应的方向，使得 $\Sigma\cup\Sigma_{1}$ 成为封闭曲面，其法向量指向外侧，并且 ${\cal P}\,\langle{\sf Q}\,,{\cal R}$ 在 $\Sigma\cup\Sigma_{1}$ 所包围的有界闭区域 $\Omega$ 上连续且有连续的一阶偏导数，则  

$$
\begin{array}{r l}&{\quad\underset{\b{\Sigma}}{\iint}P\,\mathrm{d}y\,\mathrm{d}z+Q\,\mathrm{d}z\,\mathrm{d}x\,+R\,\mathrm{d}x\mathrm{d}y}\\ &{\quad\quad=\underset{\b{\Sigma}}{\iint}+\underset{\b{\Sigma_{1}}}{\iint}-\underset{\b{\Sigma_{1}}}{\iint}}\\ &{\quad\quad=\underset{\b{a}}{\iint}\left(\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z}\right)\mathrm{d}v-\underset{\b{\Sigma_{1}}}{\iint}P\,\mathrm{d}y\,\mathrm{d}z+Q\,\mathrm{d}z\,\mathrm{d}x\,+R\,\mathrm{d}x\mathrm{d}y\,.}\end{array}
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/5c311898cdcd0f751e8bcce72293de6b7b4f104d4be68bccf9455fde403d0484.jpg)  
图18-32  

如果容易计算的话，就达到化难为易的目的了.  

例 18. 29设 $\Sigma$ 是 $z=2\mathrm{-}x^{2}\mathrm{-}y^{2}$ 在 $x\geqslant0$ 部分的上侧,计算 $I\!=\!\!\!\!\iint_{\Sigma}\frac{x\,\mathrm{d}y\,\mathrm{d}z+y\,\mathrm{d}z\,\mathrm{d}x+z\,\mathrm{d}x\,\mathrm{d}y}{\left(x^{\,2}+y^{\,2}+z^{\,2}\right)^{\frac{3}{2}}}.$  

【解】设 $r=\sqrt{x^{2}+y^{2}+z^{2}}\,,P=\frac{x}{r^{3}},Q=\frac{y}{r^{3}},R=\frac{z}{r^{3}},\frac{\partial P}{\partial x}=\frac{r^{3}-3x r^{2}\cdot\frac{x}{r}}{r^{6}}=\frac{1}{r^{3}}-\frac{3x^{2}}{r^{5}}.$ 同理 $\frac{\partial Q}{\partial y}=\frac{1}{r^{3}}-\frac{3y^{2}}{r^{5}},\frac{\partial R}{\partial z}=\frac{1}{r^{3}}-\frac{3z^{2}}{r^{5}}$  $\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+\frac{\partial R}{\partial z}=0,$  
# 比宁高等数学18讲  

作上半球面 $\Sigma_{\rho}:z=\sqrt{\rho^{2}-x^{2}-y^{2}}\,(\rho>0)$ ，方向向下， $\rho$ 充分小使得 $\Sigma_{\rho}$ 在 $\Sigma$ 的内部,再补一平面  

$$
\begin{array}{r}{\Sigma_{\,0}\!:\!z=0\,,\rho^{2}\leqslant x^{\,2}+y^{\,2}\leqslant2\,,}\end{array}
$$  

方向向下，设由 $\Sigma\,\{\Sigma_{\rho}\}$ 和 $\scriptstyle\sum_{\circ}$ 共同围成的立体区域记为 $\Omega$ ，如图18-33所示，则  

$$
I=\iint_{\Sigma}=\underset{z+\Sigma_{\rho}+z_{0}}{\iint}-\underset{z_{\rho}}{\iint}-\underset{z_{0}}{\iint}.
$$  

由高斯公式,第一项为0,对于第二项，将 $\Sigma_{\rho}$ 的方程代人被积函数分母中，得  

$$
\iint_{\Sigma_{\rho}}\!\!\!\!\!\!\!\int_{\,}\!\!\!\!\!\!\!\rho_{\phantom{3}\Sigma_{\rho}}^{\phantom{3}}\!\!\!\!\!\int_{\Sigma_{\rho}}\!\!\!\!\!\!\int_{\,}\!\!\!\!\!\!x\,\mathrm{d}y\,\mathrm{d}z+y\,\mathrm{d}z\,\mathrm{d}x+z\,\mathrm{d}x\,\mathrm{d}y\,.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/10b56494ce1cc120c1fb4837f133e70e0917a5bd8e0d0941dd6f2a304bbe72e8.jpg)  
图18-33  

补 $\boldsymbol{\Sigma}_{1}$  $:z=0\,,x^{2}+y^{2}\leqslant\rho^{2}$ ,方向向上，则  

$$
\begin{array}{l}{\displaystyle\iint_{z_{\rho}}\!\!\!\!\!\!=\!\frac{1}{\rho^{3}}\!\left(\underbrace{\!\!\!\{\bf\{\widehat{f}\}\!\!\}}_{z_{\rho}+\Sigma_{1}}-\!\!\!\!\!\int_{z_{1}}\!\!\!\!\!\right)\!\!=\!\frac{1}{\rho^{3}}\!\left(\!\!\!-\underbrace{\!\!\!\prod_{a_{1}}\!\!\!\!\!3\,\mathrm{d}\nu}_{a_{1}}-0\right)\!=\!-\frac{3}{\rho^{3}}\cdot\frac{2\pi}{3}\cdot\rho^{3}=-\,2\pi\,,}\end{array}
$$  

其中 $\Omega_{1}$ 为 $\Sigma_{\rho}$ 和 $\Sigma_{1}$ 围成的半球体，对于第三项，  

$$
\iint_{\Sigma_{0}}\!\!\!\!\!\!\!\int_{\Sigma_{0}}\!\!\!\!\!\!\!\int_{0}\frac{x\,{\mathrm{d}}y\,{\mathrm{d}}z+y\,{\mathrm{d}}z\,{\mathrm{d}}x+z\,{\mathrm{d}}x\,{\mathrm{d}}y}{\left(x^{\,2}+y^{\,2}+z^{\,2}\,\right)^{\frac{3}{2}}}=0\,,
$$  

故  

$$
I=0-(-\,2\pi)-0=2\pi.
$$  

【注】不能只用 $\begin{array}{r}{\Sigma_{\circ}:z=0}\end{array}$ 封闭 $\pmb{\Sigma}$ ，还必须用 $\Sigma_{\rho}$ 把原点抠除  

$\circled{5}$ 由div $\;\!F=0$ ，建方程求 $f(x)$ 。  

给出一个第二型曲面积分，积分表达式中含有一个连续可微的待定函数 $f(x)$ ，并且已知对于单连通区域 $G$ 内任意封闭曲面，此曲面积分为0，求 $f(x).$ 这可由高斯公式推知在 $G$ 内 $\frac{\partial P}{\partial x}+\frac{\partial Q}{\partial y}+$  $\frac{\partial R}{\partial z}\equiv0$ 由此得到关于 $f(x)$ 的一个微分方程，从而解出 $f(x)$  

例18.30设对于 $x>0$ 半空间内任意的光滑有向闭曲面 $\Sigma$ ，都有  

$$
\oint_{\Sigma}f(x\,)\,\mathrm{d}y\,\mathrm{d}z-x\,y\,f(x\,)\,\mathrm{d}z\,\mathrm{d}x\,-\mathrm{e}^{2x}z\,\mathrm{d}x\,\mathrm{d}y=0\,,
$$  

其中函数 $f(x)$ 在 $(0,+\infty)$ 内具有连续的一阶导数，且 $\operatorname*{lim}_{x\to0^{+}}f(x)=1$ ，求 $f(x)$  

【解】由题设条件和高斯公式，有  

$$
\begin{array}{r}{0=\displaystyle\bigoplus_{z}x\,f(x\,)\,\mathrm{d}y\,\mathrm{d}z-x\,y\,f(x\,)\,\mathrm{d}z\,\mathrm{d}x\,-\mathrm{e}^{2x}\,z\,\mathrm{d}x\,\mathrm{d}y}\\ {=\pm\displaystyle\iint_{a}\left[x\,f^{\prime}(x\,)+f(x\,)-x\,f(x\,)-\mathrm{e}^{2x}\,\right]\,\mathrm{d}v\,,}\end{array}
$$  

其中 $\Omega$ 为 $\boldsymbol{\Sigma}$ 所围的区域， $\boldsymbol{\Sigma}$ 的法向量向外时，取“ $^{+,\bullet},\Sigma$ 的法向量向内时，取“一”.由 $\boldsymbol{\Sigma}$ 的任意性，知  

$$
x f^{\prime}(x\,)+f(x\,)-x\,f(x\,)-\mathrm{e}^{2x}=0\,,x\,>0\,,
$$  
即  

$$
f^{\prime}(x)+\left({\frac{1}{x}}-1\right)f(x)={\frac{1}{x}}\mathrm{e}^{2x}\,,x>0.
$$  

由一阶线性微分方程通解公式，有  

$$
f(x\,)=\mathrm{e}^{\int\left(1-\frac{1}{x}\right)\,\mathrm{d}x}\,\left[\!\!\left[\,\frac{1}{x}\mathrm{e}^{2x}\,\star\mathrm{e}^{\int\left(\frac{1}{x}-1\right)\,\mathrm{d}x}\,\mathrm{d}x+C\right]\!=\!\frac{\mathrm{e}^{x}}{x}(\mathrm{e}^{x}+C).
$$  

由于 $\operatorname*{lim}_{x\to0^{+}}f(x\,)=\operatorname*{lim}_{x\to0^{+}}{\frac{\mathrm{e}^{2x}+C\mathrm{e}^{x}}{x}}=1$ ,故必有 $\operatorname*{lim}_{x\to0^{+}}(\mathrm{e}^{2x}+C\mathrm{e}^{x})=0$ ，从而 $C=-1,$ 于是  

$$
f(x)\!=\!\frac{\mathrm{e}^{x}}{x}(\mathrm{e}^{x}-1)(x>0).
$$  

# （4）两类曲面积分的关系。  

$$
\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\int_{0}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\frac{\pi}{z}}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!
$$  

其中(cos $\pmb{\alpha}$ ,cos $\beta$ ,cos $\gamma$ ）为 $\Sigma$ 在点 $(x,y,z)$ 处与 $\boldsymbol{\Sigma}$ 同侧的单位法向量.  

例 18.31设 $\boldsymbol{\Sigma}$ 为曲面 $z=\sqrt{x^{\,2}+y^{\,2}}\,(1\leqslant x^{\,2}+y^{\,2}\leqslant4)$ 的下侧， $f(x)$ 是连续函数,计算$I=\!\!\!\!\iint_{\Sigma}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!d x\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\Sigma}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!I=\!\!\!\!\!\!\!\!\!\!\!\!\!\!\int_{\Sigma}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\$ tdy.  

【解】此题在例18.25 处用了“转换投影法”,此处用“两类曲面积分的关系”这种方法解决.因为 $\pmb{\Sigma}$ 在点 $(x,y,z)$ 处的正向法向量为 $\frac{1}{\sqrt{x^{\,2}+y^{\,2}+z^{\,2}}}(x\,,y\,,-z\,)$ ，根据第二型曲面积分与第一型曲面积分的关系得  

$$
I=\!\!\!\!\int\!\!\!\!\!\!\int{\frac{1}{z^{2}+y^{2}+z^{2}}}\big[(x^{2}+y^{2}-z^{2})f(x y)+2x^{\,2}+2y^{\,2}-z^{\,2}\big]{\bf d}S.
$$  

又因为 $z^{2}=x^{2}+y^{2}$ ，所以  

$$
I={\frac{\sqrt{2}}{2}}\!\!\int\!\!\!\int\!\sqrt{x^{2}+y^{2}}\,\mathrm{d}S.
$$  

记 $D=\{(x\,,y\,)\,\mid\,1\leqslant x^{\,2}+y^{\,2}\leqslant4\}$ ，又  

$$
\sqrt{\left(\frac{\partial z}{\partial x}\right)^{2}+\left(\frac{\partial z}{\partial y}\right)^{2}+1}=\sqrt{\left(\frac{x}{\sqrt{x^{\,2}+y^{\,2}}}\right)^{2}+\left(\frac{y}{\sqrt{x^{\,2}+y^{\,2}}}\right)^{2}+1}=\sqrt{2}\,,
$$  

所以  

$$
I=\!\!\!\int_{\stackrel{{\cal{S}}}{D}}\!\!\sqrt{x^{\,2}+y^{\,2}}\,\mathrm{d}x\,\mathrm{d}y=\!\!\int_{,\,0}^{2\pi}\!\mathrm{d}\theta{\int_{\,1}^{2}}r^{\,2}\,\mathrm{d}r={\frac{14\pi}{3}}.
$$  

【注 冷令 $F(x\,,y\,,z)=x^{2}+y^{2}-z^{2}$ ，则 $\pmb{n}=(2x\,,2y\,,-\,2z\,)\,,\mid\,\pmb{n}\,\mid=2\,\sqrt{x^{\,2}+y^{\,2}+z^{\,2}}$ ，故$\left(\cos\,\alpha\,,\cos\,\beta\,,\cos\,\gamma\right)=\left({\frac{x}{\sqrt{x^{\,2}+y^{\,2}+z^{\,2}}}},{\frac{y}{\sqrt{x^{\,2}+y^{\,2}+z^{\,2}}}},{\frac{-z}{\sqrt{x^{\,2}+y^{\,2}+z^{\,2}}}}\right).$  
# 六应用  

# 1.长度  

(1）曲杆长度(弧长).  

$$
l=\!\int_{{L}}\!\mathrm{d}s=\!\int_{a}^{b}\sqrt{1+(y_{\,x}^{\prime})^{2}}\,\mathrm{d}x\,.
$$  

# (2)空间曲线长度.  

$$
l=\!\int_{r}\!\mathrm{d}s=\!\int_{a}^{\beta}\sqrt{\big[x^{\prime}(t\,)\big]^{2}+\big[y^{\prime}(t\,)\big]^{2}+\big[z^{\prime}(t\,)\big]^{2}}\,\mathrm{d}t.
$$  

2.面积  

(1）平面面积.  

$$
S=\underset{\b{D}}{\iint}\mathrm{d}\sigma.
$$  

(2) 曲面面积.  

$$
S=\!\!\!\!\int_{\frac{\d S}{\d S}}\!\!\!\!\!\int_{\frac{\d S}{\d S}}\sqrt{1+(z_{\,x}^{\prime})^{2}+(z_{\,y}^{\prime})^{2}}\,\mathrm{d}x\,\mathrm{d}y.
$$  

3.体积  

# (1）曲顶柱体体积.  

曲顶为 $z=z\left(\boldsymbol{\chi}\,,y\,\right),(x\,,y\,)\in D_{x y}$ 的柱体体积  

$$
V=\underset{\stackrel{\scriptstyle D_{x,v}}{D_{x,v}}}{\iint}\mid z\left(x\,\,,y\,\right)\mid\,\mathrm{d}\sigma\,.
$$  

# (2）空间物体体积.  

对于空间物体 $\Omega$ ，其体积计算公式为 $V=\!\!\!\!\underbrace{\prod_{a}}_{a}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!V=\!\!\!\!\!\!\!\!\!\underbrace{\prod_{a}}_{a}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!V=\!\!\!\!\!\!\!\!\!\underbrace{\prod_{a}}_{a}\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!V=\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! $  

#  $^{4,}$ 总质量  

（1）对平面薄片 $D$ ,其面密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ ，则其总质量计算公式为  

$$
m=\iint_{D}\left(\boldsymbol{\chi}\,,y\right)\mathrm{d}\boldsymbol{\sigma}\,.
$$  

（2）对空间物体 $\Omega$ ,其体积密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,\right)$ ,则其总质量计算公式为  

$$
m=\!\!\!\iint_{\!\!\!a}(\chi\,,y\,,z\,)\,\mathrm{d}v.
$$  

（3）对光滑曲杆 $L$ ，其线密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,\right)$ ，则其总质量计算公式为  

$$
m=\int_{L}\rho\left(x\,,y\right)\mathrm{d}s.
$$  
（4）对光滑曲面薄片 $\boldsymbol{\Sigma}$ ，其面密度为 $\rho(x\,,y\,,z)$ ，则其总质量计算公式为  

$$
m=\!\!\!\int_{\frac{\Sigma}{\Sigma}}\!\!\!\!\int_{}^{}\!\!\rho\left(x\,,y\,,z\right)\mathrm{d}S.
$$  

5.重心（质心）与形心  

（1）对平面薄片 $D$ ,其面密度为 $\rho\left(x\,,y\right)$ ,则其重心 $({\overline{{x}}}\,,{\overline{{y}}})$ 的计算公式为  

$$
{\cfrac{\displaystyle\iint_{x\,\rho\,}(x\,,y)\,\mathrm{d}\sigma}{\displaystyle\iint_{D}(x\,,y)\,\mathrm{d}\sigma}},{\cfrac{\displaystyle\iint_{y\,\rho\,}(x\,,y)\,\mathrm{d}\sigma}{\displaystyle\iint_{D}(x\,,y)\,\mathrm{d}\sigma}}.
$$  

注】(1)在考研的范畴内，重心就是质心。  

（2）当密度 $\rho(x\,,y)$ 或者 $\rho(x,y,z)$ 为常数时，重心就成了形心.以下同理，  

（3）由形心公式 ${\overline{{x}}}={\frac{\iint_{x}\mathrm{d}\sigma}{\iint_{D}\mathrm{d}\sigma}}$ 得 $\iint_{D}x d\sigma=\overline{{x}}\cdot\iint_{D}\!\!\!\mathrm{d}\sigma\,.$  

当 $D$ 为规则图形（ $x$ 已知且面积易求），有 $\lceil\int_{D}x\mathrm{d}\sigma=\overline{{\boldsymbol{x}}}\cdot\boldsymbol{S}_{D}$  

在本讲的三重积分、第一型曲线积分、第一型曲面积分处有同样的情形和名称。  

（2）对空间物体 $\Omega$ ,其体积密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\right)$ ,则其重心 $(\overline{{x}},\overline{{y}},\overline{{z}})$ 的计算公式为  

$$
-\,{\frac{\iiint_{x\rho}(x\,,y\,,z)\,\mathrm{d}v}{2}},{\frac{-\iiint_{y\rho}(x\,,y\,,z)\,\mathrm{d}v}{2}},{\frac{-\qquad\iiint_{x\rho}(x\,,y\,,z)\,\mathrm{d}v}{2}}\,,{\frac{-\iiint_{z\rho}(x\,,y\,,z)\,\mathrm{d}v}{2}}\,.
$$  

（3）对光滑曲杆 $L$ ，其线密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\right)$ ，则其重心 $(\overline{{x}},\overline{{y}},\overline{{z}})$ 的计算公式为  

$$
-\cfrac{\displaystyle\int_{L}x\rho\left(x\ ,y\ ,z\right)\mathrm{d}s}{\displaystyle\int_{L}\rho\left(x\ ,y\ ,z\right)\mathrm{d}s},\frac{\displaystyle\int_{L}y\rho\left(x\ ,y\ ,z\right)\mathrm{d}s}{\displaystyle\int_{L}\rho\left(x\ ,y\ ,z\right)\mathrm{d}s},\frac{\displaystyle-\int_{L}z\rho\left(x\ ,y\ ,z\right)\mathrm{d}s}{\displaystyle\int_{L}\rho\left(x\ ,y\ ,z\right)\mathrm{d}s}.
$$  

（4）对光滑曲面薄片 $\boldsymbol{\Sigma}$ ，其面密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\right)$ ，则其重心 $(\overline{{x}},\overline{{y}},\overline{{z}})$ 的计算公式为  

$$
{\cfrac{\displaystyle-\left\iint_{x\rho\left(x\;,y\;,z\right)\partial S}}{\displaystyle-\left\lbrack\int_{\frac{x}{z}}(x\;,y\;,z)\,{\mathrm{d}}S},{\cfrac{\displaystyle\iint_{y\rho\left(x\;,y\;,z\right)\partial S}}{\displaystyle\iint_{z}(x\;,y\;,z)\,{\mathrm{d}}S}},{\cfrac{\displaystyle\iint_{z\rho\left(x\;,y\;,z\right)\partial S}}{\displaystyle\iint_{z}(x\;,y\;,z)\,{\mathrm{d}}S}}\right.}.
$$  

6. 转动惯量>其微元统一为：质量微元dm与dm到转动轴的距离平方r的乘积rdm  

（1）对平面薄片 $D$ ,其面密度为 $\rho\left(x\,,y\right)$ ,则该薄片对 $_{x}$ 轴、 $_y$ 轴和原点 $O$ 的转动惯量 $I_{x}$ ， $I_{y}$ 和 $I_{o}$ 的计算公式分别为  
$$
I_{x}=\!\!\!\iint_{D}\!\!y^{2}\rho\left(x\,,y\right)\mathrm{d}\sigma\,,I_{y}=\!\!\!\iint_{D}\!\!x^{2}\rho\left(x\,,y\right)\mathrm{d}\sigma\,,I_{o}=\!\!\!\iint_{D}\!\!x^{2}\rho^{2}\!\left(x\,,y\right)\mathrm{d}\sigma.
$$  

（2）对空间物体 $\Omega$ ,其体积密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,\right)$ ,则该物体对 $_{x}$ 轴、 $_y$ 轴、 $_z$ 轴和原点 $O$ 的转动 惯量 $I_{\mathrm{~\varepsilon~}},I_{\mathrm{~y~}},I_{\mathrm{~\varepsilon~}}$ 和 $I_{\phi}$ 的计算公式分别为  

$$
\begin{array}{r l}&{\ \ \ \ I_{x}=\displaystyle\iint_{a}(y^{2}+z^{2})\rho(x\,,y\,,z)\,{\mathrm{d}}v\,,I_{y}=\displaystyle\iint_{a}(z^{2}+x^{\,2})\rho(x\,,y\,,z)\,{\mathrm{d}}v\,,}\\ &{\,\,I_{z}=\displaystyle\iint_{a}(x^{\,2}+y^{\,2})\rho(x\,,y\,,z)\,{\mathrm{d}}v\,,I_{o}=\displaystyle\iint_{a}(x^{\,2}+y^{\,2}+z^{\,2})\rho(x\,,y\,,z)\,{\mathrm{d}}v\,.}\end{array}
$$  

（3）对光滑曲杆 $L$ ,其线密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\,\right)$ ,则该曲杆对 $_{x}$ 轴、 $_y$ 轴、 $_z$ 轴和原点 $O$ 的转动惯量 $I_{x}\,,I_{y}\,,I_{z}$ 和 $I_{()}$ 的计算公式分别为  

$$
I_{x}=\!\int_{L}(y^{2}+z^{2})\rho(x\,,\!y\,,\!z\,)\mathrm{d}s\,,I_{y}=\!\int_{L}(z^{2}+x^{2})\rho(x\,,\!y\,,\!z\,)\mathrm{d}s\,,
$$  

$$
I_{z}=\!\!\int_{L}{(x^{2}+y^{2})\rho(x\,,y\,,z\,)\mathrm{d}s}\,,I_{o}=\!\!\int_{L}{(x^{2}+y^{2}+z^{2})\rho(x\,,y\,,z\,)\mathrm{d}s}.
$$  

（4）对光滑曲面薄片 $\boldsymbol{\Sigma}$ ,其面密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\right)$ ,则该曲面对 $_{x}$ 轴、 $_y$ 轴、 $\mathscr{z}$ 轴和原点 $O$ 的转动惯量 $I_{x}\,,I_{y}\,,I_{z}$ 和 $I_{o}$ 的计算公式分别为  

$$
\begin{array}{r l}&{\phantom{=}\displaystyle{\prod_{x}}_{z}=\!\!\!\!\int\!\!(y^{2}+z^{2})\rho(x\,,\!y\,,\!z)\ensuremath{\mathrm{d}}\ensuremath{\boldsymbol{S}}\,,\!\,{\ensuremath{I}}_{y}=\!\!\!\iint\!(z^{2}+x^{2})\rho(x\,,\!y\,,\!z)\ensuremath{\mathrm{d}}\ensuremath{\boldsymbol{S}}\,,}\\ &{\phantom{=}\displaystyle{\prod_{z}}_{z}=\!\!\!\!\iint\!\!(x^{2}+y^{2})\rho(x\,,\!y\,,\!z)\ensuremath{\mathrm{d}}\ensuremath{\boldsymbol{S}}\,,\!\,{\ensuremath{I}}_{o}=\!\!\!\iint\!\!(x^{2}+y^{2}+z^{2})\rho(x\,,\!y\,,\!z)\ensuremath{\mathrm{d}}\ensuremath{\boldsymbol{S}}.}\end{array}
$$  

# 7.引力  

对于空间物体 $\Omega$ ,其体积密度为 $\rho\left(\boldsymbol{x}\,,\boldsymbol{y}\,,z\right)$ ,则该物体对物体外一点 $M_{\scriptscriptstyle0}(x_{\scriptscriptstyle0},y_{\scriptscriptstyle0},z_{\scriptscriptstyle0})$ 处的质 量为 $_m$ 的质点的引力 $(F_{x}\;,F_{y}\;,F_{z})$ ）的计算公式为  

$$
\begin{array}{r l}&{\displaystyle F_{x}=G m\iiint\frac{\rho(x\,,y\,,z)(x-x_{0})}{\left[(x-x_{0})^{2}+(y-y_{0})^{2}+(z-z_{0})^{2}\right]^{\frac{3}{2}}}\mathrm{d}y\,,}\\ &{\displaystyle F_{y}=G m\iiint\frac{\rho(x\,,y\,,z)(y-y_{0})}{\left[(x-x_{0})^{2}+(y-y_{0})^{2}+(z-z_{0})^{2}\right]^{\frac{3}{2}}}\mathrm{d}y\,,}\\ &{\displaystyle F_{z}=G m\iiint\frac{\rho(x\,,y\,,z)(z-z_{0})}{\left[(x-x_{0})^{2}+(y-y_{0})^{2}+(z-z_{0})^{2}\right]^{\frac{3}{2}}}\mathrm{d}v.}\end{array}
$$  

# 例18.32  

锥面 $z=\sqrt{x^{2}+y^{2}}$ 被抛物柱面 $z^{2}=2x$ 截下的曲面的面积为  

【解】应填 ${\sqrt{2}}\,\pi$ ：  

如图18-34所示，曲面为 $z\!=\!\sqrt{x^{2}+y^{2}}$ ，联立 $\begin{array}{r}{\left\langle z=\sqrt{x^{2}+y^{2}}\right.}\\ {\left.z^{2}=2x\,,\right.}\end{array}$ 解得交线 $x^{2}+y^{2}=2x$ ，即在 $x O y$ 平面上的投影域为  

$$
D:x^{2}+y^{2}\leqslant2x.
$$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/37d90666278e80ffbfb5119d3f4f8a2394c47f77fad41316ed84899c4bb25d55.jpg)  
图18-34  
$$
S=\!\!\!\int_{D}\!\sqrt{1+\Big(\frac{\partial z}{\partial x}\Big)^{2}+\Big(\frac{\partial z}{\partial y}\Big)^{2}}\,\mathrm{d}\sigma=\!\!\!\int_{D}\!\sqrt{2}\,\mathrm{d}\sigma=\!\!\sqrt{2}\,\pi.
$$  

例18.33设曲线 $y=\frac{1}{2}(\mathrm{e}^{x}\,+\,\mathrm{e}^{-x}$ ）上每一点的密度与该点的纵坐标成反比，且在点  

（0,1）处的密度等于1,则曲线在横坐标 $x_{\mathrm{~l~}}\!=\!0$ 及 $x_{2}=1$ 之间一段 $L$ 的质量为  

【解】应填1.  

由题意 $\rho=\frac{k}{y}$ 当 ${{y}}=1$ 雞时 $\rho=1$ 则 $k=1$ 即 $\rho=\frac{1}{y}$  

$$
m=\!\!\int_{L}\,\frac{1}{y}\mathrm{d}s=\!\!\int_{0}^{1}\frac{1}{\frac{1}{2}(\mathrm{e}^{x}+\mathrm{e}^{-x})}\,\sqrt{1+\left[\frac{1}{2}(\mathrm{e}^{x}-\mathrm{e}^{-x})\right]^{2}}\,\mathrm{d}x
$$  

例18.34设 $C$ 是曲线 $x^{2}+y^{2}=2(x+y)$ ，则 $\oint_{c}(2x^{2}+3y^{2})\,\mathrm{d}s=_{-}$  

【解】应填 $20\sqrt{2}\,\pi$  $C$ 是圆 $(x-1)^{2}+(y-1)^{2}=2$ ，关于 $y=x$ 对称，由轮换对称性知  

$$
\oint_{c}{x^{\,2}}\,\mathrm{d}s=\oint_{c}{y^{\,2}}\,\mathrm{d}s\,.
$$  

$$
\begin{array}{r}{\displaystyle\oint_{c}(2x^{2}+3y^{2})\,\mathrm{d}s=\frac{5}{2}\oint_{c}(x^{2}+y^{2})\,\mathrm{d}s=5\oint_{c}(x+y)\,\mathrm{d}s}\\ {\displaystyle=5\,\overline{{x}}\star l_{c}+5\overline{{y}}\star l_{c}=10\,l_{c}=20\sqrt{2}\,\pi.}\end{array}
$$  

例18.35由曲线 $x^{2}+3y-5=0\,,x=\sqrt{y+1}$ 以及 $x=0$ 所围成的均匀薄片(密度 $\pmb{\mu}$ 为常数）对 $_y$ 轴的转动惯量为  

【解】应填 $\frac{32\sqrt{2}}{45}\mu$ 如图18-35所示，  

$$
\begin{array}{r}{I_{s}=\!\!\!\int_{0}^{\infty}\!\!\!\mu x^{\,2}\,\mathrm{d}\sigma=\!\mu\!\!\int_{0}^{\sqrt{2}}\!x^{\,2}\,\mathrm{d}x\!\int_{x^{\,2}-1}^{\frac{1}{3}(5-x^{2})}\!\!\!\!\mathrm{d}y}\\ {=\!\frac{4}{3}\mu\!\!\int_{0}^{\sqrt{2}}(2x^{\,2}-x^{\,4})\,\mathrm{d}x=\!\frac{32\sqrt{2}}{45}\!\!\!\,\mu.}\end{array}
$$  

例18.36设锥面 $\Sigma$ 的顶点是A(0,1,1)，准线是 $\scriptstyle{\bigl\{}x^{2}+y^{2}=1\,,$ 直线 $L$ 过顶点A和准线上任一点 $M_{1}(x_{1},y_{1},0).\Omega$ 是 $\Sigma(0\leqslant z\leqslant1)$ ）与平面 $z=0$ 所围成的锥体.  

（1）求 $L$ 和 $\boldsymbol{\Sigma}$ 的方程；  
(2）求 $\Omega$ 的形心坐标.  

【解】（1）如图18-36所示,从顶点A到准线上任一点 $M_{1}\left(x_{1}$  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/185bf45b9e1ac020369b992b58e78c5ddb1e447e70504a8626903fd51095b45f.jpg)  
图18-35  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a6533c235ea109a87e30c36200e2e8adf4b62595141d157ed6d9d86a94396361.jpg)  
图18-36  
$y_{1}$ ,0）作直线段 $\overline{{A M_{\scriptscriptstyle1}}}$ ,记其上任一点 $M(x\mid y\,,z\,)$ ，由于 $\overline{{A M}}\ /\overline{{/A M_{1}}}$ ，则  

$$
\frac{x-0}{x_{1}-0}\!=\!\frac{y-1}{y_{1}-1}\!=\!\frac{z-1}{-1},
$$  

此即为 $L$ 的方程，又由于 $M_{1}$ 在准线上，有  

$$
x_{\mathrm{~l~}}^{\mathrm{~2~}}+y_{\mathrm{~l~}}^{\mathrm{~2~}}=1.
$$  

由 $\textcircled{1}$ 得 $x_{1}=\frac{x}{1-z},y_{1}=\frac{y-z}{1-z}$ ，代人 $\circledcirc$ ,有  

$$
\frac{x^{2}}{(1-z)^{2}}+\frac{(y-z)^{2}}{(1-z)^{2}}=1\,,
$$  

即锥面 $\boldsymbol{\Sigma}$ 的方程为 $x^{2}+(y-z)^{2}=(1-z)^{2}$  

（2）如图18-37所示，设 $\varOmega$ 的形心坐标为 $(\overline{{x}}\,,\overline{{y}}\,,\overline{{z}}\,)$ ，因为 $\Omega$ 关于 $y O z$ 平面对称，所以 $\overline{{x}}=0$  

对于 $0\leqslant z\leqslant1$ ，记 $D_{z}=\{(x\,,y\,)\mid x^{2}+(y-z\,)^{2}\leqslant(1-z\,)^{2}\}.$  

因为  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f1e47402265a0f9c2cea4d18f7eca7e26079d16574c4ba1dc10cbb9df838e855.jpg)  
图18-37  

$$
\begin{array}{r l}&{V\!=\!\underset{a}{\iint}\!\!\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z=\!\int_{0}^{1}\!\!\mathrm{d}z\!\iint\!\mathrm{d}x\,\mathrm{d}y=\!\int_{0}^{1}\!\pi(1-z)^{2}\,\mathrm{d}z=\!\frac{\pi}{3},}\\ &{\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\!\! 
$$  

所以  

$$
{\begin{array}{l}{{\cfrac{\iiint_{y}\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z}{y}}={\frac{\,\parallel\,}{4}},}\\ {{\cfrac{\,\parallel\,}{z}}={\frac{\,\parallel\,}{1\,}}z\,\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z}\\ {{\cfrac{\,-\,}{z}}={\frac{\,{\frac{\parallel\,}{2}}\,}{V}}={\frac{\,{\frac{1}{4}}\,}{4}}.}\end{array}}
$$  

故 $\Omega$ 的形心坐标为 $\left(0,{\frac{1}{4}},{\frac{1}{4}}\right)$  

[注](1) 考生可从第一问中学到求锥面方程的一般方法,在考研题中,命题人给出方程 $x^{2}+$  $(y-z)^{2}=(1-z)^{2}$ 时,很多考生不知所云,这里的第一问回答了此问题。  

(2) 若不画图,把 $(x,y,z)$ 与 $(-x,y,z)$ 代入表达式,表达式不变,也可知锥面关于 $_{y O z}$ 平面对称，于是 $\overline{{x}}=0$  
# 附录  

# 儿种常见的空间图形  

(1)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/8f666f23b5510ea0b9e6b365002fc61185fd78fd89bd18dd4304cbbcaa52d366.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/36cf49de06056f6d833b2f353135f768c392e70e326d2a6eaf2a12e27ec0fd1e.jpg)  

(3)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/58b06ae6fefd41ca845eb501ba89f4fde0af86bb3173786069538d4cae13032b.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/03f63dd111a7085cd306ea0e9b24234f1f7fb07464928c8b941658bf9e759be1.jpg)  
(5)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/bbea9f56d0f7d07c37ed565824a2ac45e6573c5f71c32ef0efd71b0fb2a217b9.jpg)  

$z=x^{2}+y^{2}$  

(6)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a37b2881d0613e52b100edd4bd844e762f25ad46b11f6e7203f226fc1f2303d5.jpg)  

$$
x^{2}+y^{2}=a^{2}\,,z\geqslant0,a>0
$$  

(7)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a944f0f13bdcbe090d98c4353191dd8f0d51a75b1d7dc5b43ce3d2621014dd51.jpg)  

(8)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/5d700f5850fe8b71621ce084b96c365739c802ae30a2540769797b45e967d49f.jpg)  

(9)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/435ec1b605fd33a380941aa093c7010df4ad12a7513b918a72111371b4f44b52.jpg)  
$\sqrt{x}+\sqrt{y}+\sqrt{z}\,=\sqrt{a}\,,a>0$  

(10)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a459e1fd5d5a582a6cafd5ba4a7bf44dd2351a35cdd632c24c429aa6701034dc.jpg)  

xy  
(11)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/ef47ea29db16f64aebc93d76c94755e2202cb6209cc3ac0fde987c056e630838.jpg)  

(12)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/d97daa23813e524bb208ce11e889e1ddec9b017a5f85dd8435b3b4217ddc1c89.jpg)  

(13)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/d564c3993edffcaf5827bb7b88331b8cb6252169614e8912b9032984f4cd7fcd.jpg)  

(14)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/1a03d859048fc68127c923f17e1e314f793c340d3adf6a8116dc6e1cd93acd2a.jpg)  

(15)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/f2067d6b173d8dc7f27b593988a7c600ffc4a2b5f9812d6b102766528400d93b.jpg)  

$$
\scriptstyle{\binom{x^{2}+y^{2}}{z}}={\binom{1}{2}}
$$  

(16)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/a6a8c0d4664f21ca2eaf90f10251e7a0aa216e5caecf6a4b9a8c81fd845f08a1.jpg)  

$$
x^{2}+(y-z)^{2}=(1-z)^{2}\,,0\leqslant z\leqslant1
$$  
(17)  

(18)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/e93f827fdb11c2e511be9da8a77efe1e9ad38b17d31d14a965271ed5c94e4128.jpg)  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/b63b2302d0df642d1a29ed38c77dafd269a92f091f9c3c7fb2175f5c1628c71c.jpg)  
![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/526c0b47aa5d5b5abe67142678e68dca032ae5e68f5f80ddd1322bfa9bb5c08f.jpg)  

博士，全国著名考研数学辅导专家，教育部“国家精品课程建设骨干教师”，全国畅销书《张宇考研数学基础30讲》《张宇考研数学题源探析经典1000题》《张宇高等数学18讲》《张宇线性代数9讲》《张宇概率论与数理统计9讲》《张宇考研数学真题大全解》《考研数学命题人终极预测8套卷》《张宇考研数学最后4套卷》《张宇经济类综合能力数学通关优题库》作者，高等教育出版社原《全国硕士研究生入学统一考试数学考试大纲解析》及《全国硕士研究生招生考试经济类专业学位联考综合能力考试大纲解析》编者之一，北京、上海、广州、西安等全国著名考研数学辅导班首席主讲。  

![](https://cdn-mineru.openxlab.org.cn/model-mineru/prod/8f6f4a9d19837fe7d56029425c2f779b45dbdc836f3e2d2c76d63770e98ca64b.jpg)  

# ·教材类  

张宇考研数学基础30讲·高等数学分册书课包  
张宇考研数学基础30讲·线性代数分册书课包  
张宇考研数学基础30讲·概率论与数理统计分册书课包  
张宇高等数学18讲书课包  
张宇线性代数9讲书课包  
张宇概率论与数理统计9讲书课包  

?题集尖 张宇考研数学题源探析经典1000题（分数学一、数学二、数学三）书课包张宇考研数学真题大全解（分数学一、数学二、数学三）书课包考研数学命题人终极预测8套卷（分数学一、数学二、数学三） 书课包 张宇考研数学最后4套卷（分数学一、数学二、数学三）书课包  
