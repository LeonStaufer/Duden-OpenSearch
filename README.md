# Duden OpenSearch

This repository aims to provide [OpenSearch](https://developer.mozilla.org/en-US/docs/Web/OpenSearch) support for [Duden.de](https://www.duden.de/).

## How it works

OpenSearch is a description format that allows websites to define their search engine so that it can be discovered by browsers. This is done via a XML file that is autodiscovered by browsers if it is referenced through an HTML `link` tag. On Firefox it can also be installed manually.

## Installing

A search engine can be installed manually by calling the following JS in Firefox:
```js
window.external.AddSearchProvider(engineURL);
```

Here, `engineURL` is the link of XML file to the search engine you would like to add. In this case, the URL would be https://github.staufer.me/Duden-OpenSearch/opensearch.xml or https://github.staufer.me/Duden-OpenSearch/opensearch-direct.xml.


## Direct Search

The direct search engine bypasses the Duden search page and instead goes directly to the page with the word.

## Disclaimer

> This work/product/service has been developed independently from and is not endorsed by the Bibliographisches Institut GmbH. Duden, and www.duden.de are registered trademarks owned by the Bibliographisches Institut GmbH.
