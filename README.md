<p align="center">
  <img src="https://avatars0.githubusercontent.com/u/33096324?s=200&v=4" width="200px">
</p>

<h1 align="center">
  Tor Depths
</h1>

<p align="center">
  Investigation into finding unknown onion addresses on the Tor Network.
</p>

## Contents

1. [Disclaimer](#disclaimer)
1. [Introduction](#introduction)
1. [Method](#method)
1. [Results Summary](#results-summary)
1. [Links](#links)
1. [Downloads](#downloads)

## Disclaimer

We are not responsible for the bad use of the Hidden Services information 
discovered or the information contained in them. 

Some of the following addresses may contain questionable images, explicit 
or offensive content, not recommended for everyone.

All results that contain detected with pedophilic content have been excluded
from this repo and have been given to the **Department for Child Protection**. ( > 60 addresses)

## Introduction

Over the last year, as part of a larger research project on the anonymous 
[Tor Network](https://en.wikipedia.org/wiki/Tor_(anonymity_network)), we 
found ourselves needing to building a spider so that we could discover the 
addresses of new hidden services.

These addresses have been obtained by **extracting them directly** from the 
Tor nodes, instead of scraping web pages. This gave us the ability to find 
[onion addresses](https://en.wikipedia.org/wiki/.onion) that have not been 
published anywhere before.

In this repo we share the results of our investigation, with the hope that 
others find these onion addresses useful in their experiments.

## Method

For each discovered Onion address, the following process was carried out:

1. Resolve HS Descriptor
1. Port Scanning
1. Capture Website Screenshot
1. Capture of Hidden Services keywords

## Results Summary

As a summary, the investigation found:

* **76.987** onion addresses discovered
* **34.150** active onions
* **18.081** onions scanned and with open ports detected
* **13.822** web screenshots taken

## Links

1. [Dashboard](https://guest:guest@tordiscoverer.red4sec.com/?path=2017%2f05) - all hidden services that were captured during the investigation.
1. [Search Engine](https://guest:guest@tordiscoverer.red4sec.com/search.php) (beta) - search for content found within the investigation.

[![Dashboard](dashboard_panel.png)](https://guest:guest@tordiscoverer.red4sec.com/?path=2017%2f05)
[![Dashboard Menu](dashboard_menu.png)](https://guest:guest@tordiscoverer.red4sec.com/?path=2017%2f05)
>_wait until page is fully loaded_

## Downloads

* [Full list of hidden services](hidden_services.csv)
* [Hidden services with open ports](hs_scans.csv)
* [Hidden services with keywords](hs_keywords.csv) ([raw TXT files](https://www.dropbox.com/s/77cq46ql8x68nfs/webtext.tar.gz?dl=1))
* [Screenshots](https://www.dropbox.com/s/7syk4asr7wlvqc5/web_screenshots.tar.gz?dl=1) ([blank screenshots](https://www.dropbox.com/s/2ncpsdoz0kga0xl/web_screenshots_blanks.tar.gz?dl=1))
