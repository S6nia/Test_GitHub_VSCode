# Test_GitHub_VSCode
Testing: Cloning from GitHub using VS Code.

It worked. I was able to clone a repository from GitHub to my local machine, and push the changes to the remote repository. All this using VS Code.
(And also listening to Rachael Yamagata :) )

I almost forgot, I had an issue at first!
I got this error: error setting certificate verify locations CApath: none

![image](https://user-images.githubusercontent.com/73625373/125506396-7ff55b09-e68b-4877-9bc0-c366ac50fc66.png)

Then I looked for a solution...
I tried this: git config --global http.sslverify "false"

![image](https://user-images.githubusercontent.com/73625373/125506867-6e4467a8-bdcf-424f-8f79-6f1b29ce01e6.png)
Given by https://www.programmersought.com/article/10383789790/

And it worked! Thank you programmersought.com! :)
