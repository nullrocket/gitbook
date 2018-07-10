# Auto-login

Auto-login simply means that you use your Passpack It! button to have Passpack fill in the login form for you to any of the websites that you have stored in your Passpack account. You must connect to the website's login form via the **Go** button in your main password list, or on **Go There** from the entry window.

## **Auto-Login With Basic Authentication**

_Basic Authentication_ is a special \(older\) type of login where the website does not have a login form directly on the webpage. Instead the browser opens a grayish looking box requesting username and password. The_Passpack It!_ button is not able to log you into these websites because of the popup, however there is workaround method that you can use.

![](/assets/basicauthentry.jpg)

**\(1\)** In your [Entry window](https://support.passpack.com/hc/en-us/articles/200814020-The-Password-Entry-Window), click on the small **Options** tab to your right.

**\(2\)** Select **Yes** under the _Site requires Basic Authentication?_ option.

**\(3\)** Press **OK** to save your changes.

You should now see a slightly different icon in your password list for this entry ![](/assets/basicauthicon.jpg). From this point on, to auto-login to that website, you will need to click through to the website from inside your Passpack account by clicking on this icon.

{% hint style='info' %}
Usually when you auto-login to a website, we make it so that the website doesn't know your connecting via Passpack. This is an extra precaution so that a unethical webmaster doesn't try and use this information to mount a personal attack on you. It's pretty improbable, but we prefer being safe to sorry. When using Basic Authentication, Passpack can not perform this "cleaning" service for you, so please be careful to make sure that you are connecting to reputable sites, they will know you are arriving to them from Passpack.

{% endhint %}

## Limitations

This can be frustrating, but there are some very tricky things that may cause the Passpack It! button to get confused. Here are some:

* the login is on a different domain (ex. Flickr login on Yahoo)
* the site uses multiple page login (ex. egg.com)
* the site uses HTTP Basic Authentication
* the login is in a Flash movie or Java Applet
* the site itself has errors

Many of these problems may be impossible for us to fix because of browser limitations, but you can send us a message using [this form](https://support.passpack.com/hc/en-us/requests/new) and we will try anyway.

## When to Ask for Help**

The Passpack It! button depends on websites having a somewhat predictable structure to be able to detect the input fields and match up with your password for you. Unfortunatly, some websites choose to do things that are far outside the norm. We know this can be frustrating, but we will work with you to see if there is a way to make things work for your situation. Just use [this form](https://support.passpack.com/hc/en-us/requests/new) to send us a message along with the url to the offending login page and a description of the problem and we will give it a look.

## **Auto-login When There Are Three Fields**

Your _Passpack It!_ button can only autofill two fields for you. If you come across a login form with three fields \(for example, _Company_, _User ID_ and _Password_\), then try one of these two options.

#### Autofill + Paste

Manually type or paste in one of the fields, then you can train Passpack to auto-fill the other two for you. Keep in mind this will only work when all three fields are present on the same page.

#### Copy/Paste all Three

Double click on your _Passpack It!_ button. In the window that pops up, click on the copy/paste tab. If you've stored the _Company_ name in the notes section of your entry, then you can simply copy and paste all the info directly into the login form.


