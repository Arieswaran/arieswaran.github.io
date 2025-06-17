---
layout: project
type: project
image: img/IUverse/iutron.jpeg
title: "IU-tron"
date: 2023
published: true
id: 3
labels:
  - AI
  - Python
  - Discord bot
  - ClickUp and Google Playstore and Appstore API
summary: "AI powered bug reporting and task management bot for discord server"
---

Welcome to IU-tron, where bugs go to die! Just kidding, they go to ClickUp, but that's almost the same thing, right? And it also does few more non interesting things.

First up, we have the AI-powered bug reporting feature. Just tag IU-tron in your message, and it will automatically create a bug report for you. No more manual labor! (Unless you count typing out the tag as manual labor, but let's not go there.)

![image](https://user-images.githubusercontent.com/29358240/220906162-d1c5196b-1a2d-41d0-92a2-96c1130705e2.png)

![image](https://user-images.githubusercontent.com/29358240/220906463-358eb6e0-e1ce-4a62-bb3b-3a36474e82ba.png)


But wait, there's more! IU-tron also has a built-in duplication checker, because we all know how annoying it is to have multiple tasks for the same issue. It's like having a party and inviting the same person twice. Just no. The bot uses the Levenshtein distance and Jaccard similarity to detect any duplicates, and will ask you if you still want to proceed with creating the task. It's like having a personal assistant, but for bug reports.

![image](https://user-images.githubusercontent.com/29358240/220906742-1e9d564f-f00e-45d5-ac83-c32d7bb3891c.png)

And speaking of personal assistants, IU-tron will send you all the details of the created task in a handy-dandy discord message. No more scrambling around trying to find where you put that task, it's all there for you. Plus, you can change the status and priority of the task right from the comfort of your discord server. It's like having a remote control for your tasks.

IU-tron also post reviews from Playstore and Appstore on Discord channels. There are other existing APIs for this, but they don't offer the filteration that we needed. So I created our own. It's not perfect, but it does the job.

Github link : <a href="https://github.com/Arieswaran/IU-tron">IU-tron</a>
