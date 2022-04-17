# First meeting preparation

Forecasting book club with SoCal RUG

## April 11, 2022

### For next week

* Addison to present rest of chapter 2.
* Maybe get into chapter 3.

### Prep

Chapter 1 exercises

Question: For cases 3 and 4 in Section 1.5, list the possible predictor variables that might be useful, assuming that the relevant data are available.
* Responses
    * Case 3: company wants to forecast retail values of fleet vehicles after 3-year leases.
        * Prompt, "What affects resale values?"
            * Supply and demand for used cars in the market versus new
            * Condition of leased cars to be sold
            * How long company can hold onto inventory to optimize for change in possible price
    * Case 4: "weekly air passenger traffic on major domestic routes for one of Australia’s leading airlines"
        * Overall state of economy
            * Interest rates
            * Tourism demand
        * Regularly recurring holidays and events per locality of interest--locality being city or area of departure and arrival airports
        * Service capacity of competing airlines
        * Consumer gasoline prices (if it's cheaper to drive, maybe people will fly less)

Question: For case 3 in Section 1.5, describe the five steps of forecasting in the context of this project.
* 5 steps
    1. Problem definition
        * What is to be forecasted?
        * the way the forecasts will be used
        * who requires the forecasts
        * how the forecasting function fits within the organisation requiring the forecasts
    2. Gathering information
        * historical statistical data
        * accumulated expertise of the people who collect the data and use the forecasts
    3. Preliminary (exploratory) analysis
        * Start by graphing the data
        * Ask if there consistent patterns or significant trends
        * Ask if there are seasonal patterns or trends
        * Ask if there are patterns related to business cycles
        * Are there outliers in the data requiring expert insight
        * Try to identify any relationships between variables
    4. Choosing and fitting models
        * Consider availability of historical data
        * Consider strengths of relationships between forecast variable and any explanatory variables
        * Generally compare at least a few potential models
    5. Using and evaluating a forecasting model
        * Assess how well the model forecasted actual events
        * Model performance can only be assessed after the forecasting period data is available
* 5 steps in Case 3
    1. What will resale values of vehicles in their fleet be after their 3-year leasing period? 
        * This will be used by the company to better control profits, and help the company come up with more optimal leasing and sales policies to maximize profits.
    2. The forecasting team needed historical data for (at least some of) their explanatory variables.
        * The existing forecasting specialists were too protective of their own work to share information, but the company provided historical data on their fleet and past resale values.
    3. From this historical data, the forecasting team can identify possible explanatory features of resale value and graph them against the historical resale values.
        * They can also graph resale values over time, and along business cycles to try to identify seasonal or cyclical patterns.
        * The team might try to identify outliers perhaps with expertise from the company, or those knowledgeable about markets or the economy, which can help clean up the data, reduce data dimensionality, or otherwise streamline the data.
        * In this exploration, the forecasters can try to measure the strength of relationships with the forecast variable using statistical methods.
    4. Become educated on various time-series or other methods of statistical methods, modeling, and forecasting.
        * Take into account where these different methods are considered valid and calculate statistics to see which modeling methods seem most viable
        * Perhaps partition the data into the most recent data and previous data and see if any of the models can use the previous data to predict the most recent data well.
    5. After the target forecasting period has passed and resale data from then has become available, use different methods to assess forecast performance.
        * Perhaps different graphical or statistical methods
