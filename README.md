# Heideggers φύσις

Deze repository biedt een overzicht van het voorkomen van het lemma φύσις in Heideggers _Gesamtausgabe_. Hiervoor is dankbaar gebruik gemaakt van het lemma uit Patrick Unruhs [_Register zur Martin Heidegger Gesamtausgabe_](https://www.klostermann.de/Unruh-Patrick-Register-zur-Martin-Heidegger-Gesamtausgabe) uit 2017, met [enkele correcties](./index/errata.yml) en [aangevuld](./index/complement.yml) met alle delen die sinds Unruhs publicatie zijn verschenen.

## Kanttekeningen

* De protocollen uit GA 83 t/m 88 zijn achterwege gelaten in de datering. De vermeldingen in de notities niet. <!-- Wat zijn de 'Ergängzungen' uit GA 88? -->
* Niet door Unruh meegenomen: vol. 38A, 72, 80.1, 80.2, 82, 84.2, 91-93, 98-102 (14 delen)
* Niet te dateren: 
  * GA 73: Tijdspanne van ongeveer dertig jaar (*Nachwort des Herausgebers*, p. 1489)
  * GA 74
  * GA 76 (gedachten stammen uit de periode 1933 t/m 1955... wel echt een φύσις-band!)
  * GA 81 (eind jaren 30, begin jaren 40)
  * GA 91, *Denksplitter* (tweede deel): Periode van 4 decennia (*Nachwort de Herausgebers*, p. 771)

### Meerdere jaren

Een aantal werken zijn niet op een enkel jaar toe te spitsen. Voorbeelden hiervan zijn de colleges gegeven in het wintersemester (die altijd het eind van het jaar en het begin van het volgende jaar bestrijken), maar er zijn ook andere teksten waarvan de datering een reeks jaren is, en waarvaan geen preciezere datering meer te achterhalen is.  Voorbeelden zijn:

* *Beiträge* (GA 65): 1936-1938. Uit het *Nachwort des Herausgebers* blijkt dat het deel ‘Das Seyn’ uit 1938 komt, en de rest uit 1936/37 (GA 65, p. 515).
* ‘Die Geschichte des Seyns’ (GA 69, eerste deel): 1938-40

In al deze gevallen is ervoor gekozen om het eerste jaar uit de reeks aan te houden.

## Errata

In [`errata.yml`](./errata.yml) zijn de correcties op de index van Unruh aangebracht, in drie varianten:

```yaml
2:
- 282: null
5:
- 40
45:
- 137: 136f
```

In dit voorbeeld geldt:

* GA 2, p. 282 moet worden verwijderd
* GA 5, p. 40 moet worden toegevoegd
* GA 45, p. 137 moet worden vervangen door 136f.

## Categorisering

We categoriseren de referenties op basis de context waarin φύσις in de passages ter sprake komen. Deze categorieën zijn weer te groeperen:

1. Antieke referenties waarin φύσις ter sprake komt
2. Vertalingen die van φύσις gegeven worden 
3. Andere begrippen of Griekse termen waar φύσις mee in verband wordt gebracht (of tegen af wordt gezet).
4. Een bepaalde variatie van φύσις ter sprake komt

We sommen hieronder de gebruikte categorieën op in de drie genoemde groepen.

### Antieke referenties

|     Code | Toelichting                                 |
| -------: | :------------------------------------------ |
| `Her123` | Heraclitus, fr. 123: φύσις κρύπτεσθαι φιλεῖ |
| `Emped8` | Empedocles, Fr. 8                           |
| `Aia647` | Sophokles, *Aias*, vs. 647 (φύειν)          |
| `Platon` | φύσις bij Plato                             |

### Vertalingen

|     Code | Toelichting                                 |
| -------: | :------------------------------------------ |
| `SeiIGa` | Vert. als *Seiende im Ganzen*               |
| `SeAlSo` | Vert. als *Seiende als solches*             |
| `ReiAuf` | Vert. als *Reine Aufgehen*                  |
| `Aufgeh` | Vert. als *Aufgehen*                        |
| `Aufgan` | Vert. als *Aufgang*                         |
| `Hervor` | Vert. als *Hervorbringen*                   |
| `Anwahr` | Vert. als *Anwähren*                        |

### Andere begrippen

|     Code | Toelichting                                 |
| -------: | :------------------------------------------ |
| `PhuNat` | φύσις en natuur                             |
| `PhuErd` | φύσις en aarde                              |
| `PhuTex` | φύσις tegenover τέχνη                       |
| `PhuLet` | φύσις tegenover λήθη                        |
| `PhuThe` | φύσις tegenover θέσις                       |
| `PhuAle` | φύσις en ἀλήθεια                            |
| `PhuLog` | φύσις en λόγος                              |
| `PhuMoi` | φύσις en Μοῖρα                              |
| `PhuPoi` | φύσις en ποίησις                            |
| `Verneh` | *Vernehmende des Seienden* / φύσις en νοεῖν |
| `Entmac` | *Entmachtung der* φύσις                     |
| `Physik` | Physik                                      |

### Variatie

|     Code | Toelichting                                 |
| -------: | :------------------------------------------ |
| `Phusio` | φυσιολόγοι                                  |
| `Metaph` | Metaphysik/μετὰ τὰ φύσικα                   |
| `Phuein` | φύειν                                       |
| `Pephuk` | πέφυκε                                      |
| `PhuOnt` | φύσει ὄντα                                  |
| `ProPhu` | πρότερον φύσει                              |
| `Episte` | ἐπιστήμαι ἠθική, λογική & φυσική            |
| `PerPhu` | περὶ φύσεως                                 |

