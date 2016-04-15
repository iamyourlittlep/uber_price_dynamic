# uber_price_dynamic
'''Use uberpy module to grab some data from uber API
Study price dynamic problems'''

- 1, I use GIS to naturally break 264 NY zones in to 5 subset based on size.
- 2, From the biggest zones I randomly choose five representative points, and from the second biggest I choose four; So on and so forth.
- 3, Points are real time pick-up locations from NY TLC taxi data in Jan 2015
- 4, Alternative points pick-up method is use k-mean cluster, which is better, but not necessary for my purpose.

