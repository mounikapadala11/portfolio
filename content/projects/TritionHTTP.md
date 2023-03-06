---
title: "TritonHTTP Web Server"
description: "A custom web server that implements subset of HTTP/1.1 Protocol Specification"
dateString: Jan 2023-Feb 2023
draft: false
tags: ["Golang", "VS Code", "Parsing", "Framing"]
weight: 201
cover:
  # image: "/projects/obsidian-publish-github-action/cover.jpg"
---

Built a simple web server called TritonHTTP that implements a subset of the HTTP/1.1 protocol specification.

Utilized a concurrent design to enable the server to process multiple client requests overlapping in time, improving the
efficiency of the server.

The server read data from the client, interpreted them, serviced requests, and sent a response back to the client,
ensuring compliance with the HTTP/1.1 protocol specification.

<!-- ## Intro
In my video about [**How I cleared the AWS SAA Certification Exam**](https://arkalim.org/blog/aws-saa-certification/), I shared my preparation strategy as well as tips to ace the exam. I also gave a glimpse of my revision notes that I prepared while taking the course and practice exams on Udemy. After that video was out, I got so many comments and DMs, requesting me to share my notes, but the problem was that I took these notes using a note-taking app called Obsidian which stores them in markdown format locally on my Mac. Once I'm done editing my notes, I push them to a GitHub repository to make sure I don't lose them if my laptop breaks.

![my notes](/projects/obsidian-publish-github-action/img1.jpg)

So, if you want to view my notes exactly like I do, you can clone my [**Obsidian Vault**](https://github.com/arkalim/obsidian-vault) repository and download **Obsidian** to render it. But, this solution isn't elegant as it would require you to download an additional software. So, I along with my college roommate, [**Sarthak Narayan**](https://sarthaknarayan.tech/), had been working over the past 2 weeks on the project, [**Obsidian Publish using GitHub Action**](https://github.com/project-cool/obsidian-publish-action), which would allow us to effortlessly publish our notes as a static website.

It is complete and I've used it to publish my notes at [**notes.arkalim.org**](https://notes.arkalim.org).
![published notes](/projects/obsidian-publish-github-action/img2.jpg)

## Working
The **GitHub Action** spins up a **Docker** container which parses and converts Obsidian markdown notes into a special markdown format understood by **MkDocs**, an open-source static site generator. MkDocs is actually meant for preparing documentations but works well for notes too. After the markdown files have been converted, all the images in my notes are compressed to a fraction of their original size so that they can load quickly in your web browser. A static site is then built using MkDocs and then finally deployed on **Netlify**. All of this happens automatically using **GitHub Actions**. All I have to do is update my notes and push the changes to GitHub.

## Final thoughts
Having an automated way to publish your notes online with the community is a powerful way to share knowledge. This project has also made it exceedingly easy for me to refer my notes from anywhere, which is powerful when you work on a lot of systems.

## Resources -->
<!--
- [My Notes](https://notes.arkalim.org)
- [Obsidian Publish - GitHub Action](https://github.com/project-cool/obsidian-publish-action)
- [Parser and Image Compressor](https://github.com/project-cool/obsidian-to-mkdocs)
- [MkDocs - Material Theme](https://squidfunk.github.io/mkdocs-material/) -->
