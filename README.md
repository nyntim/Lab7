# Lab 7 

Tim Nguyen

## Question 1

**Where would you fit your automated tests in your Recipe project development pipeline?**

**Answer: Within a GitHub Action that runs whenever code is pushed.**

This catches bugs immediately on every push in a clean, consistent environment, without relying on developers to remember to run tests locally. Waiting until all development is complete makes regressions expensive and hard to trace to a specific commit.
