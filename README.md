# Always Begin with The Logic Problem
### The logic of the code is very simple:
1. decide what kind of universe you want to live in by determining the values of some parameters.
2. feed the program CLASS with the universe you have just decided to live in and CLASS will help you figure out what is it like in it (let's call it 'theoretical data').
3. find Planck 2018 data, which is what 'our' universe is like (let's call it 'observational data'). 
4. Use the observational data to compare with the theoretical data (your customised universe vs. our universe).
5. if the two datasets are perfectly matched -> EXCELLENT! You have just created our universe on your computer!
- (not that easy of course hahaha ;D)
6. if the two datasets are not very well matched -> create another universe and do it again until the two datasets finally reach a consensus.
- (that is, if you want to find what the real universe is like rather than create a brand new one, which is... in most cases... inhabitable)


# Your Questions Answered
1. how to decide what kind of universe you want to live in?
- by creating a .ini file.

2. how to feed the CLASS with the universe you just decided?
- by feeding it with the .ini file you just created.

3. how to find Planck 2018 data?
- hmmm... I am sure I saved it somewhere in this folder. just have a look.

4. how to compare the observational and theoretical data?
- by subtracting them and seeing the residual (plus some statistics).

5. how to know if these datasets are perfectly matched or not?
- by seeing step 6.

6. how to know if these datasets are not well-matched?
- this is the tricky part. I have two ways to deal with it, Maximum Likelihood Estimator (MLE) and Markov Chain Monte Carlo (MCMC).
- MLE: if you keep calculating the residual of the theoretical and observational data, there will be at least one theoretical dataset that generates the smallest residual. this equals to say the 'likelihood' is maximised. that is where MLE gets its name.
- NOTE: MLE has the 'local optimum' problem, which is not what we want. so we don't really use it here.
- MCMC: the author is too lazy to explain, but the take-home message is that it is very complicated. luckily, we don't have to code the MCMC algorithm by ourselves, for there are people who are kind enough to do it for us.

7. I think I have understood everything above. so what now?
- run the class_quick_run.ipynb.
- HAVE FUN!!!