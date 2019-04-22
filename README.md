# IT topics #

Informacje o zmianach oraz nowych dokumentach znajdziesz pod: https://www.facebook.com/coderbrother

## 1. Architecture ##
* **relations (one-to-many, many-to-many)** - poprzez relację rozumiemy zalezność pomiedzy komponentami, zasobami, itp. Jako przykładu możemy użyć relacji ojciec-syn. Jest to typowa relacja jeden-do-wielu (one-to-many). Jeden ojciec może posiadać wielu synów, ale konkretny syn ma tylko jednego ojca.
* **backend system (BE)** - to system odpowiedzialny za przetwarzanie danych otrzymanych lub wykonywanie zadań przekazanych przez system FE. W odpowiedzi na żądanie może on udzielić odpowiedzi i przekazać rezultaty do systemu FE.
* **frontend system (FE)** - to system zbierający żądania klienta i przekazujący zadania do systemu BE.
* **cloud system (AWS, Azure)** - system odpowiedzialny za dynamiczne tworzenie zasobów infrastruktury taki jak serwery, połączenia sieciowe, bazy danych itp. Różni się to od podejscia, w którym wszystkie zasoby są predefiniowane a każde nowe wymagania są związane z ingerencją zespołu odpowiedzialnego za infrastrukturę.
* **cloud provider** - dostawca usług chmurowych. Dostępni usługodawcy: AWS, Microsoft Azure, Google Cloud.
* **data center** - dedykowane miejsce przeznaczona do przechowywania działającej infrastruktury informatycznej: serwerów, urządzeń przechowywania danych oraz infrastruktury sieciowej.
* **microservice** - system odpowiedzialny za konkretną funkcjonalność. Dostarcza rozwiązań dla jasno określonej domeny.
* **monolith system/application** - system odpowiedzilny za realicję złożonych zadań obejmujących wiele zadań, które niekoniecznie są związane z tą samą domeną.
* **No-SQL database** - baza danych, w której dane są modelowane w sposób inny niż za pomocą relacji znanych relacyjnych baz danych.
* **relational database** - baza daych, w której podstawą modelowania danych są relacje.
* **proxy** - pośrednik w systemach informatycznych. Odpowiedzialny za wykonywanie działań w imieniu osoby wysyłającej żądanie.
* **security** - ogólnie pojęte bezpieczeństwo, które może odnosić się do bezpieczeństwa sieci, systemów, danych, itp.
* **WebService** - usługa sieciowa mająca na celu przetworzenie otrzymanego żądania, którego format jest z góry określony. Najczęstszym przykładem usługi sieciowej jest system odpowiadający na predefiniowane zapytania przy użyciu protokołu HTTP w formacie XML.
* **Rest API** - podejcie do architektury systemów, w którym wymiana danych pomiędzy systemami odbywa się w sposób bezstanowy poprzez jednorodny interfejs.
* **network** - sieć, często używane w odniesieniu do sieci komputerowej czyli logicznie i/lub fizycznie połączonych urządzeń.
* **LDAP/AD** - protokół używany do operacji na usługach katalogowych opartych o zasoby takie jak: użytkownicy, aplikacje, urządzenia sieciowe i inne zasoby sieciowe. AD jest implementacją protokołu LDAP dla systemów Windows.
* **API** - zbiór ściśle określonych reguł, za pomocą których systemu komunikują się między sobą.
* **schema** - szerokorozumiany schemat czyli opis danej struktury, systemu czy standardu.
* **diagram** - graficzna reprezentacja danego rozwiązania
* **WebSocket** - protokół komunikacji pomiędzy dwuma kanałami przy użyciu jednego połączenia TCP.
* **batch processing** - przetwarzanie, w którym brana jest pod uwagę większa partia danych/zasobów.
* **online communication** - komunikacja internegowa
* **database** - system odpowiedzialny za przechowywanie danych w sposób z góry zdefiniowany. Pojęcie używane też w odniesieniu do samego zbioru danych.
* **P2P (Peer to Peer)** - komunikacja klient-klient, która odbywa się bezposrednio pomiędzy systemami zainteresowanymi bez użycia systemu trzeciego (serwer).
* **service bus** - szyna usług, system pośredniczący w komunikacji pomiędzy systemami pozwalający na łatwe dodawanie i usuwanie komponentów z całego ekosystemu.
* **design pattern** - wzorzec projektowy, znane rozwiązanie problemu, który często występuje i jest dobrze znany.
* **distributed system** - system rozproszony, system, w którym częsci składowe komunikują się między sobą za pomocą sieci komputerowej poprzez wymianę komunikatów.
* **functional/non-functional requirements** - wymagania fukcjonalne definiują system i jego komponenty, sposób komunikacji pomiędzy nimi. Wymagania niefukcjonalne definiują natomiast kryteria, przy użyciu których ocenić jakość działania systemu.
* **business requirements** - wymagania biznesowe, zbiór zasad działania systemu zdefiniowanych przez osoby definiujące wysokopoziomowe zasady działania systemu.
* **stateful/stateless** - stanowość odnosi się to przechowywania przez system stanu/histori zachowań klienta. W systemie bezstanowym historia zachowań nie ma znaczenia - każde kolejne żądanie jest traktowane jako całkowicie nowe zapytanie.
* **load balancer** - system odpowiedzialny za rozproszenie obciążenia i przekierowywanie żądań do systemów będących w stanie odpowiedzieć za dane zapytanie.
* **caching** - sposób zwiększenia szybkości dostępu do danych poprzez częściowe ich przeniesienie z wartwy trudno dostępnej do wartwy łatwo dostępnej.
* **parsing** - przetwarzanie ciągu symboli w zdefiniowany wcześniej sposób.
* **client-server** - architektóra systemów, w którym klient wysyła żądania do serwera, który odpowiedzialny jest za dostarczenie usług.
* **queue (MQ, RabbitMQ)** - kolejka czyli struktura danych, w której elementy są dodawane na końcu a pobierane z począktu.
* **communication channel** - szerokorozumiany kanał komunikacji
* **low-level design (LLD)** - architektura niskopoziomowa
* **high-level design (HLD)** - architektura wysokopoziomowa

## 2. Development ##
* **programming language** - język programowania czyli zbiór reguł opisujących w jaki sposób ciąg znaków jest interpretowany oraz jakie czynności reprezentuje. Przykładami języków programowania są: Java, JavaScript, Python, C++, PHP, Ruby.
* **programming framework** - zbiór rozwiązań programistycznych dla danej grupy problemów, które mogą zostać w łatwy sposów rozszerzone w celu dostarczenia danej fukcjonalności systemu. Przykładami frameworków są: Spring, .Net Core, Angular.js.
* **library** - zbiór niskopoziomowych rozwiązań programistycznych dla ściśle okreslonej grupy problemów.
* **Open Source** - wolne oprogramowanie czyli takie, które jest dostępne dla każdego bez żadnych opłat. Istnieją różne poziomy, które definiują w jaki sposów może one zostań użyte oraz przetworzone.
* **object-oriented programming (class, object)** - typ programowania, które opiera się na definiowaniu obieków oraz ich zachowań.
* **IDE** - system służące do tworzenia oprogramowania
* **source code** - kod źródłowy, pliki tekstowe definiujące system
* **SQL** - język programowanie stworzony do zarządzania danymi w relacyjnych bazach danych.
* **React Native** - framework stworzony przy użyciu języka JavaScript pozwalający na tworzenie natywnych aplikacji mobilnych dla platform Android i iOS.
* **HTML** - język znaczników pozwalający na opisanie struktury strony internetowej wraz nadaniem jej fragmentom znaczenia semantycznego.
* **CSS** - język służacy do opisu warstwy prezentacji strony internetowej.
* **VBA** - język programowania oparty na Visual Basicu (VB) zaimplementowany w aplikacjach pakietu Microsoft Office.
* **Full Stack** - pojęcie używane w odniesieniu do programisty tworzącego aplikacje przy użyciu technologi FE i BE. Umożliwia to dostarczenie pełnej funkcjonalności przez jedną osobę.
* **pair programming** - technika programowania, w której odbywa się ono w parach.
* **cross platform** - dostępny/działający na wielu platformach.
* **PL/SQL** - rozszerzenie języka SQL dla baz danych Oracle.
* **T-SQL** - rozszerzenie języka SQL dla baz danych Microsoft.
* **specification** - definicja systemu informatycznego, jego zachowań i sposobu działania.
* **algorithm** - algorytm, zestaw instrukcji służących do rozwiązania danego programu. Przykładam mogą być algorytmy sotrowania.
* **compiler** - program służący do automatycznego tłumaczenia kodu napisanego w jednym języku (języku źródłowym) na równoważny kod w innym języku (języku wynikowym).
* **development environment** - środowisko programistyczne
* **assembler** - program tłumaczący kod źródłowy na kod maszynowy.
* **domain** - domena

## 3. Code Management ##
* **version control system (VCS)** - system kontroli wersji służący do zarządzania kodem zródłowym. Przykładami systemów są: Git, SVN.
* **Git** - jeden z najpopularniejszych systemow kontroli wejsji oparty na rozproszonych repozytoriach kodu.
* **Bitbucket, GitHub** - serwisy hostingu internetowego wspierające projekty informatyczne oparte na systemie Git pozwalające na zdalne przechowywanie zasobów.
* **code branch** - ścieżka/gałęź definiująca konkretną wersję systemu
* **code merge** - proces łączenia dwóch wersji kodu w jedną.
* **feature cherry picking** - proces wyciągania konkretnej funkcjonalności systemu z jednej gałęzi i łączenie jej z inną gałęzią.
* **version (1.2.15, 1.3.0)** - definicja numeru wersji oprogramowania, w standardzie to wartość trzycyfrowa.
* **repository** - miejsce przechowywania kodu.
* **code review** - proces sprawdzania jakości kodu przez programistów. Odbywa się przeważnie wzajemnie przez członków zespołu.
* **commit** - jednostkowa zmiana w kodzie dodana do repozytorium kodu.
* **code review tool (Gerrit)** - narzędzia ułatwiające i przyspieszające proces sprawdzania jakości kodu.

## 4. Delivery ##
* **continuous integration (CI)** - proces automatycznego budowania oprogramowania rozpoczynający się od umieszczenia kodu we wspólnym repozytorium a kończący się na ostatecznej intergracji wraz z innymi zamianami.
* **continuous delivery (CD)** - rozszerzony process CI o automatyczne uruchamianie nowych zmian i dostarczanie ich na środowiska testowe.
* **failfast delivery** - podejśćie w dostarczaniu oprogramowania, w którym zmiany są wprowadzane dynamicznie biorąc pod uwagę ewentualne błędy. Zakłada się, że wprowadzane błędy są akceptowane ale powinny zostać szybko naprawione.
* **Jenkins** - narządzie służące do automatyzacji procesów związanych z budowaniem, testowanie i uruchamianiem systemów. 
* **pipeline** - sposób szeregowego przetwarzania danych lub informacji, składający się z etapów, w którym to dane wyjściowe danego etapu stają się danymi wejściowymi kolejnego.
* **virtualization** - w uproszczeniu stworznenie wirtualnej wersji czegość, która ma za zadanie dostarczań funkcjonalności faktycznego zasobu. Przykładem może być wirtualizacja jednego serwera poprzez podzielenie jego zasobów i udostępnienie ich jako 2 osobnych wirtualnych serwerow. Często wirtualizacja jest transparentna dla użytkownika końcowego.
* **container (Docker)** - przykład wirtualizacji, kontener jest jednostką oprogramowania, która zawiera daną aplikację oraz wszystkie wymagane prerekwizyty potrzebne do jej uruchomienia. Może on zostań dzięki temu szybko uruchomiony oraz jest niezależny od środowiska, na którym jest uruchamiany.
* **hosting** - udostępnianie zasobów serwera przez dostawcę usług internetowych.
* **VPC** - grupa zasobów tworzonych na żądanie w środowisku chmury wprowadzająca określony poziom izolacji od innch zasobów stworzonych dla innej organizacjai.
* **Kubernetes** - open-source'owy system do zarządzania kontenerami umożliwiający automatyzację procesu uruchamiania, skalowania oraz zarządzania aplikacjami.
* **DevOps** - zbiór praktyk łączących zespoły rozwoju oprogramowania (dev, development) oraz utrzymywania (ops, operations) w celu skrócenia czasu pełnego cyklu dostarczania oprogramowania. Kładzie nacisk na wpółpracę zespołów lub też przejmowanie niektórych obowiązków jednego z zespołów przez drugi w celu usprawnienia procesu.
* **orchestration** - automatyczna konfiguracja, koordynacja oraz zarządzanie systemami komputerowymi lub oprogramowaniem.
* **Ansible** - narzędzie służące to automatuyzacji tworzenia i zarządzania infrastruktury systemów IT.
* **release** - proces uruchamiania nowej wersji oprogramowania, używane też w kontekście nazwy konkretnej wersji.

## 5. Quality Assurance ##
* **bug** - błąd, który wystąpił w oprogramowaniu. Jest to zachowanie niezgodne z wymaganiami.
* **unit test** - test jednostkowy, test oprogramowania testujący mały fragment kodu odpowiedzialny za konkretną funkcjonalność, zwyczajowy tworzony przez programistów i uruchamiany automatycznie w procesie budowania oprogramowania.
* **integration test** - test integracyjny, testmający na celu sprawdzenie współdziałania komponentów systemu.
* **performance test** - test wydajnościowy, test sprawdzający zachowanie systemu przy danym obciążeniu. Przykładem może być test strony internetowej przy założeniu, że jest odwiedzana przez daną ilość klientów w tym samym momencie.
* **manual test** - test manualny, test wykonywany przez testera ręcznie bez użycia systemów automatyzujących proces.
* **acceptance test** - test akceptacyjny, test wykonywany w celu uzyskania akceptacji i zielonego swiatła dla procesu uruchomienia nowej wersji systemu na danym śwodowisku.
* **exploratory test** - test eksploracyjny, ogólny opis procesu jednoczesnego uczenia się, projektowania i wykonywania testów.
* **security test** - test bezpieczeństwa, test sprawdzający działanie systemu pod względem możliwych naruszeń bezpieczeństwa i możliwych luk, które umożliwyłyby potencjalne ataki.
* **automation test** - test automatyczne, test, kóry może być uruchamiany wielorazowo i nie wymaga ingerencji człowieka. Jego głównym założeniem jest jednorazowe stworzenie i wielokrotna możliwość uruchomienia.
* **E2E (end to end) test** - test mający na celu sprawdzenie zachowania aplikacji oraz danej funkcjonalności od początku do końca.
* **smoke test** - test mający na celu sprawdzenie głównych funkcjonalności systemu bez wykonywania dogłębnej analizy szczegółów.
* **behavioral test** - test sprawdzający zachowanie danej fukcjonalności aplikacji.
* **stress test** - test sprawdzający działanie systemu przy większym natężeniu użytkowania.
* **functional test** - test sprawdzajacy dzialanie systemu zgodne z opisanymi wymaganiami funkcjonalnymi.
* **component test** - test komponentu, w podejściu tym każda część systemu/komponent jest testowana z osobna.
* **mutation test** - testy mutacyjne, polegają na wrowadzaniu w systemie losowych błędów i uruchamianiu testów automatycznych w celu spradzenia, czy błędy te zostaną wykryte.
* **test tool** - narzędzie służące do testów
* **test environment (DEV, SIT, UAT)** - środowisko testowe
* **test standards** - szerokopojęte standardy testowania
* **test case** - specyfikacja danych wejściowych, warunków wykonania i oczekiwanch rezultatów, które definiują test wykonywany w konkretnym celu.
* **test scenario** - scenariusz testów czyli zbiór działań mających na celu sprawdzenie danej funkcjonalności
* **code coverage** - pokrycie testami
* **Selenium** - oprogramowanie służące do automatyzacji testów dla stron internetowych
* **ISTQB** - certyfikat dla testerów oprogramowania
* **reopen** - status dla zgłoszenia mowiący o tym, iż zostało ono po raz kolejny otwarte w związku z ponownym pojawieniem się niezgodności z założeniami systemu.
* **user story** - opis wymagań systemowych zdefiniowanych z punktu widzenie użytkownika końcowego.
* **Jira** - narzędzie służące do zarządzania projektami informatycznymi. Używany głównie do utrzymywania zadań oraz sprawdzania postępu prac.
* **Cucumber** - narzędzie do tworzenia testów automatycznych pisanych przy użyciu programowania behawioralnego.
* **Selenium** - narzędzie służące do automatyzacji testów dla aplikacji opartych na przegląrkach internetowcyh (strony internetowe).
* **regression test** - test mający na celu zapewnienie, że zmiany w oprogramowaniu nie wpłyneły niekorzystnie na istniejące wcześniej funkcjonalności.
* **release blocker** - błąd, który sprawia, że nowa wersja oprogramowania nie może zostać wdrożona w związku niewłaściwym zachowaniem systemu
* **lack of requirements** - brak wymagań
* **acceptance criteria** - kryteria akceptacyjne definiowane w celu określenia ram dla ktrych dana fukcjonalność jest uznawana za działającą zgodnie z wymaganiami.
* **Definition of Done (DoD)** - w metodologi Agile, lista kryteriów, które muszą być spełnione aby dane zadanie (story) mogło zostać uznane za ukończone.
* **Definition of Ready (DoR)** -  w metodologi Agile, lista kryteriów, które muszą być spełnione aby dane zadanie (story) mogło zostać uznane za gotowe do wzięcia pod uwagę podczas planowania kolejnej iteracji.
* **priorities** - priorytety dla zadań

## 6. Maintenance ##
* **support** - grupa ludzi lub systemów odpowiedzialna za wsparcie systemu w trakcie jego działania.
* **1st/2nd/3rd Line Support** - poziomy wsparcia dla systemw informatycznych.
* **hotfix** - zmiana w kodzie systemu zawierająca poprawkę dla danego problemu.
* **backlog** - lista zadań do wykonania. Może składać sięz nowych funkcjonalności, poprawek, ulepszeń. 
* **code revert** - odwrócenie zmian w kodzie, które uprzednio zostały dodane.
* **life cycle politics** - polityki związane z cyklem życia zmian oraz zgłoszonych błędów.
* **customer service** - obsługa klientów systemu.
* **migration** - proces przeniesienia/transformacji z jednego systemu na inny.
* **disaster recovery** - proces zabezpieczenia systemu przed efektami negatywnych zdarzeń. Ma na celu przywrócenie funkcjonowania systemu po zaprzestaniu działania.
* **ticket** - zgłoszenie dotyczące poprawy funcjonalności systemu lub też naprawy danego błędu.
* **troubleshooting** - rozwiązywanie problemów
* **RFC (request for change)** - żądanie zmian w systemie
* **change management** - zarządzanie zmianami w systemie
* **documentation** - dokumentacja systemu
* **backup** - kopia zapasowa. Dotyczy głównie danych, na których działą system.
* **upgrade** - aktualizacja systemu do nowszej wersji.
* **user feedback** - informacja zwrotna o działąniu systemu pochądząca od użytkowników. Używana jest jako podstawa do analizy działania system i wdrożeń zmian.
* **monitoring** - monitorowanie/sprawdzanie działanie aplikacji
* **patch** - poprawka
* **metrics** - mierzalny zbiór danych dotyczący jakości działania systemu
