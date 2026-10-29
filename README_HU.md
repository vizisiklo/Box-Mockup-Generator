# Box Mockup Generator – Free Beta

**Gyors csomagolás-mockup készítés Windows alatt, öt lépésben.** CorelDRAW-ban vagy más vektorgrafikus programban megtervezheted a doboz grafikáját, majd a Box Mockup Generatorban kész 3D termékbemutató képet készíthetsz belőle.

**Ingyenesen használható, saját tulajdonú (nem nyílt forráskódú) próbaváltozat.** A publikus GitHub-oldalon a felhasználói leírások, hibajelentések és a letölthető Windows-kiadások szerepelnek. A program C# forráskódját itt nem tesszük közzé.

[**Windows letöltés – GitHub Releases**](https://github.com/vizisiklo/Box-Mockup-Generator/releases)

> Ha a Releases oldalon még nincs `BoxMockupGenerator.exe` fájl, a letölthető kiadás még nincs feltöltve. Kérjük, csak a hivatalos kiadásból töltsd le.

## Az öt lépés

1. **Doboz méretének megadása:** X × Y × Z méret milliméterben; az előnézet automatikusan frissül. Az élek finom lekerekítése külön beállítható.
2. **CorelDRAW-sablon mentése:** méretpontos PDF vagy SVG, hat különálló, hézagmentesen összeérő téglalappal. A fájlnév tartalmazza a méreteket, például: `Box_UV_Contour_320x240x60mm.pdf`.
3. **Kész grafika betöltése:** importáld a PDF/SVG-sablont CorelDRAW-ba **100%-os méretarányban**, tervezd meg a teljes kiterítést, rejtsd el a segédvonalakat, majd az egész oldalt exportáld PNG-be. Ezt a PNG-t töltsd vissza a programba.
4. **Renderbeállítások:** válassz kameranézetet, anyagot, világítást, hátteret és árnyékot. A program alapból a normál 3D-előnézettel indul.
5. **Kép mentése:** exportáld a mockupot **1440 × 1440 pixeles PNG** formátumban.

A jobb oldali UV-előnézeten a sablon paneljei és a betöltött grafika is látszik. A kamera szabadon forgatható, a négyzetes képkivágáshoz 5%-os biztonsági margó tartozik. Opcionálisan OBJ/MTL 3D-export is elérhető.

## Fontos CorelDRAW-tudnivalók

Az SVG/PDF **textúrakiterítés, nem gyártási stancrajz**: nem tartalmaz ragasztófüleket, nyomdai kifutót vagy vágási toleranciát. A hat téglalapot ne távolítsd el egymástól és ne méretezd át; a teljes grafika oldalarányát tartsd meg. Álló és fekvő dobozoknál eltérhet a panelkiosztás, ezt a program súgója mutatja.

## Rendszerigény és telepítés

- Windows 10/11, 64 bites.
- A [Releases oldalról](https://github.com/vizisiklo/Box-Mockup-Generator/releases) töltsd le a `BoxMockupGenerator.exe` fájlt.
- Másold egy választott mappába, és indítsd el. A program használatához a CorelDRAW nem kötelező; csak a grafikai szerkesztéshez kell valamilyen megfelelő alkalmazás.
- A program próbaállapotú, előfordulhatnak hibák. A stúdiórender egyes anyag- és fényhatásai közelítések.

## Nyelvek

24 hivatalos EU-nyelv közül lehet választani a bal panel alján. Első indításkor a program megpróbálja követni a Windows nyelvi beállítását. Egyes haladó szövegek angolul is megjelenhetnek.

## Felhasználási feltételek

A Free Beta **ingyenesen használható magán- és kereskedelmi grafikai munkákhoz**, így 99designs- és ügyfélprezentációk készítéséhez is. A szoftver módosítása, önálló továbbfejlesztése és engedély nélküli továbbterjesztése a jelenlegi feltételek szerint nem megengedett. A részletek: [Felhasználási feltételek](TERMS_OF_USE.md).

A korábban jogszerűen GPL-3.0 alatt közzétett verziókra megadott jogosultságokat az új terjesztési feltételek nem vonják vissza.

## Hibajelentés

A [GitHub Issues](https://github.com/vizisiklo/Box-Mockup-Generator/issues) oldalon add meg a programverziót, a Windows-verziót és a hiba lépéseit. Bizalmas ügyfélgrafikát ne tölts fel nyilvános hibajegyhez.

Copyright © 2026 vizisiklo. Minden jog fenntartva.
