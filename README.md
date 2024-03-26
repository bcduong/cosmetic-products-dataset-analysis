# Problem: cosmetic products dataset analysis

We are given a dataset of cosmetic products constituted by ten columns product_name, brand, product_url, product_type, ingredients, price, ingredients_list, nb_ingredients, volume, volume_unit,
The goal of this project is to analyze the ingredients using K-means clustering, build a model to predict product type from ingredients, and predict product prices from ingredients, volumes, and brands.

● Using scikit learn TfidfVectorizer vectorize the ingredients columns. 
● Cluster the vectorized features using scikit learn KMeans cluster the cosmetic products and visualize the cluster centers using WordCloud. 
● Embed the vectorized ingredients using an auto-encoder constituted by five hidden layers. The auto-encoder has to be built in tensorflow/Keras. For visualization, the embedding layer has to be 2 dimensional. Plot the embed product, and annotate each plotted product by its product type. Hint: each row of the vectorized matrix
represents a product.
● Build a 3 hidden layer model to predict product type using vectorized ingredients. The model’s hidden layer size has to be selected by 3 fold cross-validation. Training and
validation splits have to be 80/20% 
● Devise a method to infer the impact of ingredients tokens on product types predictions. Hint: use the mapping between vectorized ingredients token and vector index. Visualize the token impact using WordCloud. 
● Build a tensorflow/Keras 3 hidden layer model to predict product prices using vectorized ingredients and product volume 
● Devise a method to infer the impact of ingredient token on predicted prices, and the brand on prices. Visualize the token impact using WordCloud, and brands impact using WordCloud. 
