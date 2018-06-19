# Security



## Packing Key

### Can I Use Yubikey to Replace My Packing Key?

No, sorry. You must always provide your _Packing Key_ yourself. 

### **How to Choose a Packing Key**

When choosing your Packing Key, remember: this is the key to your kingdom, so it should be strong. The minimum requirement is only 8 characters, but the longer the better. The fastest way to choose a strongPacking Key that is easy to remember is to use a complete sentence. Here are some examples:

> Chocolate ice cream is better than vanilla  
> pink elephants on parade  
> Mr. Bowler has a funny hat

Really, it's that easy!

You can change your Packing Key whenever you'd like by going to Account &gt; Change Packing Key from within your Passpack account. However, if you forget your Packing Key, it CAN NOT be recovered or reset.

#### Minimum Requirements

Your _Packing Key_ must be at least 8 characters long and is also case sensitive. You can \(and should!\) use punctuation, numbers, foreign characters or even spaces. We suggest a quality rating of at least 80 \(optional\).

#### What Is a Packing Key Exactly?

In technical terms, it is an encryption key. You do not need to know what that means in order to use Passpack.

Passpack uses your User ID and Password to confirm you are the proper owner of your account \(sometimes called "authentication"\). Once that is done, Passpack will download your pack of passwords to your browser, where your Packing Key will be used to decrypt the pack. Then you can see your passwords. 

Your passwords are "unpacked" directly on your computer your browser, then packed back up again before getting sent back to Passpack for storage.

Passpack will do all of this for you, all you need to do is provide the proper Packing Key.

### **Lock It Up!**

In addition to the Auto-lock and Auto-save options that you can manage under your **Settings &gt; Packing & Saving** menu, you can also force Passpack to lock up and hide on command.

![](../.gitbook/assets/1click-lockup-update.jpg)

Should you ever hear footsteps coming down the hall and want to hide everything quickly, a boss or colleague enters the room, you need to run out of the room for a moment - just press the **Lock it Up!** button in the upper right hand corner of your screen. All you'll need is your _Packing Key_ to reenter your account when you're ready.

### **What Is a Packing Key? Where Do I Get It?**

Your _Packing Key_ is the secret sentence that you should have chosen yourself when you signed up for Passpack.

When you signed up you should have been asked to provide three things:

1. a _User ID_  
2. a _Password_  
3. a _Packing Key_ \(a secret sentence, you chose on the screen that looks like the image below\)

![](../.gitbook/assets/choosepackingkey.png)

If your not able to remember your Packing Key, then you may simply try and sign up for a new free account - you can have as many as you like. You'll just need to choose a different User ID. 

**For security purposes, we do not know your Packing Key, therefore we can't send it to you.**

## **Multifactor Authentication**



### **Two Factor Authentication Set Up**

_Two Factor Authentication_ is a security measure to protect against unwanted access to your account. You \(or anyone else\) can not sign into your Passpack account without it. If you opt for the Yubikey, please make sure you have at least 2, otherwise if you loose your Yubikey, you will forever be locked out of your account.

![](../.gitbook/assets/2factoryubikey.jpg)

**\(1\)** Go to **Settings &gt; Two Factor Authentication**.

**\(2\)** Select one of the two options. If you choose **Yubico Yubikey USB card** you must have, or [purchase a Yubikey](http://www.yubico.com/o.php?refid=154&rno=19380020). Choose **One Time Passwords sent via email** for a free alternative, though not quite as high-security.

**\(3\)** Press **Continue** and follow the on-screen instructions to finish the process..

Some Internet Cafès or public computers may not allow you use a USB drive for fear of keyloggers. In these cases, you will not be able to access your Passpack account from those computers.

### **Authorize Your Mobile Device to Skip Two Factor Authentication**

Passpack supports both email and Yubikey two factor authentication. On your mobile device though, there is _physically_ no place to insert your Yubikey.

To keep you from being locked out of your account when on the go, Passpack lets you do a one-time setup on your mobile device which authorizes _just that phone_ to skip the Yubikey during login. Make sure you have actually already set up a two factor authentication method in your standard \(non-mobile version\) account. 

**Your device's browser must support HTML5. If not, you can't use this one-time authorization feature. Sorry.**

#### Email Method \(pretty easy\)

On the screen that prompts you to insert the code sent to you by email, you'll also see a checkbox that says **Always consider this device safe. Don't ask me again.**. Check that off before pressing the **Verify**button.

Complete the login with your packing Key, and you're all done. The device will remain authorized unless you explicitly unauthorize it under **Settings &gt; Two Factor Authentication**

#### Yubikey Method \(a little harder\)

The process is a little convoluted, but only needs to be done once per device. Your main hurdle will be getting a copy of the Yubikey generated code to your mobile phone. You will need to have both your standard computer and your mobile device in front of you to complete this set up.

Login to your Passpack account from your mobile device. Once you arrive at the screen that prompts you for the Yubikey code, do nothing. Just leave that page open for a moment.

Now, on your normal computer, open your email and address a new email to yourself. Place the cursor in the subject line of the email, then insert your Yubikey in your computer and press the button. A code should appear. This is the code you need to insert into the page that's still open on your mobile device. Press send to email the code to yourself.

Back on your mobile device, check your email, and copy the Yubikey code \(hint, you may have to hit reply on some Android mail clients to be able to actually copy the code, just make sure to delete the "re:" before copying\). Go back to the Passpack page in your browser, and paste the code in the field. Check the box that says **Always consider this device safe. Don't ask me again.**. Then, press the **Verify** button.

Complete the login with your packing Key, and you're all done. The device will remain authorized unless you explicitly unauthorize it under **Settings &gt; Two Factor Authentication**

### **Google Authenticator**

### **YubiKey**

#### **Support for Yubikey**

1. You can use your Yubikey either as a _Two Factor Authentication_ in which case you will need your Yubikey in addition to your Passpack _Password_ and _Packing Key_. 
2. Or you can replace your Passpack _Password_ with your Yubikey and skip straight to the _Packing Key_.  

### **Emergency Access**

#### **How Many Disposable Logins Can I Use Daily?**

You can use as many _Disposable Logins_ in a day as you'd like. The only restrictions are that they be used only once, and before they expire.

#### **How Do I Know When My Disposable Logins Expire?**

To see when they expire, go to **Settings &gt; Disposable Logins**. If you have any active Disposable Login they will be listed there. At the top of the list, it should say something like "_These Disposable Logins will expire in 11 hours and 59 minutes._"

If you do not see a list, it means that they have already expired, therefore you have none.

#### **Can I Use My Disposable Logins in Any Order?**

Yes, you can use them in any order you wish. You can choose any set of _Disposable Logins_ to use from your printed list. This means you can use them in random order if you would like too. Just cross it off when you are done, because \(of course\) they can only be used once.

It does not matter if you use them in random order, or use some, then login normally, then use some more. Your _Disposable Logins_ remain active until the expiration date, or until used. 

#### **Can I Use a Disposable Login with OpenID?**

Not usually. Passpack's Disposable Logins are Password/Packing Key pairs that can not be used separately. If you use OpenID \(or other Third Party Login\*\) for authentication, then you do not have a Password and Passpack can not make a Password/Packing Key combination for you.

**\* Includes OpenID, Google, Yahoo, Hotmail, Facebook, FriendFeed, Twitter and Yubikey.**

#### An Alternative Solution

If you would like to be able to access your account with a Disposable Login, you must first set up a standard Passpack User ID and Password. You can do this under Settings &gt; Set User ID and Settings &gt; Set Password from inside your account.

You can then use either your OpenID or your standard User ID and Password to login. You have both options available to you. You may also then [set up your Disposable Logins](https://support.passpack.com/hc/en-us/articles/200698865) under Settings &gt; Disposable Logins.**make more Disposable Logins when logged in with a Disposable Login?**

#### **What is a Disposable Login?**

A Disposable Login is a set of Password and Packing Key that you use once, and then it gets thrown away. You can not choose your _Disposable Logins_, they will be assigned to you.

Disposable Logins are sometimes referred to as "One Time Password" or OTP for short. However at Passpack you get more than just a single use password, you get a Password/Packing Key combination. This is why we prefer the name"Disposable Login" over OTP.

#### When to Use Disposable Logins

Disposable Logins are for use when traveling. They help protect your Passpack account when you connect from a computer that is not under your direct control \(like at an Internet point, library, client's office or computer lab\). 

#### How Disposable Logins Protect You

Certain types of malevolent software - called keyloggers, or screenloggers - are able to capture your password as you type, or even record clicks on an on-screen keyboard. Since your Passpack account holds the keys to your kindgom, you should be very careful NOT to allow these programs to capture your Passpack Password and Packing Key.

By using a disposable Password/Packing Key pair, you will be able to protect your account from these keyloggers. Even if your Disposable Login were to get captured, it's completely useless since it only works ONCE \(the one time you used it\).**o Sign In with Disposable Logins**

#### **How to Set Up Disposable Logins**

You should set up your Disposable Logins before traveling. It's very fast, but make sure you have a printer available. First, login to your Passpack account and go to Settings &gt; Disposable Logins. Press the Generate button and the screen will change.

![](../.gitbook/assets/disposablelogins.jpg)

**\(1\)** Use the plus \(+\) and minus \(-\) buttons to choose the number of _Disposable Logins_ that you want to create

**\(2\)** Use the plus \(+\) and minus \(-\) buttons to choose when they should expire.

**\(3\)** Press the Generate button.

When you're done, you will see the list of generated codes, press the **Print** button \(there is no way you will be able to memorize them - they look like a bunch of nonsense\). A tiny, anonymous looking window will open. Print it as you normally would.

**Store your printout in a safe place together with your travel documents, or clip it and put it in your wallet.**

