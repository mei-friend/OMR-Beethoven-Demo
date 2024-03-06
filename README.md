This repository exists to demonstrate a typical workflow involving mei-friend:

Printed score -> OMR -> MusicXML -> "dirty" MEI encoding -> finalised MEI encoding.

Starting with a scanned printed score (Sechs Variationen, Opus 76 by Ludwig van Beethoven, encoding of Breitkopf und Härtel edition, 1862–90. Plate 164), we first use a commercial OMR software (Neuratron PhotoScore 2020) to extract symbolic score information from the scanned images. Unfortunately this process results in many errors, a typical outcome for OMR processes. We export this to the MusicXML format, read it in with MuseScore, and correct apparent errors. We then export as MusicXML from MuseScore, and open the resulting file in mei-friend. Unfortunately, this introduces further conversion errors, again a typical aspect of the conversion process. We use mei-friend to clean up and finalise the encoding, making it error-free as far as possible. 
