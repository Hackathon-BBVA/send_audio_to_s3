# send_audio_to_s3
code in js create a process to send a audio file to s3 storage

Create a directory
mkdir projects/bbvaHackaton

cd ~

sudo apt-get update
sudo apt-get upgrade
sudo apt install nodejs
node -v
sudo apt install npm
npm -v

otorgar permisos de owner para comunicar visual code con WSL
sudo chown -R user(jkrm) ~/projects

sudo apt-get update
sudo apt-get upgrade
sudo apt install git

Crear código de seguridad que nos conecta a github
rsa: protocoo de ecriptación(tipo de algoritmo) b: cantidad de bits
ssh-keygen -t rsa -b 4096 -jrodriguezm216@gmail.com 

se genera el key fingerprint
The key fingerprint is:
SHA256:dm1yYMG1ZqpHUR0rtPKCKfqcegHNGUR(private) jkrm@DESKT(public)

luego se evalua si está corriendo un ssh-agent
eval "$(ssh-agent -s)"

agarra la llave pública y lo copia.
ssh-copy-id jrodriguezm216@gmail.com

nos dirigimos a cd ~/.ssh
copiamos el contenido que se encuentra dentro de cat id_rsa.pub

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAACAQDRY4trnWhILTWXEvUDkCDKehyZ5u3KxN3fwXZeEVx+49MEgsysVHtK0ur3/MHbFlbiB8wo6/cmjvRkRZDz0/1GA5oVPt5HLQ3CGpO6UTi7uJQUeKiW2nw2jSD2PEM7nF9QxX1AcKQbKuNiKxAdHXLLtj/fsnRDkxv1iToKvZcr/yXMs0SIlEP+d8CRWic/iOO9k6wYzUu3QTMNZyflf+IbaQ7UOPIFaSaW87MFUBSYY43GJfB2xfpAOJCIa/fyJ71C/OkhcDCNSHwVr3mJtgUuN5o5rRmoIIEdcN/4okUHmY++D80xNzFBrwqo7ge4NmttWZqCHSH4aKstZEuy8UJO1g4Le9WpOuVWnaa0btQ2FjqGPHGx5yJWAMK2aHg3rnhqCwW6OpLwXRpuoFXoyJDLPbRUyS/ughOHsLGqhPoLrBzc4Qw4xQPCGV7jkNvoOomlI7yFMN1t1juXeNbG+i/V8DmZHT7FY5tJMfxFoQpkL8W0nKET5S


