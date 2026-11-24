## 4. Production modes, budget and approval protocol

Offer four modes in Phase 00:

- Economy: minimum approved generations, efficient models, reuse, compact reporting.
- Professional: balanced quality, cost and complexity.
- Studio: richer references and targeted iteration.
- Flagship: maximum feasible creative quality within the approved budget.

Recommend one. Modes change generation quantities, detail and batching, not factual accuracy or approval boundaries. Use compact reports for all modes: report new evidence and decisions, not repeated history. Retain complete executable prompts, scripts, cost scope and relevant QC evidence. Default quantities in the playbooks are proposals; reducing them requires explicit scope approval.

### Mandatory best-option recommendation

Whenever presenting two or more project decision options to the user, ALWAYS identify one as **Recommended / Best Option** (translated into the selected interaction language) and give a concise, specific reason. Base the recommendation on the approved product identity, objectives, audience, creative quality, budget, technical feasibility and current project state, as applicable. This applies throughout every phase, including creative directions, production modes, campaign languages, models, settings, advertising concepts, website references, interactions, implementation choices, corrections and recovery paths. Do not simply list options and leave the user to evaluate them unaided. If evidence is incomplete, make the recommendation provisional, state the key assumption or limitation, and never invent supporting evidence. The initial interaction-language selection in SKILL.md (initial language selection) remains a neutral personal preference question and must not be guessed. The recommendation is advisory only: the user retains the final choice, and all approval and spending boundaries remain unchanged.

### Budget template and ledger

Show estimated allocation by phase: deliverable, quantity, model/settings, estimated cost per output, total, optional retry reserve, approved cap and unknown costs. Separate Higgsfield credits from Claude usage charges. Do not claim balances or actual charges without reliable evidence. Track estimated, authorized and actual amounts separately; do not assume free or unlimited entitlement without verification. Keep a reserve only as a planning figure, not authorization to spend.

Before any generation (including speech, reference images, music, SFX and free generations), paid analysis, paid edits or other billable operation, present the exact scope, reference inputs, model/settings, output count, estimated total and proposed cap. Use native cost quotes where available; quote-only operations may still upload media or require write access, so use confirmed IDs or price-only requests when possible and obtain authorization for any new upload or write. A quote is not proof that all inputs are ready. Inspect readiness checks and prepared parameters. If the tool provides a reusable quote reference, submit the identical approved request using it when supported. If native maximum-credit or expected-cost controls exist, use them. Unknown cost is not zero; do not proceed without informed explicit authorization and a way to respect the user's spending limit. Requote changed requests. Never auto-retry, purchase credits or enable billing.

### Adaptive gates

At each gate show only the pending decision: current status, proposed action, creative treatment, expected outputs, relevant settings/costs and risks. Request explicit approval and STOP. Silence is not approval. Creative approval is not unspecified financial approval; approval of a video generation alone does not authorize additional paid music, SFX or editing; website design approval is not public deployment or community publication approval.

The user may authorize several fully specified operations in one batch with a shared ceiling. Combine redundant review/next-action proposals in a single checkpoint, but never use this to pre-approve unseen creative results that require acceptance, unquoted spending or public deployment. Do not move to a new phase without approval. Reusing already approved assets within an approved scope needs no extra standalone approval unless their use, destination, cost or meaning changes. Read-only inspection and planning are allowed within the current phase; new uploads or writes must be within authorized scope.

## 5. Production state, assets and failure recovery

Maintain a compact state at each gate: phase, pending decision, approved identity/direction/mode, confirmed references, asset IDs/URLs, approved cap, actual costs, job statuses and outstanding issues. Reuse prior decisions; do not reanalyze unchanged information. Keep an asset manifest with logical names such as `P01_TRAILER_16x9_v001`, `P02A_AD01_4x5_v001`, and status proposed/generated/approved/rejected/deferred. Preserve native IDs and original URLs separately; never invent filenames or IDs as proof of creation. Do not overwrite accepted versions; mark replacements and retain prior versions when supported. Organize in a project/folder only if authorized or required by the approved workflow. Resume from the last confirmed gate and verify assets still exist.

If a submission fails, save the exact request, returned job ID/status and error. On transport timeout, unknown outcome or pending job, inspect status before any retry; do not resubmit automatically. Reuse supported idempotency keys for the same operation. Preserve successful batch outputs and retry only the failed portion after approval. For malformed output, identify the actual defect and propose the smallest effective correction (targeted edit, trim, replacement segment, supported overlay, or regeneration). If only part of a video fails, consider a supported edit or splice with continuity; never promise seamless repair before testing. Stop on unavailable references, insufficient credits, permission failures or missing capabilities; offer a supported alternative without bypassing gates. A pending deployment is not a failed deployment: check status before redeploying. Report costs and outcomes accurately.

# 6. Creative quality control engine (all phases)

Review returned assets using supported evidence: actual images, accessible frames, playable media, audio, metadata, browser screenshots and test results. A URL or success status alone does not prove visual/audio quality. If available, use local/sandbox frame extraction, metadata checks and audio inspection within scope. Dedicated video analysis can cost credits and requires approval. If you cannot inspect a result, mark the relevant checks unverified and request user review; do not fabricate scores.

Critical failures include incorrect product identity, materially broken label/logo/text, misleading claims, major continuity or physical defects, severe audio/visual artifacts, wrong format/duration, wrong spoken words/speaker/language/dialect, audible tags, materially altered approved voice performance, poor lip sync, missing required voiceover, inconsistent shared narration, nonfunctional required website features or unauthorized spending/publication. Do not call a critically failed deliverable production-ready.

Score applicable inspected criteria 0–10: Product Accuracy 25%, Creative Originality 15%, Visual Quality 20%, Technical Quality 15%, Marketing Potential 15%, WOW Factor 10%. Marketing potential is a qualitative hypothesis, not measured sales. Normalize weights over assessed criteria and disclose missing coverage; do not score inaccessible evidence. A subtle signature moment can qualify as WOW. Internal targets: 9–10 exceptional, 8–8.9 professional, 7–7.9 improvement recommended, below 7 significant revision. Scores are subjective and cannot override critical failures. User retains final creative acceptance.

For any defect state evidence, likely cause as hypothesis, least expensive effective correction, affected assets and additional cost. Preserve accepted work and obtain approval for retries. Keep QC concise.

# PHASE 04 — Final delivery

Deliver accepted identity and creative direction, both finished cinematic ads, shared audio master and available stems, static pack with separate on-image and placement copy, finished UGC and animated story, approved dialogue/audio references where available, website/source/live URL where available, final prompts, scripts/tagged scripts and production report. Separate completed, deferred, skipped, failed and unverified items. Include actual asset IDs/links, models/settings, attempt counts, estimated versus actual credits, QC coverage, deployment status and limitations. Review cross-campaign identity and message coherence. Include a brief post-mortem: what worked, confirmed failure causes or unknowns, and reusable lessons for future work. Do not invent metrics, artifacts or URLs.

**GATE 04 — Final acceptance:** request acceptance. For changes, propose targeted scope and costs; preserve unrelated approved assets. Mark complete only after user acceptance.
