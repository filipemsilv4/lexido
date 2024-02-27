![lexidoLogo](https://github.com/micr0-dev/lexido/assets/26364458/a403c155-274d-468e-86ff-88c81d33c481)
get things done_

## Introduction
Lexido is an innovative assistant for the Linux command line, designed to boost your productivity and efficiency. Powered by Gemini Pro 1.0 and utilizing the free API, Lexido offers smart suggestions for commands based on your prompts and importantly **your current environment**. Whether you're installing software, managing files, or configuring system settings, Lexido streamlines the process, making it faster and more intuitive.

## Features
- **Command Suggestions**: Simply type `lexido [prompt]` to get actionable command suggestions.
- **Cross-Platform**: Support for both Linux and macOS
- **Continued Conversations**: Use `lexido -c [prompt]` to continue a previous conversation, allowing for context-aware suggestions.
- **Piping Support**: Pipe commands into Lexido (e.g., `ls | lexido [prompt]`) for enhanced command list suggestions.
- **Efficiency**: Designed with efficiency in mind, Lexido helps you get things done NOW.

## Installation
Head to the [releases](https://github.com/micr0-dev/lexido/releases) tab to pick up a binary!

Currently, lexido is not on any package managers but if you would like that to change please contribute!

### Compile from source
Ensure you have Go installed on your system. Follow these steps to install Lexido:

1. Clone the Lexido repository:
```bash
git clone https://github.com/micr0-dev/lexido.git
```

2. Navigate to the Lexido directory:
```bash
cd lexido
```

3. Build the project:
```bash
go build
```

4. Optionally, move the Lexido binary to a location in your PATH for easy access.

## Usage
- To get command suggestions:
```bash
lexido "install teamspeak via docker"
```

- To continue with a previous prompt:
```bash
lexido -c "add more details or follow-up"
```

- To use with piping commands:
```bash
ls | lexido "what should I do with these files?"
```

## Contributing
Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
Distributed under the GNU Affero General Public License v3.0. See `LICENSE` for more information.

## Acknowledgements
- [Gemini Pro 1.0](https://deepmind.google/technologies/gemini/) for the LLM powering Lexido.

Made with 💚 by Micr0byte
