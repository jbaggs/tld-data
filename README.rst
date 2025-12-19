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

Changes from 2025-12-18 to 2025-12-19:
--------------------------------------
**level 2 + :** int.apple, indevs.in, appwrite.network

**level 4 + :** \*.cloud.int.apple

**level 5 + :** \*.r.cloud.int.apple

**level 6 + :** \*.ap-north-1.r.cloud.int.apple, \*.ap-south-1.r.cloud.int.apple, \*.ap-south-2.r.cloud.int.apple, \*.eu-central-1.r.cloud.int.apple, \*.eu-north-1.r.cloud.int.apple, \*.us-central-1.r.cloud.int.apple, \*.us-central-2.r.cloud.int.apple, \*.us-east-1.r.cloud.int.apple, \*.us-east-2.r.cloud.int.apple, \*.us-west-1.r.cloud.int.apple, \*.us-west-2.r.cloud.int.apple, \*.us-west-3.r.cloud.int.apple

