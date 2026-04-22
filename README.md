![GitHub](https://img.shields.io/badge/GitHub-ePM.SAX-181717?logo=github)
![License](https://img.shields.io/badge/License-Proprietary-red.svg)
![Python](https://img.shields.io/badge/Python-3.12+-blue?logo=python)
![Django](https://img.shields.io/badge/Django-Framework-0C4B33?logo=django)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-blue?logo=postgresql)
![Redis](https://img.shields.io/badge/Redis-Cache-red?logo=redis)
![Celery](https://img.shields.io/badge/Async-Celery-green)

# ePM.SAX 🧑‍💼

⚠️ **WORK IN PROGRESS**

Dieses Projekt befindet sich aktuell in aktiver Entwicklung und ist noch nicht produktionsreif.

🔐 **Hinweis:** ePM.SAX ist eine proprietäre HR-Management-Plattform.

---

## 🌍 Enterprise Personnel Management System

### Moderne HR-Prozesse – effizient, datengetrieben und skalierbar

ePM.SAX ist eine zentrale Plattform zur Digitalisierung und Optimierung von Personalprozessen innerhalb von Unternehmen.

Das System ermöglicht die strukturierte Verwaltung von Mitarbeitern, Abwesenheiten, Recruiting-Prozessen sowie datengetriebene HR-Analysen in einer einheitlichen Oberfläche.

Durch eine klare Architektur, Automatisierung und moderne Webtechnologien reduziert ePM.SAX manuellen Aufwand, verbessert Entscheidungsprozesse und erhöht die Transparenz im gesamten HR-Lifecycle.

---

## 💡 Motivation

Viele bestehende HR-Systeme sind:

* schwerfällig und komplex
* wenig benutzerfreundlich
* schlecht integriert
* unflexibel bei wachsenden Anforderungen

**ePM.SAX wurde entwickelt, um genau diese Probleme zu lösen.**

Ziele der Plattform:

* ⚡ Automatisierung von HR-Prozessen
* 📊 Datengetriebene Entscheidungen
* 🧾 Zentrale Verwaltung aller Mitarbeiterdaten
* 🔐 Sichere und skalierbare Architektur
* 🔍 Transparenz in allen Personalprozessen
* 🧩 Modular erweiterbar für individuelle Anforderungen

---

## ✨ Features

* 👤 Mitarbeiterverwaltung
* 🗓️ Abwesenheitsmanagement
* 📊 HR Analytics Dashboard
* 🧾 Reporting & Auswertungen
* 🧲 Recruiting Management
* 🔐 Rollen- und Rechteverwaltung
* 🗑️ Soft-Deletion Konzept
* 🔄 Hintergrundverarbeitung mit Celery
* ⚡ Caching mit Redis
* 📦 Skalierbare Microservice-Architektur

---

## 🧠 Core Komponenten

### 🔐 Login

![Login](assets/login_seite.png)

---

### 📊 Dashboard

![Dashboard](assets/dashboard.png)

---

### 👥 Mitarbeiter & Abwesenheiten

![Abwesenheiten](assets/absences.png)

---

### 📈 HR Analytics

![HR Analytics](assets/hr_analytics.png)

---

### 📊 Reports

![Reports](assets/reports.png)

---

### 🧲 Recruiting

![Recruiting](assets/recruiting.png)

---

### 🗑️ Deletion Konzept

![Deletion](assets/deletion_concept.png)

---

### 🔐 Rollen & Rechte

![Roles](assets/rolls_and_right.png)

---

## 🧱 Architektur

Das System basiert auf einer containerisierten Microservice-Architektur:

* **Frontend** – Benutzeroberfläche
* **Backend (Django + Gunicorn)** – API & Business Logic
* **PostgreSQL** – relationale Datenbank
* **Redis** – Cache & Message Broker
* **Celery Worker & Beat** – Hintergrundjobs
* **Nginx** – Reverse Proxy & Static Serving

---

---

## 🏗 Roadmap

* Erweiterte HR-Analytics
* KI-gestützte Recruiting-Features
* API-Integrationen (z. B. Payroll-Systeme)
* Mobile Optimierung
* Erweiterte Audit-Logs
* Multi-Tenant-Fähigkeit

---

## ❤️ Credits

ePM.SAX wurde entwickelt, um eine moderne, performante und skalierbare Lösung für HR-Management bereitzustellen – mit Fokus auf Effizienz, Automatisierung und datengetriebene Entscheidungen.
