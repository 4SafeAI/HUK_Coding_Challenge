# Coding Challenge - HUK

Dieses Repository beschäftigt sich mit der **HUK Coding Challenge**. 

Der Code ist in einem Jupyter-Notebook (`Coding_Challenge_HUK.ipynb`) 
implementiert, das die Aufgabe zur Vorhersage von Kundenaffinitäten zur 
Kfz-Versicherung behandelt.

## Übersicht über Projektstruktur
```bash
/root-directory
    /HUK_MA_CC                   # Datenordner
      /alter_geschlecht.csv      # Daten (separat herunterladen)
      /interesse.csv             # Daten (separat herunterladen)
      /rest.csv                  # Daten (separat herunterladen)
    Coding_Challenge_HUK.ipynb   # Jupyter Notebook
    requirements.txt             # Liste der Abhängigkeiten
```

**Die Daten für dieses Projekt sind in drei CSV-Dateien aufgeteilt und müssen 
separat heruntergeladen und entpackt im Ordner HUK_MA_CC abgelegt werden!**

## Anforderungen

Für dieses Projekt wurde **Python 3.12.9** verwendet.

Bitte stell sicher, dass die **richtige Version von Python** installiert ist. 
Du kannst dies durch die Eingabe des folgenden Befehls überprüfen:

```bash
python --version
```

## Schritte

## 1. Erstellen und Aktivieren einer virtuellen Umgebung

```bash
python -m venv myenv
myenv\Scripts\activate     # Windows
source myenv/bin/activate  # MacOS/Linux
```

## 2. Update pip

```bash
python.exe -m pip install --upgrade pip
```

## 3. Laden der Abhängigkeiten

```bash
pip install -r requirements.txt
```

## 4. Öffnen von Jupyter Lab

```bash
jupyter lab
```

## 5. Öffnen des Jupyter-Notebooks

Navigiere zu `Coding_Challenge_HUK.ipynb` und öffne das Notebook.