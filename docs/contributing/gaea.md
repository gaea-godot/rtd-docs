---
weight: 10
---

# Gaea

Thanks for contributing to Gaea.

This page focuses on **addon code contributions**.

## Before You Start

- Check existing [issues](https://github.com/gaea-godot/gaea/issues) first.
- Keep your pull request focused on one problem whenever possible.
- Prefer small, reviewable changes over large mixed refactors.

If you are not sure where your change belongs, open a draft PR early and ask for guidance.

You always can ask for help in the Graveyard Discord server: [https://discord.gg/V7UsX54V49](https://discord.gg/V7UsX54V49)

## Project Structure

Main addon source code is in:

- `addons/gaea/`

The root addon entry point is `addons/gaea/gaea.gd`.

Most contributions will touch one of these areas:

- `addons/gaea/editor/`: editor UI and tooling.
- `addons/gaea/runtime/`: graph execution, resources, renderers, node logic.
- `addons/gaea_documentation_toolkit`: internal plugin to generate graph node documentation pages and images from node scripts. Not exported as part of the main plugin.
- `testing/`: GdUnit test suites.

## Development Workflow

1. Fork the repository and create a branch from the target branch.
2. Implement your change in the relevant `editor/` or `runtime/` area.
3. Add or update tests under `testing/` when behavior changes.
4. Run local checks using [GdUnit4](https://github.com/godot-gdunit-labs/gdUnit4).
5. Open a pull request with a clear description and linked issue.

## Coding Guidelines

- Follow the Godot [GDScript style guide](https://docs.godotengine.org/en/stable/tutorials/scripting/gdscript/gdscript_styleguide.html) and [pull request guidelines](https://contributing.godotengine.org/en/latest/pull_requests/pull_request_guidelines.html).
- Avoid unrelated formatting-only edits in feature PRs.
- Add documentation comments for non-obvious logic.

## Testing

Gaea uses [**GdUnit4**](https://github.com/godot-gdunit-labs/gdUnit4) tests in `testing/`.

Test groups are organized as:

- `testing/generation/`
- `testing/graph_nodes/`
- `testing/rendering/`
- `testing/other/`

You can run tests with the included GdUnit scripts:

- Windows: `addons/gdUnit4/runtest.cmd`
- Linux/macOS: `addons/gdUnit4/runtest.sh`

Both scripts accept a Godot binary path through `--godot_binary` (or `GODOT_BIN`).

## CI Checks You Should Expect

Pull requests run formatting and test workflows from `.github/workflows/`, including:

- GDLint checks for `addons/gaea/editor/` and `addons/gaea/runtime/`
- GdUnit test suites for generation, nodes, renderers, and other categories

Even if your change is small, make sure it does not break existing tests.

## Pull Request Checklist

Before opening your PR:

1. Your branch contains only related changes.
2. New/updated behavior is covered by tests when relevant.
3. Code follows style expectations and passes linting.
4. The PR description explains what changed and why.
5. The PR links the issue it fixes (when applicable).
