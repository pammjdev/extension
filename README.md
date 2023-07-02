# Jane Store Expander [janeexpander.com](http://janeexpander.com/)

## Notice
Any issues encountered using this website are not the fault of IHeartJane or Jane Technologies. This is a homemade website that assumes a lot of functionality will just work from store to store. If it does not work for you please contact me with the store number/website and what doesn't work to research the issue. pammjdev@gmail.com Do not reach out to your dispensary or IHJ/Jane Technologies.

All item purchases are through the Jane Technologies system. This website does not collect data or interfere with their purchasing process. It only tries to help make finding the medicine easier.

## Limitations
The store inventory may be up to 24 hours old. This is because I worked hard to play nice with Jane Technologies, in the name of free use, since I am not affiliated with them. I implemented a webservice I run, that only pulls the API data once a day for each store being accessed by users. It then saves the inventory so that if the data is needed again in the same day, it uses my webservice saved data and does not access IHeartJane(IHJ) again. I did this to lower the number of times the IHJ service has to be called.

## Use
The website needs to know what store to load in order to use it. If you already know your stores (typically four digit) number you can skip this step and enter it directly into the website then press Load button to load your store.

If you wish to load a sample store number use 1961, otherwise you can find a specific store number using the following steps.

Once the value is put into [janeexpander.com](http://janeexpander.com/) input hit Load button and the inventory will be generated in a moment.

The image below is an example of how to right-click the inventory item in the dispensary and then click 'Copy link address', or you can see the store number in the link preview if it displays and you can type it in manually.
![Find Store Number](https://raw.githubusercontent.com/pammjdev/extension/main/images/get_store_number.jpg)
