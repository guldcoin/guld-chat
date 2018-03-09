## Grants


#### [How to sign guld work grants.](http://guld.chat/4-FAQ.html)

guld is a meritocracy, meaning that the guld coins are only created through sweat and work of guld members. 

When you complete work for guld, you can be awarded coins through grant contracts. Grants must be approved by guld creator `Isysd` for coins to be issued.

## Signing a guld grant.

Depending on your operating system, the signing process will be a bit different.

[Here you will find how to use PGP for signing your work grant.](http://guld.chat/4-FAQ.html)

To sign a grant, you must:

1. Open up a conversation with gai, be it on a private message, or in the guld group, or a support group. Hit the 'send' button to prepare a send transaction. 
2. Write the transaction format `/send from to ammount` to ask gai for a specific transaction. He will produce a file and a text chat. 
3. You can copy the text chat to your clipboard, or paste into a text editor to prepare for signing.
4. Once you sign the transaction, you must `/sub <Signed Tx>` submit the transaction in a message to gai. He will recognize whether or not the debtor actually owns the signing key.
5. `Isysd` will need to approve your transaction, but if he does, you will be granted guld.
6. you can check your guld balance with gai by typing `/bal`


Grant formats look like this: 

```
2018/03/07 * grant for work done
    ; timestamp: 1520398947
    username:Assets   5 GULD
    username:Income   -5 GULD
    guld:Liabilities   -5 GULD
    guld:Equity:username   5 GULD
```


And the signed submitted transactions would look like the following, preceded by the `/sub` command.

```
/sub -----BEGIN PGP SIGNED MESSAGE-----
Hash: SHA256

2018/03/07 * grant for work done
    ; timestamp: 1520398947
    username:Assets   5 GULD
    username:Income   -5 GULD
    guld:Liabilities   -5 GULD
    guld:Equity:username   5 GULD
-----BEGIN PGP SIGNATURE-----

iQEzBAEBCAAdFiEEflQyPEoSv2olnyuG+mKOtSEPRCcFAlqfLEkACgkQ+mKOtSEP
RCdS7wf+N83XEWjnpc5eUdx/5b4KZeqiDco8LsI4eOxXfhyay/vqsWSCmFMRsW9w
K6yI4N/CAoAlQIHEnzlhlKlABmo5Ak4leHSG9w/a3xaq3eOC8OHL6lGMETdL4gvR
8TuaQZSLSTY+DJqXZs8lIx0cPDVh1rs5NqvOLLIYhU3zOu0avQ18MRB1+Q8KiScN
hEGkn6xWJvk5FQ5YK4yEeNjYVkDNXMvUrBSHjxNH8CiEtOp9mdoYwQ8FlM2bp0cS
dZURFQFhcGq/YrRRNbT/2Lfg20R3YQgn4FwMfq/usVh1bjOZSJF3i3W/6Gdtn5Xw
2zFClbTptF1qtTogRw8v1PNTxhNXgA==
=JQb+
-----END PGP SIGNATURE-----
```


#### More Questions

If you have any questions: [Join the guld support Telegram group](https://t.me/joinchat/EKTIchEMTw-lRYBFNbumnA) - Our support team will gladly help you out!



