# OpenSide

**A free Windows AI assistant: type what you need in a chat, and the AI does it in the Chrome or Edge you already use — from searching to clicking and typing.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/openside?lang=en)

![OpenSide screen](images/openside-en.png)

## Overview

A lot of web work takes many clicks but little thought: collecting prices from several shops into a table, filling in the same form again and again, posting to a blog, digging through a mailbox for the right email.

OpenSide lets you hand that work over in one line of chat. Type the job into the "What can I do for you?" box, and the AI opens sites in your browser, reads the pages, clicks buttons and types text until the job is done, then tells you the result in a few sentences. Data it collects can come back as an Excel file.

It does not use a separate browser — it works **in the Chrome or Edge you are already using**. Sites you are signed in to need no new sign-in, and because the AI works in its own tab, you can keep using your other tabs meanwhile. Link Telegram and you can give it jobs and get results from your phone while you are out.

For the AI itself, sign in with a ChatGPT account you already have, or enter a Claude, OpenAI or Gemini API key.

## Features

- **Web tasks by chat** — describe the job; the AI searches, clicks, types and moves between pages for you, then reports back.
- **Your browser, your sign-ins** — it attaches to the Chrome or Edge you use, so sites you are signed in to work right away.
- **Repetitive work** — hand over jobs that repeat, like filling in forms or collecting data across many pages, in one go.
- **Save to Excel** — collected data comes as an Excel (.xlsx) file, or as CSV if you ask.
- **Telegram remote** — send jobs from Telegram on your phone and get answers and files back. No need to create a bot yourself.
- **Attach files** — attach image, text or CSV files for the AI to read, or have it upload them to a site.
- **Remembers what you saw** — when turned on, it records the pages you read and the apps you use, and draws on them for questions like "that article I read yesterday".
- **Good at popular sites** — writing posts on Naver Blog, Tistory and Blogger, Gmail, Google Docs and Sheets, Notion, Slack, YouTube, Naver Real Estate and more are handled with site-specific methods that are faster and more accurate.
- **Several AI accounts** — register a ChatGPT (Codex) sign-in and Claude, OpenAI and Gemini API keys, and switch between them right in the chat.
- **Dark mode · 9 languages** — Korean, English, Japanese, Chinese, Russian, Italian, French, Spanish and Arabic.

## Download / Installation

| Edition | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/openside?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/openside?lang=en&nosetup) |

The installer starts OpenSide as soon as installation finishes. For the portable edition, unzip it and run `OpenSide.exe`. Both editions have the same features; only the initial value of **Run at startup** differs — on for the installer, off for the portable edition.

## Usage

### Getting started

1. Run OpenSide. On the first run, the connection settings page opens in your browser (Chrome or Edge) by itself.
2. On that page, turn on the **Remote debugging** checkbox. If the page did not open, type `chrome://inspect/#remote-debugging` (for Edge, `edge://inspect/#remote-debugging`) in the browser's address bar.
3. When the browser shows a connection request, click **Allow**. You only need to do this setup once.
4. **Preferences** then opens at **Account**. Click **Add**, choose the AI to use (for example **Sign in to Codex**), and sign in on the page that opens in your browser. When you see "Sign-in complete", close that window and return to OpenSide.
5. Type a job in the chat box ("What can I do for you?") and press **Enter**. For example: "Tell me the titles of the 5 latest notices on kilho.net".
6. While the AI works, its progress appears line by line. When it finishes, the result appears as an answer and the progress folds into a single "Ns of work" line, which you can click to expand again.

### Screen layout

| Element | What it does |
|---|---|
| Chat title | The title of the current chat. It is set from your first message; click it to edit (**Enter** saves · **Esc** cancels) |
| **Recent sessions** | Your past chats (the latest 15). Pick one to continue it |
| **New chat** | Starts a new chat |
| **Settings** | Opens the **Preferences** window |
| Paperclip (**Attach files**) | Attaches files to your message. Attached files appear under the input box; remove one with × |
| Input box · **Send** | Type the job and send it. While the AI works, **Send** turns into **Stop** |
| **Remote control** icon | Turns the Telegram remote on and off. Green when on |
| Eye icon (**Context**) | Shown only while page recording is on. Click to pause or resume recording |
| Usage ring | Usage of a **Sign in to Codex** account. Hover to see how much is left |
| Account · model · reasoning level | Choose the AI account, the model, and how deeply it thinks for this chat |

### Tips for common situations

**Collect information from several sites into a table**
Say what to collect and how you want it, for example "Find the price of laptop model A at three shops and put it in Excel". When it is done, a **⬇ Download** card appears in the chat. Click it to choose where to save (the Downloads folder at first); after saving, **Open file** and **Open folder** open it right away. The Excel file keeps values with leading zeros, such as `007` or phone numbers, intact. If you need a file for another program, say "as CSV" — it is written so that non-English text displays correctly.

**Fill in the same form many times**
Say something like "Submit an application for each person on this list". The AI fills the form's fields, checkboxes and dropdowns in one go, and checks that the result appears before moving on, so it never presses a submit button twice. If the list is in a file, attach the file.

**When you only want it to look, and when you want it done**
If you say "compare" or "just write a draft", the AI will not do anything that cannot be undone, such as sending, paying, deleting or publishing. If you say "send it" or "order it", it carries the job through to the final button without asking again. It is best to state clearly in your message how far it should go.

**Post to a blog**
Say something like "Write this up as a Naver Blog post and publish it". On Naver Blog, Tistory and Blogger, the title, body, subheadings, images and tags go in using methods suited to each site. Attach any images you want to include.

**Work with mail, documents and work tools**
Say things like "Find last week's quote email in Gmail and summarize it", "Read the values in column B of my Google Sheet", "Add today's notes to the meeting page in Notion", or "Tell me the latest posts in the Slack #announcements channel". It works with the accounts already signed in to your browser. If several Google accounts are signed in, say which one and it will work in that account.

**Research on YouTube, X and LinkedIn**
Say things like "Summarize this YouTube video's transcript", "Sum up the reactions in this video's comments", "Collect recent posts on this topic from X", or "Find this company's job openings on LinkedIn".

**Collect real estate listings**
Say something like "Put the jeonse listings for ○○ Apartment on Naver Real Estate into Excel", and it turns the listings into a table.

**Find images**
Say something like "Find 10 photos of ○○ and collect their addresses", and it gathers image URLs from image search results.

**Use other tabs while it works**
The AI only moves in the tab it is working in, so you can keep doing your own work in other tabs of the same browser. Its tab keeps running even in the background, just as if it were in front. If you give the next job in the same chat, it continues in the tab it was working in, even if you are looking at another tab. A new chat starts on the tab you are looking at.

**Tabs it opens and your tabs**
The AI opens a new tab only when it needs two pages at once, and closes the tabs it opened before it answers. It does not close tabs you opened. If you want your tabs tidied, ask directly, for example "Close all kilho.net tabs".

**When a verification code or bank app approval is needed**
When a step needs a person — a code sent to your phone, approval in a bank app, a text CAPTCHA — the AI brings that tab to the front and tells you in one line what to do. Do it in the browser, or type the code into the chat box, and the AI carries on. The AI ticks "I'm not a robot" checkboxes itself and hands over only when a pick-the-pictures challenge appears. If signing up needs a link or code sent by email, and Gmail is signed in to the browser, the AI opens the mailbox and finds it.

**Add something while it works**
You can type into the chat box even while the AI is working. Your message goes straight to the task in progress. Use it to change direction ("write the prices in won") or to answer something it asked. To make it stop, click **Stop**.

**Have it read files on your PC, or upload them to a site**
Attach files with the paperclip and send them, and the AI reads them. It looks at the content of images (png, jpg, gif, webp) and reads and uses text and CSV files. You can attach several at once, and the original files are never touched. Say something like "Attach the photo I sent to a post on this board", and the AI handles the site's file upload window too.

**Let it always read a set folder**
If attaching every time is a chore, add the folder under **Preferences** → **Files** → **Folders the AI may read** (**Add folder...**). Then you can say things like "Using the customer list in my data folder, …". The AI only reads that folder and never writes to it. Add only the folders you need.

**Find a page you saw before**
Turn on **Record pages I read and apps I use** under **Preferences** → **Context**, and OpenSide records the text of pages you read and the app windows you used. Then you can say things like "Summarize the investment article I read yesterday again" or "Compare the pros and cons of the hotels I looked at earlier". Records are kept for 30 days, and pages with a password field are not recorded. List sites and apps not to record, separated by commas (e.g. `bank.com, kakaotalk.exe`). To pause recording, click the eye icon in the chat screen; to erase everything, click **Delete all**. This feature is off at first.

**Find a site you visited before**
Say something like "Open that flower shop site I visited last time", and it finds it in your browser history and opens it.

**Give it jobs from your phone (Telegram)**
1. Under **Preferences** → **Remote**, click **Link now**. A QR code and a link code appear, valid for 10 minutes.
2. Scan the QR code with your phone's camera. When Telegram opens, tap **Start**. If Telegram is installed on your PC, you can click **Open on this PC** instead.
3. When Telegram shows a message that it is connected, you are done. Now send a job as a text message in Telegram, and OpenSide on your PC does it and sends the answer back.

Files it makes and requests such as "please enter the verification code" also come to your phone. Reply with the code in Telegram and it goes to the task in progress. If an answer is long, the start comes as a message and the full text as a file. Telegram only accepts text, so send words rather than photos. OpenSide must be running on your PC to work, so turning on **Run at startup** helps when you use the remote. To turn the remote off for a while, click the **Remote control** icon in the chat screen; to disconnect completely, click **Unlink**.

**Use several AI accounts**
Under **Preferences** → **Account**, click **Add** to see the kinds you can choose.

| Kind | How it works |
|---|---|
| **Sign in to Codex** | Sign in with a ChatGPT account |
| **Claude API key...** · **Gemini API key...** | Enter an API key |
| **OpenAI API key...** | Enter an API key and a **Base URL (.../v1)**. Change the address to use other services that work the same way as OpenAI |

When you save an API key account, it fetches the model list right away to check it. Choose the account for new chats with **Set default**, and double-click an account to rename it. During a chat, you can switch the account, model and reasoning level right at the bottom of the chat screen. A higher reasoning level thinks more deeply; a lower one answers faster.

**See how much usage is left**
With a **Sign in to Codex** account, a usage ring appears at the bottom of the chat screen. It fills up as you use more; hover over it to see what is left for each period. When it is nearly used up, switch to another account.

**Continue a past chat**
Click **Recent sessions** to see your latest 15 chats with when you last used them. Pick one and keep going. To give it a clearer title, click the title at the top.

**What it remembers on its own**
Each time it finishes a job, the AI keeps confirmed things — how to use a site, facts you told it — and uses them in later chats. The more often you give it jobs on the same site, the less it fumbles.

**Keep it running after closing the window**
Clicking × on the window does not quit; OpenSide moves to the notification area (tray). Click the tray icon to bring the window back. To quit completely, right-click the tray icon and choose **Quit**. **Run at boot** in the same menu is the same setting as **Run at startup** in **Preferences**; with it on, OpenSide starts quietly in the tray when Windows starts. Only one copy of OpenSide runs; running it again brings the open window to the front.

**Keep the OpenSide window in front**
To keep OpenSide beside your browser while you watch, set **Always on top** to **On** under **Preferences** → **General**. The window position and size are remembered, so it opens in the same place next time.

**Chrome or Edge — which one it works in**
OpenSide works in the browser where **Remote debugging** is turned on. If both have it on, it uses the Windows default browser first. To have it work in the other one, turn it on only in that browser.

**After you restart the browser**
If a connection is needed, OpenSide shows the **A browser connection is needed** window with the steps in order. Follow them and click **Connect**. Clicking the address in that window copies it, so you can paste it into the address bar.

## Configuration

Click **Settings** to open the **Preferences** window. Changes take effect immediately.

| Tab | Items |
|---|---|
| **General** | **Always on top** · **Theme** (Auto · Light · Dark) · **Language** (Auto or one of 9 languages) · **Run at startup** |
| **Account** | Add, delete and sign in to AI accounts · choose the default account |
| **Remote** | Link or unlink Telegram |
| **Context** | Turn page and app recording on · pause · sites and apps not to record · delete all |
| **Files** | Folders the AI may read |

When **Language** is **Auto**, OpenSide follows the Windows display language. Choosing Arabic switches the screen to right-to-left. The AI's progress lines and answers follow the language of your message. When **Theme** is **Auto**, it follows the Windows app mode (light or dark).

## Requirements

- Windows 10 · Windows 11 (64-bit)
- Google Chrome or Microsoft Edge
- A ChatGPT account, or a Claude, OpenAI or Gemini API key
- An internet connection

## Updates

To keep things secure and avoid false antivirus alerts, OpenSide does **not** update itself. When it starts, it checks for a new version and lets you know; if you choose to get it, it opens the download page and closes the program. New versions are released manually after internal verification and announced on the [OpenSide page](https://kilho.net/openside). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

## License

OpenSide is **freeware**. Use it anywhere — at the office, at home, in government offices or at school — free of charge and without restrictions, and redistribute it freely. AI usage costs follow the plan of your own AI account or API key.

## Links

- Website: <https://kilho.net/openside>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
