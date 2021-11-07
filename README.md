# Capture One Homebrew Tap

This is a [Homebrew] [tap] for [Capture One].

## How to Install

Install the tap via:

```bash
brew tap andrewsardone/homebrew-capture-one
```

Then you can install the Capture One application:

```bash
brew install andrewsardone/capture-one/capture-one
```

[Homebrew]: https://brew.sh
[tap]: https://docs.brew.sh/Taps
[Capture One]: https://www.captureone.com/en

## Frequently Asked Questions (FAQ)

### Why is this not in homebrew-cask?

Back in [Homebrew/homebrew-cask#80951], Capture One was removed because its
download files what's considered [walled] and not easily accessible for
verification. By [Homebrew policy][hp], they can't be accepted into
homebrew-cask. See [Homebrew/homebrew-cask#113922].

[Homebrew/homebrew-cask#80951]: https://github.com/Homebrew/homebrew-cask/pull/80951,
[walled]: https://docs.brew.sh/Acceptable-Casks#finding-a-home-for-your-cask
[hp]: https://docs.brew.sh/Acceptable-Casks#unofficial-vendorless-and-walled-builds
[Homebrew/homebrew-cask#113922]: https://github.com/Homebrew/homebrew-cask/pull/113922
