# IT topics #

## 1. Architecture ##
* **relations (one-to-many, many-to-many)** - poprzez relację rozumiemy zalezność pomiedzy komponentami, zasobami, itp. Jako przykładu możemy użyć relacji ojciec-syn. Jest to typowa relacja jeden-do-wielu (one-to-many). Jeden ojciec może posiadać wielu synów, ale konkretny syn ma tylko jednego ojca.
* **backend system (BE)** - to system odpowiedzialny za przetwarzanie danych otrzymanych lub wykonywanie zadań przekazanych przez system FE. W odpowiedzi na rządanie może on udzielić odpowiedzi i przekazać rezultaty do systemu FE.
* **frontend system (FE)** - to system zbierający rządania klienta i przekazujący zadania do systemu BE.
* **cloud system (AWS, Azure)** - system odpowiedzialny za dynamiczne tworzenie zasobów infrastruktury taki jak serwery, połączenia sieciowe, bazy danych itp. Różni się to od podejscia, w którym wszystkie zasoby są predefiniowane a każde nowe wymagania są związane z ingerencją zespołu odpowiedzialnego za infrastrukturę.
* **microservice** - system odpowiedzialny za konkretną funkcjonalność. Dostarcza rozwiązań dla jasno określonej domeny.
* **monolith system/application** - system odpowiedzilny za realicję złożonych zadań obejmujących wiele zadań, które niekoniecznie są związane z tą samą domeną.
* **No-SQL database** - baza danych, w której dane są modelowane w sposób inny niż za pomocą relacji znanych relacyjnych baz danych.
* **relational database** - baza daych, w której podstawą modelowania danych są relacje.
* **proxy** - pośrednik w systemach informatycznych. Odpowiedzialny za wykonywanie działań w imieniu osoby wysyłającej rządanie.
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
* programming language (Java, JavaScript, Python, C++, PHP, Ruby)
* programming framework (Spring, .Net Core, Angular.js)
* library
* Open Source
* object-oriented programming (class, object)
* IDE
* source code
* SQL
* React Native
* HTML, CSS
* VBA
* Full Stack
* pair programming
* cross platform
* PL/SQL
* T-SQL
* specification (technical standard)
* algorithm (sorting algorithm)
* compiler
* development environment
* Assembler
* domain

## 3. Code Management ##
* version control system (VCS)
* Git
* Bitbucket, GitHub
* code branch
* code merge
* feature cherry picking
* version (1.2.15, 1.3.0)
* repository
* code review
* commit
* code review tool (Gerrit)

## 4. Delivery ##
* cloud
* cloud provider (AWS, Azure, Google Cloud)
* data center
* continuous integration (CI)
* continuous delivery (CD)
* failfast delivery
* Jenkins
* pipeline
* virtualization
* container (Docker)
* hosting
* VPC
* Kubernetes
* DevOps
* orchestration
* Ansible
* release

## 5. Quality Assurance ##
* bug
* unit test
* integration test
* performance test
* regression test
* manual test
* acceptance test
* exploratory test
* security test
* automation test
* E2E (end to end) test
* smoke test
* behavioral test
* stress test
* functional test
* mutation test
* component test
* test tool
* test environment (DEV, SIT, UAT)
* test standards
* test case
* test scenario
* code coverage
* Selenium
* ISTQB
* reopen
* user story
* Jira
* Cucumber
* Selenium
* regression
* release blocker
* lack of requirements
* acceptance criteria
* specification
* Definition of Done (DoD)
* Definition of Ready (DoR)
* priorities

## 6. Maintenance ##
* support
* 1st/2nd/3rd Line Support
* hotfix
* backlog
* code revert
* life cycle politics
* customer service
* migration
* disaster recovery
* ticket
* troubleshooting
* RFC (request for change)
* change management
* documentation
* backup
* upgrade
* user feedback
* monitoring
* patch
* metrics
