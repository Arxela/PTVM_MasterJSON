# PTVM Activity Advisor - Master JSON

This repository contains the **master JSON** for the PTVM (Personal Time Value Metric) Activity Value Advisor system.

---

## 🔹 Purpose

The JSON defines:

- **Categories** (Strategic Thinking, Value Creation, Learning, Recovery, Execution, etc.)  
- **Subcategories** under each category  
- **Activity types** and their default notes  
- **Leverage multipliers** for RM/hr calculation  
- **Example guidance** (`example_note`) for users to understand each activity  

This JSON is the **official master file** used by PTVM and Claude AI to suggest categories, subcategories, and value calculations for logged activities.

---

## 🔹 Usage

1. **Master JSON (official)**  
   - URL (raw link): `https://raw.githubusercontent.com/<username>/<repo-name>/main/PTVM_ActivityAdvisor.json`  
   - Users should **not edit** this file directly. Updates are controlled by the admin.  

2. **Local JSON (personal copy)**  
   - Users can download the master JSON to modify for personal experiments.  
   - Load their local copy into Claude/PTVM to test custom categories, leverage, or notes.  

---

## 🔹 RM/hr Calculation

The system calculates $/hr based on the user’s **Daily Value Target**:
