# The ICQ Specification

Once upon a time, Instant Messaging (IM) was born on the Internet, and the name
of the program that spearheaded that revolution was **ICQ**. The year was 1996.
Every user got an UID, a sequential number increasing with each signup. Mine
was `130414`. Soon, the numbers reached into the tens of millions.

ICQ was great. But it was not perfect. And the only available client was for
Windows. I wanted a Linux client, but soon found out that none existed, since
the protocol was proprietary and undocumented. So I decided to fix that. Using
the primitive tools available before Ethereal (now Wireshark), I captured dumps
of communication between the server and client, and set out to decipher them.

The original goal was to use this information to write an "ICQ clone", but I
realized my research into the protocol had value in itself. I cleaned up my
notes and published them on the net -- and received a tremendous response. I
never got around to writing that clone. Instead, I started the `icq-devel`
mailing list, and helped organize and connect developers and reverse engineers
interested in working on ICQ clones.

But nothing lasts forever. Mirabilis, the creators of ICQ, were acquired by
AOL, who tried to merge it into their AIM instant messaging system. Other,
incompatible protocols emerged -- Yahoo and MSN being the most popular -- and
ICQ faded into obscurity.

Unfortunately, no archives of the `icq-devel` list seem to have survived, but
at least an archived version of the latest (and last) update of the **[ICQ
Protocol Specification](icq091.txt)** remains.
