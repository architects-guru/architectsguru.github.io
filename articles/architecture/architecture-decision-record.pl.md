---
layout: default
title: Dokumentowanie decyzji architektonicznych (ADR-y)
permalink: /blog/architektura/dokumentowanie-decyzji-architektonicznych-adr
tags: 
- ADR 
- achitecture
---

# Dokumentowanie decyzji architektonicznych (ADR-y)

Jako architekci bardzo często musimy podjąć jakąś decyzję: jaki język programowania wybrać? Na jaką platformę cloud się zdecydować? Jak rozwiązać komunikację między serwisami? Czy użyć mikroserwisów? Często za podjętą decyzją stoją bardzo specyficzne okoliczności. Może się zdarzyć, że celowo na jakimś etapie odrzucamy jakąś np. technologię. Warto te decyzje udokumentować, aby został po nich jakiś ślad, oraz żeby zademostrować ewolucję rozwiązań. Szczególnie, że podczas pracy w metodologii Agile, nie wszystkie decyzje architektoniczne będą podejmowane na starcie projektu.

Z pomocą przychodzą dokumenty ADR (ang. *Architecture Decision Record*).


### Czym pownien być Architecture Decision Record (ADR)?
ADR powinien być zwięzyłym dokumentem opisującym zaproponowaną decyzję, jaki problem rozwiązuje oraz jakie są jej konsekwencje. 
Dokument powinien zatemt zawierać :

- Numer porządkowy (ADR-1, ADR-2, ...) - ułatwia identyfikację i referencję ADR-ów w innych dokumentach
- Status - Zaproponowany|Zatwierdzony|Odrzucony|Przestarzały
- Data
- Kontekst - okoliczności podjęcia decyzji oraz opis problemu
- Decyzja -  zaproponowane rozwiązanie problemu
- Osoby biorące udział w podjęciu decyzji