---
pagename: 'Week of May 27th '
categoryName: Release notes
subCategoryName: 2019
indicator: messaging
subtitle: ''
level3: May
permalink: release-notes-2019-may-week-of-may-27th.html
isTutorial: false
isNew: false
date: 2019-05-27
---
These release notes include new features arriving to LiveEngage during May 2019. Exact delivery dates may vary, and brands may therefore not have immediate access to all features on the date of publication.

**Please contact your LivePerson account team for the exact dates on which you will have access to the features.**

{: .important}  
The timing and scope of these features or functionalities remain at the sole discretion of LivePerson and are subject to change.

## WeChat Business Connector - Messaging Capabilities for early adopters

### Type: New functionality


<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

The WeChat Business connector is now available for early adopters. WeChat serves 1 billion monthly active users, mostly in China, and is one of the world's most powerful apps. WeChat provides brands the ability to register as an official account, which enables them to interact with subscribers and provide them with services.

The WeChat Business connector enables brands to use LiveEngage as their messaging platform to manage official WeChat accounts at scale, allowing them to communicate with consumers more efficiently.

{: .notice}
**Please note:** WeChat Business is currently available for early adopters only. Please contact Shawn Davidson for more details.

**Screenshots**

**Image 1:** Consumer side

![](/img/week-of-may-27th-1.png)

**Image 2:** Agent side

![](/img/week-of-may-27th-2.png)

## WeChat Business Connector - Conversation attributes

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

Support has been adding for mapping WeChat Business information and passing it to LiveEngage Engagement Attributes.

* **Consumer ID -** LiveEnage will manage a unique consumer WeChat ID across consumer conversations for unified history, agent or bot context, and to allow the brands to map the consumer ID info to CRM systems. The consumer WeChat Open ID along with the prefix “wechat” and the brand’s LiveEngage account ID will be mapped to the consumer ID field in the consumer profile. The consumer ID will have the format of {wechat_siteid_wechatopenid}. This ID will be visible in real time to the agent, agent widget SDK, agent SDK, as well as in historic conversations.
* **WeChat Business ID -** The unique identifier for each business as registered within WeChat. The brand’s WeChat ID will be mapped to the “Customer Info”: ”Company Branch” engagement attribute, and will be visible in real time to the agent, agent widget SDK, agent SDK, as well as in historic conversations.
* **Consumer Name -** The consumer name will be mapped to “Consumer Info”:”Consumer name”, “Profile Name”, and “Consumer Name” under “Open Connections” and “All Connections”.

**How to enable:** This feature is enabled by default once WeChat has been enabled.

**Screenshots**

**Image 1:** Consumer Info and Customer Info as shown in LiveEngage

![](/img/week-of-may-27th-3.png)

![](/img/week-of-may-27th-4.png)

## WeChat Business Connector - Skill routing

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

Brands can configure skill routing per the brand’s business WeChat ID. Please note that only one WeChat official accounts can be connected to a LiveEngage account.

{: .notice}
**Please note:** This feature requires enablement. For more information please contact your LivePerson account team.

## WeChat Business Connector - Post Conversation Survey

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

The Post Conversation Survey enables brands to gather feedback from consumers and measure their success. Once the messaging conversation is ended by the agent, the survey will be automatically triggered. The bot will start to send the questions one by one as configured by the brand. Upon each consumer response, the bot will send the next question based on the logic defined. The survey questions and answers are based on regular text messages - all customized by the brand.

The survey can be closed in a number of different scenarios: Survey completed, survey timeout or survey skipped. Each outcome is tracked and reported on as part of the Report Builder to allow brands to fully analyze the results. Full configuration of surveys is done through the LiveEngage Bot Studio. Please [click here](https://knowledge.liveperson.com/ai-bots-automation-post-conversation-survey-bot.html) for more information.

{: .notice}
**Please note:** Structured content is not supported by the WeChat business connector, therefore a fallback text option should be configured. More information about these settings can be found [here](https://knowledge.liveperson.com/ai-bots-automation-post-conversation-survey-bot.html#enabling-support-for-textual-channels).

**Screenshots**

**Image 1:** consumer sees survey questions with the fallback text

![](/img/week-of-may-27th-6.png)

**Image 2:** agent sees the survey in progress

![](/img/week-of-may-27th-7.png)

## WeChat Business Connector - Consumer to agent image support

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

With WeChat Business’ conversational interface, consumers can select images from their device’s album or use the camera to take a real-time image and share it with agents on LiveEngage.

**Supported formats and sizes**

* Supported image types: jpeg/jpg, png
* Supported image size: there’s no limit but WeChat will autoscale in order to send the image

{: .notice}
**Please note:** This feature requires enablement. Please contact your LivePerson account team for more information.

**Screenshots**

**Image 1:** consumer sends an image to agent

![](/img/week-of-may-27th-8.png)

**Image 2:** agent sees the image consumer sends

![](/img/week-of-may-27th-9.png)

## WeChat Business Connector - Consumer to agent audio message

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

With WeChat Business’s conversational interface, consumers can share an audio with an agent by clicking the voice icon and holding down the Hold to Talk button. They can then record a voice message, release the Hold to Talk button, and send.

**Please note:** This feature requires enablement. Please contact your LivePerson account team for more information.

**Screenshots**

**Image 1:** consumer sends an audio message to agent

![](/img/week-of-may-27th-10.png)

**Image 2:** agent sees an audio message consumer sends

![](/img/week-of-may-27th-11.png)

## WeChat Business Connector - Secure forms support

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

Secure forms are now enabled for the WeChat connector. Secure forms allow brands to perform identification and authorization, and pass payment details to process payments, share PII information to generate leads, or to perform a registration process during a conversation in a PCI compliant environment. [Click here](https://knowledge.liveperson.com/security-regulations-secure-forms-secure-forms-for-messaging-user-guide.html#setting-up-liveperson-secure-forms) for more information on configuring secure forms.

## WeChat Business Connector - Automatic message support

### Type: New functionality

<div class="tablecontainer">
<table class="releasenotes">
<thead>
<tr class="categoryrow">
<th>Web Messaging</th>
<th>Mobile App Messaging</th>
<th>Twilio</th>
<th>Facebook Messenger</th>
<th>ABC</th>
<th>Line</th>
<th>Google RCS</th>
<th>Google My Business</th>
<th>WhatsApp Business</th>
<th>CM</th>
<th>WeChat</th>
<th>Chat</th>
</tr>
</thead>
<tbody>
<tr>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>No</td>
<td>Yes</td>
<td>No</td>
</tr>
</tbody>
</table>
</div>

Automatic Messages (AKA System Messages) are predefined messages about events that occur in the conversation and are sent to the consumer as the events occur. Their purpose is to gain the consumer’s trust in the messaging channel by setting expectations and giving the consumer visibility over the agent’s availability. For more information on configuring automatic messages, please [click here](https://knowledge.liveperson.com/contact-center-management-messaging-operations-automatic-messages-automatic-messages-configuration.html).

## Mobile app SDK 3.8

### Type: New functionality

The mobile app SDK 3.8 release notes are now in the Developers Community. Please see release notes for [iOS](https://developers.liveperson.com/mobile-app-messaging-sdk-for-ios-latest-release-notes.html) and [Android](https://developers.liveperson.com/mobile-app-messaging-sdk-for-android-release-notes.html#android-messaging-sdk---version-380).

## New timestamp field of original event time (History Interaction API & Messaging Interaction API)

### Type: New functionality

A new field will be introduced for each SDE within "SDEs" section in the JSON response: originalTimeStamp. The field will contain the original creation time of the SDE, along (and in the same section) with the existing field, serverTimeStamp, which contains the enrichment time of the SDE. This change is backward compatible.

## Extend user authorization of Interaction History API to support rollover agent

### Type: Enhancement

Added the ability for Rollover Agents for a given account to have access to specific conversation endpoints so that they can retrieve previous conversations and transcripts of those conversations. This is accomplished by inspecting the request to see if the requesting user has the Rollover Agent Privilege. If the user has this privilege, we then verify that the account they are requesting information for has \`Common.Answering_Service\` enabled and the \`messaging.brand.rollover.config\` enabled with the set accountId matching that of the requesting rollover agent. If all these conditions are met the request is allowed to continue.

## Add support to capping on specific conversation flow

### Type: Enhancement

The API now allows sending costume capping configuration in the request body, also on specific conversation flow (search by conversation id).

## Messaging API - Post Conversation Survey (PCS) not filtering correctly by NPS

### Type: Bug Fix

There was missing indication that it requires to filter by child filters if the NPS is the only child filter. This bug is fixed.

## PCS: NPS filter return surveys with invalid answers

### Type: Bug Fix

NPS filter returned surveys with invalid answers when the search range included “0”. This bug is fixed.

## AC-Campaign - unable to read delta of Engagement

### Type: Bug Fix

In messaging-history api the ac-client for fetching campaign gets all the relevant information of the campaign. If however, the engagement is modified at a later date, the ac-client will identify it has some delta to fetch and when it will attempt to fetch this delta, it will catch an exception and the response of the modified field will be empty value. This bug is fixed by the adoption of new ac-campaign version.
