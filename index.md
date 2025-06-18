---
layout: none
---

<!-- Analytics -->

<script defer data-domain="mhojan.github.io" src="https://plausible.io/js/script.file-downloads.outbound-links.js"></script>

<!-- Head -->

<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">

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
  word-break: normal;
  overflow-wrap: break-word;
}

p {
  line-height: 1.75;
}

main {
  background-color: var(--main-bg-color);
  max-width: 75%;
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

h1, h2, h3, h4 {
  max-width: 100%;
  word-break: normal;
  white-space: normal;
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

.image-div {
  text-align: center;
  max-width: 75%;
}

.image-div img {
  max-width: 75%;
  border-radius: 12px;
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

<h1> How to: Tweet Detox 🧹 </h1>

<h2> A step-by-step tutorial on how to clean up your digital X (formerly Twitter) footprint 👣 </h2>

<h4> By: MJ  </h4>

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
    - [Step 1: Download Necessary Files](#step-1-download-necessary-files)  
    - [Step 2: Download Your Archive](#step-2-download-your-archive)  
    - [Step 3: Create an X Developer Account](#step-3-create-an-x-developer-account)  
    - [Step 4: Set Up Your API Keys](#step-4-set-up-your-api-keys)  
    - [Step 5: Install Python](#step-5-install-python)  
    - [Step 6: Run the Script](#step-6-run-the-script)  
- [🏆 Mission Accomplished!](#-mission-accomplished)  
- [💬 Questions? Comments? Concerns?](#-questions-comments-concerns)

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
<strong> This tool is for educational and personal use only. </strong>
By using this script, you agree to the following:

- You will use <strong>your own X (formerly Twitter) Developer App credentials</strong>.
- You will not share, sell, or distribute your API keys or access tokens.
- You will not use this tool to access or delete tweets from any account that is not your own.
- You are responsible for staying within X’s Developer Agreement and Rate Limit policies.

This script is <strong>not affiliated with or endorsed by X/Twitter</strong>.  
Use at your own risk. The author assumes no liability for misuse, bans, or accidental tweet deletions.

</main>

**Long story short:** This script is just for cleaning up your **own** account. Don’t share your keys with ***anyone***, don't do anything ***shady***, and you'll be fine. This tool is not affiliated with X/Twitter. It's just a personal tool to help you take control of your content

Great! Lets get started.. 🏃🏾‍♀️

<!-- What You'll Need --> 

## 📋 What You’ll Need

- 💻 A computer (Mac or Windows) 
- 🛜 Access to the internet
- 🙏🏾 Patience and perseverance

**Note:** I personally use a Mac, but I did my best to include Windows steps throughout this guide. Let me know if anything's unclear!

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
  For the sake of simplicity -- and making the next steps easier -- I recommend saving all your files to your <strong>Desktop</strong>. This folder will be your working directory for the rest of the setup.
</div>

- Click below to download the setup files:
    - [👉🏾 Download tweet-detox.zip](resources/tweet-detox.zip)
- Depending on your computer's setup, your browser may either ask where to save the file, or automatically download it to your default folder (most likely **Downloads**).
    - In either case, move `tweet-detox.zip` to your **Desktop**
- Then unzip it:
	•	On **Mac**: double-click the file
	•	On **Windows**: right-click → **Extract All**
- You should now see the unzipped `tweet-detox` folder on your Desktop ✅

<!-- Step 2: Download your archive -->

### Step 2: Download your archive

Lets head on over to your internet browser 🔍

<!-- Request to download archive-->

<details>
<summary>Request to download archive</summary>

- Log in to your X account

- Go to [your account settings](https://x.com/settings/account)

- Click **Download an archive of your data**

<div class="image-div">
<img src="images/step2-download-archive-settings.png" style="max-height: 465px;" />
</div>

- You will be asked to verify your password here, and then enter the code sent to your email
- Once you're in, you should see something like this:

<div class="image-div">
<img src="images/step2-download-archive.png" style="max-height: 300px;" />
</div>

- Click **"Request archive"**, and wait for a confirmation email or notification. This can take anywhere from a few minutes to several hours ⏳
</details>

<!-- Download your archive -->

<details>
<summary>Download your archive</summary>

- When you get the email, open the link, (or revisit the account settings page). After verifying again, you'll be able to download your archive
<div class="image-div">
<img src="images/step2-verification-email.png" style="max-height: 400px;" />
</div>

- Click **"Download archive"**

<div class="image-div">
<img src="images/step2-download-archive.png" style="max-height: 400px;" />
</div>

- To make the next steps easier, save the `.zip` file to the `tweet-detox` folder from step 1. The downloaded archive zip file name should begin with `twitter-2025-...` 

<div class="info-box">
  ⏳ This download may take some time, depending on how active your X account has been
</div>
</details>

<!-- Open your archive -->

<details>
<summary>Open your archive</summary>

- Unzip the file

- Inside the unzipped folder, open the folder named `data`

- The only file we need is `tweets.js` -- this contains **all** your tweets and retweets 

- Copy `tweets.js` paste it into the **main** `tweet-detox` folder (essentially outside of the unzipped folder)

<div class="info-box">
  <strong>✨ Bonus:</strong> You can open <code>Your archive.html</code> for a visual overview of your entire account history. Double clicking the file should open your browser
</div>
</details>

<!-- Step 3: Create an X Developer Account -->

### Step 3: Create an X Developer Account

Okay, this part's the longest to actively get through, but **I promise, it's not hard**. Take your time, and follow along, and you'll be done in no time! 🛠️✨

<!-- Create a developer account -->

<details>
<summary>Create a developer account</summary>

In order to run the tweet deletion script, you'll need a set of API credentials. This means creating a **developer account** with X (formerly twitter). This is free, and you only need basic access. 

- Go to the [X Developer Portal](https://developer.x.com/en/portal/dashboard)
- You'll be asked to log in with your X account (if you aren't already)
- If you land on a marketing/landing page, click **Developer Portal** in the top right

<div class="image-div">
<img src="images/step3-landing-page.png" style="max-height: 400px;"/>
</div>

- You'll see a screen like this, click **Sign up for Free Account**
<div class="image-div">
<img src="images/step3-developer-portal.png" style="max-height: 400px;" />
</div>

- You'll be prompted to describe how you plan to use the API. This helps ensures you're not using it for anything shady
<div class="image-div">
<img src="images/step3-developer-agreement-policy.png" style="max-height: 400px;" />
</div>

- The description needs to be at least 250 characters, stating how exactly you plan to use the API. This is what i wrote (w/ the help of ChatGPT):
<main>
I am using a personal script to delete old tweets from my own account as part of cleaning up my digital footprint.
I will only use my own X Developer credentials, and won't share or sell them
I will not access or delete tweets from any account that is not my own.
This script is for personal use only, and complies with X's policies.
</main>

- Once you're done, and agree to all the terms, click **Submit**. Approval is usually instant, and you'll land in the Developer Portal Dashboard
</details>

<!-- Generate authentication keys -->

<details>
<summary>Generate authentication keys</summary>

- On the landing page, you should see a default project and app already created (basic plan only allows one). Click the **gear icon ⚙️** next to your App to configure authentication
<div class="image-div">
<img src="images/step3-project-app.png" style="max-height: 400px;" />
</div>

- On the app details page, click **Set up** under **User authentication settings**
<div class="image-div">
<img src="images/step3-auth-settings.png" style="max-height: 400px;" />
</div>

- Fill in these details **exactly** as shown:
<div class="image-div">
<img src="images/step3-user-auth-settings.png" style="max-height: 400px;" />
</div>

- Under **App Info**, enter the following:

| **Field**           | **Value**                          |
|---------------------|------------------------------------|
| Callback URL        | `https://example.com/callback`     |
| Website URL         | `https://example.com`              |

<div class="info-box">
<strong>Wait, why does it say example.com?</strong>
X (Twitter) requires valid-looking URLs during setup, but we’re not hosting a real website.
<code>https://example.com</code> is just makes setup work — nothing gets sent there 👍🏾
</div>

- When prompted, click **Yes** to confirm your changes
<div class="image-div">
<img src="images/step3-changing-permissions.png" style="max-height: 400px;" />
</div>

- Once setup is complete, you'll be shown your client key and token. 
<strong> 🚨 Save these somewhere safe</strong> — they won’t be shown again! 🚨
</details>

<!-- Create more keys and tokens -->

<details>
<summary>Create more keys and tokens</summary>

- Navigate back to the app details page, click on ***Keys and Tokens***
- Under **Consumer Keys**:
    - Click **Regenerate**
    - This will give you both your **API key** and **Secret key**
    - Save both in the same secure place you used for the authentication keys

- Under **Authentication Tokens**:
    - Click **Regenerate** next to "Access Token and Secret"
    - This will generate the **Access token** and **Access token secret** key
    - Save these as well!!
</details>

<!-- Step 4: Set up your API keys -->

### Step 4: Set up your API keys

Now that you've got your credentials, it's time to put them to use.

- Open your `tweet-detox` folder on your **Desktop**
- Locate the file named `env-template.txt`
- Right-click the file and choose **Open With** → your preferred text editor (Notepad, TextEdit, VS Code, etc.)
- Replace each instance of `your_api_key_here` with the actual credentials you saved in the previous step
- Save the file, and close the editor
- Finally, rename `env-template.txt` to `.env`. It must be renamed to **exactly** this, nothing more, nothing less.

<div class="info-box">
⚠️ Don’t be alarmed if the file seems to disappear after renaming-- files that start with a . are hidden by default on some systems. It’s still there!

To make it visible:
- On **Mac**: Press `Command + Shift + .` while in Finder to toggle hidden files.
- On **Windows**:  In File Explorer, click **View** > check **Hidden items**.
</div>

<!-- Step 5: Install Python -->

### Step 5: Install Python

- Open your terminal:
    - On **Mac**: Open Terminal (press `Command + Space` and search for **Terminal**)
    - On **Windows**: Use Command Prompt or Windows Terminal

- Type or copy and paste the following:
```bash
python --version
```
or if that doesn't work:

```bash
python3 --version
```
If you see something like Python 3.x.x, you’re all set! Skip to the next step 🐍 🎉

#### ❌ Don't have it? here's how to install:
- Go to python.org/downloads
- Click Download Python 3.X.X
- Run the installer and follow the steps
    - ⚠️ On Windows, be sure to check **Add Python to PATH** before clicking install!
- Once done, try running the version command again to confirm it worked (also might need to restart terminal if this doesn't work)