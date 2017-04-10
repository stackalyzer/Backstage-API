# Backstage-API

## Table of Contents
1. [Authentication and General API Usage](#1-authentication-and-general-api-usage)
2. [Campaign Items](#2-campaign-items)
3. [Campaigns](#3-campaigns)
4. [Dictionary](#4-dictionary)
5. [Errors](#5-errors)
6. [Reports](#6-reports)
7. [Users](#7-users)


## 1. Authentication and General API Usage

## 2. Campaign Items

Relevant only for advertisers.
The following operations are available via the API:
1. Fetch a List of Items for a specific Campaign - Fetch all of the Items associated with a certain Campaign.
2. Fetch a Single Item from a Campaign - Fetch a single Item associated with a certain Campaign.
3. Create an Item - Create a new Item in a specific Campaign.
4. Update an Item - Update an existing Item.
5. Delete (Stop) an Item - Move an existing Item to a 'STOPPED' status.
6. Fetch Children Items of an RSS Item
7. Fetch a specific Child Item of an RSS Item
8. Update a child of an RSS Item

## 3. Campaigns

Relevant only for advertisers.
The following operations are available via the API:
1. Fetch a List of Campaigns - Fetch a list of Campaigns associated with a specific partner account.
2. Fetch a Single Campaign - Fetch a single Campaign resource using the Campaign ID.
3. Create a Campaign - Create a new Campaign under a specific partner account.
4. Update a Campaign - Update an existing Campaign of a specific partner account

## 4. Dictionary

The dictionary allows to get from Taboola lists of possible values and their meaning in various contexts (enum’s and their relevant codes). This is used in order to get predefined allowed values to be selected by the user. 
For example, if the user would like to target specific countries, the dictionary will allow to get the possible country values supported in Taboola and display them as selectable options to the user.

The following dictionaries are available via the API:
1. Generic dictionaries:
  a. Get a list of dictionaries.
  b. Get a list of supported countries and regions.
  c. Get a list of supported platforms.
2. Resource specific dictionaries:
  a. Get a list of possible enum values that relate to campaigns.
  b. Get a list of possible enum values that relate to items.

## 5. Errors

The Backstage API returns errors in a JSON format. The response body will contain an object with several fields, and the HTTP status will be set appropriately.
This documnet details the different errors you can get and their meanings.

## 6. Reports
The document details the different reports you can pull using the API, including supported dimensions and filters.

## 7. Users

The API enables you to fetch a list of the user's allowed Accounts.
