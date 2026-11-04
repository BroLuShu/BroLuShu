![Lü Shu — design the recovery path](assets/cover.png)

# Design the recovery path

**Lü Shu · DevOps & systems architecture**

A fresh workspace for infrastructure notes, delivery experiments and the tools around keeping a system understandable.

The questions that shape this fictional engineer's work are simple: **How is it built? What tells us it is healthy? How do we recover it?**

## The operating notebook

| Before a change | While it runs | When something fails |
| --- | --- | --- |
| Clear boundaries, reproducible inputs and a rollback plan | Signals with enough context to explain behaviour | A recovery path that can be checked |

Each planned lab should leave a procedure someone else can repeat: the inputs, the signals to watch and the steps to recover.

## Small tools with an operational purpose

- **Backup Manifest** — create SHA-256 manifests and compare a copy with its source. Useful evidence for a file check; not a complete backup or disaster-recovery system.
- **Asset Dedupe** — identify exact duplicates by hash, without deleting the files. Inspect first, decide separately.
- **Link Sweep** — inspect internal links in a local documentation export before handing it to someone else.

These existing tools use **JavaScript / Node.js**. They are selected for this profile; public project repositories are being prepared.

## The next lab

The proposed infrastructure track is **Linux · containers · CI/CD · infrastructure as code · observability**.

1. Document one small deployment and its boundaries.
2. Make the build and configuration reproducible.
3. Exercise a rollback and a restore, and keep the evidence.

Later command-line experiments may explore Rust and Python.

> 🛠️ Designing systems that can recover.

[Browse the workspace](https://github.com/BroLuShu?tab=repositories)

---

<sub>Fictional developer persona · AI-illustrated avatar. Existing projects keep their original authors, licenses and commit history.</sub>
