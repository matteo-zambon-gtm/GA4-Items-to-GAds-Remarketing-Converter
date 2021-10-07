# GA4-Items-to-Gads-Dynamic-Remarketing-Converter
**Do you use Items object of Google Analytics 4 in your dataLayer?**

Well, this variable is a smart way to track the Google Ads Dynamic Remarketing using the GA4 items.


**Guide step by step:**

## Import the custom variable from the gallery

Go to the GTM gallery variable and search "GA4 Items to GAds Dynamic Remarketing Converter"


## The configuration: import the template variable

1) Go to User-Defined Variables 
2) Click Discover more variable type in the Community Template Gallery 
3) Search GA4 Items to GAds Dynamic Remarketing Converter
4) Import the Template Variable

![GA4 items to GAds Dynamic Remarketing Converter - Community Template](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/10/GA4-items-to-GAds-Dynamic-Remarketing-Converter-Community-Template.png)

## Choose the type of Dynamic Remarketing 

You can choose the type of GAds dynamic remarketing:

- **Event Data** (the new GAds dynamic remarketing). This option is suggested :)

![Event type GA4 Items to GAds Dynamic Remarketing Converter](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/10/Event-type-GA4-Items-to-GAds-Dynamic-Remarketing-Converter.png)

- **Custom parameters** (the old ecomm_pagetype, ecomm_prodid, ecomm_totalvalue)

![Custom parameters GA4 Items to GAds Dynamic Remarketing Converter](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/10/Custom-parameters-GA4-Items-to-GAds-Dynamic-Remarketing-Converter.png)

## Custom parameters the type of Dynamic Remarketing 

If you want to use the old version, you have to simply create the custom variable with this option.

Then you create the GAds Tag Remarketing:
1) Go to Custom Parameters and select Use Data Layer
2) Choose the name of the variable (in my case GAds Dynamic Remarketing - Custom Parameters)

![GAds Tag - Custom parameters GA4 Items to GAds Dynamic Remarketing Converter](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/10/GAds-Tag-Custom-parameters-GA4-Items-to-GAds-Dynamic-Remarketing-Converter.png)


- Type: Event Data 
- Type: Custom Parameters

If you choose Event Data you have to create 2 variables:
- Event Value
- Event Items

# Update your Google Ads Remarketing Tag:
## Open your Google Ads Remarketing Tag

In Google Ads Remarketing Tags on the **"Event Value"** choose the variable **GA4 Items to GAds Dynamic Remarketing Converter** with Event Value selected. 
The same thing on Event Items Parameters


![use GA4 Items to Facebook Object Converter variable on your Facebook Tag](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/06/use-GA4-Items-to-Facebook-Object-Converter-variable-on-your-Facebook-Tag.png)


# Now Debug it :)

Ok, go to debug it :)

![debug 1](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/06/debug-1.png)

![debug 2](https://www.tagmanageritalia.it/GTM/guida/uploads/2021/06/debug-2.png)

Great, it works. Now you can use the same data of GA4 directly on your Facebook Tag!

Let me know if it is helpful for you

Buon Tag :)
