# Droploid Homebrew Tap

```bash
brew tap mhdibrahimcn/tap
brew trust mhdibrahimcn/tap        # Homebrew now requires trusting third-party taps
brew install droploid
```

Installs the [Droploid CLI](https://github.com/mhdibrahimcn/droploid-cli) — deploy Flutter, iOS &
Android apps to the App Store, TestFlight & Google Play. Pulls `node`, `cocoapods`, and `fastlane`.

Prefer no Homebrew trust step? Use the one-liner instead:

```bash
curl -fsSL https://raw.githubusercontent.com/mhdibrahimcn/droploid-cli/main/install.sh | bash
```
