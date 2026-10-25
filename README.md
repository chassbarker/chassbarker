# Hi, I'm Chassidy Barker 👋

### Cloud Computing | AWS | AI Applications | DevOps | Software Development

I'm a self-directed Cloud Computing student in San Antonio, graduating in December 2026 with a 3.7 GPA. I love technology and get a little obsessed with solving problems! Outside of class, I've built three independent applications using Python, AWS, automated testing, and GitHub Actions.

I also bring an 11-month web development internship and over four years of remote work experience. I'm looking for early-career cloud, DevOps, AI, or software development opportunities in San Antonio or remotely.

[Portfolio](https://www.chassidybarker.com/) | [LinkedIn](https://www.linkedin.com/in/chassidybarker) | [Credly](https://www.credly.com/users/chassidy-barker) | [Email](mailto:chassidybarker@gmail.com)

## Featured Projects

### 🔎 AI Log Anomaly Detector

Python ML pipeline that flags unusual system logs with Isolation Forest and assigns separate rule-based severity levels to help prioritize review.

**Stack:** Python, scikit-learn, NumPy, Streamlit, Docker, pytest, GitHub Actions.

- Built an interactive dashboard with sample, paste, and upload inputs, adjustable detection settings, and CSV/JSON exports.
- Added automated tests, CodeQL scanning, and dependency monitoring.
- Containerized the dashboard with a non-root runtime and health check; CI builds the image and tests CLI analysis and dashboard readiness.
- Verified the Docker dashboard locally with sample log analysis and a CSV download.

**Troubleshooting example:** When localhost refused to connect, I checked `docker ps -a` and found that no container existed. I started the image with port 8501 mapped to localhost, then verified the container was healthy and the dashboard worked.

[Live Demo](https://chass-ai-log-anomaly-detector.streamlit.app/) | [GitHub](https://github.com/chassbarker/ai-log-anomaly-detector)

### 🤖 AI Appointment Scheduler V2.0

Full-stack appointment application with Supabase authentication and PostgreSQL, an AWS serverless scheduling layer, and a conversational booking interface.

**Stack:** JavaScript, HTML/CSS, Supabase, PostgreSQL, AWS Lambda, API Gateway, Terraform, IAM, CloudWatch, GitHub Actions, Python, Selenium WebDriver.

- Built appointment CRUD, search/filtering, date validation, and user-specific access through Row Level Security.
- Added conversational booking, rescheduling, and cancellation with explicit confirmation.
- Defined the AWS API and Lambda infrastructure with Terraform and added CloudWatch logging.
- Added automated application and scheduling tests with GitHub Actions CI.
- Developed and ran five Python Selenium WebDriver checks in Microsoft Edge covering navigation, login-field visibility, and required-field form validation; documented and troubleshot browser automation failures. [View Selenium tests](https://github.com/chassbarker/ai-appointment-scheduler/blob/main/test_selenium.py).
- Expanded browser automation with an authenticated Selenium end-to-end test that logs in, creates, edits, and cancels a test appointment, then verifies the resulting history. Added demo-friendly pauses and best-effort credential masking; the local recording-mode test passed in about 26 seconds. [View E2E test branch](https://github.com/chassbarker/ai-appointment-scheduler/blob/test/selenium-appointment-e2e/tests/test_selenium_e2e.py).

The conversational interface uses a deterministic flow; connecting an AI language model is a future improvement.

[Live Demo](https://chassbarker.github.io/ai-appointment-scheduler/) | [GitHub](https://github.com/chassbarker/ai-appointment-scheduler)

### ☁️ Serverless Intelligent Contact System

AWS serverless contact application that validates submissions, classifies inquiries with rules, and stores them in DynamoDB.

**Stack:** Node.js, AWS Lambda, API Gateway, DynamoDB, AWS SAM, IAM, CloudWatch, GitHub Actions.

- Built client-side and server-side validation with rule-based inquiry classification.
- Defined infrastructure with AWS SAM, least-privilege permissions, restricted CORS, and API throttling.
- Added privacy-conscious logging and CloudWatch error monitoring.
- Automated Node.js tests, SAM validation, and application builds in CI.

[Live Demo](https://chassbarker.github.io/serverless-intelligent-contact-system/frontend/) | [GitHub](https://github.com/chassbarker/serverless-intelligent-contact-system)

## Technical Skills

| Area | Tools and experience |
| --- | --- |
| Languages | Python, JavaScript, SQL, PHP, HTML, CSS |
| Cloud and data | AWS Lambda, API Gateway, DynamoDB, IAM, CloudWatch, S3, Supabase, PostgreSQL |
| Development and DevOps | Docker, Terraform, AWS SAM, Git, GitHub Actions, Linux, Selenium WebDriver (Python), automated testing |
| AI and applications | scikit-learn, Isolation Forest, Streamlit, Amazon Lex |
| Web development | WordPress, Elementor, responsive interfaces |
| AI developer tools | ChatGPT, GitHub Copilot, OpenAI Codex |

**Continuing to learn:** Docker, Kubernetes, cloud automation, and DevOps workflows.

## Professional Experience

**Web Development Intern | Public Alliance**  
Completed an 11-month internship, including the summer cooperative education experience, using WordPress, Elementor, ACF, PHP, HTML, CSS, and JavaScript.

- Created a TRC4 banner that the team used and developed responsive features approved for production.
- Supported Sitterle Homes website maintenance and Milberger’s content and SEO updates.

**Remote work:** Over four years as a Customer Order Specialist with QVC.

## Education and Credentials

**Northwest Vista College | San Antonio, TX**

- **Bachelor of Applied Technology, Cloud Computing** | Expected December 2026 | GPA: 3.7
- **Associate of Applied Science, Digital Media** | August 15, 2025 | Cum Laude
- **Level 1 Certificate, Digital Media** | August 15, 2025

**Occupational Skills Awards**

- Publishing for Digital Media | August 15, 2025
- Social Media Content Creation | August 15, 2025
- Web, Digital Design & Development | August 15, 2025
- Web, Digital Design & Development II | August 15, 2025
- Web Designer | August 8, 2024

## Honors and Recognition

- **Cum Laude** | AAS in Digital Media, Northwest Vista College | 2025
- **Phi Theta Kappa Honor Society** | Beta Lambda Upsilon Chapter | Inducted August 2026
- **Creative Problem-Solving Skills Badge** | Northwest Vista College | August 8, 2025 | 10 participation hours recorded

## College Involvement

**Member, NVC AI and Cloud Club | Northwest Vista College | June 2026–Present**

- Attended club meetings in September and October 2026.
- Attended the Student Enterprise Network Project event on September 3, 2026.
- Attended the Learn IP Subnetting workshop on September 10, 2026.

## Coursework and Training

Hands-on coursework includes cloud architecture and operations, SageMaker machine learning, and analytics with Athena, Glue, Redshift, EMR, and Hive.

[Amazon Lex Appointment Chatbot video demo](https://www.youtube.com/watch?v=0P_Qbqcrrw4)

<div align="center">

## 🏅 AWS Academy Graduate

<table>
<tr>

<td align="center">
<strong>Data Engineering</strong><br>
<a href="https://www.credly.com/badges/f4e12459-755f-47db-9e74-30ce2c2e8059/public_url" title="AWS Academy Graduate - Data Engineering - Training Badge">
<img src="https://images.credly.com/size/680x680/images/8a28a66c-151d-4f2d-b021-ca7d3e146437/blob" width="100"/>
</a>
</td>

<td align="center">
<strong>Machine Learning for NLP</strong><br>
<a href="https://www.credly.com/badges/0f1e95a8-66cf-4341-9665-7b36867eaa3e" title="AWS Academy Graduate - Machine Learning for Natural Language Processing">
<img src="https://images.credly.com/images/683b2e3c-0d28-42a2-ab84-7203a209f9d0/blob" width="100"/>
</a>
</td>

<td align="center">
<strong>Cloud Architecting</strong><br>
<a href="https://www.credly.com/earner/earned/badge/7516a435-8d4d-46a3-9fe4-501c6513bec5" title="AWS Academy Cloud Architecting">
<img src="https://images.credly.com/size/128x128/images/fcafd0c9-42da-4703-a191-0c397203dc1b/blob" width="100"/>
</a>
</td>

</tr>

<tr>
<td><br></td>
<td><br></td>
<td><br></td>
</tr>

<tr>

<td align="center">
<strong>Cloud Operations</strong><br>
<a href="https://www.credly.com/earner/earned/badge/930fcbb1-28c6-4319-929d-90fd0437c132" title="AWS Academy Cloud Operations">
<img src="https://images.credly.com/size/128x128/images/07e7ba52-aea4-431f-ba2d-a4113efd1d5a/blob" width="100"/>
</a>
</td>

<td align="center">
<strong>Cloud Security Foundations</strong><br>
<a href="https://www.credly.com/earner/earned/badge/6fba5143-dda2-4393-bde7-5f28a73f16b3" title="AWS Academy Cloud Security Foundations">
<img src="https://images.credly.com/size/128x128/images/7f7ea828-a10d-44f8-8baa-58a9c1af7671/blob" width="100"/>
</a>
</td>

<td align="center">
<strong>Engineering Operations Tech</strong><br>
<a href="https://www.credly.com/earner/earned/badge/8dbcef68-1083-4edf-85b4-f8ad560babeb" title="AWS Academy Engineering Operations Technicians">
<img src="https://images.credly.com/size/128x128/images/42676763-0f40-42e2-8ddb-a0005a572759/blob" width="100"/>
</a>
</td>

</tr>

<tr>
<td><br></td>
<td><br></td>
<td><br></td>
</tr>

<tr>

<td align="center">
<strong>Machine Learning Foundations</strong><br>
<a href="https://www.credly.com/earner/earned/badge/638248ab-ae91-4845-b57e-43b7984cad61" title="AWS Academy Machine Learning Foundations">
<img src="https://images.credly.com/size/128x128/images/727c2754-d727-4e27-a1aa-3de2425ce239/blob" width="100"/>
</a>
</td>

<td></td>
<td></td>

</tr>
</table>

<br>

**Data Engineering • Machine Learning for NLP • Cloud Architecting • Cloud Operations • Cloud Security Foundations • Engineering Operations Technicians • Machine Learning Foundations**

</div>


---

**Always learning. Always building. Always improving.**
