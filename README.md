# Create resume with static site generator

## This document will guide you through the process of creating a static site as a resume, and using the tools which are mentioned in Andrew Etter’s book Modern Technical Writing.
---
## Prerequisite
1. A GitHub account
2. A Jekyll theme
3. A Markdown editor 
4. A resume written in Markdown
<br>

## Instruction
### 1. Choose the version control system 
 - The reason for the version control system (VCS) is that it makes the process of updating the resume a lot easier. According to Etter, Git tracks changes over time, and each change is put in the changelog for each file, and it’s easy to trace back to the owner of the change. If you enable contribution, others can also make changes to the file and create a pull request or ask the owner to verify the changes.
 - VCS like GitHub not only helps with updating content but also has GitHub Pages that does a lot of the hosting work on your behalf, so you don’t need to put in much effort for a basic web page. I choose GitHub Pages because I have experience with GitHub before. You can also choose Codeberg Pages if you want to. 

### 2. Create a Markdown version of your resume
 - Markdown is a lightweight markup language using text editors. According to “Modern Technical Writing”, Markdown is human-readable, easy to learn and has a simple syntax. Moreover, it takes fewer characters to display the same content compare to something like XML. In today’s world, when everyone can be a contributor, using something widely used, easy to learn will increase people’s ability to contribute.
 - Since the resume must be written in Markdown, you need to choose a tool that lets you create a Markdown file and also preview it. I use StackEdit to write my resume in Markdown. If you’re already familiar with Markdown and how different syntax renders, then any simple text editor such as Notepad or Atom should give you the same result. 

### 3. Set up your GitHub account and repository
  - Create a GitHub account if you don’t have one. GitHub and GitHub Pages help you host the static site with ease. According to Andrew Etter, if you use PDFs or something similar to distribute documentation that is likely to be updated in the future, there is no way to enforce users to download the newer version. Even if they do, it will be separated PDFs, not overwriting the old one. So by updating the site that people need to go to for documentation, every change is made in one place and anyone can access the latest updates.
 - Create a repository with the name following this syntax: ```[username].github.io``` . The reason for the strict name is that when GitHub reads the repository name, they will automatically know that this is a repository to host a static page, and thus handle it differently. Unless you have a custom domain, the repository name would also be the address of the web page: ```http://[username].github.io```. 
- Go to **Settings** tab of the repository, go to **Page** and choose a theme. These are the Jekyll themes, which will work automatically with your markdown file. Once you choose a theme, your content in Markdown will be handled in the background and converted to HTML to be shown with the chosen theme. 
- Create a file for your markdown resume. If no file is created, GitHub Page will automatically use the content in the ```README.md``` of your repository to convert and show on the static site. If you want the markdown content to be on another file, you have to put it in the index.md file. To do that, click **Add file** and then **Create new file** on the main page of the repository. Add in your content, put the name as ```index.md``` and then click **Commit**. 
- GitHub Page will take whatever is written in that file and show it on the static site in the Jekyll theme that you’ve chosen.
<br>

### Animated gif
<br>

## More resources
1. [Markdown tutorial](google.com) - not included
2. [Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/) by Andrew Etter
3. [Getting Started with GitHub Pages](https://guides.github.com/features/pages/)
<br>

## Authors and Acknowledgements
 - Abu Yasin Sabik 
 - Abdullah Al Noman
 - Muhammad Hasan Saleem
 - Jaden Down
<br>

## FAQ
### Why is Markdown better than a word processor?
Documents that need to be updated over time, like software documentation, need to be kept in a version control system. Markdown is a lightweight markup that can help you achieve this. It’s straightforward and really easy to learn and pair Markdown with HTML or CSS, you will have much more room for customization compared to what a word processor like Microsoft Word can do. Word is only good for someone who wants to create short, and attractive PDFs that don’t take much effort to look good. And lastly, a Text editor for Markdown is free, while you need to pay to use a common word processor like Microsoft Word.

### I can't find a theme that I really like. What should I do?
If you find a theme that is most similar to what you're looking for, but some headings or the way the bullets are shown can use some adjustment, you can totally choose the theme and edit it to your liking. Or if nothing catch your eyes at all, you can create your own theme. Visit [Jekyll](https://jekyllrb.com/docs/themes/) to learn more about Jekyll theme



