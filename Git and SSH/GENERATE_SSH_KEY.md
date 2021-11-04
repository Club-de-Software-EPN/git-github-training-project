# SSH KEY
**Samir Zurita**

![SSH](https://www.elblogdebart.com/wp-content/uploads/2019/04/ssh.jpg)
---

### **GENERATE SSH KEY**

To generate the SSH public key and private key, you need to do the following steps:

1. Open Terminal.

2. Enter the following command to generate the key  from the ed25519 algorithm.

```
ssh-keygen -t ed25519 -C "email"
```
- *The email must be the one registered in github*.

3. Select the path where you want the keys to be saved. 

4. Enter the passphrase that will serve as a password to access the SSH service. 

5. After entering the safe phrase, the word SHA256 appears in the terminal, which will show us that our safe phrase was generated. 

---

### **EVALUATE THE OPERATION OF THE SSH AGENT**

To evaluate the ssh agent, enter the following command: 

```
eval "$(ssh-agent -s)"
```
*This agent is commonly active on UNIX systems*. 

After our system evaluates the agent, it indicates the following message:
`Agent pid (number)`