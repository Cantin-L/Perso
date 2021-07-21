Le protocole FTP précise que pour envoyer le mot de passe, il faut envoyer la chaîne sous la forme : PASS

"PASS" en hexa vaut "50 41 53 53 20".

Dans le fichier pcap, cherchez donc la chaîne hexa "5041535320". A partir de là, le mot de passe commence et se termine pas CRLF ("0x0D0A"). On trouve donc une chaîne "xxx" qui faudra convertir en ASCII "..."
