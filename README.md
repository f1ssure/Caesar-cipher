# Decrypt-Caesar-ciphertext
Python script to decipher the Caesar ciphertext (all letters are rotated alphabetically by a constant amount of positions).
 
**Usage:**

1. Install *Python* if you don't have it on your system.

2. Save the *decrypt.py* script file in some kind of local directory on your device.

3. Go to that directory in *Command Prompt* (Windows) or *Terminal* (Mac).

4. From there, type out the command below and hit 'Enter' (after *decrypt.py*, the ciphertext itself comes):

**Windows**
```
  py decrypt.py 'YOUR CIPHERTEXT'
```

**macOS**
```
  python3 decrypt.py 'YOUR CIPHERTEXT'
```

The command above will list all the possible plaintexts that could have been encrypted along with a percentage, that indicates the likeliness of it (the most natural plaintexts come up first)

If you only need the **most likely** plaintext to be outputted, then add the argument '-one' before the ciphertext like this (example for **macOS**):
```
  python3 decrypt.py -one 'YOUR CIPHERTEXT'
```
**Important!**

Using argument '-one' might result in a false decryption, for example:

Trying to decrypt 'Hufaopun pz Sprlsf!!' with '-one' argument outputs: 'Wjupdejc eo Hegahu!!', while it *probably* should've been: 'Anything is  Likely!!'

Without '-one' argument we would get the following list (percentages aren't yet implemented):
```
 % python3 decrypt.py -one 'Hufaopun pz Sprlsf!!'
 Wjupdejc eo Hegahu!!    // Fakeness score: 0
 Anything is Likely!!    // Fakeness score: 0
 Qdojxydw yi Byaubo!!    // Fakeness score: 3
 Gteznotm oy Roqkre!!    // Fakeness score: 3
 Nalguvat vf Yvxryl!!    // Fakeness score: 6
 Mzkftuzs ue Xuwqxk!!    // Fakeness score: 9
 Sfqlzafy ak Dacwdq!!    // Fakeness score: 9
 Hufaopun pz Sprlsf!!    // Fakeness score: 10
 Lyjestyr td Wtvpwj!!    // Fakeness score: 10
 Repkyzex zj Czbvcp!!    // Fakeness score: 10
 Vitocdib dn Gdfzgt!!    // Fakeness score: 10
 Bozuijoh jt Mjlfmz!!    // Fakeness score: 10
 Cpavjkpi ku Nkmgna!!    // Fakeness score: 10
 Kxidrsxq sc Vsuovi!!    // Fakeness score: 11
 Uhsnbcha cm Fceyfs!!    // Fakeness score: 12
 Ivgbpqvo qa Tqsmtg!!    // Fakeness score: 13
 Pcniwxcv xh Axztan!!    // Fakeness score: 13
 Tgrmabgz bl Ebdxer!!    // Fakeness score: 13
 Xkvqefkd fp Ifhbiv!!    // Fakeness score: 13
 Ercxlmrk mw Pmoipc!!    // Fakeness score: 13
 Jwhcqrwp rb Urtnuh!!    // Fakeness score: 14
 Dqbwklqj lv Olnhob!!    // Fakeness score: 14
 Obmhvwbu wg Zwyszm!!    // Fakeness score: 15
 Ylwrfgle gq Jgicjw!!    // Fakeness score: 15
 Fsdymnsl nx Qnpjqd!!    // Fakeness score: 17
 Zmxsghmf hr Khjdkx!!    // Fakeness score: 18
```
