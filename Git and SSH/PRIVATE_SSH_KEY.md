# 
Samir Zurita
---

To activate our private key within our computer, we must enter the following command: 

```
ssh-add ~/.ssh/id_ed25519
```
once the command is entered, it will ask us to enter the secure phrase of our SSH.

After entering the safe phrase, we would have activated SSH to work with this system. 

## **¡Important!**

If we forget the passphrase, we must delete the two files inside the `.ssh` folder and re-generate the keys with a new passphrase. 