# Build with AI, Publish to the Web

## A training example by Adam Cagle

This repository contains **Archer the Great**, the example website built during Adam Cagle's training walkthrough on creating a website with AI and publishing it through GitHub and Vercel.

Archer is Adam's boxer. His photos and a few breed facts give the class a simple, concrete project to work with. The purpose of this site is to demonstrate the learning process: turning an idea and some content into website files, saving those files in a repository, and publishing a working website that other people can visit.

The repository is named `name` because that is the example repository name used in the walkthrough. When following the lesson, choose a name that describes your own project.

## Follow the lesson

- **Watch the full YouTube walkthrough:** [How to Deploy Your AI Website | Chat GPT, GitHub & Vercel](https://www.youtube.com/watch?v=gk_mun8lB3Q)
- **Read the companion blog guide:** [Build with AI, Publish to the Web](https://adamcagle.com/blog/build-with-ai-publish-to-web)
- **Explore Adam's tutorials, projects, and AI consulting:** [adamcagle.com](https://adamcagle.com)

The video is part of **Super Intelligence with Adam Cagle**. Use the written guide alongside the video and this repository to follow the complete process.

## What the class teaches

1. Create a GitHub repository for your website.
2. Connect the repository to Vercel.
3. Connect Chat GPT to GitHub using the tools demonstrated in the lesson.
4. Give AI a clear request and the content it needs to build the site.
5. Review the generated website and save its code to GitHub.
6. Deploy the project through Vercel and open the live website.

### How the tools fit together

| Tool | Role in the lesson |
| --- | --- |
| **Chat GPT** | Helps create and revise the website from your instructions and supplied content. |
| **GitHub** | Stores the website files and records changes to the project. |
| **Vercel** | Publishes the files as a website and can deploy updates from the connected GitHub repository. |

The result is a static website built with HTML, CSS, and JavaScript. Visitors do not need Chat GPT or an AI API key to use it.

## What is included

- A responsive page introducing Archer.
- A gallery of ten photos with captions and a larger photo viewer.
- Boxer breed facts with links to their sources.
- A demonstration inquiry form.

**The inquiry form is a classroom example. It does not send email, submit messages to a server, or store submissions.** Its confirmation text explains that the message has not been sent or saved. Receiving real inquiries would require an additional integration outside this example.

## Project files

| File or folder | Purpose |
| --- | --- |
| `index.html` | Page content, structure, navigation, breed facts, and demo form. |
| `style.css` | Colors, typography, layout, and responsive styling. |
| `script.js` | Photo gallery, photo viewer, and demo form behavior. |
| `assets/` | Optimized Archer photos and gallery thumbnails. |
| `vercel.json` | Cache settings for image assets. |

Photos are oriented using their EXIF data, stripped of metadata, resized to a maximum of 1500 pixels, and converted to WebP. Gallery thumbnails are capped at 600 pixels. Original photos are not committed to this repository.

## Preview the example locally

Download or clone the repository, then open `index.html` in a browser. Keep the CSS, JavaScript, and `assets` folder together with the HTML file so styles and images load correctly.

There are no package dependencies to install and no build step. The page loads its fonts from Google Fonts when an internet connection is available.

## Publish with Vercel

Import your copy of the GitHub repository into Vercel and use these project settings:

| Setting | Value |
| --- | --- |
| Framework preset | **Other** |
| Root directory | Repository root |
| Build command | None |
| Output directory | `.` |

Deploy the project, then open the URL Vercel provides. Once the repository is connected, commits to the configured production branch can trigger updated deployments.

For the complete guided setup, follow the [video](https://www.youtube.com/watch?v=gk_mun8lB3Q) or [blog walkthrough](https://adamcagle.com/blog/build-with-ai-publish-to-web).

## Try the process with your own idea

Use the lesson to build a small project of your own. Supply your own content and images you have permission to use, review the generated code and wording, and check the finished page on both a phone and a desktop browser.

This example covers creating and publishing a static site. Databases, accounts, payments, and working contact forms are additional features that require their own setup.
