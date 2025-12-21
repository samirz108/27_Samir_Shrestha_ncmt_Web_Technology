 # WEB TECHNOLOGY 
 Assignment 1

Date: Dec 20th 2025

Name:Samir Shrestha

Program: BIT 3rd I

Roll no:26   

        

   ## CHAPTER 1: AN OVERVIEW OF THE INTERNET AND THE WEB

## Group A: Short Questions (2 Marks)

1. Define the term ”Protocol” in the context of the Internet?

 Ans: In the context of internet, a protocol is a standardized set of rules and regulations , that controls how devices   communication across diverse networks.Example: TCP and IP manage reliable data delivery and addressing.



2. *What is the primary difference between a Web Browser and a Search Engine?*

Ans:A web browser is the app you use to open the internet.

A search engine is a website that helps you find things on the internet.


 
3. *Define the World Wide Web (WWW)?*

Ans:The World Wide Web (WWW or Web) is a vast system of interconnected documents (webpages, videos, files) accessed via the Internet, using hyperlinks to jump between resources, making information easily navigable through web browsers like Chrome or Firefox



*4.Distinguish between a static web page and a dynamic web page?*

Ans: Static web page:
Shows the same content to everyone and does not change unless the developer updates it.
 Example: A basic information page.

Dynamic web page:
Content changes based on user actions or data (like login, time, or location).
 Example: Social media, online shopping sites.
 



## Group B: Long Questions (4 Marks)

5. Explain the client-server architecture of the web with a neat diagram? 


Ans:The client–server architecture explains how the web works by dividing tasks between two sides:

Client: The user’s device (computer, phone) with a web browser

Server: A powerful computer that stores websites and data

How it works:

The client (browser) sends a request (e.g., open a webpage).

The server receives the request.

The server processes it and sends back the webpage.

The client displays the webpage to the user.

![alt text](image.png)





6.Describe the functions of the following Internet services: Email, FTP, and VoIP.

Email: Lets people send and receive messages over the Internet. You can also attach files like pictures or documents, and the receiver doesn’t have to be online at the same time.

FTP: Used to move files between computers on the Internet. It’s often used to upload or download large files, especially for websites.

VoIP: Lets people make voice calls using the Internet instead of traditional phone networks. It can also include video calls and voice messages.





7."The Internet is a network of networks." Elaborate on this statement explaining how packet switching works. 

Ans: The Internet is called a “network of networks” because it is made up of many smaller networks (like home, school, and company networks) that are all connected together.

Packet switching works like this:

When you send something on the Internet, it is split into small pieces called packets.

Each packet travels across the Internet through different networks and routers.

Packets may take different paths to reach the destination.

When they arrive, the packets are put back together to form the original message.

This method makes the Internet fast, efficient, and reliable, even if some routes are busy or not working.



## Group C: Scenrio-Based Questions (5 Marks)



 8. A startup company wants to host a website that displays the same information to all visitors and requires very low maintenance costs. However, they are being advised to use a dynamic website. As a consultant, would you agree? Justify your answer.
 Ans:
 As a consultant, I would not agree with using a dynamic website in this situation. Since the startup’s website displays the same information to all visitors and needs very low maintenance, a static website is more suitable.
 A static website consists of fixed web pages written in HTML and CSS. These pages do not change unless manually updated. Static websites are cheaper to host, faster to load, and more secure because they do not use databases or server-side scripting. They also require minimal technical maintenance, which is ideal for a startup with limited resources.
 Dynamic websites are useful when content needs to change frequently, such as user logins, online forms, or real-time data updates. However, they require databases, backend programming, higher hosting costs, and regular maintenance.
 Therefore, for a startup that wants to show the same content to all users at a low cost, a static website is the best choice, and using a dynamic website would be unnecessary.



 9. A user types www.google.com into their browser, but the browser displays a “Server Not Found” error, even though the internet connection is active. However, accessing the site via 142.250.190.46 works. Diagnose the problem and explain the underlying technology that failed.
 Ans:
 The problem in this situation is a failure of the DNS (Domain Name System).
 When a user types www.google.com, the browser does not understand domain names directly. It first contacts a DNS server to translate the domain name into an IP address (for example, 142.250.190.46). This process is called DNS resolution.
 Since the website opens successfully when the IP address is entered directly, it proves that:
 The internet connection is working
 The web server is reachable
 However, because the domain name does not work, the DNS server is unable to resolve the domain name. This could be due to incorrect DNS settings, a DNS server outage, or corrupted DNS cache.
 Thus, the underlying technology that failed is the Domain Name System (DNS), which is responsible for converting human-readable domain names into machine-readable IP addresses.



 10. A multinational corporation wants to share sensitive inventory data with specific suppliers but does not want this information available to the general public. Explain which network type (Intranet, Extranet, or Internet) they should implement and why.
 Ans:
 The company should implement an Extranet.
 An Extranet is a private network that allows controlled access to external users, such as suppliers, vendors, or business partners. It uses secure authentication methods like usernames, passwords, or VPNs to ensure that only authorized users can access the information.
 An Intranet is used only by internal employees within the organization and cannot be accessed by external suppliers. The Internet, on the other hand, is public and accessible to everyone, which would make sensitive data insecure.
 Since the company wants to share sensitive inventory data only with specific suppliers and not with the general public, an Extranet provides the best balance between security and controlled access.
 Therefore, an Extranet is the most suitable network type for this requirement.