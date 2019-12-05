# Github-commands-to-upload-project
1.Create a new repository on GitHub.
2.Change the current working directory to your local project.
3.Initialize the local directory as a Git repository.
>> git init

4.Add the files in your new local repository. This stages them for the first commit.
>> git add .

5. Before Commit your repo connect it to github by the following commands
 >>  git config --global user.email "you@example.com"
 >>  git config --global user.name "Your Name"

6.Commit the files that you’ve staged in your local repository.
>> git commit -m "initial commit"

7.Copy the https url of your newly created repo
   In the Command prompt, add the URL for the remote repository where your local repository will be pushed.
   >>git remote add origin remote repository URL
>> git remote add origin https://github.com/Pratibharana96/ReactJS-Install-run-react-component-and-types-tachyons-array-maps-filter-props-states-.git

>> git push -u origin master

8. After this commands it will ask for github Username and Password.
  >>git remote -v
  Push the changes in your local repository to GitHub.

  >>git push -f origin master
