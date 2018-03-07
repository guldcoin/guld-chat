## Transfers

You can use gai to send GULD transactions to any other user on the network. All you need is your user name, your [PGP key for signing](http://guld.chat/4-FAQ.html), and the username of the person who you want to send GULD to.

#### Sending guld

1. You will need to have [1. Applied](http://guld.chat/3-transactions/1-Application.html) , and [Registered to guld](http://guld.chat/3-transactions/2-Registration.html). before you can send transactions in Telegram through `gai`.

2. Ask gai for a transaction by using the `/send` command. You must include in the request
 * your username name 
 * recepient's username 
 * ammount of guld to send 
 
Sending the following command to gai `/send usernamesender receiver 5` will produce the following transaction:

```
2018/03/06 * transfer
    ; timestamp: 1520379308
    usernamesender:Assets   -5 GULD
    usernamesender:Expenses   5 GULD
    receiver:Assets   5 GULD
    receiver:Income   -5 GULD
```


3.  Copy this text into your key manager, and sign the transaction using the key registered to the username in the first space of the command. to produce a text output like the following. 
preface the Transaction with `/sub` to submit the transaction to gai.

The transaction submitted to gai must look like this:

```
/sub -----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

2018/03/06 * transfer
    ; timestamp: 1520379308
    usernamesender:Assets   -5 GULD
    usernamesender:Expenses   5 GULD
    receiver:Assets   5 GULD
    receiver:Income   -5 GULD
-----BEGIN PGP SIGNATURE-----

iQEzBAEBCAAdFiEEflQyPEoSv2olnyuG+mKOtSEPRCcFAlqe4GAACgkQ+mKOtSEP
RCelxgf/WwIl9P/GJ11RA4eU2Eh6TPuUi3quZLQqGaiATc82+fxj5Ca2nRRnTfTM
j5fzcrnZGOZ6y4RTrDMkJuQBCbr4bJJky0pELJaU2v8NGnHC4HTXS7CjdlZ/J2Cd
OhCgEyL/guGf2MYJp1fXvrfK1fsG3WvtK6Ef3wa5nBdGp9xXblUtlUJ172lQllJ3
6N6QswHGfSPMxtoovKHUAmVVS33CDN4EL8TxVVtnSf+BN3s+ooBv0IQjeTdyssna
KWGD/478qiLAU4TCMHo/ytNBla/terpHdP09YWLfBrV4pQyqY0zaMR5rG3dlQeO9
Wccqxxjm/bXftGsGclZRhureNGeteQ==
=K+7Q
-----END PGP SIGNATURE-----

``` 

#### Checking Balance
Once a transaction been submitted, the involved accounts should reflect the changes on their balance.

you can check the new balance of the debtor, and recipient account by typing either username after the `bal` command.

You can have the data presented in `Dash`, `BTC`, `ETH` or USD by Typing `$`  after the username. Guld is the default unit of measurement.

`/bal username $` would give the dollar value of the account and `/bal username BTC` would show the nearest Bitcoin conversion.
 
#### More Questions

If you have any questions: [Join the Guld Support Telegram Group](https://t.me/joinchat/EKTIchEMTw-lRYBFNbumnA) - Our support team will gladly help you out!
