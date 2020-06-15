# 💲 Exchange Rates PRO

    Stable version is 1.1.0
    
Extended version of Currency Converter widget, that can multiple currencies real-time calculation and which has all the features of a classical currency converter.

## Special features

* ⚡ Real-time currency converter;
* 🤑 The client chooses any currency;
* 💶 Multi-currency support;

Get widget: https://fx-w.io/exchange-rates-pro/

## For Developers

**Tag of widget:** `<fxwidget-erp></fxwidget-erp>`

JavaScript: `<script src="https://s.fx-w.io/widgets/exchange-rates-pro/latest.js"></script>`

The table below contains a list of attributes that can be applied to a widget.

1. Our widgets based on a progressive JavaScript framework, in this way our currency tools has inherited reactive properties – editing attributes you can observe instant changes.
2. The color of the text depends on the background: light text will appear on a dark background and vice versa. If you use attribute background don't forget about set «background-color». Otherwise the text may merge with the background.
3. Use background attribute with background-color.

|Attribute|Type|Default|Reactive 1|Description|
|--- |--- |--- |--- |--- |
|amount|float|1|true|Amount.|
|main-curr|string|USD|true|Head currency.|
|sel-curr|string|EUR,GBP,CNY,JPY,BTC|true|Selected currencies.|
|decimal-point|string|.|true|Sets the separator for the decimal point.|
|separator|string|,|true|Sets the thousands separator.|
|decimals|int|2|true|Sets the number of decimal points.|
|background-color|string|#ffffff|true|CSS background-color Property. 2|
|background|string|none|true|CSS background Property. 3|
|border-radius|float|0.15|true|Rounded corners.|
|code|boolean|false|true|Show ISO code of currency only.|
|symbol|boolean|true|true|Currency symbol.|
|shadow|boolean|false|true|Show widget shadow.|
|large|boolean|false|true|Large widget.|
|grouping|boolean|true|true|Format amount.|
|changes|boolean|true|true|Indicator of currency rates changes in 24 hours.|
|tax|boolean|false|true|Input form: adding as a percentage/tax to the amount.|
|border|boolean|true|true|Border of widget.|
|lang|string|auto|false|Language of widget.|
