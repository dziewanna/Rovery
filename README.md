# Peleton Panika

Gra przeglądarkowa dla ludzi, którzy naprawdę znają się na kolarstwie. Wielki Tour złożony z mikroetapów po kilka sekund: komenda po kolarsku, szybka reakcja, kolejny etap.

Wystarczy otworzyć `index.html` w przeglądarce. Nie trzeba niczego instalować. Gra jest robiona przede wszystkim pod telefon, w pionie.

## Styl

Malowana animacja w duchu francuskiej karykatury lat 50.: ciepła sepia, akwarelowe tła, ołówkowy kontur, który lekko „drga” jak w ręcznie rysowanym filmie, cieniowanie grafitowym kreskowaniem, ziarno taśmy i winieta.

Kolarze to własne postacie w tym duchu: chudy, przygarbiony tors, długa szyja, mała głowa z wielkim opadającym nosem i smutnymi oczami, ręce jak makaron i monstrualne, ogolone, lśniące uda i łydki. Epoka też się zgadza: wełniane koszulki z pasami, kolarskie czapeczki z podwiniętym daszkiem, skórzany kask „siateczkowy” u rywala, zapasowa szytka zawieszona na ramionach, stalowe ramy z chromowanymi (albo złotymi) mufami, srebrne obręcze, bidon w koszyku na kierownicy, pętla linki hamulca, noski z paskami i skórzane siodła z nitami. Kibice są groteskowi: gruby pan w berecie, chudzielec, przysadzista babcia w wielkich okularach.

Wszystko rysuje kod na canvasie, bez plików graficznych.

## Etapy

| Komenda | Co trzeba wiedzieć |
|---|---|
| **NA KOŁO!** | Przy bocznym wietrze cień aerodynamiczny jest po zawietrznej, ukośnie za kołem. |
| **ZAKRĘT W LEWO / PRAWO!** | Zewnętrzny pedał w dół, inaczej pedał zahacza o asfalt. |
| **BIDON DO STREFY!** | Bidon wyrzuca się tylko w strefie zrzutu (przepisy UCI), nawet gdy kibic prosi wcześniej. |
| **ODEPNIJ SIĘ!** | Wypięcie z pedału przed zatrzymaniem. Przy kawiarni pełnej ludzi. |
| **RZUT NA KRESKĘ!** | Rzut rowerem dokładnie na linii mety. Rozstrzyga fotofinisz. |
| **POMPUJ!** | Właściwe ciśnienie dla opony. Hookless ma limit 5 bar. |
| **SIEDŹ NA KOLE!** | Rywal macha łokciem, a Ty nie wychodzisz na zmianę. Chyba że radio krzyknie „ATAK!”. |
| **PODJAZD / ŚCIANA X%!** | Przełożenie do kadencji 80–100 rpm. Prędkość liczona z prawdziwej fizyki dla 300 W. |
| **BUFET!** | Musette tylko od swojego masażysty. Nie od kibica z kiełbasą. |
| **DZIKI NA TRASIE!** | Slalom między dziurami, jamnikiem, kibicami, babcią z grzybami i rodziną dzików. |
| **RADIO Z WOZU!** | Pytanie od dyrektora sportowego: koszulki, klasyki, przepisy, sprzęt. |

Po drodze trafiają się niespodzianki (wóz techniczny, kontrola skarpetek, lotna premia ×2, dzwonki krowie), a za punkty wpadają koszulki: biała, w grochy, zielona, żółta i tęczowa.

## Poziomy

- **Spacerkiem** (domyślny): wolne tempo, 5 dętek, łagodniejsze okna na reakcję.
- **Peleton**: średnie tempo, 4 dętki.
- **Wyścig**: pełne tempo, 4 dętki.

Gra zapamiętuje wybrany poziom.

## Sterowanie

- Klawiatura: strzałki albo WASD, spacja = akcja, P = pauza, M = dźwięk.
- Telefon: stukanie w scenę (lewa połowa = lewo, prawa = prawo, w etapach z jedną akcją działa stuknięcie gdziekolwiek) albo przyciski pod sceną.
