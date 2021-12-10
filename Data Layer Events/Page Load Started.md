# Page Load Started

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Page Load Started",
    "page": {
        "pageCategory": "<pageCategory>",
        "pageName": "<pageName>",
        "pageType": "<pageType>",
        "platform": "<platform>",
        "siteCountry": "<siteCountry>",
        "siteCurrency": "<siteCurrency>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|pageCategory|string|General category or Site Section of the page. Top level of page hierarchy.|Home, About Us, Shop, Account, Blog, Investors|||||||
|pageName|string|Describes the page and its content specifically. |product - XYZ123, Mens - Tops - Sweaters, Order Confirmation|||||||
|pageType|string|Describes what purpose the page serves. Often aligns with the CMS template.|Home, Event Detail, Property Detail, Product Listing, Blog Post, Shopping Cart|||||||
|platform|string|The technology platform version of the site that the user is experiencing.||||||||
|siteCountry|string|Indicates the primary country served by the site. ISO 3166 \(alpha-2\) Uppercase.|US, CA, FR, UK|^[A-Z]{2}$||||||
|siteCurrency|string|Currency in which prices are displayed.  ISO 4217 \(3 character alpha\), uppercase|USD, CAD, EUR, GBP, CHF|^[A-Z]{3}$||||||




