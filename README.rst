tld-data
========
This is an automatically updated version of tld-data.zeek meant to be used
with domain-tld_, in support of the anomalous-dns domain query module. It
is synced with changes to Mozilla's Public Suffix List. 

.. _domain-tld: https://github.com/sethhall/domain-tld

Downloading
-----------
Download directly with the applicable command for your OS.

``wget https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

``curl https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek -o tld-data.zeek``

``fetch https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

Changes from 2024-01-31 to 2024-02-03:
--------------------------------------
**level 2 - :** run.app, blog.kg

**level 2 + :** flutterflow.app, zap.cloud, a2hosted.com, aliases121.com, cpserver.com, 12chars.dev, panel.dev, pley.games, 12chars.it, azure-api.net, azureedge.net, azurefd.net, trafficmanager.net, 12chars.pro

**level 3 - :** a.run.app

**level 3 + :** \*.run.app, servicebus.windows.net, \*.kin.one, \*.id.pub, \*.kin.pub

**level 4 + :** \*.private.repost.aws, notebook-fips.ca-central-1.sagemaker.aws, notebook.ca-west-1.sagemaker.aws, notebook-fips.ca-west-1.sagemaker.aws, execute-api.ca-west-1.amazonaws.com, s3.ca-west-1.amazonaws.com, s3-accesspoint.ca-west-1.amazonaws.com, s3-accesspoint-fips.ca-west-1.amazonaws.com, s3-fips.ca-west-1.amazonaws.com, s3-website.ca-west-1.amazonaws.com, \*.cloudapp.azure.com, \*.s.brave.io, blob.core.windows.net

**level 5 + :** s3.dualstack.ca-west-1.amazonaws.com, s3-accesspoint.dualstack.ca-west-1.amazonaws.com, s3-accesspoint-fips.dualstack.ca-west-1.amazonaws.com, s3-fips.dualstack.ca-west-1.amazonaws.com, s3-website.dualstack.ca-west-1.amazonaws.com, webview-assets.aws-cloud9.il-central-1.amazonaws.com, vfs.cloud9.il-central-1.amazonaws.com

