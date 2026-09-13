# Webbutveckling Laboration 1

En enkel webbplats byggd med HTML och lite CSS.

[Netlify Page] (https://sparkling-haupia-f822cf.netlify.app/)

[GitHub] (https://yrsadev.github.io/webbutveckling-laboration-1/)

Frågor om Git

1. Vad är skillnaden mellan git add och git commit?

Git add väljer vilka ändringar som ska med, och git commit sparar dem permanent i historiken med ett meddelande.

2. Varför använder man branches istället för att jobba direkt i main?

Branches låter dig testa ändringar utan att röra main. När allt fungerar kan du slå ihop grenarna med main.

3. Vad händer rent praktiskt när man gör en merge?

När man gör en merge förs ändringarna från en branch in i main så att allt hamnar i samma version. Det som var i en annan branch blir en del av main med merge.

4. Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?

Att pusha till GitHub uppdaterar koden i repot. Att publicera på Netlify gör sidan live för besökare. De hänger ofta ihop, men är två olika steg. Man pushar först för att sen publicera den.

5. Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?

Jag skapar en textfil som heter .gitignore i projektet och skriver in filnamnet där så att Git ignorerar den.
