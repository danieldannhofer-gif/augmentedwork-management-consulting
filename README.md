# augmentedwork-management-consulting

Management-Consulting-Skill-Sammlung im **SKILL.md-Format** — kompatibel mit gängigen Agent-Tools (Claude Skills, Mistral Vibe, Cursor u. a.), die Anweisungsdateien mit YAML-Frontmatter unterstützen. Jeder Skill liegt in einem eigenen Ordner mit einer `SKILL.md`.

## Enthaltene Skills

| Skill | Zweck | Wann verwenden? |
|---|---|---|
| [engagement-setup](management-consulting-engagement-setup/SKILL.md) | Guidance für die ersten Wochen eines Consulting-Engagements (Kickoff, Discovery, Stakeholder-Mapping) | Beim Start eines neuen Mandats oder bei einem festgefahrenen Projekt |
| [proposal-development](management-consulting-proposal-development/SKILL.md) | Angebote, SOWs, Pitch-Decks und die komplette Pursuit-Phase | Bei RFP-Analyse, Angebotserstellung, Oral Defense |
| [engagement-pricing](management-consulting-engagement-pricing/SKILL.md) | Pricing-Modelle und Commercial Strategy (Fixed, T&M, Value-based, Retainer) | Bei Fee-Struktur, Rate Cards, Margen- und Rabattplanung |
| [strategic-analysis](management-consulting-strategic-analysis/SKILL.md) | Hypothesengetriebene, MECE-Problemlösung und Analyse-Frameworks (Five Forces, SWOT, 7S u. v. m.) | Bei komplexen Problemstellungen, Issue Trees, Markt- und Portfolio-Entscheidungen |
| [workshop-facilitation](management-consulting-workshop-facilitation/SKILL.md) | Design und Moderation von Workshops (Strategy Offsites, Design Thinking, Sprints) | Bei Planung und Durchführung klientenseitiger Working Sessions |
| [project-governance](management-consulting-project-governance/SKILL.md) | Governance-Strukturen, Entscheidungsrechte und Oversight-Mechanismen | Beim Aufbau von Projekt-Governance und Entscheidungskompetenzen |
| [change-management](management-consulting-change-management/SKILL.md) | Change-Initiativen mit etablierten Frameworks (ADKAR, Kotter, Lewin, McKinsey 7S) | Bei Transformationen, Kulturwandel und Prozessverbesserungen |
| [client-deliverables](management-consulting-client-deliverables/SKILL.md) | Hochwertige Klienten-Deliverables (Reports, Decks, Analysen, Empfehlungen) | Bei der Erstellung von Ergebnisdokumenten für Klienten oder Stakeholder |
| [thought-leadership](management-consulting-thought-leadership/SKILL.md) | Thought-Leadership-Inhalte (Position Papers, Whitepaper, Case Studies) | Beim Aufbau von Glaubwürdigkeit und wiederverwendbarem Wissen |
| [project-closeout](management-consulting-project-closeout/SKILL.md) | Projektabschluss (Übergabe, Lessons Learned, Abwicklung, Folgepotenziale) | Beim Abschluss von Engagements und beim Übergang in die Linie |

## Typischer Einsatz entlang des Engagements-Lebenszyklus

```text
Angebot -> Setup -> Analyse -> Preis/Governance -> Durchführung -> Deliverables -> Abschluss
```

- **Vor Vertragsabschluss**: proposal-development, engagement-pricing
- **Projektstart**: engagement-setup, workshop-facilitation
- **Laufende Analyse**: strategic-analysis, client-deliverables
- **Veränderung umsetzen**: change-management, project-governance
- **Sichtbarkeit aufbauen**: thought-leadership
- **Abschluss**: project-closeout

## Wann verwende ich was?

Nicht jede Aufgabe braucht einen Skill. Diese Übersicht hilft bei der Einordnung:

| Situation | Passendes Werkzeug |
|---|---|
| Einmalige Aufgabe, die sich nicht wiederholt | Einfacher Prompt im Chat - kein Skill nötig |
| Aufgabe wiederholt sich, soll aber flexibel bleiben | Prompt-Vorlage, die du kopierst und anpasst |
| Aufgabe wiederholt sich immer gleich und soll zuverlässig funktionieren | **Skill** (feste Anweisungsdatei, die vom Agent automatisch geladen wird) |
| Verhalten, das bei *jeder* Konversation gelten soll | Globale Regel / Custom Instruction des Agent-Tools (z. B. bevorzugte Sprache, Ton) |

Kurz gesagt: **Ein Skill lohnt sich, wenn du dieselbe Anweisung zum dritten Mal tippst.** Er sorgt dafür, dass ein wiederkehrendes Ergebnis nicht vom Zufall oder von der Tagesform abhängt, sondern jedes Mal nach demselben Standard entsteht.

## Wie definiere ich das Ziel eines Skills?

Du musst kein Prozessexperte sein, um einen guten Skill zu definieren. Ein Skill ist nichts anderes als eine schriftliche Anweisung, die der Agent jedes Mal auf dieselbe Weise ausführt. Entscheidend ist nur, dass du klar sagen kannst, was am Ende dabei herauskommen soll.

Beantworte nacheinander diese vier Fragen - am besten in einfachen Worten, so wie du es einem Kollegen erzählen würdest:

1. **Wobei soll mir der Skill helfen?** ("Ich muss ein Angebot für ein Consulting-Mandat schreiben.")
2. **Was genau soll am Ende dastehen?** ("Ein fertiges Angebot mit Win Themes, SOW und Preismodell.")
3. **Woran erkenne ich, dass es gut gelungen ist?** ("Deckt alle RFP-Anforderungen ab, roter Faden, Klientensprache.")
4. **Wann soll der Skill zum Einsatz kommen?** ("Immer wenn ein RFP analysiert oder ein Angebot erstellt wird.")

Schreibe deine Antworten in ein bis zwei Sätzen auf. Das ist bereits die Zieldefinition deines Skills.

### Vom Ziel zur SKILL.md

Aus deinen Antworten ergibt sich die Struktur der Datei fast von selbst:

| Frage | Wird zu ... |
|---|---|
| 1 + 2 (Zweck + Endresultat) | Anweisungen: **Vorgehen** und **Ausgabe** |
| 3 (Erfolgskriterium) | **Qualitätskriterien** |
| 4 (Trigger) | `description` im YAML-Frontmatter - sie entscheidet, wann der Agent den Skill lädt |

Fehlt dir noch eine Antwort auf eine der Fragen, frage dich: "Was würde ich einem neuen Mitarbeiter erklären müssen, damit er diese Aufgabe ohne Rückfragen richtig macht?" Alles, was du dabei erklärst, gehört in den Skill.

## Aufbau einer SKILL.md

```markdown
---
name: mein-skill
description: Wann der Skill geladen werden soll (Trigger und Zweck).
---

# Mein Skill

## Eingabe
Was der Nutzer bereitstellen muss - und was nachgefragt werden soll, wenn es fehlt.

## Vorgehen
Die Schritte in der Reihenfolge, in der sie auszuführen sind.

## Ausgabe
Was am Ende dastehen soll - und in welchem Format.

## Qualitätskriterien
Woran man ein gelungenes Ergebnis erkennt.
```

Der Aufbau ist bewusst einfach gehalten und funktioniert in jedem Agent-Tool, das Markdown-Dateien als Anweisungen einliest.

## Skill hinzufügen

1. Neuen Ordner anlegen: `<name>/SKILL.md`
2. Datei nach dem Aufbau oben erstellen
3. In der Tabelle oben verlinken (inkl. "Wann verwenden?")

Details und weitere Skills siehe [augmentedwork-skill-creation](https://github.com/danieldannhofer-gif/augmentedwork-skill-creation).
