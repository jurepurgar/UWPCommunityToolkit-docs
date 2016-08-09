---
permalink: /en-US/api/Microsoft_Toolkit_Uwp_Services_Rss_RssHelper.htm
title: Microsoft.Toolkit.Uwp.Services.Rss.RssHelper API 
description: API page for Microsoft.Toolkit.Uwp.Services.Rss.RssHelper
keywords: windows, app, toolkit, UWP, API
layout: default
search.product: eADQiWindows 10XVcnh
---


# RssHelper class

Class with utilities for Rss related works.

## Members

The **RssHelper** class has this types of members

* [methods](#methods)

* [fields](#fields)

### methods

#### GetLink(System.Xml.Linq.XElement item,System.String rel)

Get feed url to see full original information.

##### parameters



| name | description | type |
#### GetSafeElementDate(System.Xml.Linq.XElement item,System.String elementName,System.Xml.Linq.XNamespace xNamespace)

Get item date from xelement, element name and namespace.

##### parameters



| name | description | type |
#### GetSafeElementDate(System.Xml.Linq.XElement item,System.String elementName)

Get item date from xelement and element name.

##### parameters



| name | description | type |
#### GetSafeElementString(System.Xml.Linq.XElement item,System.String elementName)

Get item string value for xelement and element name.

##### parameters



| name | description | type |
#### GetSafeElementString(System.Xml.Linq.XElement item,System.String elementName,System.Xml.Linq.XNamespace xNamespace)

Get item string value for xelement, element name and namespace.

##### parameters



| name | description | type |
#### SanitizeString(System.String text)

Removes \t characters in the string and trim additional space and carriage returns.

##### parameters



| name | description | type |
#### GetImage(System.Xml.Linq.XElement item)

Get feed image.

##### parameters



| name | description | type |
#### GetImageFromEnclosure(System.Xml.Linq.XElement item)

Get the item image from the enclosure element http://www.w3schools.com/rss/rss_tag_enclosure.asp

##### parameters



| name | description | type |
#### TryParseDateTime(System.String s,System.DateTime@ result)

Tries to parse the original string to a datetime format.

##### parameters



| name | description | type |
#### TimeZoneToOffset(System.String tz)

Calculate and return timezone.

##### parameters



| name | description | type |
#### GetImagesInHTMLString(System.String htmlString)

Retrieve images from HTML string.

##### parameters



| name | description | type |
### fields

#### WidthPattern

String for regular expression for width pattern.

#### RegexImages

Regular expression for image pattern.

#### RegexLinks

Regular expression for hyperlink pattern.

#### RegexHeight

Regular expression for height pattern.

#### RegexWidth

Regular expression for width pattern.

#### ImagePattern

String for regular expression for image pattern.

#### HeightPattern

String for regular expression for height pattern.

#### HiperlinkPattern

String for regular xpression for hyperlink pattern.

#### timeZones

Dictionary of timezones.