# YiimpyAlert / WalletNotify
Get alert-, block- or  wallet-notifications on your smartphone in realtime.

Example wallet.conf:

`alertnotify=echo %s | python3 yiimpyalert.py`

or 

`walletnotify=echo %s | python3 yiimpyalert.py`


ATTENTION:

Commands can only be send when piped with echo, etc.

Don't use them as a parameter, like: yiimpyalert.py %s
