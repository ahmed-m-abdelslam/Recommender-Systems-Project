a comprehensive End-to-End Recommendation System using the  MovieLens (small) dataset!

In this project, I and my Lovely team 

implemented a recommendation system to suggest specific movies to users depending on their previous actions  . we utilized two powerful approaches: Factorization Machines and Deep Learning to enhance the recommendation process.


UI Components:
  • User Page:
  
      o User selection mechanism (select from the unique users in the dataset)
      
      o User history view (show user interactions with item details)
      
      o Input for the N parameter (decide how many items to recommend per page)
      
      o User top-N list of recommendations (release a list of top-N items recommended for the user)
      
      o Recommendation section navigation (mechanism to navigate to next/previous/a certain page
                                            “release next/previous/certain N items in the list”)

                                            
  • Item Page:
      o Item selection mechanism (select from the unique items in the dataset)

      o Item profile (show the item’s meta data)
      
      o Item top-N similar items (release a list of top-N items similar to the item of interest)
      
      o Similarity section navigation (mechanism to navigate to next/previous/a certain page “release
                                        next/previous/certain N items in the list”)

                                        
Recommender Model(s):

    • User Recommender:
    
    o Advanced Model: Factorization Machines and  Neural Collaborative Filtering
    
    o Trained and saved as an inference model
    
    o Loaded on the dashboard to predict for the selected user
    
    • Item Similarity:
    
    o Appropriate approach to calculate item similarities
    
    o Run on demand when an item is selected on “Item Page”

Dataset:
• MovieLens (small)
