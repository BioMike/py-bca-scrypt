# py-bca-scrypt
Python hashing function for the Scrypt blockchain algorithm

# Source
This repository is the original ltc_scrypt package. It is obtained from the
coinhash github repo, but multiple other clones exist. I created this repo as
something within my own control for availability.

The scrypt source code is original from the Tarsnap project and is the latest
version available, 1.2.0

The scryptmodule does not contain any license information, and I don't know who
wrote it originaly.

# Python versions
In principal this package should only be used for Python versions less than 3.6.
Python 3.6 includes the scrypt hashing function in hashlib natively. For the
sake of simplicity it is adviced when using Python versions 3.6 or above to use
the hashlib function.

