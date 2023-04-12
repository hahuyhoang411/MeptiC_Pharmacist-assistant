# MeptiC_Busitech
This is the demo of MeptiC for BusiTech 2023

MeptiC Copilot is a virtual assistant to prove the potential of AI could enhance the Vietnamese healthcare system.
![image](https://user-images.githubusercontent.com/64120343/231550602-9eb14aa0-4273-4e2f-8b25-0623ef112f08.png)

# Reason
As a healthcare student, I came face-to-face with the grim realities of an overburdened healthcare system. During my clinical internship, I gained firsthand experience of the challenges that healthcare professionals face on a daily basis. I was surprised to see that even well-trained staff members made mistakes due to the stressful and chaotic nature of the hospital ward. This experience was truly enlightening and helped me to better understand the complexities of the healthcare industry.

# Statistic
The healthcare system in Vietnam faces significant challenges due to a shortage of pharmacists, with only 0.83 pharmacists available per 1000 individuals. This shortage has led to severe limitations in staffing and has resulted in an alarming medication error rate of approximately 39%.
![image](https://user-images.githubusercontent.com/64120343/231555161-1783575d-703d-4a1a-afab-a640ea8a53ba.png)


# Goals
MeptiC has 2 main goals:
1. Enhancing patient safety through acurrately verify patients' prescriptions
2. Supporting pharmacists' informed decision making through summarization of patient health records and medications.

# Functions
MeptiC has 3 functions:
## 1. Prescription Verification
MeptiC can instantly cross-check new prescriptions against a patient's records and medical databases.
In seconds, it can detect dangerous drug interactions or overdoses, alerting pharmacists to take action before the patient is harmed.
![image](https://user-images.githubusercontent.com/64120343/231552700-03636062-4c8c-4f25-a0ca-3adca8827634.png)

## 2. Electronic health record Summarization
MeptiC provides pharmacists with a full view of patient health records and medications, enabling pharmacists to make safer, more informed decisions, especially for patients on multiple medications.
![image](https://user-images.githubusercontent.com/64120343/231558649-d1ae98b2-8011-4ab7-9c23-b63e2b0f99ac.png)

## 3. Question and Answering
MeptiC taps into extensive medical knowledge to offer a safety net against knowledge gaps, increasing efficiency and accuracy.
!

# Technical approach
## 1. Reason and Act
Reason and Action is an architecture to mimic how the human brain works, enabling machines to reason and make decisions in a way that is similar to humans
<video src='[your URL here](https://user-images.githubusercontent.com/64120343/231559802-681b57fd-7904-43ad-8cde-b659a0f3a62e.mp4)' width=180/>

## 2. Semantic Search
Meptic uses AHFS as a knowledge base for precise drug information.
AHFS (American Hospital Formulary Service) is a comprehensive classification system for drugs and other therapeutic agents used in healthcare. It provides standardized coding and terminology to help healthcare professionals identify and communicate information about medications, including indications, dosages, and potential interactions. AHFS is widely used in the United States and is published by the American Society of Health-System Pharmacists (ASHP).

# FQA
### Why AHFS?
There are 2 main reasons why we chose AHFS as a knowledge base for MeptiC.
1. In Vietnam, the AHFS has been endorsed by the Ministry of Health as a primary resource for numerous healthcare guidelines and articles, including the Vietnamese National Drug Formulary (VNDF)
2. following real-life trials, we discovered that while the VNDF does not include several drugs that are commonly used in Vietnamese hospitals, the AHFS contains them all.
