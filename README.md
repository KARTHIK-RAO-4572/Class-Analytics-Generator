<div align="center">
  <a href="#"><picture>
    <img alt="Class Analytics Generator" src="https://github.com/KARTHIK-RAO-4572/GitHub-Images/blob/main/Class_Analytics_Generator_GitHub_Logo.png?raw=true">
  </picture></a>

![](https://i.ibb.co/sJ7RhGG/image-41.png)

</div>

# Background
Students engagement, commonly referred as "`Class Analytics`" is important to measure, as it indicates effectiveness of the teacher delivering the class. The existing research works suggests to view classroom student engagment in three dimensions: `Affective engagement` (face emotion based), `Cognitive engagement` (cognitive ability based) and `Behavioural engagement` (non verbal cues based). Existing systems like self-reporting (form filling by student), manual observation by professionals, etcetera are not reliable. 


# What did we do?
We have developed an AI-powered web application to measure the affective engagement of students of classroom in real-time. The web application was developed using Django framwork, with python as backend language. We have prepared a custom dataset with faces of 12 subjects and fine tuned, a pre-trained deep learning model. The model showed a accuracy of `95%` when tested. With integration, we were able to measure affective engagement and present statistics to the teacher in real-time 

# What happends when project is running?
After the teacher has log in and starts tracking
- **Live video feed** is captured from camera for every 5 seconds
- In captured frame, student faces are identified
- The extracted faces are preprocessed and fed to the **Deep Learning model** to classify into one among the four categories: `Bored`, `Confused`, `Focused` and `Sleepy` 
- The Focused and Confused category faces are considered as **"Engaged"**
- The Bored and Sleepy category faces are considered as **"Not Engaged"**
- Real-time stats are presented as graphs to the teacher
- Analytics are stored as excel file and made available to admin to measure teacher's performance 

# How to run the project ?
To run the project in your local system, follow the below steps\
\
**1. Clone repository -** to clone the repository, execute the following command in your local system
```bash
git clone https://github.com/KARTHIK-RAO-4572/Class-Analytics-Generator.git
```
\
**2. Install dependencies -** Navigate to the cloned folder and install dependencies required by executing the following command
```bash
pip install -r requirements.txt
```
\
**3. Run the project -** Now, execute the following command and visit [http://localhost:8000](http://localhost:8000)
```bash
python manage.py runserver
```
<div align="center">
  <h3>We wish you have good time using our web application!!</h3>
<h3 ><u>Development Team</u></h3>
<h4 >Karthik Rao P - karthikraopadala@gmail.com</h4>
<h4 >Vishwas Reddy T - tekulavishwasreddy@gmail.com</h4>
<h4 >Sahithi Reddy P - sahithireddypasham29@gmail.com</h4>
</div>