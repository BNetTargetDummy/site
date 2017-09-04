---
title: 'Game Data APIs'
---

## Introduction

Game Data API resource endpoints are the newest addition to the Blizzard Battle.net consumable data sets. The Game Data APIs are Blizzard commitment to share data with third-party developers. This allows Blizzard teams to use a single, well-defined interface to publish data in an easily consumable and expected format.

## Differences between the Community API and Game Data API

There are several key differences to the schema structure and conventions applied compared to the Community API endpoints. The Community API data sets were intended with an ad-hoc implementation which could be prone to errors once internal changes happened for Blizzard properties. In comparison, the tactic used for the Game Data data sets is self-documenting response structures, the introduction of namespaces, OAuth client_credential authorization strategy, and localization. 

## Differences between the Profile API and Game Data API

The difference between Game Data and Profile APIs is the type of data they handle. The Profile API is used to store data related controlled by individuals (which is calledl profile data). In comparison, the Game Data API stores reference data related to a game itself (which is called static data) and constantly changing world related data, which may reference to profile documents, but is not wholly owned by any individual (which is called dynamic data). 

## Concepts

### Self- Documenting Response structures

What this entails is as top level parent pathed items of a resource are queried, information can be discovered. The existing Community APIs are known to perform business computations on a predetermined mapped data sets to formulate a response. In comparison, the Game Data APIs return JSON responses directly to the consumer in the exact format and structure they are stored. The only time when a document is returned in a different format than that which it is stored is when the consumer makes a request that includes a localization identifier.

### Namespaces

With the Game Data / Profile APIs Blizzard introduced a new concept called a "namespace". Similar to how namespaces work in programming languages to group and separate resources or classes, namespaces allow publishing of multiple documents to a single endpoint without overwriting an existing document. This allows multiple versions of that document to remain accessible within a specific context.

NOTE: Blizzard has stated that although this allows multiple instances of the same type of document to coexist, namespaces should not be considered strict or semantic versioning.

#### How to specify a namespace?

There are currently two methods for specifying a namespace when making a request to the Game Data / Profile APIs, a ‘?namespace=query’ parameter, or a ‘Battlenet-Namespace’ request header.

<table>
  <tr>
    <td>Type</td>
    <td>Name</td>
  </tr>
  <tr>
    <td>Query Parameter</td>
    <td>?namespace=</td>
  </tr>
  <tr>
    <td>Request Header</td>
    <td>Battlenet-Namespace</td>
  </tr>
</table>


#### What data is namespaced?

All data published to the Game Data / Profile APIs are published to namespaces, however, the naming strategies and when they change are determined by the specific publisher of the API. For information on a specific game's namespacing strategy, refer to the documentation for that game and API under the Game Data APIs header on the right-side navigation.

### OAuth

The Game Data APIs like the Profile APIs follow a OAuth process. To understand how to use OAuth process it is best to look at the Topic - OAuth.

#### OAuth Resources

Currently three Blizzard Games make use of the Game Data API document structure.

Diablo 3

Starcraft 2

World of Warcraft

Note: Blizzard states that the these endpoints are intended to replace most of the Community Data API resource endpoints. Currently this is still a work-in-progress so no official deprecation notice has been given.

References

https://dev.battle.net/docs/read/game_data_apis