![wordmark](static/images/wordmark.png)

###Free peer-to-peer file transfers in your browser

Cooked up by [Alex Kern](http://kern.io) & [Neeraj Baid](http://neeraj.io) while eating *Sliver* @ UC Berkeley.

[![XKCD 949](http://imgs.xkcd.com/comics/file_transfer.png)](https://xkcd.com/949/)

## Overview

FilePizza enables fast and private peer-to-peer file transfers in your web browser.

By using [WebRTC](http://www.webrtc.org), FilePizza eliminates the initial upload traditionally required when sharing files via file sharing services (e.g. Dropbox). Instead of transmitting files through an intermediary server, the sender initializes a transfer and receives a "tempalink" they can distribute. When recipients click on this link, they connect directly to the sender’s browser to complete the download. Because the file never touches the server, the transfer is fast, private, and secure. For larger files, this is an especially big deal.

## Usage

    $ npm install
    $ npm start

## Requirements

* node `0.10.x`
* npm `2.x.x`

## License

BSD
