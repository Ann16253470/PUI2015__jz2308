Environment

All essential packages are included in Anaconda except for ggplot. ggplot can be installed by simply running the following command in the terminal:

    pip install ggplot
Otherwise, one can comment that line and the program should still go through.

Values

The data file should be stored under the same as the python script.
The user type of the city bike are basically customers and subscribers.
Customers:24-hour pass or 7-day pass user,usually consist of visitors come from the other places of the world. 
Subscriber:Annual Member,usually consist of citizens who live in NYC,
With different motivation and behavior patterns, the trip duration of customers and subscribers might be different.
According to above, we chose to test the difference in trip duration between subscribers and customers.

Test(T-test)

H0:The mean of trip duration by customer is less than or the same as the one of subscriber.
We choose confidence interval to be at α=0.05

My contribution

I participated in the discussion of the idea, helping modify the code. Running the models in different months.
(Except the test conclusion, compared the trip duration of Jan. 2015 and Jan. 2014, we can see that the number of long-tripduration people of both subscribers and customers increase a lot.)