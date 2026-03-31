# Claude-als-CMO
Entwickelt für Unternehmen, die ihre vollständige Marketing- &amp; Kommunikationskompetenz erweitern wollen — ohne eine 20-köpfige Abteilung. 
Erstellt von Robert Stefan - Robert's KI-Corner
# Robert's KI-Marketing-Team

## Was ist das hier?

11 spezialisierte Claude Skills, die gemeinsam die vollständige Marketing- und Kommunikationsfunktion einer Organisation abdecken. Jeder Skill ist ein „Teammitglied" mit tiefem Fachwissen in seinem Bereich.

Im Gegensatz zu generischen KI-Marketing-Tools deckt dieses Team auch interne Kommunikation, Change Management, Stakeholder-Governance und Public Affairs ab — die Bereiche, in denen Qualität am meisten zählt und in denen die meisten KI-Tools versagen.

---

## Das Team

| # | Rolle | Skill | Was er macht |
|---|-------|-------|--------------|
| 1 | Content-Stratege | content-strategist | LinkedIn-Posts, Thought Leadership, Content-Kalender (7 Post-Typen) |
| 2 | Newsletter-Redakteur | newsletter-editor | Vollständige Newsletter-Ausgaben mit SEO-Metadaten und Audio-Briefings |
| 3 | Performance-Marketer | performance-marketer | Anzeigentexte, Google Ads RSA, A/B-Tests, Kampagnenoptimierung |
| 4 | Brand Guardian | brand-guardian | Visuelle Identität, KI-Bildprompts, Design-System-Durchsetzung |
| 5 | PR & Medienmanager | pr-media-manager | Pressemitteilungen, Medienpitches, Krisen-PR, Sprechertraining |
| 6 | Interne Kommunikation | internal-comms-lead | Mitarbeiter-Newsletter, Change-Ankündigungen, Town Halls |
| 7 | Change & CI Coach | change-ci-coach | KI-Adoption, Marginal-Gains-Sprints, Widerstandsmanagement |
| 8 | Stakeholder-Kommunikation | stakeholder-comms | Vorstandsberichte, Investoren-Updates, Impact-Reporting (B Corp-konform) |
| 9 | Public-Affairs-Berater | government-affairs | Policy Papers, Lobbying-Transparenz, EU-AI-Act-Compliance |
| 10 | Analytics & Reporting | analytics-reporting | KPI-Dashboards, Kampagnen-ROI, Wochen-/Monatsberichte |
| 11 | Marketing Operations | marketing-ops | Budgetplanung, Meeting-Management, Lieferantenverwaltung, SOPs |

---

## Warum existiert das?

Im Februar 2026 wurde öffentlich bekannt, dass das gesamte Growth-Marketing von [Anthropic 10 Monate lang von einer einzigen Person](https://claude.com/blog/how-anthropic-uses-claude-marketing) geleitet wurde. Die IPR-Studie zeigte: 95,4 % der Kommunikationsprofis nutzen GenAI — aber nur 36 % haben eine Strategie.

Die Lücke liegt nicht bei den Tools. Sie liegt bei den Systemen.

Dieses Skill-Set schließt diese Lücke. Nicht mit Theorie, sondern mit produktionsreifen Workflows, die jede Marketingfachkraft sofort einsetzen kann.

---

## Was es anders macht

Die meisten KI-Marketing-Tools decken Content-Erstellung ab — Social Posts, E-Mails, Anzeigentexte.

Dieses Team deckt zusätzlich ab:

- **Interne Kommunikation:** Weil KI-Transformation ohne interne Ausrichtung scheitert
- **Change Management:** Weil Adoption der Engpass ist, nicht die Technologie
- **Stakeholder-Governance:** Weil B Corp- und ESG-Reporting systematische Kommunikation erfordert
- **Public Affairs:** Weil EU-AI-Act und CSRD jedes europäische Unternehmen betreffen
- **Marketing Operations:** Weil Budgets, Meetings und Administration 30 %+ der Führungszeit verschlingen

Die **Marginal-Gains-Philosophie** (1%-Verbesserungen, die sich kumulieren) zieht sich durch alles. Keine Big-Bang-Transformationen. 2-Wochen-Sprints. Messbarer Fortschritt.

---

## Installation

### Für Claude.ai (Einzelpersonen)

1. Den gewünschten Skill-Ordner herunterladen
2. Claude.ai → Einstellungen → Funktionen → Skills öffnen
3. Den Skill-Ordner hochladen (ggf. als ZIP)
4. Den Skill aktivieren

### Für Claude Code

Skill-Ordner ins Claude Code Skills-Verzeichnis legen:

```
~/.claude/skills/content-strategist/
~/.claude/skills/newsletter-editor/
...
```

### Vollständige Team-Installation

Repository klonen und alle 11 Skills installieren:

```
git clone https://github.com/hartmut-ux/ai-marketing-team.git
```

---

## Anpassung

Diese Skills sind darauf ausgelegt, für Ihre Organisation angepasst zu werden:

- **Markenstimme:** Ersetzen Sie die MMIND.ai-Markenrichtlinien durch Ihre eigenen im Brand-Guardian-Skill
- **Post-Typen:** Passen Sie die 7 LinkedIn-Post-Typen im Content-Strategen an Ihre Zielgruppe an
- **Reporting:** Passen Sie die KPI-Benchmarks in Analytics & Reporting für Ihre Branche an
- **B Corp:** Wenn Sie nicht B-Corp-zertifiziert sind, gelten die Governance-Frameworks dennoch — entfernen Sie einfach die zertifizierungsspezifischen Formulierungen
- **Sprache:** Skills sind standardmäßig DE/EN zweisprachig (Schweizerdeutsch). Anpassen an Ihren Markt.

---

## Architektur

Jeder Skill folgt Claudes Standard-Skill-Struktur:

```
skill-name/
├── SKILL.md          # Hauptanweisungen (YAML-Frontmatter + Markdown)
├── references/       # Zusätzliche Dokumentation, die bei Bedarf geladen wird
└── assets/           # Templates, Beispiele, Markendateien
```

Skills sind komponierbar — sie verweisen auf die Expertise der anderen und übergeben Aufgaben bei Bedarf. Der Content-Stratege arbeitet mit dem Brand Guardian für Visuals zusammen. Der Internal-Comms-Lead arbeitet mit dem Change & CI Coach für Transformationsnarrative. Die Stakeholder-Kommunikation arbeitet mit Public Affairs für Policy-Updates zusammen.

---

## B-Corp-Standards-Integration

Zwei B-Lab-Standards sind durchgehend eingebettet:

- **PSG (Purpose & Stakeholder Governance):** Stellt verantwortungsvolles Marketing, Stakeholder-Berücksichtigung und transparentes Reporting sicher
- **GACA (Government Affairs & Collective Action):** Stellt verantwortungsvolles Lobbying, kollektiven Impact und Steuertransparenz sicher

Diese Standards gelten unabhängig davon, ob Ihre Organisation eine B-Corp-Zertifizierung anstrebt. Sie repräsentieren Best Practices für purpose-getriebenes Wirtschaften.

---

## Mitwirken

Verbesserungen sind willkommen. Bitte beachten:

- Skills fokussiert halten (eine Rolle, eine Verantwortung)
- Claudes Skill-Format einhalten (SKILL.md mit YAML-Frontmatter)
- Qualitäts-Checklisten einschließen
- B-Corp-Standards referenzieren, wo relevant
- Mit echten Anwendungsfällen testen, bevor ein Beitrag eingereicht wird

---

## Lizenz

MIT — Frei verwendbar. Für Ihre Organisation anpassbar. Namensnennung erwünscht.

---

## Über den Autor

Rob Stefan ist KI-Consultant, Content Creator und Claude Ambassador — mit Fokus auf den deutschsprachigen Markt.
Er berät DACH-Unternehmen dabei, KI nicht nur einzusetzen, sondern wirklich zu verstehen: Was steckt dahinter, was bringt es konkret, und wie setzt man es so um, dass es sich im Alltag anfühlt.
Mit Roberts KI-Corner baut er den deutschen Newsletter auf, der den Unterschied macht zwischen „ich hab davon gehört" und „ich weiß, wie ich's anwende". Kein Hype. Kein Buzzword-Bingo. Nur das, was wirklich funktioniert — auf Deutsch, für den DACH-Kontext.
Als offizieller Claude Ambassador von Anthropic gehört er zu den wenigen deutschsprachigen Stimmen, die das Thema KI nicht nur kommentieren, sondern aktiv mitgestalten.

Dieses KI-Marketing-Team repräsentiert sine Methodik für den Aufbau agentischer Teams, die KI in Kommunikations-Workflows integrieren — bei gleichzeitiger Wahrung von Markenkonsistenz, strategischer Ausrichtung und Stakeholder-Governance.

🌐 https://robertskicorner.substack.com/
💼 https://www.linkedin.com/in/robert-stefan-ki/
