---
title: "GCH - Informatika"
excerpt: "Repozitář obsahuje výukové lekce pro programování v C++ zaměřené na konzolové aplikace. Každá lekce obsahuje příklady kódu a úkoly. <br/><img style='border: 2px solid lightgray; border-radius: 8px;' src='https://dominiksimon.com/images/project1.png'>"
collection: portfolio
permalink: gch-informatika
---

## Lekce 1: Úvod do programování, základní pojmy (proměnné, datové typy, operátory)

V této lekci se naučíte základní pojmy programování, jako jsou proměnné, datové typy a operátory. Naučíte se, jak deklarovat proměnné, přiřazovat jim hodnoty a používat různé operátory pro provádění výpočtů.

**Proměnná** je místo v paměti, kde můžete uložit hodnotu, která se může měnit během běhu programu.  
**Datové typy** určují, jaký druh hodnoty může proměnná obsahovat (např. celé číslo, desetinné číslo, znak).  
**Operátory** jsou symboly, které provádějí operace s hodnotami (např. sčítání, odčítání, násobení).

| Datový typ |   Velikost    | Popis                                                                    |
| ---------- | :-----------: | ------------------------------------------------------------------------ |
| boolean    |     1 byt     | Ukládá pravdivé nebo nepravdivé hodnoty.                                 |
| char       |     1 byt     | Ukládá jeden znak/písmeno/číslo nebo hodnoty ASCII.                      |
| int        | 2 nebo 4 byty | Ukládá celá čísla bez desetinných míst.                                  |
| float      |    4 byty     | Ukládá zlomková čísla obsahující jedno nebo více desetinných míst. (6-7) |
| double     |    8 bytů     | Ukládá zlomková čísla obsahující jedno nebo více desetinných míst. (15)  |

## Lekce 2: Instalace a nastavení vývojového prostředí (IDE)

V této lekci se naučíte, jak nainstalovat a nastavit vývojové prostředí (IDE) pro programování v C++. Nainstalujete si jedno z doporučených IDE a napíšete svůj první program "Hello World".

**IDE (Integrated Development Environment)** je software, který poskytuje komplexní prostředí pro vývoj softwaru. Obsahuje editor kódu, kompilátor, debugger a další nástroje, které usnadňují vývoj aplikací.

## Lekce 3: První program v C++ (Hello World)

V této lekci napíšete a upravíte jednoduchý program v C++, který vypisuje "Hello, World!" a následně vaše jméno. Naučíte se základní strukturu programu v C++ a práci s řetězci.

**Řetězec (string)** je sekvence znaků, která se používá k reprezentaci textu. V C++ se řetězce obvykle používají pomocí třídy `std::string`.

## Lekce 4: Podmíněné příkazy (if, else)

V této lekci se naučíte používat podmíněné příkazy `if` a `else`. Naučíte se, jak provádět různé akce na základě podmínek a jak používat logické operátory.

**Podmíněné příkazy** umožňují programu rozhodovat, které části kódu se mají provést na základě splnění určitých podmínek.  
**Logické operátory** (např. `&&`, `||`, `!`) se používají k vytváření složených podmínek.

| Logické ustanovení   |        |
| -------------------- | :----: |
| menší než            | a < b  |
| menší nebo rovno než | a <= b |
| větší než            | a > b  |
| větší nebo rovno než | a >= b |
| rovno                | a == b |
| není rovno           | a != b |

## Lekce 5: Podmíněné příkazy (switch)

V této lekci se naučíte používat podmíněný příkaz `switch`. Naučíte se, jak provádět různé akce na základě hodnoty proměnné a jak používat příkaz `break`.

**Příkaz `switch`** umožňuje programu provádět různé akce na základě hodnoty proměnné.  
**Příkaz `break`** ukončuje provádění bloku `switch` a přenáší řízení na následující příkaz za blokem `switch`.

## Lekce 6: Smyčka for

V této lekci se naučíte používat smyčku `for`. Naučíte se, jak opakovat blok kódu pevně stanovený počet opakování a jak používat smyčku `for` pro iteraci přes pole.

**Smyčka `for`** se používá k opakování bloku kódu pevně stanovený počet opakování.  
**Iterace** je proces opakování bloku kódu pro každý prvek v kolekci (např. pole).

## Lekce 7: Smyčka while

V této lekci se naučíte používat smyčku `while`. Naučíte se, jak opakovat blok kódu, dokud je podmínka pravdivá, a jak používat smyčku `while` pro různé úlohy.

**Smyčka `while`** se opakuje, dokud je podmínka pravdivá. Používá se, když nevíte předem, kolikrát se má smyčka opakovat.

## Lekce 8: Smyčka do-while

V této lekci se naučíte používat smyčku `do-while`. Naučíte se, jak opakovat blok kódu alespoň jednou a jak používat smyčku `do-while` pro různé úlohy.

**Smyčka `do-while`** se opakuje, dokud je podmínka pravdivá, ale na rozdíl od smyčky `while` se podmínka kontroluje až po provedení bloku kódu, takže se blok kódu provede alespoň jednou.

## Lekce 9: Příkaz goto

V této lekci se naučíte používat příkaz `goto`. Naučíte se, jak provádět skoky na různé části kódu a jak používat příkaz `goto` pro řízení toku programu.

**Příkaz `goto`** umožňuje provádět skoky na různé části kódu pomocí štítků. Používá se zřídka, protože může vést k nečitelnému a těžko udržovatelnému kódu.

## Lekce 10: Použití matematických funkcí (cmath)

V této lekci se naučíte používat matematické funkce z knihovny `cmath` v C++. Naučíte se, jak používat funkce pro výpočet druhé odmocniny, mocniny, absolutní hodnoty, sinusu, kosinu a tangens.

**Matematické funkce z knihovny `cmath`:**

| Funkce      | Popis                                       |
| ----------- | ------------------------------------------- |
| `sqrt(x)`   | Vypočítá druhou odmocninu z hodnoty `x`.    |
| `pow(x, y)` | Vypočítá mocninu hodnoty `x` na `y`.        |
| `fabs(x)`   | Vypočítá absolutní hodnotu z hodnoty `x`.   |
| `sin(x)`    | Vypočítá sinus hodnoty `x` (v radiánech).   |
| `cos(x)`    | Vypočítá kosinus hodnoty `x` (v radiánech). |
| `tan(x)`    | Vypočítá tangens hodnoty `x` (v radiánech). |

## Lekce 11: Součet cifer

V této lekci se naučíte využít cyklus `while` k výpočtu součtu cifer. Nejprve se seznámíte se základy cyklu `while`, který umožňuje opakovat blok kódu, dokud je splněna určitá podmínka. Poté si vytvoříte algoritmus, který bude postupně rozkládat číslo na jednotlivé cifry a tyto cifry sčítat, dokud nezískáte konečný součet.

## Lekce 12: Euklidův algoritmus

V této lekci se naučíte implementovat Euklidův algoritmus pro výpočet největšího společného dělitele (NSD) dvou čísel. Nejprve si vysvětlíme teorii Euklidova algoritmu a jeho historický význam. Poté přejdeme k praktické části, kde pomocí tohoto algoritmu vytvoříte funkci, která bude schopna rychle a efektivně určit NSD pro dvě zadaná čísla.

## Lekce 13: Leibnizova řada

V této lekci se naučíte používat Leibnizovu řadu pro aproximaci hodnoty π. Začneme vysvětlením principu Leibnizovy řady, která pomocí nekonečné posloupnosti čísel umožňuje přibližně vypočítat hodnotu π. Následně se zaměříme na implementaci tohoto výpočtu v kódu, přičemž si ukážeme, jak pomocí této řady postupně získávat stále přesnější hodnoty π.

## Lekce 14: Cyklus for

V této lekci se naučíte používat cyklus `for` pro iterace, což je základní konstrukce pro opakování bloků kódu. Nejprve si vysvětlíme syntax a základní použití cyklu `for` v různých kontextech, jako je iterace přes seznamy a řetězce. Poté se podíváme na praktické příklady, které vám ukážou, jak cyklus `for` efektivně využít v různých programátorských situacích.

## Lekce 15: Hra o hádání čísel ze součtu a ze součinu

V této lekci se naučíte vytvářet interaktivní hru na hádání čísel pomocí součtu a součinu. Začneme návrhem herního algoritmu, který bude využívat matematické operace pro určení součtu a součinu náhodně vybraných čísel. Následně tento algoritmus implementujeme v kódu a vytvoříme interaktivní hru, kterou si budete moci zahrát a testovat své logické myšlení.

## Lekce 16: Výpočet mocniny pomocí cyklu for

V této lekci se naučíte vypočítat mocninu čísla pomocí cyklu `for`. Nejprve si vysvětlíme algoritmus, který využívá opakované násobení pro výpočet mocniny. Poté tento algoritmus implementujeme v kódu pomocí cyklu `for`, který nám umožní opakovat násobení, dokud nedosáhneme požadované mocniny.

## Lekce 17: Výpočet stěnových úhlopříček kvádru pomocí volané funkce

V této lekci se naučíte vypočítat stěnové úhlopříčky kvádru pomocí volané funkce. Nejprve si vysvětlíme teorii týkající se geometrie kvádru a stěnových úhlopříček. Poté vytvoříme funkci, která bude přijímat rozměry kvádru jako parametry a bude vracet délku úhlopříčky. Následně tuto funkci zavoláme v hlavním programu a demonstrujeme její použití na konkrétních příkladech.

## Lekce 18: Výpočet na kolikátý pokus padla sestka ze tří kostek

V této lekci se naučíte simulovat házení třemi kostkami a sledovat, na kolikátý pokus padla alespoň jedna šestka. Začneme vytvořením algoritmu, který bude generovat náhodná čísla reprezentující hody kostkami. Poté vytvoříme funkci, která bude tyto hody opakovat, dokud nepadne alespoň jedna šestka. Na závěr zhodnotíme výsledky a pokusíme se analyzovat pravděpodobnost úspěchu.

## Lekce 19: Hanojská věž

V této lekci se naučíte řešit problém Hanojské věže pomocí rekurze. Nejprve si vysvětlíme pravidla a principy Hanojské věže, která zahrnuje přesouvání disků mezi třemi tyčemi podle určitých pravidel. Poté implementujeme rekurzivní algoritmus, který tento problém vyřeší.

**Hanojská věž** je logická hra, která zahrnuje přesouvání disků mezi třemi tyčemi podle následujících pravidel:

1. Na každé tyči může být pouze jeden disk.
2. Disky musí být přesouvány jeden po druhém.
3. Na žádné tyči nesmí být větší disk nad menším diskem.

## Lekce 20: Hledání maximální hodnoty v poli a aritmetický průměr pole

V této lekci se naučíte, jak najít maximální hodnotu v poli a vypočítat aritmetický průměr hodnot v poli. Nejprve si vysvětlíme, jak iterovat přes pole a porovnávat jeho prvky. Poté implementujeme algoritmus pro hledání maximální hodnoty a výpočet aritmetického průměru.

**Pole** je datová struktura, která ukládá sekvenci hodnot stejného typu.  
**Aritmetický průměr** je součet všech hodnot v poli dělený počtem hodnot.

## Lekce 21: Převod čísla z desítkové soustavy na dvojkovou

V této lekci se naučíte převádět čísla z desítkové soustavy na dvojkovou. Nejprve si vysvětlíme principy číselných soustav a postup převodu. Poté implementujeme algoritmus, který převede zadané desítkové číslo na dvojkové.

**Desítková soustava** je číselná soustava s základem 10, která používá číslice 0-9.  
**Dvojková soustava** je číselná soustava s základem 2, která používá číslice 0 a 1.

## Lekce 22: Bubble sort

V této lekci se naučíte používat algoritmus Bubble sort pro řazení prvků v poli. Nejprve si vysvětlíme princip Bubble sortu, který opakovaně prochází pole a porovnává sousední prvky, přičemž je vyměňuje, pokud nejsou ve správném pořadí. Tento proces se opakuje, dokud není celé pole seřazeno.

**Bubble sort** je jednoduchý řadicí algoritmus, který opakovaně prochází pole, porovnává sousední prvky a vyměňuje je, pokud nejsou ve správném pořadí. Tento proces se opakuje, dokud není celé pole seřazeno.

### Další řadicí algoritmy

Kromě Bubble sortu existují i další řadicí algoritmy, které se liší svou složitostí a efektivitou. Níže je uveden přehled některých z nich:

| Algoritmus     | Popis                                                                                                | Průměrná doba trvání |
| -------------- | ---------------------------------------------------------------------------------------------------- | -------------------- |
| Selection sort | Opakovaně hledá nejmenší prvek v nesetříděné části pole a umisťuje ho na správné místo.              | O(n^2)               |
| Insertion sort | Staví setříděné pole jeden prvek po druhém, vkládáním každého nového prvku na správné místo.         | O(n^2)               |
| Merge sort     | Rozděluje pole na dvě poloviny, setřídí každou polovinu a poté je sloučí.                            | O(n log n)           |
| Quick sort     | Vybere pivotní prvek a rozděluje pole na části menší a větší než pivot, poté rekurzivně třídí části. | O(n log n)           |
| Heap sort      | Vytváří binární haldu z pole a opakovaně extrahuje maximální prvek a umisťuje ho na konec pole.      | O(n log n)           |
| Radix sort     | Třídí čísla po jednotlivých cifrách, od nejméně významné po nejvíce významnou.                       | O(nk)                |
| Shell sort     | Vylepšený insertion sort, který třídí prvky s určitým odstupem a postupně zmenšuje tento odstup.     | O(n log^2 n)         |

## Lekce 23: Selection sort

V této lekci se naučíte používat algoritmus Selection sort pro řazení prvků v poli. Nejprve si vysvětlíme princip Selection sortu, který opakovaně hledá nejmenší prvek v nesetříděné části pole a umisťuje ho na správné místo. Tento proces se opakuje, dokud není celé pole seřazeno.

**Selection sort** je jednoduchý řadicí algoritmus, který opakovaně hledá nejmenší prvek v nesetříděné části pole a umisťuje ho na správné místo. Tento proces se opakuje, dokud není celé pole seřazeno.

## Lekce 24: Rekurze

V této lekci se naučíte, co je to rekurze a jak ji používat v programování. Rekurze je technika, při které funkce volá sama sebe, aby vyřešila menší podproblémy původního problému.

**Rekurze** je proces, při kterém funkce volá sama sebe, aby vyřešila menší podproblémy původního problému. Rekurze se často používá pro řešení problémů, které lze rozdělit na menší, podobné problémy.

### Příklady rekurze

| Příklad                 | Popis                                                                |
| ----------------------- | -------------------------------------------------------------------- |
| Faktoriál               | Výpočet faktoriálu čísla n (n!) pomocí rekurzivního volání.          |
| Fibonacciho posloupnost | Výpočet n-tého čísla Fibonacciho posloupnosti pomocí rekurze.        |
| Hanojská věž            | Řešení problému Hanojské věže pomocí rekurzivního algoritmu.         |
| Binární vyhledávání     | Vyhledávání prvku v setříděném poli pomocí rekurzivního dělení pole. |

## Lekce 25: Lambda výrazy

V této lekci se naučíte používat lambda výrazy v C++. Lambda výrazy jsou anonymní funkce, které můžete definovat přímo v místě, kde je potřebujete. Jsou užitečné pro krátké funkce, které se používají pouze jednou nebo několikrát.

**Lambda výraz** je anonymní funkce, kterou můžete definovat přímo v místě, kde ji potřebujete. Lambda výrazy mohou mít parametry a tělo, stejně jako běžné funkce.

### Syntaxe lambda výrazu

```cpp
[capture](parameters) -> return_type { body }
```

- **capture**: Určuje, které proměnné z okolního kontextu jsou dostupné v lambda výrazu.
- **parameters**: Seznam parametrů, které lambda výraz přijímá.
- **return_type**: (Volitelné) Určuje návratový typ lambda výrazu.
- **body**: Blok kódu, který se provede, když je lambda výraz volán.

### Příklady lambda výrazů

| Lambda výraz                                 | Popis                                                               |
| -------------------------------------------- | ------------------------------------------------------------------- |
| `[]() { return 42; }`                        | Lambda výraz bez parametrů, který vrací hodnotu 42.                 |
| `[x](int y) { return x + y; }`               | Lambda výraz s jedním parametrem, který vrací součet `x` a `y`.     |
| `[&](int a, int b) -> int { return a * b; }` | Lambda výraz s dvěma parametry, který vrací součin `a` a `b`.       |
| `[=]() mutable { x = 10; }`                  | Lambda výraz, který zachytává všechny proměnné hodnotou a mění `x`. |
| `[&](int n) { return n % 2 == 0; }`          | Lambda výraz, který vrací `true`, pokud je `n` sudé číslo.          |

Lambda výrazy jsou užitečné zejména v kombinaci s algoritmy z knihovny STL, jako jsou `std::for_each`, `std::transform` a další. Mohou vám pomoci psát čistší a čitelnější kód bez nutnosti definovat samostatné funkce.

## Lekce 26: Použití knihovny pro vektory

V této lekci se naučíte používat knihovnu pro vektory v C++. Vektory jsou dynamické pole, které mohou měnit svou velikost během běhu programu. Jsou součástí standardní knihovny C++ a poskytují mnoho užitečných funkcí pro práci s kolekcemi dat.

**Vektor** je dynamické pole, které může měnit svou velikost během běhu programu. Vektory jsou součástí standardní knihovny C++ a poskytují mnoho užitečných funkcí pro práci s kolekcemi dat.

### Základní operace s vektory

| Operace               | Popis                                                           |
| --------------------- | --------------------------------------------------------------- |
| `std::vector<int> v;` | Deklarace vektoru `v` pro ukládání celých čísel.                |
| `v.push_back(10);`    | Přidání prvku `10` na konec vektoru `v`.                        |
| `v.size();`           | Vrátí počet prvků ve vektoru `v`.                               |
| `v[0];`               | Přístup k prvnímu prvku vektoru `v`.                            |
| `v.pop_back();`       | Odstraní poslední prvek z vektoru `v`.                          |
| `v.clear();`          | Odstraní všechny prvky z vektoru `v`.                           |
| `v.empty();`          | Vrátí `true`, pokud je vektor `v` prázdný, jinak vrátí `false`. |

### Rozdíl mezi vektorem a polem (array)

| Vlastnost        | Vektor (`std::vector`)                             | Pole (array)                                    |
| ---------------- | -------------------------------------------------- | ----------------------------------------------- |
| Velikost         | Dynamická, může se měnit během běhu programu       | Statická, pevně daná při deklaraci              |
| Paměťová alokace | Automatická, spravovaná knihovnou STL              | Statická nebo dynamická, spravovaná uživatelem  |
| Funkce           | Poskytuje mnoho funkcí pro manipulaci s daty       | Omezené funkce, základní operace                |
| Bezpečnost       | Automaticky spravuje paměť, méně náchylné k chybám | Vyžaduje ruční správu paměti, náchylné k chybám |
| Výkon            | Mírně pomalejší kvůli dynamické správě paměti      | Rychlejší díky statické alokaci paměti          |

Vektory jsou velmi užitečné pro práci s dynamickými kolekcemi dat a poskytují mnoho funkcí, které usnadňují manipulaci s daty.