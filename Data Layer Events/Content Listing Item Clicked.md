# Content Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Content Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "content": {
                    "contentAuthor": "<contentAuthor>",
                    "contentDate": "<contentDate>",
                    "contentID": "<contentID>",
                    "contentTitle": "<contentTitle>",
                    "itemPosition": <itemPosition>
                }
            }
        ]
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|listingItemClicked.listing[n].content.contentAuthor|string|Unique identifer of the content author.|Betsy Ross, Ben Franklin, Howard Hughes, Tipper Gore|||||||
|listingItemClicked.listing[n].content.contentDate|string|Date of the content's publication. ISO 8601 form \(YYYY-MM-DD\). Jan 1, 2019 is 2019-01-01|2001-12-22, 2011-01-01|^([0-9]{4})-(1[0-2]|0[1-9])-(3[01]|0[1-9]|[12][0-9])$||||||
|listingItemClicked.listing[n].content.contentID|string|Unique identifer of the content.||||||||
|listingItemClicked.listing[n].content.contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|listingItemClicked.listing[n].content.itemPosition|integer|Captures the position of each content item in a content listing. |1, 2, 3, 4, 5|||||||




