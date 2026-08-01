# The Elements of Style - Claude Code Plugin

A Claude Code plugin providing William Strunk Jr.'s *The Elements of Style* (1918) as a reference skill for clear, precise writing.

## Purpose

This plugin gives Claude access to Strunk's foundational writing guidance when working on documentation, user-facing text, or any prose that needs clarity and proper style.

## What's Inside

The plugin provides:

- **Skill**: `writing-clearly-and-concisely` - Guidance on when and how to use Strunk's rules
- **Reference**: Complete 1918 text with all rules, examples, and usage guidance (~12,000 tokens)

The reference contains:

1. **Elementary Rules of Usage** - Seven fundamental grammar and punctuation rules
2. **Elementary Principles of Composition** - Eleven rules for clear, effective writing
3. **Words and Expressions Commonly Misused** - An alphabetical guide to usage pitfalls

## Usage

Once installed, Claude will automatically use the `writing-clearly-and-concisely` skill when appropriate. The skill:

- Warns about the 12,000-token reference size
- Lists all rules at a glance
- Suggests dispatching a subagent for copyediting when context is limited
- Only loads the full reference when actively writing or editing prose

## Source

This text is in the public domain. The original 1918 edition by William Strunk Jr. was obtained from Project Gutenberg and converted to clean markdown format.

- **Original Source**: [Project Gutenberg #37134](https://www.gutenberg.org/files/37134/37134-h/37134-h.htm)
- **Author**: William Strunk Jr.
- **Publication**: 1918
- **License**: Public Domain (see [LICENSE.md](LICENSE.md))

## License

See [LICENSE.md](LICENSE.md). The 1918 Strunk text is public domain. Plugin packaging and original skill guidance are also public domain, matching `.claude-plugin/plugin.json`.
