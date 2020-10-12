# Google Drive Copy/Rename script
A python script that can copy and files/folders from Team Drives to your own drive

    
<a href="https://colab.research.google.com/github/RaymondSalim/google-drive-scripts/blob/master/Google_Drive_Scripts.ipynb\" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>



## Usage
1. Click on the badge above

2. File -> Save a copy in Drive

If you have a Google Cloud project running and Google Drive API enabled, go to step 5

3. Create your own google cloud project if you don't have one by clicking the link below
    https://console.developers.google.com/apis/library/drive.googleapis.com?q=drive
    
4. Click on Create Credentials and follow the settings below
  - <img src="https://raw.githubusercontent.com/RaymondSalim/google-drive-downloader/master/src/1.png"/>

  - You will have to setup OAuth Consent Screen
   
       > User Type > External
       >
       > It is recommended to only fill in the "Application name" and Save
       
5. Download the client_id.json file from Credentials page of your google cloud project and upload it to your Google Drive
   Set the file sharing to public and get the file ID
     
     <img src="https://raw.githubusercontent.com/RaymondSalim/google-drive-downloader/master/src/3.png" />
     
    ALTERNATIVELY, you can upload the client_id.json manually to google colab. Make sure to upload it to '/content'
     
6. Follow the steps on the google colab page


Feel free to open an <a href="https://github.com/RaymondSalim/google-drive-downloader/issues">issue</a>
