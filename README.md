# Peleton Panika

Gra przeglądarkowa dla ludzi, którzy naprawdę znają się na kolarstwie. Wielki Tour złożony z 21 rodzajów mikroetapów po kilka sekund: komenda po kolarsku, szybka reakcja, kolejny etap.

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
| **BRUK! ★★★★★** | Łapanie równowagi na kocich łbach. Sektory z gwiazdkami, gładkie pobocze i kibice przy drodze. |
| **PRZERWA NA SIKU!** | Trzymasz przycisk i puszczasz, gdy ktoś nadchodzi: motor telewizji, kamper, wycieczka szkolna, babcia z jamnikiem. Siusianie przy kibicach to kara UCI. |
| **KARAMBOL!** | Przeskoki nad leżącym rowerem, zgubionym kołem i kłębowiskiem kolarzy. |
| **ZJAZD! AGRAFKA** | Hamujesz przed zakrętem, nie w nim. Za szybko lądujesz w snopkach siana. |
| **SZLABAN!** | Zatrzymujesz się przed zamkniętym przejazdem kolejowym. Kto przejedzie, dostaje dyskwalifikację (rywal właśnie ją dostał). |
| **ŚCIANA! NA STOJĄCO!** | Pedałowanie w tańcu, na zmianę lewa i prawa, przez tunel kibiców do kapliczki na szczycie. |
| **CZASÓWKA!** | Trzymasz moc na progu. Za mocno i bateria W′ się wyczerpuje, za lekko i brakuje sekund. |
| **NOSIWODA!** | Łapiesz bidony rzucane z wozu technicznego i wozisz je pod koszulką. |
| **ZMIANA KOŁA!** | Szybka sekwencja przycisków: łańcuch na najmniejszą, szybkozamykacz, koło, zacisk, pchnięcie mechanika. |
| **PODIUM!** | Wstrząsasz szampanem i strzelasz. Za mocno i korek strąca komisarzowi kapelusz. |

Po drodze trafiają się niespodzianki (wóz techniczny, dzień przerwy, kontrola skarpetek, gazeta pod koszulkę na zjazd, kontrola antydopingowa, kibic w stroju kurczaka, lotna premia ×2, dzwonki krowie), a za punkty wpadają koszulki: biała, w grochy, zielona, żółta i tęczowa.

## Poziomy

- **Spacerkiem** (domyślny): wolne tempo, 5 dętek, łagodniejsze okna na reakcję.
- **Peleton**: średnie tempo, 4 dętki.
- **Wyścig**: pełne tempo, 4 dętki.

Gra zapamiętuje wybrany poziom.

## Dźwięk

Wszystkie dźwięki i muzyka są generowane w przeglądarce, bez plików: dzwonek rowerowy, syk kapcia, terkot wolnobiegu, dzwonki krowie, gwizd pociągu, korek szampana. W tle gra własny walc musette (akordeon i um-pa-pa), który przyspiesza razem z peletonem. Dźwięk startuje po pierwszym dotknięciu ekranu. Na iPhonie gra stara się grać także przy włączonym trybie cichym.

## Sterowanie

- Klawiatura: strzałki albo WASD, spacja = akcja, P = pauza, M = dźwięk.
- Telefon: stukanie w scenę (lewa połowa = lewo, prawa = prawo, w etapach z jedną akcją działa stuknięcie gdziekolwiek) albo przyciski pod sceną.
