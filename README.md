# Hosting a Resume on GitHub Pages

## Purpose

A step by step by tutorial to host a resume on the [GitHub](https://github.com/) page. This tutorial will follow the principles has been discussed in [Andrew Etter's Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS) book. [Jekyll](https://jekyllrb.com/) static website generator and [Markdown](https://en.wikipedia.org/wiki/Markdown) will be used for the process.

[Sample static website for resume](https://alfahiyansiyam.github.io/)!
![](/images/resume.gif)

## Prerequisites
  1. A resume formatted in MarkDown (A Markup language)
  2. GitHub account ( [Login](https://github.com/login) / [Signup](https://github.com/signup) from here!)
  3. [GitHub desktop application](https://desktop.github.com/)
  4. Installing [Jekyll](https://jekyllrb.com/)
  5. Markdown Editor (Ex. [Visual Studio Code](https://code.visualstudio.com/download))

## Instructions
- In the book *Andrew Etter's* suggest using a **Distributed Version Control** to track the workflow, make it accessible to others and let others contribute. To follow *Andrew Etter's* **Distributed Version Control** principle we will use GitHub. We can create repository to work on individual projects. It will also allow us to work on our local machine staying offline, we can send our committed work to the main repository anytime we want. While working in a group we can wait for others to revise the current committed work before we merge the work with the repository. Over a period of time, if we realize we have done something terrible and we need some or all of the content from any older version we can also retrieve that work. 


### Step 1: Create GitHub Pages repository
  > Step 1.1: To create a repository to [click here](https://github.com/new)
  
  > Step 1.2: Name your repository as username.github.io (replace username with you GitHub username)
  > ![](/images/Step-1/1.2.png)
  
  > Step 1.3: Set the privacy to Public 
  > 
  > ![](/images/Step-1/1.3.png)
       
  > Step 1.4: Find **Initialize this repository with:** and select **Add a README file**
  > ![](/images/Step-1/1.4.png)
       
  > Step 1.5: From the bottom page click on **Create repository** to create your GitHub repository 
  > ![](/images/Step-1/1.5.png)
     
 
### Step 2: Setting up a copy of GitHub repository on personal computer
  > Step 2.1:  [Download link for GitHub desktop application](https://desktop.github.com/).
  
  > Step 2.2: [Click here](https://www.youtube.com/watch?v=8yqQeTbFZUg) to learn how we clone GitHub repository on personal computer
  

### Step 3: Installing Jekyll on Personal Computer 
- Jekyll is one of the tools that allow us to create a static generator site more efficiently and effectively. *Andrew Etter's* suggests using a static generator whenever it is possible. According to *Andrew Etter's*   a static generator site like Jekyll, **"have no server-side dependencies, no databases"**. Due to that, it can be hosted pretty much everywhere and can be used as a portable website. Moreover, it is much faster than dynamic websites and it provides better data safety.

  > Step 3.1: [Click here](https://www.youtube.com/watch?v=_mUmZg5qg9E) to learn how to install Jekyll
  
### Step 4: Creating Jekyll project 
  > Step 4.1: Go to the directory of GitHub repository has been created
  > ![](/images/Step-4/4.1.png)
  
  > Step 4.2: Click on the directory path
  > ![](/images/Step-4/4.2.png)
  
  > Step 4.3: Write **"cmd"** and press **Enter** to open the **Command Prompt**
  > ![](/images/Step-4/4.3.png) 
  
  > Step 4.4: Write **"jekyll new . --force"** in the **Command Prompt** to install Jekyll   
  > ![](/images/Step-4/4.5.png) 
  

### Step 5: Using Visual Studio Code to edit MarkDown

> Step 5.1: Continue from the Step 4.1 or open the **Command Prompt** from the file directory again

> Step 5.2: To open the Visual Studio Code,  Write **"code ."** and press enter
> ![](/images/Step-5/5.1.png) 


> Step 5.3: Select the desired MarkDown file to edit 
> ![](/images/Step-5/5.2.png) 


> ![](/images/Step-5/5.3.png) 




### Step 6: Adding resume in the local GitHub repository
-During this part of the tutorial, we will be using MarkDown to edit our resume. MarkDown is a markup language that can be used for editing plain text with a majority of the formatting option. For example, headings, tables, bullets, and sorted and unsorted lists. According to *Andrew Etter's* MarkDown is one of the most used lightweight markup languages. Due to having simple syntax, it is easier to understand and work with MarkDown. MarkDown offers the cleanest syntax as it has no clutter compared to regularly used markup language like HTML.

> Step 6.1: Open the repository from the file exploer

> Step 6.2: Open the resume styled with MarkDown

> Step 6.3: Copy and past the content to the **"index.md"** or **"index.markdown"**



### Step 7: Updating the static generator site on GitHub

>Step 7.1: After making any changes open the GitHub desktop from your computer.

> Step 7.2: Provide all necessary information about the update and click **"Commit to main"**

> ![](/images/Step-7/7.1.PNG) 

> Step 7.3: Now by clicking **"Push origin"** we can update the GitHub repository
> ![](/images/Step-7/7.2.png) 

 




## More Resources

### Run the static generator site on personal computer
> Step 1: Open the **Command Prompt** from repository file directory

> Step 2: Write **"bundle exec jekyll serve"** and press Enter

> Step 3: On your browser, open **"http://localhost:4000/"** or **"http://127.0.0.1:4000"** to view the static generator site

### [Click here](https://www.markdowntutorial.com/lesson/1/) to learn how to write in MarkDown.

### [Click here](https://dillinger.io/) to visit a online MarkDown Editor

### A [Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) for MarkDown


## Authors and Acknowledgements

- This tutorial followed the principals discussed in Andrew Etter's book, *Modern Technical Writing* 
- Peer reviewed by
  - [Felix Wedel](https://github.com/WedelFelix)
  - [Gurman Toor](https://github.com/GurmanToor)
  - [Nurida Karimbaeva](https://github.com/nuridak)

## FAQs

### Why is Markdown better than a word processor?

Markdown is designed in a most simplistic way than word processors. According to Etter, *it is the most widely used lightweight markup language in the world and has cleaned syntax. For a word processor, the learning curve is quite higher while MarkDown has a limited set of features and defined syntax*. In consequence, it takes less time to learn the syntax. However, the file of a MarkDown file is quite less than a regular word processor file. Therefore, it takes less space. Moreover, MarkDown can be widely used in websites, presentations, regular and technical documentation.

### Apart from Visual Studio Code what other MarkDown editor is available?
- **For personal computer**
  * Windows:
    - [Typora](https://typora.io/#windows)
    - [Sublimetext](https://www.sublimetext.com/download)
  
  * MAC:
    - [MacDown](https://macdown.uranusjr.com/)
    - [ZETTLR](https://www.zettlr.com/)
- **Online editor**
  * [Dillinger](https://dillinger.io/)
  * [Markdown Live Preview](https://markdownlivepreview.com/)

