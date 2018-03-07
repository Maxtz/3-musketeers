# cash

# Cash

This library allows to easily convert [32 currencies](./lib/currencies.json) with real time exchange rate using [Fixer Api](./https://api.fixer.io/latest)


# Installation

1. Clone the cash project to you current project
2. Open a command prompt on the cash project folder
3. Install the dependencies using npm install

# Usage

Open a command prompt in the bin folder

Run:

node index.js <amount> <FromCurrency> <ToCurrency> <ToCurrency> ...

It converts the amount of the first currency to the others currencies

![capture](/img/Capture1.PNG)

node index.js <amount> <FromCurrency>

It converts the amount of the FromCurrency to the default(s) ToCurrency(ies).

(./img/Capture2.png)

node index.js <amount>

It converts the amount of the default FromCurrency to the default(s) ToCurrency(ies).

(./img/Capture3.png)

node index.js --save <FromCurrency> <ToCurrency> <ToCurrency>...

To modify the default currencies 

(./img/Capture4.png)

node index.js --help

To see the help commands

(./img/Capture5.png)