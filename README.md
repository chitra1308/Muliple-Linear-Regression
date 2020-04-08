# Muliple-Linear-Regression
Using Backward selection and iteration model  
we should follow the below fundamental checks for rely on model:

          1. Everything IN
          2. Stepwise process:
            a) Backward Selection
            b) Forward Selection
            c)Bi-Direction
          3. Score Check


1.	Everything IN:
It is like of garbage in garbage out. What are variable you are giving to that project it will give the output like that.
If you’re giving an unrelevent data in your project it consume more time and accuracy never good than we are excepted. 

2.	Backward selection:
In this section I going explain of backward selection and their rules.

              1.	Set a significance level may 5% or 1%
              2.	Build a model with the all independent variables
              3.	Check your p values and take highest level of p value in your model :
                       If p|>SL  Reject or eliminate that column and iterate start without that variable
                      4.contiune the step 3 until we are satisfy the rule

           Based on the Backward selection we can able to rely on our model, we are going in a right way.
 3.Score :
	Finally check the score, each iteration we can able to see how much of our model tuning and score increasing when eliminate unrelevant variable. 





