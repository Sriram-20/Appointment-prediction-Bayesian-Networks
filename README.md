# Appointment-prediction-Bayesian-Networks

A Bayesian network is a data structure that represents the dependencies among random variables. 

# Equation

![image](https://user-images.githubusercontent.com/64577383/163217795-001efe08-8eb3-48be-be90-d95e1b62a4aa.png)

The equation to prediction the probability - P(Appointment, light, no) is equal to α[P(Appointment, light, no, delayed) + P(Appointment, light, no, on time)].

1. First, we create the nodes and provide a probability distribution for each one.
2. We create the model by adding all the nodes and then describing which node is the parent of which other node by adding edges between them.
3. We want to predict what is the probability that there is no rain, no track maintenance, the train is on time, and we attend the meeting.
4. Otherwise, we could use the program to provide probability distributions for all variables given some observed evidence.
