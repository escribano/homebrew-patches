# homebrew-patches

My "taps" for Mac Homebrew formulae which have patches not accepted by homebrew/homebrew.

### Usage

You can access this repository using `brew tap`:

    brew tap escribano/patches
    brew install mutt --with-sidebar-patch

Since these formulae will likely have collisions with standard homebrew/homebrew formulae, you can:

    brew install escribano/patches/<formula>

    mut 1.5.24 with sidebar
    brew install escribano/patches/mutt --with-sidebar-patch

### update patch
wget http://lunar-linux.org/~tchan/mutt/patch-1.5.24.sidebar.20151111.txt
openssl sha256 patch-1.5.24.sidebar.20151111.txt
SHA256(patch-1.5.24.sidebar.20151111.txt)= 66441edf056032119f854fc5ee86c73eece8b95dc998c0cfae5ed05b0b035070

