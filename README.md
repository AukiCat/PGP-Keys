# My Public PGP Key
[Читать на русском](README_RU.md)

This repository contains my public PGP key. It is used for file encryption and verification of my digital signature.

## Key Fingerprint

**Before importing the key, make sure the fingerprint matches.** This ensures you are using the authentic key.

Fingerprint: `F8D7 98CE 0285 8682 B383 E32C AB9A E9B8 F566 F71E`

## How to Import the Key
### Using Command Line (GnuPG)
* Download the key:  
  `wget https://raw.githubusercontent.com/AukiCat/PGP-Keys/main/Auki_cat_public.asc`

* Import into your keyring:  
  `gpg --import Auki_cat_public.asc`

* Verify the fingerprint:  
  `gpg --fingerprint AukiCat`

### Using Kleopatra (Windows)
* Download the key file `Auki_cat_public.asc` from this repository.
* Open Kleopatra.
* Click **Import**.
* Select the downloaded file `Auki_cat_public.asc`.
* Kleopatra will import the key.
* To verify the fingerprint, find the imported key in the list, right-click it, and select **Details**.