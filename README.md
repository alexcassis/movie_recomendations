# movie_recomendations
![alt text](movie_recomend.png)
## Introduction
GroupLens Research, which is a research group in the Department of Computer Science and Engineering at the University of Minnesota, operates a movie recommender based on collaborative filtering called MovieLens, which is the source of the data.
This dataset (ml-latest) describes 5-star rating and free-text tagging activity from MovieLens, a movie recommendation service. It contains 22884377 ratings and 586994 tag applications across 34208 movies. These data were created by 247753 users between January 09, 1995 and January 29, 2016. This dataset was generated on January 29, 2016.
Users were selected at random for inclusion. All selected users had rated at least 1 movies. No demographic information is included. Each user is represented by an id, and no other information is provided.
The data are contained in four files, links.csv, movies.csv, ratings.csv and tags.csv

The solution has 3 files 
* Movie_Recomendations_shell_script.txt (contains shell scripts)
* Movie_Recomendations_hive_script.txt (contains hive sql queries)
* Movie_Recomendations_analysis.txt (query for analysis)

You can also find these in my blog <a href=http://www.prathapkudupublog.com/search?q=movie</a>. 

### Installation
<table>
      <tr>
            <code>git clone https://github.com/PRkudupu/movie_recomendations.git                                                                  </code>
      </tr>
      <br>
      <tr>
          <code>cd movie_recomendations</code> 
      </tr>
</table>
These files are for reference. We can use the script in these files for completing this project

### Steps
* Create the environment which includes creating hdfs folders,folder permissions and create users
* Download data from the remote server to the cluster
* Ingest data into hive warehouse
* Create external tables for all entities including users, movies etc
* Write SQl queries for analysing recomendations

### License 
movie_recomendations is released under the MIT license:
 <a href="https://opensource.org/licenses/MIT">opensource.org/licenses/MIT</a>.
