# Lerninhalte dieser Übung 

Ziel dieser Übung ist es, den Umgang mit den Scanner zu üben und so erste Benutzerinteraktionen zu ermöglichen. 
Zum Scanner gibt es ein gutes [Tutorial auf W3Schools](https://www.w3schools.com/java/java_user_input.asp) und auch die [Dokumentation der Klasse](https://docs.oracle.com/en/java/javase/16/docs/api/java.base/java/util/Scanner.html) ist ein gutes Nachschlagewerk.

Methoden die du wahrscheinlich brauchen wirst: 
* next() - liest den nächsten String ein
* nextLine() - liest den nächsten String bis zur Newline ein 
* nextBoolean() - liest den nächsten String als Boolschen Wert ein, wirft einen Fehler falls der übrige String in der Eingabe nicht als Boolean gelesen werden kann.
* nextInt() - liest den nächsten String als Integer ein, wirft einen Fehler falls der übrige String in der Eingabe nicht als Integer gelesen werden kann.
* nextDouble() - liest den nächsten String als Double ein, wirft einen Fehler falls der übrige String in der Eingabe nicht als Double gelesen werden kann.

Da es keine nextDate() Methode gibt, musst du das Datum als String einlesen (mit `next()`) und danach mit dem SimpleDateFormat verwenden. 
Du kannst dir dazu [dieses Tutorial](https://howtodoinjava.com/java/date-time/java-parse-string-to-date/) ansehen, wie man einfach aus einem String ein Datum in einem gegebenen Format ablesen kann.
