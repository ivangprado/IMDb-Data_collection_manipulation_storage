# Movie search engine: Data collection, manipulation and storage from IMDB and TMDB

![image](https://github.com/ivangprado/IMDb-Data_collection_manipulation_storage/assets/6001254/f634446f-14ce-43a3-8713-1caf53d8eb1b)

In this project, I create a movie search engine with the information extracted from the IMDb and TMDB webs through different techniques: webscraping, data dumps and API calls. The data has been manipulated with Pandas to define the final dataframe and it is persisted in the **NoSQL** CouchDB database.

### Steps ###
1. The initial information of the movies is obtained with **webscraping** and **regex** from IMDB.
2. The dataset is completed reading IMDB data dumps wien **Pandas**.
3. Additional information is added to the dataset using the TMDB **API** to compose the final dataframe.
4. The data is persisted in a **CouchDB** cluster and some queries are made to confirm that the movie search engine is working correctly.

![image](https://github.com/ivangprado/IMDb-Data_collection_manipulation_storage/assets/6001254/0a5158fd-3b0a-42e1-aba9-775affa74c55)


#webscraping #API #JSON #Pandas #Regex #NoSQL #MongoDB #pymongo
