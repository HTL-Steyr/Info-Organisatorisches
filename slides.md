# HTL Steyr
<span>(https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.htl-steyr.ac.at%2Findex.php%2Fschule%2Fkontakt&psig=AOvVaw1dzYSeJXklboEXDU88aZA6&ust=1671121006673000&source=images&cd=vfe&ved=0CA0QjRxqFwoTCKih-oLB-fsCFQAAAAAdAAAAABAE):</span><!-- .element: class="decent x-small"-->
--

## Webuntis
* Innerhalb der ersten Schulwoche werden die Anmeldedaten für das elektronische Klassenbuch übergeben
* Mit Benutzername & Passwort bei **www.webuntis.com** einloggen
  * Einsicht in Stundenplan, Fehlzeiten, Hausaufgaben, Prüfungstermine und wichtige Informationen der Schulleitung
---

## Webmail

Die HTL Steyr hat ein eigenes System für die Kommunikation per Mail. Für die Anmeldung sind die Daten, welche man in der ersten Schulwoche bekommt erforderlich. Zum Empfangen von E-Mails auf die HTL Steyr Adresse, muss folgende Adresse verwendet werden: **benutzername@htl-steyr.ac.at**.
Mit dem Webmail der HTL Steyr kann intern mit anderen Schülern und Lehrern kommuniziert werden, ebenso kann aber auch extern kommuniziert werden, wenn die E-Mail Adresse des Empfängers bekannt ist.

---

## Webseite der HTL Steyr

Die Webseite der HTL Steyr ist über den Link: **www.htl-steyr.ac.at** abrufbar.
In der Navigationsleiste kann man verschiedene Bereiche, wie zum Beispiel **Schule** auswählen, wo man Allgemeines zur Schule findet. Ebenso gibt es aber auch die Fachrichtungen in der Navigationsleiste, wo man genauere Informationen zur genaueren Fachrichtung findet.

Auf der Startseite hat man seitlich im Menü verschiedenste Informationen, welche man sich ansehen kann, wie zum Beispiel Voraussetzungen für die HTL Steyr, Kontaktdaten zu den einzelnen Lehrkräften, des Sekretariats und der Schulleitung.

--

## Lists

---

## Unordered Lists

* a
* b
  * 1
  * 2
    * I
* c

---

## Ordered Lists

automatic numbering

1. a
1. b
    1. 1
    1. 2
1. c

---

## Ordered Lists

custom numbering

1. a  
2. b  
    2.1. 1  
    2.2. 2  
3. c

---

## Definition Lists

(actually: line breaks in long lines in lists...)

* First Term  
This is the definition of the first term.
* Second Term  
This is one definition of the second term.  
This is another definition of the second term.

---

## Font Awesome

*  Itym One<!-- .element: class="mdfa fa-info-circle"--> (this is a feature test in a very long item)
*  Itym Two<!-- .element: class="mdfa fa-question-circle"-->
*  Itym Three<!-- .element: class="mdfa fa-exclamation-circle"-->
*  Itym 4<!-- .element: class="mdfa fa-exclamation-triangle"-->  
with forced line break!

--

## Fragments

---

## Dont reveal all at once!

- Item 1 <!-- .element: class="fragment" data-fragment-index="2" -->
- Item 2 <!-- .element: class="fragment" data-fragment-index="1" -->
- Item 3 <!-- .element: class="fragment" data-fragment-index="3" -->

---

## Fancy!

- Highlight Red <!-- .element: class="fragment highlight-red" data-fragment-index="2" -->
- Fade In Then Out <!-- .element: class="fragment fade-in-then-out" data-fragment-index="1" -->
- Slide up <!-- .element: class="fragment fade-up" data-fragment-index="3" -->
- Appear and step aside  <!-- .element: class="fragment fade-in-then-semi-out" data-fragment-index="4" -->

---

## Distinguished

- Item 1 <!-- .element: class="fragment semi-fade-out" data-fragment-index="1" -->
- Item 2 <!-- .element: class="fragment semi-fade-out" data-fragment-index="2" -->
- Item 3 <!-- .element: class="fragment semi-fade-out" data-fragment-index="3" -->
- Item 4 <!-- .element: class="fragment semi-fade-out" data-fragment-index="4" -->
- Item 5

---

## FAQ (Example)

*  Question One?<!-- .element: class="fragment mdfa fa-question-circle"-->
*  Answer One!<!-- .element: class="fragment mdfa fa-exclamation-circle"-->
*  Question Two?<!-- .element: class="fragment mdfa fa-question-circle"-->
*  Answer Two!<!-- .element: class="fragment mdfa fa-exclamation-circle"-->
*  Question Three?<!-- .element: class="fragment mdfa fa-question-circle"-->
*  Answer Three!<!-- .element: class="fragment mdfa fa-exclamation-circle"-->

--

## Syntax highlighting   

---

## Java 

```java [1-6|3-5]
public class TheFirst extends Object
{
  
public static void main(String[] args)
  
{
  
}
}
```

---

## JavaScript

```js [1-2|3|4]
    let a = 1;
    let b = 2;
    let c = x => 1 + 2 + x;
    c(3);
```

---

## Callouts 

<!--https://fsymbols.com/signs/bullet-point/-->
```java
String switchExpressionPreview13(Direction way) {
    return switch (way) {                         ➊
        case N -> "Up";                           ➋
        case S -> { yield "Down"; }               ➌
        case E, W -> "Somewhere left or right";
        // default -> "Foo"                       ➍
    };
}
```

- ➊ `switch` can be used as expression
- ➋ `->` instead of `:` → no `break;` necessary!
- ➌ Lambdas can be used to. For _expressions_ they must `yield` a value [version]#13#
- ➍ `default` can be ommitted if a) no expression or b) `enum` with every value handled

---

## Callouts  (Alternative)

<!--https://fsymbols.com/signs/bullet-point/-->
```java
String switchExpressionPreview13(Direction way) {
    return switch (way) {                         ①
        case N -> "Up";                           ②
        case S -> { yield "Down"; }               ③
        case E, W -> "Somewhere left or right";
        // default -> "Foo"                       ④
    };
}
```
- ① <!-- .element: class="co"-->`switch` can be used as expression 
- ② <!-- .element: class="co"-->`->` instead of `:` → no `break;` necessary!
- ③ <!-- .element: class="co"-->Lambdas can be used to. For _expressions_ they must `yield` a value [version]#13#
- ④ <!-- .element: class="co"-->`default` can be ommitted if a) no expression or b) `enum` with every value handled

---

#### Try-with-resources now support „effectively final“ variables

```java
var inputStream = new FileInputStream(".gitignore");
try (inputStream) { … }
```

#### Private methods in Interfaces<!-- .element: class="fragment" data-fragment-index="2" -->

```java
interface Version {
    byte[] digits();
    default String text() { return text(digits()); }
    private String text(byte[] version) { … }
}
```
<!-- .element: class="fragment" data-fragment-index="2" -->

--

## Math

---

## Single Line


`$$ J(\theta_0,\theta_1) = \sum_{i=0} $$`

---

## Multiple lines

`$$\begin{aligned}
  \dot{x} & = \sigma(y-x) \\
  \dot{y} & = \rho x - y - xz \\
  \dot{z} & = -\beta z + xy
  \end{aligned} $$`

--

## Being subtle

* Point a
* Point b   
<span>(but that is not important)</span><!-- .element: class="decent x-small"-->
* Point c

--

## Images

<span>To say it with
[Dilbert](https://dilbert.com/strip/1995-12-10):</span><!-- .element: class="decent x-small"-->

![](https://assets.amuniversal.com/0e1eaf909fcf012f2fe600163e41dd5b)

--

## Transitions

---

<!-- .slide:  data-transition="slide"-->
### The train goes on ...
* none<!-- .element: class="xx-small"-->  
Switch backgrounds instantly
* fade<!-- .element: class="xx-small"-->  
Cross fade — default for background transitions
* slide<!-- .element: class="xx-small"-->  
Slide between backgrounds — default for slide transitions
* convex<!-- .element: class="xx-small"-->  
Slide at a convex angle
* concave<!-- .element: class="xx-small"-->  
Slide at a concave angle
* zoom<!-- .element: class="xx-small"-->  
Scale the incoming slide up so it grows in from the center of the screen

---

<!-- .slide:  data-transition="slide"-->
### and on …
* none<!-- .element: class="xx-small"-->  
Switch backgrounds instantly
* fade<!-- .element: class="xx-small"-->  
Cross fade — default for background transitions

---

<!-- .slide:  data-transition="convex-in concave-out"-->
### and stops.
* fade<!-- .element: class="xx-small"-->  
Cross fade — default for background transitions
* slide<!-- .element: class="xx-small"-->  
Slide between backgrounds — default for slide transitions

---

<!-- .slide:  data-transition="fade-in fade-out"-->
### (Passengers entering and leaving)
* slide<!-- .element: class="xx-small"-->  
Slide between backgrounds — default for slide transitions
* convex<!-- .element: class="xx-small"-->  
Slide at a convex angle

---

<!-- .slide:  data-transition="fade"-->
### And it starts again.
* convex<!-- .element: class="xx-small"-->  
Slide at a convex angle
* concave<!-- .element: class="xx-small"-->  
Slide at a concave angle


