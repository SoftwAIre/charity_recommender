# charity_recommender

# NYC Charity Recommender
Using a Google Colabs GUI, a donor chooses from a project from a list 48,296 New York based projects and gets recommended 10 similar projects back. 

### Localizing USA dataset to New York City
Trimming 48 million donations to 75 thousand
- Total DataSet before cleaning
+ 24 million individual donations, 
+ 4.6 million individual donors, 
+ 850,000 projects in total

And after cleaning… and only going to New York City
75,676 individual Donations
25,876 individual Donors
48,296 Projects 

+ Applied SurPRISE library to similarity matrices based on user implicit contribution history
+ Retrieved the top-10 items with highest rating prediction for each user in the New York City dataset
+ Reduced MAE on error metrics by 86.5% by comparing matrix factorization techniques such as SVD, SVD++ and NNMF
+ Created a GUI on Google Colabs for users that returns a list of recommendations
