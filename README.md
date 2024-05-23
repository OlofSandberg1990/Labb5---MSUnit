De delar jag har valt att skapa tester på är:

1, Överföringar mellan konton
* Försök att överföra negativt belopp
Ser till att man inte kan föra över ett negativt belopp när man för över till annat konto.
  
* Försök att överföra mer pengar än vad som finns tillgängligt
Det ska inte gå att föra över mer pengar än vad som finns tillgängligt på kontot

* Kontrollera att valutakonvertering fungerar korrekt
Ser till att valutakonverteringen fungerar som den ska när man för över pengar
från ett konto till ett annat. 

* Kontrollera att man inte kan överföra pengar till samma konto
Det ska inte gå att föra över från t.ex källkonto till samma källkonto.

2, Skapande av konto
* Försök att skapa ett konto med negativt belopp
När man skapar ett konto ska det inte gå att tilldela det ett negativt belopp

* Försök att skapa ett konto med valuta som inte är SEK eller USD
Det ska inte gå att skapa ett konto med annan valuta än SEK eller USD då programmet endast stödjer dessa valutor
  
* Kontrollera att ett konto skapas korrekt
När man skapar ett konto måste det skapas med korrekt värden
  
* Kontrollera att konto skapas med default name om inget namn anges
Skapar man ett konto utan namn ska default name anges

3, Skapande av användare
* Kontrollera att admin skapas vid initialisering av CustomerList
Kontrollera att en Admin skapas vid programstart
  
* Kontrollerar att CustomerList inte är tom efter skapande
  Ser till att kundlistan som startas vid uppstart av programmet faktiskt innehåller kunder och inte är tom.
  
* Kontrollerar att rätt antal användare skapas vid initialisering.
  Kontroll för att se till att korrekt (i detta fallet 6st) antal användare skapas.

  
