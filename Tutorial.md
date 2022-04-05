# Create resume with static site generator

#### This document will guide you through the process of creating a static site as a resume, and using the tools mentioned in Andrew Etter’s book *Modern Technical Writing*.
---
![resume](GIF.gif)

The resume can be found [here](https://louismacvux.github.io/)

## Prerequisite
1. A GitHub account
2. A Jekyll theme
3. A Markdown editor 
4. A resume written in Markdown
<br>

## Instruction
### 1. Choose the version control system 
 >The reason for the version control system (VCS) is that it makes the process of updating the resume a lot easier. According to Etter, Git tracks changes over time, and each change is put in the changelog for each file, and it’s easy to trace back to the owner of the change. If you enable contribution, others can also make changes to the file and create a pull request or ask the owner to verify the changes.
 - VCS like GitHub not only helps with updating content but also has GitHub Pages that does a lot of the hosting work on your behalf, so you don’t need to put in much effort to generate a basic web page. I choose GitHub Pages because I have experience with GitHub before. You can also choose [Codeberg Pages](https://codeberg.org/) if you want to. 

### 2. Write a resume in Markdown
 >Markdown is a lightweight markup language using text editors. According to *Modern Technical Writing*, Markdown is human-readable, easy to learn and has a simple syntax. Moreover, it takes fewer characters to display the same content compare to something like XML. In today’s world, when everyone can be a contributor, using something widely used, easy to learn will increase people’s ability to contribute.
 - Since the resume must be written in Markdown, you need to choose a tool that lets you create a Markdown file and also preview it. I use [StackEdit](https://stackedit.io/) to write my resume in Markdown. If you’re already familiar with Markdown and how different syntax renders, then any text editor should give the same result. 
 - Make sure the name of the file is `index.md`

### 3. Set up GitHub account 
>According to Andrew Etter, if you use PDFs or something similar to distribute documentation that is likely to be updated in the future, there is no way to enforce users to download the newer version. Even if they do, it will be separated PDFs, not overwriting the old one. So by updating the site that people need to go to for documentation, every change is made in one place and anyone can access the latest information.
 - Create a [GitHub](https://github.com/) account if you don’t have one. 
 - **Create a repository:**
	 - Go to your GitHub profile, click + in the top right corner and choose **New repository**
	 - Write`[username].github.io`as **Repository name** . The reason for the strict name is that when GitHub reads the repository name, they will automatically know that this is a repository to host a static page, and thus handle it differently. 
	 - Choose **Public** for this repository
	 - Click **Create Repository** 
 - **Create GitHub Pages:**
	 - Go to **Settings** tab of the repository, click on **Pages**. 
	 - Under **Source**, choose `main` as your branch, then click **Save**
  - Unless you have a custom domain, the address of the web page is  `http://[username].github.io`. 

### 4. Upload the Markdown resume
- Click **Add file** and then **Upload files** on the main page of the repository. 
- Choose the file on your local computer and click **Commit changes**
- GitHub Page will take whatever is written in that file and show it on the static site in the Jekyll theme that you’ve chosen.
- If no file is created, GitHub Page will automatically use the content in the `README.md` to show on the static site.  Otherwise,  it will use content in the `index.md` file.

### 5. Choose a theme 
- Go to **Settings** tab of the repository, click on **Pages**. 
- Under **Theme chooser** , click **Choose a Theme** to select a theme. 
- Go through the themes available and click **Select Theme**. These are the [Jekyll](https://jekyllrb.com/docs/themes/) themes, which will work automatically with your Markdown file
- After choosing a theme, a `_config.yml` file is added to the repository. Add `title` and `description` if you want to change the default configuration
- ![Screen Shot 2021-11-02 at 8 15 14 PM](https://user-images.githubusercontent.com/57550224/139984575-637c44be-03d4-42b0-a660-612ffb456a1b.png)
-  Once you choose a theme, your content in Markdown will be handled in the background and converted to HTML and shown on the site.
<br>

## More resources
1. [Markdown tutorial](https://www.markdownguide.org/basic-syntax/)
2. [Modern Technical Writing](https://www.amazon.com/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS/) by Andrew Etter
3. Getting Started with [GitHub Pages](https://guides.github.com/features/pages/)
4. [Codeberg Pages](https://codeberg.org/) - alternatives to GitHub Pages
5. [StackEdit](https://stackedit.io/) - Markdown editor
6. [Jekyll](https://jekyllrb.com/docs/themes/) theme
<br>

## Authors and Acknowledgements
Created by [Long Vu](https://github.com/louismacvux) using Readme template from Steven Wilcox. 
Thanks Abu Yasin Sabik, [Abdullah Al Noman](https://github.com/nomanaa), Muhammad Hasan Saleem and [Jaden Down](https://github.com/jpdown) for peer editing.
<br>

## FAQ
### Why is Markdown better than a word processor?
Documents that need to be updated over time, like software documentation, need to be kept in a version control system. Markdown is a lightweight markup that can help you achieve this. It’s straightforward and really easy to learn and pair Markdown with HTML or CSS, you will have much more room for customization compared to what a word processor like Microsoft Word can do. Word is only good for someone who wants to create short, and attractive PDFs that don’t take much effort to look good. And lastly, a Text editor for Markdown is free, while you need to pay to use a common word processor like Microsoft Word.

### I can't find a theme that I really like. What should I do?
If you find a theme that is most similar to what you're looking for, but some headings or the way the bullets are shown can use some adjustment, you can totally choose the theme and edit it to your liking. Or if nothing catches your eyes at all, you can create your own theme. Check out Jekyll in [More resources](https://github.com/louismacvux/louismacvux.github.io#more-resources)  to learn more about Jekyll theme




