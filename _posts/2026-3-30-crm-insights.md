---
title: CRM Insights Dashboard
date: 2026-3-30
categories: ["AI", "machine learning", "CRM", "CRM-Dashboard"]  
tags: ["crm", "machine learning", "artificial intelligence"]
---

# **Raw Sales Data to Smart Decisions: An AI & ML-Powered CRM Dashboard**

Stop drowning in spreadsheets. Let AI do the work.

....

Having a lot of customer data is not the same as actually understanding it. When you know how your customers behave and what they need, you can make decisions that actually grow your business.

----

## **Why Most Businesses Struggle With Their Customer Data?**
Most businesses collect customer data but don't act on it. The data sits in spreadsheets, scattered across tools, with no clear way to tell which leads are worth following up on, or which customers actually matter to the business. Leads fill up the pipeline with no scoring system to separate the serious buyers from the ones who will never convert, so sales teams end up wasting time on the wrong people.


## **How I solved this problem:**
I built an AI-powered Streamlit web app that gives you a clear, structured view of your leads and customers, saving you from going through large amounts of spreadsheet data. Just upload your data, and the app handles everything behind the scenes.

**My app covers:**
- Lead Scoring & AI-powered follow up recommendations.
- Customer Segmentation.

## **Lead Scoring:**

![lead-scoring-module](assets/images/lead-scoring-module.jpeg)
Lead scoring moduleThis module scores your leads automatically using ML model, separating hot prospects from cold ones so your sales team knows exactly who to contact first. You'll get a CSV to download that you can upload to your CRM system and a dashboard format which will give you instant overview of your all leads.
Your CSV will look this:

![csv-image](assets/images/downloadable-csv-image.jpeg)

### **Follow up recommendations:**
And this is where it gets smart, instead of a plain CSV with just probabilities and categories, it delivers AI-powered follow-up suggestions to help you convert leads into customers, so you're never left guessing what to do next


And now if you scroll down a little you'll have an AI-chatbot interface to know more about your leads. Because the CSV shown will not contain your whole data. I've choosen only a few columns just to make it short and simple, but if wanna know more about them, you've got your own chatbot interface.
Get to know more about your leads by using Gemini AI


---

Customer Segmentation:
Looks pretty great, doesn't it?Here as well, you'll have to upload data, map the columns, and in just few seconds you'll get this pretty dashboard that will tell you about your customer segments. You can instantly see which segment generates the most revenue, how each group behaves differently, and what the AI thinks about each segment. Instead of staring at raw numbers, you now have a visual breakdown that tells you a story about your customers.
Below the dashboard, you'll also get an AI-generated explanation for each segment, describing why it was named that way and what defines it.
Note: You'll always get 3 segments because the ML model is configured to produce exactly 3 clusters.

---

Tech Stack:
I chose Streamlit because it lets you build a fully functional web app in pure Python. I also used some custom HTML and CSS on top of it to make the interface cleaner and more polished than a standard Streamlit app.
For the machine learning side, I used scikit-learn, it's reliable, well- documented, and has everything I needed for both Logistic Regression (for leads scoring) and KMeans clustering (for customer segmentation).
The AI part is powered by Gemini 2.5 Flash. I chose it because it's fast, free to use, and handles both text generation and conversation really well, perfect for follow-up suggestions and the chatbot.

Everything is written in Python, with Pandas and NumPy handling the data processing, and Plotly for the interactive charts.

---

Try It Yourself:
CRM Insights is completely open source. You can explore the full code on GitHub, watch the demo on YouTube, or try the live app directly.
GitHub Repository
YouTube Demo
Live App

Note: The live app is hosted on Streamlit Community Cloud. If it appears inactive, just click "Yes, get this app back up!" and wait a few seconds for it to wake up.

---

Conclusion:
Building CRM Insights taught me that data is only useful when you can actually understand it. With the right tools, even a small business or freelancer can make decisions that were once only possible for large companies with big data teams. That's what I wanted to build, and I hope it's useful for you too.