# awesome-GP
This is a curated list of sources related to Gaussian Process, including papers, discussions, implementations and applications. 

Gaussian Process is the main focus of my phd study. Its mathematicla elegance, numerical efficiency and emprical effectiveness make it a invaluable tool in many fields.

I plan to include all resources I can find related to Gaussian process in this repo. It should include the following topics:

1. Mathematical foundation: Stochastic process, mathematical introduction to Gaussian process, reproducing kernel Hilbert space, Mercer's theorem, etc.
2. Real world Applications: Gaussian process regression/classification, Bayesian optimization, Uncertainty quantification, PDE solvers etc.
3. Numerical Efficiency: Training an exact GP is of $O(N^3)$ cost. Therefore, many approximate GP has been proposed to make it more scalable.
4. Implementations: Due to its popularity, many research group has relased packages for GP, inlcuding GPytorch, Jax-GP, Falkon etc.
5. GP in practice: Although GP is a great model to use, there are many issues occurring when blindly using GP, especially for safe-crtical applications. Therefore, some issuse like model misspecification, model calibration and model validation should be discussed in details.
6. Advanced topics: relationship between GP and Deep neural nets, GP on mainfolds, GP and kernel methods.




# uncertainty quantification:

When training a GP for a task where uncertainty quantification matters, like safe-critical applications, active leanring and Bayesian optimization, choosing the kernel and its parameters is a very important topic.
The following articles discuss this topic rigorously.

1. Comparing Scale Parameter Estimators for Gaussian Process Regression: Cross Validation and Maximum Likelihood (This paper proves cross validation is better for choosing scale parameter than using maximum likelihood since it's asymptotically well calibrated.)
2. Posterior and Computational Uncertainty in Gaussian Processes (Approximate GP methods will also introduce computational uncertainty, this papers proposed an algorithm to combine the computational unceratinty with the mathematical uncertainty for better UQ.)

 
