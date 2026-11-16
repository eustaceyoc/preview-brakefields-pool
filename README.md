# Brakefield's Pool Service: sample site

A one-page sample site I put together for Brakefield's Pool Service (Denton, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-brakefields-pool.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to service@bps940.com, and the phone buttons dial (940) 514-1043. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Brakefield's Pool Service's own website and public listings: business name, owner Jay Brakefield, Denton address, phone, service@ email, hours, 'veteran-owned and founded', and the services and resource topics listed on bps940.com. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Brakefield's Pool Service, its people or its work.

- `denton-house.jpg`: "White and Blue Wooden House" by Curtis Adams on Pexels (https://www.pexels.com/photo/white-and-blue-wooden-house-3958954/)
- `pool-steps-tile.jpg`: "Design of Swimming Pool" by Santiago Manuel De la Colina on Pexels (https://www.pexels.com/photo/design-of-swimming-pool-4421349/)

Fonts: Archivo Black, Lora (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
