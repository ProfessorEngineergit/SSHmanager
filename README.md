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

## Documentation

GitHub Copilot contributed to the documentation ([record](https://github.com/ProfessorEngineergit/SSHmanager/commit/3a76518810311205e9c89489cd7358646234b842)). This does not establish AI-generated application code.
