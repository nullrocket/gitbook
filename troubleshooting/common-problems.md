# Common Problems

## Alert: Operation failed because a another session exists

You will get this alert when more than one person is logged into a single Passpack account at one time. Passpack accounts are not intended to be used this way. If you need to share passwords with someone, you should open an account for each person, then share the passwords amongst yourselves.

If there are just two of you, you can do this each with his/her own free account.

For groups of 3 or more people, you'll require that one account upgrades to paid \(usually a company account\) then everyone else can keep their free accounts as usual. Also check out the Getting Started Guide PDF for a quick walk through of paid account capabilities and how to set them up.

## Back Button Message

**"oops. . . you are reaching the end of your history. If you continue to use the back button, you risk leaving Passpack and losing your data."**

Are you seeing this message? This message usually appears when you use your browser's back button while inside your Passpack account. Passpack is what's called an ajax application. That means that even though it seems like it changes pages, it actually technically doesn't. This, alas, means you can't use your back button.

But we know, pressing "back" is second nature, so we've implemented a little popup to warn you not to do that. In a best case situation, you keep pressing back and get accidentally logged out of Passpack. in a worst case situation, if you have unsaved changes, you may loose those changes if you keep pressing back.

Sometimes, we have found that certain browsers will pop up this alert even when you haven't pressed your back button. If that's the case, please let us know:

* Exactly what browser and version you are using, on what type of computer \(ex. Explorer 8 on Windows XP Home\).
* Tell us that you're not actually pressing your back button \(we need to know that\).

## Entry Window Empty, Until Mouseover the Cancel Button

#### Known Issue

In your entry window, the fields appear completely empty. If you mouse-over the "Cancel" button, they magically get filled in. This is most frequent in Google Chrome on Mac OS, however also happens with other browser/OS combinations as well.

#### The Fix

The culprit is the Adblock plugin. Please deactivate it for Passpack, and things should run properly for you again.

## Error Message: Referer is absent or different from current domain

If you get the error message:

Sorry, it seems that referer is absent or different from current domain.  
every time you press your Passpack It! button, then there is a 99.999% chance your browser, a plugin, or a software installed on your computer is blocking  \(or "cloaking"\) your referrer information. Please check your list of plugins.

#### Firefox users

If you have made any custom changes to your profile, please check the network.http.sendRefererHeaderproperty. If it is set to 0, you must change it back to 1.

## Visual Problems

There are very rare occasions when something looks wrong in your Passpack account. Reports of this type have been... favorites were invisible, or the single locks were switched with triple lock icons.

Don't panic. The few times we've encountered this odd behaviour, it seemed to just a visual blip. Here's what you want to do:

1. Do not add and/or save anything.
2. Log out.
3. Restart the browser.
4. Log back in.

That's it, everything should be back to normal. Should things still look odd, please contact support.

What Happened?  
In a nutshell, Passpack made your stressed your browser. Passpack uses very heavy encryption algorithms and complex logic, and can sometimes throw the browser into a loop. The result is that the browser gets mixed up and can make some of these visualization mistakes. This is why restarting the browser will usually solve the problem.

Since Passpack is goverened by the browser, the only truly important thing is that you don't save anything while the browser is confused. You don't want any problems to be saved into your encrypted pack.

## What is the P-Esc error?

Did you see this message?

**"One moment please... You may stop this process by pressing p-Esc"**

This is a generic message that appears when Passpack has been trying to do the same thing for a long time without success.

Should you see this message, you can stop whatever the process is that's throwing your computer for a loop. Simply hold down the "P" key while you press "ESC" on your keyboard \(yes, both at the same time\). Doing this will interrupt whatever it was that got stuck, you can then either try again, or contact support if it continues to happen.

#### Why does this happen?

Despite how simply and fast Passpack is, behind the scenes, Passpack uses some heavy duty encryption algorithms to and complex programming protect and manage your passwords. Therefore, in some rare occasions, Passpack can "get stuck" on a process. The reasons for this can be many and varied \(for example there is no internet connection and Passpack is trying to load or save something, or if your browser is slowed down by a separate process\). Usually pressing P-ESC will solve the problem.

#### Why Some Corrupted Entries Can Not Be Recovered

Passpack keeps backup copies of the last successful saves for each and every entry in your account. This ensures that should an entry ever get corrupted, the system will ask you if you'd like to recover the last useful backup. This is the automatic recovery system.

#### What Causes a Corrupted Entry?

A glitch in the Internet connection during saving seems to be the only cause identified so far that will cause a corrupted entry. Entry corruption is extremely rare, and nearly all of which occurred before April 19, 2010. If you are being alerted now about an recovering an corrupted entry, there's a good chance that the entry was created before that date.

#### Why Are Some Entries Recovered, Others No?

Passpack maintains a number of encrypted backup copies of each and every entry in each in your account. These backup copies are used to recover your data in the event something goes wrong.

Once exception to this rule are entries that were corrupted the first - and only - time they were saved  \(ex. a brand new entry\) . Therefore they do not have a backup copy from a previously saved version... because there is no previously saved version. This is the exception when the entry can not be recovered.

In all other cases, the automatic recovery should work just fine for you. At worst you may loose the most recent change you were making to the entry.

#### Which Entry Was Not Recovered?

Because the entries, and all the backups, are fully encrypted, Passpack has no way to let you know what the name of an entry which could not be recovered. There is no way to know. It can't be read. Scroll down and read "Can I do Anything??" below.

#### How Does Automatic Recovery Work?

The automatic recovery is fully encrypted, exactly like the rest of your Passpack account. It works like this:

1. Passpack discovers a corrupted entry  
   As soon as your account realizes that there's an entry that it's not able to decrypt and read, a notice is sent beck to the Passpack servers saying something like "Hey, I've got an entry I can't read - do you have any backups I can use instead?". Depending on your startup settings, you may or may not be asked to logout of your account before proceeding.

2. The server checks for backup versions  
   Good news - The server replies back to your account saying something like "No worries, I have backups everything you asked for" and send the encrypted backups to your account. Passpack will ask you if you'd like to try the automatic recovery. We suggest you say YES.

Bad news - The server replies back to your account saying something like "No, sorry, but I do not have any backups for that entry." If this happens, your entry can not be recovered. You will be alerted the entry is lost. It's gone. Skip step three, and read "Can I do Anything??" below.

Half & half news -  The server replies back to your account saying something like "I have backups for almost everything you asked for, except one" and send the encrypted backups it does have to your account. Passpack will ask you if you'd like to try the automatic recovery for as many entries as possible. Again, we suggest you say YES.

1. Completed recovery
   Inside your account, the corrupted version of the entry is deleted, and replaced with the backup version. In a worst case scenario, this may result in your entry being reverted to the last save.

#### Can I Do Anything??

If you have ever made personal backups of your Passpack data, you may try the restore tool to locate any missing entries.

Alternatively, if you use Passpack Desktop, maybe we can help you identify it and recover an unrecoverable entry from there. Do not synchronize your Passpack Desktop. Contact us first and we'll work with you.

We suggest, as always, that you make personal backups from time to time.

#### How Do I Know It Won't Happen Again?

On April 19, 2010 Passpack implemented a additional measure to further decrease the possibility of a entry corruption due to a blippy Internet connection. Since that date, no further entries have been corrupted \(though we did have some false positives\). Here is the blog post announcing these tighter controls and addressing false positives.

If you have encountered a corrupted entry on a brand new entry, please let us know.

