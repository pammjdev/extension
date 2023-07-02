# Jane Store Expander [janeexpander.com](http://janeexpander.com/)

## Notice
Any issues encountered using this website are not the fault of IHeartJane or Jane Technologies. This is a homemade website that assumes a lot of functionality will just work from store to store. If it does not work for you please contact me with the store number/website and what doesn't work to research the issue. pammjdev@gmail.com Do not reach out to your dispensary or IHJ/Jane Technologies.

All item purchases are through the Jane Technologies system. This website does not collect data or interfere with their purchasing process. It only tries to help make finding the medicine easier.

This has been modified from the initial idea of a Firefox Extension and is now a website. Any previous mention of this being a Firefox Extension are no longer true, the extension will no longer be supported in place of the website.

## Limitations
The store inventory may be up to 24 hours old. This is because I worked hard to play nice with Jane Technologies, in the name of free use, since I am not affiliated with them. I implemented a webservice I run, that only pulls the API data once a day for each store being accessed by users. It then saves the inventory so that if the data is needed again in the same day, it uses my webservice saved data and does not access IHeartJane(IHJ) again. I did this to lower the number of times the IHJ service has to be called.

## Use
The website loads with example store number 1961. Any store number may be entered, if you do not know your specific store number you may find it using the step below.

Once the value is put into [janeexpander.com](http://janeexpander.com/) input hit Load button and the inventory will be generated in a moment.

The image below is an example of how to right-click the inventory item in the dispensary and then click 'Copy link address', or you can see the store number in the link preview if it displays and you can type it in manually.
![Find Store Number](https://raw.githubusercontent.com/pammjdev/extension/main/images/get_store_number.jpg)
