## Server Blacklist

This repository contains a `blacklist.txt` of XMPP domains that are used by spammers, scammers, hackers, trolls, etc and do not react to abuse complaints. Servers are added according to the following rules. The track record leading to addition or removal is documented in the respective git commit.

### Addition to Blacklist

A server is added to the blacklist after the following steps were performed
and did not lead to a reduction of spam traffic from the server:

1. Contact the server operator directly (via XEP-0157 contact or info from
   server website), and wait 7 days for an appropriate reaction. *Skip this
   step if no public contact information can be found.*

2. If the server operator does not react or ceases to stop the spam: contact
   the hosting ISP abuse department (via Whois or contact from ISP website),
   and wait 14 days for an appropriate reaction.

3. If the ISP does not react or ceases to stop the spam: add the server to the
   blacklist with a documentation of the steps taken.

### Removal from Blacklist

Once you are on the blacklist, you will no longer be able to request for removal. If caught evading the blacklist ban, will add your new domain to the blacklist. This is to protect the jabber/xmpp network from bad actors.
