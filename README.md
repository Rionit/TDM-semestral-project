Popis odevzdávání semestrálních projektů z předmětu **TDM**.
=
Struktura
-

1. semestrální práce se odevzdává do adresáře `tdm_submission/sem_I` - do odpovídajících adresářů.
2. semestrální práce se odevzdává do adresáře `tdm_submission/sem_II` - do odpovídajících adresářů.

struktura adresářů jednotlivých studentů je následující a obsah bude odpovídat požadavkům:

`description.txt` - sem vyplňte vaše jméno a popis vašeho projektu - přepište to, co tam je. Je potřeba dodržet řádkování!

`project`: do tohoto adresáře nahrajte kompletní !ZAKOMPRIMOVANÝ! projektový adresář, včetně rozumného množství záloh. Nezapomeňte jednoznačně pojmenovat poslední verzi a tu uložit jak v MayaBinary (.mb) tak v MayaAscii (.ma). Nezapomeňte vymazat všechny temporary data (renders, obrázky videosekvence, atd...). Velikost by měla být do cca 100MB.

`renders`: sem nahrajte pouze rendery ve vysokém rozlišení - doporučený formát je PNG, případně JPG (s TIFFem neumí pracovat server).

`resources`: tady bude seznam všech zdrojů, referencí, podkladů, tutoriálů, které jste použili (fotografie, textury, zvuky, knihy...) s odkazem odkud jste je pořídili. Případně zde budou i jejich kopie. Nezapomeňte dodržovat autorská práva! 

`video`: finální vyrenderovaná videosekvence komprimovaná vhodným kodekem (Xvid, DivX, MPEG-4, H.264, H.265 ...) - nenahrávejte nekomprimované videosekvence - není na to místo.

podívejte se na ukázkový projekt https://gitlab.fel.cvut.cz/b221_b6b39tdm/sample_project

Odevzdání
-
Projekty v adresáři `tdm_submission` se automaticky nahrají na webové stránky (gelerie), pokud se k aktuálnímu commitu ve větvi `master` přidá `tag` - na jménu nezáleží, ale doporučená syntaxe je např. `rel_sem1_v1` (release sem1 v1). Doporučuji vyzkoušet někdy předem se správně upraveným description.

* webové stránky galerie pro rok 2022
    * sem1 - https://leyfi.felk.cvut.cz/courses/tdm/?year=2022&presenter=Project
    * sem2 - https://leyfi.felk.cvut.cz/courses/tdm/?year=2022&projID=sem_2&presenter=Project
* příklad vytvoření tagu (git bash)
    * vytvoření tagu: `git tag -a rel_sem1_v1.3 -m "release sem1 v1.3 - better render"`
    * push (upload) tagu na gitlab: `git push --tags`

*******************************
 david sedláček - 11.10.2022
*******************************