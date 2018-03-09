## Registration

#### **Registering a username on [guld](http://guld.chat/) - Invitation Only**

 [Once you have applied for your individual or group username with gai in the telegram chat](http://guld.chat/3-transactions/1-Application.html) You will need to sign a guld registration transaction.

 Follow these steps to send your first signed transaction to gai.

1. Send a message to gai in the [guld Telegram chat](https://t.me/guldcoin) or [support group](https://t.me/joinchat/EKTIchEMTw-lRYBFNbumnA), or in a direct message finding `gai` in the guld user list in any of the groups he is in. 
 
1. To register type the command `/register individual username`, where username is your desired name.

2. gai will create a transaction like the following for you to sign.

```
2018/03/06 * register individual
    ; timestamp: 1520397978
    username:Assets   -1 GULD
    username:Expenses:guld:register   1 GULD
    guld:Liabilities   1 GULD
    guld:Income:register:individual:username   -1 GULD
```
3. [See the guide here on how to sign the transaction]() in order to produce a transaction like the following, preceded by the `/sub`  submit command.

```
/sub -----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

2018/03/06 * register individual
    ; timestamp: 1520397978
    username:Assets   -1 GULD
    username:Expenses:guld:register   1 GULD
    guld:Liabilities   1 GULD
    guld:Income:register:individual:username   -1 GULD
-----BEGIN PGP SIGNATURE-----

iQEzBAEBCAAdFiEEflQyPEoSv2olnyuG+mKOtSEPRCcFAlqfKK0ACgkQ+mKOtSEP
RCeGKAf/X8Wd5hVsX7HFcgmQrHgHGh45kj5x1LyEL9SFEve3nPHZQGclD19PeHrx
DMJQtm88u5AHUEuIlDCirdG0JWBK/UdJOIFmTQGlDNQg+vGFM3rAtYzxMtDyxPci
DUauwCPIYdNpTmGPVwG2J3KhRB4dYnoSN2slIoomsymaYgF+Shv/f3v87tcbGA6j
xY55U+Y7WjHXocpini9weJmDT0wL1ZjBhgp/86JW7sQv/gZRENatkEMvO5DSTE7l
9JEPz0KH11imBdgHxMEj7R2NhNUOFIiby33FcmAxcQfM4kVGyZrzi5hmfw2Et6j0
/jz5FQQ4QgJBOWaWkbO4ZGTtkM3z2w==
=R7VP
-----END PGP SIGNATURE-----

```

4. You are now registered, but your balance is -1 [GULD](guld.io). Before going on you'll want to buy at least 1 [GULD](guld.io) from some other member, to put you back in good standing.

5. You can check how much guld you have by using the `/bal username` command followed by your username. 

6. Congratulations! You now have a functioning secure guld account. [You can start sending and receiving guld](http://guld.chat/3-transactions/3-Transfers.html)


#### More Questions

If you have any questions: [Join the guld support Telegram group](https://t.me/joinchat/EKTIchEMTw-lRYBFNbumnA) - Our support team will gladly help you out!

