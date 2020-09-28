## The Problem

The students give many different answers to the same problem and what we looking for is to build an algorithm that would classify 
these answers to either correct (fill mark), partially correct (partial mark) or not correct (zero mark). These mark should be 
assigned with some probability measures, i.e make sure we did the marking correctly with a confident probability $P$ to see the
efficiency of the algorithm. 


## Classification Algorithms

The plan is to use different calcifying algorithms, and then we can compare the efficiency of each algorithm in order to choose the most 
efficient one. 

For now, I will focus on the "binary classification problem" in which $y$ vector "The answer weather is correct or not" can take on only 
two values, $0 == not correct$ and $1 == correct$. We can extend this later on with more precise outcome, when we could give the students 
partial mark, for example  y = [0,0.5,1] "when I got to have more experience and knowledge about the algorithm". 

If we build a marking classifier, then features vector $x^{(i)}$ is going to be the students answers; and $y \in {1,0}$ - $1$ if it is the 
correct answer, and $0$ otherwise. Hence, $y \in {0,1}$. $0$ is also called the negative class  $“-”$, and $1$ the positive class $“+”$, 
given $x^{(i)}$, the corresponding $y^{(i)}$ is also called the label for the training example. 

## The Data

We are going to take the response data to classify it into correct or incorrect.  This data is going to be divide into two sets: a training
set, where we are going to used it to train the model; and testing set where we use this set to test the model.

For now, we are going to use responses that include only numbers.
The EGMA $2017$ JNR assessment is a good example to use for e.g. measure $6843$ (sorted accordingly in the google files)






