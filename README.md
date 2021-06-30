# chess-java-preview

<p align="center">
  <img width=500, src="https://user-images.githubusercontent.com/86607609/123974543-f60c1c80-d9bc-11eb-8fb8-6382e2811e21.png" />
</p>

<p align="center">
  Chess game made for a college assignment using Java.
</p>

Note: Project documentation and code itself (class/method names) were written in Slovak language. <b>Code itself is in separated private repository to block any possible attempt of plagiarism from college students.</b>

Original description in Slovak language:

Hra šach bola navrhnutá a naprogramovaná v rovnakej forme, v akej je známa s rovnako platnými pravidlami. Hrá sa na šachovnici o rozmeroch 8x8 zloženej z dvojrozmerného poľa tlačidiel JButton, ktoré majú pozmenený dizajn a rozmer pre potreby šachovnice. Tlačidlá sú interaktívne, pri jednotlivých ťahoch podfarbujú zvolené figúrky. Šachovnica pomocou nich taktiež vizualizuje šach/šach-mat, a to podfarbením šachovaného kráľa a figúrky, ktorá ho šachuje. Pohyby figúrok sú povolené iba podľa pravidiel, čo predchádza neplatným ťahom. To zahrňuje aj ťahy s figúrkami, kedy hra vyhodnocuje ako neplatný ťah akýkoľvek pohyb, ktorý by dostal kráľa do šachu. Rovnako platí, že ak sa nachádza kráľ v šachu, tak je ako platný ťah vyhodnotený iba ten, ktorý dostane kráľa zo šachu, tj. pohyb kráľa do strany, ktorý neskončí opätovným šachom, vyhodenie figúrky, ktorá drží kráľa v šachu alebo zablokovanie cesty ku kráľovi danej figúrke, ktorá ho drží v šachu. Taktiež pokiaľ prejde pešiak cez celú šachovnicu, otvorí sa mu kontextové okno, v ktorom si hráč zvolí, na ktorú zo štyroch figúrok sa pešiak zmení. Ak hra skončí šach-matom, kontextové okno o tom upozorní hráča a hra šach-mat vizualizuje.

Súčasťou hry je aj ovládací panel, na ktorom je možné vykonávať rôzne operácie s rozohranou hrou. Prvým ovládacím prvkom je uloženie hry, ktorý vezme aktuálne rozohranú hru a uloží ju do súboru pod názvom určeným hráčom. Prvok obsahuje ošetrenie chybných vstupov, ako je napríklad neplatný názov súboru alebo už existujúci súbor, na čo hra užívateľa náležite upozorní. Druhým prvkom je načítanie už uloženej hry. V tomto prípade sa otvorí kontextové okno so zoznamom hier, z ktorých sa následne po hráčovom výbere načíta hra na šachovnicu. Prvok upozorňuje na možné chyby, akými je napríklad poškodený súbor. V takomto prípade hra načíta predvolené rozloženie hry a hráča upozorní, kde pri čítaní zo súboru nastalo ku chybe. Tretím prvkom je zmazanie už uloženej hry, ktoré hráčovi otvorí kontextové okno so zoznamom uložených hier. Hra, ktorú hráč vyberie sa následne vymaže. Nasledujúci prvok pomenovaný „Resetuj hru“ resetuje šachovnicu na jej predvolené rozloženie. Posledným prvkom je zmena témy hry, ktorá sa dá meniť po celú dobu hrania. Hra obsahuje niekoľko farebných paliet, ktoré sa menia v závislosti od aktuálnej témy, ktorá sa nastavuje pomocou daného tlačidla. Vzhľad mení farbu šachovnice, podfarbenia figúrok pri zakliknutí a taktiež podfarbenie pri vizualizácii šachu.
