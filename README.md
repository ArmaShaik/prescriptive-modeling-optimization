# 🍽️ Prescriptive Modeling: Meal Plan Optimization

This project demonstrates a **Mixed Integer Programming (MIP)** optimization model built using **Pyomo** and the **CBC solver** in Python. I developed an optimization model that creates **cost-effective and balanced weekly meal plans** (breakfast, lunch, dinner, and fruit) that meet specific nutritional guidelines. The solution is ideal for individuals or institutions looking to **optimize meal planning** while staying healthy and budget-friendly.

---

## 🔍 Project Summary

I built an MIP model that helps design a 7-day meal plan using a combination of breakfasts, lunches, dinners, and fruits while:

- Satisfying **daily nutritional requirements** (calories, protein, carbs and fat)
- **Minimizing total cost** across the entire week
- Ensuring variety across meals
- Avoiding repetition of the same food item multiple times a day

The model outputs a personalized meal plan that is not only **nutritionally balanced** but also **cost-efficient**. It can easily be adapted for **personal use, institutional meal planning**, or even **diet-restricted programs**.

---

## 🧠 Optimization Model

**Objective:**  
Minimize total meal cost over the week.

**Decision Variables:**

- `x1[day, breakfast]` → 1 if a specific breakfast is chosen on a given day  
- `x2[day, meal, lunch/dinner]` → 1 if a specific lunch or dinner is chosen on a given day  
- `y[day, fruit]` → 1 if a specific fruit is selected on a given day

**Constraints:**

- Exactly one breakfast, lunch, dinner, and fruit per day  
- Total daily intake must meet minimum nutrition requirements for calories, protein, fiber, etc.  
- Avoids food repetition across the same day  
- Limits sugar and sodium intake to healthy thresholds

---

## 🥗 Sample Output (Final Meal Plan)

| Day    | Breakfast                    | Lunch                | Dinner                | Fruit     |
|--------|------------------------------|-----------------------|------------------------|-----------|
| Day 1  | Eggs and toast               | Black Bean Bowl       | Quinoa Salad           | Strawberry|
| Day 2  | Pancakes                     | Spaghetti             | Soup                   | Orange    |
| Day 3  | Yogurt with granola          | Pizza                 | Taco Bowl              | Banana    |
| Day 4  | Avocado toast with egg       | Quinoa Salad          | Veggie Burger          | Apple     |
| Day 5  | Granola with milk            | Veggie Stir Fry       | Grilled Chicken Salad  | Orange    |
| Day 6  | Smoothie (Banana, Spinach…) | Cauliflower Rice Bowl | Quinoa Salad           | Banana    |
| Day 7  | Oatmeal with fruit           | Chicken Bowl          | Grilled Salmon         | Grapes    |

---

## ✅ Features

- MIP model with multiple constraints and realistic diet goals  
- Output is human-readable and interpretable (printed in weekly format)  
- Flexibly scalable for any number of meals, nutrients, or days  
- Solver: CBC (open-source and free)

---

## 📁 Files Included

| File Name                        | Description                                      |
|----------------------------------|--------------------------------------------------|
| `Prescriptive_Final.ipynb`      | Python code with Pyomo model + output            |
| `Presentation_Prescriptive.pdf` | Executive-level project summary slides (5-min)   |
| `SampleInput.png`               | Simulated input used for optimization            |
| `FinalOutput.png`               | Visual of optimized meal plan                    |
| `README.md`                     | Project overview and explanation (this file)     |

---

## 👩‍💻 My Role

I individually scoped, built, and tested this project end-to-end:

- Defined the problem and nutrition/diet constraints  
- Designed the optimization model (objective, variables, constraints)  
- Wrote Pyomo code and implemented with CBC solver  
- Simulated realistic input data  
- Created output visualizations and a business-style presentation  

---

## 🧰 Tools & Technologies

- Python (Colab)
- Pyomo (Mixed Integer Programming)
- CBC solver
- Linear algebra, constraint modeling
- PowerPoint (for executive communication)

---

## 📬 Let’s Connect!

If you're working on something interesting in analytics, optimization, or tech-driven innovation — I’d love to chat!

📧 [Email me](mailto:arma.rahamath@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/armashaik/)  
💻 [More Projects](https://github.com/ArmaShaik)

---
