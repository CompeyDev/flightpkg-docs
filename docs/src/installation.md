# Installation

We don't have an official release of Flight yet, however, if you would like to give it a try, feel free to follow the steps below to install a alpha release.
<br>

### Linux:

#### Shell script (Recommended):
```bash
$ curl -qL https://raw.githubusercontent.com/flightpkg/flight/main/install.sh | bash
```

If the installer doesn't set your environment variables, add it using:

```bash
$ echo "export PATH=~/flight/bin:$PATH" >> YOUR_SHELL_CONFIG_HERE
```
...and restart your shell to use the command `flight`

### Windows:
Download the latest release from GitHub Releases and run in the installer.

## Build From Source
Prerequisites: Git, Yarn and/or NPM, NodeJS.

## Steps

1. Clone the repository using git.

```bash
$ git clone https://github.com/flightpkg/flight
```

2. CD into the `flight` directory.

```bash
$ cd flight
```

3. Install @vercel/ncc globally if it isnt already installed

```bash
$ npm i @vercel/ncc
$ yarn global add @vercel/ncc
```

4. Run the build script
```bash
$ npm run compile && npm run build
$ yarn compile && yarn build
```

5. CD into the dist/js directory, then init.
```bash
$ cd dist/js
-------------
$ npm init 
$ yarn init
```

<br>

## 🕵️‍♂️ VirusTotal Scans
| **Platform** | **VirusTotal Scan**    |
| -------  | ------------------ |
| Windows  | <a href="https://www.virustotal.com/gui/file/f7748343325785c81476bc802441010b624b3bbd989770a8b3ee5b694a7d5ed7/detection"> <img src="https://img.shields.io/badge/dynamic/json?label=Detections&query=%24.positives&url=https%3A%2F%2Fupdates.flightpkg.js.org%2Fapi%2Fvirustotal-win"> </a> |

<br>

## License

Apache-2.0 © flightpkg - see the [community/LICENSE.md](LICENSE) file for details.