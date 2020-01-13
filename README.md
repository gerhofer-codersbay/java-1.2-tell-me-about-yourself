# Java

## Logische und Zuweisungsoperatoren

### Aufgabe 2.1 - Erzähl mir etwas über dich!

Schreibe ein Programm, dass ähnlich zu dem Programm aus Aufgabe 1 einige Daten vom Benutzer liest. Stelle dazu auf der Konsole folgende Fragen und lies die jeweiligen Antworten im korrekten Datentyp ein, speichere sie in einer Variable und gib sie nach Beantwortung aller Fragen wieder aus. 

* Wie ist dein Vorname?
* Wie ist dein Nachname?
* Wie alt bist du?
* Bist du verheiratet? (true/false)
* Wie groß bist du in Metern? 

Um von der Konsole Benuzter Eingaben zu lesen verwendest du am besten den [Scanner](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Scanner.html): 
```
Scanner scanner = new Scanner(System.in);
String text = scanner.nextLine(); // returniert den eingegebenen Text als String, mit Enter wird der Text gesendet
```

Bonus: Lass Vor- und Nachnamen in einer Zeile mit einem Leerzeichen getrennt eingeben aber speichere sie getrennt in zwei Variablen ab.

Bonus 2: Frag nach dem Geburtsdatum. Da der Scanner keine `nextDate()` Funktion hast wirst du etwas brauchen um ein Datum aus dem String zu parsen. Sieh dir dafür die [offizielle SimpleDateFormat Dokumentation](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/text/SimpleDateFormat.html) an.

------------------------------------------------------------------------

# Java 

## Logical and assignment operators 

### Exercise 2.1 - Tell me about yourself 

Write a program similar to our first exercise to read data via console input from the user. Print the following questions and save the answers in variables of the correct datatype. Print all of the variables after all values were read. 

* What is your first name?
* What is your last name?
* How old are you?
* Are you married? (true/false)
* What's your size in meters? 

To read user input from the console you probably want to use the [Scanner class](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/util/Scanner.html): 
```
Scanner scanner = new Scanner(System.in);
String text = scanner.nextLine(); // returns the entered text as a String, text is submitted when a new line is entered
```

Bonus: Provide first and last name in one line but save them in two seperate variables.

Bonus 2: Ask for the users date of birth. As the scanner does not provide a `nextDate()` function you will have to parse a date from the String. Take a look at the [official documentation of SimpleDateFormat](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/text/SimpleDateFormat.html) an.
