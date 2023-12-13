<p align="center">
<img src="https://i.imgur.com/uxaU4CG.png" height="30%" width="60%" alt="Kali logo"/>
</p>

<h1>Changing the encryption key</h1>
In this tutorial, we will be changing the initial encryption key seen in the previous demonstration. <br />


<h2>Environments and Technologies Used</h2>

- Oracle VirtualBox (Virtual Machines/Computer)
- Kali Linux Shell

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2>Implementation Steps</h2>

<p>
<img src="https://imgur.com/f75OQ4G.png" height="80%" width="80%" alt="Key Change Steps"/>
</p>
<p>
  
1. Run the following command to initiate change of the encryption key. (ccrypt -x encryptiontest.cpt)
2. When prompted to enter the old encryption key, type 1827390 or any other key that you used for encryption, and then press Enter. When prompted to enter a new encryption key, and then press Enter. Repeat this step when prompted to reenter the new key.
3. Now use the ccat encryptiontest.cpt command to confirm that the new encryption key works.

When prompted to enter the new decryption key, type it, and then press Enter. The plaintext content of the file is displayed, confirming that the new encryption key works.
</p>
<br />

