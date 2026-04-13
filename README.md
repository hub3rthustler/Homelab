# SOC Homelab

Projekt homelabu został stworzony jako praktyczne środowisko do rozwijania umiejętności z zakresu cyberbezpieczeństwa, ze szczególnym naciskiem na analizę incydentów, monitoring zdarzeń bezpieczeństwa oraz podstawy detekcji i działań ofensywnych.

## Cel projektu

Celem projektu jest budowa i rozwój własnego środowiska laboratoryjnego typu SOC, w którym realizowane są kontrolowane symulacje ataków, analiza logów i alertów oraz dokumentowanie incydentów z perspektywy analityka bezpieczeństwa.

Projekt pozwala rozwijać praktyczne kompetencje w obszarach takich jak:
- analiza logów i alertów,
- obsługa platformy Wazuh,
- praca z SIEM/XDR,
- mapowanie aktywności do MITRE ATT&CK,
- rozumienie etapów ataku w oparciu o Cyber Kill Chain,
- tworzenie dokumentacji technicznej i raportów po incydencie.

## Architektura środowiska

Środowisko składa się z centralnego serwera **Wazuh** uruchomionego na **Ubuntu 24.04 LTS** oraz monitorowanych hostów:

- **Ubuntu 24.04**
- **Windows Server 2025** pełniący rolę kontrolera domeny
- **Windows 11**

Do realizacji scenariuszy ofensywnych i symulacji ataków wykorzystywane są:
- **Kali Linux/BlackArch**
- **Atomic Red Team**
- **AI**

## Zakres prac

W ramach projektu realizowane są scenariusze testowe obejmujące:
- wykonanie kontrolowanych działań ofensywnych,
- rejestrowanie i analizę zdarzeń po stronie hostów,
- identyfikację artefaktów pozostawionych w systemie,
- analizę alertów generowanych przez Wazuh,
- ocenę skuteczności detekcji,
- dokumentowanie przebiegu incydentu i rekomendacji usprawnień.

## Dokumentacja scenariuszy

Każdy scenariusz zawiera:
- cel ataku,
- przebieg techniczny,
- artefakty pozostawione w systemie,
- alerty i logi wykryte przez Wazuh,
- analizę z perspektywy obrońcy,
- wnioski oraz propozycje usprawnień detekcji.

## Rozwijane kompetencje

Projekt rozwija praktyczne umiejętności istotne w pracy na stanowiskach takich jak:
- SOC Analyst
- Cybersecurity Analyst
- Junior Security Engineer

Najważniejsze obszary kompetencyjne:
- monitoring i analiza zdarzeń bezpieczeństwa,
- triage alertów,
- analiza logów systemowych i bezpieczeństwa,
- podstawy threat detection,
- rozumienie technik atakujących,
- dokumentowanie incydentów i wniosków technicznych.

## Status

**Project in progress**  
Środowisko jest stale rozwijane o kolejne scenariusze ataków, reguły detekcji i elementy dokumentacji technicznej.
