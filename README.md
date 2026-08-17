# homebrew-agentskillmap

Homebrew tap for [agentskillmap](https://github.com/TakasiVenkataSandeep-08/agentskillmap).
The project is `agentskillmap`; the command it installs is `skillmap`.

```bash
brew install TakasiVenkataSandeep-08/agentskillmap/skillmap
```

`Formula/skillmap.rb` is **generated**, by `scripts/homebrew-formula.sh` in the main
repository, and attached to every release with the checksums of that release's archives. Do
not edit it by hand: update it by copying the `skillmap.rb` asset from the newest release.

The formula's `test do` block deliberately asserts more than a version banner. The binary
carries its own detection rules, so a release that embedded none would install cleanly and
report every project in the world clean; the test asserts it can still name a rule.
