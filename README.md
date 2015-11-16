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

### License

See [LICENSE](LICENSE) for details.
