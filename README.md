# cloudflare-rules

## Requirements

- (Ideally) Cloudflare Pro subscription
## Installation

- Each TXT file contains a ruleset tailored for the Cloudflare Web Application Firewall (WAF). Be sure to add one rule per file within the panel.
- At the bottom of each rule's settings, set the ASN (Autonomous System Number) and miscellaneous rules to 'Managed Challenge.'
- If you're not using bot directories in your application, you can keep them blocked as is.
- (Recommended) Ratelimit rules can be applied in the 'Rate limiting rules' tab of the WAF.
- (Pro Tip!) You can enhance your security by applying the rules from [this repository](https://github.com/growtoups/ASN_LIST) and setting them to 'Managed Challenge' for an extra layer of defense! 🚀


## Contact

You can contact me via discord @ esson if you have any questions.
