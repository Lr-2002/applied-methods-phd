## 写在前边
本仓库是 <a href="https://github.com/paulgp/applied-methods-phd">paulgp的仓库</a>
 的中文译版，希望能够帮助国内有兴趣的同学<br>
与之同时，也希望能够提高自己的英文水平和技术水平，与诸君共勉

ps: 标红的是因为暂时没有确切的描述语

# <font color =red>实用的经验方法（有待商榷）</font>
### 课程主页
1. [github仓库](https://github.com/paulgp/applied-methods-phd)
2. [耶鲁课程主页](https://yale.instructure.com/courses/64286)（似乎只支持耶鲁学生）
3. [非耶鲁学生(Youtube)](https://www.youtube.com/playlist?list=PLWWcL1M3lLlojLTSVf2gGYQ_9TlPyPbiJ)

### 课程简介
本课程主要面向<font color=red>对经济学方法在经验研究中的应用</font>的在校学生<br>
我希望这节课能够让大家对不同的经验方法有大概的了解，同时能够深入实践<br>
同时呢，我也会为大家提供一系列的ppt和笔记以供参考，还有相关的论文作为支撑

简而言之，我会在本课上为大家呈现我对常用的经验方法的观点和看法<br>
也就是说，这节课并不会过多关注<font color =red>条条框框的细节</font>（除非的确重要），而是将重点放在那些论文中常见的框架。同样地，我也会尽力讲清楚这些主题如何自洽

本课程的重点是讨论和动手，希望本节课能让大家得到这三种东西：
1. 首先是了解大量的经验方法，并且至少熟悉这些方法的优点。当你需要用到这些方法的时候，就知道去哪里复习了。
2. 其次，大量用到的经济学术语不会那么令人畏惧。当别人说什么”我用了半参数推断法“的话时，你不会觉得这很难，只会觉得这个人没有讲清楚具体的意思。
3. 最后，你会接触到很多论文的底层框架和他们推理的实验
   
## 作业
每周都会布置一些作业。包括理论计算和分析数据的机试作业。你可以使用任何你想用的库。解决方法会由 R.Since 给出，为了能够保证课程进度，我会拒收晚交的作业。如果你已经预料到ddl时候作业会交火，你可以提前问我作业并用大量额外时间来完成作业。

你们可以相互讨论问题的解法，但必须独立完成作业并上交。成绩会由作业的完成程度决定。

我希望你们用脚本来写这些作业。对于特定的问题，我会指定你们适用的第三方库。例如，当计算线性回归问题的时候，我不希望只是获得 
$y = kx + b$，
相反，我会要求大家构建两个矩阵，并通过矩阵的方法进行计算。
<br>
我也希望你们能够在本科中掌握不错的编程能力，当然，这可能对那些不擅长编程的同学有点挑战，所以，请合理安排。我不会讲述课外的编程知识，你们可以了解一下有关R语言的资源自行学习。（在此感谢Max Kasy 组织这些材料）：
   1. [R语言基础介绍（英文版）](https://cran.r-project.org/doc/manuals/r-release/R-intro.pdf)
   2. [R数据科学（中文版）](https://www.ituring.com.cn/book/2113)
   3. [数据可视化（英文版）](https://socviz.co/)

## 参考文献：
以下是一部分课程中会提到的书目：
1. Joshua Angrist and Jörn-Steffen Pischke,  *Mostly Harmless Econometrics*
2. Scott Cunningham,  *Causal Inference: The Mixtape*,  https://mixtape.scunning.com/
3. Benjamin T. Miller and Peter M. Aronow, *Foundations of Agnostic Statistics*
4.  Kieran Healy, *Data Visualization: A Practical Introduction*, https://socviz.co/
   
## 讲座（教学大纲）
（暂时还是采用英文方案）
1. **Causality, Statistics, and Economics**
	1. [**Potential Outcomes and Directed Acyclic Graphs**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/01_po_dags.pdf)
	2. [**Research Design, Randomization, and Design-Based Inference**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/02_randomization.pdf)
    3. [**Propensity Scores**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/03_propensity_scores.pdf)
    4.  [**Interference, Spillovers and Dynamics**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/04_interference_dynamics.pdf)
2. **Linear Regression**
	1. [**Inference**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/05_regression_1.pdf)
	2. [**Semiparametrics and Visualization**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/06_regression_2.pdf)
    3. [**Quantile Regression**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/07_regression_3.pdf)
    4. [**Penalized Regression Models**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/08_regression_4.pdf)
3. **Likelihood Methods**
   1. [**Binary Discrete Choice, GLM and Computational Methods**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/09_discrete_choice_1.pdf)
   2. [**Multiple Discrete Choices**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/10_discrete_choice_2.pdf)
   3. [**Duration models**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/11_duration_models.pdf)
   4. [**Hierarchical models + Bayesian Shrinkage**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/12_hierarchical_bayes.pdf)
4. **Canonical Research Designs**
   1. [**Difference-in-differences**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/13_dind.pdf)
   2. [**Event Studies, Synthetic Control + Synthetic DinD**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/14_synthetic_dind.pdf)
   3. [**Instrumental Variables (Part I)**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/15_iv_partI.pdf)
   4. [**Instrumental Variables (Part II)**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/16_iv_partII.pdf)
   5. [**Instrumental Variables (Part III)**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/17_iv_partIII.pdf)
   6. [**Bartik + Simulated Instruments**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/18_bartik_sim_iv.pdf)
   7. [**Examiner Designs aka Judge IV**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/19_judge_iv.pdf)
   8. [**Regression Discontinuity I: Identification and Groundwork**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/20_regression_discontinuity_1.pdf)
   9. [**Regression Discontinuity II: The Checklist**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/21_regression_discontinuity_2.pdf)
   10. [**Regression Discontinuity III: Extensions**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/22_regression_discontinuity_3.pdf)
5. **Machine Learning**
   1. [**Supervised Machine Learning I: Prediction**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/23_machine_learning_1.pdf)
   2. [**Supervised Machine Learning II: Heterogeneous Treatment Effects**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/24_machine_learning_2.pdf)
   3. [**Machine Learning III: Unstructured Data and Unsupervised ML**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/25_machine_learning_3.pdf) 
6. **Miscellaneous**
   1. [**Partial Identification**](https://github.com/paulgp/applied-methods-phd/blob/main/lectures/26_partial_identification.pdf)

