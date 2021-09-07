<h1 align=center><code>dora</code></h1></code>
<p align=center>
  <img src="images/dora_small.png"/>
</p>

## Installation
###
```console
# clone the repo
$ git clone https://github.com/sdushantha/dora.git

# change the working directory to sherlock
$ cd dora 

# install dora
$ python3 setup.py install --user
```

## Usage

```console
$ dora --help
usage: dora [options]

positional arguments:
  PATH                  Path to directory or file to scan

optional arguments:
  -h, --help            show this help message and exit
  --rg-path RG_PATH     Specify path to ripgrep
  --rg-arguments RG_ARGUMENTS
                        Arguments you want to provide to ripgrep
  --json JSON           Load regex data from a valid JSON file (default: db/data.json)
  --verbose, -v, --debug, -d
                        Display extra debugging information
  --no-color            Don't show color in terminal output
```
[![Open in Cloud Shell](https://user-images.githubusercontent.com/27065646/92304704-8d146d80-ef80-11ea-8c29-0deaabb1c702.png)](https://console.cloud.google.com/cloudshell/open?git_repo=https://github.com/sdushantha/dora)
[![Run on Repl.it](https://user-images.githubusercontent.com/27065646/92304596-bf719b00-ef7f-11ea-987f-2c1f3c323088.png)](https://repl.it/github/sdushantha/dora)

## Contributing
You are more than welcome to contribute in one of the following ways:
- Add or improve existing regular expressions for matching API keys
- Add or improve the `info` in the JSON data for an API key to better help the user getting a valid bug bounty report when reporting an API key they have found
- Fix bugs (kindly refrain from creating bugs)

## Credits

Original creator - [Siddharth Dushantha](https://github.com/sdushantha)

Many of the regular expressions where taken from the following GitHub repositories:
- [truffleHogRegexes](https://github.com/dxa4481/truffleHogRegexes/blob/master/truffleHogRegexes/regexes.json) by [dxa4481](https:/github.com/dxa4481)
- [secretx](https://github.com/harry1080/secretx/blob/master/patterns.json) by [harry1080](https:/github.com/harry1080)
- [gitGraber](https://github.com/hisxo/gitGraber/blob/master/tokens.py) by [hisxo](https://github.com/hisxo)
- [shhgit](https://github.com/eth0izzle/shhgit/blob/3ce441853d999dacf6e20e59b116c135dcdd0c68/config.yaml) by [eth0izzle](https://github.com/eth0izzle)
- [w13scan](https://github.com/w-digital-scanner/w13scan/blob/master/W13SCAN/scanners/PerFile/js_sensitive_content.py) by [w-digital-scanner](https://github.com/w-digital-scanner)
- [SecretFinder](https://github.com/m4ll0k/SecretFinder/blob/master/BurpSuite-SecretFinder/SecretFinder.py) by [m4ll0k](https://github.com/m4ll0k)
- [nuclei-templates](https://github.com/projectdiscovery/nuclei-templates/blob/master/exposed-tokens/generic/credentials-disclosure.yaml) by [projectdiscovery](https://github.com/projectdiscovery)
- [AdvancedKeyHacks](https://github.com/udit-thakkur/AdvancedKeyHacks/blob/master/hackcura_apikey_hacks.sh) by [udit-thakkur](https://github.com/udit-thakkur)
- [pentest-tools](https://github.com/gwen001/pentest-tools/blob/master/keyhacks.sh) by [gwen001](https://github.com/gwen001)
- [gitleaks](https://github.com/zricethezav/gitleaks) by [zricethezav](https://github.com/zricethezav)
- [dalfox](https://github.com/hahwul/dalfox/blob/1f32f3494e1aa3312f84b3e2a836eb61a9ae9aac/pkg/scanning/grep.go) by [hahwul](https://github.com/hahwul)

Majority of the exploitation/POC methods were taken from [keyhacks](https://github.com/streaak/keyhacks) repository by [streaak](https://github.com/streaak)
