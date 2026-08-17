
# OPERIXA ERP — Power BI Financial Dashboard

## Overview
A Power BI project analyzing profitability, cost structure, and strategic risk for OPERIXA ERP, a simulated B2B software 
and hardware vendor selling enterprise resource planning solutions to mid-market businesses.
OPERIXA ERP offers 19 software products (core ERP, accounting, inventory management, CRM, analytics) and 6 hardware products (5 electronics, 1 accessory). Over 2024-2025, the company processed 50,000+ orders generating $411.88M in combined revenue.
The dataset is AI-generated for demonstration purposes. The model architecture (DAX measures, relationships, cost structure) is fully generalizable and could connect to a live financial 
data source with monthly refresh.

## The Strategic Problem
OPERIXA ERP has achieved strong revenue ($205.79M in 2025) and reasonable profitability (65.77% gross margin, 79.91% 
contribution margin). Leadership is asking: "Are we building a sustainable, scalable business — or just moving high volumes of 
products without strategic direction?"

This dashboard addresses that question through three challenges.

---

## Challenge 1: Product Mix Uncertainty

**Question:** Software products generate 100-300% ROI, hardware 
generates 10-100% ROI. Should we expand software and de-prioritize hardware, reprice hardware, or exit hardware entirely?

**Findings:**
- Software: 161% average ROI ($1.61 profit per $1 of cost)
- Accessories: 90.37% average ROI
- Electronics: 38.09% average ROI ($0.38 profit per $1 of cost)
- Software is 4.2x more profit-efficient than Electronics

**Product-level positioning** (profit per unit vs. ROI%) 
identified four strategic zones:
- High Profit + High ROI → push hard (e.g., top software products)
- Low Profit + High ROI → volume play, low-touch sales
- Low Profit + Low ROI → discontinue (all Electronics fall here)
- High Profit + Low ROI (relative) → reprice or reconsider 
  investment priority

**Decision:** Allocate 80% of sales resources to software, 20% 
to hardware/accessories — the efficiency gap justifies a software-first go-to-market strategy.

---

## Challenge 2: Profitability Vulnerability

**Question:** How vulnerable is the business to a market downturn?

**Findings:**
- Fixed costs represent 27.2% of revenue ($56.7M of $205.8M)
- 52.4% of every revenue dollar becomes net profit
- Contribution margin is a healthy 79.91% — vulnerability comes from fixed cost exposure, not inefficiency

**Safety Cushion:**
Safety Cushion = Current Revenue / Break-Even Revenue
= $205,786,186 / $70,975,656 = 2.90x

**Scenario analysis:** Even a severe -50% demand drop leaves the company profitable at $25.5M. Only a -65.5% revenue collapse 
flips the business into loss territory.

**Strategic options evaluated:**
1. Widen the cushion — cut fixed costs 15-20%
2. Lock in volume — multi-year customer contracts
3. **Recommended:** Accept current risk, deploy profit into  growth — the 2.90x cushion already absorbs realistic downturns

---

## Skills Demonstrated
- DAX (layered measures, VAR architecture, break-even and  contribution margin calculations)
- Data modeling and relationships
- Financial analysis (break-even, scenario planning, ROI analysis)
- Data visualization and dashboard design
- Business storytelling through data

## Note
This project uses a simulated dataset for demonstration purposes.
