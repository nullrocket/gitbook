# Backup

A back-up of your account is a  fully encrypted package of all your passwords and associated tags and notes. No one will be able to access the data in your backup file without your packing key. It is a good idea to periodically back up your passwords to safeguard against the unforseen.

## **How to Backup Your Passwords**

To make a backup, go to Tools &gt; Backup from within your account. Choose your backup key options \(see below\) then click Continue. Once your backup is ready to download, you should see a **Save to Disk**button. Click that button and your backup will download to your computer. That's it. Make sure you save your backup in a safe place, and that you remember where you put it.

**Passpack backups are encrypted. That means that no one can read your backups without your Packing Key, making it safe to store these on your computer.**

### Selecting a Backup Key \(optional\)

By default, your Packing Key is used to do this encryption - but you can also set a different Backup Key if you'd like. If you're not sure, leave the default. Otherwise, select the I want to provide a different Backup Key option. TheBackup Key is a key that is different from your Packing Key: setting a specific Backup Key can be useful is a variety of situations. The most common which comes to mind is when you want to move data between accounts:

You would make a backup with a Backup Key from the first account. Then, in the second account, use the restore function to fill that account with the backed up data. You can safely swap data this way with another person without revealing your usual Packing Key.

If you choose to use a Backup Key, two fields will appear. Type in the Backup Key that you'd like to use - it must have a quality rating of 64 or better \(actually 128 would be best\) then repeat it to make sure you haven't mistyped.

### Will the Backup Include Shared Passwords?

The backup will include all passwords that you own. That means that **if you created a password, it will be backed up**. It doesn't matter if you are sharing it with someone else or not.

Passwords that someone else created, and are shared with you, will not be included in the backup.

### Can I Backup Settings, Messages or People?

No, as of now, just your password entries and relative tags will be backed up. **to Restore Passwords From a Backup**

## **Can I Export or Backup Shared Passwords?**

Passpack allows you to restore your data from a personal backup at any time. Use this feature to recover data, or to securely transfer data between accounts. Go to Tools &gt;Restore from within your Passpack account.

**To use Restore, you need to have a backup, not an export. Backups and exports are different.**

![](../.gitbook/assets/restore.jpg)

**\(1\)** If your browser supports it, you'll see a browse button and you can choose to upload your backup file directly. Otherwise, if you don't see a browse button, you'll need to open your backup file with a simple text editor \(like notepad - not Word, Word won't work\) and copy and pasted the encrypted text into the blue box you'll see on screen.

**\(2\) Most of the time, you can leave this option as is, however there are three cases when you'll want to choose the The backup was encrypted using a specific Backup Key option:**

1. You've changed your Packing Key between when you made the backup and when you restore it -- use your old Packing Key as the Backup Key.
2. You're restoring a backup from a different account other than your own \(this is a good way to safely move large amounts of passwords back and forth between Passpack accounts\)
3. If you specifically set a Backup Key different from your Packing Key.

If you choose the Backup Key option, a field will appear. You can insert the Backup Key there.

**\(3\)** Press Preview. This will take you to the next screen.

### Preview and Confirm

Once you've chosen all of your options, press the Preview button. Make sure everything is as it should be, then press the Import button to proceed. If you do not press the Import button, nothing will be restored. When you're done, go to your Passwords tab and press the red Save All button.

### Can I Restore Messages, Settings or People?

No, that is not currently supported. Only Passwords can be backed up, and only passwords will be restored.

### Are Shared Passwords Restored?

All the passwords which are included in your backup will be restored. Once restored, you will need to re-share it by following the same procedure you normally would to share a password entry with someone. Sharing will not be re-applied automatically. _\*\*_

## **How to Print a Copy of Your Saved Passwords**

Go to **Tools &gt; Export** from inside your account, then choose the **Printable HTML Table** option under the **What Type of Format Would You Like To Export?** section. On the screen that follows, click the **Open the printable list** link. This will open a new browser window that you may print as you would any other web page on the Internet. Close this window when you're finished printing.

If you need help with the rest of the options on the Export page.

## **What is the Difference Between Export and Backup**

An export is not the same as a backup. Exported data can be easily read by humans and computers alike. Backups can not be read without your Packing Key. Backups are safe to store on your computer. Exports are not.

If you would like to make a backup of your data, you should use the Backup feature.

### What are Exports For?

Exports are mostly for transferring data from one application to another. For example, if you'd like to switch from Passpack to a different password manager, you would need to use the export feature.

### What are Backups For?

Backups are best used to keep secured copies of your passwords. Should you ever accidentally delete something from inside your Passpack account, you may be able to retrieve it by accessing a previous backup.

