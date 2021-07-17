# linear-regression
# Project Lab 13: Linear-Regression

We are deployed on [Link](https://github.com/kevinhenry/linear-regression)

PR: [Link](https://github.com/kevinhenry/linear-regression/pulls)

Collaboration:
  Tony Regalado, Anthony Williams, Garfield Grant

Overview: Data Science to learn a bit more about the field and tools used in this space!

The best way to hone your data analysis skills is consistent, deliberate practice. One of the best places to acquire data for analysis is Kaggle, so practice your abilities with some Kaggle data sets.

Feature Tasks and Requirements:
- Find and download the following data sets:
- [Video Game Sales - Sales data from more than 16,500 games](https://www.kaggle.com/gregorut/videogamesales)
- [Cycle Share Data set - Bicycle Trip Data from Seattle’s Cycle Share System](https://www.kaggle.com/pronto/cycle-share-dataset)

- Start two Jupyter Notebooks called vg-stats and bike-stats
- Add a markdown cell at the top of each notebook with the title of this assignment, an appropriate name for the data set, as well as your name and the date
- Load up each of these data sets into a Pandas DataFrame within each respective file.
  * NOTE: There’s an issue with one of the CSV files. You will need to find a way to handle that error… Google it, and work around it!

- In the vg-stats notebook answer the following questions/do the following tasks. Note that the numbers quoted for sales are in the millions, and apply only for those games with over 10,000 sales.:
  1. Which company is the most common video game publisher?
  2. What’s the most common platform?
  3. What about the most common genre?  
  4. What are the top 20 highest grossing games?
  5. For North American video game sales, what’s the median?
    - Provide a secondary output showing ten games surrounding the median sales output
    - assume that games with same median value are sorted in descending order
  6. For the top-selling game of all time, how many standard deviations above/below the mean are its sales for North America?
  7. The Nintendo Wii seems to have outdone itself with games. How does its average number of sales compare with all of the other platforms?
  8. Come up with 3 more questions that can be answered with this data set.

- In the bike-stats notebook, answer the following questions/do the following tasks:
  1. What is the average trip duration for a borrowed bicycle?
  2. What’s the most common age of a bicycle-sharer?
  3. Given all the weather data here, find the average precipitation per month, and the median precipitation.
  4. What’s the average number of bikes at a given bike station?
  5. When a bike station is modified, is it more likely that it’ll lose bikes or gain bikes? How do you know?
  6. Come up with 3 more questions that can be answered with this data set.

User Acceptance Tests:
```
def test():

    def assert_equal(actual,expected):
        assert actual == expected, f"Expected {expected} but got {actual}"

    assert_equal(most_common_publisher, None)
    assert_equal(most_common_platform, None)
    assert_equal(most_common_genre, None)
    assert_equal(top_twenty_highest_grossing_games.iloc[0].Name, None)
    assert_equal(top_twenty_highest_grossing_games.iloc[19].Name, None)
    assert_equal(na_median_sales, None)
    assert_equal(ten_median_na_seller_names, None)

    print("Success!!!")

test()
```

Tools Used
google colab

Python
Pytest
Poetry
PyEnv

Getting Started
Clone this repository to your local machine.

$ git clone [Link](https://github.com/kevinhenry/chess-board.git)
Once downloaded, activate your virtual environment and run by ____________

`poetry init`
`poetry shell`

Collaboration with Anthony Wiliams and Tony Regalado
