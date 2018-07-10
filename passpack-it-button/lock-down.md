## **Passpack It! Button Lock Down**

We're assuming you know about [Passpack and Host-Proof Hosting](https://www.passpack.com/blog/2008/03/host-proof-hosting/) \(your Packing Key is never sent to the server\). The Passpack It! button is also Host-Proof Hosting \(it uses an Auto-login Key contained in the button which never sent to the server\).

We use Host-Proof Hosting because we don't want to know people's data. It's safer that way, and we can sleep at night. There are, however, a couple of advanced features in the _Passpack It!_ pop-up that require us to use a variation on the Host-Proof Hosting concept.

If you'd like to understand what solution we're using, please read on \(moderately technical\).

### Background Technical Info

In order to implement the Add Entry and Copy/Paste features, we had to jump through numerous hoops. These features are very since they read from and write to your Passpack account from any website in the world. To create a sandbox around them, so we added them into a double iframe. Other elements on the webpage should not be able to access that inner iframe.

Of course, that also means that the inner iframe can no longer "speak" to the script that the button injected. However _On-the-fly Keys_ \(the ones we use to add an entry, for example\) somehow needs to be communicated to the inner iframe. This can't be done purely in the browser because the inner iframe is sandboxed. The only way to pass data to that inner iframe is as a parameter in the URL upon loading it. Of course, that gets sent to the Passpack server and therefore isn't an acceptable option for these On-the-fly Keys.

So we came up with the following solution: use a separate server, as a temporary proxy for these On-the-fly Keys.

### How Does It Work?

The On-the-fly Keys are temporarily deposited on the proxy server, together with an token that identifies the transaction. The token is included in the URL when loading the inner iframe. That's ok since the token can't be used to encrypt or decrypt anything \(it's just an ID\). When the iframe loads, the Javascript in the browser can call the proxy server with the token. If all the other authentication controls are met as well, the proxy server will reply back with the proper On-the-fly Keys. These are immediately deleted from the proxy server. From that point on, the process is managed by the browser's Javascript.

### What This Means For You

This is a variation on Host-Proof Hosting in that the main \*Passpack\* server never sees any keys which could be used to unlock any user data. However, it's undoubtedly an exception to strict Host-Proof Hosting because those keys do actually go to \*a\* server - just not \*the\* server.

Ideally in the future this proxy server needs to be managed by a third party guarantor in order for all this hoop jumping to really make sense \([let us know if you'd like to partner up with us on this](mailto:partner@passpack.com)\). However here-and-now the proxy server is separate from all user data, but it's also managed by us.

### So...

We've enabled these features by default because we feel comfortable with the data privacy \(we continue to sleep just fine at night\). However, we don't want anyone to use anything they're not comfortable with. If you have _any doubts whatsoever_, you may disable these features under **Autologin &gt; Options for power users**.

Questions or concerns? [Contact us here](https://support.passpack.com/hc/en-us/requests/new).

