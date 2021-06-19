---
title: The Ultimate Gmail Setup
header:
  image: /assets/images/post-2018-07-28-header-man-computer-unsplash.jpg
  caption: "Image by [Avi Richards](https://unsplash.com/@avirichards) on Unsplash"
toc: true
toc_sticky: true
---
Love or hate it, Gmail is used by millions around the world. However, many feel it lacks power or dislike the cluttered design. I will show you - with the help of a few extensions and some setup tricks - how you can make Gmail into a beautiful powerhouse.

## How We Got Here
Gmail has been around since 2003 - an eternity by Google's standards (see [Google's Graveyard](https://killedbygoogle.com/)). It was revolutionary in how it was able to provide a powerful, web-based email client available anywhere you could get internet access.

I had the keen foresight to snag myself a great address (davidgentile[at]gmail.com) back when it was still invite only. No more awkward 'daveyg007' emails!

Outside of a few minor changes, they have only had 1 major design update in 2018. But even before that update, Google introduced the minimally inspired Inbox as an alternative email interface. Many users immediately fell in love with its simplicity and features.

<figure>
  <img src="/assets/images/google-inbox.jpeg">
  <figcaption>Google Inbox - a beautiful experiment (source: <a href="https://www.extremetech.com/computing/192778-gmail-inbox-hands-on-with-googles-latest-attempt-to-fix-email">extremetech.com</a>)</figcaption>
</figure>

But Inbox was axed in 2019, with many of the features being absorbed into the 'new' Gmail and some of the design elements as well. Those who had fallen in love with Inbox were now forced to use the 'new' Gmail or a custom desktop client.

Now there are plenty of great desktop clients out there, including Apple Mail, [Airmail](https://airmailapp.com/), [Newton](https://newtonhq.com/), and Outlook. But a desktop client has several shortcomings:
  - It's local only. You have to install the app and sync on other computers to get the same setup and accounts
  - They don't always have connected mobile app meaning you have to find and set up a third-party app to access your emails on mobile
  - You miss out on all the powerful extensions available to Gmail through Chrome Extensions

I believe I have found the ultimate Gmail setup. One in which we can have the flexibility of a web-app with the power of a desktop client. Let's begin.

## Step 1 - Combine all your email accounts into one

A major annoyance with Gmail is that if you have several Google accounts, like I do for personal and business, you have to log into each account separately (See my post about [Chrome Profiles](chrome-profiles-mulitple-accounts) on how to best manage logging into multiple accounts at the same time).

This is horribly annoying to do and means your emails are located in several locations instead of one single inbox. Not to mention if you have emails not hosted on Gmail as well.

Now the Gmail mobile app has a feature that lets you view a 'unified inbox' which works great, but had not been extended to the web app. So our only option to get that 'unified' view is to use a desktop client. Or is it...?


After a lot of of trial and error I've built a system that allows you to combine all your email accounts under a single one. Here's how to do it:

### Forward email to a single account

First we need all our emails going to the same place. With an email client this is usually done by tapping into an emails IMAP, which allows you to interact with that email remotely.

But Gmail doesn't have this option to use IMAP. It does support POP access but I've found that this is not readily supported so have opted for a different method: **forwarding**.

In your email account settings you need to find the forwarding section and set it up to have all your email sent to your selected email account.

In Gmail the steps are:
  - Open up your settings (click the gear icon, then "See all settings)
  <figure>
    <img src="/assets/images/gmail-settings.png" style="width: 300px" class="align-center">
  </figure>
  - Click on the "Forwarding and POP/IMAP" tab
  - Click "Add a forwarding address"
  - Enter the email the click "Proceed"
  - This will alert you that a confirmation code has been sent to that email
  - Open that email and click the link to confirm
  - Back in your first account, select the "Forward a copy of incoming mail to" option and pick the new email
  <figure>
    <img src="/assets/images/gmail-forwarding.png">
  </figure>
  - I then have the email in that account archived but you could choose to keep it in the Inbox, deleted, etc

Repeat for all your other accounts so that all your emails end up in this single account.

### Add settings for sending from different emails

Now that you've got all your mail coming into a single account we need to make sure that you can send and respond from the correct address! It's not a good look to use your personal email for business communication.

In Gmail we have use the "Send mail as:" setting to set up and authorize this single account to send mail using different email addresses.

The steps are:
  
  **1 - Add the address**
  - Open up your settings (click the gear icon, then "See all settings)
  - Click on the "Accounts and Import" tab
  - Find the "Send mail as:" section click "Add another email address"
  - Enter your name and the address you want to send from.
  - Click Next Step and then Send verification.
  - For school or work accounts, enter the SMTP server (for example, smtp.gmail.com or smtp.- yourschool.edu) and the username and password on that account.
  - Click Add Account.

**2 - Confirm the address**
  - Sign in to the account you added.
  - Open the confirmation message you got from Gmail.
  - Click the link.

**3 - Set default behavior**

You can set the default behavior to either
  
  - Reply from the same address the message was sent to
  
    OR
  
  - Always reply from default address

I have it reply to the same address. So if I get a work email it will automatically respond using that work address.

Now you are free to change the "From" email to any of the addresses you've added.
  - When inside an email, click the "From" line.
  - You will now see all the available options
    <figure style="width: 300px" class="align-center">
      <img src="/assets/images/gmail-from-addresses.png">
      <figcaption>I may have an email hording problem...</figcaption>
    </figure>

**Boom!** You now have all your email in a single place! No more signing into multiple accounts or having multiple tabs open.

> If you want to edit signatures for each email you can do so in "Settings" -> "General" -> "Signature"

## Step 2 - Upgrade the design

Even with the design refresh in 2018, Gmail can still feel quite "busy". Desktop clients like [Newton](https://newtonhq.com/) eschew visual clutter for white space and hidden menus.

<figure>
  <img src="/assets/images/newton-mail.png">
  <figcaption><a href="https://newtonhq.com/">newtonhq.com</a></figcaption>
</figure>

With the help of a few extensions we can achieve this same minimal aestheic and make Gmail easier on the eyes.

> Quick note: I personally use [Brave Browser]() over Chrome because of the privacy protections. Brave is built on the same 'Chromium' base the Chrome browser uses and shares many of the same features - including being able to use extensions in the Chrome Web Store

### Simplify Gmail 
[website](https://simpl.fyi/) \| [install extension](https://chrome.google.com/webstore/detail/simplify-gmail/pbmlfaiicoikhdbjagjbglnbfcbcojpj)

Built by the co-founder of Google Inbox, this extension tries to recreate the simplicity of Inbox in Gmail.

Menus, icons, and side-panels are all hidden and the colors are muted.

**Before**
<figure>
    <img src="/assets/images/simplify-gmail-before.png">
</figure>

**After**
<figure>
    <img src="/assets/images/simplify-gmail-after.png">
</figure>

Through keyboard shortcuts you can quickly show/hide the left menu bar or even return back to the normal gmail.

This extension alone is probably enough to fix the design clutter of Gmail but I have a couple other tweaks I use to make it perfect.

### Dark Reader
[website](https://darkreader.org/) \| [install extension](https://chrome.google.com/webstore/detail/dark-reader/eimadpbcbfnmbkopoojfekhnkhdbieeh?hl=en)

The king of dark mode! This extension will automatically invert the colors of any website to create a pleasing dark effect.

I use it at night to save my eyes from strain and blue light.

<figure>
    <img src="/assets/images/dark-reader-gmail2.png">
    <figcaption>Viewing a message with Dark Reader enabled</figcaption>
</figure>


### Gmail Color Theme

You can configure the main colors by using the theme settings in Gmail directly.
  -  Open up your settings (click the gear icon) and scroll down to the 'THEME' section
  - Choose "View all"
  <figure style="width: 300px" class="align-center">
    <img src="/assets/images/gmail-settings-theme.png">
  </figure>
  - You can pick from multiple different colors/images but I personally prefer the 'Soft Gray' theme to give a slight color contrast than just pure white
  <figure>
    <img src="/assets/images/gmail-theme-soft-grey.png">
  </figure>

There is a 'dark' theme but I prefer using Dark Reader as you can quickly turn that on/off as needed and the dark theme still had a white background for emails
<figure>
    <img src="/assets/images/gmail-dark-theme.png">
    <figcaption>Dark Theme leaves the message white while Dark Reader converts the entire body to dark mode</figcaption>
  </figure>


## Step 3 - Final Touches

To complete our Gmail transformation we have a couple final changes to make. We will better handle newsletters, fix an issue that prevents entire messages from being shown, and finally have Gmail act as a full application that opens separate to the browser.

### Multiple Inboxes

### Show entire message
Trimless for Google Mail ([github](https://github.com/alecmev/trimless-gmail/) \| [install](https://chrome.google.com/webstore/detail/trimless-for-google-mail/niepjjjfafhadmfdminbckmciijcaagc))
  - Nifty app that removes the annoying 'Message has been clipped' and reveals the full body of the email

### Open Gmail as a separate app
