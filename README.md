## NCAA-march-madness-competition

#### The IPython notebook '2019 NCAA march madness competition.ipynb' provides a modeling pipeline to understand and predict the NCAA march madness tournament outcomes. It compares different models (linear regression, logistic regression, support vector classification and decission tree) and features to analyze, visualize and predict the outcome of the NCAA march madness competition 2019. Overall, a simple logistic regression performs the best, once specific features have been carefully choosen.

### Takeaways
#### + Feature visualization reveals correlations
#### + Data over years is noisy and fluctuates
#### + Different models perform similarly
#### + Features matter more than models!
#### + Reducing the number of features results in better averaged results.

### Context of results
- Lower bound: Coin toss has 50% accuracy (random guess)
- This works result: ≈ 68% accuracy
- Upper glass ceiling: ≈ 74-78% for sports predictions in general (see **)
                        (NBA ≈ 72-74%)
- Experts: ≈ 68% accuracy

Room for improvement for next years 2020 NCAA march madness tournament:
- Use expert ratings/ranking, elo scoring system, etc…, for next years march madness competition
- Apply forward/backward feature selection
- Check for synergy effects and additivity property of features in model

**A. Zimmermann, S. Moorthy, Z. Shi, Predicting college basketball match outcomes using machine learning techniques: some results and lessons learned.  [CoRRabs/1310.3607](https://dblp.org/db/journals/corr/corr1310.html), (2013).


### Number of features versus accuracy of model
![Number of features versus accuracy of model](https://github.com/anose001/NCAA-march-madness-competition/blob/master/Features_vs_accuracy.png)


### Correlation of features
![Correlation of features](https://github.com/anose001/NCAA-march-madness-competition/blob/master/Feature_Correlation.png)


### Model comparison
![Model comparison](https://github.com/anose001/NCAA-march-madness-competition/blob/master/Models_Compared_4_features.png)


### Weight of coefficients
![Weight of coefficients](https://github.com/anose001/NCAA-march-madness-competition/blob/master/Coefficient_Weight.png)
