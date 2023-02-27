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
**tld-data-legacy.zeek will be retired 2023/03/01.**

.. _domain-tld: https://github.com/sethhall/domain-tld

Downloading
-----------
Download directly with the applicable command for your OS.

``wget https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

``curl https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek -o tld-data.zeek``

``fetch https://raw.githubusercontent.com/jbaggs/tld-data/master/tld-data.zeek``

Changes from 2023-02-15 to 2023-02-27:
--------------------------------------
**level 2 + :** 180r.com, dojin.com, sakuratan.com, sakuraweb.com, x0.com, 2-d.jp, bona.jp, crap.jp, daynight.jp, eek.jp, flop.jp, halfmoon.jp, jeez.jp, matrix.jp, mimoza.jp, netgamers.jp, nyanta.jp, o0o0.jp, rdy.jp, rgr.jp, rulez.jp, saloon.jp, sblo.jp, skr.jp, tank.jp, uh-oh.jp, undo.jp, websozai.jp, xii.jp, squares.net, jpn.org, kirara.st, x0.to, from.tv, sakura.tv

**level 3 + :** ivory.ne.jp, mail-box.ne.jp, mints.ne.jp, mokuren.ne.jp, opal.ne.jp, sakura.ne.jp, sumomo.ne.jp, topaz.ne.jp, rs.webaccel.jp, user.webaccel.jp

**level 4 + :** s3.isk01.sakurastorage.jp, s3.isk02.sakurastorage.jp

