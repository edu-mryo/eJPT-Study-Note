[Introduction to  Information Gathering](../Introduction%20to%20%20Information%20Gathering.md)

## theHarvester
- Link : [theHarvester](https://github.com/laramies/theHarvester)
- The tool gathers names, emails, IPs, subdomains, and URLs by using
multiple public resources. 
- The tool is **passive recon**, but it also has **active recon** setting as well which will interact with the system

## Command Usage
- `theHarverster -d {domain name}`: Harvest relevant information from the target domain
	- eg: `theHarvester -d hackersploit.com`
- **Note**: The training content uses `-b` parameter to specify which search engine , database to harvest. The video also uses sources such as Google.com , linkedin etc, but the latest version does not have these sources as options