# Devops_Assingment
Devops Assingment Question 1

## Step 1 : Create a django web application with test cases
  1. Install python
  2. Create virtual environment<br>
  
    In terminal execute following commands <br>
      ```
       1.python -m venv venv<br>
       2.venv\Scripts\activate<br>
       ```
  4. Install django and pytest by following command<br>
  
      ``` pip install django pytest pytest-django ```
## Step 2 : Create a dockerfile

  1. Download and install docker desktop for windows <br>
  2. Run docker windows <br>
  
![d2](https://github.com/user-attachments/assets/ba68f933-441f-47ba-a3c4-e5b70e00ff9c)<br>

## Step 3 : Push you django project to github . <br>
<br>
## Step 4 : Download and install Jenkins<br>


![j1](https://github.com/user-attachments/assets/ca26342c-ffbf-4552-b465-babfe1ee8fe0)<br>

  Refer below link to know step by step procedure to install jenkins<br>
  https://dev.to/msrabon/step-by-step-guide-to-setting-up-jenkins-on-docker-with-docker-agent-based-builds-43j5<br>
  <br>
    1.Login to jenkins on web browser<br>
    2.Go to "manage jenkins" and then to "plugins" to download plugins .
    3.Git , Docker pipeline and Pipeline are the main plugins required to run this project<br>
    <br>

    ![jjre](https://github.com/user-attachments/assets/8ad4b6d9-3f1d-4986-bed8-1c59205f99ea)
![jjre2](https://github.com/user-attachments/assets/cf735df9-c775-4563-b507-d9102b2d3193)

  ## Step 5 : Create a Jenkins Pipeline Job:<br>
        1. Open Jenkins dashboard.<br>
        2.Click on "New Item".<br>
        3.Enter a name for your job and select "Pipeline".<br>
        4. Click "OK".<br>
          
          
![jjre3](https://github.com/user-attachments/assets/f22c1d03-c352-4c78-ab43-175ef6493905)<br>
<br>

![jjre4](https://github.com/user-attachments/assets/3c8848b4-a9f9-4fa7-a55c-48520d16d3f1)<br>

![jjre5](https://github.com/user-attachments/assets/e2a9cc73-defb-475d-9285-caa557be6a71)<br>
<br>
## Step 6 : Save the pipeline and click on Build now .
<br>

![jjre6](https://github.com/user-attachments/assets/97744d42-36eb-45a3-b501-2efca07556f0)

![jjre7](https://github.com/user-attachments/assets/5860d03e-decf-480a-9dad-9261891172d3)

