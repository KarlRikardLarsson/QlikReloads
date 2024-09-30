# Laddningskedja installer
En automation som installerar en laddningskedja med mejlutskick när en automation har misslyckats (failat), samt ett "recovered"-mejl om laddningen misslyckas men sedan lyckas vid nästa försök.

![image](https://github.com/user-attachments/assets/e75f5739-1ce3-45f9-bffb-1f16bfc59969)

![image](https://github.com/user-attachments/assets/4d2b0258-9365-4dae-a674-177b5aea54bd)

![image](https://github.com/user-attachments/assets/1646b25a-79f2-4a6d-815f-757e4c309237)

![image](https://github.com/user-attachments/assets/1ab9b796-727f-4783-955a-89a50cf08008)

## Innehållsförteckning
1. [Info](#info)
2. [Installation](#installation)
3. [Slutförd](#slutförd)

---

## Info
### Automationen installerar en laddningskedja med följande funktioner:
- Välj vilka applikationer som ska laddas.
- Ställ in laddningstid och frekvens.
- Ange kundens namn, automationens namn och mottagare av mejlutskick.
- Bestäm om laddningen ska ske enbart på helger eller vardagar.
- Möjlighet att övervaka laddningsscheman (reload schedule tasks).

---

## Installation
### Steg 1
Ladda ner JSON-filen från repositoryt och ladda upp den i din workspace.

![image](https://github.com/user-attachments/assets/52a54133-7824-4a2d-be11-0e55aae2215a)

### Steg 2
Fyll i kundens namn, automationens namn och välj vilken typ av laddningsautomation som ska installeras. `Chain reloader` är en vanlig laddningskedja, medan `Monitoring` ger möjlighet att övervaka specifika appar (endast via reload schedule).

![image](https://github.com/user-attachments/assets/45168f36-8a9f-4cfe-973f-3ccc009080a7)

### Steg 3
Välj vilket utrymme dina extract-appar ligger i, och välj sedan vilka appar som ska laddas. Upprepa processen för `Transform` och `Load`.

![image](https://github.com/user-attachments/assets/a55798aa-954a-406f-ab9c-e35dc4cfb274)

### Steg 4
Ange hur ofta automationen ska köras, vilken tid, mejlmottagare, och om den ska köras endast på vardagar.

![image](https://github.com/user-attachments/assets/4a473cc1-fe1a-4743-b2a7-951acceaf408)

### Steg 5
När automationen har skapats, notera att mejlblocket inte fungerar förrän du kopplar det till en SMTP-server. Om du inte har dessa uppgifter kan du högerklicka på mejlblocket och välja "disable block".

![image](https://github.com/user-attachments/assets/3049b110-a91f-4dfe-89bc-17fd14a9bf94)

![image](https://github.com/user-attachments/assets/a7af5246-cf08-4474-a991-d5138341605a)

---

## Slutförd
Din laddningskedja är nu installerad och klar att användas.




