# Mastodon Moderation Run-Down

This is a quick guide to the tools currently available to Mastodon moderators. It is not intended to tell you *how* to use the tools, only what they are and what they do.

In your moderator account's Preferences page, you'll have a section called Moderation that gives you access to the moderator tools. Primary among these are the **[Mod Audit](#mod-audit)**, **[Reports](#reports)**, and **[Accounts](#accounts)**.

## Audit Log

`https://<your server>/admin/action_logs`

The Mod Audit shows you every action any moderator has taken, in reverse chronological order. It's handy if you need to figure out which of your site's moderators took a particular action. If you're the only moderator on your site, you can usually safely ignore this tool.

## Reports

`https://<your server>/admin/reports`

The Reports queue is typically where you'll spend most of your moderation time. It's a list of reports made to or from your instance. This page defaults to showing unresolved reports, but you can toggle over to resolved reports at the top of the page.

When you view an individual report, you can see who filed the report and whom the report is about. You can also see the text of the report - if the reporting user filled that out; they don't always - and any toots associated with the report.

*Reports that come from other instances are **anonymized**: they do not have the username of the reporting user attached to them. This is a deliberate choice in order to protect the privacy of non-local users who want to report local users, in order to prevent bad actors who happen to be instance admins from harassing users who report people on their instances. When you see a report from another instance, you will only see the name of the instance from which the report was issued. If you need more information, contact the listed administrator of that instance (if there is one) and ask what’s going on.*

An individual report gives you a bunch of potential actions. Some of them have the same name but different functions depending on whether the reported user is a local user or a remote user.

**Resolve report:** This will just mark the report resolved, with no note left or action taken against the reported user.

**Resolve with note:** This resolves the report, but lets you leave a note saying why you resolved it without taking further action.

**Add note:** Use this if you want to leave a note but don't want to resolve the report outright. If you want to leave the report open because you want a second opinion, here's where to leave your notes.

The behavior of the next set of tools varies depending on whether the user is local (on your own instance) or remote (on another instance).

### For Local Users

**TOOT-LEVEL ACTIONS**

These are available if the reporting user has included any toots with the report.

**Add sensitive-content overlay to toot:** Select one or more toots using the checkboxes to the left, then click Mark as sensitive at the top of the list of toots. This will add the “Sensitive Content (18+)” overlay to any images attached to the toot. It will not add a content warning to the toot. (We don’t currently have a way to do that.)

**Delete individual toot:** Select one or more toots using the checkboxes to the left, then click Delete at the top of the list of toots. This will remove the toot from your local database. This does request that other servers delete the toot as well. They may not respect that request!

**ACCOUNT-LEVEL ACTIONS**

**Warn user:** This does not do anything to the user’s account, but will send them a warning by email.

**Disable login:** This will not remove any information from the user’s account, but will log them out immediately and prevent them from logging in.

**Silence user:** This allows the user to continue logging in and posting, but prevents the user from posting to the local timeline and from appearing in the notifications of users who aren't following the user. Silencing someone doesn't prevent them from posting - but of the people on your local instance, only the people who follow them will see it. **However, their posts will still federate out normally.**

**Suspend user:** **This is a destructive action. Don’t use this unless you mean it.** This will delete all the data from the user's account. All their followers, all the people they're following, all their posts, all their media. 

All four account-level actions (Warn, Disable, Silence, and Suspend) allow you to send a note to the reported user telling them what’s going on. You can create pre-written notes for common report reasons, and you can add your own custom note at the bottom even if you've selected a prefab note. If you have multiple moderators on your instance, the user is not told which moderator sent the note or took the action.

### For Remote Users

**Add sensitive-content overlay to toot:** Select one or more toots using the checkboxes to the left, then click Mark as sensitive at the top of the list of toots. This will add the “Sensitive Content (18+)” overlay to any images attached to the toot. It will not add a content warning to the toot. (There isn't currently a way to do that.) This only affects your instance's copy of the toot. Copies on other instances are unaffected.

**Delete individual toot:** Select one or more toots using the checkboxes to the left, then click Delete at the top of the list of toots. This will remove the toot from your database, but it will not affect other instances’ copies of the toot, and it can be re-added to your instance if someone else on your instance boosts it or interacts with it.

**Silence user:** This will prevent the user's posts from appearing on your federated timeline and in the notifications of people who don't follow them. Anyone who follows the user can still see their posts and interact with them.

**Suspend user:** This will forcibly remove the user from all of your instance's timelines. It will force anyone on your instance who is following that user to unfollow them, and prevent them from ever showing up to anyone on your instance. You can safely be a little freer with this option than with a local suspension, since you can un-suspend a remote user and their information will start federating across again.

A note: Silencing or suspending a user from the reports interface will also automatically resolve all other reports about that user.

## Accounts

`https://<your server>/admin/accounts`

The Accounts page is where you can get information on specific accounts. You have the option of searching for users based on their username, display name, email, or IP, or, for remote users, their domain (the URL of their server). You can also filter by user status (Active, Silenced, or Suspended) and by user rank (all users or just moderators and admins). *By design, any search for staff on a remote instance will come up empty.*

You get different information depending on whether an account is local or remote. On each account's page you can also see how many reports they've filed and how many have been filed against them. On an individual account page, you can take several actions, listed in order:

**Remove Avatar** and **Remove Header** are self-explanatory. They will only appear if the user has an avatar or a header set, respectively.

**Change Email:** This changes the email address associated with an account. **This is a dangerous action since the email address is used to log in.** 

**Disable Login:** Logs the user out and prevents them from logging in again. This is useful as a holding action while you debate more serious action or wait for a response from the user. It’s described in more detail below.

**Silence:** Prevents a user’s posts from reaching your instance's local timeline. Described in more detail above.

**Suspend:** This destroys the user's account! It’s described in more detail above. 

**Reset Password:** Sends the user a password-reset email. Use this if you believe an account has been compromised or if the user has requested it.

**Leave Note:** This lets you leave a note on the account directly, not associated with a given report. This is handy for making sure that future moderators know your thoughts.

### Pending Accounts

`https://<your server>/admin/pending_accounts`

If you have account approval turned on, the Accounts page will appear to have a fourth moderation filter: **Pending**, which will also display the number of accounts currently awaiting approval. Clicking on that will take you to the above URL, which lists all of the pending accounts. 

Each item in the list will show the user's email address, their requested username, the IP address (v4 or v6) they used to register, and any note they left when they registered. (In the registration form, this field is labeled "Why do you want to join?" in the default configuration.)

In the most recent version of Mastodon (*which may not be a tagged release yet*), each pending account will also tell you how long the account has been waiting for approval.

You can select individual users to approve or reject, using the checkboxes on the left and the text buttons at the top right. Alternately, to save on clicking, you can use the large blue buttons at the bottom of the page to approve all pending users or reject all pending users.
