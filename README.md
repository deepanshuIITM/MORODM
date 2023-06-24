# MORODM
## Multi-objective Robust Optimization and Decision-making using Evolutionary Algorithm

![R-NSGA-III](https://github.com/deepanshuIITM/MORODM/assets/137225940/9004e11b-f8c1-41ee-84ab-c5df11a07198)

**Fig: Working of R-NSGA-III**


**Preliminary Requirements**

[1] _pymoo_ toolbox by Julian Blank.

[2] NSGA-III concept has been used from [2].

[3] The definition of robustness is given in [3].

[4] Details of R-NSGA-III is given in [4].

The existing EMO literature on robustness studies emphasized on finding the entire robust front, 
but hardly considered robustness in both optimization and decision-making tasks. In this work, 
we propose and evaluate different algorithmic implementations of three aspects – multi-objective 
optimization, robustness consideration, and multi-criterion decision-making – together. Based on 
experimental results on two to eight-objective problems, we discuss the outcomes and advantages of 
different integration approaches of these three aspects and present the most effective combined approach. 
The work should pave the way to develop more efficient multi-objective robust optimization and 
decision-making (MORODM) procedures for handling practical problems with uncertainties

![image](https://github.com/deepanshuIITM/MORODM/assets/137225940/48e57700-d6d1-4c70-a534-3d57a66cd27c)


**Fig. R-NSGA-III for MCDM**


![image](https://github.com/deepanshuIITM/MORODM/assets/137225940/a6b70478-b5fe-49b8-ae2b-4171e58dd96d)


**Fig. Four different schemes for Multi-objective Robust Optimization and Decision-making**


![image](https://github.com/deepanshuIITM/MORODM/assets/137225940/3014226a-ce5b-48f5-b285-285315902056)


**Fig. Scheme-4 for 3-objective test problem**

![image](https://github.com/deepanshuIITM/MORODM/assets/137225940/79a1d45b-c9f5-4312-a54b-3111d53215f3)


**Fig. Scheme-4 for 8-objective test problem**


**References:**

[1]. Blank, J., & Deb, K. (2020). Pymoo: Multi-objective optimization in _python_. IEEE Access, 8, 89497-89509.

[2]. Deb, K., & Jain, H. (2013). An evolutionary many-objective optimization algorithm using reference-point-based nondominated sorting approach, part I: solving problems with box constraints. IEEE transactions on evolutionary computation, 18(4), 577-601.

[3]. Deb, Kalyanmoy, and Himanshu Gupta. "Searching for robust Pareto-optimal solutions in multi-objective optimization." Evolutionary Multi-Criterion Optimization: Third International Conference, EMO 2005, Guanajuato, Mexico, March 9-11, 2005. Proceedings 3. Springer Berlin Heidelberg, 2005

[4]. Vesikar, Yash, Kalyanmoy Deb, and Julian Blank. "Reference point based NSGA-III for preferred solutions." 2018 IEEE symposium series on computational intelligence (SSCI). IEEE, 2018.
