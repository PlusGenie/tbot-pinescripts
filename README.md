## Prerequisites: 
Assuming familiarity with the PineScript V5 language and its **strategy.*** functions are required.

## What is this repository?
This repository contains a collection of PineScripts that use the PineScript Tbot library. The purpose is to help users better understand the PineScript Library.


The PineScript Tbot library is available from [PineTradingbotWebhook](https://www.tradingview.com/script/xOO4qW1P-PineTradingbotWebhook/).

The main function from [PineTradingbotWebhook](https://www.tradingview.com/script/xOO4qW1P-PineTradingbotWebhook/) is **makeWebhookJson()**, which takes several parameters, including the **direction**. The **direction** is a string type and should be set to one of the following values:

```
strategy.entrylong
strategy.entryshort
strategy.exitlong
strategy.exitshort
strategy.close
strategy.close_all
strategy.cancel
strategy.cancel_all
```

These values closely reflect PineScript's **strategy.*** functions.

You can see examples of the **direction** parameter being used in the code snippets included in this repository.