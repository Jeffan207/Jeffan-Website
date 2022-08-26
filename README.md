# Jeffan's Website

This is the repository for my personal website. I use it mainly to host Tap Dungeon stuff. In the future I might expand it to other things, but that's up to me.

## How to develop?

This site relies on using Ajax from JQuer. This means that rendering the site from raw html on your local filesystem will trigger your browser to block the JS due to its CORS policy (browser accessing file://). to get around this make sure to install a local http-server `npm install -g http-server`. 

To run the server, open a terminal in the root directory of this project and run `npx http-server`. You can leave it running while you develop and you can access the site from localhost port `8080`. All changes you make while developing will be immediately reflected in the server (since the server is just reading directly from the project files).
