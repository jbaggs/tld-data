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

Changes from 2022-10-04 to 2022-10-24:
--------------------------------------
**level 2 - :** pony.club, of.fashion, in.london, of.london, from.marketing, with.marketing, for.men, repair.men, and.mom, for.mom, for.one, under.one, for.sale, that.win, from.work, to.work

**level 2 + :** 123webseite.at, 123website.be, 123website.ch, simplesite.com, 123webseite.de, 123hjemmeside.dk, 123miweb.es, 123kotisivu.fi, 123siteweb.fr, simplesite.gr, 123homepage.it, 123website.lu, 123website.nl, 123hjemmeside.no, simplesite.pl, 123paginaweb.pt, 123sait.ru, 123minsida.se

**level 3 + :** simplesite.com.br, \*.user.fm

