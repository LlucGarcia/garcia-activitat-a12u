# Activitat: Afegir una llicència al teu repositori a GitHub

## **Objectiu de l’activitat**

En aquesta activitat aprendràs a afegir un fitxer de llicència (`LICENSE`) al teu repositori GitHub, una pràctica important en la gestió de projectes de codi obert. La llicència MIT és una de les més utilitzades i permet als usuaris utilitzar, copiar, modificar i distribuir el codi amb poques restriccions.

En aquesta activitat, simularàs que estàs configurant un projecte obert i que has d'afegir una llicència per permetre que altres persones utilitzin el teu codi. Seguiràs els passos per afegir aquest fitxer de llicència mitjançant la terminal integrada de Visual Studio Code.

---

## **Temps de dedicació**

Aquesta activitat requereix aproximadament 1 hora de treball.

---

## **Què has de fer**

Els passos següents et guiaran a afegir una llicència al teu repositori de GitHub mitjançant la terminal de Visual Studio Code.

---

### **Passos a seguir:**

### 1. **Crea un repositori a GitHub**

   - Aneu a GitHub i feu clic a **New repository** per crear un nou repositori.
   - Nom del repositori: `<PrimerCognomAlumne>-activitat-a12u` (per exemple, si el teu cognom és "Martínez García", el nom del repositori serà `martinez-activitat-a12u`).
   - No afegeixis fitxers per defecte com `README`, ja que ho farem més endavant.
   - Fes clic a **Create repository** per crear-lo.

### 2. **Clona el repositori al teu ordinador**

   Obre Visual Studio Code i la seva terminal integrada. Clona el repositori que acabes de crear amb el següent comandament:

   ```bash
   git clone https://github.com/tu_usuario/<PrimerCognomAlumne>-activitat-a12u.git
   cd <PrimerCognomAlumne>-activitat-a12u

### 3. **Crea el archivo LICENSE.md dentro del repositorio**

    Crea el archvio "LICENSE.md abrelo y copia el siguiente texto:
    ```bash
    MIT License

    Copyright (c) [año] [El teu nom]

    Es concedeix permís, de manera gratuïta, a qualsevol persona que obtingui una còpia d'aquest software i els arxius de documentació associats (el "Software"), per utilitzar el Software sense restriccions, incloent-hi, però no limitant-se a, els drets d'utilitzar, copiar, modificar, fusionar, publicar, distribuir, sublicenciar i/o vendre còpies del Software, i per permetre a les persones a qui se'ls proporcioni el Software fer-ho, subjecte a les següents condicions:

    El missatge de copyright i aquest avís de permís han d'incloure's en totes les còpies o parts substancials del Software.

    EL SOFTWARE ES PROPORCIONA "TAL COM ÉS", SENSE GARANTIA DE CAP TIPUS, EXPRESA O IMPLÍCITA, INCLOENT PERÒ NO LIMITANT-SE A LES GARANTÍES DE COMERCIALITZACIÓ, NO INFRACCIÓ I ADEQUACIÓ PER A UN PROPÒSIT PARTICULAR. EN NINGÚN CAS, ELS AUTORS O ELS TITULARS DEL COPYRIGHT SERAN RESPONSABLES PER QUALSEVOL RECLAMACIÓ, DANY O ALTRA RESPONSABILITAT, SIGUI EN UNA ACCIÓ DE CONTRACTE, AGRAVIÓ O D'ALTRA MANERA, QUE SURGI DE O EN CONEXIÓ AMB EL SOFTWARE O L'USUARI O ALTRA ACCIÓ EN EL SOFTWARE.

### 4. **Guardar i afegir el fitxer LICENSE al repositori**

    Un cop afegit el contingut de la llicència, guarda el fitxer i torna a la terminal de Visual Studio Code. Ara, has de preparar el fitxer per a ser enviat a GitHub:

    ```bash
    git add LICENSE
    git commit -m "Afegit fitxer LICENSE amb llicència MIT"

### 6. **Pujar els canvis al repositori de GitHub**

    Després de fer el commit, has de pujar els canvis al teu repositori remot. Utilitza el següent comandament per enviar els canvis:
    
    ```bash
    git push origin main