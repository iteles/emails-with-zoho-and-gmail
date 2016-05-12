# Setting up your business email with Zoho Mail & Gmail
Set up your business email address for free using Zoho's free tier and manage it from your gmail account.

## Why?

When it comes to emails, the most common question we are asked by those who work with us is
>'How do I set up an email address so that it comes from my business domain name for free/cheaply? (e.g. *yournamehere*@dwyl.io)'

The next question is usually
> How do I manage this from gmail so I can send and receive all of my email from one place?

So we wrote up this quick how-to guide so that we had somewhere to direct folks to.

*Note: This focuses on Zoho Mail because at the time of writing it is the simplest free solution we have found for this purpose. However, the concepts of setting up email forwarding and aliasing can be adapted to other email providers.*

## What?
There are many ways to set yourself up with a business email, but these are the two options that we've found to be fastest/most effective:
+ **Set up Google Apps for Work**
  + You have to pay a small fee per user per month
  + You get additional storage and access to the full suite of Google Apps
  + Very guided set up with good customer service
  + *Is it worth the money?* We send out calendar invitations for calls and share Google docs regularly with clients. For us, having these come from a business email address and the convenience factor is worth the monthly fee 
+ **Set up a free email service (in this case Zoho Mail) and link it up to your regular Gmail inbox**
  + Free 
  + A bit more of a pain to set up (hence this small how-to)
  + Allows you to manage all of your emails in one place, from your Gmail inbox, using the interface you're used to
  + A great solution if you're bootstrapping a very early stage start up and can't invest anything in it just yet
    + You can still send calendar invites from your business email address but you need to use Zoho Mail directly

This short how-to helps you set up the second option: Zoho Mail with Gmail.

## How?
There are two things to do here:
+ Get Zoho Mail to forward all of your incoming emails to your Gmail inbox
+ Set up Gmail to allow you to send emails *out* in a way that they appear to come from your *business* email account instead of your gmail account (called aliasing)

Let's get started.

##### 1. Sign up to [Zoho Mail](https://www.zoho.com/mail/)
As part of the sign up process, you will be taken through a step by step process of connecting your email to your domain name.    
This means you will have to set up `TXT` and `MX` records on your domain. You can do this by logging into the service you bought your domain from (we recommend [iwantmyname](http://www.iwantmyname.com)) and clicking on the 'Manage Domain Name Servers (DNS)' option - here you can add all of the `TXT` and `MX` required for setting up.

##### 2. Log into your Zoho email using your newly set up email address

##### 3. Set up email forwarding from Zoho :arrow_right: Gmail
a. Find the Zoho Mail settings menu and click into the 'Email Forwarding' options.
<img width="330" alt="zoho-settings" src="https://cloud.githubusercontent.com/assets/4185328/15271351/2d438bac-1a3c-11e6-9e1f-eb1748f8d653.png">
<img width="316" alt="zoho-email-forwarding-menu" src="https://cloud.githubusercontent.com/assets/4185328/15271350/2d42d1d0-1a3c-11e6-9ff7-07992f85fc0a.png">

b. Click to add an email address and add your Gmail address (the one you want to use as your main inbox) as the email you want to forward a copy of incoming messages to.

c. An email will be sent to your Gmail address with a verification code which you will have to enter here to confirm you are indeed the owner of the forwarding email address.

##### 4. Send yourself an email to confirm forwarding is working correctly
Send an email to your business email address; it should now show up in your Gmail inbox!

Now that you've set this up, it's time to set up your business email address as an [*alias*](https://support.google.com/a/answer/33327?hl=en).

##### 5. Set up your Gmail alias
In your Gmail settings, go to 'Accounts' and in the 'Send mail as' section, click on 'Add another email address that you own'

<img width="1229" alt="gmail-send-mail-as" src="https://cloud.githubusercontent.com/assets/4185328/15271377/3a4fbbde-1a3e-11e6-8e9f-1acaad441b1d.png">

This will bring up a small pop up window where you should enter your *business email address* and then follow the instructions to get it set up.

The important thing here is that you'll need to fill in Zoho Mail's SMTP configuration correctly - **it is different to the values automatically filled in by google**. You can google for 'Zoho mail smtp configuration' but at the time of writing, they can be found here: https://www.zoho.com/mail/help/zoho-smtp.html

<img width="621" alt="gmail-setup-new-alias" src="https://cloud.githubusercontent.com/assets/4185328/15450012/fcff41d4-1f86-11e6-8731-4f9888288c94.png">

Similarly to when we were setting up Zoho Mail forwarding, Gmail will also ask for a verification code which will be sent to your *business* email address. Luckily, you've already set up your business email to arrive in your *Gmail* inbox, so you shouldn't even have to leave Gmail to get it. :relaxed:

#### And you're set!

To send emails using your *business email address* from *Gmail*, just click to compose a new email and select the address you want to be the **sender** from the drop-down in the 'From' field activated by the little arrow.

<img width="417" alt="dwyl-email-alias" src="https://cloud.githubusercontent.com/assets/4185328/15450040/d1b1e3dc-1f87-11e6-8b47-46cce2f7b557.png">


##### Extra tip
You'll find that if you get an average to large amount of email, you'll quickly be wishing that your business emails stood out a little more when they land in your Gmail inbox.

Follow the instructions here: https://support.google.com/mail/answer/118708?hl=en (or google for it if this link no longer works!)

Lastly, Gmail labels are grey by default so *remember to also change the colour of your label to make it stand out!* 

##  :star2: Good luck with your new business! :star2: