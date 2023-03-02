# MountainProject_Wrap
Rating code LINK: https://www.mountainproject.com/forum/topic/116208707/rating-code-sorting-ticks#:~:text=The%20Rating%20Codes%20are%20a,or%20V%20grades%2C%20etc).

Creating a wrapped feature for climbers using Mountain Project

* 1. Clean Data *
    - Drop unnecessary columns
        - Your rating
        - Your stars 

    - Ratings Data (Oscar)
        - Create dataframe for bouldering vs others first
        - Separate numerical and alphabetical metrics into their own columns
        - Convert numerical datatypes to integer


-> Output is "Your most difficult climb was a 4.1b"


    - Location Data (Avatar)
        - Create a function to sort Location data based on State, General Area, National Park etc.
        Examples of Existing Data 
            - California > San Francisco Bay Area > Castle Rock Area > Platypus



2. Determine most difficult route performed (rating = difficulty)...could group this by route type or style
3. Determine top 5 routes performed most frequently
4. Determine top 5 route types performed
5. Determine top 5 locations climbed
6. Sentiment analysis (NLP) on Notes data
    - Enjoyed the route? Or was it bad?
    - Feeling strong or weak?

### Possible Output Ideas

- Your most frequently climbed route was at Castle Rock on Platypus. The route was Platypussy. You climbed it 10 times! 

- Your most frequently climbed route was in San Francisco California, at Castle Rock on Platypus. The route was Platypussy. You climbed it 10 times! 



