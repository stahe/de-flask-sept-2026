# Schritt-für-Schritt-Einführung in das Web-Framework [Flask]

**Kurs und Code (September 2026)**: 👉 **[https://stahe.github.io/de-flask-sept-2026/](https://stahe.github.io/de-flask-sept-2026/)**

## Autor

Der Code und der Kurs wurden vollständig von **Claude**, der KI von Anthropic, geschrieben, die der **alleinige Autor** ist, im Auftrag von Serge Tahé.

## Überblick

Dieser Kurs führt Schritt für Schritt durch die Entwicklung einer MVC-Webanwendung mit dem **Flask**-Framework (Python). Die HTML-Seiten werden serverseitig über **Jinja2**-Views erzeugt, ohne clientseitiges JavaScript-Framework.

Er knüpft an den Kurs [Schritt-für-Schritt-Einführung in das Web-Framework [Spring MVC]](https://stahe.github.io/de-springmvc-sept-2026/) an und folgt exakt derselben Progression. Dieser Kurs wiederum folgte auf die Kurse [ASP.NET Core MVC](https://stahe.github.io/de-aspnetcoremvc-sept-2026/) und [NestJS](https://stahe.github.io/de-nestjs-html-sept-2026/). Die Beispiele haben dieselben Nummern und behandeln dieselben Themen: Wer einen dieser Kurse kennt, kann die Frameworks Beispiel für Beispiel vergleichen.

Der Kurs besteht aus zwei Teilen:

- **28 kurze Beispiele**, die jeweils ein bestimmtes Konzept behandeln:
  - Actions, Routing, Antworten und Weiterleitungen;
  - Parameterbindung und Validierung (Pydantic);
  - Jinja2-Views, Templates und Makros;
  - WTForms-Formulare, Post/Redirect/Get-Muster und CSRF-Schutz;
  - Internationalisierung;
  - Gültigkeitsbereiche von Daten;
  - Lebenszyklus einer Anfrage;
  - JWT-Authentifizierung, Rollen und CAPTCHA;
  - Schichtenarchitektur mit SQLAlchemy und MySQL.
- **Eine vollständige Fallstudie**: *RdvMedecins*, eine Terminverwaltung für eine Arztpraxis. Sie kennt drei Benutzerrollen (Administrator, Ärzte, Patienten), ist zweisprachig (Französisch und Englisch) und gegen Bots geschützt. Alle Dateien werden im Kurs kommentiert.

## Technologien

Python 3.12+ · Flask 3.1 · Jinja2 · Werkzeug · Flask-WTF / WTForms · Pydantic · SQLAlchemy 2.1 · PyMySQL · PyJWT · bcrypt · Babel · waitress · Bootstrap 5.3 · MySQL 8 / MariaDB

## Voraussetzungen

- Python 3.12 oder neuer;
- Visual Studio Code mit der Erweiterung „Python“ von Microsoft;
- MySQL 8 (zum Beispiel mit Laragon unter Windows) oder MariaDB;
- curl.

Anleitungen zur Installation dieser Werkzeuge finden sich in den Anhängen des Kurses.

## Inhalt des Code-Repositorys

- `examples/`: die 28 Beispiele, jedes davon eine kleine Flask-Anwendung (Port 5000);
- `rdvmedecins2-flask/`: die Fallstudie (Port 8081) mit SQL-Skript und `README.md`;
- `directory.txt`: die vollständige Verzeichnisstruktur.
