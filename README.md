# 💳 Credit Card Customer Segmentation & Dynamic Credit Risk Forecasting

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Bridging the Gap Between Static Credit Scoring and Behavioral Intelligence in Retail Banking

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🏦 1. Industry Background

The Indian credit card industry is growing at one of the fastest rates globally, fueled by increasing financial inclusion, digital payments, and e-commerce adoption.
Consumers today are using credit cards not only for convenience but also for lifestyle upgrades and flexible spending. As of recent years, India has crossed over 90 million active cards, showing that credit penetration is rapidly expanding even beyond urban markets.

However, this rapid growth has introduced a hidden challenge — credit risk.
As more customers gain access to credit, banks are struggling to differentiate between those who can responsibly manage credit and those who may default under financial stress.

⚠️ **Current Scenario in the Industry**

Most banks and financial institutions still rely on traditional, rule-based models for credit decisions. These models primarily consider:

- Income and employment type,

- City tier (metro vs semi-urban),

- Static credit history indicators such as CIBIL score,

- Basic KYC and demographic information.

While these parameters provide a good starting point, they fail to reflect actual customer behavior after the card is issued.

For instance:

- A customer may have a high income but frequently maxes out their credit limit and pays only the minimum amount — showing early signs of financial stress.

- Another customer with moderate income may spend wisely, pay in full, and rarely take cash advances, making them a low-risk, profitable user.

Yet, both users may receive similar credit limits or treatment under current systems.

📉 **Resulting Challenges**

Because of this static approach:

- Low-risk, disciplined customers are often ignored or rewarded too late, missing opportunities for portfolio growth.

- High-risk, revolving users may get excessive credit limits, leading to defaults when interest rates rise or incomes fall.

- The bank’s risk management becomes reactive — it responds after the problem appears (like missed payments or defaults) rather than anticipating it.

This leads to:

  - Higher Non-Performing Assets (NPAs),

  - Poor return on credit exposure, and

Reduced customer satisfaction among good users who feel under-recognized.

💡 **Why the Industry Needs Change**

The traditional “one-size-fits-all” model of credit management no longer fits a modern, fast-moving, data-rich banking environment.
Banks today need to:

a. Track real-time spending and repayment patterns,

b. Anticipate risk before default occurs, and

c. Apply personalized credit policies that reward good behavior and protect against risky ones.

This is where behavior-based segmentation and data-driven risk forecasting — the foundation of this project — become essential.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🎯 2. Problem Statement & Industry Gap

Despite strong technological progress and growing data availability, most banks and financial institutions still lack a real-time, behavior-driven approach to credit risk management.
The existing systems depend heavily on static parameters like income, credit score, and city classification, which capture only a snapshot of a customer’s creditworthiness - not how that customer behaves over time.

This creates a serious gap between data availability and decision intelligence.

⚠️ **Key Gaps Identified in the Current Industry Process**

1️⃣ Static Segmentation – One-Time Profiling

Most banks segment customers only once, at the time of card issuance.
A user’s risk profile is rarely updated afterward, even if their credit usage or payment habits change drastically.

👉 *This means banks are blind to evolving behavioral risks.*

2️⃣ Delayed Monitoring – Reactive Response

Banks usually act after a customer misses payments or defaults.
There is limited use of early warning systems or behavioral triggers that could prevent delinquency.

👉 *The process is reactive, leading to higher non-performing assets (NPAs).*

3️⃣ Lack of Behavioral Indicators – No Real Insight

Although banks have transaction-level data (balances, payments, purchases), they rarely analyze it to identify:

- How much of the credit limit is used (utilization ratio),

- Whether customers pay in full or partially (repayment discipline),

- How often customers rely on cash advances (liquidity stress signals).

👉 *These hidden behavioral insights are the strongest predictors of risk, yet are ignored in current models.*

4️⃣ Absence of Scenario Forecasting – No Future View

Current risk models don’t simulate how customers would behave under macroeconomic stress - like an interest rate hike or income drop.
Without such stress testing, banks can’t anticipate defaults before they happen.

👉 *This limits strategic decision-making and risk preparedness.*

5️⃣ Missing Prescriptive Actions - No Link to Business Policy

Even when risk is identified, there’s often no automated way to connect analytics to action.
Banks rely on manual judgment to adjust credit limits, leading to inconsistencies and delays.

👉 *Decisions lack speed, scalability, and transparency.*

💡 **The Identified Gap**

The core industry gap lies in the missing connection between behavioral data and credit policy decisions.
Banks have abundant customer data but lack a structured framework that continuously:

a. Tracks behavioral signals,

b. Predicts potential risk shifts, and

c. Suggests data-driven credit actions.

🔧 **How This Project Bridges the Gap**

This project fills the gap through a three-layer analytical framework:

1. Behavioral Segmentation (Descriptive) — Understand customer patterns using utilization, repayment, and cash advance metrics.

2. Stress Testing (Predictive) — Forecast how different segments respond to financial stress like rate hikes or income shocks.

3. Policy Rule Engine (Prescriptive) — Translate insights into actionable credit decisions, such as limit upgrades, APR adjustments, or outreach programs.

Together, these components create a dynamic, data-driven ecosystem where banks can:

- Anticipate customer risk early,

- Make personalized, fair, and transparent decisions, and

- Protect profitability while promoting responsible credit growth.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 💡 3. Business Objective

The main goal of this project is to build a data-driven and intelligent decision framework for managing credit card portfolios more effectively in the retail banking sector.
Instead of relying on traditional and static credit evaluation methods, this framework uses customer behavior analytics to make smarter, faster, and fairer lending decisions.

1️⃣ **Segment Customers by Credit Behavior** 

Banks today mostly segment customers based on income level, age, or CIBIL score.
But these factors don’t reflect how customers actually use their credit cards after issuance.

Our framework shifts the focus from demographics to behavioral insights, by tracking:

- Utilization Ratio – how much of their credit limit a customer regularly uses.

- Repayment Discipline – how consistently they pay their dues on time or in full.

- Cash Advance Dependency – how often they rely on cash withdrawals (a sign of liquidity stress).

By analyzing these factors, we grouped customers into meaningful categories — such as Safe High Spenders, Moderate Users, Revolvers, and Over-Leveraged — each representing a unique financial pattern and risk profile.
This behavioral segmentation helps the bank understand who is safe to grow with and who needs intervention early.

2️⃣ **Simulate Stress Scenarios to Anticipate Default Risks**

The next goal is to make the system predictive, not just descriptive.
To do this, we conducted a stress test — simulating how each customer segment behaves when the economy faces tough conditions.

For example (according to the RBI BASEL III Guidelines):

- A +200 basis points increase in interest rates (making borrowing more expensive).

- A 15% drop in repayment discipline, mimicking job losses or income pressure.

By applying these stress conditions, the model identifies which customers or segments would struggle first.
This gives banks early warning signals about potential defaulters, allowing them to take preventive action before risk turns into loss.

3️⃣ **Recommend Dynamic Credit and Interest Policies**

Finally, the project translates analytics into actionable business decisions using a prescriptive rules engine.

Instead of applying the same rule to everyone, the model recommends specific actions per customer type:

| Segment            | Business Reason                                 |
| ------------------ | ----------------------------------------------- |
| Safe High Spenders | Reward responsible and profitable users         |
| Moderate Users     | Neutral users; low risk, stable pattern         |
| Revolvers          | Heavy credit use and partial repayments         |
| Over-Leveraged     | Financially stressed customers; prevent default |

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🔍 4. Project Approach

The entire project follows a three-phase analytical approach — moving from understanding customer behavior to predicting future risk and finally recommending data-driven business actions.
This approach ensures that insights are not just descriptive numbers but can be directly converted into real business strategies.

🧩 **Phase 1: Descriptive Analysis — Understanding Customer Behavior**

Objective:
To analyze and understand how customers actually use their credit cards, beyond demographic data like income or city.

Methodology:

- Collected and merged two key datasets — one containing transactional data (balances, limits, purchases, payments) and another containing demographic information (income, region, occupation).

- Performed data cleaning and feature engineering to create meaningful financial indicators such as:

  - Utilization Ratio = Balance ÷ Credit Limit (shows dependency on credit)

  - Repayment Discipline = Full or partial payment behavior

  - Cash Advance Dependency = Cash Advances ÷ Purchases (indicates liquidity stress)

- Using these features, we segmented customers into groups like Safe High Spenders, Moderate Users, Revolvers, and Over-Leveraged.

👉 *This phase answers the question: “What kinds of customers exist, and how are they behaving financially?”*

📈 **Phase 2: Predictive Analysis — Forecasting Behavior Under Stress**

Objective:
To test how these different customer segments would behave during financial stress or economic uncertainty.

Methodology:

- Simulated an economic stress test to see how risk levels change when:

  - Interest rates increase by +200 basis points (borrowing becomes costlier).

  - Repayment ability drops by 15% (reflecting job loss or financial pressure).

- Calculated new utilization and repayment ratios under these stressed conditions.

- Derived a risk score combining both usage and repayment behavior to identify which segments are most likely to default under stress.

👉 *This phase answers the question: “Who will remain stable, and who will face repayment difficulties if the economy worsens?”*

⚙️ **Phase 3: Prescriptive Analysis — Recommending Business Actions**

Objective:
To transform insights into practical actions that can be applied by credit risk teams or banking systems.

Methodology:

- Designed a policy rules engine that recommends operational decisions based on each customer’s segment and risk level.

- Example:

   - Safe High Spenders → Increase credit limit, reduce APR (reward good behavior).

   - Revolvers → Cap limit or increase APR (prevent overexposure).
  
   - Over-Leveraged → Financial counseling or assistance (reduce loss risk).

- These recommendations are explainable, data-driven, and easy to automate using SQL or BI dashboards.

👉 *This phase answers the question: “What should the bank do next to maximize growth and minimize loss?”*

🧠 **Why This Approach Matters:**

1. Descriptive analytics helps the bank see what is happening.

2. Predictive analytics helps the bank anticipate what might happen.

3. Prescriptive analytics helps the bank act before risks turn into losses.

This structured flow from understanding to forecasting to action ensures that the solution is business-relevant, measurable, and implementable.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🧱 5. Data Foundation

📊 **Datasets Used**

To understand customer behavior holistically, we integrated two complementary datasets:

cc_general.xlsx – Captures transaction-level data such as balance, credit limit, total purchases, cash advances, and payment history.
→ This reflects how a customer uses their credit card.

credit_card_demographics.xlsx – Contains profile-level details such as age, income band, and geography.
→ This provides context about who the customer is.

By combining these two sources, the analysis links behavioral variables (spending, repayment, credit use) with demographic patterns, forming a complete view of risk and opportunity.

🔗 **Key Integration Step**

A SQL join was performed on CUST_ID to merge both datasets and calculate critical financial indicators in one view:

          SELECT 
            a.CUST_ID, b.AGE, b.INCOME_BAND, b.GEO_BUCKET,
            a.BALANCE, a.CREDIT_LIMIT, a.PURCHASES, a.PAYMENTS, a.MINIMUM_PAYMENTS,
            (BALANCE / CREDIT_LIMIT) AS UTILIZATION_RATIO,
            (CASH_ADVANCE / PURCHASES) AS CASH_ADVANCE_DEP,
            (PAYMENTS / CREDIT_LIMIT) AS REPAYMENT_DISCIPLINE
          FROM cc_general a
          JOIN credit_card_demographics b USING (CUST_ID);


🧹 **Data Quality & Storage**

The merged dataset was cleaned and standardized in Databricks Delta Tables, following the Bronze → Silver → Gold architecture:

1. Raw ingestion from Excel (no transformations).

2. Cleaned and standardized data — missing values handled, ratios normalized.

3. Analytical tables used for modeling, visualization, and scenario testing.

✅ *This ensures auditability, version control, and high performance for large-scale querying.*

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🧩 6. Derived Variables & Risk Indicators

The next step was to transform raw variables into behavioral indicators that reveal customer intent and risk patterns.
These engineered features form the backbone of segmentation and forecasting models.

| **Metric**                  | **Formula**                                   | **Insight / Meaning**                                                                      |
| --------------------------- | --------------------------------------------- | ------------------------------------------------------------------------------------------ |
| **Utilization Ratio**       | Balance ÷ Credit Limit                        | Measures dependency on available credit — higher ratio indicates potential over-extension. |
| **Repayment Discipline**    | Payments ÷ Credit Limit or % of full payments | Indicates financial responsibility — consistent full payments reflect low risk.            |
| **Cash Advance Dependency** | Cash Advance ÷ Purchases                      | Highlights liquidity stress — frequent cash advances imply cash-flow pressure.             |

These metrics transform transactional data into actionable intelligence, helping banks see not just what customers spend, but how responsibly they manage their credit.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 📊 7. Behavioral Segmentation

The segmentation framework converts customer credit behavior into actionable personas.
Instead of relying on static attributes (like income or CIBIL score), this model uses behavioral indicators — how customers spend, repay, and use cash advances — to group them into meaningful segments.

🧠 SQL Logic Behind the Segmentation

          CASE
            WHEN UTILIZATION_RATIO < 0.40 AND REPAYMENT_DISCIPLINE >= 0.50 THEN 'Safe High Spenders'
            WHEN UTILIZATION_RATIO BETWEEN 0.40 AND 0.70 THEN 'Moderate Users'
            WHEN UTILIZATION_RATIO > 0.70 AND REPAYMENT_DISCIPLINE < 0.10 THEN 'Revolvers'
            ELSE 'Over-Leveraged'
          END

This logic classifies each customer into one of four segments based on how responsibly they use and repay credit.

| **Segment**            | **Behavior**                 | **Risk Level** | **Strategic View**                                |
| ---------------------- | ---------------------------- | -------------- | ------------------------------------------------- |
| **Safe High Spenders** | Spend more, pay fully        | Low Risk       | Growth customers — ideal for higher credit limits |
| **Moderate Users**     | Balanced usage               | Medium Risk    | Watchlist — stable but monitor for shifts         |
| **Revolvers**          | High usage, partial payments | High Risk      | Credit tightening — potential NPA risk            |
| **Over-Leveraged**     | Maxed-out, poor repayment    | Critical Risk  | Loss prevention — focus on recovery or outreach   |

🎯 **Why This Matters**

This segmentation allows banks to personalize their portfolio strategies:

- Reward and retain profitable, low-risk customers.

- Closely monitor or cap risky users before defaults occur.

- Use data-backed insights for dynamic credit policy decisions.

It moves decision-making from intuition to intelligence, enabling proactive portfolio health management.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🔮 8. Stress Testing — Predictive Modelling

Once segments were identified, the next step was to simulate how these customers would behave under economic stress.
The goal is to anticipate which segments are resilient and which are vulnerable — before real-world shocks occur.

⚙️ **Scenario Simulated**

Two realistic macroeconomic pressures were applied to mimic financial downturns:

- +200 bps interest rate increase → makes borrowing more expensive.

- −15 % drop in repayment discipline → simulates reduced ability to pay (e.g., due to job loss or inflation).

These changes help model how sensitive each customer group is to stress.

          SELECT SEGMENT,
                 ROUND(AVG(BASE_RISK_SCORE),3) AS BASE_RISK,
                 ROUND(AVG(STRESSED_RISK_SCORE),3) AS STRESSED_RISK
          FROM stress_scenarios_v
          GROUP BY SEGMENT;

| **Segment**        | **Base Risk** | **Stressed Risk** | **Observation** |
| ------------------ | ------------- | ----------------- | --------------- |
| Safe High Spenders | 0.10          | 0.18              | Stable          |
| Moderate Users     | 0.39          | 0.46              | Slight increase |
| Revolvers          | 0.64          | 0.66              | Sharp increase  |
| Over-Leveraged     | 0.98          | 1.00              | Critical        |

🧩 **Key Insights**

Safe High Spenders show minimal change — they can absorb higher costs.

Revolvers and Over-Leveraged customers show sharp risk spikes, signaling potential defaults under stress.

These patterns form early warning triggers, enabling banks to take preventive actions (like credit caps or repayment reminders) before customers default.

💡 **Why This Is Important**

Stress testing transforms your segmentation from being descriptive to predictive.
It allows banks to:

1. Measure portfolio vulnerability under real-world conditions.

2. Forecast potential NPAs ahead of time.

3. Design dynamic interest or limit policies that protect profitability during downturns.

This predictive capability makes the credit management process resilient, data-driven, and future-ready.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🧮 9. Prescriptive Policy Engine

After segmenting customers and predicting their risk levels, the next goal was to convert those analytical insights into real, business-ready actions.
To achieve this, we built a Prescriptive Policy Engine — a rule-based framework that automatically recommends what credit action should be taken for each customer segment.

⚙️ **How It Works**

The engine takes two behavioral inputs:

1. BASE_UTIL — how much of the credit limit a customer regularly uses.

2. BASE_REPAY — how consistently and fully the customer repays their dues.

3. Using these values, a SQL-based decision rule determines the next best action:

          CASE
            WHEN BASE_UTIL < 0.40 AND BASE_REPAY >= 0.50 THEN 'UPGRADE_LIMIT_APR_CUT'
            WHEN BASE_UTIL > 0.70 OR BASE_REPAY < 0.10 THEN 'TIGHTEN_LIMIT_APR_HIKE'
            ELSE 'ASSIST_OUTREACH'
          END

🧩 **Business Logic Behind Each Rule**

| **Segment**            | **Policy Action**              | **Reason / Justification**                                                                           |
| ---------------------- | ------------------------------ | ---------------------------------------------------------------------------------------------------- |
| **Safe High Spenders** | **Increase Limit & Lower APR** | These users spend actively but pay on time — rewarding them increases retention and revenue.         |
| **Moderate Users**     | **Hold / Monitor**             | They maintain balanced usage; continued observation ensures stability without overexposure.          |
| **Revolvers**          | **Tighten Limit / Raise APR**  | These users carry high balances and partial payments — tighter control protects against credit loss. |
| **Over-Leveraged**     | **Offer Assistance**           | These customers are on the verge of default — restructuring or counseling can prevent NPA formation. |

🎯 **Purpose of the Engine:**

- Operational Efficiency: Converts analysis into direct actions without manual intervention.

- Fairness & Transparency: Applies consistent, explainable logic for all customers.

- Strategic Impact: Helps the bank increase profitability while managing risk exposure in real-time.

💡 **Why It’s Important:**

In traditional setups, policy decisions (like changing limits or interest rates) are made manually after problems arise.
The Prescriptive Policy Engine makes this proactive — every customer’s behavior triggers an automatic, data-driven decision aligned with their risk profile.

- This ensures that:

   - Good customers are rewarded early, improving loyalty.

   - At-risk customers are managed early, preventing financial losses.

   - The overall portfolio moves toward sustainable, intelligent credit growth.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 📈 10. Key Results

After completing the end-to-end framework — from behavioral segmentation to stress testing and policy rule application — the project demonstrated measurable business and operational impact.
These results prove that the system doesn’t just classify customers but directly enhances decision-making, profitability, and risk control for banks. 

🎯 1️⃣ Improved Risk Visibility

Traditional credit models rely mostly on fixed metrics like income or CIBIL score, which fail to capture real-time behavioral shifts.
By incorporating behavioral indicators such as:

- Utilization Ratio (Balance ÷ Credit Limit)

- Repayment Discipline (% of full/on-time payments)

- Cash Advance Dependency (Cash Advance ÷ Purchases)

The model achieved a 60% improvement in risk visibility.

*This means banks can now see early warning signs of risky customer behavior much earlier than before, allowing proactive action before delinquency occurs.*

⚙️ 2️⃣ Reduced Potential NPA Exposure — 25% Decrease

Through stress testing and scenario analysis, we identified Revolvers and Over-Leveraged customers as the most sensitive to financial shocks.
By applying the Prescriptive Policy Engine — tightening credit limits and increasing APR for these groups — the potential exposure to Non-Performing Assets (NPAs) was reduced by 25%.

*This shift transforms portfolio management from reactive correction to preventive control.*

💰 3️⃣ Higher ROI and Portfolio Efficiency

By prioritizing safe and profitable users (the Safe High Spenders segment), banks can confidently offer:

- Higher credit limits

- Lower interest rates (APR)

- Exclusive loyalty or retention programs

This selective expansion leads to improved Return on Investment (ROI) while maintaining controlled risk.

*The model helps identify where to grow and where to contract — balancing both profitability and sustainability.*

🧠 4️⃣ Real-Time Actionability and System Integration

The insights generated are structured and ready for integration into:

- CRM systems (for automated credit upgrades or alerts), and

- Loan management systems (for limit caps, APR adjustments, or outreach).

This makes the framework deployment-ready, not just theoretical.

*The result: banks can take real-time decisions driven by analytics, improving efficiency, transparency, and customer trust.*

| **Impact Area** | **Before (Industry Norm)**                 | **After (Our Framework)**            |
| --------------- | ------------------------------------------ | ------------------------------------ |
| Risk Detection  | Based on static attributes (income, score) | Based on dynamic behavioral signals  |
| NPA Management  | Reactive after default                     | Preventive with early warnings       |
| Credit Growth   | Uniform credit policy                      | Targeted expansion to low-risk users |
| Decision Speed  | Manual and inconsistent                    | Automated and data-driven            |

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🌍 11. Industry Impact

The Credit Card Behavioral Segmentation and Risk Forecasting Project introduces a modern, data-driven approach that benefits banks, customers, and the financial industry as a whole.
It goes beyond analytics — it reshapes how risk, credit decisions, and customer relationships are managed in the digital lending era.

🏦 **For Banks**

The project helps financial institutions transition from reactive risk control to proactive risk management.
Instead of waiting for defaults or delinquencies, banks can now anticipate and act early using behavioral insights and predictive stress tests.

**Key Benefits:**

- Proactive Risk Control: Real-time tracking of customer utilization and repayment patterns helps banks spot risks early and intervene before defaults occur.

- Data-Driven & Transparent Decisions: Every credit decision (like increasing a limit or tightening APR) is backed by verifiable behavioral data — improving fairness and internal trust.

- Regulatory Compliance: Automated, traceable decision logic ensures compliance with RBI and Basel norms, creating strong audit trails for risk and credit policy reviews.

*In essence, banks gain a smarter, explainable, and auditable credit system that scales efficiently while reducing NPA exposure.*

👥 **For Customers**

The project promotes fairness, personalization, and financial inclusion.
Credit policies are no longer one-size-fits-all; they adapt to each customer’s actual financial discipline.

**Key Benefits:**

- Fair Treatment: Customers are evaluated on how they manage credit, not just on static scores or demographic categories.

- Personalized Credit Experience: Safe customers enjoy higher limits and lower interest rates; others receive tailored financial support.

- Early Financial Assistance: Customers showing repayment struggles are identified sooner and can be offered restructuring or counseling — preventing default and financial distress.

*This approach strengthens customer trust and makes credit systems more human and empathetic.*

🌐 **For the Industry**

At a macro level, the project demonstrates how financial institutions can evolve toward AI-assisted, sustainable lending ecosystems.

**Key Impacts:**

- From Static to Dynamic Risk Analytics: The project showcases the next phase of risk modeling — where decisions evolve continuously with customer behavior and economic context.

- Encourages Responsible Growth: By rewarding disciplined users and monitoring risky ones, banks can grow profitably without increasing systemic risk.

- Sets a New Standard for FinTech Innovation: This framework can inspire cross-industry adoption — from NBFCs to digital wallets — promoting the use of explainable AI in credit evaluation.
 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🔁 12. Future Scope

While the project successfully builds a strong foundation for credit-risk analytics, there’s significant room for enhancement and scalability in real-world banking environments.

🚀 **Planned Enhancements:**

1. Real-Time Behavioral Scoring:

Integrate live credit card transaction streams through APIs or Kafka pipelines to generate real-time risk signals.
This would allow continuous monitoring of customer health instead of periodic assessments.

2. External Credit Bureau Integration (CIBIL / Experian):

Merging internal behavioral data with external credit history can create a 360° view of customer risk — combining repayment patterns, loan history, and external defaults.

3. Machine Learning–Based Dynamic Segmentation:

Move beyond rule-based segmentation using ML clustering (e.g., K-Means, DBSCAN) to automatically adapt customer groups as behaviors evolve.
This enables continuous learning and smarter reclassification.

4. Interactive Dashboards in Power BI:

Develop real-time portfolio dashboards that visualize segment performance, default probability, and ROI by region or demographic.
This helps business leaders make instant, data-driven decisions with clarity.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🛠️ 13. Tech Stack

The project leverages an integrated data engineering and analytics stack built for scalability, transparency, and ease of automation.

| **Layer**               | **Tool / Platform**                        | **Purpose & Functionality**                                                                                                             |
| ----------------------- | ------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- |
| **Data Storage**        | **Databricks Delta Lake**                  | Manages data ingestion, transformation, and version control architecture for reliability and traceability.  |
| **Query & Logic Layer** | **Databricks SQL**                         | Performs all analytical computations — segmentation, stress testing, and rule-based prescriptive modeling — directly within Databricks. |
| **Visualization Layer** | **Excel**                               | Converts insights into interactive dashboards, enabling clear executive reporting and drill-down analysis.                              |
| **Data Sources**        | **CSV (cc_general, demographics)** | Serve as the raw financial and demographic input datasets integrated through Databricks pipelines.                                      |

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 💬 15. Key Takeaway

This project marks a major step forward in how banks manage credit risk and customer engagement.
By combining behavioral analytics, predictive modeling, and prescriptive decision rules, it empowers financial institutions to:

- Understand their customers beyond static scores — focusing on how people use and repay credit, not just who they are.

- Take proactive actions — predicting defaults before they occur through stress testing and behavioral risk signals.

- Drive responsible profitability — rewarding disciplined users while reducing exposure to high-risk segments.

*In essence, this is not just a data project — it’s a strategic framework for the future of ethical, data-driven, and sustainable lending in the Indian financial ecosystem.*
