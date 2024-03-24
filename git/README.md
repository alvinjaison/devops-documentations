git 

we created one Repositorie (devops-documentaion repose) using github dashboard 
mkdir name of the directorie } enter -- listed some of the directories  namley aws , docker ,git , jenkins ,linux , terraform.
touch (file name) -- to create file .html 
each and every directory have file called README.md which show the path to lean content and commads 
22/03/24 we learned how to add images in html file by using vs code with git hub commads 
step 1 : download free tempalte from w3 or any free html file 
step 2 : git clone +paste ssh its helps me to create a copy of a repository from a remote source 
         NOTE : to copy ssh ~ go to repository , click on code option , click on SSH , copy .
step 3 : create the directory my website (mdkir) and created html file (touch)
step 4 : copy the html template code into html file 
step 5 : openth file in vs code by command ( code .)
step 6 : command + f pop-up the search bar in code teminal lets say ex "image" its figure out all image names in code.
step 7 : now , download a image from the google and save it (remember the locate Ex downloads , desktop ..etc)
step 8 : create one directory (mkdir) lets say image  in vs code terminala 
         NOTE : open termianl command + j )
step 9 : now move the downloaded image to image directory in vs code terminal (mv ~/Download/image.jpj/image)
         NOTE : Downlaoed ~ location , image.jpj ~ downloaed image , image ~ created directory
step 10: mv old name new name -- like to change the name 
step 11 : copy the image name as it is and replace it in code 
step 12: save  or command + s
step 13: check the status called "git status "
step 14 : check the difference between previoues and present changes made 
step 15 : now add to the local directory by using command git add html file
step 16 : git commit -m "wwrite a message wt changed you made "
step 17: open html file in the desktop and check the changes we made 
step 18: if changes are made then add this to remote directory 
          NOTE : if not check the error and change according to that 
step 19 : adding the local content to remote by using the command called git push
step 20 : refresh the local html file and remote code file in the github 
~~~~~~~~~ in the same way we can change the name of the images and in html tempalte ~~~~~~~~~

# WORKING ON PUSH AND PULL IN BRANCHES # 

main branch namely called "master " one main person(AJ) have all right to make changes in it .
Aj added two persons to the branch # mo # sarath anna 
aj allowed some permission the make changes in the code for two persons 

now , aj boss allot work to # mo >> to replace the image at perticual area and send push request to Aj 
                           # sarath >> to rename and send push request to AJ

      # mo 
          
           made the changes by following the above steps 
           now , push the request "git push"
           we can see this line from the push action doen" git push --set-upstream origin thanveer"
           copy the this line 
           paste in the terminal and enter 
           check the status --- git status
           give commit ----- git commit -m "alloted work update"
           now , request display to boss Aj
                aj checked all the content right and given approved 
            last , # sarath anna , done his job so fetch that work to my local "git pull origin master"
                            
                job done .....

mv ~/(download location)/image.jpj (location where need to move) -- used to move the D image to created directory.
EX :  mv ~/Downloads/ntr.jpeg images/

ls ./images/ -- to check the path of image 
git status -- to check the status display the current state of the repository 
git add any file name --  to add changes from the working directory 
git diff -- to show the differences between various states of your repository 
   NOTE : if you find any red colour error init make sure to added to git my using the commade git add file name .

  git commit -m "message" -- to create a new commit with a commit message
  git push -- to upload local repository content to a remote repository
  git push -u origin master -- to push the local branch changes in the MASTER branch to the remote repository 
  git branch -- to list branches in a repository
  git checkout -b (name of the branch need to create) -- to create a new branch name
      NOTE : dont use capital letters
  git pull -- to fetch and download content from a remote repository and immediately update the local repository to match that content
  git push --set-upstream origin thanveer  -- to push the current branch to a remote repository named "origin"     


  