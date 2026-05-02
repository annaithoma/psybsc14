# Reinforcement learning exercise for PsyBSc14 Seminar (Group 2)
Please follow the installation guide below to get access to all necessary scripts. Colab is an online coding environment that is enhanced by AI (Google Gemini). This allows us to run and try out programming scripts without prior programming expertise. 

## Installation guide: Google Colab and GitHub Repository
If you do not have a Google account, you will need to create one (this can be deleted after the workshop).
1. Navigate to Google Drive (https://drive.google.com/) and sign in. In the top-left corner, click New > More > Google Colaboratory. If you do not see Colaboratory, you have to click "Connect more apps", search for 'Colaboratory', and install it. Then try again (click New > More > Colaboratory).  
2. You have now successfully opened a programming notebook. Next, we will mount Google Drive as a file storage to your new Colab programming environment. Copy the following code snippet into the first cell of the notebook as displayed in the screenshot below:  
   `from google.colab import drive`  
    `drive.mount("/content/drive")`  
   <img width="935" height="443" alt="Screenshot 2026-05-02 at 18 19 54" src="https://github.com/user-attachments/assets/3ae802d0-61e4-42d2-8ecc-541f6739d2a8" />
   
3. Run this code by pressing "shift enter " or clicking the play (►) button to mount your Google Drive to the Colab environment. A pop-up will ask you to connect; click through the steps to connect your Google Drive to Colab.
4. You will need to allow Google access to everything in your Google Drive for this to work, unfortunately. If you do not feel comfortable doing this with your existing account, you can consider creating a new Google account just for the purpose of this seminar and delete it afterwards.
5. Create a second cell in your notebook using the "+ Code" button that appears when you hover your cursor right under the first cell. Copy and run the following code snippet in the second cell of your notebook to copy this GitHub repository to your Google Drive (you can also fork the repository instead if you prefer):  
`%cd /content/drive/MyDrive`  
`!git clone https://github.com/annaithoma/psybsc14.git`

6. Go back to your Google Drive and navigate to the folder "psybsc14" (the one you just created, not the public one for the entire seminar). You should see the relevant notebooks (`.ipynb` files, which are Python notebooks that contain all necessary code) and data (it may take a couple of minutes for the files to appear). You are now ready to work through the exercises in the course!
