# KhanSoft Deutsch — Interaktive Deutsche Grammatik (A1 · A2 · B1)

[![GitHub Pages](https://img.shields.io/badge/Hosted_With-GitHub_Pages-22c55e?style=for-the-badge&logo=github)](https://pages.github.com/)
[![German Level](https://img.shields.io/badge/Level-A1_%7C_A2_%7C_B1-blue?style=for-the-badge)](#-curriculum-overview)
[![License: All Rights Reserved](https://img.shields.io/badge/License-All_Rights_Reserved-red?style=for-the-badge)](LICENSE)

> 🚀 **Live Interactive App:** [https://ashrafulsiddiquee.github.io/german-grammar/](https://ashrafulsiddiquee.github.io/german-grammar/)

---

**KhanSoft Deutsch** is a free, fast, and interactive German Grammar web application covering core grammar principles from **Level A1 (Beginner)** through **Level A2 (Elementary)** to **Level B1 (Intermediate)**. 

Built directly from practical classroom study notes, it features bilingual explanations (German with English and Bengali guidance), native German pronunciation via the browser Web Speech API, an interactive Adjective Ending Calculator, a Sentence Structure Visualizer (Satzbau-Studio), and an interactive 10-question practice quiz.

The entire web application runs inside a single, self-contained `index.html` file with zero build steps or server dependencies, making it ready for instant deployment on **GitHub Pages**.

---

## 📑 Table of Contents

- [Key Features](#-key-features)
- [Interactive Learning Tools](#-interactive-learning-tools)
- [Curriculum Overview (29 Modules)](#-curriculum-overview)
  - [🟢 Level A1: Fundamentals](#-level-a1-fundamentals)
  - [🔵 Level A2: Sentence Structure & Cases](#-level-a2-sentence-structure--cases)
  - [🟣 Level B1: Advanced Syntax & Exam Prep](#-level-b1-advanced-syntax--exam-prep)
- [GitHub Pages Deployment Guide](#-github-pages-deployment-guide)
- [Technology Stack](#-technology-stack)
- [FAQ](#-frequently-asked-questions-faq)
- [Copyright & License](#-copyright--license)

---

## ✨ Key Features

- **29 Structured Modules:** Thorough explanations covering pronunciation, articles, conjugations, all 4 cases, prepositions, connectors, and Konjunktiv II.
- **Bilingual Annotations (German · English · বাংলা):** Clear distinctions for challenging concepts like *dürfen vs. müssen*, *denn vs. weil*, *aus vs. von*, and the essential *„Doch“* rule.
- **Native German Audio (Web Speech API):** Listen to example sentences and phrases pronounced with native standard German (`de-DE`).
- **Interactive Adjective Ending Calculator:** Select any article type, case, and gender to instantly see the calculated ending and example sentence.
- **Satzbau-Studio (Sentence Builder):** Visual slot-based model demonstrating Verb Position 2, subject inversion, and the *Satzklammer* (sentence bracket).
- **Interactive Grammar Quiz:** 10 randomized multiple-choice questions with immediate visual feedback and detailed explanations.
- **Dark & Light Mode:** Seamless theme switching with system detection (`prefers-color-scheme`) and persistent `localStorage` memory.
- **Instant Search & Level Filter:** Filter modules in real time by level (A1, A2, B1) or search by keyword (e.g., *Dativ*, *Perfekt*, *Akkusativ*, *weil*).

---

## 🛠️ Interactive Learning Tools

### 1. Adjektiv-Deklinations-Rechner (Adjective Ending Calculator)
Adjective declension is one of the biggest challenges for German learners. This tool allows users to select:
* **Article Type:** Definite (*der/die/das*), Indefinite (*ein/eine*), or Without Article (*Ohne Artikel*).
* **Case:** Nominativ, Akkusativ, or Dativ.
* **Gender / Number:** Maskulin, Feminin, Neutral, or Plural.

It outputs the exact ending (e.g., `-en`, `-e`, `-er`, `-es`, `-em`), builds the complete phrase, and offers one-click audio playback.

### 2. Satzbau-Studio (Sentence Structure Visualizer)
Interactive slot-based cards showing German word order rules:
* **Standard Hauptsatz:** Subject at Position 1, conjugated verb at Position 2.
* **Time Inversion:** Time element placed at Position 1, keeping the verb in Position 2 and moving the subject to Position 3.
* **Satzklammer (Sentence Bracket):** Modal/auxiliary verb in Position 2, with the infinitive or Partizip II closing the bracket at the end.
* **Subordinate Clauses (Nebensätze):** Conjunctions (*weil*, *dass*, *wenn*) moving the conjugated verb to the very end.
* **B1 Double Object Order:** Clear rules for ordering two nouns (Dativ before Akkusativ) or two pronouns (Akkusativ before Dativ).

### 3. Grammatik-Quiz (A1 – B1)
A built-in multiple-choice quiz engine that evaluates comprehension across cases, prepositions, connectors, and causative verbs with immediate score tracking.

---

## 📚 Curriculum Overview

### 🟢 Level A1: Fundamentals
1. **Personalpronomen:** Subject pronouns across singular, plural, and formal *Sie*.
2. **Artikel & Endungen:** Definite, indefinite, and negative articles (*der/die/das*, *ein*, *kein*) plus noun-ending clues (*-ung*, *-heit*, *-chen*, *-ismus*).
3. **Ausspracheregeln (Phonetics):** Detailed sound rules for *ch* (Ach-Laut vs. Ich-Laut), *-er*, *-ig*, vowel pairs (*ei*, *ie*, *eu/äu*), *ss vs. ß*, and voiced *s*.
4. **Verbkonjugation:** Regular verb patterns (*-e, -st, -t, -en, -t, -en*), auxiliary verbs (*haben*, *sein*), and stem-vowel changing verbs (*fahren*, *schlafen*, *sprechen*, *geben*, *helfen*).
5. **Modalverben:** Full conjugations for *können, müssen, dürfen, sollen, wollen, möchten* and a practical comparison between *dürfen* (permission/prohibition) and *müssen* (obligation).
6. **Satzbau-Regeln:** Verb Position 2 rule, subject placement (Position 1 or 3), and time before location (*TeKaMoLo* principle).
7. **Verneinung (kein vs. nicht) & Doch:** Using *kein* for nouns with indefinite/no articles, *nicht* for verbs and adjectives, plus the rule for answering negative questions with *„Doch!“*.
8. **W-Fragen Übersicht:** *Was, Wo, Woher, Wohin, Warum, Wann, Wer, Wen, Welche, Wie viel, Seit wann*.
9. **Trennbare Verben:** How prefixes (*ab-, an-, auf-, ein-, mit-, aus-*) detach and move to the end of the clause.
10. **Der Akkusativ:** Direct objects answering *Wen oder Was?*, highlighting that only masculine changes (*der → den*, *ein → einen*, *kein → keinen*).
11. **Das Perfekt:** Conversational past tense with *haben* or *sein* + *Partizip II*, along with rules for untranslated prefixes (*be-, ver-, er-*) and *-ieren* verbs.
12. **Der Imperativ:** Commands and polite requests for *du* (drop pronoun and *-st*), *ihr* (drop pronoun), and formal *Sie* (inversion with *bitte*).

### 🔵 Level A2: Sentence Structure & Cases
13. **Der Dativ & Dativ-Verben:** Indirect objects answering *Wem?* with article changes (*dem, der, dem, den + n*) and verbs that take dative (*gefallen, gehören, schmecken, helfen, passen, danken*).
14. **Wechselpräpositionen:** The 9 two-way prepositions (*an, auf, hinter, in, neben, über, unter, vor, zwischen*) — stationary location (*Wo?* + Dativ) vs. directional motion (*Wohin?* + Akkusativ).
15. **Positionsverben:** Action vs. state pairs (*legen/liegen, stellen/stehen, hängen/hängen, stecken/stecken*).
16. **Feste Präpositionen:** Pure Accusative prepositions (*durch, für, gegen, ohne, um, bis*) and pure Dative prepositions (*aus, bei, mit, nach, seit, von, zu, ab, gegenüber*).
17. **Präteritum von sein & haben:** Simple past forms (*war* and *hatte*) commonly used in daily conversation.
18. **Reflexive Verben:** Reflexive pronouns (*mich, dich, sich, uns, euch*) and common prepositional combinations (*sich freuen auf/über, sich ärgern über, sich interessieren für*).
19. **Konnektoren & Satzstellung:** Position 0 (*denn*), subordinate clause final verb placement (*weil, dass, wenn*), and adverbial inversion (*deshalb, trotzdem*).
20. **Komparation:** Comparing adjectives (*gut/besser/am besten, gern/lieber/am liebsten, viel/mehr/am meisten*) using *genauso... wie* and *als*.
21. **Adjektivdeklination:** Complete declension tables after definite articles, indefinite articles, and without articles.
22. **Orts- und Richtungspräpositionen:** Choosing between *nach* (countries/cities), *in* (countries with articles/enclosed places), *zu* (people/institutions), and *bei* (staying with someone).

### 🟣 Level B1: Advanced Syntax & Exam Prep
23. **Objektstellung bei zwei Objekten:**
    - 2 Nouns: **Dativ (person) before Akkusativ (thing)**.
    - 2 Pronouns: **Akkusativ pronoun before Dativ pronoun**.
    - 1 Pronoun + 1 Noun: **The pronoun always comes first**.
24. **Konjunktiv II der Gegenwart:** Expressing wishes, hypotheticals, and polite requests using *wäre*, *hätte*, and *würde + Infinitiv*.
25. **Pronominaladverbien:** Asking and answering about things (*worauf / darauf, wofür / dafür, womit / damit*) versus people (*Auf wen? / Mit wem?*).
26. **Kausativ-Verb „lassen“:** Expressing service tasks done by others (e.g., *Ich lasse meine Haare schneiden*).
27. **Wortbildung (-bar & un-):** Creating adjectives of possibility with suffix *-bar* (*trinkbar, essbar, machbar*) and negative opposites with *un-*.
28. **Indirekte Fragen:** Forming polite indirect questions with *ob* or question words (*Können Sie mir sagen, wo der Bahnhof ist?*).
29. **Zweiteilige Konnektoren:** Two-part correlative conjunctions (*sowohl ... als auch*, *weder ... noch*, *entweder ... oder*, *nicht nur ... sondern auch*).

---

## 💻 Technology Stack

- **HTML5:** Semantic, accessible layout structure.
- **Tailwind CSS (CDN):** Modern utility-first styling with responsive grid and dark mode support.
- **Vanilla JavaScript (ES6+):** Dynamic search filtering, accordion interactions, and quiz logic without external framework dependencies.
- **Web Speech API:** In-browser speech synthesis (`de-DE`) for native German audio pronunciation.
- **Font Awesome 6 (CDN):** Vector iconography for clean navigation and UI controls.

---

## ❓ Frequently Asked Questions (FAQ)

### Is this guide suitable for Goethe-Zertifikat or telc preparation?
**Yes.** The topics follow the official Common European Framework of Reference for Languages (CEFR / GeR) curriculum from A1 to B1, directly targeting concepts examined in Goethe, telc, and ÖSD tests.

### Can I practice offline?
**Yes.** Because the application is self-contained in a single `index.html` file, you can double-click and open it locally in any web browser without an active internet connection (speech synthesis utilizes your operating system's built-in voice pack).

### Are my quiz scores saved or sent to a server?
**No.** All interactions and preferences (like dark mode) remain strictly on your local device. No personal data is collected or transmitted.

---

## 📄 Copyright & License

**Copyright © Md Ashraful Hakim Khan Siddiquee. All rights reserved.**

This project, its structured educational content, and original software code are proprietary. Unauthorized copying, distribution, or modification without prior written permission from the author is strictly prohibited.