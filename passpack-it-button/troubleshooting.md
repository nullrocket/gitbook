## **How to Regenerate Your Passpack it! Button**

If you'd like to regenerate a new Passpack It! \(1 Click Login\) button, go to the Auto-login tab inside your account, click on Install your button and then click on Regenerate Now.

You must the delete your existing button, and install the new \(regenerated\) one.

### The Slow Way to Reinstall Your Button \(But Easy\)

Delete your Passpack it! button by right clicking it and choosing delete. [Then install a new one.](https://support.passpack.com/hc/en-us/articles/200827350)

### The Faster Way \(for Advanced Folks\)

This takes longer to explain than to do. Do not delete your Passpack It! button. Rather, go to the **Auto-login**tab and Choose **Install your button**.

Right click the button on your screen and choose **Properties** from the menu. You'll get a popup window, then select the **Address** or **URL** field and copy it - it should start with

`javascript:(function(){/*PassPack It!`

and end with

`_PP_.h.appendChild(_PP_.s);})()`

\(it's very long so make sure make sure you copy the entire thing\).

Close the popup.

Now, right click the _Passpack It!_ button that you've already installed in your toolbar and choose **Properties**from the menu. You'll get another popup window, select the contents of the **Address** or **URL** field and delete it, then paste in the new link.

Close the popup. You're done.

## **Auto-login: When to Ask for Help**

As you know, you can, and should, teach Passpack how to login to new websites with your Passpack It! button. This should work pretty often, but there are some times when it's better to ask for help. Here are some examples.

### Tips to Make it Work

Before you read on to the solutions to common problems, make sure have [read this article](https://support.passpack.com/hc/en-us/articles/200736584) on how to teach Passpack a website. And remember go slowly.

### When You Need More Fields

Some websites use a captcha, require you to check boxes, or request that you fill out more fields than just the username and password. The solution is very simple: fill out the extra fields, check boxes and captchas, BEFORE pressing your Passpack It! button. Easy as that.

### When it Used to Work

Sometimes, you'll just swear that you've already used your _Passpack It!_ button on a website, but when you come back to it, it asks you to teach it. No worries, chances are, you're not going crazy. Websites change from time to time, and Passpack needs to be retrained. You can use [this form](https://support.passpack.com/hc/en-us/requests/new) or the **Feedback** tab in your Passpack It! pop-up to quickly let us know. We'll usually solve the problem fairly quickly.

### When it Just Refuses to Work

This can be frustrating, but there are some very tricky things that may cause the Passpack It! button to get confused. Here are some:

1. the login is on a different domain \(ex. Flickr login on Yahoo\)
2. the site uses multiple page login \(ex. egg.com\)
3. the site uses HTTP Basic Authentication
4. the login is in a Flash movie or Java Applet
5. the site itself has errors

In case \#1, we can help so you can [use this form](https://support.passpack.com/hc/en-us/requests/new) to request an alias. For all the others, sorry but your auto-login will not work. Passpack might \(big maybe\) support \#2 or \#3 in the future, but it will never support \#4 or \#5.

