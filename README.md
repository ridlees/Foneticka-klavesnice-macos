# Foneticka-klavesnice-macos
Krátký vhled do instalace fonetické klávesnice na macOS


# MacOS a fonetická klávesnice v pár krocích

Předčasem jsem kamarádce instalovat fonetickou klávesnici na MacOS a jelikož to nebylo tak jednoduché, jak jsem si myslel, přidávám krátký návod.

Potřebujeme: Zařízení s MacOS
             Internet (připojení k němu)
             Pár minut času.

# Nový návod (Mac OS X 10.13)

## Krok 1 - stažení potřebných věcí

1. Stáhneme nástroj [Keyman]((https://keyman.com/mac/download))

## Krok 2 - Instalace
1. Otevřeme soubor Keyman.dmg (nejspíše se bude jmenovat něco jako keyman-17.0.331.dmg
2. Otevře se instalační okno. Klikni na Install Keyman.
3. Může se otevřít okno, které varuje před instalací z internetu. Pokud se tak stane, klikni na Open.
4. V novém okně klikni na tlačítko Install.
5. Otevře se Nastavení klávesnice. V něm se otevře okno, které se ptá, zda chcete povolit Keyman ve své klavesnici. Klikni na OK.
6. Pro správné fungování je nutné v horním rohu přepnout na Keyman. Systém se vás zeptá, zda mu povolíte přístup do Accessibility settings.
7. Otevřete si Nastavení svého Macu>Security & Privacy>Accesibility. V levém dolním rohu klikněte na ikonu zámku a přihlaste se svým heslem. Vyberte Keyman a zaškrtněte políčko vedle něj. Poté znovu klikněte na ikonu zámku.
8. Restartujte svůj Mac.
9. Poté v horní liště vašeho Macu, kde máte možnost CZ Czech klikni na CZ Czech a vyber Keyman. Poté znovu klikni na Keyman a vyber Configuration. 
10. V novém menu klikni vlevo dole na Download Keyboard… a vyhledej IPATotal keyboard(pozn. 1) a klikni na IPATotal. Poté vyber Install keyboard. 
11. Klavesnice se stáhne. Klikni na Done. Zkontroluj, zda je IPATotal zaškrnutá. 
12. Tadá, máte naistalovanou fonetickou klávesnici. Pro přehlednou příručku navštiv [https://help.keyman.com/keyboard/ipatotal/3.2/ipatotal-en.pdf](https://help.keyman.com/keyboard/ipatotal/3.2/ipatotal-en.pdf)

* pozn. 1: Je možné, že budete spíše používat IPA(SIL). V tomto případě místo IPATotal nainsalujte IPA(SIL). Příručku najdete poté na [Zde](https://help.keyman.com/keyboard/sil_ipa/1.8.7/sil_ipa)
* pozn. 2: Na jednom zařízení můžete mít vícero klávesnic v jednom Keymanu. Přepínáte mezi nimi kliknutím na Keyman v horní liště Vašeho Macu. Poté si můžete vybrat, kterou klávesnici použijete.
* pozn. 3. IPA(SIL) může požadovat instalaci Charis SIL font. Pro jeho instalaci se podívejte do starého návodu. 
             
# Starý návod

## Krok 1 - stažení potřebných věcí

1. Stáhneme správný layout klávesnice [Zde](https://scripts.sil.org/cms/sites/nrsi/download/ipa-mackbd/IPA-MACkbd.dmg)
2. Stáhneme font, který podporuje fonetické znaky. Doporučuji [CharisSIL](https://software.sil.org/downloads/r/charis/CharisSIL-5.000.zip)

## Krok 2 - instalace

1. Otevřeme složku CharisSIL, kterou jsme si stáhli a klikneme na všechny soubory s koncovkou .ttf Toto na MacOS otvírá Knihu Fontů (v angličtině font Book), kde poklikáme tlačítko instalovat. Do dalšího kroku pokračujeme, máme-li nainstalovány jak Regular (R), Bold (B), Italic (I) a Bold Italic (BI).

2. Otevřeme Finder (složku souborů) a znáčkneme kombinaci shift + command + L k otevření složky Library (knihovny) a otevřeme složku Keyboard Layouts. Nelze-li toto provést, koukneme se do dalšího kroku. Jde-li, další krok přeskočíme.

3.  Otevřeme Finder a přesuneme se do složky Počítače (při otevřeném Finderu můžeme použít kombinaci shift + command + C). Klikneme na MacIntoshHD (složku Harddrive), složku uživatele (Users) a na svojí složku (většinou pod jménem admina, či profilu na kterém pracujeme). V této složce bychom měli vidět složku Library/kihovny. Nevidíme-li, zmáčkneme command + J (případně možnost nastaviní View> Show View Options) a zaškrtneme, že chceme vidět složku Knihovny/library. Zde otevřeme složku Keyboard Layouts. 

4. Klikneme na .dmg soubor layoutu a jeho obsah přesuneme do složky Keyboard layouts. 

## Krok 3 - Nastavení

1. Máme-li novější verze MacOS, v nastavení otevřeme možnost Keyboard (Klávesnice). V starších verzích je tato možnost skryta v části Language & Region (jazyk a region), kde je možnost keyboard preferences.

2. Vybereme Input Sources a klikneme na +. 

3. Scrollujeme v nabídce layouts až najdeme Others, kde již na nás čeka Layout IPA. Klikneme na něj. To nám na horní liště vytvoří maličkou českou/anglickou vlajku. Při kliknutí na ní si můžete změnit keyboard layout právě na IPA. Doporučuji do začátku kliknout na zobrazit Prohlížeč klávesnic, který Vám pomůže s psaním fonetických znaků.

## Používání IPA

Máme-li zapnutý IPA layout a  našem textovém editoru (pages, word, odt) nastaven správný font (CharisSIL), tak můžeme psát s fonetickými znaky. Tento layout používá "dead" letters, tedy klávesy, které běžně nemají význam a s jejich kombinací můžete dělat fonetické znaky. Pro začátky doporučuji používat prohlížeč Klávesnic.

Doufám, že tato krátká Guide někomu pomohla.
