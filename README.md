# Projektbeskrivning
<img src="https://github.com/user-attachments/assets/1c2c4dc6-7c3c-4334-9e31-b68889c9ebf5" alt="Description of Image" width="500" />

## 1. Kort beskrivning av projektet
I det här projektet har vi designat en hemsida för ett café. Hemsidan innehåller bland annat en huvudmeny, en sida där man kan se och köpa våra produkter (shop), samt en kassa (checkout) och en ordersida. Det finns även möjlighet att logga in och registrera sig via “Sign in” och “Sign up”-sidorna. På "About us"-sidan finns information om oss, vår plats och vår personal.

Vi har försökt att efterlikna moderna caféer som Espresso House och Starbucks, både vad gäller färgval, navigation, design och utseende. Uppgiften utfördes i designverktyget Figma.

## 2. Kända buggar (i Figma)
När användaren klickar på "Location" byter Figma till "About Us", och därefter skrollar sidan ner. Detta fungerar dock endast en gång. I Figma finns det ingen kombination av "Navigate to" och "Scroll to". Därför har vi en knapp i "About Us" som känner igen om användaren nyligen har klickat på "Location", vilket sedan aktiverar ett "Scroll to"-kommando. Detta är dock inte optimalt, eftersom det inte finns något bra sätt att återställa knappen efteråt. Knappen försvinner efter 1 ms för att undvika att användaren av misstag klickar på den. Men Figma's enkla användargränssnitt gör komplicerade uppgifter svåra.

## 3. Framtida utveckling/status
Framtida utvecklingsplaner känns svaga i dagsläget. En framtidsplan skulle kunna vara att använda detta projekt som exempel för andra som vill lära sig Figma. De som är intresserade av att använda Figma kan då använda vårt Figmaprojekt som en slags "mall" för sitt eget designarbete. Vi kan alltså ”sälja” vår ”template”, om någon skulle vara intresserad av den. Vi planerar inte att fortsätta utveckla Figma-designen efter att projektet är färdigt.

## 4. Mjukvara
Sitemap, huvuddesign, wireframe och brainstorm gjordes i Figma. För texten på hemsidan så användes bland annat ChatGPT för att komma på bra och trovärdiga scenarion, t.ex. om Bakehub’s historia och vissa av namnen på produkterna som säljs. För att generera konceptlogotyper använde vi ChatGPT för bildgenerering.

## Stilguide
Er stilguide dokumenterar designen och kan användas vid framtida utveckling. All ny design som följer stilguiden bör passa in med den befintliga. Stilguiden kan specificera t.ex.

### 1. Typsnitt
Vi använde Inter på grund av den moderna och stilrena designen som ungdomar lockas till.
- **Stor titel**: 64 px
- **Produkt Info titel**: 48 px
- **Heading**: 32 px
- **Body text**: 24 px
- **Details**: 16 px

### 2. Färgpalett
- **Ljuslila**: Hex-kod FFFFFF. En mycket ljus och mjuk lila nyans.
- **Mjuk rosa**: Hex-kod FFE3E3. En mild och behaglig rosa färg.
- **Medellila**: Hex-kod 9D5A60. En djupare lila ton med en antydan av rött.
- **Olivgrön**: Hex-kod 7A9D65. En naturlig och jordnära grön färg.
- **Dämpad teal**: Hex-kod 97AC9F. En lugn och sval teal nyans.

### 3. Återkommande komponenter
<img src="https://github.com/user-attachments/assets/469cda3c-4475-4a8c-83ac-906a3d879c5b" alt="Image 7" width="500" />

De flesta sidor ska innehålla en huvudmeny, eller en toppmeny (för smidig navigering på hemsidan) som placeras högst upp på sidan och följer med dynamiskt vid skrollning.

I toppmenyn ska följande finnas:
- **Sign up/Log in**: till höger
- **Ikon för kundvagn**: till vänster (vid klick öppnas innehållet i kundvagnen)
- **Sökknapp**: (öppnar ett sökfönster)
- **Hamburgarmeny**: längst till vänster (för enkel navigering av hemsidan) med vår logotyp till höger om den, vilken fungerar som hemknapp.
- **Knapp för tillgänglighet**: längst ner till höger, där man kan aktivera "Enable high contrast" för enklare läsbarhet.

Sidor som har undantag från detta tema är "Sign in", "Sign up", "Shopping cart page", "Checkout page" och "Order placed", som endast ska ha hamburgarmenyn och BakeHub-logotypen i toppmenyn.

Dessa två komponenter är återkommande på alla sidor på hemsidan. Anledningen till undantaget är att det exempelvis inte är logiskt att ha en "Sign in"-knapp i hörnet när användaren redan håller på att beställa en produkt.

### 4. Designstil
Designen som presenteras på sidan är skarp; ikoner, knappar, bilder och annat har alla raka kanter och hörn som presenteras med ett rektangulärt utseende, vilket gör att detaljerna står ut från hemsidans bakgrund och användarens uppmärksamhet dras dit. Vi har också mjuka skuggor på alla knappar för att de ska få bra kontrast i förhållande till den vita bakgrunden.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/8e1b7d5b-fc31-4430-b1a3-d500e930f39f" alt="Image 1" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/a09284a7-2f2f-4e11-b4ce-ca74cd599017" alt="Image 2" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/4b63136a-6e98-43fb-8c22-2c33dff883c5" alt="Image 3" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/a42b65a4-81af-4b21-8724-14b73d1382da" alt="Image 4" width="250" /></td>
    <td><img src="https://github.com/user-attachments/assets/71ade0cd-f9b7-4d33-8fb5-9c2b5dfcdd25" alt="Image 5" width="200" /></td>
</table>

### 5. Mönster och regler
Alla bilder har en viss färgskala eller visst format. På vår “main menu” och “about us” page följer de samma design och struktur. På varje form har vi använt oss av rektanglar och vi har använt mjuka skuggor på nästan varje rektangel. “Spacingen” är jämn över hela sidan. Alla bilder och former är rektangulära och många är så kallade PNGs (t.ex. på best sellers).
