# **Next.js Coding Challenge: Gamer Discussion Snippets**

![pixy-coding-challenge](https://raw.githubusercontent.com/company-recruitment/coding-challenge/main/assets/pixy-coding-challenge.png)

[![language](https://img.shields.io/badge/language-English-121212.svg?style=for-the-badge&labelColor=121212f2&color=9945FF)](https://github.com/company-recruitment/coding-challenge/blob/main/README.md)
[![language](https://img.shields.io/badge/language-German-121212.svg?style=for-the-badge&labelColor=121212f2&color=9945FF)](https://github.com/company-recruitment/coding-challenge/blob/main/README-de.md)

Hi 👋! Vielen Dank, dass du dir die Zeit nimmst, an dieser Coding-Challenge teilzunehmen. Deine Aufgabe ist es, eine kleine, aber funktionale Webanwendung zu entwickeln, die eine grundlegende Diskussionsfunktion bietet. Diese Aufgabe soll uns Einblick in deine Fähigkeiten in Next.js, Tailwind CSS, PostgreSQL (Supabase) und die Integration von UI-Komponenten von [nyxbui.design](https://nyxbui.design) geben.

#### **Was Wir Erwarten**

Wir erwarten, dass diese Aufgabe etwa 4-5 Stunden in Anspruch nimmt. Der Fokus liegt auf dem Schreiben von sauberem, gut strukturiertem Code und der Implementierung der wichtigsten Funktionen.

#### **Die Herausforderung**

Entwickle eine Anwendung, die es Benutzern ermöglicht, **kurze Diskussions-Snippets** zu erstellen und anzuzeigen. Diese Snippets könnten kurze Meinungen oder Fragen zu einem bestimmten Spiel oder Thema sein.

**Erweiterte Features:**

1. **Erstellen und Anzeigen von Snippets:**

   - Benutzer sollten in der Lage sein, kurze Diskussionsbeiträge (Snippets) über ein einfaches Formular zu erstellen.
   - Diese Snippets sollten in einer PostgreSQL-Datenbank (via Supabase) gespeichert werden.
   - Eine Liste von Snippets sollte auf der Hauptseite angezeigt werden.

2. **Verwendung von `nyxbui.design` Komponenten:**
   - Verwende Komponenten von `nyxbui.design` für das Formular und die Anzeige der Snippets.

3. **Benutzer-Authentifizierung:**
   - Implementiere eine Benutzer-Authentifizierung mit Supabase Auth.
   - Nur authentifizierte Benutzer sollten in der Lage sein, Snippets zu erstellen.

4. **Kommentare zu Snippets:**
   - Benutzer sollten in der Lage sein, Kommentare zu bestehenden Snippets hinzuzufügen.
   - Kommentare sollten ebenfalls in der Datenbank gespeichert und angezeigt werden.

5. **Echtzeit-Updates:**
   - Implementiere Echtzeit-Updates für Snippets und Kommentare mit Supabase Realtime.

6. **Erweiterte Datenbankanforderungen:**
   - Entwerfe eine Datenbankstruktur, die Benutzerinformationen, Snippets und Kommentare speichert.
   - Berücksichtige dabei die Beziehungen zwischen den Tabellen (z.B. Benutzer, Snippets, Kommentare).

7. **DRM-Diagramm:**
   - Erstelle ein DRM-Diagramm (Datenbank-Relationsmodell), das die Struktur und Beziehungen deiner Datenbank zeigt.

8. **Environment-Variablen:**
   - Stelle sicher, dass die Environment-Variablen (`NEXT_PUBLIC_SUPABASE_URL` und `NEXT_PUBLIC_SUPABASE_KEY`) in der E-Mail enthalten sind, die du uns sendest.

#### **Supabase Setup**

Um sicherzustellen, dass alle Bewerber eine optimale Erfahrung haben, richtest du dein eigenes Supabase-Projekt ein. Hier ist eine Schritt-für-Schritt-Anleitung:

1. **Erstelle ein Supabase-Konto:**

   - Gehe zu [supabase.com](https://supabase.com) und melde dich an.
   - Erstelle ein neues Projekt. Notiere dir die `API URL` und den `anon key`, die du später benötigst.

2. **Erstelle die notwendigen Tabellen:**

   - Überlege dir, welche Tabellen du benötigst und welche Spalten sinnvoll sind. Dies könnte eine Tabelle für Snippets und eine für Kommentare sein, in denen der Inhalt und andere relevante Informationen gespeichert werden.

3. **Konfiguriere dein Next.js-Projekt:**

   - Verwende die bereitgestellte `.env.local.example` Datei, um die Supabase URL und den anon key in deiner `.env.local` Datei zu konfigurieren:

   ```plaintext
   NEXT_PUBLIC_SUPABASE_URL=https://your-project.supabase.co
   NEXT_PUBLIC_SUPABASE_KEY=your-anon-key
   ```

4. **Installiere Supabase:**

   - Falls noch nicht geschehen, installiere das Supabase JavaScript SDK:

   ```bash
   npm install @supabase/supabase-js
   ```

5. **Verbinde dein Projekt mit Supabase:**
   - In deinem Next.js-Projekt kannst du nun die Supabase-Client-Bibliothek verwenden, um auf deine Datenbank zuzugreifen.

#### **Vorkonfiguriertes Projekt**

Wir stellen dir ein Basisprojekt zur Verfügung, das mit Next.js, Tailwind CSS und `nyxbui.design` vorkonfiguriert ist. Du musst es nur klonen und die obigen Schritte befolgen, um Supabase einzurichten.

1. **Klone das Repository:**

   ```bash
   git clone https://github.com/company-recruitment/coding-challenge.git
   cd coding-challenge
   ```

2. **Installiere Abhängigkeiten:**

   ```bash
   npm install
   ```

3. **Starte den Entwicklungsserver:**
   ```bash
   npm run dev
   ```

#### **FAQs**

- **Was, wenn ich Probleme beim Einrichten von Supabase habe?** Die Supabase-Dokumentation ist ein guter Ausgangspunkt. Diese Aufgabe soll auch deine Fähigkeit testen, neue Tools zu verwenden und dich selbstständig zurechtzufinden.
- **Soll ich bestimmte Features implementieren?** **Nein, alle genannten Features müssen implementiert werden.** Wir suchen nach einer soliden Grundlage, die zeigt, wie du Herausforderungen löst.

#### **Viel Glück! 💪**

Sobald du fertig bist, sende uns eine Bestätigungs-E-Mail mit den Environment-Variablen und dem DRM-Diagramm. Nach deiner Einreichung werden wir uns mit dir in Verbindung setzen.
