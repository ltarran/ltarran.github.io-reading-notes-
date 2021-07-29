What is Git?

 Github is not git.

Git is a type of version control system (VCS) that makes it easier to track changes to files. For example, when you edit a file, git can help you determine exactly what changed, who changed it, and why.

Common commands

Start your own repository from scratch (in any existing folder on your computer):

Git init

This will create a hidden .git folder inside your current folder — this is the "repository" (or repo) where git stores all of its internal tracking data. Any changes you make to any files within the original folder will now be possible to track.

Clone an existing repo:

git clone https://github.com/cooperka/emoji-commit-messages.git

This will download a .git repository from the internet (GitHub) to your computer and extract the latest snapshot of the repo (all the files) to your working directory. By default it will all be saved in a folder with the same name as the repo.
