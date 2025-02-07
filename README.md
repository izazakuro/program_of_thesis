# NGC Lab tsun Graduation Thesis

In recent years, the prediction of computation time for the Boolean Satisfiability Problem (SAT) has been actively studied. The SAT problem determines whether a given propositional logic formula is satisfiable, meaning there exists an assignment of variables that makes the formula true. As a fundamental problem in computational theory, SAT is widely known for its NP-completeness. SAT solvers are software tools designed to efficiently solve SAT problems. However, their computation time heavily depends on the characteristics of the given input, with some problems requiring significantly long processing times, which poses a major challenge for practical applications.

The motivation of this study is to explore efficient methods for handling SAT problems that require extensive computation. Quantum computing has been proposed as a potential solution to accelerate SAT problem-solving. However, before its practical implementation, it is crucial to first classify SAT problems based on their expected computation time. Specifically, distinguishing between problems that can be solved quickly and those requiring longer processing times is essential for optimizing solver performance and future quantum computing applications.

Previous research has utilized Graph Neural Networks (GNNs) to analyze the structural properties of SAT problems and predict solver runtime. However, these approaches face challenges in scalability and accuracy, particularly when applied to large-scale SAT problems. To address these issues, this research aims to improve the generalization ability of classification models and enhance the precision of problem classification.

This study proposes a methodology for classifying SAT problems based on solver computation time. We analyze past problems from SAT Competitions held between 2018 and 2024, extracting key numerical features from three distinct categories. Using these features, we construct classification models with Support Vector Machines (SVM) and Random Forest algorithms. The final goal is to evaluate the effectiveness of these models in distinguishing between "quickly solvable problems" and "time-consuming problems."

The findings of this research contribute to the efficient utilization of SAT solvers and lay the groundwork for the integration of quantum computing in SAT problem-solving. This thesis is structured as follows: Chapter 2 provides background knowledge on SAT problems, solvers, and machine learning. Chapter 3 details the proposed methodology and model construction. Chapter 4 presents experimental results and model evaluations. Finally, Chapter 5 summarizes the conclusions and discusses future research directions.
