# Kyle Cardwell — Master Experience Document

**Contact:** West Lafayette, IN | 765-434-3544 | cardwellkyle4674@gmail.com | [LinkedIn](https://www.linkedin.com/in/kyle-e-cardwell/)

> **How to use this document:** This is a long-form, source-of-truth record of all professional experience. Every bullet is written at maximum detail. To build a targeted resume: select the most relevant bullets, shorten them, and cut sections that don't fit the role. Nothing here is filler — every line should be usable in a real application.

---

## EDUCATION

### Purdue University — Daniels School of Business | West Lafayette, IN

**Master of Science, Business Analytics and Information Management (BAIM)**
*Expected August 2026*

- Concentration in data science, machine learning, operations analytics, and AI for business
- Larsen Leaders Academy member (selective leadership cohort within Daniels School of Business; admits a small number of high-achieving students for leadership development, mentorship, and experiential learning)
- Purdue Presidential Scholarship Recipient
- Relevant graduate coursework: Statistical & Machine Learning, Data Mining, Business Analytics, AI for Business Decisions, Cloud Computing, DevOps & Tech Solutions, Management of Organizational Data, IT Project Management, Spreadsheet Modeling & Simulation, Analyzing Unstructured Data, Industry Practicum (capstone), Advanced Business Analytics (upcoming), Cloud Computing — Data Engineering (upcoming)
- Graduate GPA: 3.67 (as of Spring 2026); Spring 2026 GPA: 4.00

**Bachelor of Science, Integrated Business and Engineering (IBE)** | Minor: Computer Science
*May 2025 | GPA: 3.7/4.0*

- Interdisciplinary program combining rigorous business coursework with engineering and computer science
- Multiple Dean's List semesters (Spring 2022, Fall 2022, Spring 2023, Fall 2023, Spring 2024, Spring 2025)
- Relevant undergraduate coursework: Predictive Analytics (A+), Programming Business Applications (A+), Python for Data Science (A), Advanced Spreadsheet Modeling & Simulation (A), Business Statistics (A), Management Information Systems (A+), Operations Management (A), Financial Management (A), Investments Management (A), C Programming (A), OO Programming (A), Systems Methods (A+), Data Structures & Algorithms, Computer Architecture, Storytelling with Data, Intellectual Property Management, Strategic Management
- **IBE Capstone (Spring 2025):** Built a predictive cost model for Hidden Valley Ranch to estimate the total cost of piloting new product flavors. Developed a multi-scenario Excel model using XLOOKUP, conditional cost formulas, and a structured data table; the model computed per-unit costs across fixed and variable components, supporting go/no-go pilot decisions. Final model contained ~50,000 scenario rows. Received an A.
- Larsen Leaders Academy | Purdue Presidential Scholarship

---

## PROFESSIONAL EXPERIENCE

---

### Kirby Risk Electric Co. | Lafayette, IN

**Supply Chain Analytics Intern** | *May 2025 – Present*

Kirby Risk is an electrical distribution company undergoing a full DC relocation and warehouse automation buildout. As the sole analytics resource, I led data-driven decision-making across the transition — from slotting 16,000+ SKUs to building customer-facing dashboards to standardizing scanner infrastructure.

**Warehouse Slotting & DC Transition (Flagship Project)**
- Designed and built a full warehouse slotting optimization system in Python (pandas, xlwings, openpyxl, numpy) to allocate ~14,000 active SKUs across ~3,800 locations in the new distribution center
- Managed and validated data from multiple competing measurement sources (Cubiscan, vendor packaging, internal volumetrics, manual measurements); developed a priority-ranked measurement resolution system that selected the most reliable source per SKU and fell back to family/global averages when all sources failed validation
- Identified significant inaccuracies in an external volumetric data subscription; compiled a data quality report comparing it to in-house measurements and presented findings to management — Kirby Risk subsequently canceled the subscription, saving on data costs and improving downstream model accuracy
- Engineered a multi-stage slotting algorithm covering: (1) high-hit SKU placement in premium aisles 46–47 based on pick frequency, (2) automation tote assignment with per-tote 3D bin packing and weight constraints across full, half, and eighth-tote types, (3) rack forward-pick assignment with priceline family clustering and long-item zone handling, and (4) overstock placement logic for demand exceeding forward capacity
- Output included two production files: an automation slotting CSV (14,145 SKU-tote assignments) and a fully slotted warehouse location map (3,813 locations), currently being used to stock the new DC as inventory moves in
- Generated rack reconfiguration recommendations (e.g., switching from 3×40" to 4×36" subsections per bay to gain ~33% more slot capacity) to address ~1,400 unallocated SKUs
- Iteratively improved the model using Cursor AI — restructured data handling, improved constraint logic, and made the codebase significantly more maintainable
- Coordinated slotting outputs with HAI Robotics (automation vendor), providing operational insights and ensuring automation bin assignments aligned with the physical automation system being installed

**WMS Implementation (Tecsys)**
- Participated in WMS selection and implementation meetings with Tecsys from the early planning stage through full production, serving as a subject matter expert on operational flow given 12+ months of on-site experience at Kirby Risk
- Served as a key resource for data uploads to Tecsys: wrote Python scripts to format and transform Excel files into Tecsys-compatible upload formats, enabling faster and more reliable data ingestion
- Collaborated closely with the Tecsys superuser to troubleshoot data issues and validate system configuration

**Order Status Dashboard**
- Wrote SQL queries in collaboration with the company's data engineer to build the underlying data tables needed from Tecsys WMS
- Designed and built a live order status dashboard in IBM Cognos Analytics, enabling counter customers to view real-time order progress on a TV screen at point of pickup — reducing staff interruptions and improving customer experience

**Zebra Scanner Standardization**
- Managed a fleet of 89 Zebra mobile scanners via Microsoft Intune
- Addressed a fleet-wide configuration inconsistency problem where each scanner had been set up ad hoc, requiring manual per-device troubleshooting for any issue
- Authored a gold-standard device configuration file and DataWedge profile optimized for Kirby Risk's specific workflows, then deployed it across all devices — eliminating configuration drift and reducing support burden

---

**IT Intern** | *August 2024 – May 2025*

- Maintained system reliability across the organization by diagnosing and resolving hardware, software, and network issues as primary IT support
- Led end-to-end planning and deployment of a company-wide PC replacement initiative: coordinated with management to define replacement guidelines, navigated employee-specific concerns to minimize disruption, and tracked progress in Excel and Microsoft Teams/Outlook to ensure timely completion
- Managed helpdesk ticket queue and resolved Tier 1 technical support issues with fast turnaround

---

**Business Operations Intern** | *May 2024 – August 2024*

- Authored the standard operating procedure for the warehouse returns process; prior to this, returned items were placed on a shelf with no structured process for returning them to inventory or crediting customers, creating inventory inaccuracies and delayed reimbursements
- Designed process flow diagrams for warehouse operations training, adopted and posted in the warehouse for use in new hire onboarding — improving consistency and reducing ramp-up time for new staff

---

### Cardwell Data Solutions LLC | Remote

**Founder** | *January 2026 – Present*

- Founded and operates an AI automation consulting LLC delivering custom workflow automation to small business clients
- Primary client: Huston Electric (electrical contractor), in partnership with Omni AI (platform and implementation partner)
- **AI Agent — Equipment Rental Automation:** Built an AI agent that monitors the director of purchasing's Outlook inbox, detects incoming equipment rental request PDFs, extracts key information (vendor, equipment type, dates, rates, quantities), writes the data into the company's Excel-based rental tracking file, and generates draft purchase order inputs — reducing a previously 5-minute manual process to approximately 5 seconds per rental
- **Rental Dashboard:** Built an automated dashboard to provide real-time visibility into active equipment rentals, upcoming expirations, and rental history; replaced a manual tracking process with no visibility into expiring contracts
- Operates on a project-based pricing model; seeking to expand client base as schedule allows

---

### BorgWarner Inc. | Kokomo, IN

**IT Client Tech Intern** | *June 2023 – May 2024*

BorgWarner is a global automotive components manufacturer. This role supported IT operations across the Kokomo facility.

- Led a 200+ employee company-wide PC refresh: assessed each employee's existing hardware and role requirements, used Python scripts to analyze enterprise device data and determine which replacement model was appropriate for each user, and coordinated logistics to minimize productivity loss during the transition
- Built Excel-based project dashboards to track refresh progress across all employees, providing visibility for stakeholders throughout the initiative
- Upgraded the facility's network to 10G capability in coordination with an external contractor: physically traced every cable across hundreds of network switch-patch panel cabinets (which had extremely disorganized wiring), built accurate diagrams of all connections, and used those diagrams to guide clean cable-by-cable switchover from old switches to new — enabling the upgrade without service interruption
- Resolved 100+ Tier 1 technical support tickets, maintaining fast response times and high user satisfaction across the facility

**Engineering Intern (Summers)** | *April 2021 – August 2022*

- Automated collection and refinement of production data across 400 plant computers using Batch and Python scripts — pulling hostname, IP address, MAC address, Windows version, and other system data into a structured dataset
- Built a hand-coded interactive plant map website (HTML/CSS/JavaScript) from scratch at age 18 — one of first major coding projects and built without AI assistance — that displayed the factory floor layout with all 400 computers organized by subsection; each computer entry included a real photo of its physical location, hostname, IP, MAC address, and Windows version
- The map included a search function that allowed engineers to locate any computer using partial information (IP address, hostname, or physical description), solving a real operational problem where engineers had no reliable way to cross-reference system data to a physical location
- Both the data collection scripts and the plant map were adopted by staff engineers as ongoing operational tools

---

### Huston Electric, Inc. | Kokomo, IN

**Facilities Specialist** | *2018 – June 2023 (Part-time; primarily high school summers and breaks)*

Part-time role at a small electrical contractor; served as primary warehouse and facilities help throughout high school and into early college years.

- Received and processed incoming shipments of electrical materials
- Operated forklift to move and organize inventory within the warehouse
- Completed facility renovation and maintenance tasks: removed old signs and fixtures, repainted the office, installed new bathroom fixtures, and performed general building upkeep
- Managed tasks independently in a small-team environment with minimal supervision

*Note: Huston Electric later became the first consulting client of Cardwell Data Solutions LLC (2026) — full-circle from first job to first client.*

---

## RESEARCH & ACADEMIC PROJECTS

---

### The Data Mine — Molson Coors Corporate Partner Project | Purdue University

**Graduate Data Science Researcher** | *August 2025 – December 2025*

- Partnered with Molson Coors to forecast US RTD (Ready-to-Drink) beverage market volume through 2030
- Started on the Spirits forecasting team; transferred to the RTDs team mid-semester
- Engineered a comprehensive feature set including macroeconomic drivers (CPI, GDP growth, unemployment, disposable personal income, consumer sentiment index, Fed Funds rate, population), cross-category beverage volumes (beer, wine, spirits), hard seltzer era indicator, COVID dummy, lag features (1–3 years), and rolling statistics
- Evaluated multiple model types via time-series cross-validation (5-fold): Ridge regression, Lasso, ElasticNet, Random Forest, HistGradientBoosting, and naïve baselines; Ridge outperformed complex models (MAPE ~5.27%, RMSE ~1,028 thousand hectoliters) — an important finding given the limited annual data (~34 years) that would have caused tree-based models to overfit
- Built a recursive forecasting pipeline that updated lag and rolling features at each step for multi-year forward projection
- Generated 95% confidence intervals from out-of-fold residuals for each year's prediction (2025–2030)
- Delivered an interactive dashboard providing Molson Coors with actionable visibility into sales trends across RTD categories

---

### Industry Practicum — Tarifast | Purdue BAIM Capstone

**Graduate Capstone Researcher** | *January 2026 – May 2026 (ongoing)*

Tarifast is a freight brokerage and logistics software company that targets high-value shipments and provides clients with above-average shipment visibility. The capstone team was tasked with building a real-time confidence scoring engine.

- Designed a four-component route normalcy scoring system (0–100%) combining:
  - **Route Deviation Score (30% weight):** Penalizes miles traveled off the planned route
  - **Progress/Time Score (50% weight):** Variance of actual vs. expected miles traveled at the current hour of trip
  - **Event Severity Score (20% weight):** Penalizes HIGH-severity events (−20 pts) and MED-severity events (−5 pts) from real-time telemetry
  - **ML Delay Component (integrated):** Residual-based penalty quantifying how much worse-than-expected the predicted delay is from this point forward
- Trained a **GradientBoostingRegressor** for quantile delay prediction across the full delay distribution (5th–95th percentile), using trip-level features: planned distance, planned drive hours, HOS-aware expected transit time, origin/destination state codes, and cross-border flag
- Trained a **GradientBoostingClassifier** to flag trips at risk of severe lateness (>12 hours late) for proactive intervention, reporting ROC-AUC and precision/recall metrics
- Engineered an HOS (Hours of Service)-aware baseline: modeled regulatory driving constraints (11-hour driving window, 10-hour mandatory break cycle) to compute a realistic expected transit time for each trip — replacing a naive planned-time baseline with one grounded in regulatory reality
- Worked with 30,155 hourly telemetry rows from 500 shipments, plus a data dictionary of 87 distinct event types across 9 categories
- Built a full-stack prototype with a Python backend and Node.js/Tailwind CSS frontend for operational demonstration

---

## TECHNICAL SKILLS

### Languages
- **Python** — primary language; pandas, numpy, openpyxl, xlwings, scikit-learn, XGBoost, LightGBM, matplotlib, seaborn; used across all major projects
- **SQL** — query writing, table creation, data pipeline work (used with IBM Cognos/Tecsys WMS)
- **R** — statistical analysis, used in coursework
- **Java** — OO programming coursework
- **C** — systems-level programming coursework
- **HTML / CSS / JavaScript** — front-end development (built BorgWarner plant map; Tarifast prototype frontend)

### Analytics & BI Tools
- **IBM Cognos Analytics** — built production customer-facing dashboard (Kirby Risk)
- **Power BI** — data visualization
- **Excel (Advanced)** — XLOOKUP, complex conditional formulas, large-scale scenario modeling (50,000+ rows), xlwings integration with Python, dashboard building, project tracking
- **Jupyter Notebooks** — data science development environment

### Machine Learning & Modeling
- Supervised learning: Ridge/Lasso/ElasticNet regression, Random Forest, Gradient Boosting (sklearn, XGBoost, LightGBM)
- Time series forecasting: recursive multi-step forecasting, walk-forward cross-validation, confidence interval generation
- Quantile regression, binary classification, feature engineering, model evaluation (RMSE, MAE, MAPE, ROC-AUC)
- Constraint-based optimization: custom 3D bin packing, demand-based allocation, priority-ranked assignment algorithms

### Platforms & Infrastructure
- **Tecsys WMS** — worked in implementation and production phases; used for data uploads
- **Microsoft Intune** — mobile device management; authored and deployed device config files
- **AWS** — AWS Certified Cloud Practitioner
- **Microsoft 365 (Teams, Outlook, Excel, SharePoint)** — professional project coordination

### Certifications
- AWS Certified Cloud Practitioner
- CAD — Purdue Milestone Program
- Mimo SQL Certification
- Python Data Structures — University of Michigan
- Microsoft Excel — LinkedIn Skill Assessment (passed)
- Salesforce/Tableau Desktop Foundations (planned)

---

## HIGH SCHOOL

### Northwestern Senior High School | Indiana

**Honors Diploma** | *August 2018 – May 2021 | GPA: 4.2/4.0*

- National Honors Society
- Varsity Athletics: Track & Field, Football, Wrestling

---

## LEADERSHIP & ACTIVITIES

### Larsen Leaders Academy | Purdue Daniels School of Business
- Selective leadership development program within DSB; admits a small cohort of high-achieving students
- Involves mentorship, leadership development, and applied experiential learning alongside the academic program

### Purdue Men's Rugby Club — Safety Officer
- Served as Safety Officer for the Men's Rugby Club, responsible for player safety protocols and coordination for a 30+ person team
- Managed safety planning, emergency procedures, and compliance with university athletic policies

### Purdue Presidential Scholarship
- Merit-based scholarship awarded at admission to Purdue University

---

## METRICS & IMPACT REFERENCE

*This section consolidates measurable outcomes for quick reference when tailoring applications.*

| Project / Role | Key Metric / Impact |
|---|---|
| Kirby Risk — Slotting Model | 14,000+ SKUs slotted, 3,800 locations mapped; model in active production use during DC buildout |
| Kirby Risk — Data Quality Report | Led to cancellation of inaccurate external data subscription |
| Kirby Risk — Labeling System | 12,000+ storage locations labeled in new DC |
| Kirby Risk — Cognos Dashboard | Live customer-facing dashboard used at counter daily |
| Kirby Risk — Zebra Scanners | 89 scanners standardized, eliminating per-device manual config |
| Cardwell Data Solutions — Rental Agent | 5-minute manual process → ~5 seconds |
| BorgWarner — PC Refresh | 200+ employees migrated |
| BorgWarner — Network Upgrade | Facility upgraded to 10G; hundreds of switches re-patched with no service interruption |
| BorgWarner — Plant Map | 400 computers indexed, mapped, and searchable; adopted by staff engineers |
| Molson Coors — Forecasting | MAPE ~5.27%, RMSE ~1,028k HL; Ridge outperformed complex models |
| Tarifast — Confidence Score | 4-component normalcy score + quantile delay model + severe-delay classifier; full-stack prototype delivered |
| IBE Capstone — Ranch Model | ~50,000-scenario cost model; received A in capstone |
| BorgWarner — Support | 100+ Tier 1 tickets resolved |

---

## CLIFTONSTRENGTHS PROFILE

*Gallup CliftonStrengths Top 5 — assessed January 2022*

| Rank | Strength | Domain |
|---|---|---|
| 1 | Competition | Influencing |
| 2 | Relator | Relationship Building |
| 3 | Self-Assurance | Influencing |
| 4 | Restorative | Executing |
| 5 | Analytical | Strategic Thinking |

---

### How Each Strength Shows Up in Your Work

**1. Competition**
You measure progress against others and need to win — not just finish. You do your best work when there are scores, rankings, or clear standards to beat. Accuracy sharpens when you know results will be compared.

*Evidence in your experience:* The slotting model went through multiple iterations not because it was broken but because you wanted it better. You identified that the external data vendor was worse than your in-house data and proved it — then replaced it. You're pursuing certifications (AWS, upcoming Tableau) in part because credentials are a measurable bar to clear. Competing in three varsity sports simultaneously in high school reflects the same pattern.

*Interview framing:* "I tend to set a high internal bar and then look for external data to know whether I've cleared it. That's part of why I'm drawn to analytics — it gives you an actual score."

---

**2. Relator**
You work best with people you know well and trust. You build depth over breadth. You're energized by hard work toward shared goals with a small, close group — not networking events.

*Evidence in your experience:* Your most successful work at Kirby Risk came from building real working relationships with the Tecsys superuser, the data engineer, and the HAI Robotics team — not just passing off deliverables. The Cardwell Data Solutions work grew directly out of a prior relationship with Huston Electric. The Data Mine project involved a tight team dynamic. Rugby is an inherently relational team sport.

*Interview framing:* "I do my best work when I understand the people I'm working with and they understand me. I tend to invest early in building that working relationship, which usually pays off when things get complicated."

---

**3. Self-Assurance**
You have a strong inner compass. You're confident in your judgment, willing to make calls without guarantees, and not easily swayed by emotional arguments. You're practical and realistic.

*Evidence in your experience:* At 18, you built the BorgWarner plant map from scratch with no template and no AI — you just decided it was needed and built it. You founded an LLC while enrolled in a demanding graduate program and working full time. You presented a data quality report to management recommending they cancel a paid subscription — that takes confidence in your analysis. You chose Ridge regression over more complex models for Molson Coors because the data supported it, not because it was the flashier choice.

*Interview framing:* "I'm comfortable making judgment calls and standing behind them. I try to gather the right data first, but once I have it, I move. I don't tend to second-guess decisions after the fact — I just try to learn and improve the next one."

---

**4. Restorative**
You're energized by problems. You dig into what's wrong, find the root cause, and fix it — you don't move on until you understand why something failed. You're particularly effective at inheriting broken or messy situations.

*Evidence in your experience:* The Kirby Risk returns SOP was a direct response to a broken process — returned items disappearing into a shelf with no accountability. The Zebra scanner fleet had configuration drift across 89 devices; you diagnosed the root cause (no standard config) and fixed it systematically. The BorgWarner network upgrade required tracing hundreds of disorganized cables before touching a single switch. The Tarifast project was essentially a diagnostic tool — building a system to detect when a shipment is going wrong and why.

*Interview framing:* "I genuinely like walking into a messy situation. When something isn't working, I want to understand exactly why before I try to fix it. That tendency has served me well in both IT troubleshooting and data work."

---

**5. Analytical**
You search for causes and patterns. You need facts, not feelings, to confirm a conclusion. You're skeptical of things that can't be measured, and you're drawn to understanding how variables interact — not just what the outcome was.

*Evidence in your experience:* Quantile regression, time-series cross-validation, 3D bin packing with constraint logic — these aren't things you stumbled into, they reflect a genuine drive to model systems correctly. You evaluated six model types for Molson Coors before picking Ridge. You compared the external data vendor's volumetrics to internal data source by source before making a recommendation. Victory, in your Competition strength, is confirmed by metrics — not by how something feels.

*Interview framing:* "I'm most comfortable when I can point to the data behind a decision. I'll push back on conclusions that aren't supported by the numbers — not to be difficult, but because I think precision matters."

---

### How the Strengths Interact

The combination is notably coherent for analytical/operations work:

- **Competition + Analytical:** You don't accept a win unless the numbers confirm it. This makes your work rigorous — you're not satisfied with "good enough" if you can't measure it.
- **Competition + Restorative:** Your strategy for winning often involves finding and eliminating flaws. You improve by diagnosing what's broken, not by hoping things get better.
- **Self-Assurance + Analytical:** Your decisions are data-driven, but you trust your instincts when you've done the work. You're not paralyzed by uncertainty — you assess, decide, and act.
- **Relator + Restorative:** You notice when people closest to you are struggling and try to fix the root cause, not just the symptom. This makes you a reliable collaborator on complex, ambiguous problems.

---

### How to Use This in Interviews

When asked "what are your strengths?":
> Don't just list them. Pick 2-3 that apply to the role and connect each to a specific story. For analytics/supply chain roles: lean on **Analytical + Restorative** (I dig into problems and find root causes, not just outputs) and **Self-Assurance** (I make judgment calls and stand behind them). **Competition** can come up naturally when discussing drive or standards.

When asked "what's a weakness?":
> **Relator** can be reframed honestly: "I invest heavily in working relationships, which sometimes means I take longer to get up to speed with a new team. But once I do, I tend to be a reliable collaborator on hard problems."

---

## POTENTIAL TALKING POINTS BY THEME

*For interview prep and cover letter framing.*

**"I build things that actually get used"**
→ Slotting model in active production at Kirby Risk; plant map adopted by BorgWarner engineers; Cognos dashboard live for customers; rental AI agent running at Huston Electric

**"I work at the intersection of data and operations"**
→ Every major project combines analytical thinking with operational context — slotting requires knowing how a warehouse actually runs; the Tecsys/HAI work requires knowing what data operations teams actually need

**"I'm self-directed and take ownership"**
→ As the only analytics resource at Kirby Risk during a major DC transition; founded an LLC while in school and working; built the BorgWarner plant map as an 18-year-old with minimal guidance

**"I know when to simplify and when complexity is warranted"**
→ Killed the external data source that was making the slotting model worse; chose Ridge over more complex ML models for Molson Coors because the data size didn't support it; argued for simple Python scripts over over-engineered solutions at Kirby

**"I have both technical depth and business judgment"**
→ Can write Python optimization algorithms AND present findings to management AND understand customer-facing implications (dashboard design, WMS flows, operational SOPs)

---

## NOTES & OPEN QUESTIONS

- **GPA:** 3.7 on resume is the DSB major-only GPA, which is the correct figure to use. Cumulative (3.57) was pulled down by the CS minor coursework. Major GPA is the standard for business school applications and is accurate to use as listed.
- **Huston Electric dates:** You said the role ran April 2018 – August 2020; LinkedIn lists it as 2018 – June 2023 (5.5 years). Reconcile which is accurate — LinkedIn may include sporadic work into early college years. Update accordingly.
- **Kirby Risk title:** Standardized to "Supply Chain Analytics Intern" — more specific than "Analytics Intern," more accurate than "Business Analyst Intern," and directly aligned with target roles. Update LinkedIn to match.
- **LinkedIn cross-check:** Document has now been reconciled against live LinkedIn data (experience, education, skills, certifications). Document is consistent with LinkedIn except for the Huston Electric date discrepancy noted above.
- **Tableau cert:** Planning to earn Salesforce-certified Tableau Desktop Foundations — add to certifications section once complete.

---

*Last updated: April 2026 | Source documents: Kyle_Cardwell_Resume_Base_Updated.docx, Kyle_Cardwell_Resume_2025_Revised.docx, Kirby Risk slotting project files, BAIM coursework (Molson Coors, Tarifast), unofficial Purdue transcript, LinkedIn profile (linkedin.com/in/kyle-e-cardwell), personal interview Q&A*
