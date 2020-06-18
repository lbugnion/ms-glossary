> Recording date: 20200505

> Language: en / English

> Captions: en / English

> YouTube: QbKzAfr6t2Q

> Keywords: TLS, SSL, HTTPS, Encryption, Certificates, Cryptography, Transport Layer Security, Secure Sockets Layer

> Blurb: two protocols used to encrypt communication on a network.

> Submitted by: LBugnion@Microsoft.com

> Twitter: @LBugnion

> [This topic was published here](http://gslb.ch/wod-tls-ssl).

# [TLS/SSL](/topic/en/tls-ssl)

<!-- YOUTUBEEMBED -->

<!-- LANGUAGESTITLE -->

<!-- OTHERLANGUAGES -->

<!-- DOWNLOAD-CAPTIONS -->

## Links

### Documentation

- [Add a TLS/SSL certificate in Azure App Service](http://gslb.ch/463)
- [Secure a custom DNS name with a TLS/SSL binding in Azure App Service](http://gslb.ch/464)

### Microsoft Learn

- [Security, responsibility, and trust in Azure](http://gslb.ch/459) *(Module)*
- [Cloud security](http://gslb.ch/465) *(Module)*
- [Fundamentals of network security](http://gslb.ch/460) *(Module)*

<!-- DOWNLOAD -->

<a id="transcript"></a>

## Transcript

Today's words of the day are abbreviations: TLS / SSL.

Hello and welcome to [Microsoft Azure Words of the Day](/en), the show that teaches you the Azure vocabulary!

TLS is short for Transport Layer Security

SSL is short for Secure Sockets Layer.

SSL is a standard that enables secure, encrypted transmissions over the internet. It requires a certificate that you can purchase from various vendors. 

TLS is similar to SSL but it is a newer, more modern version. It also relies on certificates, in fact when you purchase an SSL certificate, it is often already ready for TLS.

When TLS or SSL are setup on your web server, this enables you to serve web content over HTTPS. This other abbreviation means: Hypertext Transfer Protocol Secure. But just like HTTP is not just for text, HTTPS is encrypting the whole communication. HTTPS is often used in the web browser, but it can also be used for APIs, etc.

In the Azure portal, you can easily buy or import a certificate to secure your App Service. Note however that web applications on Azure are secure by default. This is why you see HTTPS in the location bar when you navigate to any website on anything.azurewebsites.net, which is the default address for App Services, Azure Functions, etc. The certificate and the HTTPS settings are needed when you want to use a custom domain, for example TailwindTraders.com.

When navigating to an HTTPS site, you can see more information about the certificate here. This shows a valid certificate used on a custom domain, it's safe to browse it.

You can sometimes choose between HTTP or HTTPS. Here we see a note in the web browser indicating that this connection is not secure.

It is recommended to always require HTTPS on your web application. In Azure, you can set it up with this switch here.

Security is a complex topic, and we definitely need more than just two minutes to talk about it. So check the links here to learn more about that. Thank you so much for watching Microsoft Azure Words of the Day. Today's abbreviations of the day were: TLS / SSL.
