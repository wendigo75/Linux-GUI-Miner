LinuxGUIMiner

No need installation simply copy it in miner folder (if have more than one miner) or desktop.

NEVER RENAME IT or the file will not save changes or reload default settings.

It's a simple bash code with minimal buttons to select default parametres for the miner.

Settings are:
Miner: choose the miner to launch inside his path.
URL: paste here the url from the pool i.e. stratum+TCP://poolurl.url:3333
USERNAME: write here the username used in pool login; it can be mail, walletaddress, username
PASSWORD: write here password if needed in pool or leave it blank
ALGO: write here the algorith to use for mining i.e. Scrypt, YespowerR166, sha256 etc. In compilance with miner settings.
EXTRA: write here extra command line if needed i.e. -api-bind 0, -freq=100 etc.

This scrypt symply invoke the selected miner command and pass parametres to the command line so selected miner must respect this:
URL (-o)
USER (-u)
PASSWORD (-p)
ALGO (-a)
EXTRA (--extra)

It not works with XLA or XMRIG miners for the different displayed text, or else it works with them but output window is unreadable!
