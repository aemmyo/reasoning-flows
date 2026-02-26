# Objective: Use structured prompting to encourage reasoning.

## Choose a math or coding problem (e.g., "Calculate the factorial of 5").

Find the sum of numbers from 1 to 10.

    Prompt the model: "Let's think step by step before answering."

### Step-by-Step Reasoning

We need to add all integers starting from 1 up to 10.

So the calculation is:

1+2+3+4+5+6+7+8+9+10

Step 1: Add progressively

1 + 2 = 3

3 + 3 = 6

6 + 4 = 10

10 + 5 = 15

15 + 6 = 21

21 + 7 = 28

28 + 8 = 36

36 + 9 = 45

45 + 10 = 55

## Step 2: (Faster reasoning method)

We can also use the formula for sum of first n numbers:

Sum=n(n+1)/  2
Sum=
2

Here n=10:

10×11/2=55
2
	​
Final Answer

The sum of numbers from 1 to 10 is 55.

## Compare outputs with and without the reasoning instruction.

| Feature              | Without Reasoning | With Reasoning |
| -------------------- | ----------------- | -------------- |
| Answer length        | Short             | Detailed       |
| Transparency         | Low               | High           |
| Learning value       | Low               | High           |
| Error detection      | Difficult         | Easy           |
| Verification         | Hard              | Easy           |
| Confidence in result | Moderate          | Strong         |

