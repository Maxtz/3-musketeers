## Cash

The library Cash allows to convert 32 curencies in real time [currency](https://api.fixer.io/latest)

## How to use

First go on the directory "3-musketeers/cash/bin" 

#Different command to convert


To convert a curenccy first you put "node index.js" "amout of the currency you want convert" "the origin currency you whant to convert" "In wich currency you want to convert(you can add the number you want)

node index.js "amount" "CurrencyOrigin" "ConvertToCurrency" "ConvertToCurrency"

![capture](https://github.com/Maxtz/3-musketeers/blob/master/cash/img/Capture1.PNG)


Conevert a currency with default parameters
It convert the currency with the amout to the curencies in parameters by defalut

node index.js "amount" "CurrencyOrigin" 

![capture](https://github.com/Maxtz/3-musketeers/blob/master/cash/img/Capture2.PNG)


Conevert a currency with default parameters
It convert the currency by default with the amout to the curencies in parameters by defalut

node index.js "amount"

![capture](https://github.com/Maxtz/3-musketeers/blob/master/cash/img/Capture3.PNG)


To modify the parameters by default the origin currency and  In wich currency you want to convert(you can add the number you want)

node index.js --save  "CurrencyOrigin" "ConvertToCurrency" "ConvertToCurrency"

![capture](https://github.com/Maxtz/3-musketeers/blob/master/cash/img/Capture4.PNG)


Obtain the help commands

node index.js --help

![capture](https://github.com/Maxtz/3-musketeers/blob/master/cash/img/Capture5.PNG)