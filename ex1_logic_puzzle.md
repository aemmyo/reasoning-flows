# Objective: Guide the model to solve a problem with explicit reasoning.

## Write a logic puzzle (e.g., "Alice is older than Bob, Bob is older than Carol. Who is the youngest?").

Three friends — Ada, Bola, and Chidi — are standing in a line.

Ada is not at the front.

Bola is behind Chidi.

Chidi is not at the back.

Question:
Who is standing at the front? 

##  Prompt the model: "Explain your reasoning before giving the final answer."

### Puzzle

Three friends — Ada, Bola, and Chidi — are standing in a line.

Ada is not at the front.

Bola is behind Chidi.

Chidi is not at the back.

Question: Who is standing at the front?

### Reasoning

There are three positions in the line:

Front — Middle — Back

Step 1: Use the clue

Chidi is not at the back.

So Chidi can be:

Front ✅

Middle ✅

Back ❌

### Step 2: Use the clue

Bola is behind Chidi.

This means Bola must stand after Chidi in the line.

So Chidi cannot be at the back (already known), and Bola cannot be in front of Chidi.

### Step 3: Test possible positions

If Chidi is in the middle, then Bola must be behind → Bola goes to the back.

Now the remaining position (front) is for Ada.

But Ada is not allowed at the front

So this arrangement is impossible.

### Step 4: Try another valid position

If Chidi is at the front, then Bola can stand behind Chidi (middle or back).

Ada cannot be at the front, which is satisfied.

A valid order becomes:

Front: Chidi
Middle: Ada
Back: Bola

All conditions are satisfied 

Final Answer

 Chidi is standing at the front.

## Verify that the model provides step-by-step reasoning followed by the correct answer.

The model followed the instruction by presenting clear step-by-step reasoning before giving the final answer. Each condition in the puzzle was logically analyzed and invalid arrangements were eliminated. The final answer satisfies all constraints, confirming both correct reasoning and correctness of the solution.