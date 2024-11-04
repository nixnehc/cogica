---
title: Cogica
---
这里是一些临时性的笔记和乱七八糟的东西....

- 🧐 [术语翻译](post/en-zh "信达雅") 
- 🤩 [符号收集者](post/symbol) 
- 🤪 [Gossip](post/gossip "一些学术八卦") 
- 🥳 [Some Slogans](post/slogans) 
- 🤔 [Open Problems](post/open-problems) 
- 🌲 [Acknowledgement & Dedication](post/ack.md) 

🐕 🐈 🚙 🚌 🚲 🛵 👾 🤖 🤢 👏 💪 

## Some Notes

1. [燃烧理性火焰](note/燃烧理性火焰)   
2. [Modal Logic for Open Mind](note/MLOpenMind)  
3. [Papadimitriou_1994](note/Papadimitriou_1994)


---





--- 
Coalgebra:

- **universal algebra**, on the other hand, we may consider it as a rather special branch of model theory in which one is interested in structures for a language without relation symbols.

- **coalgebra** can be conceived as a general and uniform theory of *dynamic systems*. 

- coalgebras over the base category $C$ are dual to algebras over the opposite category $C^{op}$.

- the link between modal logics and coalgebra is so tight, that one may even claim that *modal logic is the natural logic for coalgebras* — just like equational logic is that for algebra.

- (Kripke) frames and models are in fact coalgebras in disguise.

- The p-morphisms of Kripke models/frames are precisely the coalgebra morphisms.

- modal logic is the logic of bisimulation. 

- Universal Coalgebra is a theory of state-based evolving systems.

---


- *Tukey's Lemma* is equivalent to the Axiom of Choice [Kelley 1955, p.33]
- The proof of *Konig's Lemma* does, however, use a weak form of the Axiom of Choice.


- $\Box$ has some features of $\forall$ if one allows empty domain models. (模态词是可以论域为空的量词？)

-  "modal logic is a logic of change" `[Fit.Men2023, p. x]`


- This first decidability result for $FO^2$ was obtained by `Scott (1962)` [*A decision method for validity of sentences in two variables*], who showed that the decision problem for $FO^2$ can be reduced to that of the Godel class. Since, as mentioned above, only the Godel class without equality is decidable, Scott's reduction yields the decidability of $FO^$2 without equality, but does not cover the case of $FO^2$ with equality.    
The full class $FO^2$ was considered by `Mortimer (1975)` [*On language with two variables*]. He proved that class is decidable by showing that it has the <u>finite model property</u>.



- tableau --> plural: tableaux
- branch 分枝 $\Theta$ , 父节点
- 

- 动态算子的表达力往往可以通过静态的混合逻辑来实现 [LiuFR-23, p.~160]


- **Monte-Carlo simulation** has a long history, and has been applied to a variety of computationally difficult problems including inference in *Bayesian Networks*, *reinforcement learning*  and *computer game playing*.
- 
- on finite sets, `measures = distributions`.
- 
- **Ultrapowers**: [https://grossack.site/2021/12/05/ultraproducts-howto.html](https://grossack.site/2021/12/05/ultraproducts-howto.html "一个关于「超幂」的博文，里面的梗图很搞笑")

- The most straightforward way to provide referentiality in a modal logic is to `hybridize` this logic, that is to extend the language with, for example, the following symbols: 
    - $\mathsf{NOM}$: a countable set of nominals different than PROP;
    -  $\{@_i \mid i \in NOM\}$:  a set of satisfaction operators indexed with nominals.





---
不可判定的模态逻辑 ~~>  可判定片段：
1. to limit the number of modal operators in the language.

2. weakening the definitions of relations interpreting the modal operators.

3. imposing additional constraints on the semantical structures.

4. imposing restriction on the use of propositional connectives, e.g., sub-propositional fragments.

(cf. Wałęga_2019_Hybrid fragments of Halpern–Shoham logic and their expressive power.)


---
一些证明模态逻辑可判定的方法：  
1. effective finite model property
    - selection
    - filtration   
    - NB: $FOL$ has no $f.m.p$. 
       Let $\phi$ be a first-order sentence say that $<$ is an *irreflexive transitive order where every point has a successor*. 
       $\phi$ has only infinite model, e.g. natural number with the usual order $(\mathbb{N},<)$.
2. semantic tableaux ==> completeness + termination

3. Translation: 
    all basic modal formulas can be translated into $FO^2$, the two-variable fragment of $FOL$, which is decidable shown in the 1970s. 
    But note that $FO^n \; (n \geq 3)$ is undecidable.



---
以下摘抄自：Cresswell《模态逻辑中的框架和模型》(in *Algebra and Logic*, 1975)（康宏逵译）：  

- 要分清作为一个公式集的逻辑和一个公理系统: 
    - 公理系统是有某个能行可枚举的公理集加上若干变形规则组成的。一个逻辑 L（作为公式集）是可公理化的，当且仅当，有一公理系统 A 使得 L 是 A 的定理集。L 是有穷可公理化的，当且仅当，有一这样的 A，其中只有有穷多个公理。  
    - 显然，同一个（作为公式集的）逻辑能按照不同的办法公理化。并且，不是所有逻辑都可以公理化。

- 任何一致的逻辑，我们总可以定义它的典范模型.

- **存在引理**堪称模态逻辑的基本定理，因为迄今得到的模态系统的完全性结果几乎都是从它得出。

- $K \oplus \Box\Diamond p \to \Diamond\Box p$ 在它的典范框架上不是有效的，但却是完全的，并且任何一阶公式都不能刻画它的框架。

- 如果一个逻辑 L 可公理化且具备有穷模型性质，则 L 是可判定的, 反之不然.

- 证明有穷模型性质最有力的方法是 Segerberg 的 filtration 方法，其余的方法有比如 Mckinsey (1941) 的一种代数方法。





---
- Substitution v.s. Schema:  
    schema 是一集结构类似的公式，而 sub 是对公式中的变元做统一替换。一般来说 sub 和 schema 可以不加以刻意区分。但是！但是！在有些逻辑中，只能用 schema 而不能用 sub，比如「公开宣告逻辑」PAL 中的公理： $[\phi]p \leftrightarrow (\phi \to p)$， 就不能通过 sub 把 $p$ 换成别的公式。


- 语义方面的概念可以涉及到无穷的情况（如传递自反闭包），而语法层面的东西就不能包含无穷。(2021-06-14)

- 
- `Predicate abstracts` built by means of the lambda operator were introduced to studies on FOML by [Thomason, R. and R. Stalnaker, Modality and reference, Nous 2 (1968), pp. 359–372] and then the technique was developed by [Fitting, M., Modal logic should say more than it does, 1991].  
- 
- the **Henkin-Scott-Makinson method** of maximally consistent (MC) theories
- 
- Lewis constructed five axiomatic systems : $S1$--$S5$, actually, $S5$ was introduced before Lewis by H. McColl (1906).
- 

- 铢积寸累 --> 洋洋大观
- 
- 逻辑总是表述在语言中的。
- $FO^2_C$, the two-variable fragment of FOL with cunting quantifiers, is NEXPTime--complete.


--- 
「插值性」的证明方法大致有：
1. purely syntactic
    - constructive
    - no proof system
2. algebraic
    - non-constructive
    - amalgamation $\approx$ interpolation
3. proof theoretic
    - sometimes constructive
    - sequent / tableau systems




---
## 算是方法论吧

1. 证明过的东西就不用再证一遍了，说明下即可。

2. 要学会淡化别人的证明，这个能力很重要。

3. 对证明中的符号要有说明。

4. 「数理逻辑最初的主题是一致性、可判定性和完备性。现代数理逻辑的主题是独立性、可定义性和可归约性。希望这个口号能让大部分认为自己在做数理逻辑的人满意。」（这是`@午时葵` 20 年在知乎上的一个回答）

5. **鸽笼原理**是**拉姆齐理论**的一个例子。
鸽笼原理传统的理解是，n+1 只鸽子飞进 n 个笼子里，一定会有一个鸽笼里面至少有两只鸽子。如果遵循 Ramsey 理论的思想，鸽笼原理的另一种理解方式是：给定 n 个鸽笼，如果想要「鸽子同笼」这件事一定发生，那我们至少需要多少只鸽子呢？答案是 n+1 只。   
再换一套语言。假设有 A、B 两个集合，其中 B 中有 n 个元素。现在从集合 A 向 B 作映射 f，如果要保证一定会出现 f(a)=f(b)，问 A 的元素个数至少是多少个？答案还是 n+1。  
从这个角度看，鸽笼原理以至于拉姆齐理论其实是在探讨这样的问题：如何从不确定性中取出确定性，或者说如何从混沌 chaos 中找到秩序 order。（摘自中科院物理所公众号19年的某篇推文）





---
## Testing

- Inline formula
    -  `$...$`: $\bot \to \phi$
    - Inline `\\(...\\)`: \\( \Sigma \vdash \varphi \;\leftrightarrow\; \Sigma \models \varphi \\)

- Inline + display style `$\displaystyle ....$`:  $\displaystyle \bigcup_{i \in I} A_i$.

- When $a \ne 0$, there are two solutions to $ax^2 + bx + c = 0$ and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$.

Use `$$...$$` (separate line)

$$
 \int_{-\infty}^{\infty} f(t) e^{-j\omega t} dt
$$

Use `\\[...\\]` (separate line)

\\[
 \int_{-\infty}^{\infty} f(t) e^{-j\omega t} dt
\\]



## Appendix

- [Converted from Markdown file](test1)
- [Converted from HTML file](test2)
- [Basic Syntax](https://www.markdownguide.org/basic-syntax/)