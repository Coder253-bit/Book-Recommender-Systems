# Book-Recommender-Systems
A set of recommender techniques such as a novel statistical hybrid filter, KMeans clusters, context aware recommender systems that are evaluated using collaborative filtering (user-user and item-item similarity) and SVD + Cross Validation. The performance metric used to measure performance is RMSE.
- The contextual information is location for this dataset as there are not many features that are in the dataset to begin with. The context is manually added into every cluster by determining which locations are predominant.
- The best model is KMeans clusters with added contextual information, evaluated by an SVD + Cross Validation which gives the least RMSE, as well as consumes less computational resources. 
- The data was collected by Cai-Nicolas Ziegler in a 4 week crawl (August / September 2004) from the Bookcrossing website with kind permission from Ron Hornbaker, CTO of Humankind.
- The dataset consists of three files: Books, Ratings, and Users.
- Link to the dataset download: http://www2.informatik.uni-freiburg.de/~cziegler/BX/. Dataset citation: (Zhang, 2009)
