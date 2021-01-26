# Using the Synopsis Client

> Previous page: [Creating content for the Glossary: Getting started](./getting-started.md)

The synopsis has the following sections that you must fill before submitting it for review.

Note that the new synopsis is into a GitHub `branch`. It means that your changes will be into a kind of sandbox and won't affect the rest of the site until you are ready to submit. [More information about GitHub branches](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches).

## Submitted by

You have already entered your information when you submitted the form above. Please check that the following is available:

Name: Your name
Email: Your email address
Twitter: Your Twitter username
GitHub: Your GitHub username. This information is optional.

If more than one author is present, please use comma-separated lists, for example:

Name: Laurent Bugnion, Scott Cate
Email: lbugnion@microsoft.com, scottca@microsoft.com
Twitter: LBugnion, ScottCa
GitHub: LBugnion, ScottCa

## Short Description

You should see here the Short Description that you entered in the form. It will be used later in the social videos, in the title card. 

> IMPORTANT **Please keep the Short Description between 60 and 200 characters**.

You can see an example here:

![Microsoft Glossary Social Video Title Card](./images/ShortDescription.png).

## Phonetics

We show a phonetic transcription of the term to create a feeling of being in a dictionary. You can easily create the phonetics with the following steps:

1. Go to [https://tophonetics.com](https://tophonetics.com/).
2. Paste or type your english text in the box.

![tophonetics screenshot](images/2020-04-29_17-21-27.png)

3. Make sure that `American` is selected. This is just to ensure that we have consistent phonetics through all the entries.
4. Click on `Show Transcription`.
5. Copy the transcription.
6. Include the transcription into your Synopsis markdown.

## Personal notes

This section is intended as a notepad where you can quickly jot down some ideas about the video. For example when doing some research online, this is a convenient place to create a bullet points list, and to consult it later when you create the script.

## Keywords or key expressions

The list of keywords will be used to cross-reference items within the Glossary. They can be one word, a short expression, 2-3 words. They can also be abbreviations.

For example, if you have this list of keywords in the app-service.md file:

`Web Server, Web API`

and another page has this text:

`[...] and you can install this application on a web server locally or in the cloud [...]`

then after processing, the text becomes

`[...] and you can install this application on a [web server](/glossary/term/app-service/web-server) locally or in the cloud [...]`

> A given keyword or key expression can be used in multiple pages. In that case a disambiguation page will be created to help the user choose which page he wants to read.

## Demos

We try to illustrate each term with some small "demos" (note the quote signs here...). By this we mean that the demos are not necessarily aimed at showing a technical solution, but rather to illustrate the point you are making. The demos should be short (a few seconds), for example a quick action in the Azure portal, a navigation through some items, some screenshots, etc.

For "on camera" scenes, you can also add some logos in overlay to make things more interesting.

You can see a few examples of "demos" below.

> Click on the animated GIF to see the video

*Demo 1: Showing logos on the camera*

[![Demo 1: Showing logos on the camera](images/Demo1-OnScreenCallouts.gif)](https://1drv.ms/v/s!As15SQCXjw37tthGrnjGJNK8uT8XRw?e=VY5Lwr)

*Demo 2: Using callouts to attract attention*

[![Demo 2: Using callouts to attract attention](images/Demo2-BorderCallouts.gif)](https://1drv.ms/v/s!As15SQCXjw37tthH6xdeBGgqSVOPOg?e=NOwesH)

*Demo 3: Showing logos on screen*

[![Demo 3: Showing logos on screen](images/Demo3-OnScreenLogos.gif)](https://1drv.ms/v/s!As15SQCXjw37tthIYGn9rzf9tRZaLA?e=AfTzoK)

*Demo 4: Showing the Azure Portal*

[![Demo 4: Showing the Azure portal](images/Demo4-PortalDemo.gif)](https://1drv.ms/v/s!As15SQCXjw37tthJdVQQzrdUNrqPRg?e=RHAnSb)

*Demo 5: Fun with fingers*

[![Demo 5: Fun with fingers](images/Demo5-FunWithFingers.gif)](https://1drv.ms/v/s!As15SQCXjw37tthKJMVdNC3amneSXw?e=R27JHc)

*Demo 6: Animating screenshots*

[![Demo 6: Animating screenshots](images/Demo6-AnimatingScreenshots.gif)](https://1drv.ms/v/s!As15SQCXjw37tthL7pjFWq_uFE7PRQ?e=dgWubC)

## Links to Docs

One of the goals of this project is to drive traffic to the Microsoft documentation and Learn pages. For each term, you should provide a list of Docs and Learn links.

Each link will be instrumented with information allowing us to track the clicks. You don't have to worry about that however. In the synopsis document, simply list the links, for example:

- [App Service overview](https://docs.microsoft.com/azure/app-service/overview)
- [App Service documentation](https://docs.microsoft.com/azure/app-service)

## Links to Learn

Similarly to Docs links, we also ask you to provide a list of Microsoft Learn links, in order to drive traffic to these modules. 

You can either provide a link to a Learning path, or to a specific module, or both.

For example:

- [Deploy a website to Azure with Azure App Service](https://docs.microsoft.com/learn/paths/deploy-a-website-with-azure-app-service) *(learning path)*
- [Capture Web Application Logs with App Service Diagnostics Logging](https://docs.microsoft.com/learn/modules/capture-application-logs-app-service) *(module)*
- [Create and publish a web application with Azure App Service and Visual Studio Code](https://docs.microsoft.com/learn/modules/create-publish-webapp-app-service-vs-code) *(module)*

## Script

> For the script, we recommend aiming for **330 - 350 words** for the 2 minutes video.

Maybe the most important part of the synopsis, and the one you'll spend the most time creating, is the script.

All Microsoft Glossary videos are scripted. This serves a few purposes:

- Help us review the video before it is even created.
- Help you create videos that are short (below 2:20 so they can be posted to Twitter) and to the point.
- Help create captions for the videos.

You can see examples of scripts [here](../synopsis/aad.md#script) and [here](../synopsis/app-service.md#script). Here are some tips:

- Keep it simple. Start by writing what you want to say, then go over the script again and remove unnecessary words, repetitions, etc. Going through the script a few times will make it tighter and better.

- Add production notes as a `> blockquote`. These notes will be useful for you later when you are ready to record. For example:

> Speak to the camera

or

> Show the portal on the application insights dashboard

If you have images, screenshots etc, add them to the script too (you can save the images in the [synopsis/images](../synopsis/images/) folder). Any information you add to the script will be helpful later when recording the video.

Don't worry, we will also review the script and help you get it right before filming the video :)
