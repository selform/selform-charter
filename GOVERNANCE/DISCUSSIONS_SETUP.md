# Discussions setup checklist (manual)

This repository is designed to run **Discussions-first**. The files under `.github/DISCUSSION_TEMPLATE/` provide discussion *category forms* (YAML). They become available only after the corresponding discussion categories exist.

## 1) Add repository topics

In the repo “About” panel, add these topics:
- `philosophy`
- `agency`
- `tools-for-thought`
- `ai-alignment`
- `sensemaking`
- `human-computer-interaction`
- `ethics`

## 2) Create / confirm discussion categories

Recommended categories (names) and slugs:
- **Welcome** → `welcome`
- **Open questions** → `open-questions`
- (Optional) **Principles**, **Risks**, **Meta**

If your category slug differs, rename the corresponding files under `.github/DISCUSSION_TEMPLATE/` to match the actual slug (per GitHub docs).

## 3) Seed and pin two starter threads

### Pinned #1: “Welcome to Selform: Introduce yourself & your thoughts on Agency”

Use the “Welcome” discussion form, or paste the prompt from `TEMPLATES/en/discussion-welcome.md`.

Suggested opener (short):
- What do you mean by *agency* today?
- Where do you fear “outsourcing judgment” the most?
- What should Selform refuse to do, even if it can?

### Pinned #2: “Open Question: Enhancement vs. Replacement”

Anchor to: `en/questions/q-enhancement-vs-replacement.md`

Suggested opener (short):
- Where is the boundary between enhancement and replacement?
- What are concrete *progress signals* for this question?
- What “refusal rights” are necessary for learning to remain intact?

