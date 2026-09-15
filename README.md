# LeetEnum Homebrew tap

Install the shell implementation on macOS or Linuxbrew:

```sh
brew tap theleetsec/tap
brew install theleetsec/tap/leetenum
leetenum install
leetenum doctor
```

The formula uses a checksummed release source archive. Additional enumeration tools and massdns are installed by `leetenum install`; run `doctor` before an authorized assessment.

Updates:

```sh
brew update
brew upgrade theleetsec/tap/leetenum
```

Source: https://github.com/theleetsec/LeetSec-Tools

Newer Homebrew versions may require explicit formula trust before tapping. After reviewing the formula, run `brew trust --formula theleetsec/tap/leetenum`, then retry `brew tap theleetsec/tap`. Older versions without `brew trust` can omit this step.
