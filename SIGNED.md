##### Signed by https://keybase.io/max
```
-----BEGIN PGP SIGNATURE-----
Version: GnuPG/MacGPG2 v2.0.22 (Darwin)
Comment: GPGTools - https://gpgtools.org

iQEcBAABCgAGBQJTj4+mAAoJEJgKPw0B/gTfghoH/1Mz/RMWA/IuceqHQ2BDpSlq
Z7PAMtZtPIGJqjl+UbBiHYNUrWgiJw2LDpM9wYW6SQ3PS+QwZxNdDYbTpCAPd7G+
ZnZTtBHYjv0143GZdQynFTRdCJuvfHrMPVW5f74DkXQ6O3Pheo4kAyAa8Jz4mFmQ
OBNBMfQKoacr1CLQTxQtDxn3h22ufMQwrMBik+eRTBHL5o7miavpH9Xvs/fnaPc5
42PxOr65ohBDBrHsaOeQaxabhuGMOsvj1OVXN+H2fAhXacjLC5PAgJIWtz5KYlIq
zunadcTiu/7+1Ai0R1lTzOqhT9J0/DIMaAOrFpDvyORmfgK0/cpAZhqpteCqqNs=
=dGTM
-----END PGP SIGNATURE-----

```

<!-- END SIGNATURES -->

### Begin signed statement 

#### Expect

```
size  exec  file              contents                                                        
            ./                                                                                
547           .gitignore      a3260451040bdf523be635eac16d28044d0064c4e8c4c444b0a49b9258851bec
165           CHANGELOG.md    5d865e22f9ce7006548560cb8ddb55cf9ea534bbc5ef06a7466e15dac4f0b3c8
1062          LICENSE         f5f4ff3d4bd2239d1cc4c9457ccee03a7e1fb1a6298a0b13ff002bee369bf043
407           Makefile        32e05964b75b43fd5492411f781568a8e8ea25f1ec9c12ddc795868549d231f6
56            README.md       0bd4207a9490a68de9a1b58feac0cdeff349eaa778c8a0eaf859d07873026b07
              lib/                                                                            
916             const.js      bee1762e6130dd8167212f07dda3c6416116d2e87fc364e8fce4ef80214b2da6
8917            library.js    37ab82fb064111b42497ad8c93d3aef595fc9883cb61a4a1d424ff7ae5cb5447
348             main.js       f29a1669ebc50cbda9dec9685acfb4af2248f48b997d823b43bb28671ba8b6f4
5461            runtime.js    b12348f2062b5cf3d8a46b5a99f9d50578ef01566e0c2df00cbd842e93b0661e
621           package.json    a702a742ffa314d1456f8c3100b0414d7ec0b947e8c9d9f78830ae5ce33f4587
              src/                                                                            
785             const.iced    cce728a752c7b9bdaa0cee2466a4e996d525dc27804a1de68ed588be4f82c205
3881            library.iced  2acf49cd6eceae202a162af11b98b4faf5cd2bcee186cad669b59a2d22643dda
142             main.iced     bb74f97e5473e7f9b5f79264f3a3ba7126a4849d97fd37c49dfdbb711120e314
5280            runtime.iced  6f5b8096866ee3834463eea201153a5582d1927a611d51da45f71e6002978de7
```

#### Ignore

```
/SIGNED.md
```

#### Presets

```
git      # ignore .git and anything as described by .gitignore files
dropbox  # ignore .dropbox-cache and other Dropbox-related files    
kb       # ignore anything as described by .kbignore files          
```

<!-- summarize version = 0.0.9 -->

### End signed statement

<hr>

#### Notes

With keybase you can sign any directory's contents, whether it's a git repo,
source code distribution, or a personal documents folder. It aims to replace the drudgery of:

  1. comparing a zipped file to a detached statement
  2. downloading a public key
  3. confirming it is in fact the author's by reviewing public statements they've made, using it

All in one simple command:

```bash
keybase dir verify
```

There are lots of options, including assertions for automating your checks.

For more info, check out https://keybase.io/docs/command_line/code_signing