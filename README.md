# PwC Call Center Performance Dashboard (Power BI)


An interactive Power BI dashboard that tracks call center performance across **call handling capacity, speed of answer, and customer satisfaction by agent**. It gives call center managers a single view of how many calls are answered, how fast, and how satisfied customers are, so they can prioritize agent coaching.

---

## Business Problem

The call center management team needed to understand how well the center was performing and how satisfied customers were. Key questions:

- How many incoming calls are actually being answered?
- How quickly are agents answering calls?
- How satisfied are customers compared with the target?
- How do call volumes and answer rates change month to month?
- Which agents need coaching?

Call handling capacity and agent performance were not being tracked, so managers had no clear, data-backed view for coaching and staffing decisions. This dashboard fills that gap.

---

## Dataset

| Item | Detail |
|------|--------|
| Source | PwC call center case study dataset [add link if downloaded from Forage, Kaggle, or another site] |
| Records | **5,000 calls** |
| Period | **January 1, 2021 to March 31, 2021** |
| Agents | **8** |
| Key fields | Agent, Topic, Date/Time, Answered (Y/N), Resolved (Y/N), Speed of Answer, Talk Duration, Satisfaction Rating |

---

## Headline KPIs

| KPI | Value |
|-----|-------|
| Total Calls | **5,000** |
| Answered Calls | **4,054** |
| Answer Rate | **81.1%** |
| Unanswered Calls | **946** |
| Average Speed of Answer | **67.52 sec** |
| Average Customer Satisfaction | **3.40 / 5** |
| Satisfaction Target | **4.50 / 5** |
| Gap to Target | **1.10 points** |

---

## Key Insights

**1. Nearly 1 in 5 calls goes unanswered.** Only 4,054 of 5,000 calls were answered, an answer rate of **81.1%**. The other 946 calls represent a capacity gap that was previously untracked.

**2. Customers wait over a minute on average.** The average speed of answer is **67.52 seconds**, which points to a staffing or call-routing opportunity.

**3. Satisfaction is well below target.** The average satisfaction rating is **3.40 out of 5** against a target of **4.50**, a gap of 1.10 points.

**4. January was the busiest month.** January had the highest call volume (about 35% of all calls), ahead of February and March, with a similar unanswered share (~19%) in each month.

**5. Agent-level visibility enables coaching.** Satisfaction, talk duration, and answered and unanswered calls are broken down across all 8 agents, so coaching can focus on the agents furthest from the 4.50 target.

---

## Dashboard Visuals

| Visual | Purpose |
|--------|---------|
| KPI cards (Agents, Total Calls, Answered, Unanswered, Avg. Speed of Answer, Avg. Satisfaction) | Headline performance at a glance |
| Performance Quadrant table | Compare agents on talk duration, answered and unanswered calls, resolution, and satisfaction |
| Answered and Unanswered Calls by Month (column chart) | Track call handling capacity over time |
| Average Satisfaction Rating (gauge, target 4.50) | Show satisfaction against target |
| Satisfaction Ratings by Agent (pie chart) | Compare each agent's share of satisfaction ratings |
| Average Talk Duration and Time by Agent (area chart) | Compare handling time across agents |
| Slicers: Date, Agent, Topic, Resolved | Filter the whole dashboard interactively |

---

## Recommendations

1. **Close the capacity gap.** Review staffing in the periods with the most unanswered calls to raise the answer rate above 81.1%.
2. **Reduce speed of answer.** Investigate call routing and staffing to bring the 67.52 sec average down.
3. **Coach below-target agents.** Use the agent-level satisfaction view to focus coaching on agents furthest from the 4.50 target.
4. **Track KPIs regularly.** Refresh the dashboard on a set schedule so managers can monitor progress against targets.

---

## Tools Used

- **Power BI Desktop:** data modeling, visuals, slicers, and report design
- **Power Query:** data cleaning and transformation
- **DAX:** calculated measures for answer rate, speed of answer, and satisfaction

---

## How to Use

1. Clone or download this repository.
2. Open the `.pbix` file in **Power BI Desktop**.
3. Use the **Date, Agent, Topic, and Resolved** slicers to filter the dashboard.
4. Click any chart element to cross-filter the other visuals.

---

## Limitations and Future Improvements

- Add trend analysis by day and hour to find peak unanswered-call periods.
- Add call volume forecasting to support staffing plans.
- Add first-contact resolution and average call duration (TAT) measures.
- Add SQL scripts for data extraction and KPI validation.
