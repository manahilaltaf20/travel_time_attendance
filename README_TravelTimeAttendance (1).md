# 🚌 Is Your Commute Quietly Killing Your Attendance?

### I tracked 30 students' travel time against their attendance — the pattern is almost a straight line.

---

"Sir, traffic thi" — the most common excuse for a missed class.  
But **does distance from campus actually predict absenteeism, or is it just an excuse?**

I surveyed **30 university students** — tracking one-way commute time and semester attendance percentage — then ran real statistical tests to see if commute distance is a genuine academic risk factor.

---

## 🔢 What the Numbers Revealed

📊 **Average one-way commute → 46.4 minutes**
Nearly an hour each way for the average student — almost 1.5 hours a day just getting to and from class.

📉 **Correlation between travel time & attendance → r = −0.9484**
Extremely strong negative relationship. The longer the commute, the lower the attendance — almost every time.

🔴 **P(Low Attendance | Long Commute >45 min) = 86.7%**
Students commuting more than 45 minutes one-way have an **86.7% chance** of falling below 80% attendance.

🔄 **Bayes' Rule result:**
Flip the question — *"A student has low attendance. What's the probability they have a long commute?"*
→ **86.7%**

Not a coincidence. That's the math talking.

---

## 📐 Statistical Concepts Applied

```
✅ Mean, Median, Mode & Standard Deviation
✅ IQR Outlier Detection        (Weiss Definition 3.10)
✅ Contingency Table
✅ Conditional Probability       P(A|B) = P(A∩B) / P(B)
✅ Multiplication Rule
✅ Law of Total Probability      (Weiss Formula 4.8)
✅ Bayes' Rule                   (Weiss Formula 4.9)
✅ Normal Distribution + Z-scores
✅ Confidence Intervals          90% | 95% | 99%
```

---

## 📊 Charts Generated

Running the code produces 6 visualizations:

1. Histogram — Travel Time Distribution
2. Scatter Plot — Travel Time vs Attendance *(r = −0.9484)*
3. Bar Chart — Average Attendance by Travel Time Category
4. Normal Distribution Curve with Empirical Rule
5. Confidence Interval Comparison
6. Bayes' Rule — Prior vs Posterior

---

## 💻 Full Code on GitHub 👇

**[travel_time_attendance.py](./travel_time_attendance.py)**

---

## ▶️ Run It Yourself

```bash
pip install numpy matplotlib scipy
python travel_time_attendance.py
```

---

## 💡 The Takeaway

> *"Statistics doesn't just describe data — it reveals truth hidden inside numbers."*

This is exactly what MTH-262 taught me — that the formulas we study aren't abstract.  
They quantify trade-offs students live with every single day, and could realistically inform university transport or hostel-subsidy decisions.

---

**Thank You Sir 🫡 : [Sir's Name]**

`#DataScience` `#Python` `#Statistics` `#BayesTheorem` `#NormalDistribution` `#COMSATS` `#Mathematics` `#StudentDeveloper`
