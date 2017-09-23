---
title: 'Login with Blizzard'
---

## Introduction

**Login with Blizzard** allows third-party developers applications or websites to extend the game experience leveraging Blizzard authentication services. From a developer perspective, it is easier to securely login to third-party sites surrounding Blizzard products and services that support **Log in with Blizzard**. Third-party developers have control afforded to them to allow Blizzard account holders the discretion to limit what should be shared with third-party sites. In return this allows developers to provide specialized services to verified Blizzard account holders.

## How it works

Here are a few ordered steps that outline the process for using **Login with Blizzard **on third-party applications or websites::

1. Any application or website that uses this function, will have a action **Log in with Blizzard**.
2. If necessary, a user will need log in to their Blizzard Account.
3. The user will see what special permissions (if any) the  application or site is requesting. The user at their discretion can disable access to specific data scopes Blizzard has created.
4. Press **OK** to grant the app or site access.
5. The user will be redirected to the original app or site.
6. For the next 30 days, Blizzard will remember the permissions given to the developer's application. Next time a user needs to login, just follow the **[Log in with Blizzard - How I**t](#heading=h.rcpvlfj5gt5z)** **works process again.

## Authorization

### Permissions

Users have control over what data they share with your application or website. Blizzard categorizes data sets it deems to be separated and should be permission controlled. Considering the data is more personal in nature and it could reveal concepts of association and ownership to an individual, Blizzard has decided to put these data sets behind the OAuth flow. In this authorization scheme developers must be granted access to this categorized data sets (known as scopes) to be able to retrieve and continually retrieve this personalized data from Blizzard products and services.

### Creating, modifying, delete permissions

When first logging into or reauthorizing an application a user can select what information they like to allow them to access in the **Log in with Blizzard** popup login window.

#### To first allow an application or websites access:

Follow the steps outline in the How it works section of this page.

#### To revoke an application's or website’s access:

1. Log in to the[ Blizzard Account](http://battle.net/account) site.
2. Select **Security Options**.
3. Select[ Authorized Applications](https://battle.net/account/management/authorizations.html). You’ll see a list of applications and the permissions you’ve granted them.
4. Find and remove the application you want to revoke.

#### To modify permissions that you've granted an application:

1. Log in to the[ Blizzard Account](http://battle.net/account) site.
2. Select **Security Options**.
3. Select[ Authorized Applications](https://battle.net/account/management/authorizations.html). You’ll see a list of applications and the permissions you’ve granted them.
4. Find and revoke the application you want to modify.
5. Go back to the site/application and login again using **Log in with Blizzard**.
6. When prompted, only grant the application access to the data you want to share.

### Expired Access

Blizzard may ask you to reauthorize an application to access user scoped details for several reasons:

* According to Blizzard, granted access_tokens are valid for 30 days. Once the access_token expires, Blizzard will ask the user to re-confirm that the application can access previously selected account information.
* Developer application or site may have added additional permissions. To get more information from Blizzard, the user permission is required.
* The application or site may want more permissions than originally provided by the user. If this happens, using the OAuth flow the user will be redirected to Blizzard to login. If the user is already logged in, Blizzard will show you a list of permissions being requested. For example, to allow a site or app to show their World of Warcraft characters, it might ask for permission to read their World of Warcraft character list.

## User Security

It is important for your application or site and for your users sake to take seriously the vulnerable nature of the Internet. It is not unheard of a breaking news story of security breaches and information being stolen. It is not a matter of if a security breach will happen, but if and when and how much users are educated with best practices when navigating the world wide web.

Having a user log into their Blizzard Account from a third-party application or website can be a source of nervousness, especially with the reputation of a new service being unknown. 

Here are a few steps a user can use to make sure the Blizzard Account is secure with **Log in with Blizzard** when logging in from third-party :
* Check that the login site says **https://battle.net**.
* If a user is not sure if the site is secure, recommend for them to open a new browser window and visit[ battle.net](https://battle.net) login directly. Once logged in, return to the third-party site. If the website is secure, the user will be able to access the site without needing to login, since they are already logged in to Blizzard.

## Developer Security

As a developer you hold a degree of responsibility and reputation when working with Blizzard APIs and user personal data. Remember Blizzard is holding your application or website to a set policy, which you can be read at the [API Terms of Service](https://dev.battle.net/policy).

Here some general good and security practices when working with the APIs:

* Always use encrypted protocols (e.g. https) and secure-socket connections (e.g. ssh) when making requests.
* Always make sure to use end-to-end (client to server) encryption. Avoid middle-ware transmission wherever possible, which could lead to man in the middle attacks between networked applications.
* Never give out or use your Application client_id or client_secret.
* Never use client-side requests to authorize access. Client side applications are prone to be hacked, data-mined, or sourced for information. It is highly recommended to use a server side application.
* Salt any sensitive stored information. Something that is prone to database injection and query could open up reading sensitive data like your Application client_id and client_secret, it would be better to salt this information to keep it more obscure. 
* **Do NOT try to collect Blizzard account information (username/email and password) for any reason. This is strictly prohibited and not the authorization flow**

