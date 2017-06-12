"master" branch for "master" branch from https://github.com/openbabel/openbabel
"osra" branch for patches made in OSRA
"deb" branch is for debianized version of "osra" branch + patches made originally in Debian

*** Bindings ***
There is a strict build dependency on SWIG 2.0. Make sure that only swig2.0 is installed in the system, it cannot be built with SWIG 3.0.
Still, python-openbabel package doesn't pass tests, so this package is invalid at the moment. Probably we should start using prebuilt SWIG bindings again to ensure that everything is fine.

*** Documentation ***
libopenbabel-doc package isn't generated at the moment.
