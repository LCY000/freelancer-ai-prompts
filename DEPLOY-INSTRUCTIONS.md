# Deploy in 5 minutes — GitHub Pages (free hosting)

## Before you start
1. Convert `product/50-claude-prompts-for-freelancers.md` to PDF (paste into Google Docs → File → Download → PDF)
2. Upload the PDF to Gumroad.com and get your product URL
3. Replace PAYPAL_LINK_HERE in index.html with your Gumroad or PayPal.me link

## Deploy steps

```bash
# 1. Create a new GitHub repo at github.com/new
#    Name it: freelancer-prompts (or any name)
#    Set it to Public
#    Do NOT initialize with README

# 2. In terminal, from this folder:
cd /Users/cyouuu/Desktop/work/makemoney/github-pages-deploy

git init
git add .
git commit -m "Initial landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/freelancer-prompts.git
git push -u origin main
```

## Enable GitHub Pages
1. Go to your repo on GitHub
2. Settings → Pages
3. Source: Deploy from branch → main → / (root)
4. Save

Your live URL will be: **https://YOUR_USERNAME.github.io/freelancer-prompts**
(Takes 1–2 minutes to go live)

## Share the URL
Post this on Reddit (r/freelance, r/ChatGPT, r/ClaudeAI):

---
**Title:** I made 50 AI prompts for freelancers — here are 3 free samples

**Body:**
Been freelancing for a while and these are the Claude/ChatGPT prompts I use constantly.

Free samples:

**Handling "your rate is too high":**
> A client said my rate of $[amount] is too high. Help me write a response that doesn't apologize, reframes cost as ROI, offers one alternative (smaller scope, not lower rate), and keeps the door open. Tone: confident, not defensive. Under 120 words.

**Scope creep response:**
> A client is asking me to do [extra task] outside our agreement. Write a friendly but firm email that acknowledges the request, explains it's outside scope, and gives them two options: pay for extra work at $[rate], or add it to a future project. Under 100 words.

**LinkedIn post formula:**
> Write a LinkedIn post about [topic]. Line 1: bold specific hook. Lines 2-4: the story. Line 5: counterintuitive takeaway. Line 6: question to drive comments. No buzzwords. Under 200 words.

I put together 50 of these covering client communication, content, operations, productivity, and business strategy: [YOUR_GITHUB_URL]

It's $7. Feel free to save the free ones above either way.
---
