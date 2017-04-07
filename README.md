# 38 Use Case Diagram & Scanner Class

## Use Case Diagram



## Scanner Class
Når vi skal have input fra konsollen har vi indtil nu brugt ````System.console().readLine();````   
Input er her kun strings, men disse kan konverteres med:
````Java
  String text = "12.34";
  double value = Double.parseDouble(text);

  String number = "10";
  int result = Integer.parseInt(number);
````   
### Scanner
Scanner klassen er smartere, den har flere metoder:

* [Java Docs](https://docs.oracle.com/javase/7/docs/api/java/util/Scanner.html)

#### Øvelse

[Calculator](https://github.com/dat17v1/38_UCD_Scanner/blob/master/Exercises/Calculator.md)