# CHAD 🤖
## Healthcare Chatbots for COMP4461 Project Two
Authors: Tiffany Fu, Nicole Lucas, Sherie Lam, Edith Leung

<img width="602" alt="Screenshot 2024-03-26 at 7 39 43 PM" src="https://github.com/tiffanyfu7/hci-p2-healthcare-chatbots/assets/71473099/11a0d621-2e81-42f4-ad0d-467e0ce86f55">

<a href="https://docs.google.com/presentation/d/1pw1Ttja2CEmkxsx-5gDffttAko7qnYzHE5KAZWmp6t4/edit?usp=sharing">Presentation Slide</a> | <a href="https://youtu.be/3zHUk017LXM">Video Demo</a>
  

> ✨ Our solution is an integrated healthcare application that utilizes AI chatbots to collect customer information, enable quick interactions with datasets, and summarize conversations. 

### CHAD for Patients
<img width="595" alt="Screenshot 2024-03-26 at 7 42 10 PM" src="https://github.com/tiffanyfu7/hci-p2-healthcare-chatbots/assets/71473099/391ee8ce-16ad-4e3d-a6e0-15df1a06dbd1">
  
Collect preliminary patient information using stages and prompts  
*To run patient chatbot:*
```
cd patient
pip intall -r requirements.txt
streamlit run patient_chatbot.py
```

### CHAD for Caregivers
<img width="920" alt="Screenshot 2024-03-26 at 7 41 21 PM" src="https://github.com/tiffanyfu7/hci-p2-healthcare-chatbots/assets/71473099/7fb64327-bf4f-40d9-821d-2c75a7c44efa">
  
Allow caregivers to interact with Patient Records stored in file  
*To run caregiver chatbot:*
```
cd caregiver
pip intall -r requirements.txt
streamlit run src/Home.py
```

### CHAD for Doctors
<img width="349" alt="Screenshot 2024-03-26 at 7 41 01 PM" src="https://github.com/tiffanyfu7/hci-p2-healthcare-chatbots/assets/71473099/0847d7ff-f618-4456-af42-6d1b5b1361a2">
  
Summarize conversational transcripts between doctors and patients  
*To run doctor chatbot:*
```
cd doctor
pip intall -r requirements.txt
streamlit run doctor_notes.py
```
