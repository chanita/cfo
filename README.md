[![Build Status](https://travis-ci.com/poorprogrammer/cfo.svg?branch=master)](https://travis-ci.com/poorprogrammer/cfo)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=poorprogrammer_cfo&metric=coverage)](https://sonarcloud.io/dashboard?id=poorprogrammer_cfo)[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=poorprogrammer_cfo&metric=bugs)](https://sonarcloud.io/dashboard?id=poorprogrammer_cfo)
[![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=poorprogrammer_cfo&metric=code_smells)](https://sonarcloud.io/dashboard?id=poorprogrammer_cfo)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=poorprogrammer_cfo&metric=duplicated_lines_density)](https://sonarcloud.io/dashboard?id=poorprogrammer_cfo)

![Github Action Unit Test](https://github.com/poorprogrammer/cfo/workflows/Github%20Action%20Unit%20Test/badge.svg?branch=master)

# Automated CFO for Odds

Automated Chief Financial Officer for Odds people

## Run api server

```
cd api
npm run serve
```

### Load initial fixtures

```
cd api
node tests/fixtures/loadInvoices.js
```

## Run web server

```
cd web
npm run serve
```

## Run unit test

```
./script/unittestweb
./script/unittestapi
```

## Run end-to-end test

```
docker-compose -f compose/test/docker-compose.yml run --rm e2e
```

## Production configuration 

overwrite it in `web/.env.production.local` 
<https://cli.vuejs.org/guide/mode-and-env.html>
