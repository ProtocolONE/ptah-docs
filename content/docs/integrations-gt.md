---
title: How to set up Google Tag Manager
bookToc: true
---

# How to set up Google Tag Manager on your landing page
***

The Google Tag Manager container snippet (a tag) is a small piece code loads with your landing page. It works together with Google Analytics and allows you to collect data and event on your landig page such as: 
* monitor form submissions
* track how people arrive at your site
* monitor link clicks
* track the scrolling
* and other events

To start, you'll need a Google Analytics account.

## Create a Google Tag account for your landing page
***

- Log into your Google Analytics account and go to [Google Tag Manager](https://tagmanager.google.com/).
- Add a new Google Tag Manager account for your landing page.

TODO image эту картинку сделать в нашем стиле (доступ к аккаунту у меня есть, можно переделать эту картинку)
{{< figure src="/images/img10.png">}}

## Connect your Google Tag account to Ptah
***

- Click the Settings icon on the top menu. Choose the *Integrations tab* and click the *Google Tag icon*.
- In the *GTM container ID field*, enter your GTM container ID from your Google Tag account.
- Click *Apply*.

TODO image интерфейс настройки GT с введенным container ID

## Create a tag with Google Analytics
***

You can configure a lot of tags that depend on events and triggers on your own. Anytime [an event](https://support.google.com/tagmanager/answer/6106716) is registered with Google Tag Manager, [event triggers](https://support.google.com/tagmanager/topic/7679108) are evaluated and tags are fired accordingly. 

For example, this video by Google shows how to notify Google Analytics anytime someone views your landing page:

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
