# Spam-Resistant Bitcoin

## A fork of ordisrespector

## Ordisrespector Installation guide: https://minibolt.info/guide/bonus/bitcoin/ordisrespector.html#build-it-from-the-source-code

####  Use that link to build basic ordisrespector,
####  once its built with the basic patch you can clone in this repo's version of core and rebuild

Note: This is an EXPERIMENT all added features are EXPERIMENTAL and are only theoretically capable of mitigating inscription spam

If you want to contribute please do!

####  Changes Made to Ordisrespector:

Created smaller function to check for inscriptions that behaves like EvalScript (called InscriptionFilter)

Implemented check for InscriptionFilter at SendBlockTransactions, avoids relaying inscribed block transactions (i think)
