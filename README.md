# MiASI - Modelowanie i analiza systemów informatycznych

Ćwiczenia informatyczne z przedmiotu Modelowanie i analiza systemów informatycznych na Uniwersytecie Łódzkim.<br />
Więcej informacji o przedmiocie: [karta przedmiotu](https://usosweb.uni.lodz.pl/kontroler.php?_action=katalog2/przedmioty/pokazPrzedmiot&prz_kod=1100-MA0UII).

## Projekt 1 - Use Case Diagram 
Celem ćwiczenia jest stworzenie systemu **CMS dla platformy elearningowej**. Ma on umożliwiać publikacje materiałów szkoleniowych w formie elektronicznej. Opracowanie materiałów szkoleniowych wymaga przygotowaniatreści merytorycznej szkolenia, elementów multimedialnych oraz testów sprawdzających stopień przyswojenia wiedzy. Elementy te są organizowane w ramach rozdziałów składających się na szkolenie. Podsystem CMS oferuje ponadto zarządzanie użytkownikami, obejmujące takie czynności, jak zakładanie kont i przydzielanie uprawnień do poszczególnych kursów.

[Link do projektu](./P-1_DPU_30_10/DPU_2.pdf)

##  Projekt 2 - Class Diagram
Celem projektu jest stworzenie diagramu klas dla **systemu aukcyjnego**. Przyjąć należy, że każdy towar należy bezpośrednio tylko do jednej kategorii. Jednak ponieważ kategoria może zawierać pod – kategorie więc jeden towar może pośrednio należeć do wielu kategorii. 

[Link do projektu](./P-2_ClassDiagram_13_11/)

## Projekt 3 - Activity Diagram
Celem zadania jest sporządzenie diagramu czynności dotyczący **zakupu towaru w sklepie internetowym**. Należy pamiętać o uwzględnieniu następujących czynności: kompletowanie towaru, wystawienie faktury,wysyłka, zamówienie, potwierdzenie płatności itd.

[Link do projektu](./P-3_ActiveDiagram_27_11/)

## Projekt 4 - State Machine Diagram
Celem projektu jest utworzenie diagramu maszyny stanowej dla informatycznego **systemu serwisowego** w firmie komputerowej. Należy uwzględnić przyjęcie reklamacji, sposób rozliczenia reklamacji, naprawy sprzętu. Należy pamiętać, że czas naprawy może się wydłużyć w sytuacji gdy firma oczekuje na brakujące części. Całość  prac powinna być monitorowana na bieżąco. Należy także pamiętać że w firmie zatrudniamy kilku pracowników, i naprawa sprzętu może być przydzielona jednemu lub kilku pracownikom. Każdy z nich raportuje wprowadzane naprawy.  Reszta założeń po własnym przemyśleniu tematu.

[Link do projektu](./P-4_StateMachine_11._12/)

## Projekt 5 - Sequence Diagram
Celem projektu jest przygotowaie diagramów sekwencji dla **Rejestracji sprzedającego na aukcji internetowej** oraz **Przystąpienia kupującego do licytacji**. Uwzględnić przesłanie przydzielonego kodu sprzedaży mailem. Pamiętać o przesyłanych komunikatach stereotypowych «create».

[Link do projektu](./P-5_SequenceDiagram_08.01/)

## Projekt 6 - Interaction Overview Diagram
Celem projektu jest utworzenie diagramu dla systemu przeprowadzania **seminariów online**. Student po otrzymaniu powiadomienia o poprawkach może przejść do redagowania pracy. Analogicznie do przypadku redagowania przez prowadzącego tworzona jest lokalna kopia pracy ze zintegrowanymi poprawkami. Na ich podstawie pobierany jest obiekt Zmiana. Następnie studentowi wyświetlana jest lista poprawek. Może wybrać dowolną z nich następnie zapoznać się ze zmianami i dodać dowolną ilość własnych sugestii. Po zatwierdzeniu wszystkie informacje związane z propozycjami są dodawane do poprawki w ramach obiektu Zmiana. Następnie możliwe jest ponowne wybranie kolejnej poprawki do redagowania, ilość sugestii oraz poprawek jest dowolna (loop).Po zatwierdzeniu zmian wywoływane jest ich rejestrowanie a następnie powiadomienie o zmianach przez email, tak jak miało miejsce w przypadku promotora.

[Link do projektu](./P-6%20InteractionDiagram_29.01/)