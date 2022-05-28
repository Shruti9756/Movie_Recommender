# Movie Recommendation System
# Content-Based Movie Recommendation System -
This type of recommendation engine works on the concept that if a user liked a particular movie, he/she might like a movie similar to it based on attributes such as genre, director, actors etc.

![image](https://user-images.githubusercontent.com/90978030/170785934-3a3aabc1-125f-419c-adc3-358e861b7eec.png)


For this initially the datasets were selected from https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata


# Similarity Score -
How does it decide which item is most similar to the item user likes? Here come the similarity scores.

It is a numerical value ranges which between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

# Cosine Similarity -
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

![image](https://user-images.githubusercontent.com/90978030/170785665-3662d48f-4573-4029-b73f-38fcc9dc842b.png)


# IDE's used -
Visual Studio Code


# How to run the project?
1. Clone or download this repository to your local machine.

2. Install all the libraries mentioned in the requirements.txt file with the command pip install -r requirements.txt in VS Code. 

3. Open your terminal/command prompt from your project directory and run the file app.py by executing the command python app.py.

4. And Hurray! That's it. Your Recommendation Engine is ready!
