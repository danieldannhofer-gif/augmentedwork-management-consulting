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

## Aufbau einer SKILL.md

Jede `SKILL.md` folgt demselben Muster: YAML-Frontmatter (`name`, `description` als Trigger) gefolgt von den Abschnitten Trigger, Inputs, Vorgehen/Framework, Output Format und Usage.

Details zur Zieldefinition und zum Erstellen eigener Skills siehe [augmentedwork-skill-creation](https://github.com/danieldannhofer-gif/augmentedwork-skill-creation).
