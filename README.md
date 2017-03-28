# Spodermen

A dumb site crawler to highlight broken links and faulty routes. 

Searches for `href` attributes in HTML content and follows any links on the
same domain. Reports the HTTP status code, content length and request duration
of all crawled URLs.


## Usage

    $ ./spodermen https://github.com/cavaliercoder/spodermen
    GET /cavaliercoder/spodermen 200 48600 1538
    Dolan, y u do dis?


## Reviews

> Terrible. Don't use it.
> - Ryan Armstrong
