QUADRANT CBSM v6.1 MULTIUSUARI

QUÈ CANVIA
- Tots els usuaris autoritzats treballen sobre el mateix quadrant.
- Canvis de PC, iPhone o altres dispositius se sincronitzen amb Firebase.
- L'administrador principal pot crear nous usuaris des de la mateixa app.
- També pot revocar-los l'accés.
- El guardat local/offline continua actiu.
- Les dades de la v5 de l'administrador es migren automàticament al primer inici.

ADMINISTRADOR PRINCIPAL
UID: EY9wXGdbKONum3VvAIrXvaBJz0Z2

ABANS D'UTILITZAR-LA
1. Puja TOTS els fitxers del ZIP al repositori de GitHub Pages, substituint els anteriors.
2. Firebase > Firestore Database > Reglas.
3. Copia el contingut de firestore.rules.txt.
4. Prem Publicar.
5. Obre l'app i comprova que posa “v6 multiusuari”.
6. Inicia sessió amb el teu usuari actual.
7. A “Usuaris amb accés” pots posar correu + contrasenya inicial i crear un usuari.
8. La persona nova inicia sessió a la mateixa app amb les seves credencials.

IMPORTANT
- Revocar l'accés des de l'app elimina el permís per veure/modificar el quadrant.
- El compte pot continuar apareixent a Firebase Authentication; això no li dona accés sense el document de membre.
- No comparteixis la teva contrasenya d'administrador.


MILLORA v6.1
- Si un mateix equip té 2 o més partits dins la mateixa setmana, ara apareixen TOTS al quadrant “Partits de la setmana”.
- La cel·la de l'equip queda agrupada i els diferents partits surten en files separades.
