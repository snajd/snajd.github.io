# Långtidslåna böcker från biblioteket (eller läs på valfri enhet)

1. Ladda hem och installera Calibre från https://calibre-ebook.com/download
2. Se till att Adobe Digital Editions (ADE) är installerat (https://www.adobe.com/solutions/ebook/digital-editions/download.html) och att du där är inloggad med ditt konto från Adobe
3. "Låna" en digital bok från t.ex https://biblioteket.stockholm.se/titel/1065927/format/58?ds=new och öppna den i ADE
4. Starta Calibre och gå igenom guiden för att välja den ebokläsare du vill använda.
5. Nu börjar det roliga.
Surfa till: https://github.com/apprenticeharper/DeDRM_tools/releases och ladda hem den senaste DeDRM_tools_<version>.zip
6. Packa upp den nerladdad zipfilen.
7. Inne i Calibre, öppna Inställningar i menyraden högst upp (om knappen inte syns, gör fönstret bredare) och välj "Ändra beteendet för Calibre/Change Calibre behavior".
8. Välj Insticksmoduler under kategorin Avancerat.
9. Klicka på Läs in insticksmodul från fil och bläddra till platsen du packade upp den nerladdade filen i steg 6. Välj DeDRM_plugin och tryck på Öppna.
10. Svara ja på säkerhetsfrågan. Markera DeDRM pluginet och välj "Anpassa insticksmodul" (om fönstret försvunnit ligger det under kategorin Filtyp). Välj Adobe Digital Editions ebooks och tryck på det gröna plustecknet i dialogrutan som dyker upp. Tryck på OK för att godkänna namnet på den nya nyckeln. 
11. Tryck på Stäng, sen Tillämpa för att stänga Inställningar. Stäng sen Calibre och starta programmet igen.
12. Växla till Adobe Digital Editions och högerklicka på boken du vill långtidslåna. Välj "Show File in Explorer"
13. Dra epub-filen för boken till Calibre för att öppna den där.
14. Du bör nu se en förhandsgranskning av framsidan på boken när du markerar den i listan i Calibre. Om detta fungerar är nu kopieringsskyddet (DRM = Digital Rights Management) borta.
15.  Du kan nu högerklicka på boken och välja Spara till disk för att spara epuben på valfritt ställe, för att sen föra över till din enhet på valfritt vis, t.ex genom att lägga den i Dropbox/OneDrive på datorn och sen öppna den i telefonen
