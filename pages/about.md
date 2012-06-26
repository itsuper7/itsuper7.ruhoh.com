---
title : About Me Ha ha ha .
description:
---


<?xml version="1.0" encoding="iso-8859-1"?>
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
               "http://www.w3.org/TR/xhtml1/DTD/xhtml1-strict.dtd">
<html xmlns="http://www.w3.org/1999/xhtml"
lang="en" xml:lang="en">
<head>
<title>probability<sub>theory</sub></title>
<meta http-equiv="Content-Type" content="text/html;charset=iso-8859-1"/>
<meta name="generator" content="Org-mode"/>
<meta name="generated" content="2012-03-23 17:39:37 HKT"/>
<meta name="author" content="sijin"/>
<meta name="description" content=""/>
<meta name="keywords" content=""/>
<style type="text/css">
 <!--/*--><![CDATA[/*><!--*/
  html { font-family: Times, serif; font-size: 12pt; }
  .title  { text-align: center; }
  .todo   { color: red; }
  .done   { color: green; }
  .tag    { background-color: #add8e6; font-weight:normal }
  .target { }
  .timestamp { color: #bebebe; }
  .timestamp-kwd { color: #5f9ea0; }
  p.verse { margin-left: 3% }
  pre {
	border: 1pt solid #AEBDCC;
	background-color: #F3F5F7;
	padding: 5pt;
	font-family: courier, monospace;
        font-size: 90%;
        overflow:auto;
  }
  table { border-collapse: collapse; }
  td, th { vertical-align: top; }
  dt { font-weight: bold; }
  div.figure { padding: 0.5em; }
  div.figure p { text-align: center; }
  .linenr { font-size:smaller }
  .code-highlighted {background-color:#ffff00;}
  .org-info-js_info-navigation { border-style:none; }
  #org-info-js_console-label { font-size:10px; font-weight:bold;
                               white-space:nowrap; }
  .org-info-js_search-highlight {background-color:#ffff00; color:#000000;
                                 font-weight:bold; }
  /*]]>*/-->
</style>
<script type="text/javascript">
<!--/*--><![CDATA[/*><!--*/
 function CodeHighlightOn(elem, id)
 {
   var target = document.getElementById(id);
   if(null != target) {
     elem.cacheClassElem = elem.className;
     elem.cacheClassTarget = target.className;
     target.className = "code-highlighted";
     elem.className   = "code-highlighted";
   }
 }
 function CodeHighlightOff(elem, id)
 {
   var target = document.getElementById(id);
   if(elem.cacheClassElem)
     elem.className = elem.cacheClassElem;
   if(elem.cacheClassTarget)
     target.className = elem.cacheClassTarget;
 }
/*]]>*///-->
</script>
</head>
<body>
<div id="content">

<h1 class="title">probability<sub>theory</sub></h1>


<div id="table-of-contents">
<h2>Table of Contents</h2>
<div id="text-table-of-contents">
<ul>
<li><a href="#sec-1">1 Population Process </a>
<ul>
<li><a href="#sec-1.1">1.1 Definition </a>
<ul>
<li><a href="#sec-1.1.1">1.1.1 Point Process </a></li>
<li><a href="#sec-1.1.2">1.1.2 Population Process </a></li>
<li><a href="#sec-1.1.3">1.1.3 Counting Process </a></li>
<li><a href="#sec-1.1.4">1.1.4 Mapping from a "point" in population space to a "point" Couting process </a></li>
</ul>
</li>
<li><a href="#sec-1.2">1.2 Properties </a></li>
<li><a href="#sec-1.3">1.3 Generating function </a></li>
</ul>
</li>
<li><a href="#sec-2">2 PhDfilter </a>
<ul>
<li><a href="#sec-2.1">2.1 conditional independence with graph </a></li>
<li><a href="#sec-2.2">2.2 conditional probability is also a probability distribution </a></li>
<li><a href="#sec-2.3">2.3 PHD and the moment of multi-track moment </a></li>
</ul>
</li>
<li><a href="#sec-3">3 EM </a></li>
<li><a href="#sec-4">4 Kolmogorov's zero-one law </a></li>
</ul>
</div>
</div>

<div id="outline-container-1" class="outline-2">
<h2 id="sec-1"><span class="section-number-2">1</span> Population Process<sup><a class="footref" name="fnr.1" href="#fn.1">1</a></sup> </h2>
<div class="outline-text-2" id="text-1">


</div>

<div id="outline-container-1.1" class="outline-3">
<h3 id="sec-1.1"><span class="section-number-3">1.1</span> Definition </h3>
<div class="outline-text-3" id="text-1.1">


</div>

<div id="outline-container-1.1.1" class="outline-4">
<h4 id="sec-1.1.1"><span class="section-number-4">1.1.1</span> Point Process </h4>
<div class="outline-text-4" id="text-1.1.1">


</div>

</div>

<div id="outline-container-1.1.2" class="outline-4">
<h4 id="sec-1.1.2"><span class="section-number-4">1.1.2</span> Population Process </h4>
<div class="outline-text-4" id="text-1.1.2">

<p>Population state is a state of populations. A point in the population space will be like $x<sup>\{n\}</sup> = {x<sub>1</sub>,&hellip;x<sub>n</sub>}, x<sub>i</sub> &isin; X(space)$.
n is the size of the population. 
&chi; is a population state space, B is a &sigma; filed of set in &chi;, and P is the probability on B. (&chi;, B, P) is a population 
process.
</p>
</div>

</div>

<div id="outline-container-1.1.3" class="outline-4">
<h4 id="sec-1.1.3"><span class="section-number-4">1.1.3</span> Counting Process </h4>
<div class="outline-text-4" id="text-1.1.3">

<p>Suppose $N(\dot)$ is a function on the class U of subsect of X, and satisfy the following properties
</p><ol>
<li>
non-negative
</li>
<li>
finite 
</li>
<li>
integral-valued
</li>
<li>
completely additive
</li>
</ol>
</div>

</div>

<div id="outline-container-1.1.4" class="outline-4">
<h4 id="sec-1.1.4"><span class="section-number-4">1.1.4</span> Mapping from a "point" in population space to a "point" Couting process </h4>
<div class="outline-text-4" id="text-1.1.4">

<p>$N(A|x<sup>\{n\}</sup>) = &sum;<sub>i = 1</sub><sup>n</sup> &delta;(A|x<sub>i</sub>)$, where $\dalta(A|x<sub>i</sub>)$ is the characteristic function of the set A.
Let's consider k-th product measure N<sub>k</sub> on B<sup>k</sup>. 
\begin{equation}
\label{equ:}
N<sub>k</sub>(A<sup>(k)</sup>|x<sup>\{n\}</sup>) = &sum;<sub>i<sub>1</sub> = 1</sub><sup>n</sup>&hellip;&sum;{\i<sub>k</sub> = 1}<sup>n</sup> &delta;(A<sup>(k)</sup>|x<sub>i<sub>1</sub></sub>,&hellip;x<sub>i<sub>k</sub></sub>) 
\end{equation} 
</p></div>
</div>

</div>

<div id="outline-container-1.2" class="outline-3">
<h3 id="sec-1.2"><span class="section-number-3">1.2</span> Properties </h3>
<div class="outline-text-3" id="text-1.2">

<p>From the relation with Counting process, it is nature to use the mapping to induce probability to the space of counting space.
Therefore, we are able to measure the probability 
\[
P<sub>N</sub>(N(A<sub>i</sub>) = k<sub>i</sub>, i = 1,2,&hellip;r) = P<sub>S</sub><sup>\{n\}</sup>({A<sub>1</sub>}<sup>k<sub>1</sub></sup>&hellip;{A<sub>r</sub>}<sup>k<sub>r</sub></sup>)<sub>S</sub> = \frac{n!}{{k<sub>1</sub>}!&hellip;{k<sub>n</sub>}!}P<sub>S</sub><sup>n</sup>({A<sub>1</sub>}<sup>k<sub>1</sub></sup>&hellip;{A<sub>r</sub>}<sup>k<sub>r</sub></sup>)
\]
</p></div>

</div>

<div id="outline-container-1.3" class="outline-3">
<h3 id="sec-1.3"><span class="section-number-3">1.3</span> Generating function </h3>
<div class="outline-text-3" id="text-1.3">

<p>$w(x<sup>n</sup>) = &xi;(x<sub>1</sub>)&xi;(x<sub>2</sub>)&hellip;&xi;(x<sub>n</sub>)$,
</p>
<p>
\[
G[&xi;] = Ew = &sum;<sub>n = 0</sub><sup>&infin;</sup>&int;<sub>x<sup>n</sup></sub> w(x<sup>n</sup>) P<sup>(n)</sup>(dx<sup>n</sup>) = &sum;<sub>n = 0</sub><sup>\infy</sup>G<sup>n</sup>[&xi;] = &sum;<sub>n = 0</sub><sup>&infin;</sup>p<sub>n</sub> Z<sup>(n)</sup>[&xi;]
\]
$p<sub>n</sub> = P<sup>(n)</sup>(X<sup>n</sup>), Z<sup>n</sup>=G<sup>n</sup>/p<sub>n</sub>
</p>
<p>
The idea of generating function is to use the sum to describe or "generate" a function. More information about generating function can be found 
at <sup><a class="footref" name="fnr.2" href="#fn.2">2</a></sup>.
</p>
<p>
If we choose proper $&xi;$ and &lambda;, the derivative of generating function can be used to calculate the probability,$P<sub>s</sub><sup>(k)</sup>(A<sub>1&hellip</sub>;A<sub>k</sub>)$, in others words,
G determines P<sub>S</sub> uniquely.
</p></div>
</div>

</div>

<div id="outline-container-2" class="outline-2">
<h2 id="sec-2"><span class="section-number-2">2</span> PhDfilter </h2>
<div class="outline-text-2" id="text-2">


</div>

<div id="outline-container-2.1" class="outline-3">
<h3 id="sec-2.1"><span class="section-number-3">2.1</span> conditional independence with graph </h3>
<div class="outline-text-3" id="text-2.1">

<p>How to block and make them independent
</p><ul>
<li>
tail-to-tail or tail-to-tail nodes being observed
</li>
<li>
head-to-head node is <b>not</b> observed
</li>
</ul>
</div>

</div>

<div id="outline-container-2.2" class="outline-3">
<h3 id="sec-2.2"><span class="section-number-3">2.2</span> conditional probability is also a probability distribution </h3>
<div class="outline-text-3" id="text-2.2">

</div>

</div>

<div id="outline-container-2.3" class="outline-3">
<h3 id="sec-2.3"><span class="section-number-3">2.3</span> PHD and the moment of multi-track moment </h3>
<div class="outline-text-3" id="text-2.3">

<ul>
<li>
PHD $\hat{D}<sub>k|k</sub>$ is the expentation density of the track set
</li>
</ul>

<p>Let $&Gamma;$ be 
\begin{equation}
\hat{D}<sub>k|k</sub>(x|Z<sup>(k)</sup>) = Pr(x &isin; &Gamma;<sub>k</sub>)
\end{equation}
</p>
<ul>
<li>
Multitarget moment density
</li>
</ul>

<p>\begin{equation}
\hat{D}<sub>k|k</sub> = &int; f<sub>k|k</sub>(X &cup; W|Z<sup>(k)</sup>)&delta; W = &sum;<sub>i = 0</sub><sup>&infin;</sup> &int; f<sub>k|k</sub>(X &cup; \{x<sub>1</sub>,&hellip;x<sub>i\</sub>})dx<sub>1</sub> &hellip; dx<sub>i</sub>
\end{equation}
</p><ul>
<li>
Condition of equality $\hat{D}<sub>k|k</sub>(x|Z<sup>(1)</sup>) = D<sub>k|k</sub>(\{x\}|Z<sup>(k)</sup>)$ 
</li>
</ul>

<p>When we set $f<sub>k|k</sub>(X|Z<sup>(k)</sup>) = \frac{&delta; &beta;<sub>k|k</sub>}{&delta; X}(&empty;|Z<sup>(k)</sup>)$, where $&beta;<sub>k|k</sub>(S|Z<sup>(k)</sup>) = Pr(&Gamma; &sub; S)$.
That is first-moment density and the PHD(Probability Hypothesis Density) are the same thing.
</p><ul>
<li>
Inversion formula for multitarget moment densities

</li>
</ul>

<p>\begin{equation}
\label{equ:inv}
f<sup>k|k</sup>(X|Z<sup>(k)</sup>) = &int; (-1)<sup>|W|</sup> D<sub>k|k</sub>(X &cup; W|Z<sup>(k)</sup>) &delta; W
\end{equation} 
</p><ul>
<li>
Formula
</li>
</ul>

<p>\begin{equation}
\hat{D}<sub>k+1|k</sub>(y|Z<sup>(k)</sup>) = &int; (d<sub>k+1|k</sub>(x)f<sub>k+1|k</sub>(y|x) + \hat{b}<sub>k+1|k</sub>(y|x))\hat{D}<sub>k|k</sub>(x|Z<sup>(k)</sup>)dx
\end{equation}
where $\hat{b}<sub>k+1|k</sub>(y|x)$ denotes the PHD of the multitarget density $b<sub>k+1|k</sub>(y|x)$
</p>
<ul>
<li>
Update Equations

<p>
<b>assume the current observations depent onlly on the current condensed state x&mdash;i.e, $Pr(Z<sub>k+1</sub>|x&isin; |&Gamma;<sub>k+1</sub>,Z<sup>(k)</sup>))&cong; Pr(Z<sub>k+1</sub>|x &isin; &Gamma;<sub>k+1</sub>)$</b>
</p></li>
</ul>

<p>\begin{equation}
\hat<sub>D</sub><sub>k+1|k+1</sub>(x|Z<sup>(k+1)</sup>) = Pr(x &isin; &Gamma;|Z<sup>(k+1)</sup> = \frac{Pr(Z<sub>k+1</sub>|x&isin; &Gamma;)Pr(x&isin; &Gamma; |Z<sup>(k)</sup>)}{Pr(Z<sub>k+1</sub>|Z<sup>(k)</sup>)} =\frac{ \hat{D}(Z<sub>k+1</sub>|x)D<sub>k+1|k</sub>(x|Z<sup>(k)</sup>)}{f<sub>k+1</sub>(Z<sub>k+1</sub>|Z<sup>(k)</sup>)}
\end{equation}
\begin{equation}
\hat{D}(Z<sub>k+1</sub>|x) = \frac{ &int; f(z|\{x\}&cup; W) f<sub>0</sub>(\{x\} &cup; W) &delta; W   }{&int; f<sub>0</sub>(\{x\}&cup; W)&delta; W}
\end{equation}
$f<sub>0</sub>{X}$ is a multitarget uniform density.
<b>use convariance-free posterior to approximate $f<sub>k|k</sub>$</b>
</p>
<p>
\begin{equation}
\label{equ:dconv}
D<sub>k|k</sub>(X|Z<sup>(k)</sup>) = D<sub>k|k</sub>(x<sub>1|Z</sub><sup>(k)</sup>)*&hellip;D<sub>k|k</sub>(x<sub>n|Z</sub><sup>(k)</sup>),\quad X = \{x<sub>1</sub>,&hellip;x<sub>n\</sub>}
\end{equation} 
Use <b>Equ</b>\ref{equ:dconv},and <b>Equ</b>\ref{equ:inv} to compute f<sub>k|k</sub>
Information-Update using the approximatioe prosterior of a PH
</p>
</div>
</div>

</div>

<div id="outline-container-3" class="outline-2">
<h2 id="sec-3"><span class="section-number-2">3</span> EM </h2>
<div class="outline-text-2" id="text-3">

<p>EM Study Nodes
</p>
<p>
Read EM algorhm in PRML. The idea is to introduce latent variable, and modify the form.
And P(X|&theta;) = &sum; P(X,Z|&theta;)
</p><ol>
<li>
Estimate the posterior P(Z|X, &theta;)
</li>
<li>
Calculate &theta;<sup>new</sup> by optimize Q(&theta;, &theta;<sup>new</sup>) = E(ln(P(X,Z|&theta;<sup>new</sup>))).
</li>
</ol>

<p>It happen to have the expectation form. In fact, we only want to optimize P(X|&theta;).
However, in order to ease the optimization, we divide ln(P(X|&theta;)) in two parts.
ln(P(X|&theta;)) = L(&theta;,q) + KL(q,p).
</p>
<p>
L(&theta;, q) = &sum;<sub>z</sub> q(z)ln(\frac{P(X,z|&theta;)}{q(z)})
</p>
<p>
KL(q,p) = &sum;<sub>z</sub> -q(z)ln(\frac{P(z|X,&theta;)}{q(z)}).
</p>
<p>
KL part is always greater than zero, the equlity holds iff q(z) = P(z|X,&theta;).
EM can be described like this
</p><ol>
<li>
We change q(z) to make KL = 0. Note that q(z) has nothing to do with P(X|&theta;).So at this st  ep, L + KL is unchanged.(L becomes larger in this step unless it has already achieve
</li>
</ol>

<p>local(global) maximum)
</p><ol>
<li>
We optimize L by update &theta;. Here, q(z) is P(z|x,&theta;). The form is like optimizing expection under the posterior p(z|x,&theta;).(Of cause, L tend to become larger again, K becomes positive because the equility might not hold again, hence the increase in P(X|&theta;) is larger than L in this step)
</li>
</ol>
</div>

</div>

<div id="outline-container-4" class="outline-2">
<h2 id="sec-4"><span class="section-number-2">4</span> Kolmogorov's zero-one law </h2>
<div class="outline-text-2" id="text-4">

<p>Let (&Omega;,F,P) be a probability space and let F<sub>n</sub> be a sequence of mutually independent &sigma;-algebras contained in F. Let
</p>
<p>
G<sub>n</sub> = &sigma;{&cup;<sub>k = n</sub><sup>infty</sup>F<sub>k</sub>} be the smalleset &sigma;-algebras containing F<sub>n</sub>, f<sub>n+1</sub>,&hellip; Then Kolmogorov's zero-one law asserts that for any event
F &isin; {&cap;<sub>n = 1</sub>}<sup>infty</sup>G<sub>n</sub>.  one has either P(F) = 0 or P(F) = 1;
</p>


</div>
</div>
<div id="footnotes">
<h2 class="footnotes">Footnotes: </h2>
<div id="text-footnotes">
<p class="footnote"><sup><a class="footnum" name="fn.1" href="#fnr.1">1</a></sup> The general theory of stochastic popoulation process, by J.E.MOYAL
</p>
<p class="footnote"><sup><a class="footnum" name="fn.2" href="#fnr.2">2</a></sup> <a href="http://en.wikipedia.org/wiki/Generating_function">http://en.wikipedia.org/wiki/Generating_function</a>
</p>
</div>
</div>
<div id="postamble">
<p class="author"> Author: sijin
<a href="mailto:sijin@ubuntu.ubuntu-domain">&lt;sijin@ubuntu.ubuntu-domain&gt;</a>
</p>
<p class="date"> Date: 2012-03-23 17:39:37 HKT</p>
<p class="creator">HTML generated by org-mode 6.33x in emacs 23</p>
</div>
</div>
</body>
</html>
