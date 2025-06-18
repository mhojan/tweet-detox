---
layout: none
---

<!-- Analytics -->

<script defer data-domain="mhojan.github.io" src="https://plausible.io/js/script.file-downloads.outbound-links.js"></script>

<!-- Head -->

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap">

<!-- Styling -->

<style>
:root {
  --bg-color: #f8f5f2;
  --main-bg-color: #f8f5f2;
  --info-box-bg-color: #f3f3f3;
  --code-box-bg-color: #f5f5f5;

  --text-color: #2e2e2e;
  --link-color: #0070f3;
  --link-hover-color: #0050c2;
}

body {
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  font-size: 18px;
  line-height: 1.5;
  background-color: var(--bg-color);
  color: var(--text-color);
  padding: 4rem 1.5rem;
  margin: 0;
  margin-top: 1.0rem;
}

p {
  line-height: 1.75;
}

main {
  background-color: var(--main-bg-color);
  max-width: 0.75;
  margin: 0 auto;
  margin-bottom: 2rem;
  padding: 3rem 2rem;
  border-radius: 25px;
  box-shadow: 
    0 4px 12px rgba(0, 0, 0, 0.08),
    0 0 0 1px rgba(0, 0, 0, 0.03),
    0 8px 24px rgba(0, 0, 0, 0.06);;
}

h1 {
  text-align: center;
  font-size: 2.5rem;
  font-weight: 600;
  margin-top: 0;
  color: var(--text-color);
}

h2 {
  font-size: 1.25rem;
  font-weight: 400;
  color: var(--text-color);
  margin-bottom: 2.5rem;
}

a {
  color: var(--link-color);
  text-decoration: none;
  border-bottom: 1px solid #cce4ff;
}

a:hover {
  color: var(--link-hover-color);
  border-bottom: 1px solid var(--link-hover-color);
}

.info-box {
  background-color: var(--info-box-bg-color);
  padding: 1rem 1.25rem;
  border-left: 4px solid #ccc;
  border-radius: 8px;
  margin: 2rem 0;
  font-size: 0.95rem;
  line-height: 1.6;
}

code {
  background: var(--code-box-bg-color);
  padding: 0.2em 0.4em;
  border-radius: 4px;
  font-size: 90%;
}

summary {
  font-size: 1.1rem;
  font-weight: 600;
  margin: 0.5em 0;
  cursor: pointer;
}
</style>

<!-- Title -->

<main style="text-align: center;">

# How to: Tweet Detox 🧹

## A step-by-step tutorial on how to clean up your digital X (formerly Twitter) footprint 👣

#### By: MJ 

<div style="text-align: center; margin-top: 1rem;">
  <a href="https://instagram.com/madeintanzania" target="_blank">📷 @madeintanzania</a>
</div>

</main>

<!-- Table of contents -->

## 🧭 Table of Contents

- [🙋🏾‍♀️ Introduction](#-introduction)
- [⚠️ Legal & Responsible Use](#️-legal--responsible-use)
- [📋 What You’ll Need](#-what-youll-need) 
- [⏳ Estimated Time Breakdown](#-estimated-time-breakdown)
- [📝 Instructions](#-instructions)

<!-- Introduction --> 

## 🙋🏾‍♀️ Introduction

Hello 👋🏾 and welcome! My name is MJ, and I'm a Senior Software Engineer specialized in iOS 📲. 

With privacy getting harder to protect as technology advances, I've been working on cleaning up my digital footprint. One of my biggest missions? Deleting my old tweets. I've had my account since high school.. and i am **embarazzed** by the things i used to do and say! Like what was i even talking about? lol

I searched **everywhere** for tools to wipe them, but most were either broken, sketchy, or required payment. Just as I was about to give up, I had a lightbulb moment and realized: **I can do it myself** 💡 

With a little research and effort, I put together a script that helped me delete over **40,000 tweets 🎉**. After sharing it with friends, I got a lot of requests to help others do the same. So, here we are.

<div class="info-box">
<strong>This tutorial is beginner friendly </strong>. No tech experience is needed. This runs 100% local, so your data never leaves your machine. No logins, no hidden apps -- just you, your archive, and a script 😀
</div>

Just follow my lead, and let me know if you run into issues. Let's get into it! 🚀

<!-- Legal & Responsible Use --> 

## ⚠️ Legal & Responsible Use

Now.. before we start, I'd like to avoid any legal trouble 😅. So here's a quick disclaimer before we continue:

<main>

**This tool is for educational and personal use only.**

By using this script, you agree to the following:

- You will use **your own X (formerly Twitter) Developer App credentials**.
- You will not share, sell, or distribute your API keys or access tokens.
- You will not use this tool to access or delete tweets from any account that is not your own.
- You are responsible for staying within X’s Developer Agreement and Rate Limit policies.

This script is **not affiliated with or endorsed by X/Twitter**.  
Use at your own risk. The author assumes no liability for misuse, bans, or accidental tweet deletions.

</main>

**Long story short:** This script is just for cleaning up your **own** account. Don’t share your keys with ***anyone***, don't do anything ***shady***, and you'll be fine. This tool is not affiliated with X/Twitter. It's just a personal tool to help you take control of your content

Great! Lets get started.. 🏃🏾‍♀️

<!-- What You'll Need --> 

## 📋 What You’ll Need

- 💻 A computer (Mac or Windows) 
- 🛜 Access to the internet
- 🙏🏾 Patience and perseverance

<!-- Estimated Time Breakdown --> 

## ⏳ Estimated Time Breakdown

<div class="info-box">
  <strong>⏱️ Total Active Time: ~30–45 mins</strong><br>  
  🧘🏾‍♀️ Plus passive wait time for archive downloads & the script to complete
</div>

| Step | Description                        | Time |
|------|------------------------------------|------|
| 📁 Step 1 | Download necessary files       | 3–5 min |
| ⬇️ Step 2 | Download your archive          | 5 min + wait |
| 🛠 Step 3 | Create an X Developer Account  | 10–15 min |
| 🔑 Step 4 | Setup your API Keys            | 2–4 min |
| 🐍 Step 5 | Install Python                 | 3–10 min |
| 🏃🏾‍♀️ Step 6 | Run the script                 | 2-5 min (then let it run!) |

<!-- Instructions -->

## 📝 Instructions

<!-- Step 1 - Download Necessary Files -->

### Step 1: Download Necessary Files

<div class="info-box">
  For the sake of simplicity -- and making the next steps easier -- I recommend saving all your files to your <strong>Desktop</strong> 
</div>

- Click below to download the setup files:
    - [👉🏾 Download tweet-detox.zip](resources/tweet-detox.zip)
- Depending on your computer's setup, your browser may either ask where to save the file, or automatically download it to your default folder (most likely **Downloads**).
    - In either case, move `tweet-detox.zip` to your **Desktop**
- Then unzip it:
	•	On **Mac**: double-click the file
	•	On **Windows**: right-click → **Extract All**
- You should now see the unzipped `tweet-detox` folder on your Desktop ✅

<div class="info-box">
<strong>This folder will be your working directory for the rest of the setup</strong>
</div>

