# 2048

## Apraksts
Origenal 2048 ir pārlūkprogrammas spēle, ko JavaScript programmēšanas valodā (https://play2048.co) sarakstījis 19 gadus vecais itāļu izstrādātājs Gabriele Cirulli. Spēles laukumam ir 4x4 kvadrāta forma. Spēles mērķis ir iegūt 2048 nominālvērtības flīzi (ja vēlaties, varat turpināt tālāk). Es kā projekts tehnikumā gribu uzrakstīt 2048, tikai C ++, izmantojot SFML bibliotēku.
## Galvenās funkcijas
Katrā kārtā parādās flīze ar nominālu "2" (ar varbūtību 90%) vai "4" (ar varbūtību 10%)
Nospiežot bultiņu, spēlētājs var nomest visas spēles laukuma flīzes vienā no 4 virzieniem. 
Ja, nometot, divas viena nomināla flīzes "saskaras" viena ar otru, tad   tās pārvēršas par vienu, kuras nominālvērtība ir vienāda ar savienoto flīžu summu.
Pēc katras kustības brīvajā lauka daļā parādās jauna flīze ar nominālvērtību "2" vai "4". Ja, nospiežot pogu, flīžu atrašanās vieta vai to nominālvērtība nemainās, gājiens netiek veikts.
Ja vienā rindā vai vienā kolonnā ir vairāk nekā divas viena un tā paša nomināla flīzes, tad, nokrītot, tās sāk savienoties no tās puses, uz kuru tās bija vērstas.
Piemēram, flīzes (4, 4, 4) tajā pašā rindā pārvērtīsies par (8, 4) pēc gājiena pa kreisi un par (4, 8) pēc gājiena pa labi. Šāda neskaidrību apstrāde ļauj precīzāk veidot spēles stratēģiju.
Par katru savienojumu spēles punkti tiek palielināti par iegūtās flīzes nominālvērtību.
Spēle beidzas ar sakāvi, ja pēc nākamā gājiena nav iespējams veikt darbību.
## Izmantotās tehnoloģijas
- C++
- SFML library
## Izmantotie avoti
- [SFML dokumentācija](https://www.sfml-dev.org/style.php)
