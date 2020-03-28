Beyondcoin Core version *0.15.2* is now available from:

  <https://beyondcoin.io/bin/beyondcoin-core-0.15.2/>

This is a new major version release, including new features, various bugfixes
and performance improvements, as well as updated translations.

Please report bugs using the issue tracker at GitHub:

  <https://github.com/beyondcoin-project/beyondcoin/issues>

To receive security and update notifications, please subscribe to:

  <https://groups.google.com/forum/#!forum/beyondcoin-dev>

How to Upgrade
==============

If you are running an older version, shut it down. Wait until it has completely
shut down (which might take a few minutes for older versions), then run the 
installer (on Windows) or just copy over `/Applications/Beyondcoin-Qt` (on Mac)
or `beyondcoind`/`beyondcoin-qt` (on Linux).

Compatibility
==============

Beyondcoin Core is extensively tested on multiple operating systems using
the Linux kernel, macOS 10.8+, and Windows Vista and later. Windows XP is not supported.

Beyondcoin Core should also work on most other Unix-like systems but is not
frequently tested on them.

0.15.2 Change log
=================

### Validation
- `15e8103` Update checkpoints (Tech1k)
- `ed74e01` [Fix]: Build error in chainparams.cpp (Tech1k)
- `5ad7172` Update hardcoded seeds (Tech1k)
- `e78c6b5` Update chainparams (Tech1k)

### Wallet
- `735de4d` Update Denominations (Tech1k)

### Miscellaneous
- `59a925` Fix grammar (Tech1k)
- `ccaeaef` Fix typo (Tech1k)
- `a6f84cf` Update release notes and manpages for v0.15.2 (Tech1k)
- `e54ac50` Update link in src/init.cpp (Tech1k)
- `34ab2f9` Update readme (Tech1k)
- `01433c2` Add Tech1k gpg key (Tech1k)

Credits
=======

Thanks to everyone who directly contributed to this release:

- Kristian Kramer
