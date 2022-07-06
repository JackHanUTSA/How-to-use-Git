## How to use git hub

05/07/2022 12:15

![Frances Benjamin Johnston](https://www.moma.org/media/W1siZiIsIjQzNjAxMCJdLFsicCIsImNvbnZlcnQiLCItcXVhbGl0eSA5MCAtcmVzaXplIDIwMDB4MjAwMFx1MDAzZSJdXQ.jpg?sha=bbb4cd7c2dc53f22)

When you start to write code, or simply to do anything, the smart move is always check if there is some good tools you could use. **Git** is one of these tools for coding.
> It’s an intricate platform that fosters collaboration and communication between developers.

> With GitHub, you can collaborate and work on projects with others anywhere in the world.


### Install Git

		sudo apt install git
		


![Screenshot from 2022-07-02 17-51-55.png](/home/jack/Documents/GitHub/How-to-use-Git/Screenshot from 2022-07-02 17-51-55.png)


	
### Create a Repository 

![](https://devmountain.com/wp-content/uploads/2022/04/CSmSKCsEKcv6B9O255b0nWyWj0TqkPQa_ugP3mPMZ2_oEu99wTHSgrXptB2a73KxEHs83PrU9oH2tO9bbro1h1E4pdTO38tUM81WJ8OuWbCcLRgodBhT-bPGZtNKufNMwxNbPDIx-1.jpeg)

A repository is a location contain or will contain everything you needed to build your own project. Such as pictures, code files, data sheets and so on. As a professional coder, you should add **README** file to demonstrate what is your project about and how to use it. The **repo** can be created on **git** website or on **git** desktop or from command line. Once you master one you will quickly understand others, for me I like command line better just simple and less distruction.

### Create a Branch

![](https://i2.wp.com/digitalvarys.com/wp-content/uploads/2019/06/image-7.png?fit=640%2C311&ssl=1)

Just think about you working on a robot program, which you planing to let the robot use camera to move around the house, while the first step you create a code to run the robot only with remote command from mouse. And then you want to add the camera navigation to the robot system. Now you need a branch that just copy the orgional file called(_master_), once your development passed the test then you can `merge` to the master. Then your master project have the new feature(camera navigation). 

### Create and Commit Changes to a Branch

![](https://devmountain.com/wp-content/uploads/2022/04/MoitkFdNz_mJZWVJZe_yiN6xsauXjyE9YfMPpzSvg_Knc6wmvODq_isgulDIVVuUlgn4EckCuCC18a5x7AQNS12mTqOKgyKnpjT9SVLuF4zdXJlz7DwZthY969LbgHfM5uX76ZTV-1.jpeg)
Each branch in GitHub can be tracked in details. Once you made a change on a file in your branch you will be asked to  make a commit to explain why you made the change. The commits is very important for project managers to understand your work and help other contributors to track the project process.

### Git commands in the Terminal

Typing `git status` in the terminal will give information about the working directories in the computer.

		git status

![Screenshot from 2022-07-02 17-51-5](/home/mingye/Documents/GitHub/How-to-use-Git/Terminal git status.png)



`git add 


		git commit -m "message"


		git push
### Open a Pull Request

Once your branch is done, you may think to merge your branch to other's branch. In order to do that you need to open a pull request. The GitHub will based on your request to notify the relevant parties that you want to incorporate changes to their branch. If you need to mention someone in the request you can use `@` feature.


### Merge Your Pull Request

![](https://wac-cdn.atlassian.com/dam/jcr:83323200-3c57-4c29-9b7e-e67e98745427/Branch-1.png?cdnVersion=jt)
When you find someone want to merge to your master branch, you can chose the `merge pull request` then select `confirm merge`. Then you can **delete** the branch you have merged to the **master**.

![](https://raw.githubusercontent.com/durgaswaroop/blogimages/master/git_post_octopus_merge.png)




### Desktop VS Command Line

![](https://ictsolved.github.io/assets/images/blog/2019-03-03-git-merge-tutorial/git-merge-tutorial.png)



#### Reference

[What is git](https://devmountain.com/blog/what-is-github-and-how-do-you-use-it/)

[Install Git Desktop](https://github.com/shiftkey/desktop/releases)


___

## How to Use GitHub Desktop 

GitHub Desktop is an extension to GitHub, [BLANK]

![](https://carldesouza.com/wp-content/uploads/2020/03/img_5e72a64e32003.png)


### Install 

### Cloning Repositories 

After installing GitHub for the first time, you can choose to clone or edit your repository. In order to clone a repository, click the dropdown menu, and select `add`. From there, choose an existing repositroy from your GitHub and open it through VS Code. 

![](https://user-images.githubusercontent.com/50087820/57088503-4b522380-6cb7-11e9-931d-c36aba32aa44.png)
_Click [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/troubleshooting-cloning-errors) if you are having cloning erros._ 



### Pushing Changes to GitHub through Desktop 

When making changes to your website, through VS Code, make sure to constantly update your [commits](https://docs.github.com/en/pull-requests/committing-changes-to-your-project/creating-and-editing-commits/about-commits) to the origin remote. This ensures that the changes you are making are constantly being renewed to the mainframe. 
