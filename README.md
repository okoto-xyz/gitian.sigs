This repository contains Gitian signatures for [Koto](https://github.com/KotoDevelopers/koto).

It should be updated on each release.

If you have 2FA on your github account, you'll need an auth token to push your sigs from within the vagrant VM.
Another way is to copy them into a clone of this repo on your local computer before pushing:

`vagrant scp :/home/vagrant/gitian.sigs/v2.0.0 ~/Koto/gitian.sigs/`
