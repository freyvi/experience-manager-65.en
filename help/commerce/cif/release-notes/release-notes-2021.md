---
title: AEM Content and Commerce Release Notes 2021
description: AEM Content and Commerce Release Notes 2021
---
# Commerce Integration Framework GitHub Release Overview

## Overview of System Requirements

Review the minimum system requirements in the table below for the CIF version you are currently using or plan to use in the future.

**CIF add-on now available via [Adobe Software Distribution](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html). The old AEM CIF Connector is going into maintenance mode and should not be used anymore. Please migrate to the new CIF add-on.**

|Component| System Requirements|
|:-------|:-----:|
|CIF add-on |Minimum: AEM 6.5.7, Magento 2.3.5 GraphQL schemas|
|CIF Core Components |[System Requirements](https://github.com/adobe/aem-core-cif-components/blob/master/VERSIONS.md)|
|AEM Project Archetype |[System Requirements](https://github.com/adobe/aem-project-archetype/blob/master/VERSIONS.md)|

## Release Date: April, 2021

|Component| Version| Details|
|:-------|:-----:|---------------------:|
|CIF add-on | 2021.04.22|[Software Distribution](https://experience.adobe.com/#/downloads/content/software-distribution/en/aem.html?package=%2Fcontent%2Fsoftware-distribution%2Fen%2Fdetails.html%2Fcontent%2Fdam%2Faem%2Fpublic%2Faem-commerce-addon-65-2021.04.22.zip)|
|CIF Core Components |1.10.0|[GitHub](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Venia Reference Site| 2021.04.22|[GitHub](https://github.com/adobe/aem-cif-guides-venia/releases)|

### What's New {#what-is-new-april}

* Support for category UID - This unlocks third party commerce integrations for systems that use Strings for category ids

* AEM extension for PWA Studio incl. example integration

* New CIF navigation core component that extends WCM navigation core component

* Visual indicator for staged catalog data in AEM storefront

### Bug fixes {#bug-fixes-april}

* The root category field was not displayed under the commerce tab in the page properties of category pages

## Release Date: March, 2021 {#what-is-new-march}

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 1.9.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |1.9.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Venia Reference Site| 2021.03.25|[Release Notes](https://github.com/adobe/aem-cif-guides-venia/releases)|

### What's new

* Support for Magento 2.4.2

### What's Improved

* Improved reusability of product detail component for content driven pages

* Better caching and less backend calls for PDPs

* Multiple bug fixes.

## Release Date: February, 2021

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 1.8.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |1.8.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Venia Reference Site| 2021.02.24|[Release Notes](https://github.com/adobe/aem-cif-guides-venia/releases)|

### What's New {#what-is-new-february}

* Product Experience Management: Enrich product catalog pages individually with Experience Fragments.

* Extended product console properties to show linked Assets and Experience Fragments, including action to quickly navigate to the associated content.

### What's Improved  {#what-is-improved-february}

* Enhanced client-side data layer with product image url and category information.

* Multiple bug fixes.

## Release Date: January, 2021

|GitHub| Version| Detailed Release Notes|
|:-------|:-----:|---------------------:|
|CIF Connector | 1.7.0|[Release Notes](https://github.com/adobe/commerce-cif-connector/releases)|
|CIF Core Components |1.7.0|[Release Notes](https://github.com/adobe/aem-core-cif-components/releases)|
|CIF Venia Reference Site| 2021.02.02|[Release Notes](https://github.com/adobe/aem-cif-guides-venia/releases)|

### What's New {#what-is-new-january}

* Product Experience Management: New 'Commerce' property tab for Assets and Experience Fragments. This tab enables you to link Assets and Experience Fragments to products & categories. The tab also shows real-time data for linked commerce objects and a link to show details in the product console.

### What's Improved  {#what-is-improved-january}

* Send user data after authentication to Adobe Client Data Layer.

* Multiple bug fixes.
