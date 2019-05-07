# ![LOGO](logo.png) Most Popular **flow**ground Connector

## Description

A generated **flow**ground connector for the Most Popular API (version 2.0.0).

Generated from: https://api.apis.guru/v2/specs/nytimes.com/most_popular_api/2.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:20+03:00

## API Description

Get lists of NYT Articles based on shares, emails, and views.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Most Emailed by Section & Time Period

#### Input Parameters
* `section` - _required_ - Limits the results by one or more sections. You can use
`all-sections` or one or more section names seperated by semicolons. See `viewed/sections.json` call to get a list of sections. 

    Possible values: Arts, Automobiles, Blogs, Books, Business Day, Education, Fashion & Style, Food, Health, Job Market, Magazine, membercenter, Movies, Multimedia, N.Y.%20%2F%20Region, NYT Now, Obituaries, Open, Opinion, Public Editor, Real Estate, Science, Sports, Style, Sunday Review, T Magazine, Technology, The Upshot, Theater, Times Insider, Today's Paper, Travel, U.S., World, Your Money, all-sections.
* `time-period` - _required_ - Number of days `1 | 7 | 30 ` corresponds to a day, a week, or a month of content.
    Possible values: 1, 7, 30.

### Most Shared by Section & Time Period

#### Input Parameters
* `section` - _required_ - Limits the results by one or more sections. You can use
`all-sections` or one or more section names seperated by semicolons. See `viewed/sections.json` call to get a list of sections. 

    Possible values: Arts, Automobiles, Blogs, Books, Business Day, Education, Fashion & Style, Food, Health, Job Market, Magazine, membercenter, Movies, Multimedia, N.Y.%20%2F%20Region, NYT Now, Obituaries, Open, Opinion, Public Editor, Real Estate, Science, Sports, Style, Sunday Review, T Magazine, Technology, The Upshot, Theater, Times Insider, Today's Paper, Travel, U.S., World, Your Money, all-sections.
* `time-period` - _required_ - Number of days `1 | 7 | 30 ` corresponds to a day, a week, or a month of content.
    Possible values: 1, 7, 30.

### Most Viewed by Section & Time Period

#### Input Parameters
* `section` - _required_ - Limits the results by one or more sections. You can use
`all-sections` or one or more section names seperated by semicolons. See `viewed/sections.json` call to get a list of sections. 

    Possible values: Arts, Automobiles, Blogs, Books, Business Day, Education, Fashion & Style, Food, Health, Job Market, Magazine, membercenter, Movies, Multimedia, N.Y.%20%2F%20Region, NYT Now, Obituaries, Open, Opinion, Public Editor, Real Estate, Science, Sports, Style, Sunday Review, T Magazine, Technology, The Upshot, Theater, Times Insider, Today's Paper, Travel, U.S., World, Your Money, all-sections.
* `time-period` - _required_ - Number of days `1 | 7 | 30 ` corresponds to a day, a week, or a month of content.
    Possible values: 1, 7, 30.

## License

**flow**ground :- Telekom iPaaS / nytimes-com-most-popular-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
