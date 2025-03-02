# Hosting a Resume/CV online as a GitHub WebPage

**By this steps, any user who doesn't have coding knowledge or just have basic knowledge of HTML/CSS can create beautiful Resume/CV/ Portfolio**

**This whole process can be divided mainly into three Parts:**

1. Creating a GitHub Webpage repository.
2. Creating a resume using MS Word or other such Word/DOC Processor & Creator and Converting the DOC resume to HTML+CSS
3. Uploading Resume/CV webpage to GitHub repo

------



#### Let's get into Part 1: Creating a GitHub Webpage repository.

- If you don't have a GitHub Account then it's time for you to create one. (it's Free, but there is a paid version too with some added benefits)
- If you have a GitHub Account or you are done creating one, then here is the next thing:
- Find the '+' button on the top right corner of the GitHub profile just beside you profile picture.
- Click on it >> Now you can see "New Repository" option >> Select it >> It redirects to new repo creation page
- Now name the repo in 'Repository name' field (it is like the username for the repo profile.).
- Keep the repo as 'Public'. (Caution: Don't keep it as 'Private'.)
- You can leave the optional steps like Description, Initializing README.md file, adding .gitignore and adding a license.
- Click on "Create Repository" >> Hurray!! New Repo is created, you will be shown with Setup guide which you can check based on your interest
- Now go-to "Code" tab and create an index.html file which is the homepage for you website/CV/ Resume >> Then type some content in file like 'Hello World'
- Scroll down and you'll find "Commit Changes" option where you can enter Commit message and description. Click on Commit Changes (adding message and description is Optional but is recommended to add for reference).
- Now find the "Settings" tab in the repo page >> Click on it >> Scroll down the page.
- You will find 'GitHub Pages' settings >> in this part, select the Source as "master branch"
- Now you can see that in GitHub Pages part, it shows the URL with which you can access your webpage/CV/Resume

> TIP: To have a short and easy URL, make the name of repository as your_github_username.github.io (E.g.: http://bbsusheelkumar.github.io) to access webpage using it as URL >> Check https://pages.github.com

------



#### Let's get into Part 2: Creating a resume using MS Word or other such Word/DOC Processor & Creator and Converting the DOC resume to HTML+CSS.

- Create a resume/CV using an Word Processor (Microsoft Word, OpenLibre etc).

  > TIP: Make sure you create using standard Fonts, fewer images and everything organized as Tables without borders (specifically like Bootstrap design format i.e Grid System). This will make us easy to manage the spacing and page printing structure.

- Now save the resume/CV >> After Saving, click on export as HTML which is generally available in 'File' menu of any Word. If not available just renaming the .doc/.docx to .html may work (but not recommended).

- Open the .html file in Notepad and you can find all the data formatted in you .doc file as HTML & CSS code. Also you'll find some XML code which is generally useless and you can delete it.

- Now Save the .html file >> Copy all the contents of .html file

  

  *Great!! We are done with second part too.*

------



#### At last get into Part 3: Uploading Resume/CV webpage to GitHub repo.

- Here is the final step, Go to "Code" section of the repo >> open index.html file in our repo which we previously created.

- In the code page of index.html, you could find a 'Pen/Pencil' like button on top right side of the file. It is nothing but 'Edit this file' button.

- Click on it >> Paste the copied .html code in the 'Edit File' area >> Scroll down and click "Commit Changes" just like we have done previously.

  

  *Super!! We are done. Now you can find the CV/Resume webpage in username.github.io URL !!*



------

> **EXTRA TIP:**
>
> **Now go to the URL and try to print webpage and check whether Print Layout of the page is the same as your Resume/CV in doc file, if not make some spacing and tab alterations by adding, removing or modifying HTML and CSS properties with just basic knowledge of it.**
