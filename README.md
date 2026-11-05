# Koki Short Video Skill

[![English](https://img.shields.io/badge/English-2563EB?style=for-the-badge)](README.md) [![简体中文](https://img.shields.io/badge/简体中文-DC2626?style=for-the-badge)](README.zh-CN.md)

Edit vertical talking-head videos with clean speech, language-aware captions, topic visuals, and an editable timeline.

A standalone skill from my own creator workflow, shared as a configurable public edition. Instructions and workflow references are available in English and Simplified Chinese.

## What it does

- Conservative voice cleanup before speech editing.
- Remove failed takes and obvious repetition while keeping meaning and natural delivery.
- English word groups and Chinese semantic phrases use different caption rhythms.
- Add a first-frame cover, opening title, relevant visuals, and optional configured closing.
- Verify faces, captions, visuals, and timing in the composed output.

## Install & use

Send [this repository](https://github.com/leilei926524-tech/koki-short-video-skill) to your agent and ask:

```text
Install the skill in skills/vertical-talking-head from this repository. If a skill with the same name already exists, keep it and tell me about the conflict before replacing it.
```

Alternatively, download the repository and copy the complete `skills/vertical-talking-head` folder into your tool's personal skill directory. Use a tool that supports Agent Skills; editing also needs an available editor connection.

```text
Use $vertical-talking-head to edit this vertical talking-head video. Clean the speech, use English word groups or natural Chinese phrases for captions, add relevant visuals, and save an editable project.
```

The default [SKILL.md](skills/vertical-talking-head/SKILL.md) is in English. A [Chinese edition](skills/vertical-talking-head/SKILL.zh-CN.md) is included; references contain both languages. Output language follows your request.

## Make it yours

Copy [creator.example.yaml](creator.example.yaml) to `creator.local.yaml` in your working project and fill in your name, media directories, and preferences. The agent reads this file; it does not connect accounts or execute by itself. Missing private media or closing text should be skipped or reported, never borrowed from the original author. See [PRIVACY.md](PRIVACY.md).

## Tools

These workflows primarily use [ChatCut](https://chatcut.io/docs/web-plugin). Connect the official editor tools in your agent environment first. This repository contains my custom workflow, not the official ChatCut plugin or its bundled skills. Save an editable project by default; export or publish when requested. External services may have their own fees and terms.

## About Koki & contact

Created by **Koki**, creator of Anti-Distill Skill and initiator of Social Coding.

[Website](https://kokiai.net/) · [X / Twitter](https://x.com/kokisanai) · [Instagram](https://www.instagram.com/kokisanai/) · [YouTube](https://www.youtube.com/@kokiainet) · [LinkedIn](https://www.linkedin.com/in/koki-x-309815217/) · [Substack](https://kokimemo.substack.com/)

For collaborations or questions, message me on [X](https://x.com/kokisanai) or [LinkedIn](https://www.linkedin.com/in/koki-x-309815217/). For a skill bug or suggestion, open an issue in this repository. Please keep private media and account details out of public issues.

## Other creator skills

- [Koki Writing Skill](https://github.com/leilei926524-tech/koki-writing-skill)
- [Koki Long Video Skill](https://github.com/leilei926524-tech/koki-long-video-skill)

## License

Original skill instructions and adapter code are licensed under [MIT](LICENSE). Third-party products, fonts, media, and services retain their own licenses and terms.
