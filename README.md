# SGH_plates

Owning a license plate (牌照 pai2 zhao4) in Shanghai is huge investment to the few upper class citizens who can afford one. The due process of registering for a license plate in China is not as easy and by all means more expensive as it is in the USA. Take New York, where the lisense plate fee for a new car is $25.00(1). Add another $50 for the title registration and you could theoretically walk away with a newly registered plate for $75.  

In this mini-project, I hope to shed some light on the cost of obtaining a license plate in Shanghai and why the piece of metal alone can cost up to the price of a new car. The dataset I used can be found on Kaggle which logs statistics from Jan 2002-Jan 2019(2). A 17 year timeine of the data allowed myself to uncover obvious trends. Note: This data is the cost of a standard non-electric passenger model car. 

This project is one component of a larger project I hope to complete comparing the cost of driving in different cities around the world.

# A little background 

The license plate in China is much more restrictive in China. The biggest difference from a USA licesnse is the type of license you have/want determines where and when in the in the city you are allowed to drive. For example, a person with a license registered in Shanghai would not be allowed to drive on the streets in Beijing and would also not be allowed to drive during the hours of 7:30AM - 9:30AM and 4:30PM - 6:30PM. The information provided on the license plate allows people to know where they are and aren't allowed to dirve. The format of a license plate in China is as follows: 沪A.73B28. The first and only Chinese character determines the city/province where the driver could drive. In this example, the character 沪 (hu4) represents licenses registered in Shanghai. The second letter outlays a more specific area the driver is permitted to drive in. Going along with our example, in Shanghai the letters A-B, D-H, and J-N grant the driver to drive in urban/suburban areas while a C letter license is only allowed to drive in the suburbs of Shanghai and not the cities center(3). Major cities in China follow this aproach with some variation in leter meaning. For registrants outside of major cities, there is a general province wide character. Sorry, no cross China roadtrips happening anytime soon.

# The cost

So how could a license plate possibly cost as much as the car your trying to register in the first place? The short answer: a huge demand in an auction-type system.  
Unlike some cities in China, Shanghai uses an aution based system that drives the cost of plates to incredible hights. In Figure_1 you can see the datetime line graph of the winning bids of license plates in Shanghai. The red line represents to the number of applicants in the auction and the blue line represents the price of the winning bid.
14,099元

4 unlucky, 8 lucky


1. New York State Department of Motor Vehicles - Passenger vehicle registration fees: https://dmv.ny.gov/registration/registration-fees-use-taxes-and-supplemental-fees-passenger-vehicles
2. Shanghai Car License Plate Auction Price: https://www.kaggle.com/bogof666/shanghai-car-license-plate-auction-price 
3. Vehicle registration plates of China: https://en.wikipedia.org/wiki/Vehicle_registration_plates_of_China
