# Smart City Complaint Analysis Dashboard

## Problem Statement

Modern cities receive thousands of citizen complaints related to public services such as water supply, sanitation, roads, traffic management, drainage systems, and public safety. Managing and resolving these complaints efficiently is a major challenge for city authorities.

This project analyzes smart city complaint data to identify complaint patterns, service efficiency, complaint hotspots, and department performance. The objective is to support data-driven decision-making through interactive dashboards and actionable insights.

---

## Project Objectives

- Analyze citizen complaint data.
- Identify recurring civic issues.
- Evaluate department performance.
- Measure complaint resolution efficiency.
- Monitor citizen satisfaction.
- Develop interactive Power BI dashboards.
- Provide recommendations for service improvement.

---

## Dataset Description

The dataset contains approximately 1,000,000 smart city complaints.

### Features

| Column | Description |
|----------|------------|
| Complaint_ID | Unique complaint identifier |
| Complaint_Date | Date complaint was registered |
| Resolved_Date | Date complaint was resolved |
| Category | Type of complaint |
| Department | Responsible department |
| Zone | Complaint location |
| Priority | Low, Medium, High |
| Status | Resolved/Pending |
| Citizen_Satisfaction | Satisfaction rating |
| Resolution_Delay_Days | Resolution duration |
| Complaint_Description | Complaint details |

---

## Data Cleaning & Preprocessing

Performed using Python:

- Missing value handling
- Duplicate removal
- Date conversion
- Resolution delay calculation
- Data validation
- Feature engineering

---

## KPI Definitions

### Total Complaints
Total number of complaints registered.

### Resolved Complaints
Number of complaints successfully resolved.

### Resolution Rate

Resolution Rate = (Resolved Complaints / Total Complaints) × 100

### Average Resolution Time

Average days taken to resolve complaints.

### High Priority Complaints

Number of complaints marked as High Priority.

### Citizen Satisfaction Score

Average satisfaction rating provided by citizens.

### Complaint Hotspot Zones

Zones generating the highest number of complaints.

### Department Performance Score

Measured using:

- Average Resolution Delay
- Resolution Rate

Lower delay and higher resolution rate indicate better performance.

---

## Analysis Performed

### Zone vs Complaint Count
Identifies complaint hotspots across city zones.

### Category vs Resolution Time
Analyzes which complaint categories take longer to resolve.

### Department vs Performance
Measures department efficiency using average resolution delay.

### Complaint Trends Over Time
Tracks complaint growth and seasonal patterns.

### Priority vs Resolution Delay
Evaluates urgency handling performance.

---

## Dashboard Sections

### Executive Overview
- Total Complaints
- Resolution Rate
- Satisfaction Score
- Complaint Trends

### Complaint Dashboard
- Complaint Categories
- Resolution Patterns
- Complaint Growth Trends

### Geographic Dashboard
- Zone-wise Issues
- Complaint Hotspots
- Geographic Distribution

### Service Performance Dashboard
- Department Performance
- Resolution Efficiency
- Priority Handling

---

## Dashboard Screenshots

Add screenshots inside the images folder.

Example:

- Executive Overview Dashboard
- Complaint Dashboard
- Geographic Dashboard
- Service Performance Dashboard

---

## Key Findings

- Certain complaint categories occur more frequently.
- Some departments receive significantly higher workloads.
- High-priority complaints are resolved faster.
- Specific zones generate recurring complaints.
- Citizen satisfaction is strongly related to resolution speed.

---

## Business Recommendations

- Allocate additional resources to overloaded departments.
- Focus on high-complaint zones.
- Reduce resolution delays.
- Improve coordination between departments.
- Monitor citizen satisfaction regularly.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Power BI
- DAX
- Google Colab

---

## Project Structure
