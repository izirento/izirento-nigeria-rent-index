# Nigeria: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Nigeria: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

Nigerian tenancy law is state law. Only Lagos State (Tenancy Law 2011, official gazette on the Lagos Ministry of Justice site) was read; every row is labelled Lagos State and the other states were not checked.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Lagos State: main law | The Tenancy Law of Lagos State 2011 governs tenancies of premises in Lagos State; other Nigerian states have their own laws. | [Lagos State Ministry of Justice (Lagos State Official Gazette No. 37 of 26 August 2011)](https://lagosministryofjustice.org/wp-content/uploads/2022/01/Tenancy-Law-2011.pdf) |
| deposit | Lagos State: advance rent cap | A landlord may not demand or receive from a sitting tenant more than six months' rent from a monthly tenant or one year's rent from a yearly tenant, and from a new or prospective tenant not more than one year's rent; paying or receiving more is an offence with a fine of N100,000 or three months' imprisonment (s. 4). | [Lagos State Ministry of Justice (Lagos State Official Gazette No. 37 of 26 August 2011)](https://lagosministryofjustice.org/wp-content/uploads/2022/01/Tenancy-Law-2011.pdf) |
| rent_payment | Lagos State: rent receipts | On every rent payment the landlord must issue a receipt stating the date, the names and addresses of landlord and tenant, the premises, the amount and the period covered; failure is punishable by a fine of N100,000 (s. 5). | [Lagos State Ministry of Justice (Lagos State Official Gazette No. 37 of 26 August 2011)](https://lagosministryofjustice.org/wp-content/uploads/2022/01/Tenancy-Law-2011.pdf) |
| termination | Lagos State: notice to end a tenancy | Where the agreement sets no notice, the notice to end a tenancy is one week for a tenant at will, one month for a monthly tenant, three months for a quarterly or half-yearly tenant and six months for a yearly tenant (s. 13(1)). | [Lagos State Ministry of Justice (Lagos State Official Gazette No. 37 of 26 August 2011)](https://lagosministryofjustice.org/wp-content/uploads/2022/01/Tenancy-Law-2011.pdf) |
| termination | Lagos State: arrears | A monthly tenancy lapses where the tenant is six months in arrears, and a quarterly or half-yearly tenancy where the tenant is one year in arrears, and the court makes an order for possession and arrears (s. 13(2)-(3)). | [Lagos State Ministry of Justice (Lagos State Official Gazette No. 37 of 26 August 2011)](https://lagosministryofjustice.org/wp-content/uploads/2022/01/Tenancy-Law-2011.pdf) |
| termination | Lagos State: end of fixed term | After a fixed term ends by passage of time no notice to quit is needed, but a landlord who goes to court to recover possession must first serve seven days' written notice of intention (Form TL5) (s. 13(5)). | [Lagos State Ministry of Justice (Lagos State Official Gazette No. 37 of 26 August 2011)](https://lagosministryofjustice.org/wp-content/uploads/2022/01/Tenancy-Law-2011.pdf) |

## Files

| File | Content |
| --- | --- |
| `nigeria_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Nigeria: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-nigeria-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
