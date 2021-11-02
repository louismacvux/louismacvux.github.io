# Create resume with static site generator

## This will guide you through the process of creating a static site as a resume, and using the tools which are mentioned in Andrew Etter’s book Modern Technical Writing.

## Prerequisite
1. A GitHub account
2. A Jekyll theme
3. A Markdown editor 
4. A resume written in Markdown

## Instruction - still need to refer to Etter's book
### 1. Choose the version control system 
The reason for the version control is that it makes the process of updating the resume a lot easier. Also, if you’re new to this, these systems do a lot of work on your behalf, so you don’t need to put in much effort for a basic web page. I choose GitHub Pages because I have experience with GitHub before. You can also choose Codeberg Pages if you want to. 

### 2. Create a Markdown version of your resume
Since the source of the resume must be written in Markdown, you need to choose a tool that lets you create a Markdown file and also preview it. I use StackEdit to write my Markdown resume. If you’re already familiar with Markdown and how different syntax renders, then any simple text editor such as Notepad or Atom should give you the same result. 

### 3. Set up your GitHub account and repository
  - Create a GitHub account if you don’t have one. 
  - Create a repository with the name following this syntax: [username].github.io . The reason for the strict name is that when GitHub read the repository name, they will automatically know that this is a repository to host a static page, and thus handle it differently. Unless you have a custom domain, the repository name would also be the address of the web page: http://[username].github.io. 
- Go to settings tab of the repository, go to Page and choose a theme. These are the Jekyll themes, which will work automatically with your markdown file. Once you choose a theme, your content in Markdown will be handled in the background and convert to HTML to be shown with the chosen theme. 
- Create a file for your markdown resume. If no file is created, GitHub Page will automatically use the content in the README.md of your repository to convert and show on the static site. If you want the markdown content to be on another file, you have to put it in the index.md file. In order to do that, click Add file then Create new file on the main page of the repository. Add in your content, put the name as index.md and then commit. 
- GitHub Page will take whatever is written in that file and show it on the static site in the Jekyll theme that you’ve chosen.

### Animated gif

## More resources:
1. [Markdown tutorial](google.com) - not included
2. [Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/) by Andrew Etter
3. One more source

## Authors and Acknowledgements
Credit group member and template authors

## FAQ
### Q: Why is Markdown better than a word processor?
A:

### Q: Why is my resume not showing up?
A:



