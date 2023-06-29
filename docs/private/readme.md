# Observations

**to see the current latest block height** or latest block hash and other things.  
we can use the following command 

like in this case

    checkersd status | jq  

Or if you want to see the output in a json format you can use the following command although it is recommended to use the above command (by me)

    checkersd status | json_pp