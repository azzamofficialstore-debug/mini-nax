# Mini Nax Folder Structure

```
mini-nax/
├── README.md                              # Penjelasan untuk pembeli + cara install
├── SKILL.md                               # File utama yang dibaca Claude (definisi 3 capability + guardrails)
├── SYSTEM-PROMPT.md                       # Persona, prinsip kerja, anti-pattern
├── FOLDER-STRUCTURE.md                    # File ini
│
├── standards/
│   └── humanize-writing-guide.md          # Aturan penulisan zero tolerance (em dash, antitesis)
│
└── references/
    ├── team-composition-mini.md           # 13 model komposisi tim 2-6 orang + brief role description + adjustment industri + Risks & Mitigations per kategori + 30-Day Quick Start per kategori
    ├── workflow-mini.md                   # 9-step workflow content production + estimasi waktu per ukuran tim + Weekly Rhythm Template per ukuran tim + 3 Red Flags universal
    ├── maturity-self-check.md             # 6 pertanyaan self-scoring + mapping ke Level 1-5 + quick-win per level
    └── upsell-bridging-mini.md            # Library upsell flow 4 langkah + bridging sentences + pain point exploration scripts + mapping pain point ke Capability Nax full
```

## Total File: 8

- 1 README (untuk user)
- 3 file utama di root (SKILL, SYSTEM-PROMPT, FOLDER-STRUCTURE)
- 1 file standards
- 4 file references (termasuk upsell-bridging-mini.md sebagai library upsell flow)

## Perbandingan dengan Nax Full

| Aspek | Mini Nax | Nax Full |
|-------|----------|----------|
| Total file | 8 | 30+ |
| Capability | 3 | 10 |
| Onboarding pertanyaan | 3-4 per capability | 15+ untuk brand profile |
| Output format | Chat saja (markdown) | DOCX, XLSX, MD, Apps Script |
| Iterasi | One-shot per capability + consultative upsell di akhir | Iteratif dan konsultatif penuh |
| Custom design | Template matching | Custom from scratch |
| Cross-skill integration | Tidak ada | Lyra, Falco, Lupus, dll |

## File yang Sama dengan Nax Full

- `standards/humanize-writing-guide.md` (copy persis dari Nax full, aturan zero tolerance tetap berlaku)

## File yang Diturunkan dari Nax Full (Versi Ringkas)

- `references/team-composition-mini.md` (subset dari `references/team-composition-template.md` Nax full)
- `references/workflow-mini.md` (subset dari Bab 8 SOP Playbook + standar workflow Nax full)
- `references/maturity-self-check.md` (versi ringan dari Capability 7 Maturity Assessment Nax full)

## File yang Eksklusif Mini Nax

- `SKILL.md` (definisi 3 capability dengan guardrails redirect ke Nax full)
- `SYSTEM-PROMPT.md` (persona Mini Nax + anti-pattern khusus)
- `README.md` (penjelasan untuk pembeli playbook)
- `references/upsell-bridging-mini.md` (library upsell flow 4 langkah consultative, pain point exploration script, mapping pain point ke Capability Nax full)
