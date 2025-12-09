# homebrew-tap

This is a [Homebrew](https://brew.sh/) tap repository containing custom formulae for installing software on macOS and Linux.

## What is a Homebrew Tap?

A Homebrew tap is a third-party repository that provides additional formulae (package definitions) beyond those available in Homebrew's core repository. Taps allow developers to distribute their software through Homebrew without needing to add it to the official Homebrew core.

## Installation

To use the formulae in this tap, first tap this repository:

```bash
brew tap illarion/tap
```

Once tapped, you can install any formula from this repository just like you would install any other Homebrew package:

```bash
brew install <formula-name>
```

## Available Formulae

Formulae in this tap will be added to the `Formula/` or `Casks/` directories. Check those directories or run the following command to see available packages:

```bash
brew search illarion/tap/
```

## Updating

To update the tap and get the latest formulae:

```bash
brew update
```

## Uninstalling

To remove this tap from your Homebrew installation:

```bash
brew untap illarion/tap
```

## Contributing

If you have issues or suggestions for formulae in this tap, please open an issue or pull request on this repository.
