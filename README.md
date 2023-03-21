# Einarbeitung

## Java

📥 https://adoptium.net

📥 https://www.eclipse.org/downloads/packages

## git

📥 https://git-scm.com/downloads

📺 [Git und GitHub Tutorial](https://www.youtube.com/watch?v=9IINVQ5wx0c)

## Web

📺 [JavaScript Tutorial](https://www.youtube.com/watch?v=hrDEjR5NQoY)

📺 [HTML Tutorial](https://www.youtube.com/watch?v=-ogPn2b0n-E)

## Angular

📥 https://code.visualstudio.com/Download

📺 [TypeScript und Angular Tutorial](https://www.youtube.com/watch?v=CdvoH90fcaU)

📜 https://angular.io/tutorial

## Maven

📺 [Apache Maven installieren Windows](https://www.youtube.com/watch?v=nURYX9jASTw)

Die Tour of Heroes endet mit einem simulierten JavaScript-Backend.
Dieses habe ich nach Java mit Spring Boot übersetzt.
Das Java-Backend kann man über Maven starten:

```
c:\Users\fred\git\heroes-backend> mvn spring-boot:run
```

Um das Java-Backend auch zu nutzen, muss man im Frontend die Variable `heroesUrl` wie folgt ändern:

```ts
private heroesUrl = 'http://localhost:8080/api/heroes';
//                   ^^^^^^^^^^^^^^^^^^^^^^
```

📺 [Apache Maven Tutorial](https://www.youtube.com/watch?v=ExKq23bNABk)

## Spring Boot

📺 [Spring Boot Tutorial: Web, Datenbank, Dependency Injection](https://www.youtube.com/watch?v=92YpXWAjf8o)

Zwischendurch könnte man mal das `heroes-backend` studieren...

📺 [Dependency Inversion und Dependency Injection](https://www.youtube.com/watch?v=mIRa94u8e9g)

📺 [Dependency Injection selbst gebaut](https://www.youtube.com/watch?v=f_dM81I-s64)
