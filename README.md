# BlogPosts
Blog-like posts to help solidfy understanding of mathematical underpinnings of machine learning techniques as well as help other people that are trying to self-learn or just looking for another resource to grasp the concepts.

I'm open to suggestions on potentially changing somethings about my future posts. Just make a pull request and I'll review and we can have a discussion through that interface.

Post #1: Regression - IN PROGRESS (Current notebook needs work - don't judge just yet) - to be posted TBD

Outline-
(1) Simple Regression
(2) Multiple
(3) Significance Testing
(4) Subset Selection / Regularization
(5) Non linear extensions (splines / polynomials)
(6) Bias and Variance trade off and how it relates to models found in (1), (2), (4) and (5)


Possible Themes: - Write down an outline for these. Put in 3 things of stuff I've already written that should go in each and 3 things that shouldn't - and then stuff that needs to be addded
Demystifying ML (1) Intro part (2) Non linear extensions (3) Signficance testing ...Need to add: (1) Current ML techniques (2) Discussion of ML's limitations

(DO THIS ONE NOW) reducing complexity or increasing complexity - pros and cons complexity vs simplicty (1) Significance testing (2) Subset Selection / Regularization (3) Non linear extensions (4) Bias and Variance ...Need to add: (1) More techniques to compare and discuss complexity (2) discussion on available on having enougn / the right data to make certain complex models make sense (3) PCA / SVD / Other LA topics

Outline:
(1) Summary of what makes a model more 'complex'
(2) Brief summary of pros and cons of simpler models (easier to interpret, no overfitting etc..) and complex models (better fits, most things trying to model are potentially complex, if have a lot of data to train on less risk of overfitting etc..)
(3) Discuss bias and variance tradeoff (use ESL and Learning from Data explanation and visuals to help). This can be introduced as a more mathy way of looking a the trade offs between simple and complex models
(4) Cover significance testing and how it can be applied to parameter coefficients to determine if the amount of complexity can even be 'supported' by the data we have. Could have parameter coefficients that are insignificant so cannot really make an estimate on its impact on the model (this might just be a conversation of reduced chi squared / chi squared testing)
(5) Talk about subset selection and regularization techniques that can take a more complex model and pare it down to a simpler model
(6) Talk about PCA and then discuss how SVD and other relevant LA topics are required for things like PCA and how to interpret them
(7) Talk about going the other direction of taking a simplistic model and adding complexity through techniques like regression splines

significance testing - how do we know if the model we choose are valid or not? (1) Significance testing (2) subset selection / regularization (3) Non linear extensions ...Need to add: (1) Table of signficance tests (start from ISL) (2) In depth discussion on p-values (3) How this is used in real applications / how this relates to the most current ML techniques


Mathematical validity between regression vs  deep learning (deep dive into P value and more into Deep Learning) (1)Significance Testing (2) Non linear extensions (splines / polynomials)  ...Need to add: (1) Deep learning overview and motivations (2) Comparison of pros and cons on deep learning vs other simpler techniques and situations where each one is better or worse.


