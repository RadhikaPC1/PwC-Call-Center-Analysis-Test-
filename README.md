# 📞 PwC Call Center Analysis Dashboard (Power BI)

A single-page **Power BI dashboard** that tracks call center efficiency, agent performance and customer satisfaction. Built as part of a PwC virtual job simulation.

---

## 🎯 Project Overview

**Objective:** Help a call center manager answer questions such as:

- How many calls were received, answered and left unanswered?
- How quickly are calls answered, and how long do agents spend on calls?
- How satisfied are customers overall and per agent?
- Which agents perform best, and which need support?
- How do call volumes change month by month and by topic?

---

## 📈 Key Metrics

| KPI | Value |
|---|---|
| Total Calls | _add value_ |
| Answered Calls | _add value_ |
| Unanswered Calls | _add value_ |
| Avg. Speed of Answer (sec) | _add value_ |
| Avg. Satisfaction Rating | _add value_ |
| Number of Agents | _add value_ |

---

## ✨ Dashboard Features

- **KPI cards** for calls, answer speed and satisfaction
- **Slicers** for Agent, Date, Resolved status and Topic
- **Gauge** for average satisfaction rating
- **Performance Quadrant table** comparing agents side by side
- **Cross-filtering** between all visuals

---

## 🧩 Visuals Explained

| Visual | Chart Type | What It Shows |
|---|---|---|
| Average Talk Duration and Time by Agent | Area chart | Talk duration per agent over time |
| Answered and Unanswered Calls by Month | Column + line combo | Monthly call volume and missed calls |
| Average Satisfaction Rating | Gauge | Overall satisfaction against target |
| Satisfaction Ratings by Agent | Pie chart | Rating distribution per agent |
| Performance Quadrant | Table | Answered calls, talk time, resolution, satisfaction and unanswered calls per agent |

---

## 🗂 Dataset

| Column | Description |
|---|---|
| Agent | Call center agent name |
| Date / Time | When the call took place |
| Topic | Reason for the call |
| Answered (Y/N) | Whether the call was answered |
| Resolved | Whether the issue was resolved |
| Speed of Answer (sec) | Wait time before an agent answered |
| AvgTalkDuration | Length of the call |
| Satisfaction Rating | Customer rating of the call |

*(Update to match your source file.)*

---

## 🛠 Tools & Technologies

- **Power BI Desktop**: modelling and visuals
- **Power Query**: data cleaning
- **DAX / calculated columns**: Answered Calls, Unanswered Calls
- **Excel / CSV**: source data

---

## 🔮 Future Improvements

- Add a satisfaction-vs-speed scatter plot
- Add hourly / day-of-week call volume heatmap
- Add targets and alerts for answer rate and speed
- Add resolution-rate % card and trend

---


