# Assignment-3-Drawing-inference-from-statistical-models-and-statistical-power

## Setting up a simulation
In light of what you know now about the process of conducting a study with a random sample, use your own words and…
1. Explain the estimate, SE, t-value, and p-value from the regression models that we created previously (m1 and m2).
2. Discuss what contributes to the different results in the two studies (m1 and m2).
3. Why do we use the shaded area in the lower and upper tail of the t-distribution (See Figure @ref(fig:t-dist-fig)).

## Many studies
4. Calculate the standard deviation of the estimate variable, and the average of the se variable for each of the study sample sizes (8 and 40). Explain why these numbers are very similar. How can you define the Standard Error (SE) in light of these calculations?
5. Create a histogram (see example code below) of the p-values from each study sample-size. How do you interpret these histograms, what do they tell you about the effect of sample size on statistical power?
6. Calculate the number of studies from each sample size that declare a statistical significant effect (specify a threshold for , your significance level).
7. Using the pwr package, calculate the power of a one-sample t-test, with a effect size of 1.5/3, your specified significance level and sample sizes 8 and 40. Explain the results in the light of your simulations.

## Many studies without population effect
8. With a significance level of 5%, how many studies would give you a “false positive” result if you did many repeated studies?
