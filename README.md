# Agents and Skills

Five Claude Code agents for reviewing pull requests and related code:

| Agent | Focus |
| --- | --- |
| `security-auditor` | Security vulnerabilities |
| `php-reviewer` | PHP, Laravel, and WordPress code quality |
| `wp-reviewer` | WordPress plugin and theme standards |
| `react-reviewer` | React and Next.js code quality |
| `a11y-checker` | Accessibility issues |

## Documentation skill

[`skills/simple-docs/SKILL.md`](skills/simple-docs/SKILL.md) guides an
assistant to write or revise documentation that readers can follow on the first
read. It uses the shared Agent Skills format and has no bundled scripts or tools.

To use it in Codex, copy `skills/simple-docs/` to
`~/.agents/skills/simple-docs/` and invoke `$simple-docs`. To use it in
Claude Code, copy the same directory to `~/.claude/skills/simple-docs/`
and invoke `/simple-docs`.

See `LICENSE` for the MIT license and copyright notice.
