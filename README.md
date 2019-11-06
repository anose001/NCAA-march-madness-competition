## NCAA-march-madness-competition

#### The IPython notebook '2019 NCAA march madness competition.ipynb' provides a modeling pipeline to understand and predict the NCAA march madness tournament outcomes. It compares different models (linear regression, logistic regression, support vector classification and decission tree) and features to analyze, visualize and predict the outcome of the NCAA march madness competition 2019. Overall, a simple logistic regression performs the best, once specific features have been carefully choosen.

### Takeaways
#### + Feature visualization reveals correlations
#### + Data over the years can be noisy and fluctuate
#### + Models can perform similarly
#### + Features matter more than models!
#### + Reducing the number of features can result in better averaged results.

### Context of results
- Lower bound: Coin toss has 50% accuracy (random guess)
- Our results: ≈68%
- Upper glass sealing: ≈74-78% for sports predictions in general (see **)
                        (NBA ≈ 72-74%)
- Experts: ≈68%

Room for improvement:
- Use expert ratings/ranking, elo scoring system, etc…, for next years march madness competition

**A. Zimmermann, S. Moorthy, Z. Shi, Predicting college basketball match outcomes using machine learning techniques: some results and lessons learned.  [CoRRabs/1310.3607](https://dblp.org/db/journals/corr/corr1310.html), (2013).

[![Number of features versus accuracy of model](https://github.com/anose001/NCAA-march-madness-competition/blob/master/Features_vs_accuracy.png)]
