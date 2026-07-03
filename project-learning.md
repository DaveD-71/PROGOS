# PROGOS Project Learning

## Current State

- Last updated: 2026-07-03T15:37:33.9034656+09:00
- Status: active
- Workspace: `\\prod-fs-gen01\WorkFile\04_在宅勤務\★グローバルビジネス推進部（在宅）\ランゲージサービス課\Dobson（在宅）\04. Projects\code\PROGOS`
- Repository: Git repository on branch `main`, tracking `origin/main`; after the 2026-07-03 fetch, local `main` and `origin/main` are aligned.
- Bootstrap commit: local commit `740beac` contains the five memory scaffold files and has remote commit `b3f3c2a` as its parent.
- Observed contents: PROGOS result PDFs and an Aozawa screenshot set were already present before bootstrap.

## Durable Decisions And Constraints

- Keep the standard five-file memory scaffold at the repository root.
- Preserve pre-existing staged PDFs, screenshots, and archive files unless the user explicitly requests changes.
- Use literal UNC paths for this workspace in memory and troubleshooting notes.
- Treat `C:\Users\d-dobson\.codex\memories\user-learning.md` as the machine-local user-memory source and `user-learning-mirror.md` as its repository-portable mirror.
- Prefer fetch and ahead/behind inspection before any pull; do not push or rewrite the bootstrap commit without explicit user direction.
- CEFR report matching must evaluate workbook taxonomy as well as wording and level. Retain a side-by-side PROGOS-versus-official comparison table for every competence, then state whether the PROGOS comment matches the official CEFR descriptor for the named competence and reported level. When No, also show the closest match, its workbook level, a differing competence scale when applicable, the descriptor with its cell reference appended in parentheses, and the match note as the final row. Current decisions: Range and Interaction are No; Accuracy, Fluency, Coherence, and Phonology are Yes.
- The PROGOS Overall Assessment is a report summary, not an individual CEFR competence or scale represented in `CEFR Descriptors_en.xlsx`. Do not assign official or potential workbook matches to it; CEFR matching applies only to the six individual competence sections.
- Preserve source-language order when formatting bilingual PROGOS content. Japanese-origin report statements use Japanese-left/English-right tables. In retained PROGOS-versus-CEFR comparison tables, label all four language blocks: PROGOS Japanese as Original text, PROGOS English as Translated text, CEFR Japanese as Translated text, and CEFR English as Original text. Model example sentences are English originals in the PDF followed by direct Japanese translations; format those examples English-left/Japanese-right without adding outer brackets around the Japanese translation.
- Before writing or revising the main evaluation report, review the existing repo deliverables first: extracted report markdown, CEFR comparison files, test-item extracts, transcripts, legal-page captures/extracts, prior issue lists, and report plans. Do not rerun source analysis that already exists unless the underlying source changed, the extracted file is missing, or the user explicitly asks for revalidation.
- `PROGOS_prior_analysis_retention.md` is the first-stop retention file for prior findings and conclusions drawn from repo docs and the ChatGPT share thread. Review it before starting fresh analysis, and update it when a reusable finding is established or materially refined.
- Retention entries must be evaluative judgments supported by the underlying artifact or an explicitly identified conversation turn. Do not reconstruct findings from procedural memory. When sources conflict, direct artifacts and later explicit corrections govern.
- In `PROGOS_prior_analysis_retention.md`, distinguish direct evidence and reference sources from prior analysis/provenance sources. Earlier reports and conversation turns show where a judgment was developed, but they are not independent evidence and must not be used circularly.
- The retained Overall Assessment judgment is that both sentences primarily concern vocabulary and basic expression and only touch on Interaction; they do not form a useful or accurate summary of performance across the six reported competences.
- Instruction-language analysis must distinguish L1 task setup from L2 response content. L2-only instructions are defensible only if English comprehension is part of the intended construct; for a spoken-production interpretation, L1 task and role clarification can reduce construct-irrelevant comprehension demands.
- In Aozawa's Part 5 performance, the absence of L1 role clarification coincided with a persistent misunderstanding of the entire scenario: he responded as an employer or recruiter rather than advising a job applicant across all four prompts. Treat this as direct evidence that instruction comprehension confounded the intended task, while avoiding the unsupported claim that L2-only instructions were proven to be the sole cause.
- Do not frame the evaluation around supposed PROGOS “claims.” This restriction is broader than psychometric claims: do not invent, infer, catalogue, verify, or rebut any attributed claim. Quote an exact reviewed source only when attribution is necessary and relevant; otherwise evaluate the observed materials directly.
- Current official PROGOS part names are `Part 1 Interview`, `Part 2 Reading Aloud`, `Part 3 Presentation`, and `Part 5 Communication Activity`. PROGOS uses inconsistent English names for Part 4: `Graphics Presentation` on the English product-information and trial pages, `Graphic Presentation` on the English sample page, and `Presentation with Graphic` on the Japanese sample-page English label. Use `Graphics Presentation` for this project because it matches the product-information page, trial page, and captured test audio, while noting the official-site inconsistency when terminology is material.
- For mojibake checks in this repo, distinguish stored file corruption from shell-display artifacts. The external `check_mojibake.py` script is a detector only; it flags any unexpected non-ASCII by design, so Japanese-bearing folders and files require explicit allowlisting. Verify suspected corruption with Python UTF-8 reads before patching files.

## Active Goals

- Maintain project-specific decisions, constraints, milestones, and preferred workarounds here as the project develops.
