# Hosting Your Resume on GitHub Pages: The Algorithm

## Purpose
This is a step-by-step guide on how to put your resume on GitHub Pages. You'll use Markdown and Jekyll to style and format your resume, then you will create a repository and host it on GitHub Pages.  

This README will:  
- Describe the practical steps on how to host and format your resume onto GitHub Pages
- Relate the practical steps described to the general principles of current Technical Writing, as explained in Andrew Etter's book [Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)


## Prerequisites
- Have your resume ready, formatted in Markdown.
   - If Markdown is new to you, check out this [Markdown Tutorial](https://www.markdowntutorial.com/) for a quick introduction.
   - You can use [Visual Studio Code](https://visualstudio.microsoft.com/downloads/) to format your resume in Markdown.
- A [GitHub](https://github.com/) Account
   - You will use GitHub Pages to host your formatted resume
- Basic knowledge on Jekyll/YAML
   - If you are unfamiliar with Jekyll/YAML, check out this [Tutorial](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_yaml_tutorial.html) for a quick introduction.

## Instructions
Follow these straightforward steps to host your resume on GitHub Pages:

1. **Go to your GitHub Home Page:**
   - If you don't have one, sign up for a [GitHub account](https://github.com/).
- *This step aligns with Etter's emphasis on using collaborative platforms for documentation*

2. **Create a New Repository:**  

   ![](https://github.com/tsangkevin99/tsangkevin99.github.io/blob/main/Gifs/newrepo.gif?raw=true)
   - Go to the main page on GitHub.
   - Click on the green "New" button at the top left.
   - Pick a repository name, perhaps something like `yourusername.github.io` where "yourusername" is your GitHub username.
   - Initialize the repository with a README file. (Optional)
   - Click on `Create Repository` at the bottom of the page.  
- *This reflects Etter's focus on organized and structured documentation as well as using Distributed Version Control*

3. **Upload Your Markdown Resume:**  

   ![](https://github.com/tsangkevin99/tsangkevin99.github.io/blob/main/Gifs/upload.gif?raw=true)
   - Click on the 'Add file' drop down and select `Upload files`.
   - Upload your markdown resume and save the file as `index.md` in the repository.
   - At the bottom, click on the green `Commit changes` button to make the change.
- *This step emphasises valuable content and starting documentation with essential information. In addition, using Markdown is one of Etter's key concepts as they believe it has the cleanest syntax*

4. **Enable GitHub Pages:**  

   ![](https://github.com/tsangkevin99/tsangkevin99.github.io/blob/main/Gifs/gitpages.gif?raw=true)
   - In your repository, go to `Settings` located at the top of the page in the center.
   - Next, navigate to the left hand side and click on the `Pages` section.
   - Under Build and deployment scroll down to Branch and choose the `main` branch.
   - Afterwards you can navigate back to your repository page by clicking on your repository name on the top left e.g. `yourusername.github.io`
- *This step relates to Etter's concept of making documentation accessible*

5. **Jekyll Template:**
   - Next we are going to create a file to utilize Jekyll.
   - Navigate to the `Add file` button in your repository.
   - Click on `Create new file` 
   - At the top left there is a bar that says `Name your file...`, name the file `_config.yml`.
   - Configure the file, select a theme and add any site details you want.
      - [Here](https://jekyllrb.com/docs/themes/) are some themes to look at 
   - Click on the `Commit changes` button at the top right corner when finished.
- *This step relates to Etter's concept on using templates for consistency and simplicity in documentation. In addition, Etter emphasises on making static websites for their speed and simplicity*

6. **README File: (OPTIONAL)**
   - Next, if you initialized the README file when creating your repository
   - Format the `README.md` file in markdown and provide a summary about yourself and your resume
   - To do this, navigate to your repository page, there should be a README underneath your files such as `README.md`, `_config.yml` and `index.md`.
   - Click on the pencil icon at the top right to edit your `README.md` file
   - Once you are done making changes, click on the top right `Commit changes` button that is green  
- *This step relates to Etter's concept on making documentation easily available and accessible to users*

7. **Open Your Hosted Resume:**
   - After a few minutes, your resume will be accessible at `https://yourusername.github.io`.
   - If you have done everything correctly, it should look similar to this!  
![](https://github.com/tsangkevin99/tsangkevin99.github.io/blob/main/Gifs/demo.gif?raw=true)  
*Congratulations! You successfully hosted your own resume on GitHub Pages using Markdown and Jekyll.*
- *This step relates to Etter's principle of making documentation easily available to users*

## More Resources
- [Markdown Guide](https://www.markdownguide.org/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Visual Studio Guide](https://code.visualstudio.com/docs/introvideos/basics)
- [Andrew Etter's Modern Technical Writing](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS)

## Authors and Acknowledgements
[Kevin Tsang](https://github.com/tsangkevin99): Author of Resume and README file  
[Heejeong Kim](https://github.com/Heejoy): Peer editor and Group 7 member  
[Jonathan Placatka](https://github.com/jonathanplacatka): Peer editor and Group 7 member  
Theme by [orderedlist](https://github.com/orderedlist)

## FAQs

**Q: Why is Markdown better than a word processor?**  
- Markdown gives a simple and readable way to format text without the complexities of using a word processor. It allows for easy version control since text files are easier to manage using tools like Git. Additionally, Markdown is not platform dependent meaning it is suitable for collaborative projects where contributors may use different operating systems.

**Q: Why is my resume not showing up?**  
- If your resume is not showing up on GitHub Pages try:
   - Checking that your repository is set to public visibility Settings > Options > GitHub Pages > make sure the source branch is correctly configured.  
   - Verifying that your Markdown and Jekyll files are correctly named as `index.md` and `_config.yml`
   - Waiting at least a few minutes for changes to reflect
- If the issue persists, check for typos or formatting errors in your Markdown file that could be causing an issue

**Q: Why host my resume on GitHub Pages?**  
- Hosting your resume on GitHub Pages offer several advantages such as:
   - Free hosting for static websites making it available to anyone without spending money
   - Easy version control using Git
   - Easy integretion using Jekyll, a static site generator
   - Showcases proficiency in using modern technical documentation tools
   - Resume accessible to potential employers or collaborators

