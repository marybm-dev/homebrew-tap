# marybm-dev/tap

Homebrew formulae for [VOFocus](https://github.com/marybm-dev/vofocus), which drives
real VoiceOver on iOS Simulators and devices from agents and CI.

```sh
brew install marybm-dev/tap/vofocus
claude mcp add vofocus -- "$(brew --prefix)/bin/vofocus-mcp"
```

VOFocus needs macOS and Xcode 27 or later. It builds from source, and builds its
runner with Xcode the first time it starts.

Report problems in the [VOFocus repository](https://github.com/marybm-dev/vofocus/issues).
