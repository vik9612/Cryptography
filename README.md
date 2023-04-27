# Cryptography

Creating a text file Saketh_msg.txt with a message.

Commands to encrypt a file
openssl enc -aes-256-cbc -in Saketh_msg.txt -out Saketh_encrypted.txt -k file:Saketh_key.txt

Send the Public Key file "Saketh_Key" and Encrypted message "Saketh_encrypted" across.

Commands to decrypt a file
openssl enc -d -aes-256-cbc -in Saketh_encrypted.txt -out Saketh_decrypted.txt -k file:Saketh_key.txt
