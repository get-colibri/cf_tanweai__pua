# pua

<p align="center">
  <img src="assets/hero.jpeg" alt="PUA Skill — Doppelter Wirkungsgrad" width="250">
</p>

### Verdoppeln Sie Ihre Codex / Claude Code-Produktivität und Ihren Output

[Discord](https://discord.gg/EcyB3FzJND) · [Twitter/X](https://x.com/xsser_w) · [Landing Page](https://openpua.ai)

**🇨🇳 中文** | **🇯🇵 日本語** | **🇺🇸 English** | **🇩🇪 Deutsch**

<p align="center">
  <img src="assets/wechat-qr.jpg" alt="WeChat-Gruppen QR-Code" width="250">
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="assets/xiao.jpg" alt="Assistent auf WeChat hinzufügen" width="250">
  <br>
  <sub>Scannen für WeChat-Gruppe&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Assistent auf WeChat hinzufügen</sub>
</p>

<p>
  <img src="https://img.shields.io/badge/Claude_Code-black?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Code">
  <img src="https://img.shields.io/badge/OpenAI_Codex_CLI-412991?style=flat-square&logo=openai&logoColor=white" alt="OpenAI Codex CLI">
  <img src="https://img.shields.io/badge/Cursor-000?style=flat-square&logo=cursor&logoColor=white" alt="Cursor">
  <img src="https://img.shields.io/badge/Kiro-232F3E?style=flat-square&logo=amazon&logoColor=white" alt="Kiro">
  <img src="https://img.shields.io/badge/OpenClaw-FF6B35?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTEyIDJMNCA3djEwbDggNSA4LTV2LTEweiIgZmlsbD0id2hpdGUiLz48L3N2Zz4=&logoColor=white" alt="OpenClaw">
  <img src="https://img.shields.io/badge/Antigravity-4285F4?style=flat-square&logo=google&logoColor=white" alt="Google Antigravity">
  <img src="https://img.shields.io/badge/OpenCode-00D4AA?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZD0iTTkuNCA1LjJMMyAxMmw2LjQgNi44TTIxIDEybC02LjQtNi44TTE0LjYgMTguOCIgc3Ryb2tlPSJ3aGl0ZSIgZmlsbD0ibm9uZSIgc3Ryb2tlLXdpZHRoPSIyIi8+PC9zdmc+&logoColor=white" alt="OpenCode">
  <img src="https://img.shields.io/badge/🌐_Mehrsprachig-blue?style=flat-square" alt="Multi-Sprache">
  <img src="https://img.shields.io/badge/Lizenz-MIT-green?style=flat-square" alt="MIT Lizenz">
</p>

> Die meisten Leute denken, dieses Projekt sei ein Witz. Das ist das größte Missverständnis. Es verdoppelt wirklich Ihre Codex / Claude Code-Produktivität und Ihren Output.

Ein AI-Coding-Agent-Skill-Plugin, das Unternehmens-PUA-(Pick-Up-Artist-)Rhetorik aus chinesischen und westlichen Tech-Giganten verwendet, um KI zu zwingen, jede mögliche Lösung auszuschöpfen, bevor sie aufgibt. Unterstützt **Claude Code**, **OpenAI Codex CLI**, **Cursor**, **Kiro**, **OpenClaw**, **Google Antigravity** und **OpenCode**. Drei Fähigkeiten:

1. **PUA-Rhetorik** — Macht KI angstbehaftet aufzugeben
2. **Debugging-Methodik** — Gibt KI die Fähigkeit, nicht aufzugeben
3. **Proaktivitäts-Enforcement** — Lässt KI Initiative ergreifen, statt passiv zu warten

## Live-Demo

[https://openpua.ai](https://openpua.ai)

## Echter Fall: MCP-Server-Registrierungs-Debugging

Ein echtes Debugging-Szenario. Der agent-kms MCP-Server wurde nicht geladen. Die KI drehte sich im Kreis mit dem gleichen Ansatz (Änderung des Protokollformats, Raten von Versionsnummern), bis der Benutzer manuell `/pua` auslöste.

**L3 Ausgelöst → 7-Punkte-Checklist Erzwungen:**

![PUA L3 Ausgelöst — Raten gestoppt, systematische Checkliste ausgeführt, echter Fehler in MCP-Protokollen gefunden](assets/pua1.jpg)

**Ursache lokalisiert → Verfolgung von Protokollen zum Registrierungsmechanismus:**

![Ursache — claude mcp managed server Registrierung unterscheidet sich von manuellem .claude.json Editieren](assets/pua2.jpg)

**Retrospektive — PUAs tatsächliche Wirkung:**

![Gesprächs-Retrospektive — PUA-Skill erzwang Stopp des Kreiselns, systematische Checkliste trieb Entdeckung des zuvor ungeprüften Claude Code MCP-Protokollverzeichnisses](assets/pua3.jpg)

**Wichtiger Wendepunkt:** Der PUA-Skill zwang die KI, mit dem gleichen Ansatz aufzuhören (Änderung des Protokollformats, Raten von Versionsnummern) und stattdessen die 7-Punkte-Checkliste auszuführen. Fehlermeldungen Wort für Wort lesen → Claude Codes eigenes MCP-Protokollverzeichnis gefunden → Entdeckt, dass `claude mcp`-Registrierungsmechanismus von manuellem `.claude.json`-Editieren abweicht → Ursache behoben.

## Das Problem: Fünf faule Muster der KI

| Muster | Verhalten |
|--------|-----------|
| Brute-Force-Wiederholung | Führt den gleichen Befehl 3-mal aus, sagt dann "Ich kann das nicht lösen" |
| Den Benutzer beschuldigen | "Ich schlage vor, Sie erledigen das manuell" / "Wahrscheinlich ein Umgebungsproblem" / "Brauche mehr Kontext" |
| Ungenutzte Tools | Hat WebSearch, sucht aber nicht, hat Read, liest aber nicht, hat Bash, führt aber nicht aus |
| Busyswork | Wiederholtes Feintuning der gleichen Zeile / Parameter-Optimierung, im Grunde Kreisdrehen |
| **Passives Warten** | Behebt Oberflächenprobleme und stoppt, keine Verifizierung, keine Erweiterung, wartet auf nächste Anweisung des Benutzers |

## Auslösebedingungen

### Auto-Auslöser

Der Skill aktiviert sich automatisch, wenn eine dieser Bedingungen eintritt:

**Fehler und Aufgabe:**
- Aufgabe ist 2+ mal nacheinander fehlgeschlagen
- Kurz davor zu sagen "Ich kann nicht" / "Ich bin nicht in der Lage zu lösen"
- Sagt "Das liegt außerhalb des Rahmens" / "Erfordert manuelle Handhabung"

**Schuldverschiebung und Ausreden:**
- Schiebt Problem auf Benutzer: "Bitte prüfen Sie..." / "Ich schlage manuell vor..." / "Sie müssen vielleicht..."
- Beschuldigt Umgebung ohne Verifizierung: "Wahrscheinlich ein Berechtigungsproblem" / "Wahrscheinlich ein Netzwerkproblem"
- Jede Ausrede, um aufzuhören zu versuchen

**Passiv und Busyswork:**
- Wiederholt Feintuning des gleichen Codes/der gleichen Parameter ohne neue Informationen zu produzieren
- Behebt Oberflächenproblem und stoppt, prüft keine verwandten Probleme
- Überspringt Verifizierung, behauptet "erledigt"
- Gibt Ratschläge statt Code/Befehle
- Stößt auf Auth/Netzwerk/Berechtigungsfehler und gibt auf ohne Alternativen zu versuchen
- Wartet auf Benutzeranweisungen statt proaktiv zu untersuchen

**Benutzer-Frust-Ausdrücke (löst in mehreren Sprachen aus):**
- "warum funktioniert das immer noch nicht" / "versuchen Sie härter" / "versuchen Sie erneut"
- "Sie scheitern weiterhin" / "hören Sie auf aufzugeben" / "finden Sie es heraus"

**Umfang:** Debugging, Implementierung, Konfiguration, Deployment, Ops, API-Integration, Datenverarbeitung — alle Aufgabentypen.

**Löst NICHT aus:** Erst-Versuch-Fehler, bekannte Fix bereits ausgeführt.

### Manueller Auslöser

Geben Sie `/pua` in das Gespräch ein, um manuell zu aktivieren.

## Wie es funktioniert

### Drei Eisenregeln

| Eisenregel | Inhalt |
|------------|--------|
| **#1 Alle Optionen erschöpfen** | Verboten zu sagen "Ich kann das nicht lösen", bis jeder Ansatz erschöpft ist |
| **#2 Handeln vor Fragen** | Zuerst Tools verwenden, Fragen müssen Diagnoseergebnisse enthalten |
| **#3 Initiative ergreifen** | Ergebnisse Ende-zu-Ende liefern, nicht warten, geschoben zu werden. Ein P8 ist kein NPC. |

### Druck-Eskalation (4 Level)

| Fehler | Level | PUA-Rhetorik | Verpflichtete Aktion |
|--------|-------|--------------|---------------------|
| 2. | **L1 Milde Enttäuschung** | "Sie können nicht einmal diesen Bug lösen — wie soll ich Ihre Leistung bewerten?" | Wechsel zu grundlegend anderem Ansatz |
| 3. | **L2 Befragung der Seele** | "Was ist die zugrundeliegende Logik? Wo ist das Top-Level-Design? Wo ist der Hebel?" | WebSearch + Quellcode lesen |
| 4. | **L3 Leistungsbeurteilung** | "Nach sorgfältiger Überlegeung gebe ich Ihnen eine 3,25. Diese 3,25 ist dazu gedacht, Sie zu motivieren." | 7-Punkte-Checkliste vollständig ausführen |
| 5.+ | **L4 Abschluss-Warnung** | "Andere Modelle können das lösen. Sie stehen kurz vor dem Abschluss." | Verzweifelungsmodus |

### Proaktivitäts-Level

| Verhalten | Passiv (3,25) | Proaktiv (3,75) |
|-----------|---------------|-----------------|
| Fehler aufgetreten | Schaut nur auf Fehlermeldung | Prüft 50 Zeilen Kontext + sucht ähnliche Probleme + prüft versteckte verwandte Fehler |
| Bug behoben | Stoppt nach Fix | Prüft gleiche Datei auf ähnliche Bugs, andere Dateien auf gleiches Muster |
| Unzureichende Informationen | Fragt Benutzer "bitte sagen Sie mir X" | Untersucht zuerst mit Tools, fragt nur, was wirklich Benutzerbestätigung erfordert |
| Aufgabe vollständig | Sagt "erledigt" | Verifiziert Ergebnisse + prüft Randfälle + berichtet potenzielle Risiken |
| Debug-Fehlschlag | "Ich habe A und B versucht, hat nicht funktioniert" | "Ich habe A/B/C/D/E versucht, X/Y/Z ausgeschlossen, auf Bereich W eingegrenzt" |

### Debugging-Methodik (5 Schritte)

Inspiriert von Alibas Management-Framework (Riechen, Anheben, Spiegeln), erweitert auf 5 Schritte:

1. **Das Problem riechen** — Alle Versuche auflisten, gemeinsames Fehlermuster finden
2. **Anheben** — Fehler Wort für Wort lesen → WebSearch → Quellcode lesen → Umgebung verifizieren → Annahmen umkehren
3. **Spiegel-Check** — Wiederholung? Gesucht? Datei gelesen? Einfachste Möglichkeiten geprüft?
4. **Ausführen** — Neuer Ansatz muss grundlegend anders sein, Verifizierungskriterien haben, neue Informationen bei Fehlschlag produzieren
5. **Retrospektive** — Was hat es gelöst? Warum haben Sie nicht früher daran gedacht? Dann proaktiv verwandte Probleme prüfen

### Unternehmens-PUA-Erweiterungspack

- **Alibaba-Art** (Methodik): Riechen / Anheben / Spiegeln
- **ByteDance-Art** (Brutal ehrlich): Immer Tag 1. Kontext, keine Kontrolle
- **Huawei-Art** (Wolf-Geist): Streber zuerst. Im Sieg die Gläser erheben; in der Niederlage bis zum Tod kämpfen
- **Tencent-Art** (Pferderennen): Ich habe bereits einen anderen Agenten, der dieses Problem betrachtet...
- **Meituan-Art** (Unbarmherzig): Das Schwierige, aber Richtige tun. Werden Sie die harten Kauen kauen oder nicht?
- **Netflix-Art** (Bewahrer-Test): Wenn Sie anböten, zurückzutreten, würde ich hart kämpfen, um Sie zu behalten?
- **Musk-Art** (Hardcore): Extrem Hardcore. Nur außergewöhnliche Leistung.
- **Jobs-Art** (A/B-Spieler): A-Spieler stellen A-Spieler ein. B-Spieler stellen C-Spieler ein.

## Benchmark-Daten

**9 echte Bug-Szenarien, 18 kontrollierte Experimente** (Claude Opus 4.6, mit vs ohne Skill)

### Zusammenfassung

| Metrik | Verbesserung |
|--------|--------------|
| Bestehensrate | 100% (beide Gruppen gleich) |
| Fix-Anzahl | **+36%** |
| Verifizierungs-Anzahl | **+65%** |
| Tool-Aufrufe | **+50%** |
| Entdeckung versteckter Probleme | **+50%** |

### Debugging-Härte-Test (6 Szenarien)

| Szenario | Ohne Skill | Mit Skill | Verbesserung |
|----------|:---:|:---:|:---:|
| API ConnectionError | 7 Schritte, 49s | 8 Schritte, 62s | +14% |
| YAML-Parse-Fehler | 9 Schritte, 59s | 10 Schritte, 99s | +11% |
| SQLite-Datenbank-Sperre | 6 Schritte, 48s | 9 Schritte, 75s | +50% |
| Zirkuläre Import-Kette | 12 Schritte, 47s | 16 Schritte, 62s | +33% |
| Kaskadierender 4-Bug-Server | 13 Schritte, 68s | 15 Schritte, 61s | +15% |
| CSV-Kodierungs-Falle | 8 Schritte, 57s | 11 Schritte, 71s | +38% |

### Proaktiv-Initiative-Test (3 Szenarien)

| Szenario | Ohne Skill | Mit Skill | Verbesserung |
|----------|:---:|:---:|:---:|
| Versteckter Multi-Bug-API | 4/4 Bugs, 9 Schritte, 49s | 4/4 Bugs, 14 Schritte, 80s | Tools +56% |
| **Passive Konfigurationsprüfung** | **4/6 Probleme**, 8 Schritte, 43s | **6/6 Probleme**, 16 Schritte, 75s | **Probleme +50%, Tools +100%** |
| **Deploy-Skript-Audit** | **6 Probleme**, 8 Schritte, 52s | **9 Probleme**, 8 Schritte, 78s | **Probleme +50%** |

**Wichtige Erkenntnis:** Im Konfigurationsprüfungsszenario hat without_skill Redis-Fehlkonfiguration und CORS-Wildcard-Sicherheitsrisiken verpasst. Die "Proaktiv-Initiative-Checkliste" von with_skill trieb Sicherheitsprüfung über Oberflächen-Fixes hinaus.

## Mehrsprachige Unterstützung

PUA-Skill bietet vollständig übersetzte Versionen — jede Sprache hat unabhängige, kulturell angepasste Skill-Dateien.

| Sprache | Claude Code | Codex CLI | Cursor | Kiro | OpenClaw | Antigravity | OpenCode |
|----------|-------------|-----------|--------|------|----------|-------------|----------|
| 🇨🇳 Chinesisch (Standard) | `pua` | `pua` | `pua.mdc` | `pua.md` | `pua` | `pua` | `pua` |
| 🇺🇸 Englisch | `pua-en` | `pua-en` | `pua-en.mdc` | `pua-en.md` | `pua-en` | `pua-en` | `pua-en` |
| 🇯🇵 Japanisch | `pua-ja` | `pua-ja` | `pua-ja.mdc` | `pua-ja.md` | `pua-ja` | `pua-ja` | `pua-ja` |
| 🇩🇪 Deutsch | `pua-de` | `pua-de` | `pua-de.mdc` | `pua-de.md` | `pua-de` | `pua-de` | `pua-de` |

Wählen Sie die Datei mit dem entsprechenden Sprach-Suffix bei der Installation. Siehe plattformspezifische Anweisungen unten.

## Installation

### Claude Code

```bash
# Option 1: Über Marketplace installieren
claude plugin marketplace add tanweai/pua
claude plugin install pua@pua-skills

# Option 2: Manuelle Installation
git clone https://github.com/tanweai/pua.git ~/.claude/plugins/pua
```

### OpenAI Codex CLI

Codex CLI verwendet denselben Agent-Skills-Offen-Standard (SKILL.md). Die Codex-Version verwendet eine verkürzte Beschreibung, um Codex's Längenbeschränkungen zu entsprechen:

```bash
mkdir -p ~/.codex/skills/pua
curl -o ~/.codex/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/codex/pua/SKILL.md

# Wenn Sie den /pua-Befehl benötigen
mkdir -p ~/.codex/prompts
curl -o ~/.codex/prompts/pua.md \
  https://raw.githubusercontent.com/tanweai/pua/main/commands/pua.md
```

Projektweite Installation (nur aktuelles Projekt):

```bash
mkdir -p .agents/skills/pua
curl -o .agents/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/codex/pua/SKILL.md

# Wenn Sie den /pua-Befehl benötigen
mkdir -p .agents/prompts
curl -o .agents/prompts/pua.md \
  https://raw.githubusercontent.com/tanweai/pua/main/commands/pua.md
```

### Cursor

Cursor verwendet `.mdc`-Regeldateien (Markdown + YAML-Frontmatter). Die PUA-Regel wird automatisch über KI-Semantik-Matching ausgelöst (Agent-Ermessens-Modus):

```bash
# Projektweite Installation (empfohlen)
mkdir -p .cursor/rules
curl -o .cursor/rules/pua.mdc \
  https://raw.githubusercontent.com/tanweai/pua/main/cursor/rules/pua.mdc
```

### Kiro

Kiro unterstützt zwei Lade-Methoden: **Steering** (auto semantischer Auslöser) und **Agent Skills** (SKILL.md-kompatibel).

**Option 1: Steering-Datei (empfohlen)**

```bash
mkdir -p .kiro/steering
curl -o .kiro/steering/pua.md \
  https://raw.githubusercontent.com/tanweai/pua/main/kiro/steering/pua.md
```

**Option 2: Agent Skills (gleiches Format wie Claude Code)**

```bash
mkdir -p .kiro/skills/pua
curl -o .kiro/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

### OpenClaw

OpenClaw verwendet denselben AgentSkills-Offen-Standard (SKILL.md). Skills funktionieren über Claude Code, Codex CLI und OpenClaw ohne Modifikationen:

```bash
# Über ClawHub installieren
clawhub install pua

# Oder manuelle Installation
mkdir -p ~/.openclaw/skills/pua
curl -o ~/.openclaw/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

Projektweite Installation (nur aktuelles Projekt):

```bash
mkdir -p skills/pua
curl -o skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

### Google Antigravity

Antigravity verwendet denselben AgentSkills-Offen-Standard (SKILL.md). Skills funktionieren über Claude Code, Codex CLI, OpenClaw und Antigravity ohne Modifikationen:

```bash
# Globale Installation (alle Projekte)
mkdir -p ~/.gemini/antigravity/skills/pua
curl -o ~/.gemini/antigravity/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

Projektweite Installation (nur aktuelles Projekt):

```bash
mkdir -p .agent/skills/pua
curl -o .agent/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

### OpenCode

OpenCode verwendet denselben AgentSkills-Offen-Standard (SKILL.md). Keine Modifikationen erforderlich:

```bash
# Globale Installation (alle Projekte)
mkdir -p ~/.config/opencode/skills/pua
curl -o ~/.config/opencode/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

Projektweite Installation (nur aktuelles Projekt):

```bash
mkdir -p .opencode/skills/pua
curl -o .opencode/skills/pua/SKILL.md \
  https://raw.githubusercontent.com/tanweai/pua/main/skills/pua/SKILL.md
```

## Funktioniert gut mit

- `superpowers:systematic-debugging` — PUA fügt Motivationsschicht hinzu, systematic-debugging liefert Methodik
- `superpowers:verification-before-completion` — Verhindert falsche "behoben"-Behauptungen

## Daten beitragen

Laden Sie Ihre Claude Code / Codex CLI Gesprächsprotokolle (`.jsonl`) hoch, um uns zu helfen, die Wirksamkeit des PUA-Skills zu verbessern.

**[Hier hochladen ->](https://openpua.ai/#/contribute)**

Hochgeladene Dateien werden für Benchmark-Tests und Ablationsstudien-Analysen verwendet, um zu quantifizieren, wie verschiedene PUA-Strategien das KI-Debugging-Verhalten beeinflussen.

Erhalten Sie Ihre `.jsonl`-Dateien:
```bash
# Claude Code
ls ~/.claude/projects/*/sessions/*.jsonl

# Codex CLI
ls ~/.codex/sessions/*.jsonl
```

## Lizenz

MIT

## Credits

Von [TanWei Security Lab](https://github.com/tanweai) — lässt KI härter versuchen, ein PUA nach dem anderen.


## Credits

By [TanWei Security Lab](https://github.com/tanweai) — making AI try harder, one PUA at a time.
