## API Description

This API would allow users to access information about the population of Manitoba. It allows users to specify parameters such as city age and income.

## Desription of Endpoints

### By City

Allows users to get the population of a specific city

    https://manitoba.population/api/city



####  City JSON



    {
        "message": "cityname"
        "status": "success"
    }







### By Age

Allows users to get the population of Manitobans within a specific age range

    https://manitoba.population/api/city/age
    
    
    
####  Age JSON



    {
        "message": '10000'
        "status": "success"
    }







### By Income

Allows users to get the population of Manitobans within a range of income

    https://manitoba.population/api/city/income
    
    
    
####  Income JSON



    {
        "message": '400000'
        "status: "success
    }






# Sample Request

https://api.manitoba_population.com/json?city=winnipeg

https://api.manitoba_population.com/json?age=6

https://api.manitoba_population.com/json?income=28000

# Response
