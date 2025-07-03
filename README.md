# 📧 Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- Nike needs a Principal Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
- Atliq is Software Development company can provide a dedicated software development engineer to Nike. So, the business development executive (Mohan) from Atliq is going to reach out to Nike via a cold email.

![img.png](imgs/img.png)

## Architecture Diagram
![img.png](imgs/architecture.png)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   Benefits:

Saves time (especially when emailing hundreds).

Personalizes at scale.

Increases reply rate with better-written messages.

Reduces writer's block.

Uses of a Cold Mail Generator:

Sales & Marketing Outreach

• Generate personalized emails to potential customers or clients.

Ο

Promote products, services, or special offers.

Reach out to leads at scale without sounding robotic.

2. Job Hunting / Freelancing

• Contact potential employers or clients.

• Offer your services or portfolio.

O

Request informational interviews or collaboration.

3. Startup Fundraising

• Contact investors (angel investors, VCs).

• Pitch your startup idea or send a deck.

4. Networking

• Reach out to industry experts or mentors.

Request meetings or guidance.

• Start professional conversations.

5. Link Building / Guest Posting (SEO)

• Reach out to websites or blog owners for guest posting.

• Propose collaborations to get backlinks.



Copyright (C) Codebasics Inc. All rights reserved.

**Additional Terms:**
This software is licensed under the MIT License. However, commercial use of this software is strictly prohibited without prior written permission from the author. Attribution must be given in all copies or substantial portions of the software.


