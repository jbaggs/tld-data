tld-data
========
This is an automatically updated version of tld-data.zeek meant to be used
with domain-tld_, in support of the anomalous-dns domain query module. It
is synced with changes to Mozilla's Public Suffix List. 

**NOTE:** As of 2022/01/25, support has been added for 5th level TLDs.
In making this transition, it was noted that adding a 5th level to tld-data.zeek
would break domain-tld_ if it was not updated at the same time.
This has been corrected in the latest version of domain-tld_,
and will not be an issue in future versions.

As of 2022/06/13, tld-data.zeek is the correct version.  
If you are using domain-tld_ 1.2.1 or earlier, use tld-data-legacy.zeek.

.. _domain-tld: https://github.com/sethhall/domain-tld

Downloading
-----------
Download directly with the applicable command for your OS.

``wget https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

``curl https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek -o tld-data.zeek``

``fetch https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

Changes from 2022-08-25 to 2022-09-23:
--------------------------------------
**level 5 + :** vfs.cloud9.af-south-1.amazonaws.com, webview-assets.cloud9.af-south-1.amazonaws.com, vfs.cloud9.ap-east-1.amazonaws.com, webview-assets.cloud9.ap-east-1.amazonaws.com, vfs.cloud9.ap-northeast-1.amazonaws.com, webview-assets.cloud9.ap-northeast-1.amazonaws.com, vfs.cloud9.ap-northeast-2.amazonaws.com, webview-assets.cloud9.ap-northeast-2.amazonaws.com, vfs.cloud9.ap-northeast-3.amazonaws.com, webview-assets.cloud9.ap-northeast-3.amazonaws.com, vfs.cloud9.ap-south-1.amazonaws.com, webview-assets.cloud9.ap-south-1.amazonaws.com, vfs.cloud9.ap-southeast-1.amazonaws.com, webview-assets.cloud9.ap-southeast-1.amazonaws.com, vfs.cloud9.ap-southeast-2.amazonaws.com, webview-assets.cloud9.ap-southeast-2.amazonaws.com, vfs.cloud9.ca-central-1.amazonaws.com, webview-assets.cloud9.ca-central-1.amazonaws.com, vfs.cloud9.eu-central-1.amazonaws.com, webview-assets.cloud9.eu-central-1.amazonaws.com, vfs.cloud9.eu-north-1.amazonaws.com, webview-assets.cloud9.eu-north-1.amazonaws.com, vfs.cloud9.eu-south-1.amazonaws.com, webview-assets.cloud9.eu-south-1.amazonaws.com, vfs.cloud9.eu-west-1.amazonaws.com, webview-assets.cloud9.eu-west-1.amazonaws.com, vfs.cloud9.eu-west-2.amazonaws.com, webview-assets.cloud9.eu-west-2.amazonaws.com, vfs.cloud9.eu-west-3.amazonaws.com, webview-assets.cloud9.eu-west-3.amazonaws.com, vfs.cloud9.me-south-1.amazonaws.com, webview-assets.cloud9.me-south-1.amazonaws.com, vfs.cloud9.sa-east-1.amazonaws.com, webview-assets.cloud9.sa-east-1.amazonaws.com, vfs.cloud9.us-east-1.amazonaws.com, webview-assets.cloud9.us-east-1.amazonaws.com, vfs.cloud9.us-east-2.amazonaws.com, webview-assets.cloud9.us-east-2.amazonaws.com, vfs.cloud9.us-west-1.amazonaws.com, webview-assets.cloud9.us-west-1.amazonaws.com, vfs.cloud9.us-west-2.amazonaws.com, webview-assets.cloud9.us-west-2.amazonaws.com

