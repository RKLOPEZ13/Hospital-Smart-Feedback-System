# Smart Feedback Mechanism

## Overview
The Smart Feedback Mechanism is a web-based feedback system designed for San Antonio Medical Center of Lipa, Inc. (SAMCLI). It consolidates patient, visitor, and staff feedback into a centralized dashboard, enabling Quality Assurance (QA) personnel to monitor, analyze, and report feedback in real time. The system leverages **smart sentiment analysis** using LLaMA 3.3 70B-Versatile to classify feedback as positive, neutral, or negative, and supports ISO 9001:2015-aligned reporting for continuous quality improvement.

## Key Features
- **External Feedback Collection:**  
  Patients and visitors submit feedback via QR codes linked to mobile-optimized forms. Each QR code allows one submission per visit and includes Google reCAPTCHA for spam prevention.
  
- **Internal Feedback Collection:**  
  Staff submit monthly feedback via institutional email verification and one-time passwords (OTP). This ensures focused, high-value reporting of systemic issues.
  
- **Smart Sentiment Analysis:**  
  Narrative feedback is processed using LLaMA AI to classify sentiment, reducing manual workload while preserving human oversight.
  
- **Real-Time QA Dashboard:**  
  Displays key metrics, interactive analytics graphs (13 total), and a dynamic feedback table. Filters include status, sentiment, source, department, urgency, rating, and date range.
  
- **Bayesian Smoothing Analytics:**  
  Stabilizes department-level percentages from small sample sizes, producing reliable and interpretable performance indicators.
  
- **PDF Report Generation:**  
  Generates ISO-aligned reports including:  
  - Key Takeaways and Overall Situation  
  - Top Problem Areas  
  - Successes and Positive Highlights  
  - Recommended Actions  
  All analytics graphs are embedded for visual support.

## Benefits
- Consolidates fragmented feedback channels into a single, structured platform.
- Provides actionable, ISO-aligned insights to improve patient care and service quality.
- Enables small hospitals to maintain compliance with ISO 9001:2015 requirements.
- Reduces administrative burden while preserving staff oversight in feedback analysis.
- Supports data-driven decision-making and continuous quality improvement.

## Technologies Used
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** Express.js, Node.js  
- **Database:** MongoDB  
- **Real-Time Updates:** Socket.IO  
- **AI Integration:** LLaMA 3.3 70B-Versatile for sentiment analysis  
- **Security:** Google reCAPTCHA, OTP authentication, encryption  
- **PDF Generation:** Automated report synthesis for ISO-aligned documentation  

## System Workflow
1. User accesses external or internal feedback form.  
2. Feedback is validated (QR code or email OTP) and submitted.  
3. QA Dashboard displays incoming feedback with sentiment classification.  
4. Bayesian smoothing applied to department-level analytics.  
5. Filters dynamically update analytics graphs and feedback table.  
6. QA staff can generate comprehensive PDF reports for ISO documentation.  

## System Purpose
The Smart Feedback Mechanism transforms SAMCLI’s feedback process from manual, fragmented channels into a structured, data-driven platform. It ensures timely and accurate insights, supports ISO 9001:2015 compliance, and enables continuous quality improvement in patient care and hospital operations.
