# Word Nuance Tutor

A lightweight AI vocabulary coach for advanced English learners and writers. Explore why a writer chooses one word over another, with concise comparison tables and optional interactive practice.

## Features

- **Learn:** Understand a word in context, including connotation, register, collocations, and close alternatives.
- **Practice:** Write your own sentences and get focused feedback on naturalness and precision.
- **Review:** Quiz yourself on previously studied vocabulary when you provide a word list or accessible study history.
- **Clean output:** Short Markdown tables for explanations; exercises stay in the chat.

## Install from Terminal (Codex)

After uploading this repository to GitHub, run:

```bash
git clone https://github.com/YOUR_USERNAME/word-nuance-tutor.git
mkdir -p ~/.codex/skills/word-nuance-tutor
cp word-nuance-tutor/SKILL.md ~/.codex/skills/word-nuance-tutor/SKILL.md
```

Replace `YOUR_USERNAME` with your GitHub username. Restart Codex or open a new session so it discovers the skill.

### One-command installation (after the repository is published)

```bash
mkdir -p ~/.codex/skills && git clone https://github.com/YOUR_USERNAME/word-nuance-tutor.git ~/.codex/skills/word-nuance-tutor
```

Use this instead of the commands above on a fresh installation, **not both**. If the target directory already exists, use the update instructions below.

### Update the installed skill

If you used the one-command `git clone` installation:

```bash
git -C ~/.codex/skills/word-nuance-tutor pull --ff-only
```

If you used the copy-based installation, pull the repository where you cloned it and copy `SKILL.md` again:

```bash
git -C word-nuance-tutor pull --ff-only
cp word-nuance-tutor/SKILL.md ~/.codex/skills/word-nuance-tutor/SKILL.md
```

> **Note:** Changes on GitHub do not automatically update your locally installed copy. The commands above are for Codex's local skill directory; installing a local skill does not automatically install it in the ChatGPT web app.

## Use

Try asking Codex:

- `Use word-nuance-tutor: Why did the writer choose "barreling" rather than "passing" in this sentence?`
- `Use word-nuance-tutor to compare "flake on" and "leave hanging".`
- `Use word-nuance-tutor in Practice Mode. Check my sentence: "Time slipped through my hands."`

## Files

- [`SKILL.md`](SKILL.md) — skill metadata, behavior, output format, and interaction rules.
