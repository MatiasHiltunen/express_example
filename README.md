# NodeJS REST API Example

## Tarvittavat ohjelmistot

- git
- NodeJS

## Käyttöönotto

1. Kloonaa repositorio
2. Suorita komento **npm install** asentaaksesi package.json tiedostossa määritellyt npm-paketit joita projektissa käytetään (dependencies)
3. Luo .env -niminen tiedosto on kansion juureen ja lisää sinne ympäristömuuttuja **JWT_SECRET** avainarvoparina seuraavasti: "JWT_SECRET=tähän_satunnainen_merkkijono_salaisuudeksi_millä_jwt_token_allerkirjoitetaan_ja_luetaan".
4. Käynnistä kehityspalvelin komennolla **npm run dev**


Luo uusi käyttäjä tekemällä POST request /api/v1/user -endpointtiin



