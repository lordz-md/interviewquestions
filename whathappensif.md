๐ช๐ต๐ฎ๐ ๐ต๐ฎ๐ฝ๐ฝ๐ฒ๐ป๐ ๐๐ต๐ฒ๐ป ๐๐ผ๐ ๐๐๐ฝ๐ฒ ๐ฎ ๐จ๐ฅ๐ ๐ถ๐ป๐๐ผ ๐๐ผ๐๐ฟ ๐ฏ๐ฟ๐ผ๐๐๐ฒ๐ฟ?

The process involves the browser, your computerโs operating system, your internet service provider, the server where you host the site, and services running on that server.

๐ญ. ๐ฌ๐ผ๐ ๐๐๐ฝ๐ฒ ๐ต๐๐๐ฝ๐://๐๐ผ๐บ๐ฒ๐๐ฒ๐ฏ๐๐ถ๐๐ฒ.๐ฐ๐ผ๐บ/๐ฝ๐ฎ๐ด๐ฒ ๐ถ๐ป ๐๐ผ๐๐ฟ ๐ฏ๐ฟ๐ผ๐๐๐ฒ๐ฟ ๐ฎ๐ป๐ฑ ๐ฝ๐ฟ๐ฒ๐๐ ๐๐ป๐๐ฒ๐ฟ

Here, https:// is a scheme, which tells browser to make connection to the server using TLS.ย somewebsite.comย is the domain name of the site and it points to a specific IP address of a server. And /page is a path to the resource you need.

๐ฎ. ๐๐ฟ๐ผ๐๐๐ฒ๐ฟ ๐น๐ผ๐ผ๐ธ๐ ๐๐ฝ ๐๐ฃ ๐ฎ๐ฑ๐ฑ๐ฟ๐ฒ๐๐ ๐ณ๐ผ๐ฟ ๐๐ต๐ฒ ๐ฑ๐ผ๐บ๐ฎ๐ถ๐ป

After youโve typed the URL into your browser and pressed enter, the browser needs to figure out which server on the Internet to connect to. To do that, it needs to look up the IP address of the server hosting the website using the domain you typed in. It does this using a DNS lookup.ย 

๐ฏ. ๐๐ฟ๐ผ๐๐๐ฒ๐ฟ ๐ถ๐ป๐ถ๐๐ถ๐ฎ๐๐ฒ๐ ๐ง๐๐ฃ ๐ฐ๐ผ๐ป๐ป๐ฒ๐ฐ๐๐ถ๐ผ๐ป ๐๐ถ๐๐ต ๐๐ต๐ฒ ๐๐ฒ๐ฟ๐๐ฒ๐ฟ

Using the public Internet routing infrastructure, packets from a client browser request get routed through the router, the ISP, through an internet exchange to switch ISPs or networks, all using transmission control protocol, more commonly known as TCP, to find the server with the IP address to connect to. But this is a very roundabout way to get there and itโs not efficient. Instead, many sites use a content delivery network, or CDN, to cache static and dynamic content closer to the browser.

๐ฐ. ๐๐ฟ๐ผ๐๐๐ฒ๐ฟ ๐๐ฒ๐ป๐ฑ๐ ๐๐ต๐ฒ ๐๐ง๐ง๐ฃ ๐ฟ๐ฒ๐พ๐๐ฒ๐๐ ๐๐ผ ๐๐ต๐ฒ ๐๐ฒ๐ฟ๐๐ฒ๐ฟ

Now that the browser has a connection to the server, it follows the rules of communication for the HTTP(s) protocol. It starts with the browser sending an HTTP request to the server to request the contents of the page. The HTTP request contains a request line, headers (or metadata about the request), and a body. The request line contains information that the server can use to determine what the client (in this case, your browser) wants to do.

๐ฑ. ๐ฆ๐ฒ๐ฟ๐๐ฒ๐ฟ ๐ฝ๐ฟ๐ผ๐ฐ๐ฒ๐๐๐ฒ๐ ๐ฟ๐ฒ๐พ๐๐ฒ๐๐ ๐ฎ๐ป๐ฑ ๐๐ฒ๐ป๐ฑ๐ ๐ฏ๐ฎ๐ฐ๐ธ ๐ฎ ๐ฟ๐ฒ๐๐ฝ๐ผ๐ป๐๐ฒ

The server takes the request and based on the info in the request line, headers, and body, decides how to process the request.ย For the request,ย ๐ถ๐ด๐ /๐๐๐๐/ ๐ท๐๐๐ฟ/๐ท.๐ท, the server gets the content at this path, constructs the response and sends it back to the client.

๐ฒ. ๐๐ฟ๐ผ๐๐๐ฒ๐ฟ ๐ฟ๐ฒ๐ป๐ฑ๐ฒ๐ฟ๐ ๐๐ต๐ฒ ๐ฐ๐ผ๐ป๐๐ฒ๐ป๐

![Whathappenswhen](./whathappensif.png?raw=true "What happens when")
