## API Description

manitoba.population holds data regarding the population of Manitoba. Use the manitoba.population API to retrieve population by city, age, and income of Manitobans.

## Desription of Endpoints

Our endpoint has 3 parameters: city, age, and income. You can use any combination of these three parameters to specify the population number you want to receive. For example if you can search for the number of 25 year olds in Winnipeg by setting the city parameter to Winnipeg and the age parameter to 25. 

For age and income you can add specify a range rather than a single number by using two numbers separated by a dash. For example, you can search for the number of Manitobans between the ages of 10 and 12 by setting the age parameter to "10-12."

### By City

Allows users to get the population of a specific city


    https://manitoba.population.com/api/city



####  City JSON



    {
        "message": "20000"
        "status": "success"
    }
















### By Age

Allows users to get the population of Manitobans within a specific age range


    https://manitoba.population.com/api/age
    
    
    

####  Age JSON



    {
        "message": '10000'
        "status": "success"
    }







### By Income

Allows users to get the population of Manitobans within a range of income


    https://manitoba.population.com/api/income

    
    
    
####  Income JSON



    {
        "message": '400000'
        "status: "success"
    }






# Sample Request


https://manitoba.population.com/api/json?city=winnipeg

https://manitoba.population.com/api/json?age=6

https://manitoba.population.com/api/json?income=28000


# Response
