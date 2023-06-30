# Page Load Started

### Page Load Started is part of the page load sequence, including virtual page loads in the case of single page apps, and must be the first event pushed in the page load event sequence.

## Javascript Code
```js
window.appEventData = window.appEventData || [];
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "internalBusinessOwner": "<internalBusinessOwner>",
        "pageName": "<pageName>",
        "pageTitle": "<pageTitle>",
        "pageType": "<pageType>"
    }
});
```

## Variable Definitions

|Path|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|page.internalBusinessOwner|string|Describes the internal team who manages this particular page of the website.|XX product management, marketing, vendor name|||||||
|page.pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|page.pageTitle|string|HTML title tag for the page||||||||
|page.pageType|string|Describes what purpose the page serves. Often aligns with the CMS template.|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||




