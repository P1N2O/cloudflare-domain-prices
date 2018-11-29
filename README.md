# Actual-Domain-Prices
The real cost of each TLD (top-level-domain). Find out how much your registrar marks up your domain prices.

This list is in **US Dollars**.

|tld|price (USD)|
|---|---|
|.com|7.85|
|.net|9.77|
|.org|9.93|
|.school|20.00|
|.plus|20.00|
|.space|15.00|
|.xyz|8.00|
|.live|15.00|
|.company|5.00|


This repo is an effort to list the *real* costs that registries put on their TLDs. Since almost all registrars are for-profit operations, they usually increase the price of domains by a few dollars to turn a profit. Another tactic is drastically lowering the price for new customers (*cough* godaddy, 1and1) then effectively performing a bait-and-switch with expensive renewal costs.

This list is aggregated from prices shown via the [Cloudflare Registrar](https://cloudflare.com/registrar), which guaranteed to only charge you what the registry charges (+ icaan fee) for the domain. Unfortunately, [as said here](https://developers.cloudflare.com/registrar/domain-registration/tld-support/), Cloudflare can't directly show each TLD price in their marketing material, so I made this list.

For programmatic use, there is a text file named `list.txt` in the format of `tld:price`.

#### Terminology: 

- **Registry**: https://icannwiki.org/Registry This is who actually runs a TLD. They choose how much to charge registrars for purchasing domains for their TLDs.
- **Registrar**: https://icannwiki.org/Registrar The company/website where you purchase a domain. Facilitates actually getting your domain registered with the Registry operators.

#### Unsupported TLDs

Some TLDs are not supported by Cloudflare, so we won't be able to get every TLD's wholesale price. See https://www.cloudflare.com/tld-policies/

#### Contributing

To contribute, make a pull request by editing this file AND `list.txt` with the TLD and the TLD's price.

Please ensure the price is USD. If the CF transfer page shows a different currency, use a currency converter and make a note in your PR what currency you converted from.
