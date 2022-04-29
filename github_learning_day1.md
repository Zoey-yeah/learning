# Github Mastary 
1. First make sure you have installed the github by using 
<code>git --version</code>
2. Update your github using <code> git update-git-for-windows</code>

## Terminal Usage 
- Tells you where you are in the directory <code>pwd</code>
- Make directory <code>mkdir</code>. For instance, this line creates a new directory called "Websites"
<code>mkdir websites</code>
- Then I can switch to that directory using <code>cd</code>, which stands for change diretory
- <code>ls -la</code> tells you what's in the folder 
- Using <code>control +L </code> to clear your terminal output page


## Github Basics  
- <code>.md</code> stands for markdown
- <code>git clone http://....git directory_name_optional</code> 
- Use <code>git status</code> to show any untracked files / changes
- Next, we are going to stage a file, meaning preparing it. For instance <code>git add filename</code>
- Then, we need to tell them where to go, with a little message <code>git commit -m"Message"</code>
- Lastly, we ship ths file to github master brahcn by using <code>git push origin master</code>

If we have made some changes to our file, we can use <code>git diff filename</code> to show what have changed 
