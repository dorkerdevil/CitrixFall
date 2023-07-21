
# CVE-2023-3519 Citrix Vulnerability NSE Script for Nmap

This Nmap NSE script checks for the CVE-2023-3519 vulnerability in Citrix Gateway and Citrix AAA.

## Installation

To use this script, you will need to have Nmap installed. You can download Nmap from [here](https://nmap.org/download.html).

Copy the `cve-2023-3519-checker.nse` file to your Nmap scripts directory. This is typically `/usr/share/nmap/scripts/` on a Unix-based system.

You can verify the script is recognized by Nmap by running:

```shell
nmap --script-updatedb
```

## Usage
To use this script, run the following command:

```shell
nmap --script cve-2023-3519-checker --script-args checktype=service <target>
```

Replace <target> with the IP address or hostname you want to scan.

## Note
Feel Free to open issues or anything you want me to add in like new checks .

## License
This project is licensed under the same license as Nmap - GPLv2.

## Author
[Ashish Kunwar](https://twitter.com/D0rkerDevil)

