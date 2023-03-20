# Supply Data Analysis
### Business Objectives
Important part of our business is a supply/demand balance. We can’t control demand but we can shift some supply to necessary hours to cover more demand during peaks.

As part of the task you will have sample supply and demand data over a few weeks in a single city a few weeks after launch.

### We need to understand:
- What is the supply to demand dynamic and whether they match?
- Where are the hours of oversupply? Can we shift some of them to undersupply hours?
## Data understanding
### Hourly driver activity:
- Date – date + hour for which the row of data is presented
- Active drivers – number of active drivers (any level of activity) available during time period
- Online (h) – total supply hours that were available during time period
- Has booking (h) – total hours during which drivers had a client booking (any state)
- Waiting for booking (h) – total hours which drivers spent waiting for booking
- Busy (h) – total hours which drivers were not available to take orders in
- Hours per active driver – aka HPA - average number of hours each driver was online during time period
- Rides per online hour – aka RPH – avg. finished trips per online hour during period
- Finished Rides – number of finished trips during period
### Hourly Overview Search:
- Date – date + hour for which the row of data is presented
- People saw 0 cars (unique) – number of users who didn’t not see a car.
- People saw +1 cars (unique) – number of users who saw a car.
- Coverage Ratio (unique) – % of users who saw the car.
