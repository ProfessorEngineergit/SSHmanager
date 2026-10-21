# SSHmanager

Concept for a graphical SSH connection manager, with macOS as the initial target and Windows as a possible later port.

## Current status

The default branch contains this README and `LICENSE`. It does not contain an application, build configuration or installer. The items below are plans, not available features.

## Proposed scope

- Store named SSH connection profiles and group them by project.
- Launch a selected connection in a terminal.
- Explore importing `~/.ssh/config`, search and favourites after a basic prototype works.

The UI framework, storage format, credential handling and Windows support have not been selected or implemented in this branch. There is no installation command yet.

## Next steps

1. Choose a target platform and UI framework.
2. Implement a minimal connection list and terminal launch.
3. Document the storage and credential model and add tests for command construction.

## License

See [LICENSE](LICENSE), which contains the GNU GPL version 3 text.

## Development and AI assistance

The default-branch history includes contributions explicitly attributed to GitHub Copilot ([example](https://github.com/ProfessorEngineergit/SSHmanager/commit/410c962a9b9f7ac6b9eff303428d421a3df75eab)). This documents AI involvement in those contributions; it does not establish the origin of every line or independent validation. Existing author, co-author and session records are retained.
