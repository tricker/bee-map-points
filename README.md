# A map of castles for Bee


## to run it on a mac

* clone this project
* substitute your real token where it says `<YOUR-TOKEN-HERE>` on line 13 of `index.html`
* update apache config so DocumentRoot is the root of this project

    for example:

    edit the file: `sudo vi /etc/apache2/httpd.conf` (or instead of vi use your favorite text editor)

    change DocumentRoot to reflect your own environment:
    ```
    DocumentRoot "/Users/tricker/src/family/bee-map-points"
    <Directory "/Users/tricker/src/family/bee-map-points">
    ```
* start apache sudo `sudo apachectl start`
* in a web browser go to http://localhost/

* don't forget to stop apache if you want to be neat and tidy `sudo apachectl stop`