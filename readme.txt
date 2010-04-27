1. I did not make this, some other guy did:

	http://code.google.com/p/keynotetweet/

2. But it was broken after Twitter changed all their API Calls. 
3. So I fixed it.

xo,
-Mike

~~

In order for the script to work, you'll need to have your Twitter credentails in your Kechain. If they're not in there already (e.g. b/c you use Twitterific or similar), use Keychain Access to add a new password to your login keychain with the following information:
	•	Keychain Item Name: http://twitter.com
	•	Account Name: Your email address
	•	Password: Your Twitter password
(Thanks to codahale.com for this approach to applescript)

To run the script, simply double-click the Keynote Tweet icon. To edit it, open the same file in AppleScript Editor (formerly Script Editor). Note that you cannot run this or any 'Stay-Open' script from the editor, but must run it as an application instead.