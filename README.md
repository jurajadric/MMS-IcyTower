Ovo je dorada projekta iz 2020/21.

## Linkovi na prehodne verzije  
[2020./2021.] https://github.com/katarinasupe/MMS_IcyTower 

[2019./2020.] https://github.com/pimaja/Mulitimedia-Systems-Icy-Tower-Game-Extension (nadogradnja)
 
[2018./2019.] https://github.com/bderic1/MMS-IcyTower (originalni projekt)

## Dorade  
U ovoj verziji napravljene su sljedeće promjene:  
  -ispravljena imena varijabli, tako da se kod može kompajlirati (pretpostavljam da je var u međuvremenu postala keyword u Processingu)  
  -popravljen tematski bug gdje se prikazuje animacija uplašenog lika kada se nalazi na rubu platforme - animacija se više ne prikazuje ako platforma na kojoj se lik nalazi ide preko cijele širine ekrana (na prvoj platformi, i svakoj koja je višekratnik od 50)  
  -dodan novi lik uz Harolda i Davea - (Wild) Wendy  
  -popravljeno poravnanje teksta u main menu, kao i na screenEnd zaslonu pomoću funkcija imageMode(CORNER) i zericu hardcodiranja - vremenom se rodila greška gdje je poravnanje prilikom pokretanja igre bilo dobro na main menu, no nakon odigrane igre bi se poremetilo na screenEndu, ali i na main menu  
  -više manjih popravaka/modifikacija koda  
  
## Daljnja poboljšanja  
Preporuke za iduću nadogradnju:  
  -organizirati postojeće likove u igri u neku strukturu za lakše dodavanje novih  
  -dodati nove likove  
  -prebaciti kodom generirane platforme u izvorne spriteove  
