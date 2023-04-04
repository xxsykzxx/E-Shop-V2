# E-Shop-V2

- ID Transakce z eshopu (https://www.morex.cz/userscartorders.aspx) do Abry (objednávky přijaté)
- MailChimp (opuštěný košík)
- Tel. kontakt vedle vyhledávání není červeným textem (nechat jak je nyní)
- (-) Přepínač EURO / CZ
- Rychlá objednávka (přepnout z enter na tab)
- Nechat infoproužek
- WebP icon 
- (❗) Menu při přidání košíku zmizí nahorů
- 4. Krok košíku (pokud nedokončí obj, alert jestli opravdu chce odejít)
- border byl doděláván, nechat jak je na starým (nyní) -> profile, oblíbený, košík, pokračovat, ...
- Reklamace (není dořešeno v E-shopu ani Abře)
- 4 . Krok košíku (Souhrn objednávky) -> přidat datum dodání / doručíme od ... + pokud nepotvrdím podmínky, sjet dolu a upozornit na to
- BOD 39. vymazat starou slevu v rychlé objednávce (uloží se ze staré rychlé objednávky)
- BOD 46. pokud není v Abře povoleno "Bankovním převodem" tak nezobrazovat splatnost na e-shopu (žměna údajů)
- DOTAZ - Firmy, který mají ceník uvidí jen produkty, ktere jsou v ceník (například coop) -> checkbox díky, kterému uvídí všechno zboží + pokud budu přihlášen pod firmou, napípnu zboží, ukátat hlášku, že zboží není zalistované
- VO - slevněné produkty - původní cena je s DPH a slevněné je BEZ DPH .. (chceme obě ceny bez dph)
- Při poslání Zapomenuté heslo -> osekat formulář na čístě vyplnění hesla ?
- Infoproužek (ABRA) - nezobrazovat, pokud není žádný text
- Uživatel -> Změna údajů -> Seznam uživatelů -> přidat osobu -> Nekontroluje tel. čislo: nedoplní +420 a můžu zadat nesmyslné číslo (739 822 1999) zřejmě to same i u 
SK, stejný problém u "Nový login" -> napojení na foxentry
- Nefunguje vyhledávání: Admin -> seznam firem -> vyhledávání podle názvu firmy. Např.: ***Pavel Procházka, Helena Michalčáková*** (IČO: 47335769)
- patičku blbne u některých souborů (basket3, basket2 ...) správně v account.html (patička)
- Vyhledávání ve fulltextu nefunguje filtr (např. vyhledám krabičku)
- Pokud zadám množství 100ks, ale skladem 30ks -> automaticky nastavit 30ks do košíku
- Rozdělit 2. jakost do samostatné sekce a samotnou 2. jakost nezobrazovat mezi ostatníma položkama. Častá reklamace techto položek.
- Dodací adresu omezit na max 30 znaků. Pokud má více než 30 nelze vytvořit balík. Do balíkobotu následně udělat úpravu, aby se automaticky přenášelo max 30 znaků (např. z fakturační adresy) avšak ji nevymazalo v Adresáři firem (pouze do Abry, ne eshop)
- občerstvít všechny eshopy najednou (bude za stejný čas ? nebo bude trbat 3x dýl)
- zapomněl heslo, nechat pouze email (odebrat přihlašovací jméno), hláška pokud zadá špatný email: Zadaný e-mail nebyl nalezen.
- Zísilkovna nemá manipulační poplatek kvůli hmotnosti (špatně)
- Po přidání do košíku +/- mění množství jen po 1 (pedig má 0,5kg, přidá pak 1,5kg)
- Skrýt / zobrazit vyprodané oddělení (např. pedig -> úplety) .. skrýt stejně jako sklad. položky, které už nejsou. Admin uvidí vše (url bude existovat)
- Lze limity dopravy nastavit pro dealery s jinou částkou ? VO - 5000kč / Dealer 3000kč
- V mutacích jsou odkaty česky (např. [Doprava a platba](https://www.morex.shop/dokument/doprava-a-platba/))
- Manipulační poplatek je součástí dopravy. Lze řešit samostatně ? Nyní je zmatek i v textu. + Zásilkovna u VO nemá žádný manupulačni poplatek kvůli nastavení hmotnosti u balíků. Ideálně následně rozdělit text na dobírku a manipulační částku zvlášť.
- Pokud má zákazník po splatnosti, alert po přihlášení. (něco jako Modal)
- Pokud je položka vyprodaná a zároveň je v OV, zobrazit datum kdy přijde. Např.: **"Na předobjednávku 15.08.2024"**. Pokud nebude vůbec na OV - zobrazit "Vyprodané"
- Dealer může řadit dle množství, nastavit třízení pro všechny. Nahradit za "Nejnovější"
- Po přihlášení na mobil není poznat, zda je uživatel přihlášen. TODA: Vyřešit obarvením ikony uživatele obdobně jako u Oblíbených.
- Zaokrouhlení na 1 desetinu pokud číslo nebude celé. Pokud bude celé nechat celé jednotky. TODA: Zobrazit dostupnost zaokrouhlenou na 2 desetinna místa, pokud je zbývající dostupné množství < 10
- Při nékupu neregistrovaného zákazníka přidat možnost zadat heslo a tím se vytvoří nová registrace.
- Přihlášení pomocí google / seznam 
- Pokud je sleva na položku při počtu např. 10ks a v košíku nasledně snížím množství na 9ks, sleva pořád zustane stejná jako na 10ks (tulipány)
- Přepočítávání položek v košíku probíhá 4x (každý krok košíku), pokud je hodně položek, trvá to příliž dlouho.
- U produktů, které se prodávají podle hmotnosti (12,5kg), objemu, délky nebo kusy, je zákonnou poviností uvádět základní cenu. (např. 4L vody, základní cena za 1L).
- 



<hr>

# Obrázky 

## Velké ikony
WebP
![ikon](https://user-images.githubusercontent.com/59166385/172812747-90259ae4-9636-491d-9c30-49eb2cda38d1.png)

## Řadit dle dostupnosti
![image](https://user-images.githubusercontent.com/59166385/229710824-6a7f5fd4-48b8-4383-8d37-68c48b311ea5.png
)
