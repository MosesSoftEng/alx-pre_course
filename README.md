![Meme Git Compilation](https://miro.medium.com/max/640/0*VcMPr1unIjAIHw2j.webp)

# :book: 0x01. Git
## Topics Covered.
1. Version control using Git and github.
2. Shell commands.

## :computer: Technologies.
Github, Shell

## :office: Environment, Tools and IDEs.
Ubuntu 20.04, Visual Studio Code, Github.

## :wrench: Project setup.
```bash
# Create project directory.
mkdir 0x01-git

# Create readme file.
touch 0x01-git/README.md

# Switc to create directory.
cd 0x01-git
```

# :computer: Tasks.
## [0. Create and setup your Git and GitHub account](README.md)
### :page_with_curl: Task requirements.
#### Step 0 - Create an account on GitHub [if you do not have one already]

You will need a GitHub account for all your projects at ALX. If you do not already have a github.com account, you can create an account for free here
#### Step 1 - Create a Personal Access Token on Github

To have access to your repositories and authenticate yourself, you need to create a Personal Access Token on Github.

You can follow this tutorial to create a token.

Once it’s created, you should have a token that looks like this:
![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/a449483cd76a72cef1b42df831e686c64faa1cf6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230123%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230123T075850Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=2e00581552889a9c14cf61437f3fc03e51cdfb17a8339800cb78006bb3cd08f8)

#### Step 2 - Update your profile on the Intranet

Update your Intranet profile by adding your Github username here

If it’s not done the Checker won’t be able to correct your work
![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/6270480a0a982cd1846b877eda2ee405d2e8f575.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230123%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230123T075850Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=1949cd0b40706a80d7a41f5c70f3becc590d721a3e08ee6293c91666c9cf11d1)

#### Step 3 - Create your first repository

Using the graphic interface on the github website, create your first repository.

    *   Name: alx-pre_course
    *   Description: I'm now a ALX Student, this is my first repository as a full-stack engineer
    *   Public repo
    *   No README, .gitignore, or license

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2022/2/2340a2d0f7c74b5dd6f8fc2aa58f94d13ea2c775.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230123%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230123T075850Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=6e013bba181727dbed313984d5acf8687ec82fb3b7c1af806462ac52b16df68d)
#### Step 4 - Open the sandbox

On the intranet, just under the task, click on the button and run to start the machine.

Once the container is started, click on to open a shell where you can start work from.
#### Step 5 - Clone your repository

On the webterm of the sandbox, do the following:

    *   Clone your repository
```
root@896cf839cf9a:/# git clone https://{YOUR_PERSONAL_TOKEN}@github.com/{YOUR_USERNAME}/alx-pre_course.git                  
Cloning into 'alx-pre_course'...
warning: You appear to have cloned an empty repository.       
```

Replace {YOUR_PERSONAL_TOKEN} with your token from step 1

Replace {YOUR_USERNAME} with your username from step 0 and 1

Pro-Tip: On windows, use CTRL + A + V to paste in the web terminal
#### Step 6 - Create the README.md and push the modifications

    *   Navigate to this new directory. Tips
```
root@896cf839cf9a:/# cd alx-pre_course/
root@896cf839cf9a:/alx-pre_course#
```
    *   Create the file README.md with the content My first readme. Tips

```
root@896cf839cf9a:/alx-pre_course# echo 'My first readme' > README.md                                                                 
root@896cf839cf9a:/alx-pre_course# cat README.md                                                                                      
My first readme                                                                                                                       
```
    *   Update your git identity
```
root@896cf839cf9a:/alx-pre_course# git config --global user.email "you@example.com"
root@896cf839cf9a:/alx-pre_course# git config --global user.name "Your Name"
```
    *     Add this new file to git, commit the change with this message “My first commit” and push to the remote server / origin
    
```
root@896cf839cf9a:/alx-pre_course# git add .
root@896cf839cf9a:/alx-pre_course# git commit -m 'My first commit'
[master (root-commit) 98eef93] My first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
root@896cf839cf9a:/alx-pre_course# git push                                                                                           
Enumerating objects: 3, done.                                                                                                         
Counting objects: 100% (3/3), done.                                                                                                   
Writing objects: 100% (3/3), 212 bytes | 212.00 KiB/s, done.                                                                          
Total 3 (delta 0), reused 0 (delta 0)                                                                                                 
To https://github.com/{YOUR_USERNAME}/alx-pre_course.git                                                                                       
 * [new branch]      master -> master              
```
Good job!

You pushed your first file in your first repository of the first task of your first ALX School project.

You can now check your repository on GitHub to see if everything is good.

### :wrench: Task setup.

### :heavy_check_mark: Solution.
> [:point_right: README.md](README.md)


## []()
### :wrench: Task setup.

### :heavy_check_mark: Solution.
> [:point_right: <NAME>](<FILE)

# :books: References.
1. [Set up Git](https://docs.github.com/en/get-started/quickstart/set-up-git)
1. [Learn Git Branching](https://learngitbranching.js.org/)

# :sunglasses: Author and Credits.
This project was done by [SE. Moses Mwangi](https://github.com/MosesSoftEng). Feel free to get intouch with me;

:iphone: WhatsApp [+254115227963](https://wa.me/254115227963)

:email: Email [moses.soft.eng@gmail.com](mailto:moses.soft.eng@gmail.com)

:clap: A lot of thanks to [ALX-Africa Software Engineering](https://www.alxafrica.com/) program for the project requirements.