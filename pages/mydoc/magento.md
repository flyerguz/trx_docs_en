---
title:  "How to install and configure the Magento plugin"
permalink: magento.html
sidebar: mydoc_sidebar
folder: mydoc
---

### Obtaining the latest Prestashop module
You can download the latest version from your dashboard by going to **My Account -> Integration -> Select Magento 1.x**, click **Download the plugin**.

{% include image.html file="magento/downloadplugin.png" url="/images/magento/downloadplugin.png" %}

### Installing the module

From **Magento Connect Manager** click on **Scegli File** poi **Upload**.

{% include image.html file="magento/connectmanager.png" url="/images/magento/connectmanager.png" %}

Click on Transactionale **Settings**.

{% include image.html file="magento/settings.png" url="/images/magento/settings.png" %}

### Settings details

You will be redirected to the module configuration page

The details of the fields displayed are shown below:

*Attivato*| select Yes to enable the plugin.
*Debug*| select No.
*Auth Key*|his is used to identify your account. **Follow the instructions below to fill it**.
*Import leads automatically*|Enable leads automatic import. When enabled, copy and paste the displayed URL into your Transactionale account at My Account -> Integration -> Webhook URL.

{% include image.html file="magento/webhook.png" url="/images/magento/webhook.png" %}


### Last steps

Copy your Auth Key from your Transactionale account under **My Account-> Integration** ed  and paste into the Auth Key of the Magento plugin settings.

{% include image.html file="magento/apikey.png" url="/images/magento/apikey.png" %}

After completing all the required fields click on Save.


### Enabling automatic import of leads - Webhook

For the automatic import of leads via webhook you have to select **YES** in the field **Import leads automatically**

{% include image.html file="magento/webhook.png" url="/images/magento/webhook.png" %}

Paste the link you see in the **My Account-> Integration** section of your Transactional account in the **Webhook Url** field.

{% include image.html file="magento/webhookurl.png" url="/images/magento/webhookurl.png" %}

To check the correct functioning click on **Test** .