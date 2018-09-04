# Teams

## **Add & Manage User Groups**

When managing shared password entries with multiple users, you may choose to use the _Groups_ feature to simplify your workflow. You can choose to share password entries with a group and all users who have been added to it, will instantly receive access. This saves time when sharing passwords with multiple people from the same team or department.  

![](../.gitbook/assets/groupmanage.jpg)

**\(1\)** To add a new Group, or to manage your existing ones, click the **Manage Groups** link in your **People** tab. This will open a popup window similar to the one shown above.

**\(2\)** List of existing Groups. Use the arrow next to the name to see all the shared users assigned to that Group. If the arrow does not appear, the Group is empty.

**\(3\)** Use these controls to modify the name of the Group, or to delete it. Any entries that have been shared with that Group, will be unshared from all users assigned to the deleted Group \(the entries will disappear from their accounts\). One exception would be in the event a user belongs to a different group which also has access to the same entries. 

**\(4\)** Click **Create a new group** and you will be able to add a new group to the list. 

**\(5\)** Click **OK** when you're done to apply all your changes. If you have deleted any Groups with users or entries in it, you may have to wait a moment while Passpack propagates the changes you've made. Please remember Passpack uses secure encryption, so it may take a few moments.

## **How to Set the Security Level for an Entry**

By default, all of your Passpack entries are created using the medium security level \(see _Double Lock_ below\). However, if you'd like to change the security level for an entry, you have two options:

1. Click an entry to open it. On the right-hand side, next to the **Notes** tab, there is a small **Options** tab. Click the **Options** tab and change the security setting. Press **Ok** when you have finished.  
2. Click on the **lock icon** in your password list. The lock icon is not visible by default. If you will be making frequent changes to your security levels, you can change this default setting under **Settings &gt; Appearance**.

### What Do the Different Security Levels Mean? 

In more technical terms, the lock represents your choice of encryption. You can choose a Single Lock, aDouble Lock or a Triple Lock.

**Triple Lock -- AES-256 bit encryption.**

> This is the same encryption used by the US government for top secret information and is said to take 149 trillion years to crack only one entry encrypted with AES-256 yes, ONE at a time. We suggest you use this lock for all sites linked to any personal information, e-mail accounts, links to online shopping or critical information.

**Double Lock -- AES-128 bit encryption**, your Passpack default lock.

> This encryption is also approved and used by the US government for classified or secret information. You'd probably want to Double Lock entries that take you to frequently visited forum sites or social networking sites where your name and reputation is public.

**Single Lock -- xxTEA-128 bit encryption.**

> This is the fastest, yet least robust, of the 3 locks. Using a Single Lock would lighten your account and making unpacking faster overall. The Single Lock is a valid option for sites in which no personal information has been disclosed, such as online magazines, download registrations and the famous junk accounts. Some users also store some-non password entries in their Passpack account - like bookmarks. Single Lock security would also be fine for these non-critical entries as well.

### How To See Only Entries With a Certain Security Level

Click the **show more** link in the bottom right corner of the **Quick Filters** pane. You can expand the **Security Level** item to see the three security levels available. Clicking any one of these will filter your list to view only those with the secirity level you have chosen. 

### Making Passpack Faster with Security Levels

If you have a very large account \(with 50 entries or more\), you may start to notice that Passpack becomes slow to load right after you sign in. Since the most advanced levels of security require more time to decrypt, you can reduce the wait by giving more speed to the entries which are less critical and extra protection to those you'd prefer to keep top secret.

## **How Do I Transfer Ownership of a Password?**

Yes! This is generally useful when someone on your team needs to create password entries, then offer ownership of those entries back to the administrator of the main account. Normally, whoever creates the entry is considered the owner. So we call this feature - you guessed it - _transfer of ownership_. 

To transfer ownership of a password entry that you have created to someone else, you need to: 

1. Make sure that you have already shared the entry with that person. [Here's how to do this](https://support.passpack.com/hc/en-us/articles/200673275-How-to-Share-a-Password-with-Someone).
2. In your **Passwords** tab, click on the **Bulk edit your entries** link \(it's just under the tab itself\)
3. Tick the checkboxes next to the entries for which you want to transfer ownership
4. Choose **Apply an Action &gt; Transfer Ownership**
5. You'll get a popup. Select the person you'd like to transfer to, then press **OK**.
6. Press **OK** again to confirm.
7. Your work is done, but the person will need to accept the entry before the process is fully completed.

If you _did not_ create the original password entry, you'll need to ask the person who did to go through the steps above.

### How to Accept Ownership of an Entry 

1. In your **Passwords** tab, click on the **Bulk edit your entries** link \(it's just under the tab itself\)
2. Click on **Pending entries** in the Quick filters panel to your left to see items awaiting your acceptance.
3. Tick the checkboxes next to the entries for which you want to accept ownership
4. Choose **Apply an Action &gt; Accept transfer of ownership**
5. You'll get a popup. Press **OK** to confirm.

**Why is it only available under Bulk Edit?**

It's a fairly advanced feature and wanted to keep it off the main interface. 

## **What Happens to Shared Passwords When an Account is Deleted?**

If you created passwords and shared them with someone else, those passwords will be deleted when the account is deleted. The person who you were sharing with will no longer be able to see those passwords, because they will cease to exist.

Also, your nickname will no longer appear in anyone else's People tab, because the account that nickname is associated with has been deleted. You can not recover a nickname from a deleted account.

## **I Removed a Person From a Group, But They Still See Certain Entries!?**

If you have shared certain entries with multiple groups _and_ the person was assigned to both groups, then they will continue to see all the passwords assigned to the second group. Below is an example.

Bob is assigned to the groups  "**Marketing**" and "**Sales**" which each have the following entries shared with them: 

|  **Marketing** |  **Sales** |
| --- | --- | --- | --- | --- |
|  CRM admin |  Commissions |
|  Surveys |  Brochures |
|  Basecamp |   |
|  Brochures |   |

Bob therefore has access to 5 accounts. You'll notice that the account "_Brochures_" has been shared with both groups. If you remove Bob from the group **Marketing**, but leave him in the group **Sales**, he will still have access to 2 accounts: _Commissions_ and _Brochures_. So even though he was removed from the group **Marketing**, he still maintains access to any password entries \(ex. _Brochures_\) that are shared with any other groups he belongs to.

## **Why We Don't Have a "Masked" Option For Shared Passwords**

Occasionally we are asked about adding a feature allowing the sharing of passwords with other people without them actually seeing the password itself.

Other password managers offer this feature, however we do not because it is not really possible and we feel offering the feature gives a false sense of security.

How to bypass a masked password.

You probably are not an expert in Javascript. And you probably think that it is necessary to be a Javascript ninja to intercept a “masked password”. However, that isn’t so. Look at the following code:

```text
var Jq;
(function () {
  var D = document,
  h = D.getElementsByTagName('head')[0] || D.documentElement,
  s = D.createElement('script');
  s.src = 'http://ajax.googleapis.com/ajax/libs/jquery/1.5.2/jquery.min.js';
  h.appendChild(s);
  function run() {
    if (typeof jQuery != 'undefined') {
      Jq = jQuery.noConflict(true);
      Jq('input:password').change(function () {
        alert(Jq(this).val());
      });
      alert('Ready.');
    }
    else setTimeout(run, 50);
  }
  setTimeout(run, 50);
})();
```

Even if you don’t understand what’s written there, you’ll notice that it’s short. This bookmarklet code loads a standard Javascript framework \(in this case jQuery\) and runs code that “watches” every password field. When the content of a password field changes, this code will cause the browser to show you an alert revealing the password in the field.

Now imagine that you had shared a “masked password” with a co-worker. You may feel safe because you believe that since he cannot read your password, then he can not access it. This false sense of security would likely lead you to ignore the best practices while sharing — ex. changing the password every time that you remove someone from sharing. In other words, you would probably continue to use your no-longer-safe password.

Without knowing any programming language, your co-worker could load a login page, run a simple Javascript snippet like the one above, click the button that starts the autofill… _et voilà_, he’d know your top-secret “masked password”.

There are plenty of other techniques that a person could use to capture a password field from within his browser. The real take away here is that you understand it is not possible to truly mask a password that transits in the browser of a user. So please, don’t tempt fate. Change your password every time it is necessary, for example and most especially, immediately after you stop sharing the password with another User.

## **I Can No Longer Modify a Shared Password**

Have you received this, or a similar error message when trying to modify a password entry?

> _Sorry, you no longer have permission to save changes to this shared entry ..._

If so, it means that the person sharing the entry with you has switched it to **read only** mode. There are two ways this can happen:

1. They were previously sharing it with you in **read & modify**, and changed that setting from within their account.
2. You [transfered](https://support.passpack.com/hc/en-us/articles/200265549) the entry to someone else, and they accepted it putting you into **read only** mode from within their account.

If you need to make changes to the entry, you should contact the owner and ask them to switch you to**read & modify**. [Here's how](https://support.passpack.com/hc/en-us/articles/200673275-How-to-Share-a-Password-with-Someone).

**When you transfer an entry to someone, the default is that you will be shared in read only mode.**

