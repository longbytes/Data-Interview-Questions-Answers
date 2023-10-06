# Probability Interview Questions & Answers

---
**Note:**
- Before jumping into the list of questions and answers, it's beneficial to review the following key concepts.
- For each concept, ask yourself this question to make sure you grasp the definition and applications: "Explain [the concept] in your own words and describe a real-world situation where it can be applied."
## KEY CONCEPTS
- The Bayes Theorem
- Conditional probability
- Normal distribution
- Uniform distribution
- Bernoulli distribution
- Binomial distribution
- Geometric distribution
- Poisson distribution
- Exponential distribution
- Deriving the mean and variance of distributions
- Central Limit Theorem
- The Birthday problem
- Card probability problems
- Die roll problems

---
## QUESTIONS

## Easy
### The Bayes' Theorem
- Explain Bayes' Theorem in your own words and describe a real-world situation where it can be applied.
- Given a medical test that has a 95% probability of detecting a disease when it is present and a 5% probability of indicating the disease when it's not present. If 1% of the population has the disease, what is the probability that a person with a positive test result actually has the disease?
- Why is Bayes' Theorem important for data analysts and data scientists in making predictions based on prior knowledge?

### Conditional Probability
- Define conditional probability and provide an example.
- If P(A) = 0.5, P(B) = 0.4, and P(A and B) = 0.2, what is P(A|B)?
- How is conditional probability different from joint probability?

### Normal Distribution
- What properties define the normal distribution?
- Why is the normal distribution significant in statistics and data science?
- Given a dataset with a mean of 50 and a standard deviation of 10, what percentage of the data lies between 40 and 60?

### Uniform Distribution
- Describe a situation where a uniform distribution might be applicable.
- What are the mean and variance of a continuous uniform distribution defined between a and b?
- How does the probability density function of a uniform distribution look?

### Bernoulli Distribution
- Define a Bernoulli trial and give an example.
- How does the probability mass function of a Bernoulli distribution look?
- What are the mean and variance of a Bernoulli distribution?

### Binomial Distribution
- Under what conditions is a binomial distribution used?
- Given 10 trials with a success probability of 0.2, what is the probability of achieving exactly 3 successes?
- How does the binomial distribution change as the number of trials increases?

### Geometric Distribution
- Describe the geometric distribution and its application.
- If the probability of success in a trial is 0.3, what's the expected number of trials to get the first success?
- How is the geometric distribution different from the binomial distribution?

### Poisson Distribution
- When is it appropriate to use the Poisson distribution?
- Given a mean rate of 5 events per hour, what is the probability of observing exactly 7 events in an hour?
- How is the Poisson distribution related to the binomial distribution?

### Exponential Distribution
- Explain the relationship between the Poisson and exponential distributions.
- If the average time between events is 10 minutes, what is the probability that the next event will occur within the next 5 minutes?
- Describe a scenario where the exponential distribution might be useful.

### Deriving the Mean and Variance of Distributions
- How do you compute the mean and variance of a discrete probability distribution?
- Why is understanding the mean and variance important for a data analyst or data scientist?
- What does a variance of zero indicate about a distribution?

### Central Limit Theorem
- What is the Central Limit Theorem and why is it important?
- If you were to take repeated samples of size n from a population, how would the distribution of sample means look as n increases?
- Why is the Central Limit Theorem crucial for hypothesis testing?

### The Birthday Problem
- Describe the Birthday Paradox. How is it counterintuitive?
- What is the probability that in a group of 23 people, at least two share the same birthday?
- How does the probability change as the size of the group increases?

### Card Probability Problems
- If you draw a card from a standard deck, what is the probability it's a heart or a queen?
- What is the probability of drawing 2 aces in a row from a shuffled deck of 52 cards?
- How many ways can you arrange 5 cards drawn from a standard deck?

### Die Roll Problems
- What's the probability of rolling a sum of 7 with two six-sided dice?
- If you roll a fair six-sided die three times, what is the probability of rolling at least one 6?
- How would you calculate the expected value of a single die roll?

## Hard
### The Bayes Theorem
- Given two correlated events A and B, where event B has a known probability distribution, how would you leverage Bayes' theorem to estimate the distribution of event A when B is observed?
- How would you deal with situations where the prior probabilities required for Bayes' theorem are not available or are unreliable?
- Discuss the potential pitfalls of using Bayes' theorem in model updating and prediction in a real-world application you've encountered.

### Conditional Probability
- In a Bayesian network with multiple nodes and dependencies, how do you calculate the conditional probability of an event considering evidence from multiple observed variables?
- Discuss a scenario where naive assumptions about conditional independence could lead to incorrect results.
- Given a high-dimensional dataset, how would you estimate conditional probabilities without running into the "curse of dimensionality"?

### Normal Distribution
- Explain how skewness and kurtosis can affect the applicability of the normal distribution in modeling real-world data.
- Describe a scenario where a normal distribution assumption in a machine learning model led to poor results.
- Discuss methods for assessing the normality of a dataset and potential transformations that can be applied.

### Uniform Distribution
- In the context of Monte Carlo simulations, discuss potential issues with relying solely on uniformly generated random numbers.
- How can you test whether a given set of data follows a continuous uniform distribution, especially in high dimensions?
- Discuss the impact of discretization or binning on a truly continuous uniform variable.

### Bernoulli Distribution
- Describe the relationship between the Bernoulli and binomial distributions in the context of Bayesian modelling.
- Discuss potential issues when using a Bernoulli-distributed variable as a feature in machine learning models.
- Given a set of data that should follow a Bernoulli distribution, explain methods to detect outliers.

### Binomial Distribution
- Discuss the relationship between the binomial and Poisson distributions and the conditions under which they become equivalent.
- Given a dataset believed to follow a binomial distribution, how would you validate this assumption?
- Describe potential issues when modelling a highly imbalanced binary outcome using the binomial distribution.

### Geometric Distribution
- Discuss the memoryless property of the geometric distribution in the context of queueing models.
- In modelling time-to-event data, under what conditions would a geometric distribution be more appropriate than an exponential distribution?
- Given a time series that's believed to follow a geometric distribution, describe a methodology to test this hypothesis.

### Poisson Distribution
- Describe the relationship between the Poisson and exponential distributions in terms of events and inter-event times.
- Discuss potential issues in using the Poisson distribution to model rare events.
- Given a dataset of events over time, how would you test for overdispersion relative to a Poisson assumption?

### Exponential Distribution
- In reliability analysis, how is the exponential distribution used to model component failures?
- Describe a method to test if time-to-event data deviates from an exponential distribution due to a non-constant hazard function.
- Discuss the differences and similarities between the exponential and geometric distributions in modelling time-to-event data.

### Deriving the Mean and Variance of Distributions
- Discuss the implications of infinite mean or variance in the context of modelling financial data.
- Describe a scenario where using higher moments (beyond mean and variance) significantly impacted a model's performance.
- How do you handle issues of non-finite mean or variance in practical data analysis?

### Central Limit Theorem
- Describe a situation where the assumptions of the Central Limit Theorem do not hold, and discuss potential remedies.
- How would you determine the minimum sample size needed for the Central Limit Theorem to give a reasonably accurate approximation?
- Discuss the implications of heavy-tailed distributions in the context of the Central Limit Theorem.

### The Birthday Problem
- Extend the Birthday problem to consider the probability that at least three people share the same birthday in a group. How does the result compare to the classic problem?
- How would you generalize the Birthday problem to a situation with a non-uniform distribution of birthdays?
- Discuss the real-world implications of the Birthday problem in the context of hashing and cybersecurity.

### Card Probability Problems
- What is the probability of drawing a sequence of King, Queen, and Jack (in that order) from a shuffled deck without replacement?
- Given a hand of 5 cards, how would you calculate the probability of it being a specific type of poker hand, such as a full house?
- Discuss the computational challenges and potential solutions in evaluating probabilities in complex card games like bridge.

14. Die Roll Problems
- Given a biased die where the probability of rolling a 6 is twice as likely as rolling any other single number, calculate the entropy of this die.
- Discuss the implications of using a non-fair die in statistical simulations and potential methods for correction.
- Given a sequence of die rolls, how would you test the hypothesis that the die is fair?
