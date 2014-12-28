mutability-repo
===============

This is a Debian/Raspbian package to automate use of repo.mutability.co.uk.

It is an architecture-independent package containing two conffiles:

 * `/etc/apt/sources.list.d/mutability.list`: an apt configuration that points
   to the repo.mutability.co.uk archive.
 * `/etc/apt/trusted.gpg.d/mutability.gpg`: the public key used to sign
   releases on repo.mutability.co.uk

Installing this package will allow packages from repo.mutability.co.uk to be
installed and upgraded by apt-get without warning/prompting about use of
unauthenticated packages (assuming the releases are correctly signed, of
course).
