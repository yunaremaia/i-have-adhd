# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.0] - 2026-10-07

### Initial public release

A skill for your coding assistant that stops it from burying the answer. Action first. Steps numbered. No "Hope this helps!"

#### What's included

- **Core skill** (`skills/i-have-adhd/SKILL.md`): 10 rules for ADHD-friendly output — lead with the next action, number multi-step tasks, restate state every turn, suppress tangents, give specific time estimates, make wins visible, cap lists to 5 items, no preamble/recap/closers.
- **Multi-assistant support**: Extensions for Claude Code, Codex, Gemini, OpenCode, Qwen, and Kimi.
- **Always-on hooks**: Automatic activation without manual invocation.
- **Evaluation harness**: Scenario-based evals with a judge script to measure output quality.
- **Test suite**: 8 test files covering install docs, judge, evals, scenario eval, hooks, and plugin packaging.
- **Documentation**: README in 9 languages (English, Chinese, Spanish, Portuguese, Japanese, Vietnamese, Korean, Persian, Thai), INSTALL.md with per-assistant setup instructions, and CONTRIBUTING.md.
- **Plugin manifests**: `plugin.json`, `package.json`, and per-assistant config files for marketplace distribution.

#### Rules summary

1. Lead with the next action.
2. Number multi-step tasks.
3. End with one concrete next step.
4. Suppress tangents.
5. Restate state every turn.
6. Give specific time estimates (minutes, not "a bit").
7. Make wins visible.
8. Matter-of-fact errors.
9. Cap lists to 5 items.
10. No preamble. No recap. No closers.

#### License

MIT
