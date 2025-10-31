# 🧠 Automated Problem Recommendation System

## 📊 Overview
This project automates the process of collecting, analyzing, and recommending coding problems using **UiPath**, **Excel VBA**, and **AI**.  
It helps learners practice coding problems efficiently by generating daily challenges, analyzing difficulty levels, and sending personalized problem sets via email.

---

## ⚙️ Features
- 🕵️ **Data Scraping:** UiPath extracts problem details such as `Problem ID` and `Problem Difficulty` from websites like *Leetcode,GeeksForGeeks*.
- 📈 **Pivot Analysis:** Excel VBA automatically creates a **PivotTable** and **PivotChart** to show the count of problems by difficulty (Easy, Medium, Hard).
- 🤖 **AI Recommendation:** Suggests coding problems based on user performance, difficulty trend, or past attempts.
- 📧 **Email Automation:** Sends a curated list of recommended problems directly to the user’s inbox for daily practice.
- 🔁 **End-to-End Automation:** Seamless integration between UiPath and Excel with no manual intervention.

---

## 🧰 Tech Stack
| Component | Technology Used |
|------------|-----------------|
| Automation | UiPath Studio |
| Data Processing | Microsoft Excel + VBA |
| AI Recommendation | Content Generation (gpt-4o)|
| Email Integration | SMTP Configuration |

---
## 📂 Folder Structure
```text
├── UiPathAutomation.xaml        # UiPath workflow for scraping and automation
├── CreatePivotChart.txt         # VBA script for PivotTable & Chart creation
├── ProblemData.xlsx             # Excel file storing scraped problem data
├── README.md                    # Project documentation

```
---

## 🚀 How It Works
1. **Run UiPath Bot:** Scrapes coding problems from a selected website and stores data in Excel.  
2. **Execute VBA Macro:** Generates a PivotTable and a clustered column chart displaying the count of problems by difficulty.  
3. **AI Module:** Recommends problems to the user based on historical performance.  
4. **Email Delivery:** Sends the recommended problems to the user’s email inbox automatically.

---

## 🧩 Output Example
A **clustered column chart** displaying:
```
Easy   ████████████████ (Count: 50)
Medium ██████████        (Count: 30)
Hard   ████              (Count: 10)
```

Followed by a personalized email:
> “Here are your daily coding challenges based on your performance!”

---

## 🏁 Outcome
This project simplifies coding practice by combining **automation, analytics, and AI recommendations**, helping users stay consistent and focused on improving their problem-solving skills.

---

## 👩‍💻 Author
**Deepika P**  
Automation & AI Enthusiast | UiPath Developer

