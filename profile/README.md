# Doma(in)Validity

[Doma(in)Validity](https://api.domainvalidity.dev/) was born because I found myself goggling how to check if a domain was valid. I always ended up using regular expressions that were too complex to account for several scenarios (mainly the TLD having different formats), it was just a pain in the butt because I always had to go back to that code to fix the regex to account for an edge case that I didn't think about.

Well, no more! Welcome [Doma(in)Validity](https://api.domainvalidity.dev/), this stupid simple API will check if a domain is valid or not based on the [Public Suffix](https://publicsuffix.org/) list.

I hope this is helpful for developers. You can see a [working example here](https://api.domainvalidity.dev/validate?host=https://adro.rocks/blog/) and a [failing example here](https://api.domainvalidity.dev/validate?host=https://$uper.m4n.is.badTld/).