# Microsoft Glossary Synopsis: TLS / SSL

## Submitted by

Name: Laurent Bugnion

Email: lbugnion@microsoft.com

Twitter: @LBugnion

GitHub: LBugnion

## Short description

two protocols used to encrypt communication on a network

## Phonetics

ti-ɛl-ɛs / ɛs-ɛs-ɛl

## Notes

- TLS Transport Layer Security
- SSL Secure Sockets Layer (deprecated, predecessor)
- Encryption, cryptography
- Used for web browsing, email, instant messaging, voice over IP, etc
- Certificates

## Keywords

TLS, SSL, HTTPS, encryption, certificates, cryptography, transport layer security, secure sockets layer

## Demos

- Show what happens in web browser when browing in HTTP
- Show what happens in web browser when using invalid certificate
- Show custom domain tab in App Service

## Links to docs

- [Add a TLS/SSL certificate in Azure App Service](https://docs.microsoft.com/azure/app-service/configure-ssl-certificate)
- [Secure a custom DNS name with a TLS/SSL binding in Azure App Service](https://docs.microsoft.com/azure/app-service/configure-ssl-bindings)

## Links to Learn

- [Security, responsibility, and trust in Azure](https://docs.microsoft.com/learn/modules/intro-to-security-in-azure/) *(Module)*
- [Cloud security](https://docs.microsoft.com/learn/modules/cmu-cloud-security/) *(Module)*
- [Fundamentals of network security](https://docs.microsoft.com/learn/modules/network-fundamentals-2/) *(Module)*

## Script

> On camera

Today's words of the day are abbreviations: TLS / SSL.

Hello and welcome to Microsoft Azure Words of the Day, the show that teaches you the Azure vocabulary!

> Show the letters on the screen with finger, tap tap tap. Remember to tap right to left.

TLS is short for Transport Layer Security

> Show the letters on the screen with finger, tap tap tap. Remember to tap right to left.  

SSL is short for Secure Sockets Layer.

> Camera

We often hear these two abbreviations put together, for example when someone says "you can setup TLS/SSL on the Azure Portal".

> SSL / TLS publication / deprecation

SSL is a standard that enables secure, encrypted transmissions over the internet. It requires a certificate that you can purchase from various vendors.

TLS is similar to SSL but it is a newer, more modern version. It also relies on certificates, in fact when you purchase an SSL certificate, it is often already ready for TLS.

> Demo in the azure portal
> - Explain `HTTPS Only`
> - Show option to buy certificate

When TLS or SSL are setup on your web server, this enables you to serve web content over HTTPS. This other abbreviation means: Hypertext Transfer Protocol Secure. But just like HTTP is not just for text, HTTPS is encrypting the whole communication. HTTPS is often used in the web browser, but it can also be used for APIs, etc.

> DEMO Show the App Service portal, click on the URL, show that it's HTTPS.

In the Azure portal, you can easily buy or import a certificate to secure your App Service. Note however that web applications on Azure are secure by default. This is why you see HTTPS in the location bar when you navigate to any website on anything.azurewebsites.net, which is the default address for App Services. The certificate and the HTTPS settings are needed when you want to use a custom domain, for example TailwindTraders.com.

> Show certificate info in Edge

When navigating to an HTTPS site, you can see more information about the certificate here. This shows a valid certificate used on a custom domain, it's safe to browse it.

> Show invalid certificate site

On the other hand, if you see this kind of information, you need to be careful, something is wrong with the certificate!

> Show [http://galasoft.ch](http://galasoft.ch)

If you navigate to a site using a custom domain, you can sometimes choose between HTTP or HTTPS. Here we see a note in the web browser indicating that this connection is not secure.

> Show [https://galasoft.ch](http://galasoft.ch)

> Back to portal, show the redirect switch

It is recommended to always require HTTPS on your web application. In Azure, you can set it up with this switch here.

> Back on camera

Security is a complex topic, and we definitely need more than two minutes to talk about it. That's why you should check the links here to learn more about this topic. Thank you so much for watching Microsoft Azure Words of the Day. Today's abbreviations of the day were: TLS / SSL.
