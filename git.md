# <center><b>What is Git?</b></center>

 Github is *not* git.

Git is a type of version control system (VCS) that makes it easier to track changes to files. For example, when you edit a file, git can help you determine exactly what changed, who changed it, and why.

### <b>States</b>

Files in Git can reside in three main states: committed, modified and staged.

<b>Committed</b>

Data is securely stored in a local database

<b>Modified</b>

File has been changed but not committed to the database


## <b>Common commands</b>



Start your own repository from scratch (in any existing folder on your computer):

    Git init

This will create a hidden .git folder inside your current folder — this is the "repository" (or repo) where git stores all of its internal tracking data. Any changes you make to any files within the original folder will now be possible to track.

###  <b>Clone an existing repo:</b>

    git clone https://github.com/ltarran/emoji-commit-messages.git
    
After using these commands, files are tracked and staged for committing.
This will download a .git repository from the internet (GitHub) to your computer and extract the latest snapshot of the repo (all the files) to your working directory. By default it will all be saved in a folder with the same name as the repo.

###  <b>Check File Status</b>

     $ git status
    
This will print some basic information, such as which files have recently been modified. You should check your status anytime you’re confused. Git will print additional information depending on what’s currently going on in order to help you out.

### <b>Single File</b>

     git add filename
     
After editing some files, this command will mark any changes you’ve made as “staged” (or “ready to be committed”).

### <b>All Files</b>

     $ git add *
    
After using these commands, files are tracked and staged for committing.

#

1. [Home](https://ltarran.github.io/reading-notes)  

2. [Growth Mindset](https://ltarran.github.io/reading-notes/growthmindset)

3. [Learning Markdown](https://ltarran.github.io/reading-notes/learningmarkdowns)

4. [Coders Computer](https://ltarran.github.io/reading-notes/git)

5. [Wire Framing](ltarran.github.io/reading-notes/wireframing)

6. [HTML](ltarran.github.io/reading-notes/html)

