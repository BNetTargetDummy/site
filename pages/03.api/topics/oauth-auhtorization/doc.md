---
title: 'OAuth Auhtorization'
---

## What is OAuth?

As taken from the OAuth website [https://oauth.net](https://oauth.net), OAuth is an open protocol to allow secure authorization in a simple and standard method from web, mobile and desktop applications.

Due to the "open" versatility of the OAuth 2.0 it often contributes to a source of confusion among first time developers. The goal with this document is to clarify common points of uncertainty, and a basic guide to incorporating the process into your application.

## Using OAuth

The Blizzard APIs use OAuth 2.0, a standard that gives flexibility in the authentication and thus authorization of specific data sections for various API endpoints. OAuth specifically allows developers Blizzard to depend on authentication for both application and user OAuth flows. In a less technical outlook, it is a series of steps a application must perform before it is allowed to access data.

## Overview

A good analogy to this is to think of your application as a person trying to enter a secure location like a building. In order to access the building you need an access token also known as a key. There is a catch, the locks are changed after an interval of time and you must request a new key from the building manager to continue to access the same building. The OAuth process is a transaction process to get the key so you can access the building.

## How it works

Understanding how the OAuth works, the steps involved, and a general picture will help clarify the process involved.  It is important to understand that OAuth is an authentication process. Since it is a process it can be adapted to different use case where access control is needed. More specifically it can be adapted to allow an application (the client) requesting access to any nonspecific or specific service (the server). A common practice is to authorize an application access to a set of generic (non-user defined) data resources or a specific user data resource.

There are currently 2 authentication workflows employed by the current Blizzard APIs

1. Client Credential OAuth Flow
2. User OAuth Flow

## Client Credential OAuth flow

The client credential flow is specifically used when the application (client) is trying to access generic (non-user defined) data resources. An example of this must used with the Game Data APIs for Diablo 3, Starcraft 2, and World of Warcraft resource data sets..

The steps to retrieve the required access_token to gain access to these types of data resources are as follows. NOTE: You must already have created a registered application in Blizzard’s Mashery Application page to proceed, you can find out how to do that here:

1. Retrieve Application client_id and client_secret from Blizzard’s Mashery Application page.
2. Make a request to 

## User OAuth flow

OAuth Libraries

Regarding OAuth flow open ended nature to implementation, it is highly recommended to uses a tested library that handles this process for you. Here is a list of commonly used libraries sorted by language:

Warning! We do not guarantee this list to be up-to-date with the latest versions. It is also worth noting that although some of these libraries might look like they are no longer maintained, this is not necessarily the case. OAuth is a specification for message exchange for authorization of an application, therefore when the specific is implemented it is rare to see changes in the codebase. However it is highly recommended the library maintains good policy on security patches and is diligent in patching known vulnerabilities.

