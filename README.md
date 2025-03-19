# Smart India Hackathon Workshop
# Date: 17-03-2025
## Register Number:212224230269
## Name:Sivabalan M
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
The Web-based Selector-Applicant Simulation Software will streamline and enhance the recruitment process through an automated system that assists interviewers and applicants. The software will simulate a boardroom-style experience that ensures questions and answers are tailored to the candidate’s skill level, facilitating a more accurate and objective assessment. This system will:

Generate relevant questions based on the job role and candidate profile.
Evaluate responses and question relevancy.
Provide real-time feedback to the experts and candidates.
Quantify scores based on response accuracy and relevance.

## Proposed Solution / Architecture Diagram
User Interface (UI):
For Experts: Admin panel to configure questions, conduct interviews, and evaluate responses.
For Candidates: A clean, simple interface for answering questions and submitting responses.
Backend System:
Question Generator Engine: Generates dynamic, role-based questions (Ice-breaking, Technical, Managerial).
Response Evaluation Engine: Uses NLP to analyze the relevance and quality of answers.
Scoring System: Calculates scores for both questions and responses (Question Relevancy and Answer Relevancy).
Database Layer:
Candidate Database: Stores candidate profiles, interview results, and feedback.
Expert Database: Stores expert evaluation metrics, feedback, and past performance.
AI/ML Integration:
Natural Language Processing (NLP): To assess candidate responses for relevancy and coherence.
Machine Learning Algorithms: To improve question generation based on past performance and patterns.
![p 1](https://github.com/user-attachments/assets/584f1ef0-d44d-4c17-880c-ab8cdbe38714)


## Use Cases
Candidate Registration:

A candidate can register, upload their resume, and submit their profile for review.
Expert Question Configuration:

Experts can define the areas of expertise required for the interview and configure questions accordingly.
Interview Simulation:

The system generates a mix of ice-breaker, technical, and managerial questions based on the candidate's profile.
The expert and candidate interact in real-time during the interview.
Response Evaluation:

Expert evaluates responses by scoring them based on their relevance and depth.
AI evaluates the response quality based on keywords, context, and relevance to the question.
Scoring and Feedback:

Both experts and candidates receive detailed feedback and scores, including a breakdown of question relevance and answer performance.
Final Evaluation Report:

A detailed report is generated for each candidate, highlighting strengths, weaknesses, and suitability for the position.


## Technology Stack
Frontend (Web-based UI):

HTML, CSS, JavaScript (ReactJS/Angular) for the user interface.
WebSockets for real-time communication between expert and candidate.
Backend:

Node.js / Django / Flask for building the server-side logic.
Python for integrating NLP and machine learning features.
Database:

MySQL or MongoDB for storing user profiles, questions, and interview results.
AI/ML and NLP:

Natural Language Processing (NLP) tools like spaCy or NLTK for analyzing answers.
Machine Learning Libraries like TensorFlow or Scikit-learn to improve question generation and evaluation over time.
Cloud Infrastructure:

AWS, Azure, or Google Cloud for hosting the web application and databases.
Docker for containerization and easy deployment.
Authentication:

OAuth 2.0 or JWT for secure login and role-based access control.
Dependencies
External APIs & Libraries:

NLP libraries (spaCy, NLTK).
Machine learning frameworks (TensorFlow, Keras).
Cloud Infrastructure Providers:

AWS, Azure, or Google Cloud for hosting and storage.
Security Measures:

Encryption protocols (SSL/TLS).
Secure authentication mechanisms (OAuth, JWT).
Real-time Communication:

WebSocket for real-time communication during interviews.
APIs for scheduling and session management.

## Dependencies
External APIs and Libraries:

NLP libraries like spaCy or NLTK for language processing.
Machine learning libraries like TensorFlow or Scikit-learn for intelligent question generation.
Cloud Infrastructure:

AWS, Google Cloud, or Azure for scalable hosting and storage.
Docker for containerization and microservices architecture.
Authentication & Security:

JWT (JSON Web Tokens) or OAuth for secure login.
SSL/TLS encryption for secure data transmission.
Real-time Communication:

WebSocket for real-time interaction between the candidate and expert.
