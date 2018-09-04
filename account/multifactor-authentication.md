# **Multifactor Authentication**

_Two Factor Authentication_ is a security measure to protect against unwanted access to your account. You \(or anyone else\) can not sign into your Passpack account without it.

## **Two Factor Authentication Set Up**

If you opt for the Yubikey, please make sure you have at least 2, otherwise if you loose your Yubikey, you will forever be locked out of your account.

![](/assets/assets%2F-LCBoecSUMMtKc_rFkkd%2F-LF5o1d3K2h1ttPlLvPx%2F-LF5onS4PCronlVaQJ5z%2F2factoryubikey.jpg)

**\(1\)** Go to **Settings &gt; Two Factor Authentication**.

**\(2\)** Select one of the two options. If you choose **Yubico Yubikey USB card** you must have, or [purchase a Yubikey](http://www.yubico.com/o.php?refid=154&rno=19380020). Choose **One Time Passwords sent via email** for a free alternative, though not quite as high-security.

**\(3\)** Press **Continue** and follow the on-screen instructions to finish the process..

Some Internet Cafès or public computers may not allow you use a USB drive for fear of keyloggers. In these cases, you will not be able to access your Passpack account from those computers.

## **Authorize Your Mobile Device to Skip Two Factor Authentication**

Passpack supports both email and Yubikey two factor authentication. On your mobile device though, there is _physically_ no place to insert your Yubikey.

To keep you from being locked out of your account when on the go, Passpack lets you do a one-time setup on your mobile device which authorizes _just that phone_ to skip the Yubikey during login. Make sure you have actually already set up a two factor authentication method in your standard \(non-mobile version\) account.

**Your device's browser must support HTML5. If not, you can't use this one-time authorization feature. Sorry.**

#### Email Method

On the screen that prompts you to insert the code sent to you by email, you'll also see a checkbox that says **Always consider this device safe. Don't ask me again.**. Check that off before pressing the **Verify**button.

Complete the login with your packing Key, and you're all done. The device will remain authorized unless you explicitly unauthorize it under **Settings &gt; Two Factor Authentication**

#### Yubikey Method

The process is a little convoluted, but only needs to be done once per device. Your main hurdle will be getting a copy of the Yubikey generated code to your mobile phone. You will need to have both your standard computer and your mobile device in front of you to complete this set up.

Login to your Passpack account from your mobile device. Once you arrive at the screen that prompts you for the Yubikey code, do nothing. Just leave that page open for a moment.

Now, on your normal computer, open your email and address a new email to yourself. Place the cursor in the subject line of the email, then insert your Yubikey in your computer and press the button. A code should appear. This is the code you need to insert into the page that's still open on your mobile device. Press send to email the code to yourself.

Back on your mobile device, check your email, and copy the Yubikey code \(hint, you may have to hit reply on some Android mail clients to be able to actually copy the code, just make sure to delete the "re:" before copying\). Go back to the Passpack page in your browser, and paste the code in the field. Check the box that says **Always consider this device safe. Don't ask me again.**. Then, press the **Verify** button.

Complete the login with your packing Key, and you're all done. The device will remain authorized unless you explicitly unauthorize it under **Settings &gt; Two Factor Authentication**

### 



