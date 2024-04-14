# CI/CD Car-detection-HF
Felhők hálózati szolgáltatásai laboratórium HF - BMEVITMMB11 

# Feladat kiírás:
 

A félév során mindenkinek létre kell hoznia egy fejlesztői CI/CD környezetet a saját gépén és ennek használatával egy olyan web szolgáltatást kell létrehozni ami az alábbi funkciókat látja el:

    Kép és hozzá tartozó leírás feltöltése (kép és leírás páros tárolás)	
    A feltöltött képen automatikus autó detektálás és a megtalált autók bekeretezésével a kép megjelenítése a weboldalon
	A weboldal “üzemeltetői” képesek legyenek feliratkozni az oldalra, azaz kapjanak értesítést az összes eddigi és az új feltöltött képekről úgy, hogy kiküldésre kerül számukra a képhez tartozó leírás és a rendszer által detektált autók száma a feltöltött képen

FONTOS! A fejlesztésről készítsetek fejlesztői dokumentációt, melyben szerepeljen a futási környezet leírása, a CI/CD környezet leírása, a fejlesztett kód vázlatos leírása, a használt adatszerkezetek és a webszolgáltatás architektúrája.
 
Egyéb tudnivalók:

	
A weboldal létrehozásánál nem a dizájn a lényeg (akár sima HTML is lehet), hanem az általatok összerakott és használt CI/CD illetve a webszolgáltatáshoz tartozó “felhős ökoszisztéma”, azaz a félév során bemutatott backend technológiák használata
	
A fejlesztéshez nincsen technológiai megkötés, viszont a HF bemutatásakor legyenek érveitek, hogy miért a használt backend megoldást választottátok (pl. Funkció 1-et konténerben valósítottam meg a jól ledobozálhatóság miatt, míg a Funkció 2-re FaaS-t gondoltam alkalmasnak a gyors skálázódás és párhuzamos végrehajtás miatt). Kiváncsian várjuk, hogy ki milyen architektúrát tartott megfelelőnek a kiírt feladat megoldására.
	
Természetesen az autó detektáló modellt nem a hallgatóknak kell lefejleszteniük. Bármilyen online elérhető ingyenes detektáló modellt szabad használni.
	
Az üzemeltetői feliratkozásra érdemes lehet valamilyen message queue-t használni
 

# Osztályzás:
 

A házi feladat három részből áll:
	
	
1) CI/CD környezet telepítése	
2) weboldal + autó detektálás funkció imeplementálása
3) üzemeltetők feliratkozási funkciója
		
	
04.14 Fejlesztői dokumentáció feltöltése, mely tartalmazza az általatok használt CI/CD környezetet
	
04.28 Fejlesztői dokumentáció feltöltése, mely tartalmazza a képfeltöltéssel és az autók detektálásával kapcsolatos leírásokat
	
05.12 Végleges Fejlesztői dokumentáció feltöltése és jelentkezés HF bemutatásra

[![Create File on Push](https://github.com/istex9/CICD-Car-Detection-HF/actions/workflows/test-build-and-release.yml/badge.svg)](https://github.com/istex9/CICD-Car-Detection-HF/actions/workflows/test-build-and-release.yml)

Legfrissebb release: [Itt letölthető](https://github.com/istex9/CICD-Car-Detection-HF/releases/tag/latest)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>
