# ŠDL WiFi

Uradno stališče ŠDL je, da je povezava preko kabla primarna in se smatra, 
da večina uporabnikov dostopa do interneta preko kabla. 
Omogočena je tudi uporaba WiFi omrežja, ampak se je potrebno 
zavedati, da je to sekundarni način dostopa do interneta in 
ni zagotovila, da bo dobro delovalo. Na WiFi se tako lahko zgodi, 
da se internet precej upočasni, lahko nam pa tudi prekine povezavo 
in se moramo znova povezati (Pri čemer ponovimo samo 8. točko iz 
spodnjih navodil).

Priporočeno je, da se ob nastavljanju omrežja uredi tudi povezava 
preko kabla (če nimate kabla, si ga začasno sposodite od cimra/e, 
dobite pa ga v vsaki tehnični trgovini pod imenom UTP kabel).


# Nastavitev ŠDL WiFi na Windows 10

1. Odpri zavihek z nastavitvami za internet (spodaj desno) in v 
   njem izberi **Nastavitve omrežja in interneta**.

![wifi1](../media/wifi/wifi1.png)

2. V nastavitvah izberi možnost **Stanje** in podrsaj do konca strani. 

![wifi2a](../media/wifi/wifi2a.png)

Izberi možnost **Središče za omrežje in skupno rabo** 
(Na različnih verzijah Windows 10 lahko to okno zgleda malo drugače, ime 
potrebne nastavitve ostaja isto).

![wifi2b](../media/wifi/wifi2b.png)

3. Izberi možnost **Namestitev nove povezave ali omrežja**

![wifi3](../media/wifi/wifi3.png)

4. Izberi **Ročna povezava z brezžičnim omrežjem**

![wifi4](../media/wifi/wifi4.png)

5. Potrebno je vnesti nekaj podatkov:

* **Ime omrežja**: Mora biti točno `SDLnet`, pri čemer je treba biti 
  pozoren na velike/male začetnice.
* **Vrsta varnosti**: Mora biti WPA2 – Podjetniško oz. Enterprise.
* **Vrsta šifriranja**: Mora biti AES (je že privzeta vrednost)
* **Varnostni ključ**: Ostane prazno polje
* **Samodejno zaženi to povezavo**: Ta možnost naj bo izbrana
* **Vzpostavi povezavo, tudi če omrežje ne oddaja**: Pustimo neizbrano

‼️‼️ **POMEMBNO:**
Kliknemo **Naprej**. Ko nas vpraša ali bi radi spremenili nastavitve 
povezave, kliknemo na okvir s tem besedilom, in se nam odpre 
okno, prikazano v točki 6.

![wifi5](../media/wifi/wifi5.png)

6. V odprtem oknu izberemo zavihek **Varnost** – Če tega zavihka ni, 
   moramo najprej namestiti [SecureW2](./SecureW2.md).

![wifi6](../media/wifi/wifi6.png)

V zavihku varnost nastavimo naslednje vrednosti:

* **Vrsta varnosti**: WPA2 – Podjetniško (oz. Enterprise)
* **Vrsta Šifriranja**: AES
* **Način preverjanja pristnosti v omrežju**: SecureW2: SecureW2 EAP-TTLS
* **Zapomni si poverilnice za to povezavo ob vsaki prijavi**: 
  Izberemo to možnost

Kliknemo na gumb **Nastavitve**.

![wifi7](../media/wifi/wifi7.png)

7. Kliknemo na gumb **Konfiguriraj**.

![wifi8](../media/wifi/wifi8.png)

V prvem, drugem in tretjem zavihku, preverimo, da so izbrane iste 
možnosti kot na sliki:

![wifi9](../media/wifi/wifi9.png)

![wifi10](../media/wifi/wifi10.png)

![wifi11](../media/wifi/wifi11.png)


V zadnjem zavihku pa vnesemo naslednje možnosti:
* **Vprašaj uporabnika za geslo**: ne izberemo
* **Uporabniško ime**: Vnesemo svoj ŠDL račun, ki ste ga 
  dobili ob vselitvi. (Račun je v obliki xxxxxx@sd-lj.si, pri 
  čemer je prvi del sestavljen iz imena in priimka,
  [glej povezavo](./Username.md))
* **Geslo**: Geslo je isto kot za MojŠtudent in je isto, 
  kot ste ga nastavili ob prvi prijavi v MojŠtudent. Če 
  prve prijave v MojŠtudent niste še opravili in ste izgubili 
  geslo, je potrebno zaprositi za novo geslo – to se stori 
  lahko samo na upravi.
* **Uporabi ta račun za prijavo**: To možnost izberemo.

![wifi12](../media/wifi/wifi12.png)

8. Vsa okna lahko sedaj zapremo (S klikom na gumb V redu). Nazaj 
   odpremo wifi okno (gumb spodaj desno, korak ena na prvi sliki) 
   in vzpostavimo povezavo z omrežjem SDLnet. Če vse deluje ok, bi 
   se moralo povezati.
