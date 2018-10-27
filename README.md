## InspIRCd TextMate Bundle

## About

This bundle implements syntax highlighting for various InspIRCd formats.

### Installation

#### TextMate 2

```sh
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/inspircd/inspircd-tmbundle.git InspIRCd.tmbundle
```

### To Do

- Fix some minor omissions in the configuration highlighter:
  - Automatically detect the configuration format.
  - Escape codes (`<config format="compat">`).
  - XML entities (`<config format="xml">`).

### License

This bundle is licensed under the same license as InspIRCd (GPLv2).
