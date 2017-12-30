[Language](../README.md#language)
---
# Conditionals, Part 1

Example of a conditional sentence, someone says:

> If the bicycle needs repair, I will fix it.

Conditional sentences like the one above consist of two parts:

- **antecedent**: *"the bicycle needs repair"*
- **consequent**: *"I will fix it"*

One way of figuring out what the sentence told us is to get clear on what it has **not** told us. He hasn't told us the bicycle needs repair, and he also hasn't told us that he will fix the bicycle. Rather, what he said is that there is some connection between the bicycle needing repair and he fixing it. But what connection? 

Here's a simple answer: by saying the sentence, he has told us that **it's not the case that**:

1. The bicycle needs repair.

    **AND**

2. He won't fix it.

Equivalently, he said that **either**:

1. The bicycle doesn't need repair.

    **OR**
    
2. He will fix it.

## The material conditional theory

    P -> Q
    
    (P implies Q. Read: If P, then Q)

In orders to state the material conditional theory more precisely, we will make use of a device from logic called a **truth table**. A **truth table** is a way of representing hos the truth of a complex sentence depends on the truth values of its parts.
    
### Simple example of conjunction

> The future is uncertain, and the end is always near.

Naturally, someone (*Jim Morrison*) who says this, tells you two things:

- The future is uncertain.

    **AND**

- The end is always near.

Thus, the sentence is true if both the future is uncertain **and** the future is always near, and false if either the future isn't uncertain or the end isn't always near. We draw this dependence of the truth value of the whole sentence on its parts:

The future is uncertain. | The end is always near. | The future is uncertain, and the end is always near.
-------------------------|-------------------------|--------------------------------------------
 True                    | True                    | True
 True                    | False                   | False
 False                   | True                    | False
 False                   | False                   | False

This captures the fact that conditions are true only if both of their conjunctions are true and false otherwise. The conditional sentence, according to the material conditional theory, tells us that both the future is uncertain and the end is always near, since that is the only condition under which it is true.

### Back to our previous sentence

According to the material conditional theory, one tells us that is not the case that the bicycle needs repair and he won't fix it.

The bicycle needs repair. | I will fix it. | If the bicycle needs repair, I will fix it.
--------------------------|----------------|--------------------------------------------
 True                     | True           | True
 True                     | False          | **False**
 False                    | True           | True
 False                    | False          | False
 
Notice that according to the theory, the sentence is true in all rows besides the second. This doesn't seem right. There are some challenges facing the material conditional theory. There are some other theories about what conditionals mean that may perform better.


    

