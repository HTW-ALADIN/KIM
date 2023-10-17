# Glossar

Die nachfolgenden Begriffe sind inzwischen gängiges Jargon im Bereich generativer KI und werden an vielen Stellen innerhalb des Workshops verwendet.
Die Liste ist nicht vollumfänglich und soll in erster Linie dazu dienen, dass die Lehrenden einen Überblick über die wichtigsten Begriffe erhalten.
Jeder Begriff ist mit einer technischen und einer allgemeinverständlichen Erklärung versehen.
Diese können als Vorschläge für die Erklärung der Begriffe für die Schülerinnen und Schüler während der Workshopdurchführung verwendet werden, je nach dem welchen Kentnissstand und welches Interesse die Schülerinnen und Schüler aufweisen.

## Prompts

### Technische Erklärung

Ein **Prompt** ist der zentrale Eingabeparameter zur Nutzersteuerung für den Output eines generativen "KI-Modells". Die Modalität des Eingabeparameters ist abhängig vom Modell. Manche Modelle können mehrere Prompts derselben oder unterschiedlicher Modalität verarbeiten, z. B. "positive" und "negative" Prompts, welche die im Prompt beschriebenen Merkmale in der Ausgabe anregen oder verhindern. Das Erstellen von Prompts und die Anwendung fortgeschrittener Techniken wird [Prompt Engineering](https://www.promptingguide.ai/techniques) genannt.

### Allgemeinverständliche Erklärung

Der Prompt beschreibt die "Aufgabe", die das Modell "lösen" soll. Bei GPT-3, also einem Sprachmodell ist der Prompt ein Text, der die Aufgabe beschreibt, die die "KI" lösen soll. Bei Stable-Diffusion, kann Prompt zusätzlich zu dem Text, auch ein Bild sein, das als Grundlage für die Generierung eines neuen Bildes dient. Je präziser die Beschreibung der Aufgabe ist, desto besser kann das Modell die Aufgabe lösen und die Wahrscheinlichkeit, dass die Ausgabe des Modells zu dem passt, was mit dem Prompt gemeint wurde, erhöht sich.

## Seed

### Technische Erklärung

Ein "Seed" ist ein anfänglicher Wert oder eine Eingabe, die verwendet wird, um einen Zufallszahlengenerator zu initialisieren. (Pseudo)Zufallszahlengeneratoren (RNGs) sind Algorithmen, die scheinbar zufällige Zahlen oder Sequenzen von Werten generieren, und sie werden häufig in Anwendungen wie Simulationen, Kryptografie und Spielen verwendet. Bei Verwendung desselben Seeds generiert ein RNG die gleiche Sequenz von zufällig Zahlen. Deterministisch generierte Zufallszahlenfolgen sind nützlich, um Ergebnisse zu replizieren oder konsistente Zufälligkeit in verschiedenen Programmläufen zu erzeugen.

### Allgemeinverständliche Erklärung

Stell dir vor, der Computer ist eine Maschine, die zufällige Zahlen liefert, wie das Werfen eines Würfels. Um sicherzustellen, dass die zufääligen Zahlen jedes Mal gleich sind, kann der Computer mit einer speziellen Zahl starten, die als "Seed" bezeichnet wird. Wenn derselbe Seed verwendet wird, werden jedes Mal dieselben zufälligen Zahlen "gewürfelt". Also, wenn man z. B. Bilder durch den Computer generieren möchte, kann derselbe Seed verwendet werden, um genau dasselbe zufällige Bild zu erhalten.

## Inference Steps

### Technische Erklärung

"Inference Steps" beziehen sich auf die Anzahl der Schritte, die von dem Modell durchgeführt, um Details hinzuzufügen. Bei einer zu geringen Anzahl sieht das Bild zusammengewürfelt aus, bei einer zu hohen Anzahl ist der Nutzen rückläufig und es besteht die Gefahr, dass zu viele Details hinzugefügt werden. Für höherere Bildauflösungen sollte der Wert erhöht werden (mehr Pixel erfordern mehr Iterationen).

### Allgemeinverständliche Erklärung

"Inference Steps" sind die Schritte, die ein Computer unternimmt, um kluge Schlüsse aus Informationen zu ziehen. Denke z. B. daran, wie du aus verschiedenen Puzzleteilen ein Bild zusammensetzt. Der Computer verwendet Schritte, um aus Daten Muster zu erkennen und Vorhersagen zu treffen, wie zum Beispiel, welches Bild sich aus den Puzzleteilen ergibt. Diese Schritte helfen Computern, kluge Entscheidungen zu treffen, basierend auf dem, was sie bereits wissen oder gelernt haben.

## Orientierungsskala

### Technische Erklärung

Theoretisch funktionieren auch negative Werte

### Allgemeinverständliche Erklärung

Die "Orientierungsskala" ist wie der Einfluss, den Anweisungen auf die Art und Weise haben, wie Daten entstehen. Stell dir vor, du hast ein Bild und beschreibst dieses Bild mit einem Text für den Computer. Die Orientierungsskala hilft dabei, zu entscheiden, wie ähnlich das neue Bild deiner Beschreibung sein soll. Wenn die Orientierungsskala hoch ist, wird der Computer versuchen sich sehr stark an die Beschreibung zu halten, so dass das generierte Bild hoffentlich so aussieht wie das Bild was du ursprünglich beschrieben hast. Wenn sie niedrig ist, kann das Bild womöglich vollkommen anders aussehen, als du es beschrieben hast.
