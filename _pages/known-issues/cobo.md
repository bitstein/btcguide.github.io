---
title: Cobo Vault
---

#### Not Fully Open-Source
The device has been audited, but is not fully open-source for various reason.
See more on their blog here:
<https://medium.com/cobo-vault/on-open-source-and-transparency-7f516f80b8d>

If firmware cannot be built from source reproducibly, then users are merely trusting that the binaries the software developers sign are actually derived from the correct source.
Unless users build the firmware themselves, this is essentially the same tradeoff as just using closed source code.
Note that developers working on the project needn't be malicious for issues to occur as their computers could be hacked.

#### Built on General Purpose OS (Android)
Some hardware wallets use streamlined operating systems to reduce their attack surface.
Cobo did harden their Android installation.

#### Supports Many Altcoins
Altcoin support increases the complexity of your codebase and makes it harder to audit/verify what's happening.
While Cobo has a bitcoin-only firmware, this is not a perfect solution.

TODO: add links explaining more.

#### Mild Annoyances
These are all things that are annoying but not show-stoppers:
* **Slow bootup time**.
The fingerprint reader does help makeup for this!
* **Long PIN can be annoying to enter on keyboard**.
However, this only matters when the fingerprint reader fails.
* **The microSD card is hard to remove**.
A simple pair of tweezers solves the problem.
More importantly, the strong QR-code airgap means you only have to use SD card to update the firmware.


{% include encouragement.md %}
