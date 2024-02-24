��#   t e s t n i 
 
... or create a new repository on the command line
echo "# testni" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/marioblazeka/testni.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/marioblazeka/testni.git
git branch -M main
git push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

repo -> repository

clone -> bring a repo down from the internet (remote repository like Github) to your local machine

add -> track your files and changes with Git

commit -> save your changes into Git

push -> push your changes to your remote repo on Github (or another website)

pull -> pull changes down from the remote repo to your local machine

status -> check to see which files are being tracked or need to be commited

init -> use this command inside of your project to turn it into a Git repository and start using Git with that codebase


🔗 Git Commands: [https://gist.github.com/gwenf/19e5748...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbXVqd19XWC0yOUhHY1VzbVFZVFk1ZTBRVy0zQXxBQ3Jtc0ttT29WVGl1djdETFhJY1dzVExmeDRIYkJYbFhVWXJBb3NMTXdSRlhGZEszdVF3bUZfLW1TcUllREdJUXlEdVpnZDY1UzRVQ1VzN19BdFVBR2ZwdklJVl85RUg5eEpEaVZvbjNFRFRhdHZxVFhBdGVsQQ&q=https%3A%2F%2Fgist.github.com%2Fgwenf%2F19e5748a5391929e8e938a22c8a4b3f2&v=RGOj5yH7evk)https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbXVqd19XWC0yOUhHY1VzbVFZVFk1ZTBRVy0zQXxBQ3Jtc0ttT29WVGl1djdETFhJY1dzVExmeDRIYkJYbFhVWXJBb3NMTXdSRlhGZEszdVF3bUZfLW1TcUllREdJUXlEdVpnZDY1UzRVQ1VzN19BdFVBR2ZwdklJVl85RUg5eEpEaVZvbjNFRFRhdHZxVFhBdGVsQQ&q=https%3A%2F%2Fgist.github.com%2Fgwenf%2F19e5748a5391929e8e938a22c8a4b3f2&v=RGOj5yH7evk
🔗 Install git: [https://www.atlassian.com/git/tutoria...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbXZFWnMwdFZ5Q2dIRVVJdWVlc3Z1Z0lmaVBDUXxBQ3Jtc0tsT1VCMEEza2Zjc2g1S0ZYTzRXanFuLU9XOUtfUUVFWXhLOHdMYUxuR0I1Nk9YNF93LWxGUHhnSXg5dXd1WUh6T3djLV95MWZfb0R6QWxGdUl3Z2tESk9jeEE0ck5TQm5SWVdRaVlraW1NRkZwN1VQTQ&q=https%3A%2F%2Fwww.atlassian.com%2Fgit%2Ftutorials%2Finstall-git&v=RGOj5yH7evk)https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbXZFWnMwdFZ5Q2dIRVVJdWVlc3Z1Z0lmaVBDUXxBQ3Jtc0tsT1VCMEEza2Zjc2g1S0ZYTzRXanFuLU9XOUtfUUVFWXhLOHdMYUxuR0I1Nk9YNF93LWxGUHhnSXg5dXd1WUh6T3djLV95MWZfb0R6QWxGdUl3Z2tESk9jeEE0ck5TQm5SWVdRaVlraW1NRkZwN1VQTQ&q=https%3A%2F%2Fwww.atlassian.com%2Fgit%2Ftutorials%2Finstall-git&v=RGOj5yH7evk
🔗 SSH Keys: [https://help.github.com/en/github/aut...](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbHhTUkFPYUNNc1F6V3BtWkRtTDRYSmVqTWUtd3xBQ3Jtc0tuV2lmazkzZVptNWlkX2tudFFhb1JBc0psLVVuWFpSUHlyS01FV3FuaU8xQ1RqQ0V5aTd3ZHExSzBqbUhvcU5Gc01tUjhxal90U0Nvckd5Vm05VWlPbVhKdEM3TTdCdVdtM3VUOHhpajlKVUxfUG8zTQ&q=https%3A%2F%2Fhelp.github.com%2Fen%2Fgithub%2Fauthenticating-to-github%2Fgenerating-a-new-ssh-key-and-adding-it-to-the-ssh-agent&v=RGOj5yH7evk)https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbHhTUkFPYUNNc1F6V3BtWkRtTDRYSmVqTWUtd3xBQ3Jtc0tuV2lmazkzZVptNWlkX2tudFFhb1JBc0psLVVuWFpSUHlyS01FV3FuaU8xQ1RqQ0V5aTd3ZHExSzBqbUhvcU5Gc01tUjhxal90U0Nvckd5Vm05VWlPbVhKdEM3TTdCdVdtM3VUOHhpajlKVUxfUG8zTQ&q=https%3A%2F%2Fhelp.github.com%2Fen%2Fgithub%2Fauthenticating-to-github%2Fgenerating-a-new-ssh-key-and-adding-it-to-the-ssh-agent&v=RGOj5yH7evk
