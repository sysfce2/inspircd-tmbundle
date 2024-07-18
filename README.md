## InspIRCd TextMate Bundle

## About

This bundle implements syntax highlighting for various InspIRCd formats.

### Installation

#### Sublime Text

Assuming that CONFIGDIR is set to the appropriate directory for your platform:

```sh
mkdir -p ${CONFIGDIR}/Packages/User
cd ${CONFIGDIR}/Packages/User
git clone https://github.com/inspircd/tmbundle.git InspIRCd.tmbundle
```

#### TextMate

```sh
mkdir -p ~/Library/Application\ Support/TextMate/Bundles
cd ~/Library/Application\ Support/TextMate/Bundles
git clone https://github.com/inspircd/tmbundle.git InspIRCd.tmbundle
```

### To Do

- Highlight named color escapes in the MOTD grammar.
- Highlight XML entities in the configuration grammar.

### License

This bundle is licensed under the same license as InspIRCd (GPLv2).
