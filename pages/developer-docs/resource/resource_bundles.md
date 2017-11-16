---
type: landing
directory: developer-docs/installation
title: Install Sunbird on Laptop
page_title: Install Sunbird on Laptop
description: Installing Sunbird requires two primary software components, the Sunbird portal or web application, and the Sunbird services stack or the backend API interface.
published: true
allowSearch: true
---
Rendering sunbird portal pages in multiple languages , user can view page elements in their prefered language.

## How Resource Bundle Work

The Resource Bundle reads a property file based on the locale and name suffix used in the naming of the property. For example, consider a label file named en.properties. This file is read by ResourceBundle helper(app/helpers/resourceBundlesHelper.js) and it will generate js file in app/common folder .
Locale represents a region or location with its attributes. Locale is generally used to maintain details about the client using our application. Locale contains attributes of location and language to be used for the respective location. Thus, a Locale assists ResourceBundle to pick the right label file by determining the location to which the user belongs.

