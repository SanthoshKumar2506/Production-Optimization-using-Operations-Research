# Production Optimization using Operations Research

##  Overview

This project focuses on optimizing production scheduling for a manufacturing company using Operations Research techniques. The goal was to minimize total operating costs while ensuring all customer demand is met under real-world constraints such as machine capacity, setup time, and production yield.

---

##  Business Problem

Falcon Die Casting Company faced inefficiencies in production planning due to:

* Manual, trial-and-error scheduling
* High machine setup times (8–24 hours)
* Low production yield (55–75%)
* Strict capacity constraints (regular + overtime limits)
* Uneven overtime distribution increasing labor costs

These challenges led to increased operational costs and risk of unmet demand.

---

##  Solution Approach

Developed a **Mixed Integer Linear Programming (MILP)** model to optimize production scheduling.

The model:

* Allocates production across **5 machines and 5 products**
* Considers **setup time, yield loss, and capacity constraints**
* Optimizes across **multiple time periods**
* Minimizes total cost, especially overtime

---

##  Optimization Model

### Objective Function

Minimize:

* Total overtime cost
* Setup-related inefficiencies
* Excess operational cost

---

### Decision Variables

* Production quantity per machine and product
* Machine allocation
* Setup decisions
* Inventory (for multi-week models)

---

### Constraints

* Machine capacity limits (Regular + Overtime)
* Demand fulfillment requirements
* Setup time restrictions
* Production yield adjustments
* Inventory policies across weeks

---

##  Results & Insights

* Reduced unnecessary overtime usage
* Balanced workload across machines
* Identified **capacity shortfalls in high-demand weeks**
* Highlighted opportunity to use **multi-week planning for cost savings**
* Demonstrated impact of setup sequencing on efficiency

---

##  My Contribution

* Built and implemented **optimization models using Python**
* Translated business problem into mathematical formulation
* Defined constraints, variables, and objective functions
* Analyzed model outputs and derived business insights
* Contributed to final report and presentation

---

##  Tools & Technologies

* Python
* Optimization techniques (MILP)
* Excel (data handling)

---

##  Project Assets

* Python model outputs
* Optimization results
* Demand and capacity data

---

##  Future Scope

* Real-time production planning integration
* Automated scheduling dashboards
* Scenario-based optimization for demand uncertainty
* Integration with ERP systems

---
