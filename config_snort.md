## Snort Configuration Guide

1. Install Snort: `sudo apt install snort`
2. Replace default config with our custom rules in `snort_rules.conf`
3. Start Snort: `sudo snort -A console -q -c /etc/snort/snort.conf -i eth0`