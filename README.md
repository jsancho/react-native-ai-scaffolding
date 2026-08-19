# React Native Scaffolding for AI Agents

This configuration assumes that React 19 is being used with Expo SDK 57.
If you upgrade to a more recent version, make the necessary adjustments to this file as well as [AGENTs.md](./AGENTS.md) and [REACT.md](./docs/REACT.md).

The `reactCompiler` must be set to `true` in the [app.json](./app.json) file

## AGENTS.md

The [AGENTS.md](./AGENTS.md) file must be updated with a brief project description and the basic commands to build, test, and run the project.

### Claude

This template is agent-agnostic, to use with Claude you can create a symlink from AGENTS.md to CLAUDE.md

`ln -s AGENTS.md CLAUDE.md`

## Folder Structure

The [ARCHITECTURE](./docs/ARCHITECTURE.md) contains a barebones project structure that follows a feature-based layout.

Ensure that this structure matches your preferences to avoid confusing the agent with poor file mapping.

## TODO

[ ] React guidelines; consider splitting the rules into separate files to not overwhelm the context.

Additionally, we could also recommend using comprehensive skills, such as

- [React Native Best Practices - Callstack](https://github.com/callstackincubator/agent-skills/blob/main/skills/react-native-best-practices/SKILL.md)
- [React Best Practices](https://github.com/davila7/claude-code-templates/tree/main/cli-tool/components/skills/development/react-best-practices/rules)

[ ] Animations guidelines; consider using the [CallStack skill](https://github.com/callstackincubator/agent-skills/blob/main/skills/react-native-best-practices/SKILL.md) instead.

## References

[A Complete Guide to Agents.MD - Matt Pocock](https://www.aihero.dev/a-complete-guide-to-agents-md)

[React Native Implementation Playbook](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/skills/web-development/react-native-architecture/resources/implementation-playbook.md)

[React Best Practices](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/skills/development/react-best-practices/AGENTS.md)

[React Performance Best Practices - by Vercel](https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/skills/development/react-best-practices/SKILL.md)

[AI TEMPLATES](https://aitmpl.com/) Is a great starting point to find agent skills and template files.
