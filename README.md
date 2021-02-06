# 2021 Rice Datathon: Chevron Challenge
Harry Golen, Milan Chopra, and Christi Nguyen
2/6/2021


In our initial exploration of the data, we looked at different visualizations of the data to decide whether hot dog purchases followed noticeable trends by day of the year, season, month, and a few other factors. We noticed large differences between each store. For example, the store in San Antonio, TX sold far more hot dogs than the other locations, and also by amount in each time bucket. We also tried to look for correlations with hot dog sales in categorical factors such as whether EBT was accepted, alcohol was sold, and a car wash was present at the gas station. By far, the most consistent trend was that hot dog sales followed was a periodic, oscillating trend each week. That convinced us to fit a sinusoidal model to the data which fit a model for each time bucket at each store. 
Additionally, we noticed an extremely large outlier on the 185th day of the year in the data, which happens to be July 4th. Because of this, we removed these data points when making our model in order to not skew the model, keeping in mind that there will be a large quantity sold on the July 4th of every year.









