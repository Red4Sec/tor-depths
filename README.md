
# A look at the depths

During the last year as part of a bigger research project on the anonymous Tor Network, we found ourselves in the necessity of building a spider to discover the addresses of new hidden services.

These addresses have been obtained by __extracting them directly from the Tor protocol and its nodes__, and not by scraping web pages, giving the possibility of finding onion addresses that have not been published anywhere before.

We want to share the obtained results and all the Onion addresses discovered in case they are useful to help in other investigations.

For each discovered Onion address, the following process has been carried out:

1. Resolve HS Descriptor.
2. Port Scanning.
3. Capture Website Screenshot.
4. Capture of Hidden Services keywords.

As a summary, these are some statistics obtained:

* **76.987** Onion addresses discovered.
* **34.150** active Onions.
* **18.081** Onions scanned and with open ports detected.
* **13.822** Web Screenshots taken.  


>_**Disclaimer**: We are not responsible for the bad use of the Hidden Services information discovered or the information contained in them.  
Some of the following addresses may contain questionable images, explicit or offensive content, not recommended for everyone._

>_**Note**: All Hidden Services detected with pedophilia content have been deleted and notified to the authorities to the Department for Child Protection. ( > 60 addresses)_

## Dashboard  

Dashboard with Hidden Services captured during the investigation, sorted by month of processing.
Click on the images for the details of each Hidden Services.

[![Dashboard](dashboard_panel.png)](https://guest:guest@tordiscoverer.red4sec.com/?path=2017%2f05)

>_Wait until page loads completely, especially in months with a lot of content like August or December._

### [Dashboard - Access to the capture panel](https://guest:guest@tordiscoverer.red4sec.com/?path=2017%2f05) (guest:guest)

Click on the Menu to browse the different months in which the Onion addresses have been captured and processed.

[![Dashboard Menu](dashboard_menu.png)](https://guest:guest@tordiscoverer.red4sec.com/?path=2017%2f05)

### [Search Engine (experimental)](https://guest:guest@tordiscoverer.red4sec.com/search.php)

## Downloads

* [Download Full Hidden Services List](hidden_services.csv)
* [Hidden Services Open Ports](hs_scans.csv)
* [Hidden Services Keywords](hs_keywords.csv) ([raw txt files](https://www.dropbox.com/s/77cq46ql8x68nfs/webtext.tar.gz?dl=1))
* [Download Screenshots](https://www.dropbox.com/s/7syk4asr7wlvqc5/web_screenshots.tar.gz?dl=1) ([blanks screenshots](https://www.dropbox.com/s/2ncpsdoz0kga0xl/web_screenshots_blanks.tar.gz?dl=1))
