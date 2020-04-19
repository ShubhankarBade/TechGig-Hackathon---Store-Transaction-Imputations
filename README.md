## TechGig-Hackathon---Store-Transaction-Imputations

Nielsen Holdings plc (NYSE: NLSN) is a global measurement and data analytics company that provides the most complete and trusted view available of consumers and markets worldwide.

Nielsen receives transaction level scanning data (POS Data) from its partner stores on a regular basis. Stores sharing POS data include bigger format store types such as supermarkets, hypermarkets as well as smaller traditional trade grocery stores (Kirana stores), medical stores etc. using a POS machine.

While in a bigger format store, all items for all transactions are scanned using a POS machine, smaller and more localized shops do not have a 100% compliance rate in terms of scanning and inputting information into the POS machine for all transactions.

A transaction involving a single packet of chips or a single piece of candy may not be scanned and recorded to spare customer the inconvenience or during rush hours when the store is crowded with customers.

Thus, the data received from such stores is often incomplete and lacks complete information of all transactions completed within a day.

Additionally, apart from incomplete transaction data in a day, it is observed that certain stores do not share data for all active days. Stores share data ranging from 2 to 28 days in a month. While it is possible to impute/extrapolate data for 2 days of a month using 28 days of actual historical data, the vice versa is not recommended.

**Primary Objective** To create a model which can help impute/extrapolate data to fill in the missing data gaps in the store level POS data currently received.
