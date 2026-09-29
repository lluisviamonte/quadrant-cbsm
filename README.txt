QUADRANT CBSM v5 SINCRONITZADA

Aquesta versió manté GitHub Pages com a app i utilitza Firebase per sincronitzar dades.

PASSOS:
1. Puja tots els fitxers d'aquesta carpeta al repositori de GitHub Pages i substitueix els anteriors.
2. A Firebase > Firestore Database > Reglas, copia el contingut de firestore.rules.txt i prem Publicar.
3. Obre l'app al PC i inicia sessió amb l'usuari que has creat a Firebase Authentication.
4. Obre l'app a l'iPhone i inicia sessió amb el mateix usuari.
5. A partir d'aquí, les setmanes i els partits se sincronitzen entre els dos dispositius.

UID autoritzat:
EY9wXGdbKONum3VvAIrXvaBJz0Z2

NOTES:
- La contrasenya no queda escrita dins l'app.
- Firebase Authentication recorda la sessió al dispositiu quan el navegador ho permet.
- El guardat local continua funcionant com a còpia/offline.
- Si no hi ha internet, els canvis queden locals i l'app intenta sincronitzar quan torna la connexió.
