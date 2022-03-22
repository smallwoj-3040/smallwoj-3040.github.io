# Hosting Your Resume on GitHub Pages


**Purpose**: This document serves as a guide to hosting a resume online using Jekyll, Markdown, and GitHub Pages. This guide will demonstrate practices described in Andrew Etter's book [*Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).


## Prerequisites
It is recommended to be familiar with Markdown to best follow along with this guide. In addition, it is important to have a resume tailored to the position you wish to apply for.

For more resources on Markdown and resume writing, see the [More Resources](#more-resources) section of this guide.

## Instructions
The steps highlighted in this section will guide you through the process of hosting a resume on GitHub Pages while following Etter's general principles of Technical Writing.

1. Sign up for GitHub.
    - If you do not have a GitHub account already, you can do so by going to https://github.com/signup and following the prompts there to set up your account.

2. Create the repository.

    a. You can do this from anywhere on GitHub! Just click on the + in the top left beside your icon to create a new repository.
    
     ![image](https://user-images.githubusercontent.com/31932412/159107669-5387dafe-50e9-42e2-b5c4-06358e119e5e.png)
       
    b. To best use GitHub Pages, make sure the repository name is `<Your Username>.github.io`
      - For example, someone with the username `biggie-cheese24` would name their repository `biggie-cheese24.github.io`.
      
      ![image](https://user-images.githubusercontent.com/31932412/159108426-09c36d88-7f4b-4dfc-8baa-8492018943f4.png)


3. Upload your resume in Markdown.

    a. If you have your resume built in Markdown, you can upload it to the repository using the `Add File` button at the top of the files section.
       
      ![image](https://user-images.githubusercontent.com/31932412/159206082-d525486b-0b18-42f1-af1d-dcaa49062e89.png)

    b. Make sure the resume is saved as `index.md` to ensure the best results for viewing the resume on your final static website.
  

4. Choose a Jekyll theme.

    a. Click the `Settings` tab along the top.
    
    b. Click the `Pages` tab along the side.
    
    c. Click the `Change Theme` button under the `Theme Chooser` heading.
    
    d. Select the theme you like best.
    
    e. Click the `Select theme` button to confirm your selection.

![3040-theme](https://user-images.githubusercontent.com/31932412/159219508-f415de07-7e36-4b73-a23f-8d131f32bde2.gif)

5. View the finished page.
    
    - After selecting your theme, you can view the built website from the link above the `Source` heading.
    ![resume](https://user-images.githubusercontent.com/31932412/159591141-7ea71bc1-34f4-46ac-b696-a23e97018b31.gif)


## Authors and Acknowledgments
Leap Day theme by [Matt Graham](https://github.com/pages-themes/leap-day).

Editors:
- Azizul Hakim
- Harshal Bhalerao
- Deepta Mandal

## Frequently Asked Questions
### Why use Markdown or other lightweight markup options?
Andrew Etter, in his book, notes some key highlights of using lightweight markup:
- Stored in a pure text format.
- Can use virtually any text editor to write.
- Plays nice with version control options. (Like GitHub!)
- No need for any expensive software to edit and view documents.

### How do I make text Right Justified?
This can depend on what theme you choose, but one method that works for most themes is to surround the text with html as follows:

```html
<span style="float: right;">Text goes here</span>
```

Using this arrangement, you can have text right justified on the same line as other text that is left justified.

Note that this is not respected in GitHub's rendering of the Markdown file, but it is respected in some themes, such as the Leap Day theme by [Matt Graham](https://github.com/pages-themes/leap-day).

## More Resources
### Markdown
- [Markdown Tutorial](https://www.markdowntutorial.com/)
### Technical Writing
- Andrew Etter's book [*Modern Technical Writing*](https://www.amazon.ca/Modern-Technical-Writing-Introduction-Documentation-ebook/dp/B01A2QL9SS).
### Resume Writing
- [Job Bank Canada - How to write a good resume](https://www.jobbank.gc.ca/findajob/resources/write-good-resume)
