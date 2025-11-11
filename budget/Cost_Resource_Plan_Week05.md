# Cost & Resource Plan — Week 05

> Project: AI-LungCare  
> Team: Waleed Isskandar Almandari, Yaseen Mohammed Awad, Alwaleed Hassan Elyas  
> Supervisor: Dr. Farhan Khan (Senior Lecturer, UTeM Malacca; Assistant Professor, GIK Institute; Corporate Trainer of AI & Data Science)  
> Date: 10/11/2025

## Links
- Schedule (Planner/Excel): [add link or file path]
- Repository: https://github.com/waleedisskandar-bot/AI-LungCare
- Folder for this plan: /budget/

## Part 2 – Resource Identification (linked to WBS)

| WBS ID | Task | Resource Type | Resource Name | Qty / Hours | Description |
|:--:|:--|:--|:--|:--:|:--|
| 1.1 | Collect and clean X-ray dataset | Human | Waleed Isskandar Almandari | 6 hrs | Data collection and labeling |
| 1.2 | Model training and tuning | Human | Yaseen Mohammed Awad | 8 hrs | Train CNN and optimize hyperparameters |
| 1.3 | Web integration (React + Flask) | Human | Alwaleed Hassan Elyas | 7 hrs | Frontend and backend integration |
| 1.4 | Project supervision | Human | Dr. Farhan Khan | 2 hrs | Consultation and feedback |
| 2.1 | Model development | Software | Python (Google Colab) | — | Model training environment |
| 2.2 | Code repository | Software | GitHub | — | Version control and team collaboration |
| 2.3 | Web frameworks | Software | React & Flask | — | System integration |
| 3.1 | GPU computing | Hardware | Cloud GPU Instance | 10 hrs | Model training hardware |
| 3.2 | Workstations | Hardware | Personal laptops | 3 units | Development and testing |
| 4.1 | Meetings & coordination | Other | MS Teams | — | Team communication |
| 4.2 | Scheduling | Other | MS Project | — | Timeline tracking |




## Part 3 – Task Cost Estimation

> Formula = Rate × Hours/Qty

| Task | Resource | Hours/Qty | Rate (RM/hr or flat) | Total Cost (RM) |
|:--|:--|:--:|:--:|:--:|
| Collect and clean X-ray dataset | Waleed Isskandar Almandari | 6 | 25 | 150 |
| Model training and tuning | Yaseen Mohammed Awad | 8 | 25 | 200 |
| Web integration (React + Flask) | Alwaleed Hassan Elyas | 7 | 25 | 175 |
| Project supervision | Dr. Farhan Khan | 2 | 40 | 80 |
| GPU Computing | Cloud GPU Instance | 10 | 8 | 80 |
| Tools and Software (flat) | Colab, React, Flask | — | 50 | 50 |
| **Subtotal** | — | — | — | **735 RM** |

**Observation:**  
- Highest cost from human work (data prep + model training).  
- GPU and software costs are moderate.  
- Supervisor consultation and tools are fixed, small costs.



## Part 4 – Simple Budget Summary

| Cost Category | Example Items | Subtotal (RM) |
|:--|:--|:--:|
| **Human Resources** | Team members (Waleed, Yaseen, Alwaleed) + Supervisor (Dr. Farhan) | 605 |
| **Hardware / Cloud** | GPU instance and laptops | 130 |
| **Software / Licenses** | Colab, React, Flask, MS Project | 50 |
| **Communication** | MS Teams meetings and coordination | — |
| **Total Estimated Cost** |  | **≈ 785 RM** |

**Notes:**  
- Most of the budget is human labor (> 75 %).  
- Hardware/cloud costs depend on GPU usage hours.  
- Software tools are mostly free (open source or educational licenses).  
- Communication tools (MS Teams) are free under university accounts.  


---

## Part 5 – Link Costs to Schedule

| WBS ID | Task | Start Date | End Date | Estimated Cost (RM) | Milestone Impact |
|:--:|:--|:--|:--|:--:|:--:|
| 1.1 | Collect and clean X-ray dataset | Week 1 | Week 2 | 150 | Data Preparation Complete |
| 1.2 | Model training and tuning | Week 3 | Week 4 | 200 | Model Performance Validated |
| 1.3 | Web integration (React + Flask) | Week 5 | Week 6 | 175 | System Integration Ready |
| 1.4 | Project supervision & testing | Week 6 | Week 7 | 80 | Supervisor Approval |
| 3.1 | GPU computing (cloud) | Parallel Weeks 3–4 | — | 80 | — |
| 4.1 | Reporting & Presentation | Week 8 | Week 9 | 100 |  Final Submission |

### Observations
- Costs **peak during Weeks 3–4** due to GPU training and developer hours.  
- **Human resources** dominate early and mid phases; supervision occurs near milestones.  
- Align high-cost periods with **available budget and sprint cycles**.

