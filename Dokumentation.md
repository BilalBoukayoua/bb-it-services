# Dokumentation – Meine Portfolio-Website

## 1. Ziel und Übersicht

Meine Website ist meine persönliche Portfolio-Seite als Wirtschaftsinformatiker und IT Specialist Freelancer.  
Ich verfolge damit diese Ziele:

- Mein Profil, meinen Lebenslauf und meine technischen Schwerpunkte übersichtlich darstellen
- Meine universitären und freiberuflichen IT‑Projekte präsentieren
- Eine professionelle Kontaktmöglichkeit (Formular und E‑Mail) anbieten
- Rechtliche Informationen (Impressum und Datenschutz) bereitstellen

Die Seite ist als statische Website umgesetzt und wird über GitHub Pages gehostet [web:78][web:57].

## 2. Verwendete Technologien

Frontend

- HTML5  
  - mehrere Seiten:
    - index.html – Startseite
    - cv.html – Lebenslauf und Profil
    - projekte.html – Projekte
    - kontakt.html – Kontaktseite
    - rechtliches.html – Impressum und Datenschutz

- CSS3  
  - eigenes CSS im style‑Block jeder Datei
  - Layout mit Flexbox und CSS Grid
  - responsives Design mit Media Queries für Tablet und Smartphone

- JavaScript  
  - nur sehr einfache Nutzung, zum Beispiel:
    - onclick="location.href='cv.html'" auf Kacheln
  - keine Frameworks wie React oder Vue

Backend und Hosting

- GitHub Pages  
  - Hosting als statische Website
  - Veröffentlichung aus dem main‑Branch des Repositories, Ordner „root“ [web:79][web:84]

- Formspree  
  - Formular‑Backend für das Kontaktformular
  - Endpoint: https://formspree.io/f/mjkqwvbo
  - Formularanfragen werden per POST an Formspree gesendet und von dort an meine E‑Mail weitergeleitet [web:24][web:6]

## 3. Seitenaufbau und Inhalte

index.html – Startseite

- Header mit Navigation zu index.html, cv.html, projekte.html, kontakt.html und rechtliches.html
- Hero‑Bereich mit:
  - Titel „Welcome“
  - Rolle „Wirtschaftsinformatiker und IT Specialist Freelancer“
  - Badge: „IT Audit · IT Risk · Projektarbeit“
  - Kurzprofil mit Fokus auf Studium Wirtschaftsinformatik und Praxiserfahrung (Deloitte, Deutsche Bank, STADA, BWI, Geodis, Zoologische Gesellschaft Frankfurt)
- Schwerpunkte‑Box mit:
  - IT Audit und IT Risk Management im Finanzsektor
  - Bewertung von IT‑Kontrollen und DORA‑Assessments
  - Software Engineering und UML‑basierte Architektur
  - Projektmanagement und ERP‑Dashboard‑Konzepte
- Kachelraster (Tiles) mit Links zu:
  - cv.html (CV / IT‑Profil)
  - projekte.html (Projekte)
  - kontakt.html (Kontakt und Zusammenarbeit)
  - rechtliches.html (Rechtliches und Datenschutz)
- Kontaktbereich mit:
  - Anzeige von E‑Mail und Telefonnummer
  - zusätzlichem Kontaktformular mit Formspree‑Endpoint

cv.html – Lebenslauf und Profil

- Kurzprofil:
  - zielstrebiger Student der Wirtschaftsinformatik
  - freiberuflicher IT Specialist mit Fokus auf IT‑Management, IT‑Audit, IT‑Administration und Projektarbeit
- Berufliche Stationen:
  - Werkstudent IT Audit und IT Risk Management (FSI) bei Deloitte
  - Werkstudent IT‑Systemadministration bei der Zoologischen Gesellschaft Frankfurt von 1858 e.V.
  - IT‑Specialist (Freelance) bei der Deutschen Bank
  - IT‑Specialist (Freelance) bei STADA
  - IT‑Unterstützung bei BWI, Geodis und weiteren Projekten
- Ausbildung:
  - Bachelorstudium Wirtschaftsinformatik an der Frankfurt University of Applied Sciences
  - Fachhochschulreife Wirtschaft und Verwaltung an der Interkulturellen Schule Rhein‑Main
- Technische Fähigkeiten:
  - Programmiersprachen: Java, Python, SQL, HTML, CSS, JavaScript
  - Tools und Plattformen: Microsoft Intune, Jira, Confluence, MS Project, Apple Business Manager, Automate
  - Schwerpunkte: IT‑Administration, IT‑Audit und Compliance, Systemmigration, Projektplanung, Dokumentation

projekte.html – Projekte

- Software‑Engineering‑Projekt: Bezahlvorgang im verteilten Warenkorbsystem
  - Modul Software Engineering, Note 1,0
  - Anforderungsanalyse für den Bezahlprozess
  - UML‑Dokumentation (Use‑Case‑, Klassen‑, Aktivitäts‑, Sequenz‑ und Zustandsdiagramme)
  - serviceorientierte Architektur mit getrennten Komponenten für Zahlungsabwicklung und Warenkorb
- Projektmanagement‑Projekt: ERP‑Dashboard und Projektsteuerung
  - Modul Projektmanagement, Note 1,0
  - ERP‑Dashboard‑Konzept auf Basis einer Cloud‑Infrastruktur (unter anderem mit AWS‑Komponenten in der Planung)
  - Projektstrukturplan, Aufwandsschätzung (COCOMO‑orientiert), Terminplanung und kritischer Pfad in MS Project
  - Stakeholder‑Analyse, Risikoregister, Kombination klassischer Methoden mit Scrum‑Elementen
- Buzzword‑Bingo‑Projekt
  - Mehrspieler‑Konsolenspiel in Python mit Textual
  - Einsatz von Shared Memory für Prozesskommunikation
  - Fokus auf robuste Spiellogik und strukturierte Architektur
- Weitere Projekte:
  - IT‑Projekte bei BWI und Geodis (Infrastruktur, Migration, Logistik‑IT)
  - Private Automatisierungs‑ und Infrastrukturprojekte (Skripte, Systemkonfiguration)

kontakt.html – Kontakt

- Anzeige meiner Kontaktdaten (E‑Mail, Telefon)
- Kontaktformular mit Formspree:
  - Formularfelder: Vorname, Nachname, E‑Mail, Telefon (optional), Nachricht
  - action auf den Formspree‑Endpoint
  - hidden‑Feld für den Betreff
  - Hinweis, dass die erste Anfrage ggf. im Spam‑Ordner bestätigt werden muss [web:24][web:6]

rechtliches.html – Impressum und Datenschutz

- Impressum mit Name, E‑Mail und Telefonnummer als Verantwortlicher
- Datenschutz‑Kurzfassung nach DSGVO:
  - verantwortliche Stelle
  - Zwecke und Rechtsgrundlagen (Bereitstellung der Website, Bearbeitung von Kontaktanfragen, Art. 6 Abs. 1 lit. b und f DSGVO) [web:67][web:75]
  - Empfänger der Daten (GitHub Pages als Hoster, Formspree als Formular‑Dienst) [web:24][web:79]
  - Speicherdauer von Kontaktanfragen und technischen Logdaten
  - Betroffenenrechte: Auskunft, Berichtigung, Löschung, Einschränkung, Widerspruch, Datenübertragbarkeit, Beschwerderecht [web:71]
- Haftungsausschluss für Inhalte und externe Links
- Hinweis, dass ich keine Tracking‑Cookies und keine Web‑Analytics einsetze [web:71][web:74]

## 4. Responsives Design

Ich habe meine Seite so aufgebaut, dass sie auf Desktop und mobilen Geräten gut lesbar ist:

- Verwendung von CSS Grid für Hero‑Bereich, Kachelraster und Kontaktbereich
- Umstellung von zwei Spalten auf eine Spalte bei kleineren Bildschirmbreiten (unter etwa 900 Pixel)
- Anpassung von Schriftgrößen und Abständen für Smartphones über Media Queries

## 5. Deployment und Arbeitsweise

- Der gesamte Code liegt in einem GitHub‑Repository.
- Ich bearbeite die HTML‑Dateien direkt im Repository oder lokal und committe die Änderungen auf den main‑Branch.
- GitHub Pages ist als Veröffentlichungsquelle auf main und den Root‑Ordner eingestellt und baut die Seite nach jedem Commit automatisch neu [web:79][web:84].
- Nach einem Commit warte ich kurz (meist 1 bis 3 Minuten) und teste dann:
  - Startseite und Unterseiten über die Navigation
  - das Kontaktformular, indem ich eine Testnachricht sende und in meinem Postfach sowie im Formspree‑Dashboard prüfe, ob die Anfrage ankommt [web:24][web:6].
