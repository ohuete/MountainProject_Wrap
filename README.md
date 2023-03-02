# MountainProject_Wrap
Creating a wrapped feature for climbers using Mountain Project

1. Clean Data
    - Drop unnecessary columns
        - Your rating
        - Your stars

    - Ratings Data (Oscar)
        - Create dataframe for bouldering vs others first
        - Separate numerical and alphabetical metrics into their own columns
        - Convert numerical datatypes to integer

def(ratings)
a=1
b=2
c=3
d=4

Ratings
4.1b

Ratings Num | Ratings Alp
4.1              b

Ratings Num | Converted Ratings Alp
4.1              2

Ratings Num
4.12

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



