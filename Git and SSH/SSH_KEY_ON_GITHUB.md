# SSH KEY ON GITHUB
**Samir Zurita**

![SSH ON TERMINAL](https://lh3.googleusercontent.com/pH5F_x-w_KCLIL-LgXX7EGpJMHKfUshKIQkxaqppd6MfxON-8IyCqi91t0RW9M3qzQ)

---

### **ACTIVATE SSH KEY ON GITHUB**

To activate the SSH key on Github, it is necessary to locate the folder in wich the generated SSH keys are found.

We have to enter the main directory or   home directory, for this we will enter the following command in the terminal:

```
cd ~
```

Inside the directory we will look for the hidden ssh folder, which can be found with the command: 

```
ls -a
```

Within the list of directories we will find one with the following name: `.ssh/`

we enter the folder with the command: 

```
cd .ssh/
```

---

Inside the directory we will find a private key and a public key, these will look like this: 

- `id_ed25519`
- `id_ed25519.pub`

*The key with the .pub extension is the public key*

the following command is used to display the public key: 

```
cat id:ed25519.pub
```
Once the command is executed, the public key will be displayed, which will be used in github. 

---

#### **ACTIVATION ON GITHUB**

![Github SSH](https://play-lh.googleusercontent.com/PCpXdqvUWfCW1mXhH1Y_98yBpgsWxuTSTofy3NGMo9yBTATDyzVkqU580bfSln50bFU)

---

To activate the public key on Github, we must follow these steps: 

1. Login to [Github](https://github.com)
2. Go to settings
3. Find the section of `SSH and GPG keys`
4. Inside `SSH and GPG keys` put in `Add new SSH Key`
5. Assign a title to the password (* can be the username and the date the password is entered *) 
6. Inside the text field, paste the public key that was displayed with the command `cat`. 
7. Click on Add SSH key 

Done, the public key is already activated on Github. 

