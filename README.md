
# Evidence of the malware at guildme.net/requestMobile.php

Directed by official content of MentoLabs, I was robbed in 
guildme.net/requestMobile.php as I presented in detail at
https://forum.mento.org/t/discord-server-of-mento-lab-used-for-scamming/75
(saved in 10-Jun-2025/screencapture-forum-mento-org-t-discord-server-of-mento-lab-used-for-scamming-75-2025-06-10-21_51_45.pdf)


Although the owners of guildme.net have been deactivating the functionality
presented in the videos made on 2.Jun.2025 (see 2-Jun-2025), on 10.Jun.2025 the
URL guildme.net/requestMobile.php still has the malicious code.

OKX Wallet reports it as soon as I enter.

I sent it to virustotal that already reports as phishing.
https://www.virustotal.com/gui/url/528298faef7e2de43de4e96818f02cd990d57cc3a506ba7e5a8f316fb5138121?nocache=1


I was able to download:

* The HTML generated in 10-Jun-2025/requestMobile.php.html
* The Javascript it uses in 10-Jun-2025/e45dbd8b-991a-46c2-b94b-d43dcd3d6354.js

Partially deobfuscated with https://obf-io.deobfuscate.io/ in 10-Jun-2025/deobf.js

But it has several layers of obfuscation and uses one that doesn't work with
that tool.

We tried debugging but seems to use an anti-debugging mechanism calling
periodically the function debugger that will stop continously the
development console of chrome.

However we closed for a while the dev console and allowed the connection,
it printed to console some variables and examining them we could find the 
address of the robber. We made video of this 10-Jun-2025/use_robber_address.webm. This proves that this was the tool used to rob us the positions in
Unicorn on 30.May.2025.


Unfortunately on 10.Jun.2025 collecting and analyzing this malware it robbed
us other 540CELO and 2.73USDT that we had in the same wallet (it did the 
transfer with weird transaction because I cancelled the usual ones as 
presented in video 10-Jun-2025/draining_without_transfer.webm).

