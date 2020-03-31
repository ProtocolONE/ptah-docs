---
title: How to set up Google Tag Manager
bookToc: true
---

# How to set up Google Tag Manager on your landing page
***

The Google Tag Manager container snippet (a tag) is a small piece of JavaScript and non-JavaScript code that you paste into your page.
Thus you can update the contents from the Tag Manager user interface.

When you use Google Tag Manager in conjunction with Google Analytics, you’re able to collect a lot of data: 
monitoring form submissions, tracking how people arrive at your site, clicking on certain links, scroll tracking and a ton of other events.

To start, you'll need a Google Analytics account.

## Create a Google Tag account for you landing page
***

- Log into your Google Analytics account and go to [Google Tag Manager](https://tagmanager.google.com/).
- Add a new account for your landing page and accept the Google Tag Manager Terms of Service Agreement.

TODO image эту картинку сделать в нашем стиле (доступ к аккаунту у меня есть, можно переделать эту картинку)
{{< figure src="/images/img10.png">}}

## Connect your Google Tag account with Ptah
***

- Click the Settings icon on the top menu. Choose the *Integrations tab* and click the *Google Tag icon*.
- In the *GTM container ID field*, enter your GTM container ID from your Google Tag account.
- Click *Apply*.

TODO image интерфейс настройки GT с введенным container ID

## Create a tag with Google Analytics
***

You can configure a lot of tags depending on the events and triggers. 
Anytime [an event](https://support.google.com/tagmanager/answer/6106716) is registered by Google Tag Manager, [event triggers](https://support.google.com/tagmanager/topic/7679108) are evaluated and tags are fired accordingly. 

For example, this video shows how to notify Google Analytics anytime someone views your landing page:

<iframe width="400" height="230" src="https://www.youtube.com/embed/MmhDzlkillU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

***

{{< hint info >}}
**Next steps**
{{< /hint >}}

- [Connect with Mailchimp](/docs/integrations-mailchimp/)
- [Connect with Google Analytics](/docs/integrations-ga/)
- [Setting up a payment system](/docs/payments/)

***

{{< questions >}}{{< questions-text >}}{{< /questions-text >}}{{< /questions >}}