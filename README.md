# Awesome EPiServer [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of EPiServer CMS & Commerce goodness and other resources.

## CMS

### Reference Architecture

#### AlloyDemoKit [[source](https://github.com/episerver/AlloyDemoKit)]

A version of the Alloy reference site containing additional features for demoing purposes. This is not intended to be a starter solution but provides the ability to showcase a number of features and add-ons that may be needed for a demo.

### Code Snippets

#### Remove UI components for some editors [[blog](https://www.david-tec.com/2016/05/remove-episerver-ui-components-for-certain-editors/)]

Limited UI targeting specific group of editors.

#### Thumbnail for image properties [[blog](https://tedgustaf.com/blog/2016/display-thumbnail-for-image-properties-in-episerver/)]

Replace the default editor for image properties in Episerver to display a thumbnail of the selected image.

#### Visually compare page versions with markup [[blog](https://gregwiechec.com/2015/11/compare-page-versions-with-markup/)]

It allows editor to visually check the differences between two pages. The compare page versions with markup view is similar to previous solution, but instead of comparing data on property level, whole HTML is compared.

### Add-Ons

#### Possible.Robots Txthandler [[nuget](https://nuget.episerver.com/en/OtherPages/Package/?packageId=POSSIBLE.RobotsTxtHandler), [source](https://github.com/markeverard/POSSIBLE.RobotsTxtHandler)]

Add management of your robots.txt file straight from the CMS

#### MenuPin [[nuget](https://nuget.episerver.com/en/OtherPages/Package/?packageId=MenuPin), [source](https://github.com/davidknipe/MenuPin)]

Add the ability to pin the menu bar in the episerver admin

#### 404 Handler [[nuget](https://nuget.episerver.com/en/OtherPages/Package/?packageId=BVN.404Handler), [source](https://github.com/BVNetwork/404handler)]
Allows your content team to manage 404 redirects.

#### PixieEPiServerExtensionMaxMindGeoIP2 [[nuget](https://nuget.episerver.com/en/OtherPages/Package/?packageId=PixieEPiServerExtensionMaxMindGeoIP2), [source](https://github.com/khurramkhang/Maxmind.GeoIP)]

Allows you to use paid Maxmind databases for better accuracy.

#### RRS Feed [[nuget](https://nuget.episerver.com/en/OtherPages/Package/?packageId=Chief2moro.SyndicationFeeds), [source](https://github.com/markeverard/Chief2moro.SyndicationFeeds)]

Flexible ATOM/RSS feed creation for EPiServer CMS

#### EPi.Extensions [[nuget](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.EPi.Extensions), [source](https://github.com/Geta/EPi.Extensions)]

EPi.Extensions is library with useful extension methods and helpers for EPiServer.

#### EPiServer Instant Templates [[source](https://github.com/Geta/InstantTemplates)]

Allows editors to create their own templates directly from within EPiServer.

#### Tags [[nuget](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.Tags), [source](https://github.com/Geta/Tags)]

Geta Tags is library that adds tagging functionality to EPiServer content.

#### Media reference selector [[nuget](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.Epi.MediaReferenceSelector), [source](https://github.com/Geta/Epi.MediaReferenceSelector)]

This module replaces the built-in media content reference editors in Episerver and adds possibility to upload files directly without having to go the extra step through the assets panel.

#### Geta.Epi.FontThumbnail [[nuget](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.Epi.FontThumbnail), [source](https://github.com/Geta/Epi.FontThumbnail)]

Generates images based on FontAwesome or custom icon font, to be shown when creating new content in Episerver.

#### HotspotsEditor [[source](https://github.com/Geta/Geta.EPi.HotspotsEditor)]

Originaly created by Oxx and BVNetwork in their [CommerceStarterKit](https://github.com/BVNetwork/CommerceStarterKit), extracted out by Geta. 

## Commerce

### Reference Architecture

#### Quicksilver [[source](https://github.com/episerver/Quicksilver)]

Is the starter site for the EPiServer Commerce reference implementation

#### SocialQuicksilver [[source](https://github.com/episerver/SocialQuicksilver)]

Demonstrates the use of Episerver Social in an e-commerce scenario.

### Add-Ons

#### Google Product Feed for Episerver [[blog](https://getadigital.com/no/blogg/google-product-feed-for-episerver/), [nuget](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.GoogleProductFeed), [source](https://github.com/Geta/GoogleProductFeed)]

Allows developers to create Google Shopping feed easier

#### Klarna Checkout Module [[nuget](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.EPi.Commerce.Payments.Klarna.Checkout), [source](https://github.com/Geta/EPi.Commerce.Payments/tree/master/Geta.EPi.Commerce.Payments.Klarna.Checkout)]

Geta.EPi.Commerce.Payments.Klarna.Checkout is library which helps to integrate Klarna Checkout as one of the payment options in your EPiServer Commerce sites.

## Cms and Commerce

### Add-Ons

#### Geta SEO.SiteMaps [[nuget cms](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.SEO.Sitemaps), [nuget commerce](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.SEO.Sitemaps.Commerce), [source](https://github.com/Geta/SEO.Sitemaps)]

This tool allows you to generate xml sitemaps for search engines to better index your EPiServer sites

#### Geta Episerver geolocation tools [[nuget cms](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.Epi.GeolocationTools), [nuget commerce](http://nuget.episerver.com/en/OtherPages/Package/?packageId=Geta.Epi.GeolocationTools.Commerce), [source](https://github.com/Geta/EPi.GeolocationTools)]

This library can be used to retrieve the languagebranch which matches the given request best. It provides methods to retrieve a preferred languagebranch by a users' geolocation, browser language preference or both. The commerce library can be used to find the right market and corresponding language based on the same parameters. Useful to prompt the user that a different language might suit him/her better. Useful for setting the right market for a user or for suggesting a specific market and language. Builds on top of Episervers' built in support for geolocation