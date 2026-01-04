# SolveWithExcel – Challenge #4
## Flagging High-Risk Orders with Conditional Logic

This challenge focuses on using conditional logic in Excel to automatically flag high-risk orders based on predefined business rules. You will build calculated columns and a live summary that updates as data changes—no manual tagging required.

This pattern is widely used in finance, operations, audit, and compliance reporting.

# Difficulty

Early Intermediate
Estimated Time
15–25 minutes

# The Problem

You are given a list of customer orders.
Some orders may pose higher financial or operational risk based on quantity, price, or total value.

Your task is to:

Calculate the total value of each order
Automatically flag orders that meet risk criteria
Produce a small summary showing how many risky orders exist
All logic must be implemented using Excel formulas.

# Dataset

Orders columns:

Order ID
Customer
Order Date
Quantity
Unit Price

# Business Rules

An order is considered High Risk if any of the following conditions are met:

Quantity ≥ 10
Unit Price ≥ 500
Order Value ≥ 10,000

If none of these conditions apply, the order is considered Normal.

# Your Tasks

## 1. Calculate Order Value

Add a calculated column:

Order Value = Quantity × Unit Price

## 2. Flag High-Risk Orders

Create a Risk Flag column that returns:

"High Risk" if any rule is met
"Normal" otherwise

Use clear, readable conditional logic.

## 3. Build a Summary

Create a small summary that shows:

Total number of orders

Number of high-risk orders

The summary must update automatically.

# Requirements

Use Excel formulas only
No manual tagging
No Pivot Tables required
Logic must remain readable and maintainable

# Learning Objectives

By completing this challenge, you will practice:

Applying conditional business rules in Excel
Using IF and OR for decision logic
Building exception-based reporting
Creating audit-friendly spreadsheets

# Files Included

solvewithexcel_challenge_4_solution_hidden.xlsx
→ Blank calculation cells for learners

solvewithexcel_challenge_4_solution_revealed.xlsx
→ Completed formulas for reference

# Next Challenge

In the next challenge, you will:

Add conditional formatting for visual alerts
Extend rule logic with thresholds and categories
Prepare the dataset for monitoring dashboards

# About SolveWithExcel

SolveWithExcel focuses on solving real-world business problems using Microsoft Excel through practical, challenge-based learning.

Visit https://solvewithexcel.org
 to learn more.
