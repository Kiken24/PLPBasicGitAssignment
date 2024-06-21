TASK 1: REPOSITORY SETUP
1. Creation of GitHub Repository:
- Logging in to my GitHub account.
- Create a new repository on GitHub (let's call it "PLPBasicGitAssignment").
![alt text](image.png)
- Initialize it with a README file:
 ![alt text](image-1.png)
 ![alt text](image-2.png)

TASK 2: LOCAL SETUP
2. Local Folder Setup:
- Creating a local folder on my local machine:
 ![alt text](image-3.png)
 ![alt text](image-4.png)
- I have named it "PLPBasicGitAssignment" as demonstrated below:
 ![alt text](image-5.png)
- Opening a terminal or command prompt and navigate to the created folder:
 ![alt text](image-6.png)
3. Git Initialization:
- Initialize a new Git repository in your local folder:
 ![alt text](image-7.png)
4. Connecting to GitHub:
- Copy the URL from GitHub repository as demonstrated below:
 ![alt text](image-8.png)
- Linking my local repository to the GitHub repository I created in Task 1 by typing on the Gitbash terminal the following command: 
git remote add origin https://github.com/Kiken24/PLPBasicGitAssignment.git
![alt text](image-9.png)
TASK 3: MAKING CHANGES
5. Create a File:
- Inside your local folder, create a new text file (e.g., `hello.txt`).
•	I created a new text file in my local folder through Gitbash terminal by typing the command: vi hello.txt
 ![alt text](image-10.png)
•	This prompted opening of vim where I added a simple text message.
- Add a simple text message (e.g., "Hello, Git!"):
•	After vim was opened I pressed I on my keyboard to allow me to insert text on the file for which I typed “Hello,Git!”
•	To close vim I pressed the following keyboard keys in succession escape, shift+colon, w, q then enter.
 ![alt text](image-11.png)
 ![alt text](image-12.png)
 ![alt text](image-13.png)
 ![alt text](image-14.png)
 ![alt text](image-15.png)
 
6. Committing Changes:
 - Stage the changes:
•	git add hello.txt
 ![alt text](image-16.png)
 - Commit the changes:
•	git commit -m "Add hello.txt with a greeting"
 ![alt text](image-17.png)
TASK 4: PUSHING TO GITHUB
7. Pushing to GitHub:
- Push the committed changes to your GitHub repository:
•	git push -u origin master
 ![alt text](image-18.png)
TASK 5: VERIFICATION
8. Verify on GitHub:
- Visit your GitHub repository in a web browser and confirm that the `hello.txt` file and commit message are visible.
 ![alt text](image-19.png)


