# fullstack
Full stack for frontend engineers, condensed in short notes. 

## Full Stack Engineer
Many definitions exist for this term (and many controversies), but a full stack engineer is someone who can build an application from start to end. 

It's a bit complicated to delve into the details as both frontend and backend technologies are expansive such that no one is truly super-grounded enough in all tech to call themselves truly full stack, but the term is a useful description of the disciplines you straddle. 

## Command Line Interface
It is an unbridled interface for talking with your computer at an OS level. Many people swap out CLIs for GUIs (Graphic User Interfaces), and that's a shame. GUIs are opinionated, and thus throttled. 

CLIs are fast, consistent and easier to automate. 

### Common commands for the CLI
cd - check directory
pwd - print working directory
mkdir - make directory
rmdir - remove directory
echo - return your input
etc

## Shell 
This is your command interpreter that interfaces with your system. 

Popular examples: bash, zsh. 

The shell is the frontline you interface with, which gives you access to the application (the OS, typically) which gives you access to the kernel (which is the core of the OS. It handles the communication with the machine layer.)

## How does the internet work?
The internet is 'a bunch of computers talking with eachother' using a bunch of requests and responses (a series of tubes). The world-wide web is simply a part of the internet. There's FTP, streaming, etc. 

The internet can also be thought of as a series of publicly internet-connected devices, which is what separates it from the intranet. 

## Internet Protocol
A set of agreed-upon rules that is trust-based for defining how computers can talk to each other. The internet protocol is called IP. 

IP address: set of numbers that denotes the address of your computer. 

There are over 3.4 billion devices currently running on the internet. 

IPv4 (4 numbers for IP addresses, eg 8.8.8.8) was one of the first IP addresses. There were 4.3bn addresses, but the number of interconnected devices outpaced it, which leads to IPv6.

IPv6 looks more like this (2001:4868:4868:8888), and it has 340decillion IP addresses, so we shan't be running out any time soon.

## Transmission Control Protocol (TCP)
Lossless transmission, using error-correction and error-checking. It sends a syn package and the responder sends an ack package, and then transmission happens. 

## User Diagram Protocol
UDP is a one-way blast of information. As a result, it's faster than TCP. 

'I have a good joke about UDP, but you might not get it.' 

## Pings
Useful for debugging a site. You basically say 'hey' repeatedly to a destination, and you can use that to measure the round-trip and see how fast responses are coming, or if the server is even online.

`$ ping twitter.com`

## Domain Name System (DNS)
DNS is run by ICANN. It's an intelligent internet phone book. It reroutes you to the closest server that resolves to your location. DNS maps domain names to IP addresses. 

## Subdomains versus Paths
Subdomain - blog.justinirabor.com
Subdomain implies a different website entirely. 

Paths - justinirabor.com/about


## Nameservers
Map domains to IP addresses. They're the record keepers of the internet. 

## Trace routes
`traceroute google.com`
Shows you the hops that the servers pass to get to the location you're trying to locate. 