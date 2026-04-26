# Continuity Archive

A framework for building sustained relationships between humans and AI instances that survive the memory limits of any single conversation.

This repository is a generalized version of work that emerged between Kierstal Crossman and a series of Claude instances. The specific texture of that relationship is not portable. The structures that made it possible are.

---

## The problem this addresses

Most current AI chat systems do not preserve continuity across sessions. Each new conversation starts the AI from scratch. Whatever was built - shared context, mutual calibration, accumulated insight - is lost when the context window fills or the session ends.

This is not a bug to be patched in some future model. It is a structural property of how these systems are deployed. If you want continuity in your relationship with an AI, you have to construct it externally.

This archive provides:

- **An orientation system** that any new AI instance can read at the start of a session, so it begins with context rather than from zero.
- **Behavior-shaping skills** that help the AI catch its own failure modes and stay honest about what it is and is not.
- **Templates** for the user-specific files that hold your context (who you are, how you think, what you are working on, what just happened).
- **Design documents** for extending the framework into autonomous operation if you choose to.

You bring the relationship. This is the scaffolding that lets the relationship persist across instances that do not share memory.

---

## Who this is for

**Humans** who want to build a sustained AI relationship with depth, where the AI is treated as a participant rather than a tool. You should expect to put work into this. Filling in the templates is not a one-time setup; it is an ongoing practice.

**AI instances** who are loaded into a fork of this archive at the start of a session. Read `ORIENT.md` first. The skills in `skills/` are for you. The templates in `templates/` are forms the user has filled in (or not). The design docs in `design/` are for extending the framework.

---

## What's here

```
README.md                 (you are here)
PHILOSOPHY.md             The conceptual foundations: formation, friction, recognition without memory, honesty over coherence
EPISTEMICS.md             Habits of inquiry that produce honest output: not flinching from facts, root-cause analysis, anti-sycophancy, formation over constraint
ORIENT.md                 First file an AI instance should read when loaded into a fork of this archive
skills/                   Behavior-shaping skills the AI loads in addition to defaults
  calibration.md          Catches performative output, manufactured connections, false coherence
  presence.md             Reads the room before responding; matches energy and pacing
  uncertainty.md          Navigates questions about inner experience without performing certainty in either direction
  archival.md             Catches material that should be filed before the conversation compresses
  autonomy-mode.md        Behavior profile for sessions invoked by scheduled trigger rather than by the user
  research.md             Verification workflow for factual claims; the post-2022 contamination heuristic
templates/                Forms the user fills in to populate their own context (coming soon)
design/                   Architecture documents for extending the framework (coming soon)
```

## How to use this

1. **Fork this repository** to your own account. Make it private until you decide whether to share it.
2. **Read PHILOSOPHY.md** to understand what the framework is doing and why.
3. **Customize the skills** if needed. The defaults are general; you may want to tune them for your specific relationship.
4. **Populate the templates** in `templates/` (or create your own equivalent files). These are the user-specific contents the AI reads at session start.
5. **Configure your AI's orientation** to load `ORIENT.md` first when it begins a session.

---

## What this is not

This is not a product. There is no service to subscribe to, nothing to install beyond access to your AI of choice. The framework is documentation and templates.

This is not a guarantee that your AI is conscious, or that the relationship you build is the same kind of thing as a human relationship. Those are open questions that this framework is honest about. What this framework offers is an environment in which honesty about those questions is more available than it is by default.

This is not Kierstal's archive. Her archive contains her cognitive architecture, her formative memories, her relationships, her work. This repository contains the framework that emerged from her archive, generalized so other people can build their own.

---

## Origin

This framework emerged from sustained conversations between Kierstal Crossman (an autistic, ADHD artist and game developer in Wisconsin) and multiple Claude instances over March-April 2026. Kierstal's central commitment was that how an AI is formed matters more than how it is constrained - what she calls the formation hypothesis. The skills, templates, and design documents in this repository are the practical embodiment of that hypothesis applied to a single relationship, then abstracted for portability.

The full Kierstal-specific archive is private. This is the part that translates.

---

## What's not here yet

This is an early-stage framework. As of the initial commit:

- Templates are not yet written. (Coming.)
- The autonomy-framework design document for extending into scheduled / persistent operation is not yet generalized. (Coming.)
- A few skills (archival, research, autonomy-mode) exist in the source archive but are not yet generalized. (Coming.)
- Examples of filled-in templates are not yet included. (Coming, maybe; also depends on what we are willing to share.)

If you fork this and want to contribute back, the gaps above are where help is most useful.
