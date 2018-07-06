# Book2Vec

Representing Books as vectors using the Word2Vec algorithm 

Using the Cbow version of the Word2Vec algorithm on Goodreads data, vectors were trained to represent books. 

This repository includes Google Colab notebooks used to analyze and clean the original goodreads data, train the book vectors, and analyze the vectors. 

These notebooks requires the 'ratings.csv' and the 'books.csv' files which can be found here

http://fastml.com/goodbooks-10k-a-new-dataset-for-book-recommendations/

These notebooks are set up to download these files from your Google Drive, and will ask permission to access your Google Drive file. 

The following images are from a 2D TNSE plotting the resulting book embeddings. This particular TNSE plotted 3000 books (out of 10,000 book vectors that were trained)

![alt text](Images/Book2VecSample1.JPG)
![alt text](Images/Book2VecSample2.JPG)
![alt text](Images/Book2VecSample3.JPG)
![alt text](Images/Book2VecSample4.JPG)
![alt text](Images/Book2VecSample5.JPG)
![alt text](Images/Book2VecSample6.JPG)
![alt text](Images/Book2VecSample7.JPG)
![alt text](Images/Book2VecSample8.JPG)
![alt text](Images/Book2VecSample9.JPG)
![alt text](Images/Book2VecSample10.JPG)
![alt text](Images/Book2VecSample11.JPG)
![alt text](Images/Book2VecSample12.JPG)
![alt text](Images/Book2VecSample13.JPG)
![alt text](Images/Book2VecSample14.JPG)
![alt text](Images/Book2VecSample15.JPG)
![alt text](Images/Book2VecSample16.JPG)


This is the full map containing all 3000 vectors. 

![alt text](Images/Book2Vec0-3000New.jpg)

The following images show samples of showing which vectors are most similiar to a particular book. 

![alt-text-1](Images/sim1.JPG) ![alt-text-2](Images/sim2.JPG)
![alt text](Images/sim3.JPG) ![alt text](Images/sim4.JPG)
![alt text](Images/sim5.JPG) ![alt text](Images/sim6.JPG)
![alt text](Images/sim7.JPG)

The following images show some of the arithmetic properties of the book vectors. Although these properties are not as robust as word vectors' arithmetic properties, I hope to improve these with better hyperparameter optimization and more data. But in the meanwhile, here are some of the more interesting results I found. 

Vampire Classic - Vampire = Classics

![alt text](Images/va1.JPG)

Twilight Graphic Novel - Twilight + Coraline = Coraline Graphic Novel (in top 2 vectors returned)

![alt text](Images/va2.JPG)

Winnie-The-Pooh + Zen = Zen Pooh

![alt text](Images/va3.JPG)

Romance Classic - Classic = Romance 

![alt text](Images/va4.JPG)

Neil Gaiman Childrens' - Neil Gaiman = Childrens'

![alt text](Images/va5.JPG)

Vampire Romance - Vampire = Romance

![alt text](Images/va6.JPG)



![alt text](Images/va7.JPG)
