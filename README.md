# 📧 Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- Apple needs a Principal Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
- Atliq is Software Development company can provide a dedicated software development engineer to Apple. So, the business development executive (Vineet Sharma) from Atliq is going to reach out to Apple via a cold email.

<img width="964" height="608" alt="image" src="https://github.com/user-attachments/assets/5b123c8f-5479-42f8-9a7f-5e9494c140f0" />


## Architecture Diagram
<img width="1009" height="375" alt="image" src="https://github.com/user-attachments/assets/7bf0813e-beb8-425d-948b-f7ce6c53253b" />


## Youtube Tutorial: https://youtu.be/xZqPtJAxxDI?si=R1CnnZP7BuWvygq2


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
   
