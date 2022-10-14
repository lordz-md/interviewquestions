𝗪𝗵𝗮𝘁 𝗵𝗮𝗽𝗽𝗲𝗻𝘀 𝘄𝗵𝗲𝗻 𝘆𝗼𝘂 𝘁𝘆𝗽𝗲 𝗮 𝗨𝗥𝗟 𝗶𝗻𝘁𝗼 𝘆𝗼𝘂𝗿 𝗯𝗿𝗼𝘄𝘀𝗲𝗿?

The process involves the browser, your computer’s operating system, your internet service provider, the server where you host the site, and services running on that server.

𝟭. 𝗬𝗼𝘂 𝘁𝘆𝗽𝗲 𝗵𝘁𝘁𝗽𝘀://𝘀𝗼𝗺𝗲𝘄𝗲𝗯𝘀𝗶𝘁𝗲.𝗰𝗼𝗺/𝗽𝗮𝗴𝗲 𝗶𝗻 𝘆𝗼𝘂𝗿 𝗯𝗿𝗼𝘄𝘀𝗲𝗿 𝗮𝗻𝗱 𝗽𝗿𝗲𝘀𝘀 𝗘𝗻𝘁𝗲𝗿

Here, https:// is a scheme, which tells browser to make connection to the server using TLS. somewebsite.com is the domain name of the site and it points to a specific IP address of a server. And /page is a path to the resource you need.

𝟮. 𝗕𝗿𝗼𝘄𝘀𝗲𝗿 𝗹𝗼𝗼𝗸𝘀 𝘂𝗽 𝗜𝗣 𝗮𝗱𝗱𝗿𝗲𝘀𝘀 𝗳𝗼𝗿 𝘁𝗵𝗲 𝗱𝗼𝗺𝗮𝗶𝗻

After you’ve typed the URL into your browser and pressed enter, the browser needs to figure out which server on the Internet to connect to. To do that, it needs to look up the IP address of the server hosting the website using the domain you typed in. It does this using a DNS lookup. 

𝟯. 𝗕𝗿𝗼𝘄𝘀𝗲𝗿 𝗶𝗻𝗶𝘁𝗶𝗮𝘁𝗲𝘀 𝗧𝗖𝗣 𝗰𝗼𝗻𝗻𝗲𝗰𝘁𝗶𝗼𝗻 𝘄𝗶𝘁𝗵 𝘁𝗵𝗲 𝘀𝗲𝗿𝘃𝗲𝗿

Using the public Internet routing infrastructure, packets from a client browser request get routed through the router, the ISP, through an internet exchange to switch ISPs or networks, all using transmission control protocol, more commonly known as TCP, to find the server with the IP address to connect to. But this is a very roundabout way to get there and it’s not efficient. Instead, many sites use a content delivery network, or CDN, to cache static and dynamic content closer to the browser.

𝟰. 𝗕𝗿𝗼𝘄𝘀𝗲𝗿 𝘀𝗲𝗻𝗱𝘀 𝘁𝗵𝗲 𝗛𝗧𝗧𝗣 𝗿𝗲𝗾𝘂𝗲𝘀𝘁 𝘁𝗼 𝘁𝗵𝗲 𝘀𝗲𝗿𝘃𝗲𝗿

Now that the browser has a connection to the server, it follows the rules of communication for the HTTP(s) protocol. It starts with the browser sending an HTTP request to the server to request the contents of the page. The HTTP request contains a request line, headers (or metadata about the request), and a body. The request line contains information that the server can use to determine what the client (in this case, your browser) wants to do.

𝟱. 𝗦𝗲𝗿𝘃𝗲𝗿 𝗽𝗿𝗼𝗰𝗲𝘀𝘀𝗲𝘀 𝗿𝗲𝗾𝘂𝗲𝘀𝘁 𝗮𝗻𝗱 𝘀𝗲𝗻𝗱𝘀 𝗯𝗮𝗰𝗸 𝗮 𝗿𝗲𝘀𝗽𝗼𝗻𝘀𝗲

The server takes the request and based on the info in the request line, headers, and body, decides how to process the request. For the request, 𝙶𝙴𝚃 /𝚙𝚊𝚐𝚎/ 𝙷𝚃𝚃𝙿/𝟷.𝟷, the server gets the content at this path, constructs the response and sends it back to the client.

𝟲. 𝗕𝗿𝗼𝘄𝘀𝗲𝗿 𝗿𝗲𝗻𝗱𝗲𝗿𝘀 𝘁𝗵𝗲 𝗰𝗼𝗻𝘁𝗲𝗻𝘁

<div style="width:60px ; height:60px">
![What happens when](/repository/assets/employee.png?raw=true "What happens when")
<div>
