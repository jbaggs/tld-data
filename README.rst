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

Changes from 2022-11-24 to 2023-02-01:
--------------------------------------
**level 2 - :** asso.bj, barreau.bj, gouv.bj

**level 2 + :** africa.bj, agro.bj, architectes.bj, assur.bj, avocats.bj, co.bj, com.bj, eco.bj, econo.bj, edu.bj, info.bj, loisirs.bj, money.bj, net.bj, org.bj, ote.bj, restaurant.bj, resto.bj, tourism.bj, univ.bj

