# Swedish Facebook

Data collections from Swedish Facebook: news accounts, political parties and non-governmental organizations.

CSV headers of [sidor-facebook.csv](sidor-facebook.csv):

- `media` is an integer value whether the account is a media organization (`1`) or not (`0`).
- `politicalparty` is an integer value whether the account is a political party (`1`) or not (`0`).
- `politics` is an integer value whether the account is political in some way (`1`) or not (`0`).
- `pagename` is the full name of page.
- `pageid` is the ID of the page.
- `url` is the URL to the page on facebook.com.

The first three fields (media, politicalparty and politics) are not necessarily accurate at the moment.

Many of the pages are found via <https://gist.github.com/christopherkullenberg/07b38d18de8e747387c2d00915dba327> and then expanded with more details.

## See also

- [Swedish Twitter](https://github.com/peterdalle/swedishtwitter)
