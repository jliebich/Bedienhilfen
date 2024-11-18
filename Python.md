# Virtuelle Umgebung anlegen

Im Terminal in das Projektverzeichnis wechseln (alos da wo die .py Datein liegen)
Python Version prüfen - mit dieser Version wird die virtuelle Umgebung angelegt:

    python -V

Umgebung anlegen

    python -m venv venv

Umgebung aktivieren

    venv\Scripts\activate

Jetzt kann man mit pip Sachen in die virtuelle Umgebung installieren

In VSCode:
Klicke auf das Python-Symbol in der unteren rechten Ecke von VSCode oder öffne die Befehlspalette mit Strg + Shift + P.
Suche nach „Python: Interpreter auswählen“ und wähle den Python-Interpreter aus, der sich in deinem venv-Ordner befindet (normalerweise venv/Scripts/python)

# pip und Virtualenv innerhalb der Virtuellen Umgebung aktualisieren
Umgebung aktivieren

    source venv/bin/activate  # For Unix/Linux
    venv\Scripts\activate  # For Windows

pip aktualisieren
    
    python -m pip install --upgrade pip

virtualenv aktualisieren
    
    pip install --upgrade virtualenv

# Genutzte Python version in der Virtuellen Umgebung anzeigen
    
    source venv/bin/activate  # For Unix/Linux
    venv\Scripts\activate  # For Windows
    python -V

# Genutzte Python Version in der Virtuellen Umgebung aktualisieren

Requirements-Datei erzeugen:

    source venv/bin/activate  # For Unix/Linux
    venv\Scripts\activate  # For Windows
    pip freeze > requirements.txt





    


