# Project-Invisible
Sistema de transmision (RF) com cifrado hibrido 
Sistema de transmissão de audio utilizando criptografia asimetrica (RSA), sem deixar metadados (apenas baseados em uma sessão temporaria do
usuario)

O = original message

F = final message 

E = encrypt session with public key 

e = unique hash (based in temporary id) to avoid corruption (in case of corruption, re-transmission P2P of package(beta)) 







A(E(e)) --- Device verify(e)-(E-decrypt(E)-- O(F)   



