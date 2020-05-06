# Cloudflare DDNS
Provides a bash script to update Cloudflare DNS records to the IP of the machine executing the script; uses a restricted API token instead of a global API key.

A more in-depth tutorial can be viewed [here](https://nickperanzi.com/blog/cloudflare-ddns-with-token/)

# Usage
1. Place the `cloudflare-ddns.sh` script in your desired directory, either by directly downloading the raw file or cloning this repo.
2. Make the Cloudflare DDNS script executable: `chmod +x cloudflare-ddns.sh`
3. Change all variables in the script to the applicable parameters for your site
4. Test if this script runs: `./cloudflare-ddns.sh`; you should see output like:
```
IP changed to: 123.456.789.10
````