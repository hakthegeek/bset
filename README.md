# bset

`bset` is a simple box setup repository that installs common recon and pentest tooling into `~/tools`.

## What it does

- installs packages and dependencies for reconnaissance tooling
- clones a set of tools into `~/tools`
- adds shell aliases from `recon_profile` to your `~/.bash_profile`
- installs Go tools like `aquatone`, `httprobe`, `unfurl`, and `waybackurls`

## Tools installed

- dirsearch
- JSParser
- knock.py
- lazys3
- recon_profile
- sqlmap-dev
- Sublist3r
- teh_s3_bucketeers
- virtual-host-discovery
- wpscan
- webscreenshot
- massdns
- asnlookup
- unfurl
- waybackurls
- httprobe
- SecLists
- Sn1per Community Edition
- wfuzz

## Installation

```bash
git clone https://github.com/hakthegeek/bset.git
cd bset
chmod +x install.sh
./install.sh
```

## Notes

- The installer creates `~/tools` and clones repositories there.
- It requires `sudo` for system package installation.
- It also installs `awscli` and reminds you to configure AWS credentials if needed.

## Fork usage

This script prefers forks under `https://github.com/hakthegeek` for:

- `recon_profile`
- `JSParser`
- `lazys3`
- `lazyrecon`

If your fork does not exist yet, the installer will fall back to the upstream repository.

## Recommended next steps

1. Create your forks for the above repositories on GitHub.
2. Re-run the install script.
3. Verify that the tools are installed in `~/tools`.

## License

Use this repository at your own risk. No warranty is provided.
