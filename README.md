# Offline AI

An offline AI hub with two ways to get started: a **Simple** experience for straightforward local AI use, and a **Multi-Model** experience for working with different models.

> **Project goal:** make locally run AI easier to explore while keeping privacy, user choice, and offline use at the centre.

## Overview

Offline AI is a hub for accessing AI tools without depending on a hosted chatbot for every interaction. It is organised around two routes:

- **Simple version** — a streamlined starting point for people who want a straightforward AI experience.
- **Multi-model version** — a route for users who want to choose between, or work with, multiple AI models.

The exact features available depend on the implementation and the models configured on your device.

## Why Offline AI?

- **Privacy-minded:** local inference can keep prompts and files on your own device.
- **More control:** choose the model and setup that suit your needs.
- **Offline potential:** once the required application components and model files are available locally, compatible workflows can run without an internet connection.
- **Flexible:** different models can offer different trade-offs in speed, capability, memory use, and response quality.

## Offline use

“Offline” depends on how the app is configured. You may need an internet connection initially to obtain the application dependencies or download model files. Features that call external APIs or online services will still require a connection.

For genuinely offline use, make sure the selected model and all required runtime files are stored locally, and avoid configuring external services.

## Getting started

1. Open the project and review the files and setup instructions included in the repository.
2. Install the runtime and dependencies required by the implementation.
3. Make sure any required model files are available locally.
4. Start the application using the command or launch method provided by the project.
5. Choose the **Simple** or **Multi-Model** experience and configure the models you want to use.

> **Note:** Project-specific installation commands and supported model requirements will be documented here once they are confirmed against the repository's implementation. Avoid assuming that every model runs on every device; memory, processor, and accelerator requirements vary.

## Hardware considerations

Local AI performance depends on several factors:

- **RAM / VRAM:** larger models generally require more memory.
- **Processor and accelerator:** supported GPUs or other accelerators can improve performance, depending on the runtime.
- **Model size and quantisation:** smaller or quantised models are often more practical on everyday computers.
- **Context length:** longer conversations can increase memory use.

If a model is too slow or fails to load, try a smaller compatible model and check the runtime's requirements.

## Privacy and security

- Keep API keys and other secrets out of source control.
- Check model licences and terms before redistributing model files.
- Review the settings of any optional online integrations.
- Remember that “local” processing only applies to features that actually run on-device; external API calls send data to the configured service.

## Project status

Offline AI is under development. Features, model compatibility, and setup instructions may change as the project evolves. Check the repository for the latest implementation and updates.

## Contributing

Suggestions, bug reports, and improvements are welcome. When reporting an issue, include:

- Your operating system and hardware (avoid sharing private or identifying details).
- The steps needed to reproduce the issue.
- Any relevant error message, with secrets and personal data removed.

## Licence

A licence has not been specified in this README. Check the repository for a `LICENSE` file before reusing or redistributing the project.
