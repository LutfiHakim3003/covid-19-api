<p align="center">
  <img width="500" src="https://covid19.mathdro.id/api/og" />
</p>

# COVID-19 API

> Serving data from John Hopkins University CSSE as a [JSON API](https://covid19.mathdro.id)

[![Deploy with ZEIT Now](https://zeit.co/button)](https://zeit.co/import/project?template=https://github.com/mathdroid/covid-19-api)


## Routes

- /: contains opengraph image for sharing

- /api: global summary

- /api/og: generate a summary open graph image

- /api/confirmed: global cases per region sorted by confirmed cases

- /api/recovered: global cases per region sorted by recovered cases

- /api/deaths: global cases per region sorted by death toll

- /api/daily: global cases per day

- /api/daily/[date]: detail of updates in a [date] (e.g. /api/daily/2-14-2020)

- /api/countries: all countries and their ISO codes

- /api/countries/[country]: a [country] summary (e.g. /api/countries/Indonesia or /api/countries/USA or /api/countries/CN)

- /api/countries/[country]/confirmed: a [country] cases per region sorted by confirmed cases

- /api/countries/[country]/recovered: a [country] cases per region sorted by recovered cases

- /api/countries/[country]/deaths: a [country] cases per region sorted by death toll

- /api/countries/[country]/og: generate a summary open graph image for a [country]

## Usage

1. Clone

2. Install deps (`yarn`, `npm install`)

3. Install and register to [ZEIT Now](https://zeit.co/now) if you haven't. This project is exclusively made for the platform.

4. `now dev` to run a local dev deployment, `now` to publish.

## Showcase

- [17 responsible live visualizations about the coronavirus, for you to use](https://blog.datawrapper.de/coronaviruscharts/), (Web) by [Datawrapper](https://datawrapper.de)

- [Android kotlin-mvvm-covid19](https://github.com/rizmaulana/kotlin-mvvm-covid19), (Android) by [Rizki Maulana](https://github.com/rizmaulana)

- [CovidNow](https://github.com/OMIsie11/CovidNow), (Android) by [Oskar Misiewicz](https://github.com/OMIsie11)

- [https://github.com/andreyyoshua/Covid-19](https://github.com/andreyyoshua/Covid-19), (iOS) by [Andrey Yoshua](https://github.com/andreyyoshua)

- [https://github.com/pararang/vue-covid](https://github.com/pararang/vue-covid), (VueJS) by [Muhammad Ikhsan](https://github.com/pararang)

- [Vue Covid 19 monitoring App](https://github.com/princerafid01/covid19), (VueJS) by [Mahmud Rafid](https://github.com/princerafid01) . A [demo](https://covid-19-stat.now.sh).

- [https://github.com/pooladkhay/covid19](https://github.com/pooladkhay/covid19), (React, NextJS) by [Mohammad Javad Pooladkhay](https://mamadev.ir)

- [https://github.com/alancampora/corona-virus-react](https://github.com/alancampora/corona-virus-react), (React) by [Alan Adrian Campora](https://github.com/alancampora)

- [https://github.com/alankilalank/react-covid-19](https://github.com/alankilalank/react-covid-19), (React, CRA) by [Alank Ilalank](https://github.com/alankilalank)

- [https://github.com/pabloVinicius/covid-19-dashboard](https://github.com/pabloVinicius/covid-19-dashboard) [https://covid19.data.eti.br/](https://covid19.data.eti.br/), (Web) by [Pablo Vinicius](https://github.com/pabloVinicius)

- [https://github.com/freakyfelt/gatsby-source-mathdroid-covid19](https://github.com/freakyfelt/gatsby-source-mathdroid-covid19)(https://github.com/freakyfelt/gatsby-source-mathdroid-covid19), (Gatsby, TypeScript) by [Bruce Felt](https://github.com/freakyfelt)

- [https://github.com/miftahafina/covid19-data](https://github.com/miftahafina/covid19-data), (React) by [Miftah Afina](https://github.com/miftahafina)

- [https://github.com/mazik/corona/](https://github.com/mazik/corona/), (An Electron based Desktop application based on VueJS) by [Md Mazedul Islam Khan](http://twitter.com/iamazik/)

- [https://github.com/hoaaah/flutter-covid19ina](https://github.com/hoaaah/flutter-covid19ina), (Flutter) by [@hoaaah](https://github.com/hoaaah)

- [https://github.com/kasramp/COVID-19-Telegram-bot](https://github.com/kasramp/COVID-19-Telegram-bot), (Telegram Bot, Java) by [Kasra Madadipouya](https://github.com/kasramp)

- [https://covid-19-map.netlify.com/](https://covid-19-map.netlify.com/),(React, Deck.GL) by [Jason Feng](https://github.com/iyci)

- [https://github.com/Ghazif-Adeem/COVID-19-Statistics-Checker](https://github.com/Ghazif-Adeem/COVID-19-Statistics-Checker), (PHP) by [Ghazif Adeem](https://github.com/Ghazif-Adeem)

- [Access mathdroid API to store Coronavirus COVID-19 worldwide data in JSON format](https://github.com/maxMaxineChen/COVID-19-worldwide-json-data-script), (Javascript script, get updated every 8 hours by Github Actions) by [Maxine Chen](https://github.com/maxMaxineChen)

- [A Coronavirus COVID-19 global data statistics website](https://github.com/maxMaxineChen/COVID19-Worldwide-Stats), (React + Gatsby + Material UI + Recharts) by [Maxine Chen](https://github.com/maxMaxineChen)

- [https://novel-coronavirus-reports.netlify.com/](https://novel-coronavirus-reports.netlify.com/), (PWA with Map & reports) by [Sharad Raj Singh Maurya](https://github.com/sharadcodes)

- [https://github.com/sutanlab/covid19-visualized](https://github.com/sutanlab/covid19-visualized), (Next.js, TypeScript) by [Sutan Gading F. Nasution](https://github.com/sutanlab)

- [Covid-19 World Map](https://github.com/pvogenthaler/covid-19) (D3.js globe displaying confirmed, recovered, and death counts by country) by [Paige Vogenthaler](https://github.com/pvogenthaler/)

- [https://souryvath.github.io/ng-covid-19/](https://souryvath.github.io/ng-covid-19/), (Angular, ApexCharts) by [Souryvath NIRASAY](https://github.com/souryvath/)

- [Corona-tracker](https://corona-tracker-2020.netlify.com/), (Vue frontend for the API with main focus on India) by [Akash Raju M](https://github.com/akashrajum7) 

- [https://github.com/satyawikananda/Vucovid-Covid-info](https://github.com/satyawikananda/Vucovid-Covid-info), (VueJS, PWA) by [Satya Wikananda](https://github.com/satyawikananda)

- [https://github.com/juanitourquiza/ng-covid-19](https://github.com/juanitourquiza/ng-covid-19) [https://hackeruna.com/covid19/](https://hackeruna.com/covid19/), (Angular) by [Juan Urquiza](https://github.com/juanitourquiza)

- [RN-Covid19](https://github.com/Hamaar/RN-Covid19), (React-Native) by [Hamaar](https://github.com/Hamaar)

- [Last 7 days chart with percentages](https://covidchart.netlify.com/),(Next, React, PWA) by [Mithhu](https://github.com/mithhu)

- [https://livecovid19stats.netlify.com](https://livecovid19stats.netlify.com), (Gatsby, React) by [Dhaiwat Pandya](https://github.com/Dhaiwat10)

- [https://corona-stats-eta.now.sh/](https://corona-stats-eta.now.sh/), (React, Hooks) by [Vitor Boccio](https://github.com/vitorboccio)

- [COVID-19 | Coronavirus Live Stats and Tracker](https://covidstats.ca/), (React) by [Micah Mones](https://github.com/micahmones)

- [https://sandipnirmal.github.io/covid-19-tracker](https://sandipnirmal.github.io/covid-19-tracker), (React PWA) by [Sandip R. Nirmal](https://github.com/sandipnirmal)

- [https://github.com/NoumanHere/COVID-19-Using-Django](https://github.com/NoumanHere/COVID-19-Using-Django), (Django, Python) by [Nouman](https://github.com/NoumanHere/)

- [https://github.com/mazik/corona-tracker/](https://github.com/mazik/corona-tracker/), (A Google Chrome extension for tracking CORONAVIRUS - COVID-19 update) by [Md Mazedul Islam Khan](http://twitter.com/iamazik/)

- [https://krishnatre-siddhartha.github.io/](https://krishnatre-siddhartha.github.io/), (HTML+JS) by [Siddhartha Sharma](https://github.com/krishnatre-siddhartha/)


## License

MIT License 2020, mathdroid.

Transitively from the John Hopkins Site, the data may not be used for commercial purposes.
