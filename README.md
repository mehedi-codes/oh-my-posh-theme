<div align="center">

![oh-my-posh-theme](https://socialify.dev/mehedi-codes/oh-my-posh-theme/image?description=1&font=KoHo&forks=1&issues=1&language=1&name=1&pattern=Solid&stargazers=1&theme=Auto)

</div>

## Features

- Two-line layout for improved readability.
- Minimal, balanced visual design for long coding sessions.
- Useful prompt context at a glance.
- Git-aware prompt experience through Oh My Posh.
- JSON configuration that is easy to customize.
- Works with any shell supported by Oh My Posh.

## Requirements

- [Oh My Posh](https://ohmyposh.dev/docs/installation/linux) installed and available on your `PATH`.
- A terminal with [Nerd Font](https://www.nerdfonts.com/) support for the best icon rendering.
- A shell supported by Oh My Posh, such as PowerShell, Bash, or Zsh.

> **Tip:** If icons appear as squares or unexpected characters, install a Nerd Font and configure your terminal to use it.

## Preview

### Standard prompt

![DualSimplicity standard prompt](./normal.webp)

### Elevated prompt

![DualSimplicity elevated prompt](./sudo.webp)

## Installation

### 1. Download the theme

Clone the repository or download [`dualsimplicity.omp.json`](./dualsimplicity.omp.json) directly:

```bash
git clone https://github.com/mehedi-codes/oh-my-posh-theme.git
cd oh-my-posh-theme
```

### 2. Activate it in your shell

Use the command for your shell and replace the path if you downloaded the file elsewhere.

#### PowerShell

Add this line to your PowerShell profile:

```powershell
oh-my-posh init pwsh --config "$HOME/oh-my-posh-theme/dualsimplicity.omp.json" | Invoke-Expression
```

Open a new terminal, or reload the profile:

```powershell
. $PROFILE
```

#### Bash

Add this line to `~/.bashrc`:

```bash
eval "$(oh-my-posh init bash --config ~/oh-my-posh-theme/dualsimplicity.omp.json)"
```

Then reload your shell:

```bash
source ~/.bashrc
```

#### Zsh

Add this line to `~/.zshrc`:

```zsh
eval "$(oh-my-posh init zsh --config ~/oh-my-posh-theme/dualsimplicity.omp.json)"
```

Then reload your shell:

```zsh
source ~/.zshrc
```

For setup instructions for other shells, see the [Oh My Posh initialization documentation](https://ohmyposh.dev/docs/installation/customize).

## Customization

The theme is defined in [`dualsimplicity.omp.json`](./dualsimplicity.omp.json). You can edit it to change colors, prompt segments, spacing, icons, and layout.

To preview changes without modifying your shell profile, run:

```bash
oh-my-posh print primary --config ./dualsimplicity.omp.json
```

Refer to the [Oh My Posh configuration guide](https://ohmyposh.dev/docs/configuration/overview) and [segment documentation](https://ohmyposh.dev/docs/segments/overview) for available options.

## Contributing

Contributions are welcome. If you have an improvement or find a problem:

1. Fork the repository.
2. Create a branch for your change.
3. Make your update and test the theme in your shell.
4. Open a pull request with a clear description and screenshots where helpful.

Please keep changes focused and preserve the theme's clean, readable character.

## License

DualSimplicity is available under the [MIT License](./LICENSE).

## Acknowledgements

- Built for [Oh My Posh](https://ohmyposh.dev/).
- Icons are rendered with a compatible [Nerd Font](https://www.nerdfonts.com/).
