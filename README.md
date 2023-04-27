# Cryptography

Creating a text file Saketh_msg.txt with a message.

Commands to encrypt a file
openssl enc -aes-256-cbc -in Saketh_msg.txt -out Saketh_encrypted.txt -k file:Saketh_key.txt

Commands to decrypt a file
openssl enc -d -aes-256-cbc -in Saketh_encrypted.txt -out Saketh_decrypted.txt -k file:Saketh_key.txt
