# 😺 Online kurz Git a Github
Materiály k online kurzu Git a GitHub


## Zoznam základných Bash príkazov s vysvetleniami
Tu je zoznam základných Bash príkazov s konkrétnymi vysvetleniami:

**1. 📂 ls** – Zobrazí zoznam súborov a priečinkov v aktuálnom adresári.
 
``bash   
ls       
ls -l         
``
ls vypíše všetky súbory v aktuálnom adresári.   
ls -l zobrazí súbory vo forme zoznamu s podrobnosťami (veľkosť, práva, dátum).   

**2. 📁 cd [adresár]** – Zmení aktuálny adresár.  

``bash  
cd dokumenty    
cd ..   
``

cd dokumenty presunie do priečinka dokumenty.  
cd .. sa vráti o úroveň vyššie.  

**3. 🗑️ rm [súbor]** – Odstráni súbor.

``bash  
rm subor.txt  
rm -r priecinok  
``

rm subor.txt odstráni súbor subor.txt.
rm -r priecinok odstráni priečinok priecinok spolu s jeho obsahom.

4. ✏️ touch [súbor] – Vytvorí nový prázdny súbor.

``bash  
touch novy_subor.txt  
``

Tento príkaz vytvorí nový súbor s názvom novy_subor.txt.


5. 📝 cat [súbor] – Zobrazí obsah súboru.

``bash 
cat subor.txt  
``

Tento príkaz vypíše obsah súboru subor.txt do terminálu.

6. 📑 mkdir [priečinok] – Vytvorí nový priečinok.

``bash  
mkdir nove_dokumenty  
``
Tento príkaz vytvorí priečinok s názvom nove_dokumenty.

7. 🛠️ cp [súbor] [cesta] – Skopíruje súbor alebo priečinok.

``bash
cp subor.txt /domov  
cp -r priecinok /domov  
``

cp subor.txt /domov skopíruje súbor subor.txt do adresára /domov.
cp -r priecinok /domov skopíruje priečinok priecinok a jeho obsah do /domov.

8. 🔄 mv [súbor] [cesta] – Premiestni alebo premenuje súbor.

``bash
mv subor.txt /domov  
mv subor.txt novy_nazov.txt  
``

mv subor.txt /domov presunie súbor subor.txt do priečinka /domov.
mv subor.txt novy_nazov.txt premenuje súbor na novy_nazov.txt.

9. 🔍 pwd – Zobrazí aktuálny adresár.

``bash
pwd  
``
Tento príkaz vypíše cestu aktuálneho pracovného adresára.

10. 🔎 find [cesta] -name [názov_súboru] – Vyhľadá súbor alebo priečinok.

``bash
find . -name subor.txt  
``
Tento príkaz vyhľadá súbor subor.txt v aktuálnom adresári a jeho podadresároch.

11. 📊 du -h – Zobrazí veľkosť súborov a priečinkov.

``bash 
du -h  
``
Tento príkaz vypíše veľkosti súborov a priečinkov v aktuálnom adresári v čitateľnej forme (MB, GB).

12. 🖼️ clear – Vyčistí terminál.

``bash
clear  
``
Tento príkaz vymaže všetok text z terminálu a obnoví čistú obrazovku.

13. 🔐 chmod [práva] [súbor] – Zmení prístupové práva k súboru.

``bash
chmod 755 subor.sh  
``
Tento príkaz nastaví práva pre súbor subor.sh (čítanie, zápis, spúšťanie pre vlastníka; čítanie a spúšťanie pre ostatných).

14. 🔧 whoami – Zobrazí aktuálneho používateľa.

``bash 
whoami  
``
Tento príkaz vypíše meno používateľa, ktorý je momentálne prihlásený.

15. 💡 echo [text] – Vypíše text na obrazovku alebo zapíše do súboru.

``bash
echo "Ahoj, svet!"  
echo "Tento text bude v súbore" > subor.txt  
``

Prvý príkaz vypíše text Ahoj, svet! do terminálu.
Druhý príkaz zapíše text do súboru subor.txt.

16. 🧹 history – Zobrazí históriu príkazov.

``bash
history  
``
Tento príkaz zobrazí zoznam všetkých príkazov, ktoré boli vykonané v termináli.

17. ⚙️ top – Zobrazí aktuálne bežiace procesy.

``bash
top  
``
Tento príkaz zobrazí zoznam procesov, ich využitie CPU, pamäte a ďalšie informácie.

18. 🕒 date – Zobrazí aktuálny dátum a čas.

``bash 
date  
``
Tento príkaz vypíše aktuálny dátum a čas.

19. 🌍 ping [adresa] – Otestuje pripojenie k sieti.

``bash
ping google.com  
``

Tento príkaz odošle testovacie pakety na server google.com a zobrazí odozvu.

20. 📥 wget [URL] – Stiahne súbor z internetu.

``bash
wget https://example.com/subor.txt  
``
Tento príkaz stiahne súbor subor.txt z adresy example.com.

