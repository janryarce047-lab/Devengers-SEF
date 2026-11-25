
@'
# Topic Bank: Devengers

> **Preliminary research shortlist.** This topic bank contains five proposed AI and machine learning research topics by Devengers, a three-member BS Computer Science team from National University Laguna. The ideas prioritize real societal problems, identifiable beneficiaries, measurable research contributions, and feasibility within an undergraduate thesis timeline.
>
> Scores are preliminary team/adviser assessments from 1 to 5. **Interest** represents the team's willingness to dedicate a thesis term to the topic. **Feasibility** considers data accessibility, computing resources, technical requirements, and development time.

---

## Shortlist

| Idea | Paradigm | Lab | Interest | Feasibility | Status |
|---|---|---|---|---|---|
| AidTrack AI: disaster relief demand forecasting and intelligent donation matching | Classical ML, predictive analytics, optimization | 01 | TBD | 4 | Candidate topic |
| SakaySense: jeepney waiting time prediction using historical passenger and vehicle arrival patterns | Classical ML, regression | 01 | TBD | 4 | Candidate topic |
| TindaWise: small-data demand forecasting and inventory replenishment for sari-sari stores | Classical ML, predictive analytics | 01 | TBD | 4 | Candidate topic |
| FoodWise: meal demand forecasting for reducing university cafeteria food waste | Classical ML, time-series forecasting | 01 | TBD | 4 | Candidate topic |
| HireSafe PH: context-aware detection of fraudulent online recruitment advertisements | NLP, supervised machine learning, explainable AI | 01 | TBD | 4 | Candidate topic |

**Note:** Interest scores have not yet been provided. They should be determined through team discussion rather than inferred from the preliminary adviser assessment.

---

## Lab 01: AI and Machine Learning Research Topic Scan (Week 1)

Five preliminary research ideas developed around practical applications of artificial intelligence and machine learning. The focus is on identifying local problems, potential beneficiaries, accessible datasets, and research opportunities that can be completed by a three-member undergraduate team.

### 1. AidTrack AI: Disaster Relief Demand Forecasting and Intelligent Donation Matching

- **Idea:** Develop an improved version of AidTrack that uses machine learning to forecast short-term relief requirements and recommend suitable allocations of available donations to disaster-affected communities.
- **Problem it addresses:** Disaster response operations frequently encounter unequal distribution of relief goods, mismatched donations, and difficulties anticipating the actual needs of affected communities.
- **Closest existing work:** *An AI-Based Framework for Earthquake Relief Demand Forecasting: A Case Study in Türkiye* (2024).
- **Data needed:** Department of Social Welfare and Development Disaster Response Operations Monitoring and Information Center (DSWD DROMIC) reports and historical relief requests validated by disaster response coordinators, subject to data accessibility.
- **Compute needed:** Laptop; Python; pandas; scikit-learn; and a development environment for the AidTrack application.
- **Biggest risk:** Limited access to historical relief requests with sufficient detail to train and evaluate a reliable forecasting model.
- **AI component:** Random Forest Regression or Linear Regression for demand forecasting, combined with constrained resource matching for donation allocation.
- **Research opportunity:** Determine whether lightweight machine learning can improve relief demand estimation using limited and potentially incomplete disaster reports.
- **Beneficiaries:** Disaster-affected families, donors, non-government organizations (NGOs), and local government units (LGUs).
- **Team interest:** To be determined.
- **Feasibility:** 4/5, conditional on data access.
- **Advantage:** An existing AidTrack system provides a development foundation, potentially reducing the time needed to build the application from scratch.
- **Initial assessment:** Promising because it addresses a significant societal problem and offers opportunities to combine predictive analytics with practical resource allocation.

### 2. SakaySense: Jeepney Waiting Time Prediction Using Historical Passenger and Vehicle Arrival Patterns

- **Idea:** Develop a commuter application that estimates jeepney waiting times along a selected route using historical passenger and vehicle arrival observations, without requiring GPS trackers on every vehicle.
- **Problem it addresses:** Commuters experience unpredictable waiting times because jeepney arrival schedules and passenger demand are not always consistent or readily available.
- **Closest existing work:** *Transforming the Public Transport Sector in the Philippines through Service Contracts: A Program Evaluation Study* (2025 journal issue).
- **Data needed:** Independently collected jeepney arrival records along one selected route in Laguna, including observation time, location, day of the week, and relevant passenger activity.
- **Compute needed:** Laptop; Python; pandas; scikit-learn; and a mobile or web application development environment.
- **Biggest risk:** Collecting enough consistent arrival observations to represent different operating conditions, including peak hours, off-peak periods, and varying traffic conditions.
- **AI component:** Random Forest Regression for estimating waiting times from historical observations and contextual variables.
- **Research opportunity:** Investigate how accurately waiting times can be predicted using limited observations, time, location, and day-of-week information.
- **Beneficiaries:** Students, employees, daily commuters, and public transportation operators.
- **Team interest:** To be determined.
- **Feasibility:** 4/5.
- **Advantage:** The study can begin with one selected jeepney route, making data collection and system development more manageable.
- **Initial assessment:** Promising because it addresses a common transportation problem and provides a measurable research outcome through waiting-time prediction accuracy.

### 3. TindaWise: Small-Data Machine Learning for Demand Forecasting and Inventory Replenishment in Sari-Sari Stores

- **Idea:** Develop an inventory management application that predicts product demand and recommends appropriate restocking quantities for small neighborhood retail stores.
- **Problem it addresses:** Sari-sari store owners experience lost income due to unsold products, unexpected stock shortages, and inefficient purchasing decisions.
- **Closest existing work:** *Machine Learning Algorithms in Intermittent Demand Forecasting: A Review* (2025).
- **Data needed:** Public retail datasets and voluntarily provided sales records from participating sari-sari stores, including product quantities, sales dates, and available inventory information.
- **Compute needed:** Laptop; Python; pandas; scikit-learn; and an application development environment.
- **Biggest risk:** Inconsistent or incomplete sales records, particularly among small stores that do not use digital point-of-sale systems.
- **AI component:** Random Forest or XGBoost for product demand forecasting, with a recommendation mechanism for inventory replenishment.
- **Research opportunity:** Evaluate whether lightweight machine learning can produce useful demand forecasts despite limited sales records and irregular purchasing patterns.
- **Beneficiaries:** Sari-sari store owners, small business operators, and microentrepreneurs.
- **Team interest:** To be determined.
- **Feasibility:** 4/5.
- **Advantage:** The system can initially focus on a limited number of frequently purchased products, reducing the complexity of data collection and model development.
- **Initial assessment:** Promising because it supports small businesses through accessible predictive analytics and has a manageable application development scope.

### 4. FoodWise: Machine Learning-Based Meal Demand Forecasting for Reducing Food Waste in University Cafeterias

- **Idea:** Develop a meal demand forecasting application that recommends the number of food portions a university cafeteria should prepare based on historical consumption, class schedules, weather conditions, and campus activities.
- **Problem it addresses:** Food establishments lose money and generate unnecessary food waste when the number of prepared meals exceeds actual customer demand.
- **Closest existing work:** *Reducing Food Waste in Campus Dining: A Data-Driven Approach to Demand Prediction and Sustainability* (2025).
- **Data needed:** Historical cafeteria sales, daily meal preparation quantities, leftover records, class schedules, and available campus activity information. Access is subject to cafeteria cooperation.
- **Compute needed:** Laptop; Python; pandas; scikit-learn; and an application development environment.
- **Biggest risk:** Securing consistent cafeteria records that include both prepared meal quantities and actual consumption or leftover measurements.
- **AI component:** Linear Regression, Random Forest, or XGBoost for meal demand forecasting.
- **Research opportunity:** Determine whether accurate meal demand forecasting is achievable using minimal operational data rather than expensive monitoring systems.
- **Beneficiaries:** University cafeteria operators, students, and small food businesses.
- **Team interest:** To be determined.
- **Feasibility:** 4/5, subject to cafeteria cooperation.
- **Advantage:** A university cafeteria provides a relatively controlled research environment where daily food preparation and consumption patterns can be observed.
- **Initial assessment:** Promising because it combines operational efficiency with environmental sustainability and provides measurable outcomes through demand prediction and potential food waste reduction.

### 5. HireSafe PH: Context-Aware Machine Learning for Detecting Fraudulent Online Recruitment Advertisements

- **Idea:** Develop an application that analyzes online recruitment advertisements, identifies potentially fraudulent characteristics, and explains warning signs that may indicate suspicious employment opportunities.
- **Problem it addresses:** Filipino jobseekers are exposed to fraudulent employment advertisements, illegal recruitment activities, and financial exploitation through misleading online job postings.
- **Closest existing work:** *An Explainable, Cost-Aware Hybrid Framework for Fraudulent Online Job Posting Detection* (2026).
- **Data needed:** The Employment Scam Aegean Dataset (EMSCAD) and verified Philippine recruitment advertisements with reliable labels, subject to availability and appropriate usage permissions.
- **Compute needed:** Laptop; Python; pandas; scikit-learn; NLP libraries; and an application development environment.
- **Biggest risk:** Obtaining enough reliably labeled Philippine recruitment advertisements to train and evaluate a model that can distinguish legitimate but informal job postings from genuinely fraudulent ones.
- **AI component:** Natural Language Processing (NLP), Support Vector Machine (SVM), and Logistic Regression for text classification and suspicious advertisement detection.
- **Research opportunity:** Investigate whether models trained on conventional job listings remain effective when applied to informal, incomplete, and contemporary social media recruitment advertisements.
- **Beneficiaries:** Filipino jobseekers, graduating students, and aspiring Overseas Filipino Workers (OFWs).
- **Team interest:** To be determined.
- **Feasibility:** 4/5, dependent on reliable local data labels.
- **Advantage:** The project can use an existing public recruitment dataset as a starting point before evaluating its effectiveness on Philippine recruitment advertisements.
- **Initial assessment:** Promising because it addresses employment-related fraud and offers opportunities to investigate model generalization, text classification, and explainability.

---

## Comparative Assessment

The following scores are preliminary adviser assessments, not experimentally validated results. Each criterion is rated from 1 to 5, with higher scores representing stronger performance.

| Criteria | AidTrack | SakaySense | TindaWise | FoodWise | HireSafe |
|---|---:|---:|---:|---:|---:|
| Social necessity | 5 | 5 | 4 | 5 | 5 |
| Research potential | 5 | 4 | 4 | 4 | 5 |
| Originality potential | 4 | 5 | 4 | 3 | 4 |
| Ease of development | 4 | 4 | 5 | 5 | 5 |
| Data accessibility | 3 | 4 | 3 | 3 | 3 |
| Practical usefulness | 5 | 5 | 5 | 5 | 5 |
| **Total / 30** | **26** | **27** | **25** | **25** | **27** |

### Preliminary Ranking

1. **SakaySense – 27/30:** Strong potential due to its local transportation problem, manageable single-route scope, and opportunity for independent data collection.
2. **HireSafe PH – 27/30:** Strong research potential through context-aware recruitment fraud detection, with local data labeling as its main challenge.
3. **AidTrack AI – 26/30:** Builds on an existing system and addresses disaster response, although access to validated historical demand data remains a concern.
4. **TindaWise – 25/30:** Practical and relatively manageable, with data consistency from participating sari-sari stores as a major consideration.
5. **FoodWise – 25/30:** Offers a measurable sustainability application, but depends on obtaining complete cafeteria preparation and leftover records.

**Note:** The numerical ranking is based only on the supplied preliminary assessment. A final topic selection should also consider team interest, adviser feedback, research novelty, and confirmed data access.

---

## Initial Topic Selection Considerations

Before selecting a final thesis topic, the team should investigate the following:

- **Data availability:** Confirm whether the required datasets can actually be obtained before committing to a model or application.
- **Research gap:** Identify what existing studies and systems have not adequately addressed, particularly in the Philippine setting.
- **Measurable contribution:** Define evaluation metrics such as MAE, RMSE, F1-score, precision, recall, or forecasting accuracy, depending on the selected topic.
- **Development scope:** Ensure the system can be designed, implemented, and evaluated by three undergraduate researchers within the available thesis timeline.
- **Beneficiary validation:** Consult potential users or stakeholders to confirm that the proposed system addresses an actual need.
- **Team interest:** Evaluate whether all three members are willing to dedicate a thesis term to the chosen problem.

## Preliminary Outcome

Based on the initial comparative assessment, SakaySense and HireSafe PH received the highest scores, both earning 27 out of 30. AidTrack AI follows with 26 out of 30.

However, no final topic has been selected. The team must still validate data accessibility, investigate the research gaps, and determine its collective interest before proceeding to a formal thesis proposal.

**Current status:** Preliminary shortlist completed; topic validation and selection pending.

**Team:** Devengers

**Program:** BS Computer Science

**Institution:** National University Laguna
'@ | Set-Content -Path ".\TOPIC_BANK.md" -Encoding utf8
