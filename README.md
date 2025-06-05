# Github-webhook-with-jenkins - adding

# Pre-requisites:
    Github Repo
    Jenkins setup
    Install Git
    Install Maven
# Add Jenkins URL in git hub as webhook
  Goto github --> settings --> webhook --> Add webhook
  Provide Jenkins url as shown in below image
  
  ![image](https://user-images.githubusercontent.com/58024415/103783684-0c18d000-505f-11eb-8896-1a3036c2ac04.png)
  
  Click on Add Webook
  
  ![image](https://user-images.githubusercontent.com/58024415/103783724-18049200-505f-11eb-994a-854e6259d646.png)
  
# Create Jenkins job with Jenkinsfile content and click on GitHub hook trigger for GITScm polling as shown below
  ![image](https://user-images.githubusercontent.com/58024415/103785745-96623380-5061-11eb-8151-8fcde6439553.png)
  
  Click on Build

  ![image](https://user-images.githubusercontent.com/58024415/103784987-a75e7500-5060-11eb-8b77-bc7f703cde10.png)
  
# Change code in Github repo
  Build will happen automatically as show in below image
  
  ![image](https://user-images.githubusercontent.com/58024415/103785555-58fda600-5061-11eb-9fc9-4f600eceabc2.png)
