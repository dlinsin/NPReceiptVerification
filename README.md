###NPReceiptVerification
Drop-in Mac App Store Receipt Verification

By [Nick Paulson](http://twitter.com/nckplsn)

###Installation
1. Add this file to your project
2. Change the values of kReceiptBundleVersion and kReceiptBundleIdentifier at the top of NPReceiptVerification.m to your own values.
	These must be equivalent to CFBundleShortVersionString and CFBundleIdentifier, respectively. (These are found in your Info.plist file)

That's it!

###Thank You
Thank you to roddi's ValidateStoreReceipts which I used as an example and some code from.
That can be found [here](https://github.com/roddi/ValidateStoreReceipt).