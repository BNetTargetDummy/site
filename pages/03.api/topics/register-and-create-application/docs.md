---
title: 'Register and create application'
---

There are a few introductory steps that are required before you are able to make requests to Blizzard API endpoints and retrieve resource data.

Blizzard uses a third party service called [Mashery](http://www.mashery.com/) in order to provide their services and documentation. The service powers APIs of leading brands in retail, media, business services, software, and more. By signing in to a Mashery powered portal, you can gain access to Mashery's base of API providers. All with a single Mashery ID.

Regarding this situation, developers must register a new user account that does not use the login credentials of Battle.net account. Due to the severe security implications of using the same email and password in other services, it is highly recommended to use an email address and password that is different from the services you typically use.

Please use proper security practices and use strong password conventions. This is especially true considering the fact that malicious intent could be used in conjunction with the credentials associated with your registered Applications. It is important to keep a security barrier to prevent that could affect the reputation of Blizzard reserves the right and discretion to terminate the account and any associated applications that may be live.#

## Registering a Developer Account
An account can be created here:
[https://dev.battle.net/member/register](https://dev.battle.net/member/register)

Description of the fields that must be filled out:
<table>
  <tr>
    <td>Field Name</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>Username</td>
    <td>Name used to log into Mashery</td>
  </tr>
  <tr>
    <td>Display Name</td>
    <td>Display name for public profile, others can see this name</td>
  </tr>
  <tr>
    <td>Email</td>
    <td>Email address, contact required to be verified by a confirmation email Blizzard sends out. </td>
  </tr>
  <tr>
    <td>Password</td>
    <td>Password to log into the Masery Service</td>
  </tr>
</table>

It is known a few Email providers sometimes do not receive the confirmation email from Blizzard. Please let up to 1 hour in order to receive an email and also make sure to check your SPAM folder. Unfortunately at this time there is no way to resend the confirmation email. As a last resort contact Blizzard API support at [api-support@blizzard.com](mailto:api-support@blizzard.com). Please provide the account username and time you sent the original request. Responses are typically only given during normal business hours, please allow up to 3 business days to receive acknowledgement. Typically Blizzard will approve the user account with further intervention.

## Registering an Application
After registering a developer account, a application must be added to the account created here:
[https://dev.battle.net/apps/myapps](https://dev.battle.net/apps/myapps)

<table>
  <tr>
    <td>Fieldname</td>
    <td>Description</td>
  </tr>
  <tr>
    <td>Name of your Application</td>
    <td>Used to help you recognized your applications. When implementing the OAuth authorization flow, the name will be displayed to a user when trying to retrieve the ‘access_token’.</td>
  </tr>
  <tr>
    <td>Website</td>
    <td>A valid hostname that is associated with the application (if there is one). When implementing the OAuth authorization flow, the name will be displayed to a user when trying to retrieve the access token.</td>
  </tr>
  <tr>
    <td>Describe</td>
    <td>A text description for what you are going to do with the key. Blizzard uses this for internal use to understand what your application is meant to do.</td>
  </tr>
  <tr>
    <td>Register Callback URL</td>
    <td>Only used for OAuth flows. When implementing the OAuth authorization flow, the redirect hostname passed during the flow must match ‘website’ hostname. For security purposes, communication must be done over an encrypted https protocol through SSL</td>
  </tr>
  <tr>
    <td>Which Franchises</td>
    <td>Internal to Blizzard statistics, allowing them to measure API usage.</td>
  </tr>
</table>