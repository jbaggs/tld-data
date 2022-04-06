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
If you are using the most recent domain-tld_, use tld-data-1.2.2.zeek. 
Continue to use the old tld-data.zeek until you have upgraded domain-tld_.

.. _domain-tld: https://github.com/sethhall/domain-tld

Downloading
-----------
Download directly with the applicable command for your OS.

``wget https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

``curl https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek -o tld-data.zeek``

``fetch https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

Changes from 2022-03-31 to 2022-04-06:
--------------------------------------
**level 2 + :** dedibox.fr

**level 3 + :** k8s.scw.cloud, scalebook.scw.cloud, smartlabeling.scw.cloud

**level 4 + :** fr-par-1.baremetal.scw.cloud, fr-par-2.baremetal.scw.cloud, nl-ams-1.baremetal.scw.cloud, fnc.fr-par.scw.cloud, k8s.fr-par.scw.cloud, s3.fr-par.scw.cloud, s3-website.fr-par.scw.cloud, whm.fr-par.scw.cloud, priv.instances.scw.cloud, pub.instances.scw.cloud, k8s.nl-ams.scw.cloud, s3.nl-ams.scw.cloud, s3-website.nl-ams.scw.cloud, whm.nl-ams.scw.cloud, k8s.pl-waw.scw.cloud, s3.pl-waw.scw.cloud, s3-website.pl-waw.scw.cloud

**level 5 + :** functions.fnc.fr-par.scw.cloud, nodes.k8s.fr-par.scw.cloud, nodes.k8s.nl-ams.scw.cloud, nodes.k8s.pl-waw.scw.cloud

