# Abgabe-Data-Science-Gruppe-3
Dies ist der Code unserer Projektleistung im Fach "Vertiefung Data Science"

## Getting Started
Sollten Sie den Code selbst ausführen wollen, so ist Folgendes zu beachten:

1. Der Code liegt in einem Jupyter Notebook und wurde lediglich in Google Colab entwickelt. Funktionen, wie die interaktive Karte könnten in anderen Umgebungen ggf. nicht funktionieren. Wir Empfehlen daher das Notebook in Google Colab auszuführen.
2. Die Anwendung greift auf Google Earth Engine zu, wofür ein Google Cloud account nötig ist. Deshalb wurde ein technischer Nutzer erstellt, dessen credentials in der Authentisierung genutzt werden. Kontaktieren Sie bitte den Administrator ([philipp.wopienka@ba-rm.de](mailto:philipp.wopienka@ba-rm.de)), um die Credentials zu erhalten.

### Einrichtung der Credentials
![Ein Screenshot der Google Colab Anwendung, die den Tab "Secrets" zeigt](./images/secrets_tab.png)

Unter dem Tab "Secrets" können Sie ein neues Secret hinzufügen, wobei Sie `SERVICE_ACCOUNT_CREDENTIALS` als Name eingeben und für den Wert den Inhalt des Key-files, den Sie erhalten haben. Wenn der Schlüssel für das Notebook aktiviert ist, sollte die Authentifizierung funktionieren.
