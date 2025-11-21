# Assignment 6 Part 1 - Writeup

**Name:** Juan Torres  
**Date:** 11/21/25

---

## Part 1: Understanding Your Model

### Question 1: R² Score Interpretation
What does the R² score tell you about your model? What does it mean if R² is close to 1? What if it's close to 0?

**YOUR ANSWER:**

The R^2 score measures the variance and how close it is to actual values. It means it is very close to actual values. If it is close to 0 it means it performs poorly in predicting. 


---

### Question 2: Mean Squared Error (MSE)
What does the MSE (Mean Squared Error) mean in plain English? Why do you think we square the errors instead of just taking the average of the errors?

**YOUR ANSWER:**

MSE means how off the models predictions are from actual values. I think we square because it is possible to have negative values and it would give a skeewed average. Squaring it allows for us to eleminate this error.


---

### Question 3: Model Reliability
Would you trust this model to predict a score for a student who studied 10 hours? Why or why not? Consider:
- What's the maximum hours in your dataset?
- What happens when you make predictions outside the range of your training data?

**YOUR ANSWER:**

I would but i would also be cautious. The maximum hours set are 9 and the model could probably give a close answer but it can also be off so you could trust it to an extent. 


---

## Part 2: Data Analysis

### Question 4: Relationship Description
Looking at your scatter plot, describe the relationship between hours studied and test scores. Is it:
- Strong or weak?
- Linear or non-linear?
- Positive or negative?

**YOUR ANSWER:**
It is strong, linear, and positive. 



---

### Question 5: Real-World Limitations
What are some real-world factors that could affect test scores that this model doesn't account for? List at least 3 factors.

**YOUR ANSWER:**
1. Amount of hours slept
2. Stress levels
3. If the person ate or not


---

## Part 3: Code Reflection

### Question 6: Train/Test Split
Why do we split our data into training and testing sets? What would happen if we trained and tested on the same data?

**YOUR ANSWER:**

We split so that it can start with an idea of our data. Then we compare to the actual data to see how close it was in its predictions. If we trained and tested on the same data it the model will already have seen it so it will memorize instead of predicting. 


---

### Question 7: Most Challenging Part
What was the most challenging part of this assignment for you? How did you overcome it (or what help do you still need)?

**YOUR ANSWER:**

The most challenging part was making the graphs. The math model itself was pretty easy but being able to make the actual graph and get the points was challening because I did not have any previous knowledge on how to code it. I overcame it by useing the sample as reference. This helped immensly as I managed to get the graphs right.


---

## Part 4: Extending Your Learning

### Question 8: Future Applications
Describe one real-world problem you could solve with linear regression. What would be your:
- **Feature (X):** 
- **Target (Y):** 
- **Why this relationship might be linear:**

**YOUR ANSWER:**

weight tracker
X = calories
Y= weight gained
The more you intake the more you usually gain so it is a positive corrlation and linear.

---

## Grading Checklist (for your reference)

Before submitting, make sure you have:
- [ ] Completed all functions in `a6_part1.py`
- [ ] Generated and saved `scatter_plot.png`
- [ ] Generated and saved `predictions_plot.png`
- [ ] Answered all questions in this writeup with thoughtful responses
- [ ] Pushed all files to GitHub (code, plots, and this writeup)

---

## Optional: Extra Credit (+2 points)

If you want to challenge yourself, modify your code to:
1. Try different train/test split ratios (60/40, 70/30, 90/10)
2. Record the R² score for each split
3. Explain below which split ratio worked best and why you think that is

**YOUR ANSWER:**
