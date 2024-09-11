This is a test

This is my first change

Goin to try to push it to GitHub

This is yet another attempt to get this right.

One more try to get this correct.

I had to use: git push "origin url"
instead of the: git push main master
In order to get the origin url use: git remote -v

Final test!
Steps I took.

1. Create a new reposotory on GitHub

2. Copy the HTTPS (origin url)

3. Open terminal

4. Use cd to change what directory I want to save my repo in.

5. Once I'm in the folder I want to save my repo I need to clone my repo.

6.Type: git clone "HTTPS" (this is the one I copied earlier)
NOTE: I can create a folder at the same time I'm cloning this repo by using a space and the name of the new folder after the "HTTPS" EX: https://github.com/Examplerepo example_repo
This will put my repo in a folder called example_repo

7. Open repo folder in VSCode and add a README.me or any other file and save.

Let's send out updated file back to GitHub to update the repo.

8. Go into the terminal and type: git status
   This should show the changed/new file in red.

9. stage the file by typing: git add "file name"

10. type: git status
    The file should now be green and ready to ship to GitHub

11. type: git commit -m "Your message about what you did to the file here" (message is in quotations)

12. type: git push "HTTPS" (this is from the url I copied in step 2)
    NOTE! You may need to use:
    git push origin master

This way does not work for me.

Go back into your GitHub and checkout your updated repo!

EXTRA NOTES

- To check what your origin url is set at type: git remote -v
- If you have more then one file you need to add you can type: git add --all
