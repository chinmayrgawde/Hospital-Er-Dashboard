# 🏥 Hospital Emergency Room (ER) Analytics & Patient Flow Dashboard

# 1. Recommended Structure & Headline
Repository Headline
Real-Time Emergency Room (ER) Operational Intelligence: Triage Efficiency, Wait Times, Patient Satisfaction & Admission Pathways Dashboard

# 2. Short Description & Purpose
Overview
The Hospital ER Analytics Dashboard is an operational monitoring and decision-support solution designed in Microsoft Power BI. Emergency Departments operate under high pressure, dynamic capacity constraints, and critical time-to-treatment benchmarks. This reporting suite provides clinical directors, nurse managers, and hospital administrators with near-real-time visibility into patient throughput, triage distribution, bottleneck periods, and quality of care.
Core Objectives
1.	Reduce Door-to-Doctor Wait Times: Detect peak arrival spikes and acute bottlenecks across shifts and triage categories.
2.	Track Triage Severity & Acuity (ESI Levels): Monitor immediate-need vs. non-urgent patient distribution to safeguard bed and doctor allocation.
3.	Elevate Patient Experience: Correlate wait durations directly with net patient satisfaction scores.
4.	Streamline Admission & Discharge Pathways: Track conversion rates from ER consultation to inpatient ward admissions vs. routine discharges and specialist referrals.

# 3. Tech Stack
List the key technologies used to build the dashboard.

Example: The dashboard was built using the following tools and technologies:
• 📊 Power BI Desktop – Main data visualization platform used for report creation.
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the data.
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures, dynamic visuals, and conditional logic.
• 📝 Data Modeling – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.
• 📁 File Format – .pbix for development and .png for dashboard previews.

# 4. Features & Key Highlights
1. Executive Summary & Operational Cockpit
●	Total Patient Inflow: Live counts of daily and monthly emergency registrations.
●	Average Wait Time (Door-to-Doctor): Dynamic tracking of wait duration in minutes across all arrival hours.
●	Patient Satisfaction Index: Aggregated patient rating score linked with operational performance.
●	Admission Conversion Rate (%): Proportion of ER arrivals escalated to inpatient hospital beds.
2. Patient Flow & Hourly Arrival Heatmap
●	Peak Surge Analysis: Day-of-week vs. hour-of-day matrices highlighting peak ER crowding (e.g., Sunday evenings, Monday mornings).
●	Left Without Being Seen (LWBS) Alert: Tracks patient walkout rates when wait thresholds exceed target limits.
3. Triage & Acuity Breakdown (ESI Severity Levels)
●	Dynamic segmentation of visits by clinical urgency:
○	Immediate / Resuscitation (Level 1)
○	Emergent (Level 2)
○	Urgent (Level 3)
○	Less Urgent (Level 4)
○	Non-Urgent (Level 5)
●	Cross-filtering enabling instant review of high-priority cases vs. fast-track eligible non-urgent patients.
4. Referral & Admission Disposition Pathways
●	Breakdown of patient origin: Self-presentation, Ambulance/EMS, Physician referral, or Inter-facility transfer.
●	Downstream routing analysis tracking ICU transfers, surgical ward admissions, and outpatient discharge instructions.

# 5. Screenshots /Demo 




