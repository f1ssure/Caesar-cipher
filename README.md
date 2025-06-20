# Decrypt-Caesar-ciphertext
Python script to decipher the Caesar ciphertext (all letters are rotated alphabetically by a constant amount of positions).
 
**Usage:**

1. Install *Python* if you don't have it on your system.

2. Save the *decrypt.py* script file in some kind of local directory on your device.

3. Go to that directory in *Command Prompt* (Windows) or *Terminal* (Mac).

4. From there, type out the command below and hit 'Enter' (after *decrypt.py*, the ciphertext itself comes):

**Windows**
```
  py decrypt.py <YOUR CIPHERTEXT>
```

**macOS**
```
  python3 decrypt.py <YOUR CIPHERTEXT>
```

The command above will list all the possible plaintexts that could have been encrypted along with a percentage, that indicates the likeliness of it (the most natural plaintexts come up first)

If you only need the **most likely** plaintext to be outputted, then add the argument '-one' before the ciphertext like this (example for **macOS**):
```
  python3 decrypt.py -one <YOUR CIPHERTEXT>
```
