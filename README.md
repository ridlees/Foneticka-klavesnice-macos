# Fonteticka-klavesnice-macos
Krátký vhled do instalace fonetické klávesnice na macOS


# MacOS a fonetická klávesnice v pár krocích

Předčasem jsem kamarádce instalovat fonetickou klávesnici na MacOS a jelikož to nebylo tak jednoduché, jak jsem si myslel, přidávám krátký návod.

Potřebujeme: Zařízení s MacOS
             Internet (připojení k němu)
             Pár minut času.

# Krok 1 - stažení potřebných věcí

1. Stáhneme správný layout klávesnice [Zde](https://scripts.sil.org/cms/scripts/render_download.php?format=file&media_id=IPA-MACkbd&filename=IPA-MACkbd.dmg)
2. Stáhneme font, který podporuje fonetické znaky. Doporučuji [CharisSIL](https://software.sil.org/downloads/r/charis/CharisSIL-5.000.zip)

# Krok 2 - instalace

1. Otevřeme složku CharisSIL, kterou jsme si stáhli a klikneme na všechny soubory s koncovkou .ttf Toto na MacOS otvírá Knihu Fontů (v angličtině font Book), kde poklikáme tlačítko instalovat. Do dalšího kroku pokračujeme, máme-li nainstalovány jak Regular (R), Bold (B), Italic (I) a Bold Italic (BI).

2. Otevřeme Finder (složku souborů) a znáčkneme kombinaci shift + command + L k otevření složky Library (knihovny) a otevřeme složku Keyboard Layouts. Nelze-li toto provést, koukneme se do dalšího kroku. Jde-li, další krok přeskočíme.

3.  Otevřeme Finder a přesuneme se do složky Počítače (při otevřeném Finderu můžeme použít kombinaci shift + command + C). Klikneme na MacIntoshHD (složku Harddrive), složku uživatele (Users) a na svojí složku (většinou pod jménem admina, či profilu na kterém pracujeme). V této složce bychom měli vidět složku Library/kihovny. Nevidíme-li, zmáčkneme command + J (případně možnost nastaviní View> Show View Options) a zaškrtneme, že chceme vidět složku Knihovny/library. Zde otevřeme složku Keyboard Layouts. 

4. Klikneme na .dmg soubor layoutu a jeho obsah přesuneme do složky Keyboard layouts. 

# Krok 3 - Nastavení

1. Máme-li novější verze MacOS, v nastavení otevřeme možnost Keyboard (Klávesnice). V starších verzích je tato možnost skryta v části Language & Region (jazyk a region), kde je možnost keyboard preferences.

2. Vybereme Input Sources a klikneme na +. 

3. Scrollujeme v nabídce layouts až najdeme Others, kde již na nás čeka Layout IPA. Klikneme na něj. To nám na horní liště vytvoří maličkou českou/anglickou vlajku. Při kliknutí na ní si můžete změnit keyboard layout právě na IPA. Doporučuji do začátku kliknout na zobrazit Prohlížeč klávesnic, který Vám pomůže s psaním fonetických znaků.

# Používání IPA

Máme-li zapnutý IPA layout a  našem textovém editoru (pages, word, odt) nastaven správný font (CharisSIL), tak můžeme psát s fonetickými znaky. Tento layout používá "dead" letters, tedy klávesy, které běžně nemají význam a s jejich kombinací můžete dělat fonetické znaky. Pro začátky doporučuji používat prohlížeč Klávesnic.

Doufám, že tato krátká Guide někomu pomohla.
