---
title: What Happens When a Beginner Refuses to Stay a Beginner
date: 2026-4-23
categories: ["AI", "machine learning", "progress"]
tags: ["AI", "learning"]
---

# **What Happens When a Beginner Refuses to Stay a Beginner**
A love story between me, my laptop, Claude, and a notebook that saw too much

![image](assets/images/medium-refuses-to-stay-beginner.webp)

I had no business building this, but… I built it anyway. Classic move!

If you’re here for the technical breakdown, I’ve got a whole separate article for that. Here’s the [deep dive](https://medium.com/@namalrizwan4/raw-sales-data-to-smart-decisions-an-ai-ml-powered-crm-dashboard-da52e84eac06).

But if you’re here for the story, let’s go!

## **How I started it:**
I started my CRM (Customer Relationship Management) project with almost no knowledge about customers and leads, but I was pretty excited to work on this project. I wanted to understand how the market works and how businesses manage their customers.

So I decided to go with this project. I took up my pen and notebook and started writing about the workflow. At that time, I was feeling like I was going to do this project in just a few days. I had that powerful feeling. Well, every programmer thinks like that, but life always has other plans!

Anyway, I downloaded a dataset from Kaggle, set up a notebook, imported the libraries, and started exploring the data. That part felt great, structured, familiar, under control. But the moment the exploration was done, I looked at the screen and said: *what now?*

## **Overthinking the Simple**
I kept staring at the screen for a few minutes, then decided to Google *“how to work on a customer segmentation project”*. One of the first results included something called “RFM”. It was technically intimidating at first. I felt that this would take me weeks to understand and implement it. That confident feeling I started with? It started quietly fading.

I started searching for it, and after understanding what it actually was, I was like Booom, it’s so easy, I was stressing out for no reason.

With this happy feeling, and a smile on my face, I kept working on the project.

## **The Wall wasn’t a Wall**

After exploring the data, I moved on to the “Feature Engineering” part. I always used to think of feature engineering as the challenging thing, since we have to figure out on our own what features would be useful in our use case.

And that’s already the hard part. Add zero domain knowledge on top of that , and it gets even trickier. But not knowing something never stopped me. If I don’t know something, I find out.

So, I again pulled out my trusty pen and notebook, figuring out what I could do with this dataset. After lots of research, and bombarding Claude with every possible question, I finally came up with some features and created them. And I realized, well, feature engineering is not a “monster”. It’s fun to create something after putting in effort.

The reason I used to think of it as a really tricky thing is because in courses, our instructors have laid out a clean, well-structured path for us. Errors are already figured out for us, and everything is clean and understandable. But in the real world, working on projects is a lot messier than your course projects.

And that’s exactly what makes it fun.

You’re solving an error at 2 am that’s been haunting you for 2 days? Damn man! We are in the same boat!!

## **The Results Were Pretty, the Plots Were Prettier**

Same story for the modelling, ran the numbers, let the algorithms do their thing, and ended up with these plots.
![image](assets/images/medium-post-plots.webp)

*Well, these graphs were made before the clusters knew who they were, classic identity crisis.*

![image](assets/images/medium-post-detail-clusters(2).webp)

*This is what the brainstorming looked like. Truly historic work. Took this one just for you.*

**And Lead Scoring?** Well, the process was the same, but I wasn’t. And honestly, that was the whole point.

By the time I got to lead scoring, I knew what I was doing. Mostly.

I’d done classification before, but every dataset humbles you differently. An AUC of 0.66 , not perfect, not going to lie. But it was above the baseline and the curve was behaving itself. I’ll take it.

*And as you can see below , properly labeled this time. Growth!*
![image](https://github.com/namal-xx/namal-xx.github.io/blob/main/assets/images/medium-post-plots(2).webp)

## **The Gemini Chapter. Claude, Don’t Read This.**

It was the time to add a brain into my app and actually make it intelligent. It was the most fun and exciting part for me. I first selected OpenAI for making **AI-Powered follow-up recommendations**, but when it was time for testing, I found out I couldn’t use OpenAI API for free (I might be wrong, but that’s what I came up with).

Then I decided to go with Gemini *(Sorry Claude for not choosing you, but I had no other option)*. I could use Gemini at no cost for my portfolio project, so it was a fair option.

*Well, I couldn’t access the Gemini API key at first because I’m under 18, used my brother’s account!*

I spent most of my time building an AI chatbot and getting recommendations from Gemini. I had to watch a lot of videos on how to create a chatbot.

Three hours of YouTube later, something finally clicked. And when the chatbot gave its first actual response, I did the thing. You know the pose.
![image](assets/images/medium-post-verstapen-pose.webp)

At that moment, I felt like I was Max Verstappen of coding.

## **The Glow Up**

This was the time to put everything on streamlit. So other people can also access my app.

The workflow was to get data from the user and instantly show recommendations based on their lead categories and dashboard based on customers segments.

The code was getting longer and longer. Putting them all together was difficult. I lost my mind many times, but I knew I’d complete it beautifully.

And that’s exactly what happened. After weeks of effort, my app had that glow up. It looked good. It had pretty dashboards for segments.

![image](assets/images/medium-post-dashboard.webp)

## **Oh Right, I Have to Deploy This Thing**
I hit the deploy button. Waited. Refreshed. And there it was, live and working. No error pages. No broken layouts. Just the app, sitting on the internet, doing its thing.

I didn’t trust it though. Kept clicking around, testing every feature, half expecting something to fall apart. Nothing did. Opened it on my phone just to be sure. Still worked. I should’ve been happy. And I was. But getting here? That’s a different story.

## **It Wasn’t All Verstappen Poses**

There are so many things I struggled with while working on this app. Some of them are:

1. **When in Doubt, Run the Code:**

The very first thing was finding out the optimal number of clusters. It was my first unsupervised learning project so, I had no idea what would be good. Watched tutorials, asked questions but I couldn’t get anything. Then I applied my instructor’s advice, “If in doubt, run the code”. I did exactly this, made some plots, experimented, and selected the number I found optimal for my dataset.





















