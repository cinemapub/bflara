![bash_unit CI](https://github.com/cinemapub/bflara/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/cinemapub/bflara/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/cinemapub/bflara)
![GH stars](https://img.shields.io/github/stars/cinemapub/bflara)
![GH tag](https://img.shields.io/github/v/tag/cinemapub/bflara)
![GH License](https://img.shields.io/github/license/cinemapub/bflara)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# bflara

Quick Laravel Setup

## 🔥 Usage

```
Program : bflara  by p.forret@brightfish.be
Version : v0.0.3 (Nov 14 09:44:21 2025)
Purpose : Quick Laravel Setup
Usage   : bflara [-h] [-Q] [-V] [-f] [-L <LOG_DIR>] [-T <TMP_DIR>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -Q|--QUIET       : [flag] no output [default: off]
    -V|--VERBOSE     : [flag] also show debug messages [default: off]
    -f|--FORCE       : [flag] do not ask for confirmation (always yes) [default: off]
    -L|--LOG_DIR <?> : [option] folder for log files   [default: /Users/pforret/log/bflara]
    -T|--TMP_DIR <?> : [option] folder for temp files  [default: /tmp/bflara]
    <action>         : [choice] action to perform  [options: new,check,env,update]
    <input>          : [parameter] input file/text (optional)
                                                                                                                                                                                                    
### TIPS & EXAMPLES
* use bflara new to create new Laravel project and install all crucial add-ons
  bflara new
* use bflara check to check if this script is ready to execute and what values the options/flags are
  bflara check
* use bflara env to generate an example .env file
  bflara env > .env
* use bflara update to update to the latest version
  bflara update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar```

## ⚡️ Examples

```bash
> bflara -h 
# get extended usage info
> bflara env > .env
# create a .env file with default values
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install cinemapub/bflara

or with `git`

	$ git clone https://github.com/cinemapub/bflara.git
	$ cd bflara

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2025 Peter Forret
