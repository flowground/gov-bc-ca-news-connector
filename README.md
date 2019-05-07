# ![LOGO](logo.png) BC Gov News API Service 1.0 **flow**ground Connector

## Description

A generated **flow**ground connector for the BC Gov News API Service 1.0 API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/gov.bc.ca/news/1.0/openapi.json<br/>
Generated at: 2019-05-07T17:42:12+03:00

## API Description

News API

## Authorization

This API does not require authorization.

## Actions

### Get a Facebook post based on a Uri

*Tags:* `FacebookPosts`

#### Input Parameters
* `uri` - _optional_
* `api-version` - _required_ - The requested API version

### Returns the top level content for the home page

*Tags:* `Home`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get all ministries

*Tags:* `Ministries`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the Ministry associated with the ministry key

*Tags:* `Ministries`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

### Get the Minister associated with the ministry key

*Tags:* `Ministries`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

### Get all newsletters

*Tags:* `Newsletters`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the image object reference by of a Newsletter Edition associated with the image guid

*Tags:* `Newsletters`

#### Input Parameters
* `guid` - _required_
* `api-version` - _required_ - The requested API version

### Get a specific newsletter

*Tags:* `Newsletters`

#### Input Parameters
* `newsletterKey` - _required_
* `api-version` - _required_ - The requested API version

### Returns a specific edition of a newsletter

*Tags:* `Newsletters`

#### Input Parameters
* `newsletterKey` - _required_
* `editionKey` - _required_
* `api-version` - _required_ - The requested API version

### Get an article belonging to a Newsletter edition

*Tags:* `Newsletters`

#### Input Parameters
* `newsletterKey` - _required_
* `editionKey` - _required_
* `articleKey` - _required_
* `api-version` - _required_ - The requested API version

### Get the posts associated with the keys in the list passed in.

*Tags:* `Posts`

#### Input Parameters
* `postKeys` - _optional_
* `api-version` - _required_ - The requested API version

### Get all keys for the specified index (newsroom or category)

*Tags:* `Posts`

#### Input Parameters
* `indexKind` - _required_ - home or one of categories
* `indexKey` - _required_ - default or one key of the categories (ministries, sectors, services, tags, themes)
* `postKind` - _optional_ - One of: releases, stories, factsheets, updates or default (releases+stories+factsheets)
* `count` - _optional_ - number of posts to return
* `skip` - _optional_ - number of posts to skip
* `api-version` - _required_ - The requested API version

### Get the post key associated with the reference.

*Tags:* `Posts`

#### Input Parameters
* `reference` - _required_
* `api-version` - _required_ - The requested API version

### Get the latest posts of postKind for the specified index (default or category)

*Tags:* `Posts`

#### Input Parameters
* `indexKind` - _required_ - home or one of categories
* `indexKey` - _required_ - default or one key of the categories (ministries, sectors, services, tags, themes)
* `postKind` - _optional_ - One of: releases, stories, factsheets, updates or default (releases+stories except top/feature)
* `count` - _optional_ - number of posts to return
* `skip` - _optional_ - number of posts to skip
* `api-version` - _required_ - The requested API version

### Gets the latest Social Media post for the social media type passed in.

*Tags:* `Posts`

#### Input Parameters
* `mediaType` - _required_
* `api-version` - _required_ - The requested API version

### Get the post associated with the key

*Tags:* `Posts`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

### Get all resource links

*Tags:* `ResourceLinks`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get all Sectors

*Tags:* `Sectors`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the sector associated with the key

*Tags:* `Sectors`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

### Get all Services

*Tags:* `Services`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the service associated with the passed key

*Tags:* `Services`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

### Get all Slides

*Tags:* `Slides`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the slide associated to the id

*Tags:* `Slides`

#### Input Parameters
* `id` - _required_
* `api-version` - _required_ - The requested API version

### Get all Tags

*Tags:* `Tags`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the Tag associated with the key

*Tags:* `Tags`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

### Get all Themes

*Tags:* `Themes`

#### Input Parameters
* `api-version` - _required_ - The requested API version

### Get the Theme associated with the key

*Tags:* `Themes`

#### Input Parameters
* `key` - _required_
* `api-version` - _required_ - The requested API version

## License

**flow**ground :- Telekom iPaaS / gov-bc-ca-news-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
