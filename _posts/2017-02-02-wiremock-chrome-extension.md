---
layout: post
title:  "Wiremock chrome extension: Simple UI for programming stubs"
date:   2017-02-02 12:00:00 +0100
permalink: /wiremock-chrome-extension/index.html
tags: exploratory-testing chrome-extensions
image: /img/article/wiremock.png
---

I'm proud to announce a new project that I've just released, a [chrome extension for Wiremock](https://chrome.google.com/webstore/detail/wiremock-extension/ikiaofdpbmofgmlhajfnhdjelkleljbl).  The [ Wiremock chrome extension ](https://chrome.google.com/webstore/detail/wiremock-extension/ikiaofdpbmofgmlhajfnhdjelkleljbl) provides users with a simple GUI that allows you to create, view, edit and delete stubs that are stored within Wiremock.

If you've not come across [Wiremock](http://wiremock.org/) before, it's a great tool and I'm a huge fan it!  It offers all sorts of cool features, like how you can use Wiremock to create a programmable mock server to receive HTTP requests and respond back with programmed responses.  I found it to be a great tool in an exploratory testing context and when testing one application I spent a lot of time priming Wiremock to test how it handled different responses, which required a lot of back and forth between the browser and Wiremock.  So over the past 8 months I have been working on this extension to allow Testers and Developers to quickly program Wiremock and see the results without leaving the browser.

You can [download the extension from here](https://chrome.google.com/webstore/detail/wiremock-extension/ikiaofdpbmofgmlhajfnhdjelkleljbl) but if you want to know more, check out some of the features in more detail...

<h2>Creating stubs with Wiremock chrome extension</h2>

<a href="/img/2017/02/wiremock-chrome-extension-slide-1.png"><img src="/img/2017/02/wiremock-chrome-extension-slide-1-243x300.png" alt="Wiremock chrome extension - Create stub" width="300" height="300" class="alignleft size-medium wp-image-583" style="border: 1px solid #000000" /></a>

Wiremock chrome extension allows you to easily create and update stubs from a single form, which includes:

* Full support for URL matching
* Ability to create multiple query strings and request/response headers
* Multiple request body matching support
* Status code and response body setting

Download [ Wiremock chrome extension here](https://chrome.google.com/webstore/detail/wiremock-extension/ikiaofdpbmofgmlhajfnhdjelkleljbl)

<h2>Mapping management with Wiremock chrome extension</h2>

<a href="/img/2017/02/wiremock-chrome-extension-slide-2.png"><img src="/img/2017/02/wiremock-chrome-extension-slide-2-242x300.png" alt="Wiremock chrome extension - Mappings view" width="300" height="300" class="alignright size-medium wp-image-584" style="border: 1px solid #000000" /></a>

Wiremock chrome extension hooks into Wiremock's mapping features to give users:

* Ability to view all currently stored mappings within Wiremock
* Edit and deletion support for each stub
* Ability to view the JSON structure for each mapping

Download [ Wiremock chrome extension here](https://chrome.google.com/webstore/detail/wiremock-extension/ikiaofdpbmofgmlhajfnhdjelkleljbl)

<h2>Connecting to your Wiremock with Wiremock chrome extension</h2>

<a href="/img/2017/02/wiremock-chrome-extension-slide-3.png"><img src="/img/2017/02/wiremock-chrome-extension-slide-3-242x300.png" alt="Wiremock chrome extension - Settings" width="300" height="300" class="alignleft size-medium wp-image-585" style="border: 1px solid #000000" /></a>

Wiremock chrome extension can be hooked into either locally or remotely deployed Wiremock instances, offering:

* HTTP and HTTPS support
* Storable settings for host and port

Download [ Wiremock chrome extension here](https://chrome.google.com/webstore/detail/wiremock-extension/ikiaofdpbmofgmlhajfnhdjelkleljbl)
