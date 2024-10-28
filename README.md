# TypeScript Basics Bootcamp

## 01 - Skapa upp ditt första TypeScript-projekt

1. Skapa upp mapparna **src** och **dist**.
2. I sourcemappen skapar du upp filen index.ts.
3. Skapa upp filen **tsconfig.json** och klistra in följande kod:
   ```typescript
    {
      "compilerOptions" : {
          "target" : "ES6",
          "outDir" : "./dist"
      },
      "include" : ["./src"],
      "exclude" : []
    }
   ```
4. Skapa upp variabler som innehåller datatyperna **string**, **number** och **boolean**.
5. Vad händer om du försöker ändra värdet i en variabel till en annan datatyp?
6. Använd dina variabler till att skriva ut något i konsollen.
7. Kompilera din TypeScript-kod till JavaScript.
8. Skapa en filen **index.html** i din distmapp och läs in din .js-fil.
9. Öppna en liveserver i din distmapp och testkör programmet.

## 02 - Arbeta med strängar

1. Skapa upp en Array innehållandes namnen på dina favoritskådisar. Ge din array korrekt datatypsdeklaration.
2. Vad händer om du försöker stoppa in ett värde av en annan datatyp i din array?
3. Mappa dig igenom värdena i din array och logga ut dem i konsollen.
4. Kompilera din TypeScript-kod till JavaScript och kontrollera resultatet i webbläsaren.

## 03 - Funktioner med TypeScript

1. Börja med att göra så att kompilatorn lyssnar efter förändringar i din .ts-fil, och automatiskt kompilerar när en ändring sker.
2. Skapa funktionen calculate som tar emot 3 parametrar, 2 numbers och en string innehållandes en operator (+, -, *, /).
3. Typa upp dina mottagna parametrar, samt vad din funktion kommer returnera.
4. Försök att skicka in lite felaktiga värden, vad händer?
5. Koda klart din funktion, och logga ut svaret i konsollen.

## 04 - TypeScript och DOMen

1. I din HTML-fil kodar du upp ett registreringsformulär innehållandes username, password x 2, email, telefonnummer. Styla gärna om du vill.
2. I din TypeScript skapar du nu en valideringsfunktion som körs när användaren klickar på **Registrera**.
3. Hur gör du för att sätta en preventDefault nu i din funktion?
4. Typa upp dina DOM-element så att du kan komma åt inputfältens value-attribut.
5. Glöm inte att definiera vilken datatyp returen från din valideringsfunktion består utav.

## 05 - Todo-app

Skapa upp en enkel Todo-applikation där du lagrar dina todos (bara namnen på uppgiften som sträng) i en array och tryck ut dem på skärmen. Skapa även ett formulär där användaren kan lägga till nya todouppgifter under pågående session.

Denna uppgift kan ni egentligen göra så komplex som ni själva känner för. Vill ni lagra i localStorage - gör det! Vill ni använda ES6 moduler - gör det!

## 06 - Freestyla hej vilt!

Gör precis vad ni vill som innefattar TypeScript!
