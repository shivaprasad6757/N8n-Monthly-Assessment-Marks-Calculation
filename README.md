# N8n-Monthly-Assessment-Marks-Calculation

This project automates the monthly assessment evaluation process for students as part of my Automation learning at Innomatics Research Labs. Using n8n, I built a complete workflow that simplifies the calculation of average marks and determines eligibility for placement drives — all without manual intervention.

**🎯Objective**
- To automate the process of:
- Collecting module-wise assessment scores
- Calculating average marks
- Evaluating student eligibility for placement
- Sending instant automated feedback

**🧩 Workflow Overview**
**✨ 1. Form-Based Input Collection**

Created an n8n Form to collect module-wise marks for:
**Data Analytics (DA) students**
**Data Science (DS) students**

**⚙️ 2. Automated Calculations**
- Average marks were computed using Function nodes in n8n.
- Logic ensures consistent and error-free data processing.

**🔍 3. Eligibility Evaluation**
Implemented conditional logic using IF nodes:
- ✅ Eligible: Average > 70
- ⚠️ Not Eligible: Average ≤ 70
- Includes tailored suggestions for improvement.

**📩 4. Instant Notifications**
- Students automatically receive personalized messages regarding:
- Their average score
- Eligibility status
- Suggestions for improvement if applicable

**🛠️ Skills & Tools Used**
- n8n Workflow Automation
- Google Forms Integration
- Function Nodes for Data Processing
- IF Nodes for Conditional Logic
- Automation Triggers & Notifications

**🚀 Impact**
- This automation project:
- Reduces manual evaluation time
- Ensures consistent and error-free calculations
- Provides real-time results to students
- Streamlines the assessment workflow for academic teams

**📸 Screenshots**
<img width="1585" height="744" alt="Placement Eligibility Screenshot" src="https://github.com/user-attachments/assets/26538ac0-28a6-4029-878d-f2744758eec6" />
