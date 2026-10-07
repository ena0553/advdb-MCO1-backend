we can ignore the .env file later

set up:
1.  Clone
2.  Download the 2025 dataset [here](https://duckdb.org/docs/lts/guides/snippets/dutch_railway_datasets) and add the extracted csv to the data folder
3.  run ```docker compose up -d``` to make the container.
4.  Go to ```http://localhost:8080``` and input airflow as both username and password
5.  If there isn't one yet, make the postgres connection from the Admin page and set it up like so ![setup](https://cdn.discordapp.com/attachments/1031509162921832559/1557376179332194424/image.png?backend=b2&ex=6ac79317&is=6ac64197&hm=4abfdd2731af533eb11049bd3236336802ae56210e49adc30c2c6816acd1bdac)
6.  feel free to edit the dags as you see fit, my machine is struggling w storage atm 
   
