# PROGOS Legal-Document Evidence Map

Saved on: `2026-07-03T10:18:00+09:00`

## Purpose

This file maps areas where the project still lacks technical or governance evidence to the closest related statements found in the captured PROGOS legal pages:

- `output/playwright/progos-legal-page-snapshots/2026-07-03_progos_kiyaku_text.md`
- `output/playwright/progos-legal-page-snapshots/2026-07-03_progos_privacy-management_text.md`
- `output/playwright/progos-legal-page-snapshots/2026-07-03_progos-ai_user-policy_text.md`
- `output/playwright/progos-legal-page-snapshots/2026-07-03_progos-ai_privacy_text.md`

It is intended as a report-writing aid, not as a substitute for the source documents.

## 1. Unpublished Psychometric Evidence

### Related PROGOS policy

From `kiyaku`:

- `PROGOSはプロゴス独自の判定基準に基づいて採点を行うものとする。`
- `PROGOSの結果および内容について、プロゴスはいかなる問合せにも応じないものとする。`
- `申込者は、プロゴスがPROGOSの結果について、完全性や正確性等のいかなる表明・保証もするものではないことに同意する。`

From `progos-ai_user-policy`:

- `PROGOSは自動音声で行い、当社独自の判定基準に基づいて採点を行うものとする。`
- `PROGOSの結果および内容について、当社はいかなる問合せにも応じないものとする。`
- `申込者は、当社がPROGOSの結果について、完全性や正確性等のいかなる表明・保証もするものではないことに同意する。`
- `当社はPROGOSの採点後...当該PROGOSの結果を、受験後5営業日以内に受験者サイトにて通知するものとする。`

### What this confirms

- PROGOS states that scoring is based on its own proprietary criteria.
- PROGOS does not commit in these terms to answering questions about results or test content.
- PROGOS disclaims representations or warranties as to completeness or accuracy of the reported results.
- The test-taker terms add one operational detail: reported results are to be posted on the examinee site within 5 business days after the test.

### What remains unavailable

- validity evidence
- subscore evidence
- classification accuracy evidence
- psychometric studies

## 2. Vendor-Internal Scoring Documentation

### Related PROGOS policy

From `kiyaku`:

- `PROGOSはプロゴス独自の判定基準に基づいて採点を行うものとする。`

From `progos-ai_user-policy`:

- `PROGOSは自動音声で行い、当社独自の判定基準に基づいて採点を行うものとする。`

### What this confirms

- The legal page confirms the existence of an internal scoring framework.
- The public terms also confirm automated voice delivery and proprietary scoring, but not the scoring method itself.

### What remains unavailable

- documentation of the scoring criteria
- explanation of how criteria are operationalized
- explanation of how subscores and overall scores are derived

## 3. Formal Reliability Studies

### Related PROGOS policy

From `kiyaku`:

- `申込者は、プロゴスがPROGOSの結果について、完全性や正確性等のいかなる表明・保証もするものではないことに同意する。`

From `progos-ai_user-policy`:

- `申込者は、当社がPROGOSの結果について、完全性や正確性等のいかなる表明・保証もするものではないことに同意する。`
- `PROGOSオンライン試験監視` is defined as a monitoring function to confirm proper test-taking.

From `progos-ai_privacy`:

- voice data are collected from the PROGOS test
- image data from the PC camera are collected when `PROGOSオンライン試験監視` is used

### What this confirms

- PROGOS publicly describes a proctoring/monitoring layer and the collection of related data.
- PROGOS does not publicly provide reliability evidence in these pages.
- The closest explicit legal statement instead limits result warranties.

### What remains unavailable

- test-retest evidence
- inter-form equivalence evidence
- measurement-error information
- reliability statistics

## 4. Item Bank Specifications Or Technical Manuals

### Related PROGOS policy

From `kiyaku`:

- `PROGOSに関する商標、システム、ウェブサイト、教材等の知的財産権、所有権は、全てプロゴス又はプロゴスに正当に権利を許諾している第三者に帰属するものとする。`

From `progos-ai_user-policy`:

- `PROGOSに関する商標、システム、ウェブサイト、教材等の知的財産権、所有権は、全て当社又は当社に正当に権利を許諾している第三者に帰属するものとする。`
- `申込者は、当社の許諾なく、PROGOSの全部または一部の販売、レンタル、リース、再許諾、譲渡、変更、翻訳、リバースエンジニアリング、逆コンパイル、逆アセンブルを行ってはならないものとする。`

### What this confirms

- PROGOS treats system and materials as protected intellectual property.
- The legal posture is consistent with non-disclosure of technical internals and explicit restriction of reverse-engineering style access.

### What remains unavailable

- item bank specifications
- technical manuals
- scoring-system technical documentation
- public architecture or model documentation

## 5. Broader Legal Documentation Beyond The Four Captured Pages

### Related PROGOS policy

From `kiyaku`:

- the page contains multiple distinct legal sections beyond the main PROGOS test terms, including:
  - `PROGOSオンライン試験監視の利用に関する規約`
  - `プロゴス トレーニングプログラム総合利用規約`
  - `プロゴス 外国人社員向けプログラム総合利用規約`
  - `PROGOS-MENTER 総合利用規約`
  - `CAPE-Impactの利用に関する規約`
- the main PROGOS terms also refer to a separate user-facing test-taker terms page:
  - `ビジネス英語スピーキングテストPROGOSの利用に関する規約（受験者向け）`
  - linked in the extracted file as `https://progos.ai/terms/user_policy.html`
- the main terms also say personal information is handled according to PROGOS’s privacy policy

From `privacy-management`, `progos-ai_user-policy`, and `progos-ai_privacy`:

- `本契約は、日本語で作成され、英語に翻訳されます。日本語版が正本であり、英語版は参考として作成されます。これら両言語版の間に矛盾抵触がある場合、日本語版が優先します。`

### What this confirms

- The original two captured pages did not exhaust the broader legal/document set relevant to PROGOS.
- The previously missing separate test-taker terms page is now captured.
- The PROGOS AI personal-data page is also now captured and is materially more detailed than the older corporate privacy-management page for test-related data handling.
- The Japanese version governs if language versions conflict.

### What remains unavailable

- any additional assessment-specific governance documents not exposed in these public pages
- any technical manual, scoring manual, or psychometric appendix not linked from the captured pages

## 6. Data Handling, Outsourcing, And Related Governance

### Related PROGOS policy

From `privacy-management`:

- personal information is collected only for stated purposes
- data may be jointly used with RareJob and domestic group companies
- data may be outsourced to service providers such as customer-management and e-mail-delivery systems
- data subjects may request disclosure, correction, addition/deletion, erasure, suspension of use, suspension of provision, and disclosure of third-party provision records

From `kiyaku`:

- PROGOS may outsource all or part of service provision and related administrative procedures to RareJob, instructors, and third parties, including re-outsourcing and further re-outsourcing
- PROGOS may create anonymized statistical data from information learned under the contract and use that data for future product/service development and sales activity
- personal information obtained in providing PROGOS is handled under the privacy policy

From `progos-ai_user-policy`:

- when taking the test, the applicant agrees that the Company records audio and uses that audio and monitoring-related information for the purposes stated in the personal-data policy
- when `PROGOSオンライン試験監視` is used, the applicant must provide images and other specified information
- the Company may outsource part or all of PROGOS and related administrative procedures, including re-outsourcing and further re-outsourcing
- test results and registration information may be provided to the applicant’s company or service provider, depending on the contract

From `progos-ai_privacy`:

- collected personal data explicitly include name, email address, PROGOS voice data, IP address, cookie information, website access history, and PC-camera image data for online test monitoring
- purposes explicitly include test evaluation and analysis of test results
- cross-border transfer and management may occur across multiple countries, with Japan and the Republic of the Philippines named
- personal data are retained continuously unless deletion is requested; after a deletion request they are deleted within one month
- shared use may include RareJob group companies
- third-party provision may include the applicant’s employer, service provider, campaign sponsor, or agency where relevant to contract performance
- card-fraud-prevention disclosure may include email address, cardholder name, IP address, and device information
- data-subject rights include access, correction, deletion, restriction, objection, portability, consent withdrawal, and complaint rights
- the page also states breach-notification measures to supervisory authorities and affected persons
- cookies and advertising-effectiveness measurement are expressly disclosed

### What this confirms

- The legal pages provide an outsourcing and privacy-handling framework.
- They also provide a basis for anonymized statistical use of contract-derived information.
- The newer `progos.ai` privacy page provides direct confirmation that voice data and, for monitored tests, camera image data are in scope.
- The newer `progos.ai` privacy page also provides explicit cross-border-transfer, retention, rights, and breach-notification statements that were not available in the older corporate privacy-management page alone.

### What remains unavailable

- explicit routine retention period for voice records absent a deletion request
- explicit routine retention period for camera images absent a deletion request
- explicit speech-data lifecycle details beyond collection, use, transfer, and deletion-on-request
- explicit score-appeal or human-review procedure
- explicit AI-model governance details for PROGOS scoring

## Practical Report Use

For the final evaluation report, these documents support the following cautious phrasing:

- PROGOS publicly states that scoring uses proprietary criteria.
- PROGOS publicly limits inquiries into results and disclaims warranties of completeness and accuracy.
- PROGOS publicly permits outsourcing and re-outsourcing of service-related functions.
- PROGOS publicly states that test voice data are collected, and that PC-camera image data are collected when online test monitoring is used.
- PROGOS publicly states that test-related personal data may be transferred across countries including Japan and the Philippines.
- PROGOS publicly states that data are retained until deletion is requested and then deleted within one month.
- PROGOS publicly provides a privacy-handling framework, third-party disclosure conditions, and data-subject rights.
- The public legal pages do not provide the psychometric, scoring-method, reliability, or technical-governance evidence that would be needed for stronger claims.
