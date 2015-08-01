# Todo:
- NUnit [Category] Group
- Warum NUnit?
- Die anderen (neuen) Services (BrowserStack etc)
    - US vs EU Server

# Brainstorming
- Fälle definieren mit business
- Schätzung der Fälle
- Aufwandschätzung wie lange wird im moment getestet
- Wie viel aufwand ist die entwicklung der test?
- Outsourcing  der entwicklung?
- 10 fälle selber programmieren
- http://lefthandedgoat.github.io/canopy/
- saucelabs vs internal

# Deliverables
- Testfallspezitifkation inkl. Priorisierung
- Evaluation von Testframeworks
- Architekturbeschreibung der Testinfrastruktur
- Aufsetzen der Testinfrastruktur
- Implementierte Testfälle
- Testfallintegration in den bestehenden Application Lifecycle
- Tests sollen auf verschiedenen Browsern ausgeführt werden.

# Dokumentaufbau
- Anforderungsmanagement
- Architektur
- Implementation


# local vs saucelabs vs crossbrowsertesting
- local: Schlecht da Browser gepflegt werden müssen
- crossbrowsertesting
    - Schlechtes UI
    - Keine Controll-Übernahme bei Tests.
- saucelabs
    - Besseres UI als CBT.
    - Controll-Übernahme bei Tests.
    - Schneller!
# Bamboo
- Automated vs on request.
    - Automated schlecht da man für die Minuten zahlt.
    - Nicht jeder Deploy erfordert immer das Tests ausgeführt werden.
    - Wenn Tests immmer durchgeführt werden beim Deploy, weiss man erst ob es korrekt deployed wurde wenn alle Tests gelaufen sind. Dass kann aber bis zu 2h laufen und dauert zu lange.
- nunit.exe
    - Ist die GUI Exe und wurde durch die Command Line Exe ersetzt.
    - Startet bei default mit .NET Framework 3.5.
        - ch01s238.hotelplan.net -> D:\NUnit\bin -> nunit.exe.config -> configuration.startup -> <supportedRuntime version="v4.0.30319" />
