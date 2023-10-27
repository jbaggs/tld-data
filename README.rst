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

Changes from 2023-10-25 to 2023-10-27:
--------------------------------------
**Addition of 6th level TLDs.**

**level 6 + :** \*.cn-north-1.airflow.amazonaws.com.cn, \*.cn-northwest-1.airflow.amazonaws.com.cn, s3.dualstack.cn-north-1.amazonaws.com.cn, s3-accesspoint.dualstack.cn-north-1.amazonaws.com.cn, s3-website.dualstack.cn-north-1.amazonaws.com.cn, s3.dualstack.cn-northwest-1.amazonaws.com.cn, s3-accesspoint.dualstack.cn-northwest-1.amazonaws.com.cn

