# Minimal Crypto Tracker

This is a rainmeter skin currently under development. It displays the current price and 24hr change of specified cryptocurrencies using the binance public api. 

**Currently Under Very Early Development! Expect Issues!**

---

## **Setting the cryptocurrencies you wish to track:**
This will be in the variables section and may slightly vary depending on the skin you are using a guide on how to use the variables section is [here](#Variables).

1. Single Tracker:
    
    Find the variable:
    ```ini
    TradeSymbol=BTCUSDT
    ```
    Then change the BTCUSDT part to whatever crypto symbol pair you with to track, for example if I wished to track Etheruem TO Binance USD, I would change it as follows:
    ```ini
    TradeSymbol=ETHBUSD
    ```
1. MuliTrackers:
    Multitrackers can also be changed in a very similar way the only difference is the variable names are slightly different. They will look like so:
    ```ini
    TradeSymbol1=BTCUSDT
    TradeSymbol2=ETHUSDT
    TradeSymbol3=DOGEUSDT
    ;And so on!
    ```
    The number next to TradeSymbol represents its position in the list, TradeSymbol1 is the first in the list.

---
## **Variables**    

You can modify the variables by right clicking on any one of the skins and hitting the edit skin button. As shown below:

![Edit Skin](./img/Edit-Skin-Menu.png)

This will open up the code for the skin and may seem intimidating at first, However, to personalize the skin you only need to change items in the variables section, **DO NOT TOUCH THE REST OF THE CODE UNLESS YOU KNOW WHAT YOU'RE DOING!**

*Variables will be located under a tag that looks like this:*
```ini
[Variables]
;Variables are here!
```  

Some variables will be commented, explaining what they do, and providing the default value as a point of reference if you need to go back and change them later:
```ini
;The default colour of the text. DEFAULT VALUE: 255,255,255
TextColor=255,255,255
```

However, as I am early in the development stage these comments may not be present and if they are may be very basic, this will improve as development progresses.

---
## **Variants:**
- Single Tracker:

    ![Single Tracker](./img/SingleTracker.png)

- Multi Trackers:
    * 3 Trackers

        ![Muli Trackers - 3 Trackers](./img/MultiTracker-3-Tracker.png)

