# Elektroniczny kelner (Kerfuś)

## Spis treści

(#elektroniczny-kelner-kerfuś)

- [Elektroniczny kelner (Kerfuś)](#elektroniczny-kelner-kerfuś)
  - [Spis treści](#spis-treści)
  - [Wymagania systemu](#wymagania-systemu)
      - [Co robi:](#co-robi)
      - [Jak:](#jak)
      - [Gdzie:](#gdzie)
      - [Kto:](#kto)
      - [Ograniczenia/wymogi:](#ograniczeniawymogi)
  - [Słownik pojęć](#słownik-pojęć)

## Wymagania systemu

#### Co robi:

- Robot ma za zadanie **dostarczać jedzenie/produkty** w **zamkniętych pomieszczeniach** (np. w Carrefourze, restauracji). Robot **przyjmuję zamówienie poprzez aplikację mobilną/tablet**, a następnie **samodzielnie wybiera się do wybranego miejsca**, aby przekazać towar. Robot jest w stanie **wykryć**, czy **paczka została odebrana**, a następnie wraca do punktu startowego.
- W przypadku **wielu zamówień**, robot **dobiera optymalną ściężkę dla środowiska** w którym się znajduję.
- Robot powinien być w stanie **dowieźć rzeczy, bez żadnego wypadku po drodze**, tj. powinien **omijać napotkane przeszkody**, **stabilizować swój ruch** oraz wykrywać, czy ktoś go **zatrzymał** (w przypadku takiej sytuacji, włączany jest alarm).
- Elektroniczny kelner jest w stanie wykryć, czy zamówienie zostało odebrane. Jeśli tak, robot kontynuuje swoją pracę, jak nie, **głośno krzyczy**.
- W przypadku problemów z dostarczeniem towaru, robot wykorzystuje alarmy dzwiękowe, by powiadomić o tym pracowników.

#### Jak:

- Robot oczywiście **jeździ na kółkach**, dlatego wykorzystuje **kilka silników DC**, aby się poruszać.
- Wykorzystuje **czujniki podczerwieni**, aby wykrywać napotykane przeszkody i zapewnić bezpieczne dostarczenie towaru.
- Robot wykorzystuje **system nawigacji** (np. mapowanie terenu za pomocą czujników podczerwieni etc.), który pozwala mu poruszać się po lokalu i dostarczać zamówienia.
- Wykorzystuje **żyroskop**, aby stabilizować swój ruch.
- **Sensory dotyku** odpowiadają za wykrywanie niechcianego dotyku (np. usiłowanie zatrzymania robota, dotykanie po uszkach)
- **Głośniki** odpowiadają za wydawanie dzwięków alarmowych, w przypadku niepożądanego dotyku.
- **Czujnik siły nacisku** wykrywa czy produkt został zabrany przez klienta.
- Aby zapewnić długie działanie robot wraca raz na jakiś czas do punktu startowego, aby naładować baterię.

#### Gdzie:

- Robot może być wykorzystywany tylko w zamkniętych środowiskach.
- Robot może być wykorzystywany w wielu lokalach gastronomicznych, a także w sklepach, instytucjach publicznych, magazynach.
- Generalnie, wszędzie, gdzie trzeba przenieść coś z punktu A do punktu B, Kerfuś się tu sprawdzi.

#### Kto:

- Robot jest wykorzystywany przez wszystkich uczestników procesu. Klienci zamawiają jedzenie, które robot ma im dostarczyć, pracownicy wydają komendy robotowi, aby ustalić odpowiednie miejsce dostarczenia towaru, a także przekazują mu towary, które mają zostać dostarczone.
- Serwisanci mogą naprawiać roboty, gdy są one uszkodzone.

#### Ograniczenia/wymogi:

- Elektroniczny kelner musi być zgodny z wieloma wymaganiami bezpieczeństwa, w tym normami dotyczącymi bezpieczeństwa elektrycznego oraz ochrony danych klientów.
- W zależności od środowiska, w którym się znajduję, mogą być nałożone dodatkowe ograniczenia prawne jego działania, jak np. w restauracjach powinien być on często czyszczony, w instytucjach publicznych powinien w sposób anonimowy przekazywać wrażliwe informacje i być zabezpieczony przed ewentualną kradzieżą (np. skrzynka z kodem dostępu), etc.
- Poza tym, robot jest silnie ograniczony przez fizyczną strukturę środowiska, w którym się znajduję, np. drzwi, schody etc.
- Powinien być regularnie serwisowany, aby spełniać odpowiednie wymagania bezpieczeństwa.

## Słownik pojęć

- Kerfuś - wymienna nazwa na elektronicznego kelnera
