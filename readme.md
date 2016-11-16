# Serverless Website

I've managed to cobble together a basic system that allows users to input a hash of a torrent (only from instant.io at the moment) - download a HTML page and display it!

## How to get this demo up and running

1. Git clone into a location of your choice. It doesn't need to be on a server, you PC will do!
2. Open https://instant.io and drag the test.html onto the page. Copy the __Torrent info hash:__ you see
3. Open index.html in a browser. I've tested in Chrome and FF, and it works good!
4. Open dev tools to get a look at the development console. Paste in the hash you got in part 2 in the box and click __Load Website__
5. Wait a few seconds for the torrent to download, and volia - the HTML should change to the website!