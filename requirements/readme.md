List of dependencies [![Requirements Status](https://requires.io/github/SickRage/SickRage/requirements.svg?branch=develop)](https://requires.io/github/SickRage/SickRage/requirements/?branch=develop)
======================

 Status  |  Package  |  Version / Commit  | Notes
:------: | :-------: | :----------------: | -----
:exclamation: | adba | ??? | **Modified**<br>not on PYPI - [GH:lad1337/adba](https://github.com/lad1337/adba)
:ok: | babelfish | 0.5.5 | Resolved by [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | backports_abc | 0.5
:ok: | backports.ssl-match-hostname | 3.5.0.1
:ok: | beautifulsoup4 | 4.6.0
:ok: | bencode | 1.0 | Resolved by [#3858](https://github.com/SickRage/SickRage/pull/3858) + [#3871](https://github.com/SickRage/SickRage/pull/3871)<br>A newer version (fork) is available: [GH:fuzeman/bencode.py](https://github.com/fuzeman/bencode.py)
:ok: | CacheControl | 0.11.7 | Pinned to <0.12.0 because<br>the new 'msgpack-python' dependency has C extensions.
:warning: | certgen.py | [d52975c](https://github.com/pyca/pyopenssl/blob/d52975cef3a36e18552aeb23de7c06aa73d76454/examples/certgen.py) | Source: [GH:pyca/pyopenssl](https://github.com/pyca/pyopenssl/blob/master/examples/certgen.py)
:ok: | certifi | 2017.4.17
:ok: | cfscrape | 1.7.1 | Pinned to <1.8.0 because Node.js is now required.
:ok: | chardet | 3.0.4 | Resolved by [#3870](https://github.com/SickRage/SickRage/pull/3870)
:ok: | configobj | 4.6.0
:ok: | decorator | 4.1.1
:ok: | dogpile.cache | 0.6.4
:ok: | enzyme | 0.4.1
:ok: | fake-useragent | 0.1.7
:warning: | feedparser | [f1dd1bb](https://github.com/kurtmckee/feedparser/tree/f1dd1bb923ebfe6482fc2521c1f150b4032289ec) | Vanilla'd by [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | futures | 3.1.1
:ok: | guessit | 2.1.4
:warning: | hachoir_core | [708fdf6](https://bitbucket.org/haypo/hachoir/src/708fdf64a982ba2e638aa59d94f143112066b8ce/hachoir-core/hachoir_core/) | Bitbucket
:warning: | hachoir_metadata | [708fdf6](https://bitbucket.org/haypo/hachoir/src/708fdf64a982ba2e638aa59d94f143112066b8ce/hachoir-metadata/hachoir_metadata/) | Bitbucket
:warning: | hachoir_parser | [708fdf6](https://bitbucket.org/haypo/hachoir/src/708fdf64a982ba2e638aa59d94f143112066b8ce/hachoir-parser/hachoir_parser/) | Bitbucket
:ok: | html5lib | 1.0b10
:ok: | httplib2 | 0.10.3
:ok: | idna | 2.5 | Added in [#3870](https://github.com/SickRage/SickRage/pull/3870)
:warning: | IMDbPY | 5.1.1 | Resolved by [#3877](https://github.com/SickRage/SickRage/pull/3877)<br>**Still can't install this from requirements.txt**,<br>because we need to be able to use `--no-deps`, but it's unsupported in the context of requirement files.<br>A workaround seems to be to use `pip install --no-deps -r requirements.txt`, which is fine as long as we list ALL dependencies (which is planned).<br>Also, I don't think `install_requires` in `setup.py` supports anything more than simple package version constraints, maybe VCS sources (git/mercurial/etc..) - untested.
:warning: | js2py | [05e77f0](https://github.com/PiotrDabkowski/Js2Py/tree/05e77f0d4ffe91ef418a93860e666962cfd193b8)
:ok: | jsonrpclib | 0.1.7
:warning: | libgrowl | - | **Custom by Sick-Beard's midgetspy**<br>Some of the code is from [GH:kfdm/gntp](https://github.com/kfdm/gntp)
:warning: | libtrakt | - | **Custom**<br>Just a small note -<br>if needed, [GH:fuzeman/trakt.py](https://github.com/fuzeman/trakt.py) is a great implementation of Trakt.tv's API.
:ok: | Mako | 1.0.7
:ok: | markdown2 | 2.3.4 | Resolved by [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | MarkupSafe | 1.0
:ok: | oauthlib | 2.0.2 | Added in [#3870](https://github.com/SickRage/SickRage/pull/3870)
:ok: | pgi | 0.0.11.1 | Not installed on Windows (\*nix only library)
:exclamation: | pkg_resources.py | - | Copied from setuptools and looks to be modified.<br>Used to load `pymediainfo*.egg` and `pytz*.egg` as packages.<br>Also explicitly used by: `babelfish`, `dogpile.cache`/`dogpile.util`, `enzyme`, `guessit`, `Mako`, `pymediainfo`, `pytz`, `stevedore`, `subliminal`.
:ok: | profilehooks | 1.9.0
:ok: | putio.py | 7.0.0
:ok: | PyGithub | 1.35
:ok: | PyJWT | 1.5.0 | Added in [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | pymediainfo | 2.0 | as an `.egg` file, loaded by `pkg_resources`
:ok: | pynma | 1.0
:ok: | PySocks | 1.6.7 | Added in [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | pysrt | 1.1.1
:ok: | python-dateutil | 2.6.1
:exclamation: | python-fanart | 1.4.0 | **Modified**<br>API url was updated. No newer version.
:ok: | python-twitter | 3.3 | Updated in [#3870](https://github.com/SickRage/SickRage/pull/3870)
:ok: | pytz | 2017.2 | as an `.egg` file, loaded by `pkg_resources`
:warning: | rarfile | [c074828](https://github.com/markokr/rarfile/tree/c0748286f892c2c8e705df12995b7a2f4dce345b)
:ok: | rebulk | 0.9.0
:ok: | requests | 2.18.1 | Updated in [#3870](https://github.com/SickRage/SickRage/pull/3870)
:ok: | requests-oauthlib | 0.8.0 | Added in [#3870](https://github.com/SickRage/SickRage/pull/3870)
:exclamation: | rtorrent-python | 0.2.9 | **Modified**<br>See [commits log for `lib/rtorrent`](https://github.com/SickRage/SickRage/commits/master/lib/rtorrent)
:exclamation: | send2trash | 1.3.0 | **Modified**<br>See [`9ad8114`](https://github.com/SickRage/SickRage/commit/9ad811432ab0ca3292410d29464ce2532361eb55)
:ok: | singledispatch | 3.4.0.3
:ok: | six | 1.10.0
:ok: | stevedore | 1.19.1 | Pinned to <1.20.0 -- see [Diaoul/subliminal#780](https://github.com/Diaoul/subliminal/pull/780)
:warning: | subliminal | [7eb7a53](https://github.com/Diaoul/subliminal/tree/7eb7a53fe6bcaf3e01a6b44c8366faf7c96f7f1b) | **Modified**<br>Subscenter provider disabled until fixed upstream, [#3825 `diff-ab7eb9b`](https://github.com/SickRage/SickRage/pull/3825/files#diff-ab7eb9ba0a2d4c74c16795ff40f2bd62)
:warning: | synchronous-deluge | - | **Custom: by Christian Dale**
:ok: | tmdbsimple | 0.3.0 | Note: Package naming is modified.
:ok: | tornado | 4.5.1 | Note: Contains a `routes.py` file,<br>which is not a part of the original package
:ok: | tus.py | 1.3.0
:exclamation: | tvdb_api | 1.9 | **Heavily Modified**<br>Deprecated API, will be disabled by October 1st, 2017
:ok: | twilio | 5.7.0 | Next version is a major (6.0.0)
:ok: | tzlocal | 1.4 | Resolved by [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | Unidecode | 0.04.21 | Updated in [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | urllib3 | 1.21.1 | Added in [#3870](https://github.com/SickRage/SickRage/pull/3870)
:ok: | validators | 0.10
:ok: | webencodings | 0.5.1
:ok: | win-inet-pton | 1.0.1 | Required for PySocks on Windows systems<br>Added in [#3877](https://github.com/SickRage/SickRage/pull/3877)
:ok: | xmltodict | 0.11.0 | Resolved by [#3877](https://github.com/SickRage/SickRage/pull/3877)

***

:heavy_minus_sign: Removed libs:
-------------

 Package  |  Reason  | Reference
:-------: | :------: | ---------
dogpile.core | EOL | (Merged into dogpile.cache upstream)
enum34 | Unused | (Was a dependency of `chardet`, but isn't anymore)
LockFile | Deprecated | (Is an extra dependency of CacheControl, but wasn't being used)
MultipartPostHandler.py | Unused | Removed in [#3716](https://github.com/SickRage/SickRage/pull/3716)
ndg-httpsclient | Unused | Added [with pyOpenSSL when it was added](https://github.com/SickRage/SickRage/commit/69cd6cf8eaaf3193434e77956639eb237419bb63), but wasn't removed when [pyOpenSSL was removed](https://github.com/SickRage/SickRage/commit/78c8b5e17db3478e9580292463478c6250b62ac1).
oauth2 | Outdated | Removed in [#3870](https://github.com/SickRage/SickRage/pull/3870)
pyasn1 | Unused | Added [with pyOpenSSL when it was added](https://github.com/SickRage/SickRage/commit/69cd6cf8eaaf3193434e77956639eb237419bb63), but wasn't removed when [pyOpenSSL was removed](https://github.com/SickRage/SickRage/commit/78c8b5e17db3478e9580292463478c6250b62ac1).
simplejson | Unused | Removed in [#3877](https://github.com/SickRage/SickRage/pull/3877)
SocksiPy | Outdated | Replaced with PySocks in [#3877](https://github.com/SickRage/SickRage/pull/3877)
SQLAlchemy | Unused
sqliteshelf.py | Unused | Removed in [#3716](https://github.com/SickRage/SickRage/pull/3716)
