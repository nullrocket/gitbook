# 

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

## **How to Auto-Login With Basic Authentication**

_Basic Authentication_ is a special \(older\) type of login where the website does not have a login form directly on the webpage. Instead the browser opens a grayish looking box requesting username and password. The_Passpack It!_ button is not able to log you into these websites because of the popup, however there is workaround method that you can use.

![](.gitbook/assets/basicauthentry.jpg)

**\(1\)** In your [Entry window](https://support.passpack.com/hc/en-us/articles/200814020-The-Password-Entry-Window), click on the small **Options** tab to your right.

**\(2\)** Select **Yes** under the _Site requires Basic Authentication?_ option.

**\(3\)** Press **OK** to save your changes.

![](.gitbook/assets/basicauthicon.jpg)

You should now see a slightly different icon in your password list for this entry. From this point on, to auto-login to that website, you will need to click through to the website from inside your Passpack account by clicking on this icon.

**Tech info: usually when you auto-login to a website, we make it so that the website doesn't know your connecting via Passpack. This is an extra precaution so that a unethical webmaster doesn't try and use this information to mount a personal attack on you. It's pretty improbable, but we prefer being safe to sorry. When using Basic Authentication, Passpack can not perform this "cleaning" service for you, so please be careful to make sure that you are connecting to reputable sites, they will know you are arriving to them from Passpack.**

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

## 

### How Long Does it Take to Get Fixed?

That depends. Some sites require just a quick fix on our part and can generally get done in a couple of days. Others may be much more complex, must be escalated directly to the development team, and will take longer depending on their work load.

**Should there be a backlog, we try and give priority to links submitted by our premium users.**

### What If I Don't Get an Email?

If you do not receive an email, then you may not have set one up and confirmed it in your account. [Here's how to do that](https://support.passpack.com/hc/en-us/articles/200698505-How-to-Confirm-and-Manage-Your-Email).

Also, if the link is beyond repair, we'll just mark it off as such and won't bother you with an email. You'll still be able to login to that website, but you may need to copy/paste the password from the \_Passpack It!\_popup, into the login form manually.

### It Seems Like ALL Sites are Broken...

If it feels like "it just doesn't work" then you'll be best served by contacting us for personal support. Thousands of users login to thousands websites every day with their _Passpack It!_ buttons. If all the sites broke at once... we'd know \[grin\]. Chances are there's something that isn't set up just quite right. Check these things first:

1. [The button is correctly installed](https://support.passpack.com/hc/en-us/articles/200827350).
2. [That you are using it correctly](https://support.passpack.com/hc/en-us/articles/200736584).
3. You have left Passpack open in the background while you use your button \([how to get around this](https://support.passpack.com/hc/en-us/articles/200254369)\).

Still not working? [No worries, let us know what's not working, and we'll help you out](https://support.passpack.com/hc/en-us/requests/new).

## **How to Install the Passpack It! Button**

Once you're signed into Passpack, just choose Auto-Login &gt; Install Your Button. Right click on the_Passpack It!_ button and add it to your bookmarks. A button that says "Passpack It!" should then appear in your bookmarks. Below are detailed instructions for each type of internet browser.

Didn't work? See instructions below for each type of browser.

### Internet Explorer 9

### The first step to gain access and display the bookmark tool is to let Internet Explorer 9 show it. In fact, all toolbars are hidden by default.

* Open Internet Explorer 9.
* Right click the tabbed area. At this point a small menu will appear. Such a menu is quite important \(and well hidden,too!\) because it will shows you how to display the bookmark toolbar and other options.
* Untick the Lock Toolbars option.
* Click the Favorites Bar.

At this point, once you have “unleashed” all the bookmarks, simply drag the Passpack It! button on the bookmark toolbar and drop it.

### Internet Explorer 8

You'll need to make sure your Internet Explorer 8 Favorites bar is enabled and visible. Here's how:

1. _Enable:_ from your browser's menu, go to **Tools &gt; Toolbars** and make sure Favorites bar is checked**.**
2. _View:_ from your browser's menu, go to **View &gt; Toolbar &gt; Favorites bar**
3. _Install:_
   * Right-click on the Passpack It! button and choose **Add to Favorites**. 
   * A security alert dialog will appear, click **Yes**. 
   * The _Add a Favorite_ dialog opens. Click the **Create In** combo box and choose **Favorites bar**.
   * Then click **Add** to add the bookmarklet to your Favorites bar.

### Internet Explorer 7

To install the button, right click the _Passpack It!_ link and choose **Add to favorites** from the menu. A small popup will appear, choose to save it to the "Links" option then press **OK**. You may get a security warning, just press OK. It's safe.

You should see it show up in your browser bar right away. If this isn't the case, you may not have your links bar showing. From your browsers menu, choose **View &gt; Toolbar &gt; Links**. That should do it.

### Internet Explorer 6

To install the button, right click the _Passpack It!_ link and choose **Add to favorites** from the menu. A small popup will appear, press OK. Then open your favorites and drag _Passpack it!_ into the "Links" folder.

### Chrome

Make sure you actually have the bookmarks bar showing, or you won't have a place to drag the button _onto_. Open a new tab. Right click the bookmarks bar near the top of the page and choose **Always show the bookmarks bar**.

### All Other Browsers

To install the button, simply drag the _Passpack It!_ link to your **Personal Toolbar**.

### If It _Still_ Didn't Show Up

If you followed the instructions, you should see the button show up in your browser bar right away. If this isn't the case, you may not have your Personal Toolbar showing. That's easy enough to fix.

> In Internet Explorer  
> choose **View &gt; Toolbar &gt; Links**.
>
> In Firefox  
> **View &gt; Toolbar &gt; Bookmarks**
>
> In Netscape  
> **View &gt; Toolbar &gt;Personal Toolbar**
>
> In Opera  
> **View &gt; Toolbar &gt;Personal Toolbar**
>
> In Mozilla  
> **View &gt; Show/Hide &gt; Personal Toolbar**
>
> In Safari  
> **View &gt; Show Bookmarks Bar**

## **Auto-login, 1 Click Login and Passpack It! -- Help?**

### What is the difference between Auto-login and 1 Click Login?

With Auto-login  
You can log into a site from within your account. For example, you want to check my mail, you press the Go There button next to the entry for my Yahoo account, a new tab opens in my browser, you press thePasspack It! button and you're in.

With 1 Click Login turned on  
You can log into a site without going through your account each time. For example, you are surfing the Internet normally, you come across an article on Yahoo, you decide you want to check your email while you're there, you click on the "Sign In" link on the page, press your Passpack It! button and you're in. For this to work you have to have your Passpack account open in another tab or window of my browser, and [1 Click Login turned on](https://support.passpack.com/hc/en-us/articles/200254359).

### Why has my Passpack It! Button stopped working? How can I fix this?

This could happen for a series of reasons: an update on our side, a bug, a browser update, etc. The fastest way to fix this is to regenerate your button. To do this, go to the Auto-login tab within your account. Click on Install your button, at the bottom of the page you will see Security Tip: Regenerate Your Buttons. As the warning says, this will cause every button you have ever installed to stop working permanently.

### Why does a particular site not work when I try to use Auto-login?

Some sites need training in order to work properly, you can [train them yourself](https://support.passpack.com/hc/en-us/articles/200736584) when the instructions appear.

### When I try to use Auto-login to access a site, it says I have to connect through Passpack. What does it mean?

If Passpack tells you 'To use the Passpack It! button, you must connect to this website through your Passpack Password Manager' that usually means your browser does not accept cookies. The Passpack It! button can only work if your browser accepts cookies. To make sure the browser accepts them, you can follow these steps:For Internet Explorer  
Tools Menu -&gt; Internet Options -&gt; Privacy Tab -&gt; Advanced Options -&gt; select both "Allow cookies from sites" and "Allow third party cookies"

For Firefox  
Edit Menu -&gt; Preferences -&gt; Privacy Tab -&gt; select both "Accept cookies from sites" and "Accept third party cookies." If you are using Firefox 3, you might also want to put "passpack.com" in the list of allowed exceptions.

For Google Chrome  
Go to the Tools Icon in the upper-right corner of the browser, select Options then the "Under the Hood" tab. At the bottom make sure that "Allow all cookies" is selected. Press OK and it's all done \(you may have to restart the browser\).

### How do I install my Passpack It! button in Internet Explorer 6 & 7?

Internet Explorer 7  
To install the button, right click the Passpack It! link and choose Add to favorites from the menu. A small popup will appear, choose to save it to the "Links" option then press OK. You may get a security warning, just press OK. It's safe.  
You should see it show up in your browser bar right away. If this isn't the case, you may not have your links bar showing. From your browsers menu, choose View &gt; Toolbar &gt; Links. That should do it.Internet Explorer 6  
To install the button, right click the Passpack It! link and choose Add to favorites from the menu. A small popup will appear, press OK. Then open your favorites and drag Passpack It! into the "Links" folder.

### How do I install my Passpack It! button in Firefox, Opera, Safari, Netscape, Seamonkey and Flock?

To install the button, simply drag the Passpack It! link to your Personal Toolbar.

### Certain websites use one page to enter your username, and one webpage to enter your password. Is this a supported type of login?

No, sorry.

## **How to Auto-login When There Are Three Fields**

Your _Passpack It!_ button can only autofill two fields for you. If you come across a login form with three fields \(for example, _Company_, _User ID_ and _Password_\), then try one of these two options.

**1. Autofill + Paste**

Manually type or paste in one of the fields, then you can train Passpack to auto-fill the other two for you. Keep in mind this will only work when all three fields are present on the same page.

**2. Copy/Paste all Three**

Double click on your _Passpack It!_ button. In the window that pops up, click on the copy/paste tab. If you've stored the _Company_ name in the notes section of your entry, then you can simply copy and paste all the info directly into the login form.

## **Passpack It! says I have to connect through Passpack, but I did.**

If Passpack tells you **To use the Passpack It! button, you must connect to this website through your Passpack Password Manager** that almost always means your browser does not accept cookies.

The Passpack It! button can only work if your browser accepts cookies. Follow these steps:

**For Internet Explorer**  
Tools Menu -&gt; Internet Options -&gt; Privacy Tab -&gt; Advanced Options -&gt; select both "Allow cookies from sites" and "Allow third party cookies"

**For Firefox**  
Edit Menu -&gt; Preferences -&gt; Privacy Tab -&gt; select both "Accept cookies from sites" and "Accept third party cookies." If you are using Firefox 3, you might also want to put "passpack.com" in the list of allowed exceptions.

**For Google Chrome**  
Go to the Tools Icon in the upper-right corner of the browser, select Options then the "Under the Hood" tab. At the bottom make sure that "Allow all cookies" is selected. Press OK and it's all done \(you may have to restart the browser\).

**For Opera**  
Go to the Opera icon in the upper-left corner of the browser, select Settings &gt; Preferences, then the "Advanced" tab. Make sure that "Accept cookies" is selected. Press OK and it's all done \(you may have to restart the browser\).

## **How to Login to a Website With the Passpack It! Button**

Ok, so you have a list of passwords saved in Passpack and you've [installed your personal _Passpack It!_ button](https://support.passpack.com/hc/en-us/articles/200827350). Now here's what you can do:

### The Tried & True Click-Through Method

> _Do this once:_

1. You login to Passpack. . _Then do this every time you want to login to a website:_ .
2. You can click on a password in your list.
3. The website will open in a new window or tab.
4. Navigate to the login page.
5. Click your _Passpack It!_ button ... and Passpack will log you in

**Hint:** if you save the link to the login page in your password entry, then you can skip step 4. To avoid repeating step 1 all day long, read about the [remember me feature](https://passpackinc.zendesk.com/hc/en-us/articles/200748974-How-to-Use-Remember-Me), [auto-locking options](https://support.passpack.com/hc/en-us/articles/200691035) and - for advanced users - [check out this article](https://support.passpack.com/hc/en-us/articles/200254369).  
\_\_

### 1 Click Login While You Browse

> _Do this once:_

1. You login to Passpack.
2. You turn on 1 Click Login.
3. You leave Passpack open in the background and browse the web at your leisure all day long. . _Then do this every time you want to login to a website:_ .
4. When you come across a website login page, press your _Passpack It!_ button ... and Passpack will log you in

**Hint:** you can [do step 2 manually](https://support.passpack.com/hc/en-us/articles/200254359), or skip it by [changing your startup settings](https://passpackinc.zendesk.com/hc/en-us/articles/200749064). Advanced users can can even skip step 3 - [check out this article](https://support.passpack.com/hc/en-us/articles/200254369).

