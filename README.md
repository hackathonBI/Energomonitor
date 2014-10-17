Energomonitor Data Description
====

Provided data are 22 months of power consumption from one of our customers. That's more than 560k samples in total.

Data are in CSV format with three columns:

1. **UTC timestamp** - time when sample was received
2. **value** - power consumption in Watts
3. **delta** - time period for which the value was measured

|time|value|t-delta|
|---|---|---|
|1357776033 |284 |90|
|1357776334 |283 |90|
|1357776635 |275 |90|
|1357776936 |263 |90|
|1357777237 |257 |90|
|1357777538 |255 |90|
|1357777839 |218 |90|
|1357778140 |266 |90|
|1357778441 |259 |90|
|1357778742 |258 |90|

We would like you to have some fun during Hackathon so we picked some tasks which may be more interesting than useful:

* When the customer was on holidays?
* How long the customer sleeps?
* Was the customer working over night?
* Does the customer wake up same time every day?

But if you are more interested in real problems, here are some useful tasks:

* Identify unusual power comsumptions.
* Find permanent power consumption (that means power consumption of devices powered on for whole day) for each day.
* Are there differencies in power consumption during summer and winter time?

