# Doma(in)Validity

Doma(in)Validity was born because I found myself goggling how to check if a domain was valid. I always ended up using complex regular expressions and unenviable I always had to go back to that code to fix the regex.

Well, no more! Welcome [Doma(in)Validity](https://domainvalidity.dev/), this stupid simple API will check if a domain is valid or not based on the [Public Suffix](https://publicsuffix.org/) list.

You can see a [working example here](https://api.domainvalidity.dev/validate?host=https://adro.rocks/blog/) and a [failing example here](https://api.domainvalidity.dev/validate?host=https://$uper.m4n.is.badTld/).