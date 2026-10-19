# Start here: build your app with Claude

You describe what you want in plain English. Claude builds it, checks it in a browser, and gives you a link you can open on your phone and share. When your team is happy with a change, it goes live at your app's permanent address.

**You will need:**
- a GitHub account, invited to your team's repository by your instructor;
- the **Claude account provided for this event** (look for the invitation email from Claude). Use it instead of any personal Claude account: your team's setup only exists there.

## One-time setup (about 10 minutes)

1. **Accept the GitHub invitation** your instructor sent (check your email, or github.com/notifications).
2. **Join the here.now workspace.** Open the invitation email from here.now to the **rossbusinesstech** workspace and sign in with **the same email address it was sent to**. Signing in with a new address creates your here.now account; signing in with a *different* address creates a separate, empty account that isn't in the workspace.
3. **Accept the Claude invitation**, then go to **claude.ai/code** and sign in with that event account.
4. **Follow Claude's first-time steps:**
   - If asked, connect your GitHub account and allow access to your team's repository.
   - If you see a form called **Create your first cloud environment**, keep everything as it is and click **Create & finish**.
5. **Check the environment.** On the new-session screen, the first button in the row under the message box shows an environment name. It should say **Business+Tech**. If it doesn't, click it and choose **Business+Tech** under *Organization*.
6. Select your team's repository.

## Every time you work on the app

**Your team's prompts are in `PROMPTS.md`.** Start with *Kickoff* (one person), then everyone uses the others.

1. Open **claude.ai/code**, check the environment button under the message box says **Business+Tech**, select your team's repository, and start a new session.
2. Tell Claude what you want. Be specific about *who* uses it and *what they should be able to do*. For example:
   - *"This is a booking page for our campus coffee cart. Customers pick a pickup time and enter their name. Make it look friendly and work well on phones."*
   - *"Add a page where people can vote on next week's special. Show the results as a bar chart."*
   - *"The button on the home page is hard to see. Make it bigger and use our brand color, maize."*
3. The first time Claude publishes in a session, it will ask **which email you use with here.now** (the one from step 2) and then for a **code** that here.now emails you. Paste the code into the chat. (Never paste passwords or keys, only this code.)
4. Claude will build it, test it, and give you a **test link**. Open it on your phone. Tell Claude what to change.
5. Repeat until you like it.

**About test links:** they expire after 7 days (or 24 hours if Claude published without signing you in to here.now). You don't need to keep them: the team's live app is permanent.

## Sharing with your team and going live

1. When you're happy, tell Claude: **"This is ready. Open a pull request for the team."**
2. Claude puts your **test link** in the pull request. Send the pull request to a teammate.
3. A teammate opens it on GitHub, tries the link on their phone, clicks **Files changed > Review changes > Approve**, then **Merge**.
4. A few minutes later, the change is live at your app's permanent address (your instructor will give it to you).

Several of you can work at the same time, each in your own session. Pull requests are how everyone's work comes together. If two people changed the same thing, Claude will combine them and tell you what it did.

## Rules

- **Your team's repository is public.** Anyone on the internet can read your code, your commit messages, and your GitHub username.
- **Use made-up data only.** No real names, emails, grades or other personal information.
- **Never paste passwords or API keys into the chat or the app.** If your idea needs a paid service (like AI features), ask your instructor.
- Don't ask Claude to change the files in `scripts/`, `.github/`, `.claude/` or `admin/`. Those keep the publishing working.

## If something goes wrong

| What you see | What to do |
| --- | --- |
| Claude says you're "not a member" of the workspace | Accept the here.now invitation email (or ask your instructor to invite the email you used), then tell Claude "check my here.now sign-in again". |
| **Business+Tech** isn't in the environment list, or you can't find your team's repository | You're probably signed in to a personal Claude account. Sign out and sign back in with the event account from the invitation email. |
| Claude says the environment setup didn't run, or here.now is blocked | Start a **new** session and make sure the environment button says **Business+Tech** *before* you send your first message. |
| The test link shows an old version | Wait a minute and refresh. Still old? Ask Claude to publish the preview again. |
| The pull request says "checks failed" | Open your Claude session and say "the pull request checks failed, please fix them." |
| Anything else | Ask Claude to explain the problem in plain words, then contact your instructor with that explanation. |

