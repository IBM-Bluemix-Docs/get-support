---

copyright:

  years: 2015, 2018

lastupdated: "2018-01-16"

---

{:shortdesc: .shortdesc}
{:codeblock: .codeblock}
{:screen: .screen}
{:tip: .tip}
{:new_window: target="_blank"}

# Viewing {{site.data.keyword.Bluemix_notm}} status and notifications
{: #viewing-bluemix-status}

The Status page is the central place to find notifications and announcements about key events that are affecting the {{site.data.keyword.Bluemix_notm}} platform and major services.
{:shortdesc}

On the Status page, you can find the following information:

  * The current status of services and components in all {{site.data.keyword.Bluemix_notm}} Foundry Service regions.
  * A list of announcements, in chronological order, for maintenance and incidents. You can filter the list or open an individual announcement for more details.
  * Planned maintenance windows for which prior notice is provided, except in extreme circumstances.
  * Unplanned incidents or outages, which are posted as soon as the {{site.data.keyword.Bluemix_notm}} team becomes aware of them. Incident notifications are regularly updated until they are resolved.
  * References to security bulletins that affect the various {{site.data.keyword.Bluemix_notm}} services or the platform.
  * Other platform-wide announcements of general interest to you.
  * [An RSS feed to which you can subscribe](#subscribing-rss-feed).

You can find the Status page by choosing either of the following options:

  * Log in to the {{site.data.keyword.Bluemix_notm}} console. From the menu bar, click **Support** and select **Status**. Check the listed resources for the ![some issues](images/some_issues.svg) icon. This icon might indicate an outage.
  * Access it directly at [{{site.data.keyword.Bluemix_notm}} - Status ![External link icon](../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/status){: new_window}.


## Best practices for monitoring status
{: #best-practices}

Use the following best practices for monitoring the status of {{site.data.keyword.Bluemix_notm}} to stay informed and plan accordingly.

### Check for upcoming maintenance windows
{: #monbp-checmaintwin}

Check for upcoming maintenance windows posted on the Status page, at least once every 24 hours, by using one of the following options:
* Navigating directly to the [Status ![External link icon](../icons/launch-glyph.svg "External link icon")](https://console.bluemix.net/status){: new_window} page
* Using the RSS feed or an RSS-to-email forwarder

### Check for current maintenance windows or an incident in progress
{: #monbp-checcurmaninprog}

If you suspect that {{site.data.keyword.Bluemix_notm}} is not functioning as expected, check the Status page for current maintenance windows or an incident in progress. To report an incident that is not already listed on the Status page, open a support ticket by clicking **Support** and selecting **Add Ticket** on the menu bar or by accessing the [{{site.data.keyword.Bluemix_notm}} Support ![External link icon](../icons/launch-glyph.svg "External link icon")](http://www.ibm.biz/bluemixsupport){: new_window} help page.

### Take advantage of multiple {{site.data.keyword.Bluemix_notm}} Foundry Service regions
{: #monbp-multpreg}

All users of {{site.data.keyword.Bluemix_notm}} Public automatically have access to the US-SOUTH, US-EAST, EU-GB, EU-DE, and AU-SYD regions. The {{site.data.keyword.Bluemix_notm}} Global Operations team manages all regions to avoid maintenance impacts and minimize the risk of incidents that affect all regions at the same time.

To switch regions, from the {{site.data.keyword.Bluemix_notm}} menu bar, expand the region menu, and then select another region.

### Prepare for minor interruptions
{: #monbp-prepmininter}

In most cases, {{site.data.keyword.Bluemix_notm}} can continue to be used normally, even during the maintenance window. However, minor interruptions of a service can't always be avoided. Running applications typically remain available even if the application management functions of {{site.data.keyword.Bluemix_notm}}, such as starting and stopping apps, are temporarily interrupted. To maximize the availability of your running applications, run at least three instances of each application.

## Subscribing to an RSS feed
{: #subscribing-rss-feed}

You receive alerts of any notifications by subscribing to the RSS feed for the {{site.data.keyword.Bluemix_notm}} Status page. This approach provides a way for you to get updates without having to regularly consult the Status page.

To subscribe, follow these steps:

1. Download and install an RSS reader.
2. Use your reader to subscribe to the feed with one of the following methods:
    * Drag the RSS ![RSS](images/rss.svg) icon into your RSS reader.
    * Right-click the RSS icon, select **Copy link address**, and paste the URL into your RSS reader.

See your reader's **Help** section for more information. 	   

Other methods of reading RSS feeds are available through web browser plug-ins such as:
  * [RSS Feed ![External link icon](../icons/launch-glyph.svg "External link icon")](http://feeder.co/){: new_window} Reader for Chrome
  * [Brief ![External link icon](../icons/launch-glyph.svg "External link icon")](https://addons.mozilla.org/en-US/firefox/addon/brief/){: new_window} add-on for Firefox

News sources, such as the following sites, also provide methods to read RSS feeds:
  * [Feedly ![External link icon](../icons/launch-glyph.svg "External link icon")](http://www.feedly.com/){: new_window}
  * [G2reader ![External link icon](../icons/launch-glyph.svg "External link icon")](http://www.g2reader.com/en/){: new_window}

You can also use a third-party service to automatically send an email for each RSS update. The following list provides some example third-party services:

  * www.feedmyinbox.com
  * www.rssforward.com
  * www.feedrabbit.com
  * www.mailchimp.com
  * www.feedmailer.com
  * www.iftt.com

{{site.data.keyword.Bluemix_notm}} typically has approximately 50 updates per month.


## Setting up incident and maintenance email notifications
{: #setting-up-notifications}

For {{site.data.keyword.Bluemix_notm}} Public, you can sign up for platform notifications. Platform notifications are optional email alerts for incident and maintenance events for the {{site.data.keyword.Bluemix_notm}} platform. You can choose to receive these email notifications by clicking **Manage** > **Account** > **Notifications** and selecting the **Platform** tab. For more information about setting account notifications, see [Setting notifications](/docs/account/notifications.html#setting-notifications).
