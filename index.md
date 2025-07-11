---
layout: none
---

<head>
  <!-- Analytics -->
  <script defer data-domain="mhojan.github.io/tweet-detox" src="https://plausible.io/js/script.js"></script>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700;800&display=swap" rel="stylesheet">
</head>

<!-- Styling -->

<style>
:root {
  --bg-color: #eeeae6;
  --main-bg-color: #e8e1d9;
  --info-box-bg-color: #dcdcdc;
  --code-box-bg-color: #dcdfe3;

  --text-color: #s;
  --link-color: #3366cc;
  --link-hover-color: #1a53b0;
}

body {
  font-family: 'Open Sans', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  font-size: 18px;
  line-height: 1.5;
  background-color: var(--bg-color);
  color: var(--text-color);
  padding: 4rem 1.5rem;
  margin: 0;
  word-break: normal;
  overflow-wrap: break-word;
}

p {
  line-height: 1.75;
}

h1 {
  font-weight: 800;
  color: var(--text-color);
}

h2, h3 {
  font-weight: 700;
  color: var(--text-color);
}

h4, h5 {
  font-weight: 600;
  color: var(--text-color);
}

strong, b {
  font-weight: 700; /* or 800 for maximum boldness */
}

a {
  color: var(--link-color);
  text-decoration: none;
  border-bottom: 1px solid rgba(51, 102, 204, 0.2);
}

a:hover {
  color: var(--link-hover-color);
  border-bottom: 1px solid var(--link-hover-color);
}

.ig-link {
    text-align: center;
    margin-top: 1rem;
}

ul, ol {
  line-height: 1.75; /* Match your body line-height or adjust as needed */
  margin-bottom: 1rem; /* Optional: adds breathing room below lists */
}

li {
  margin-bottom: 0.5rem; /* Optional: adds space between individual list items */
}

.image-div {
  text-align: center;
  max-width: 75%;
  margin: 0 auto;
}

.image-div img {
  max-width: 75%;
  border-radius: 12px;
}

code {
  background: var(--code-box-bg-color);
  color: #24292f;
  font-family: SFMono-Regular, Consolas, Liberation Mono, Menlo, monospace;
  padding: 0.2em 0.4em;
  border-radius: 4px;
  font-size: 85%;
}

summary {
  font-size: 1.2rem;
  font-weight: 600;
  margin: 0.5em 0;
  cursor: pointer;
}

table {
  width: 75%;
  border-collapse: collapse;
  margin: 1.5rem auto;
}

th, td {
  border: 1px solid #ccc;
  padding: 0.75rem;
  text-align: left;
}

th {
  background-color: var(--info-box-bg-color);
}

.container {
  max-width: 75%;
  margin: 2rem auto;
  padding: 2rem;
}

.elevated-container {
  background-color: var(--elevated-bg-color);
  margin: 0 auto;
  margin-bottom: 2rem;
  padding: 3rem 2rem;
  border-radius: 25px;
  box-shadow: 
    0 4px 12px rgba(0, 0, 0, 0.08),
    0 0 0 1px rgba(0, 0, 0, 0.03),
    0 8px 24px rgba(0, 0, 0, 0.06);
}

.info-box {
  background-color: var(--info-box-bg-color);
  padding: 1rem 1.25rem;
  border-left: 4px solid #ccc;
  border-radius: 8px;
  margin: 2rem 0;
  font-size: 0.95rem;
  line-height: 1.6;
  color: #2c2c2c;
}

hr {
  border: none;
  border-top: 1px solid #ccc;
  margin: 2rem 0;
  height: 0;
}
</style>

<div class="container">

<!-- Title -->

<div class="elevated-container" style="text-align: center;">

<h1>How to: Tweet Detox 🧹 </h1>

<h2>A step-by-step tutorial on how to clean up your digital X (formerly Twitter) footprint 👣</h2>

<h4> By: MJ  </h4>

<div class="ig-link">
  <a href="https://instagram.com/madeintanzania" target="_blank">📷 @madeintanzania</a>
</div>
</div>

<!-- Table of contents -->

<h2>🧭 Table of Contents</h2>

<ul>
  <li><a href="#introduction">🙋🏾‍♀️ Introduction</a></li>
  <li><a href="#legal-responsible-use">⚠️ Legal & Responsible Use</a></li>
  <li><a href="#what-youll-need">📖 What You’ll Need</a></li>
  <li><a href="#estimated-time-breakdown">⏳ Estimated Time Breakdown</a></li>
  <li><a href="#instructions">📝 Instructions</a>
    <ul>
      <li><a href="#step-1">Step 1: Download Necessary Files</a></li>
      <li><a href="#step-2">Step 2: Download Your Archive</a></li>
      <li><a href="#step-3">Step 3: Create an X Developer Account</a></li>
      <li><a href="#step-4">Step 4: Set Up Your API Keys</a></li>
      <li><a href="#step-5">Step 5: Install Python</a></li>
      <li><a href="#step-6">Step 6: Run the Script</a></li>
    </ul>
  </li>
  <li><a href="#mission-accomplished">🏆 Mission Accomplished!</a></li>
  <li><a href="#questions-comments-concerns">💬 Questions? Comments? Concerns?</a></li>
</ul>

<hr />

<!-- Introduction --> 

<h2 id="introduction">🙋🏾‍♀️ Introduction</h2>

<p>Hello 👋🏾 and welcome! My name is MJ, and I'm a Senior Software Engineer specialized in iOS 📲.</p>

<p>
With privacy getting harder to protect as technology advances, I've been working on cleaning up my digital footprint. One of my biggest missions? Deleting my old tweets. I've had my account since high school.. and I am <strong>embarazzed</strong> by the things I used to do and say! Like what was I even talking about? lol
</p>

<p>
I searched <strong>everywhere</strong> for tools to wipe them, but most were either broken, sketchy, or required payment. Just as I was about to give up, I had a lightbulb moment and realized: <strong>I can do it myself</strong> 💡
</p>

<p>
With a little research and effort, I put together a script that helped me delete over <strong>40,000 tweets 🎉</strong>. After sharing it with friends, I got a lot of requests to help others do the same. So, here we are.
</p>

<div class="info-box">
  <strong>This tutorial is beginner friendly.</strong> No tech experience is needed. This runs 100% local, so your data never leaves your machine. No logins, no hidden apps -- just you, your archive, and a script 😀
</div>

<p>Just follow my lead, and let me know if you run into issues. Let's get into it! 🚀</p>

<hr />

<!-- Legal & Responsible Use --> 

<h2 id="legal-responsible-use">⚠️ Legal & Responsible Use </h2>

Now.. before we start, I'd like to avoid any legal trouble 😅. So here's a quick disclaimer before we continue:

<div class="elevated-container">
<p><strong>This tool is for educational and personal use only.</strong></p>
<p>By using this script, you agree to the following:</p>

<ol>
  <li>You will use <strong>your own X (formerly Twitter) Developer App credentials</strong>.</li>
  <li>You will not share, sell, or distribute your API keys or access tokens.</li>
  <li>You will not use this tool to access or delete tweets from any account that is not your own.</li>
  <li>You are responsible for staying within X’s Developer Agreement and Rate Limit policies.</li>
</ol>

<p>This script is <strong>not affiliated with or endorsed by X/Twitter</strong>. Use at your own risk. The author assumes no liability for misuse, bans, or accidental tweet deletions.</p>

</div>

<strong>Long story short:</strong> This script is just for cleaning up your <strong>own</strong> account. Don’t share your keys with <strong><em>anyone</em></strong>, don't do anything <strong><em>shady</em></strong>, and you'll be fine. This tool is not affiliated with X/Twitter. It's just a personal tool to help you take control of your content

Great! Lets get started.. 🏃🏾‍♀️

<hr />

<!-- What You'll Need --> 

<h2 id="what-youll-need"> 📋 What You’ll Need </h2>

<ul>
  <li>💻 A computer (Mac or Windows)</li>
  <li>💬 A text editor of your choice (I recommend <a href="https://code.visualstudio.com" target="_blank">Visual Studio Code</a>, but any will do</li>
  <li>🛜 Access to the internet</li>
  <li>🙏🏾 Patience and perseverance</li>
</ul>

<p>
<strong>Note:</strong> I personally use a Mac, but I did my best to include Windows steps throughout this guide. Let me know if anything's unclear!
</p>

<hr />

<!-- Estimated Time Breakdown --> 

<h2 id="estimated-time-breakdown">⏳ Estimated Time Breakdown</h2>

<div class="info-box">
  <strong>⏱️ Total Active Time: ~30–45 mins</strong><br>  
  🧘🏾‍♀️ Plus passive wait time for archive downloads & the script to complete
</div>

<table>
  <thead>
    <tr>
      <th>Step</th>
      <th>Description</th>
      <th>Time</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>📁 Step 1</td>
      <td>Download necessary files</td>
      <td>3–5 min</td>
    </tr>
    <tr>
      <td>⬇️ Step 2</td>
      <td>Download your archive</td>
      <td>5 min + wait</td>
    </tr>
    <tr>
      <td>🛠 Step 3</td>
      <td>Create an X Developer Account</td>
      <td>10–15 min</td>
    </tr>
    <tr>
      <td>🔑 Step 4</td>
      <td>Setup your API Keys</td>
      <td>2–4 min</td>
    </tr>
    <tr>
      <td>🐍 Step 5</td>
      <td>Install Python</td>
      <td>3–10 min</td>
    </tr>
    <tr>
      <td>🏃🏾‍♀️ Step 6</td>
      <td>Run the script</td>
      <td>2–5 min (then let it run!)</td>
    </tr>
  </tbody>
</table>

<hr />

<!-- Instructions -->

<h2 id="instructions">📝 Instructions<h2>

<!-- Step 1 - Download Necessary Files -->

<h3 id="step-1">Step 1: Download Necessary Files</h3>

<div class="info-box">
  For the sake of simplicity -- and making the next steps easier -- I recommend saving all your files to your <strong>Desktop</strong>. This folder will be your working directory for the rest of the setup.
</div>

<ul>
  <li>
    Click below to download the setup files:
    <ul>
      <li><a href="resources/tweet-detox.zip">👉🏾 Download tweet-detox.zip</a></li>
    </ul>
  </li>
  <li>
    Depending on your computer's setup, your browser may either ask where to save the file, or automatically download it to your default folder (most likely <strong>Downloads</strong>).
    <ul>
      <li>In either case, move <code>tweet-detox.zip</code> to your <strong>Desktop</strong></li>
    </ul>
  </li>
  <li>
    If its not already unzipped:
    <ul>
      <li>On <strong>Mac</strong>: double-click the file</li>
      <li>On <strong>Windows</strong>: right-click → <strong>Extract All</strong></li>
    </ul>
  </li>
  <li>
    You should now see the unzipped <code>tweet-detox</code> folder on your Desktop ✅
  </li>
</ul>

<!-- Step 2: Download your archive -->

<h3 id="step-2">Step 2: Download your archive</h3>

Lets head on over to your internet browser 🔍

<!-- Request to download archive-->

<details>
  <summary>Request to download archive</summary>

  <ul>
    <li>Log in to your X account</li>
    <li>
      Go to <a href="https://x.com/settings/account" target="_blank">your account settings</a>
    </li>
    <li>Click <strong>Download an archive of your data</strong></li>
  </ul>

  <div class="image-div">
    <img src="images/step2-download-archive-settings.png" style="max-height: 465px;" />
  </div>

  <ul>
    <li>You will be asked to verify your password, then enter the code sent to your email</li>
    <li>Once you're in, you should see something like this:</li>
  </ul>

  <div class="image-div">
    <img src="images/step2-download-archive.png" style="max-height: 300px;" />
  </div>

  <ul>
    <li>
      Click <strong>Request archive</strong>, and wait for a confirmation email or notification.
      This can take anywhere from a few minutes to several hours ⏳
    </li>
  </ul>
</details>

<!-- Download your archive -->

<details>
  <summary>Download your archive</summary>

  <ul>
    <li>When you get the email, open the link (or revisit the account settings page)</li>
    <li>After verifying again, you'll be able to download your archive</li>
  </ul>

  <div class="image-div">
    <img src="images/step2-verification-email.png" style="max-height: 400px;" />
  </div>

  <ul>
    <li>Click <strong>Download archive</strong></li>
  </ul>

  <div class="image-div">
    <img src="images/step2-download-archive.png" style="max-height: 400px;" />
  </div>

  <ul>
    <li>
      To make the next steps easier, save the <code>.zip</code> file to the
      <code>tweet-detox</code> folder from Step 1. The downloaded archive should begin with
      <code>twitter-2025-...</code>
    </li>
  </ul>

  <div class="info-box">
    ⏳ This download may take some time, depending on how active your X account has been.
  </div>
</details>

<!-- Open your archive -->

<details>
  <summary>Open your archive</summary>

  <ul>
    <li>Unzip the file.</li>
    <li>Inside the unzipped folder, open the folder named <code>data</code>.</li>
    <li>
      The only file we need is <code>tweets.js</code> — this contains <strong>all</strong> your tweets and retweets.
    </li>
    <li>
      Copy <code>tweets.js</code> and paste it into the <strong>main</strong> <code>tweet-detox</code> folder (outside of the unzipped archive).
    </li>
  </ul>

  <div class="info-box">
    <strong>✨ Bonus:</strong> You can open <code>Your archive.html</code> for a visual overview of your entire account history. Double-clicking the file should open it in your browser.
  </div>
</details>

<!-- Step 3: Create an X Developer Account -->

<h3 id="step-3">Step 3: Create an X Developer Account</h3>

<p>Okay, this part's the longest to actively get through, but <strong>I promise, it's not hard</strong>. Take your time, and follow along. You'll be done in no time! 🛠️✨</p>

<!-- Create a developer account -->

<details>
<summary>Create a developer account</summary>

<p>In order to run the tweet deletion script, you'll need a set of API credentials. This means creating a <strong>developer account</strong> with X (formerly twitter). This is free, and you only need basic access.</p>

<ul>
  <li>Go to the <a href="https://developer.x.com/en/portal/dashboard" target="_blank">X Developer Portal</a></li>
  <li>You'll be asked to log in with your X account (if you aren't already)</li>
  <li>If you land on a marketing/landing page, click <strong>Developer Portal</strong> in the top right</li>
</ul>

<div class="image-div">
  <img src="images/step3-landing-page.png" style="max-height: 400px;" />
</div>

<ul>
  <li>You'll see a screen like this, click <strong>Sign up for Free Account</strong></li>
</ul>

<div class="image-div">
  <img src="images/step3-developer-portal.png" style="max-height: 400px;" />
</div>

<ul>
  <li>You'll be prompted to describe how you plan to use the API. This helps ensures you're not using it for anything shady</li>
</ul>

<div class="image-div">
  <img src="images/step3-developer-agreement-policy.png" style="max-height: 400px;" />
</div>

<ul>
  <li>The description needs to be at least 250 characters, stating how exactly you plan to use the API. This is what i wrote (w/ the help of ChatGPT):</li>
</ul>

<div class="elevated-container">
  <em>
    I am using a personal script to delete old tweets from my own account as part of cleaning up my digital footprint.<br>
    I will only use my own X Developer credentials, and won't share or sell them<br>
    I will not access or delete tweets from any account that is not my own.<br>
    This script is for personal use only, and complies with X's policies.
  </em>
</div>

<ul>
  <li>Once you're done, and agree to all the terms, click <strong>Submit</strong>. Approval is usually instant, and you'll land in the Developer Portal Dashboard</li>
</ul>
</details>

<!-- Generate authentication keys -->

<details>
<summary>Generate authentication keys</summary>

<ul>
  <li>On the landing page, you should see a default project and app already created (basic plan only allows one). Click the <strong>gear icon ⚙️</strong> next to your App to configure authentication</li>
</ul>

<div class="image-div">
  <img src="images/step3-project-app.png" style="max-height: 400px;" />
</div>

<ul>
  <li>On the app details page, click <strong>Set up</strong> under <strong>User authentication settings</strong></li>
</ul>

<div class="image-div">
  <img src="images/step3-auth-settings.png" style="max-height: 400px;" />
</div>

<ul>
  <li>Fill in these details <strong>exactly</strong> as shown:</li>
</ul>

<div class="image-div">
  <img src="images/step3-user-auth-settings.png" style="max-height: 400px;" />
</div>

<ul>
  <li>
  Under <strong>App Info</strong>, enter the following:
    <table>
    <thead>
        <tr>
        <th><strong>Field</strong></th>
        <th><strong>Value</strong></th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td>Callback URL</td>
        <td><code>https://example.com/callback</code></td>
        </tr>
        <tr>
        <td>Website URL</td>
        <td><code>https://example.com</code></td>
        </tr>
    </tbody>
    </table>
  </li>
</ul>

<div class="info-box">
  <strong>Wait, why does it say example.com?</strong><br>
  X (Twitter) requires valid-looking URLs during setup, but we’re not hosting a real website.<br>
  <code>https://example.com</code> just makes setup work — nothing gets sent there 👍🏾
</div>

<ul>
  <li>When prompted, click <strong>Yes</strong> to confirm your changes</li>
</ul>

<div class="image-div">
  <img src="images/step3-changing-permissions.png" style="max-height: 400px;" />
</div>

<ul>
  <li>Once setup is complete, you'll be shown your client key and token.</li>
</ul>

<div class="info-box">
    <strong>🚨 Save these somewhere safe</strong> — they won’t be shown again! 🚨
</div>
</details>

<!-- Create more keys and tokens -->

<details>
<summary>Create more keys and tokens</summary>

<ul>
  <li>Navigate back to the app details page, click on <strong><em>Keys and Tokens</em></strong></li>
</ul>

<ul>
  <li>Under <strong>Consumer Keys</strong>:
    <ul>
      <li>Click <strong>Regenerate</strong></li>
      <li>This will give you both your <strong>API key</strong> and <strong>Secret key</strong></li>
      <li>Save both in the same secure place you used for the authentication keys</li>
    </ul>
  </li>
</ul>

<ul>
  <li>Under <strong>Authentication Tokens</strong>:
    <ul>
      <li>Click <strong>Regenerate</strong> next to "Access Token and Secret"</li>
      <li>This will generate the <strong>Access token</strong> and <strong>Access token secret</strong> key</li>
      <li>Save these as well!!</li>
    </ul>
  </li>
</ul>
</details>

<!-- Step 4: Set up your API keys -->

<h3 id="step-4">Step 4: Set up your API keys</h3>

<p>Now that you've got your credentials, it's time to put them to use.</p>

<ul>
  <li>Open your <code>tweet-detox</code> folder on your <strong>Desktop</strong></li>
  <li>Locate the file named <code>env-template.txt</code></li>
  <li>Right-click the file and choose <strong>Open With</strong> → your preferred text editor (Notepad, TextEdit, VS Code, etc.)</li>
  <li>Replace each instance of <code>your_api_key_here</code> with the actual credentials you saved in the previous step</li>
  <li>Save the file, and close the editor</li>
</ul>

<!-- Step 5: Install Python -->

<h3 id="step-5">Step 5: Install Python</h3>

<details>
<summary>Check Python Version</summary>

<ul>
  <li>Open your terminal:
    <ul>
      <li><strong>Mac:</strong> Open Terminal (press <code>Command + Space</code> and search for <strong>Terminal</strong>)</li>
      <li><strong>Windows:</strong> Use Command Prompt or Windows Terminal</li>
    </ul>
  </li>

  <li>Type or copy and paste the following:</li>
</ul>

<pre><code>python --version</code></pre>

<p>or if that doesn't work:</p>

<pre><code>python3 --version</code></pre>

<p>If you see something like <code>Python 3.x.x</code>, you’re all set! Skip to the next step 🐍🎉</p>

</details>

<details>
<summary>Don't have it? here's how to install</summary>

<ul>
  <li>Go to <a href="https://www.python.org/downloads/" target="_blank">python.org/downloads</a></li>
  <li>Click <strong>Download Python 3.X.X</strong></li>
  <li>Run the installer and follow the steps:
    <ul>
      <li>⚠️ On <strong>Windows</strong>, be sure to check <strong>Add Python to PATH</strong> before clicking install!</li>
    </ul>
  </li>
  <li>Once done, try running the version command again to confirm it worked</li>
  <li>If this doesn't work, try restarting the terminal and try confirming again</li>
</ul>

</details>

<!-- Step 6: Run the Script -->

<h3 id="step-6">Step 6: Run the Script</h3>

<details>
<summary>Prepare Your tweet.js file</summary>
<ul>
  <li>
    You may need to update your <code>tweets.js</code> file before the script can use it:
    <ul>
      <li>In the <code>tweet-detox</code> folder, right-click <code>tweets.js</code> → <strong>Open with</strong> → select your editor of choice.</li>
      <li>If you see <code>window.YTD.tweet.part0 = </code> at the top, <strong>delete that line</strong>.</li>
      <li>Make sure the file:
        <ul>
          <li>Starts with <code>[</code></li>
          <li>Ends with <code>]</code></li>
        </ul>
      </li> 
    </ul>
  </li>
</ul>
</details>

<details>
<summary>Update Your Desired Date Range</summary>
<p>
  Inside the <code>tweet-detox.py</code> script, there’s a section near the top where you can customize the time frame of tweets you want to delete
</p>

<ul>
  <li>Open the file <code>tweet-detox.py</code> in your text editor</li>
  <li>Scroll to the section that looks like this:
    <pre><code># Optional: Set the date range for tweets you want to delete
# Use the format: YYYY, M, D (Year, Month, Day)
# If you leave one as None, it will just use the other limit
MIN_DATE = datetime(2020, 6, 8)
MAX_DATE = datetime(2022, 6, 8)</code></pre>
  </li>
  <li>Edit the <code>MIN_DATE</code> and <code>MAX_DATE</code> values to reflect your desired time frame
    <ul>
      <li>To delete all tweets before a certain date, set <code>MAX_DATE</code> and leave <code>MIN_DATE = None</code></li>
      <li>To delete all tweets after a certain date, set <code>MIN_DATE</code> and leave <code>MAX_DATE = None</code></li>
      <li>To delete everything ever: set both to <code>None</code></li>
    </ul>
  </li>
</ul>

<div class="info-box">
💡 <strong>Example:</strong>  
To delete tweets from 2021 and later, use:
<pre><code>MIN_DATE = datetime(2021, 1, 1)
MAX_DATE = None</code></pre>
</div>

<p>Once you've made your edits, save the file and you're good to go!</p>
</details>

<details>
<summary>Rename <code>env-template.txt</code> to <code>.env</code></summary>

<p>We need to rename the file so the script can find your credentials.</p>

<ul>
  <li>Open your terminal</li>
  <li>If you followed Step 1 as recommended, navigate to the project folder:
    <pre><code>cd ~/Desktop/tweet-detox</code></pre>
  </li>
  <li>Rename the file:
    <pre><code>mv env-template.txt .env</code></pre>
  </li>
</ul>

<div class="info-box">
  ⚠️ Don’t be alarmed if the file seems to disappear after renaming — files starting with a <code>.</code> are hidden by default on some systems.<br /><br />
  <strong>To make it visible:</strong>
  <ul>
    <li><strong>Mac:</strong> Press <code>Command + Shift + .</code> in Finder to toggle hidden files.</li>
    <li><strong>Windows:</strong> In File Explorer, go to <strong>View</strong> → check <strong>Hidden items</strong>.</li>
  </ul>
</div>

</details>

<details>
<summary>Run your script</summary>

<p>Cool, so now we're ready to run things 😎</p>

<ul>
<li>To run the script, type or copy and paste the following:
  <pre><code>python tweet-detox.py</code></pre>
</li>
<li>If that doesn't work, try:
 <pre><code>python3 tweet-detox.py</code></pre>
</li>
<li>
This will kick off the deletion workflow, and start wiping those old tweets out for you 🧹
</li>
</ul>
<div class="info-box">
  <strong>Heads up:</strong><br />
  This step can take a while, especially if you have a lot of tweets. I had ~40,000 I wanted to delete, and it took a little over 24 hours to fully finish
  <br /><br />
  So just:
  <ul>
    <li>Leave your terminal open</li>
    <li>Keep your computer from sleeping (I use the <a href="https://apps.apple.com/us/app/jolt-of-caffeine/id1437130425?mt=12" target="_blank">Jolt of Caffeine</a> app)</li>
    <li>Let the script do its thing 👌🏾</li>
  </ul>
</div>
</details>

<hr />

<!-- Finale -->

<h2 id="mission-accomplished">🏆 That’s It!</h2>

<p>Congrats on making it this far 🥳🎉. Once it's done, your old tweets are wiped, and your timeline is brand new.</p>

<h2 id="questions-comments-concerns">💬 Questions? Comments? Concerns?</h2>

<p>
This is an open-source tool. All code is available for you to view yourself. Nothing is hidden, nothing is sent to me, and no data ever leaves your machine.
</p>

<p>
Got feedback? Need help? Feel free to reach out to me on
<a href="https://instagram.com/madeintanzania" target="_blank">Instagram</a> ☺️
</p>
</div>