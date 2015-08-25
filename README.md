Sample Assignment - (Simple Workflow)
=================

This Sample Assignment will go through the workflow of Processing and GitHub that you will use for your subsequent assignments. 

1. Sign up for a free GitHub account if you don’t already have one and sign in to your GitHub account

3. Fork the SampleAssignmentSimple here at https://GitHub.com/APCSLowell/SampleAssignmentSimple. Forking is making a copy of the of the *repo* (that's short for repository). It's like copying a google doc. Click on the *Fork* button at the top right corner.  
![Image 1](/images/SampleAssignmentSimple1.PNG)

4. Click on SampleAssignmentSimple.pde file
![Image 2](/images/SampleAssignmentSimple2.png)

5. Start Git Bash. Git Bash gives you the ability to use Unix commands on Windows PC. Go to the Windows Start Menu and double click Git Bash. It will be listed under All Programs.

6. Open the apjava folder. Your apjava folder should be located at  
`C:\Users\ < Your User Name > \Documents\apjava`  

6. The following five commands should navigate to your apjava folder:  
`cd c:`  
`cd users`  
`cd < Your User Name >`  
`cd documents`  
`cd apjava`  

7. If you don't have an apjava folder at that location, one way to create one is to navigate to the Documents folder and type the command `mkdir apjava`

8. Clone the Forked SampleAssignment. Cloning is like downloading a file from google docs. We need the program Git Bash to do the cloning. Make sure that your are in your apjava folder with the Unix command `pwd`. Then type `git clone`. Then press the *insert* key to paste in the URL you copied in Step 4. Your Git Bash window should look similar to this one.  
![Image 3](/images/SampleAssignment3.png)

9. Open the program Sublime. Sublime is an editor. It's like a word processor for code. We will use Sublime to personalize our web page. Go to the Start Menu and choose *All Programs | Sublime Text 3*.

10. Open the *SampleAssignment* folder in Sublime. Make sure to choose *File | Open Folder*. Click on *SampleAssignment* and choose *Select Folder*.  
![Image 4](/images/SampleAssignment4.png)

10. Click on the arrow next to *SampleAssignment* to reveal all the documents in the folder  
![Image 5](/images/SampleAssignment5.png)

11. Then click on *index.html* to reveal the code  
![Image 6](/images/SampleAssignment6.png)

11. Change *index.html* to use your first name. *index.html* is the webpage that loads your program. To protect your privacy, you should not use your full and complete name on any webpage you create for a school assignment. Change the text on line 4, 11 and 18 to personalize the text with your first name. Then choose *File | Save*  
![Image 7](/images/SampleAssignment7.png)

12. Go back to the Git Bash program and navigate to the *SampleAssignment* folder. Check your current location by typing `pwd`, (your *present working directory*). Navigate to the *apjava folder* and then type `ls` to list the files and folders. You should see a screen similar to this:  
![Image 8](/images/SampleAssignment8.png)

13. `add` all 4 files to be "staged." To add all 4 files you can type either `git add .`, `git add -A` or `git add –-all`. Check the results of your add by typing `git status`. Your screen should look similar to this:  
![Image 9](/images/SampleAssignment9.png)

14. Configure your username and password. git needs to be configured to your user email and user name. You configure your user name with the code git `config user.name < your user name >`. For example, if your user name was `MaxwellG` you would type `git config user.name MaxwellG`. You configure your email with the similar code `git config user.email < your email address >`. You can check to see that you've correctly configured your username and password by typing  `git config user.name` and  `git config user.email`. Your screen should look similar to this:  
![Image 10](/images/SampleAssignment10.png)

15. `commit` the 4 files. When we `commit` we are packaging up the 4 files they we want to share on our GitHub website. You can imagine `commit` as placing the 4 files in an envelope with a coversheet that explains the contents. First we can check to see if our files are ready to commit by typing `git status`.  
![Image 11](/images/SampleAssignment11.png)

15. Type `git commit -m "Added first name to index.html"`.  Press *enter*.  
![Image 12](/images/SampleAssignment12.png)


16. `push` the modified SampleAssignment to the remote repository on your GitHub account. We `push` the modified files to our remote GitHub site by typing the code `git push origin gh-pages`. You'll be prompted for your username and password. After you enter them, you should see a screen like this one.  
![Image 13](/images/SampleAssignment13.png)

17. The hard work is done! Now you can see your program on the web. First, be patient. It may take 15 minutes or so before your first web page is ready. Then, open up a browser like Google chrome and enter  
`<your github username>.github.io/SampleAssignment/`  
as the URL. You should see a webpage like this one.  
![Image 14](/images/SampleAssignment14.PNG)

18. OPTIONAL: If you have extra time, feel free to change the code in the *SampleAssignment.pde* file to make a different design.

18. Submit the URL of your finished assignment to the dropbox in school loop
