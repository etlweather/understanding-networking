Internet
====================================
The Internet is often confused with its most prominent part - the world wide 
web. The Internet is a network of networks, it does not specify in itself what
it is used for.

The word wide web (usually refered to as "the web") is the providing and viewing
of web pages provided by various people over the Internet.

There are many other common use for the Internet:

 * Email
 * Voice/Video calls
 * Chat
 * File transfer
 * Remote access of computers
 * Inter-connecting private networks
 * and many more...

> According to the Computer History Museum, the official launch of the Internet
> was in 1983. In 1992, it became a new standard for computer networking.

## The world-wide-web
The world-wide-web - commonly referred to as "the web" - is a set of computer
service over the Internet network where individuals and corporations make
data available in the form of pages with links to other pages. The pages may
or may not contain multimedia content (images, sound, video, etc).

Originally, the content was purely academic type data. But when commercial use 
of the Internet was approved, it rapidly started changing.

To go on the web, you use a *web browser* - a computer software which knows how
to connect to the web servers, retrieve the page you asked for and display it
on the screen. The most known browsers today are Firefox, Chrome and Internet 
Explorer.

When you want to pull up a web site in your browser, you type what is called a
*URL* - Uniform Resource Locator. This is a fancy term to mean, the address of
the page - the word resource is used because it is not only used for web pages. 
A URL is formed with the following parts:

   | Part           | Example         | Description 
   | -------------- | --------------- | ---------------------------
   | scheme         | http://         | Defines the protocol which will be used for the connection used to retrieve the resource.
   | user:password@ | job:mypass@     | If a username and password is needed to access the resource, it can be provided, putting a `@` sign at the end. This is optional.
   | host           | www.example.com | The host (server) which provides the resource.
   | :port          | :80             | In this case, port refers to a identifier for a connection between two computers. It is similar to a physical port - a connection for a cable - except this is between to computers, not physical. The port tells your computer how to connect to the server. It is optional in a URL if the standard port is used for the *scheme* given.
   | /path          | /search         | A path which represents the data organization where the resource is located on the server.
   | ?query         | ?search=example | Options which are sent to the server for the execution of a program which will create content - for example, a web search. This is optional and is rarely entered by the user, rather, links on a page usually contain the query part.
   | #fragment      | #sectionA       | This is like a bookmark within a page. It tells the browser to jump to the given section. The section must have been defined by the page's author. This is optional as well.

Here is an example of a URL containing all parts:

`http://joe:mypass@www.example.com/search?query=documents#footnote`

Many schemes exists - protocols to retrieve information - however, the most
common ones are:

   * **http**: HyperText Transfer Protocol - a protocol for transfering web 
   pages and their content (defined in 1991). Originally, web pages were called 
   HyperText files  because they contain links to other pages and when clicked, 
   the links send the user to the other page. A link was called an *hyper text*.

   * **https**: Same as `http` but uses encryption to secure the connection
   from prying eyes.

   * **ftp**: File Transport Protocol - an old standard (defined in 1971) for 
   transfering files, still in wide use today.

## Who controls the Internet
There is no one who is in ultimate control of the Internet. As such, it is 
really just a concept - the idea being that multiple private networks are 
inter-connected.

There are major players however - large telecommunication and IT corporations 
as well as governments - which provides key servers and routers which makes the
Internet work.

When you are accessing a server through the Internet, the network packets sent
by your computer traverse multiple routers and servers to reach their 
destination. A program called `traceroute` can be used to get an idea of the
route taken by packets from one computer to another. Note that some routers
may hide their existence and switches (which don't participate in routing) won't
be shown - so in reality, there will be many more devices that come into play.
Here is an example of a `traceroute` report, generated from an on-line service
called [ViewDNS.info](viewdns.info):

```
traceroute to google.com (216.58.217.174), 30 hops max, 60 byte packets
1 obfuscated.internal.network.com (0.0.0.0) 0.000 ms 0.000 ms 0.000 ms
2 obfuscated.internal.network.com (0.0.0.0) 1.000 ms 1.000 ms 1.000 ms
3 66.231.176.253 (66.231.176.253) 14.893 ms 15.000 ms 14.949 ms
4 mta121.mirrield.com (66.231.179.126) 7.242 ms 7.629 ms 7.504 ms
5 eqixva-google-gige.google.com (206.126.236.21) 8.390 ms 7.639 ms 7.669 ms
6 209.85.252.121 (209.85.252.121) 8.693 ms 209.85.253.215 (209.85.253.215) 7.014 ms 209.85.252.121 (209.85.252.121) 7.693 ms
7 209.85.143.145 (209.85.143.145) 7.728 ms 209.85.143.143 (209.85.143.143) 8.149 ms 8.177 ms
8 iad23s44-in-f14.1e100.net (216.58.217.174) 7.355 ms 7.398 ms 7.596 ms
```

In October 2003, Barrett Lyon started a project to make an accurate representation
of the Internet. Here is the 2015 updated rendition.

![Visualization of the routing paths of the Internet](diagrams/internet.png)

<sup>Barrett Lyon / The Opte Project</sup>
 
 * Blue: North America
 * Green: Europe
 * Purple: Latin America
 * Red: Asia Pacific
 * Orange: Africa
 * White: major inter-connections


## What is the cloud?
The word "cloud" is simply a marketting term referring the practice of using 
services provided by companies via the Internet. The term and practice became 
popular since 2006 due to a growing number of on-line services. 

When some service or software is "cloud based", it signify that either all of it
or some portion of it is done by servers accessed through the Internet. A 
cloud-based storage is a service to store files on servers belonging to some 
company through a service they provide. A cloud-based email service is an email
system accessed through the Internet as opposed of it being installed on your 
own computer/server.

However, "cloud computing" has existed since the 1960s - at the time, computers 
were expansive, so large servers were installed in corporations and dumb 
terminals were installed at user's desks or in computer labs. Users would share 
the large server. This is the same as today's cloud services. 

With the arrival of the Personal Computer, the trend went the other way - 
processing was done on your own computer instead of on servers. But since around 
2006, with the growing Internet precense and the need to have on-line services, 
the practice of renting computer processing time on large servers came back. 

For a new company starting up, it is less expansive to rent processing time than
to set up and run their own server room connected to the Internet with fast 
bandwidth.



