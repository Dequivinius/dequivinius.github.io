
# Wie erstelle ich ein Bild mit JSF?

## Aufgabenstellung

JSF ist eine Java-Bibliothek...

Mein Ziel ist es:

   1. Ein Benutzer ohne Vorwissen kann ein Bild anzeigen mittels JSF

## Produkt

Hier ist ein Text. Hier ist ein **fetter Text**.



Änder Sie hierzu die `web.xml` und fügen Sie folgende Zeilen hinzu:

```xml
    <context-param>
        <param-name>javax.faces.WEBAPP_RESOURCES_DIRECTORY</param-name>
        <param-value>/WEB-INF/resources</param-value>
    </context-param>
```


```java
public String getFilename() {
        String returnstring = "";
        
        if (this.eyecolor == "gruen") {
            returnstring += "g";
        }
```

<img width="766" alt="Capture d’écran 2021-08-30 à 15 50 51" src="https://user-images.githubusercontent.com/80431964/131349862-84aab1c4-8d88-46b0-b057-374c4c410271.png">


## Reflektion und Verifikation

Mir hat das Modul gut gefallen, aber ich konnte nicht gut folgen, weil...

