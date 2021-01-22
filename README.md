Welcome.

This is a maintained technical guide that aims to provide introduction to various online tracking techniques, online id verification techniques and guidance to creating and maintaining (truly) anonymous online identities including social media accounts safely and legally.

This guide is open-source, licensed under cc-by-4.0 (Creative Commons Attribution 4.0 International).

The guide is available at https://anonymousplanet.github.io/thgtoa/guide.html (best viewed on this link as GitHub repository markdown doesn't support the many endnotes).

A PDF version of this guide is available at https://github.com/AnonymousPlanet/thgtoa/raw/main/guide.pdf

Alternatively, a weak password protected PDF version of this guide is available at https://github.com/AnonymousPlanet/thgtoa/raw/main/guide-p.pdf (password is thgtoa)

SHA56 Checksums in https://github.com/AnonymousPlanet/thgtoa/raw/main/sha256sum.txt

The latest version (0.5.5) of the guide as well as the media files are also signed using PGP (see the .sig files).

If you don't know how to verify files with PGP signatures, you should first install gpg on your system:
- Windows: Install gpg4win from https://www.gpg4win.org/download.html
- MacOS: Install GPG Tools from https://gpgtools.org/
- Linux: gpg should be installed by default

Import the PGP key using the following command from a command prompt or terminal: "gpg --auto-key-locate nodefault,wkd --locate-keys 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601" 

If it doesn't work, you can also download/view it directly from here: https://github.com/AnonymousPlanet/thgtoa/raw/main/AnonymousPlanet_0x89DAB601_public.asc

And then import it manually by issuing the following command: "gpg --import AnonymousPlanet_0x89DAB601_public.asc" (or any other file you saved it to). Or if you're using indows, just use the import function within the Kleopatra app.

Finally verify the files by issuing the following commands: "gpg --verify guide.md.sig guide.md" and "gpg --verify guide.pdf.sig guide.pdf".

Alternatively on Windows if you installed gpg4win, just double click any sig file and it will automatically check the file in question for validity using Kleopatra.
The result should show a good signature for each file.

You can also verify the authenticity of this gpg signature using my Keybase.io profile https://keybase.io/anonymousplanet and the PGP key is also published on http://keys.gnupg.net/, https://pgp.mit.edu/ and https://keyserver.ubuntu.com/ using the following PGP fingerprint: 0xEB16B6AB4AB7BA61F33E2DFD0051E9A589DAB601

All commits on this repository are now signed and verified using the same key since version v0.5.0

Feel free to submit issues using Github Issues or discuss using Github Discussions.

Have a good read.
