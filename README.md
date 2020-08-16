# First Timers

Let's make our first open-source contribution!

Excited? Let's Begin!

### Step 1

Go to this [GitHub repository](https://github.com/jatin2003/first-timers/) and fork this repository to your account.

Click on the fork button on the top right corner of the repository page to do it. Once done, GitHub will take you to the forked copy in your account.

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597592899333/FEGPJtlrF.png)

### Step 2

Clone the forked repository to your local machine. Click on the big green button saying "Clone or download" and copy the https url of your repository.


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597593013858/DouI5mF3s.png)

If you're on Windows, fire up [Git Bash](https://git-scm.com/download/win) navigate to your project directory and type the following command. 

Replace the link with the clone URL of your repository and hit Enter.

```bash
git clone https://github.com/your_username/first-timers.git
```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597593191013/rTNmZCM-D.png)

### Step 3

Let's start working on the changes required now! First `cd` into the cloned folder by typing the following command.

`cd first-timers`


![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597593269448/Y8dvitXrE.png)

### Step 4

In your file manager/terminal navigate to the cloned repo. Open the `Contributors.md` and add a new line to the end of the file.

It should like this 👇

```
- #### [Your Name](https://github.com/your_username)
```

### Step 5

Commit the changes with a suitable commit message. First, we need to stage all the changes we made. Open the terminal inside the project directory and execute the following commands.

```bash
git add .
```

The above command stages all the changes, now let's commit it with a suitable message.

```bash
git commit -m "Your_Commit_Message"
```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597593427646/eFhOm0C-v.png)

### Step 6

Let's push the changes to your repository! Execute the following command to push all the changes to the forked copy in your GitHub account.

```bash
git push -u origin
```

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597593539041/k-xc4Omfj.png)

### Step 7

Now, open your forked repository on GitHub. If your changes have been pushed to your forked copy, You'll be able to see an option saying "Pull Request" in your repository. 

![image.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1597595291777/mWzydMF1y.png)

Then click on create pull request. Once you fill in the commit message and comment. Click on submit pull request.

Now, Wait for a reviewer to review your file and merge it to the master. Once it been successfully merged, your account will appear on the contributor's list.

And Tada 🎉! You just made a contribution to Open Source.
