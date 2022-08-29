# Lern-Bericht
✍️ Lernbericht, von mir, Eray Çimen.

## Einleitung

✍️ Im Modul 133 lernt man das JSF kennen. In diesem Auftrag ging es darum, eine Applikation zu erstellen, sodass ein Nutzer ein Avatar basierend auf die PokemonGo Models konfigurieren kann.

## Was habe ich gelernt?

✍️ Ich habe den "<f:setPropertyApplicationListener />"-Xhtml-Tag genauer kennengelernt. Dieser setzt voraus, in einem "Action-Parent" als Kind hinzugefügt zu werden. Sobald das Elternelement ausgelöst wird, setzt der PropertyApplicationListener die gewünschten Daten in die Bean-Attribute.

## Beschreibung

✍️ Verwenden Sie drei verschiedene Medien, um zu zeigen, was Sie gelernt haben. Zum Beispiel:

```html
<h:commandLink action="augen.xhtml">
        <f:setPropertyActionListener target="#{pokemonBean.haut}" value="h" />
        <h:graphicImage value="/resources/pokemon/h.png">
        </h:graphicImage>
</h:commandLink>

<!-- Nächste Seite -->

<h:outputLabel value="#{pokemonBean.haut} wurde als Wert gesetzt."> </h:outputLabel>
```
![lernbericht](https://user-images.githubusercontent.com/26624740/187164785-ba0a43a1-df69-41db-b97d-c864733dcadf.PNG)
![lernbericht2](https://user-images.githubusercontent.com/26624740/187164817-bf4381ca-c312-42c5-9085-f34b2f68b4ba.PNG)

## Verifikation

Der Codeabschnitt zeigt auf, dass beim Klicken des rechten Bildes (gem. Screenshot) der Wert "h" in der pokemonBean abgespeichert wird.
Auf dem zweiten Screenshot wird nochmals bestätigt, ob die Eingabe richtig gespeichert wurde. Wie auf dem Codeabschnitt, zeigt der Text den Buchstaben "h" für hell an.

# Reflektion zum Arbeitsprozess

👍 Durch verfügbare Dokumentationen im Internet, waren die gesetzten Ziele immer sehr schnell realisierbar.

👎 Die Entwicklungsumgebung "IntelliJ" macht bei JSF-Projekten nicht gut mit. Anfangs wurde die Bean nicht erwartungsgemäss instanziiert.

**VBV**: ✍️ Mit neuen Entwicklungsumgebungen zu arbeiten ist schön und gut, allerdings sollte als Backup-Plan Netbeans installiert werden, um bei Problemsituationen nicht zu viel Zeit zu verlieren.
