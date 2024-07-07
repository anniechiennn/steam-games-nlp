# 15 Years of Steam: Marketplace and Genre Trends

## Business Problem Statement
After the covid pandemic, the video game industry has seen slower  growth and more cost-saving measures. Towards the end of 2023 and continuing into 2024 a large number of layoffs was conducted, with over 10,000 jobs lost in 2023 and at least 8,000 in 2024. Thus, it is becoming more important to make optimal marketing decisions with limited resources to manage risks when launching a new product.

Steam is the largest digital distribution platform for PC gaming, with a dominant market share. In 2023, games worth $9 billion were sold on Steam, accounting for more than 580 million copies.

By diving into the Steam dataset with data from 2007 to 2022, this project aims to:
1. Pinpoint the important features that drive peak concurrent players. 
2. Conduct word frequency analysis with NLP to find popular keywords in the game description.
3. Provide a marketing dashboard tool for developers to lookup relevant info, ensuring a successful product launch. 

The goal is to inform video game publishers and developers in optimizing the pricing strategy, product description, and release window of the new products.

[Click here to go to dashboard](https://public.tableau.com/views/15YearsofSteamMarketplaceandGenreTrends/LandingPage?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Dataset Description
The SteamGames (71k games) dataset contains comprehensive information on a large collection of games on the Steam platform from 1997-2025, including unreleased games. The dataset consists of 39 columns and 71,171 rows, providing information about game genres, price, number of player and more. This provides a valuable opportunity to delve into the dynamics of the Steam marketplace and observe store page content trends through the years and across different genres.

**Datasource:** https://www.kaggle.com/datasets/mexwell/steamgames


**Data description for games**

| Column Name                 | Data Type  | Description                                                   |
|-----------------------------|------------|---------------------------------------------------------------|
| AppID                       | Integer    | Unique game ID                                                |
| Name                        | String     | Game title                                                    |
| Release date                | Date       | Date game was released                                        |
| Estimated owners            | String    | Estimated number of users that own the game                   |
| Peak CCU                    | Integer    | Peak concurrent players                                       |
| Required age                | Integer    | Age requirement of the game                                   |
| Price                       | Float      | Game price in USD                                             |
| DLC count                   | Integer    | Number of downloadable content for a game                     |
| About the game              | String     | Description of the game on the store page                     |
| Supported languages         | String     | Languages supported by the game                               |
| Full audio languages        | String     | Audio language options of the game                            |
| Reviews                     | String     | Game reviews by media                                         |
| Header image                | String      | Image URL                                                     |
| Website                     | String        | Game website URL                                              |
| Support url                 | String        | Contact support URL                                           |
| Support email               | String     | Contact support email                                         |
| Windows                     | Boolean    | Whether playable on Windows                        |
| Mac                         | Boolean    | Whether playable on Mac                            |
| Linux                       | Boolean    | Whether playable on Linux                          |
| Metacritic score            | Integer    | Game review score on a scale of 0 to 100                      |
| Metacritic url              | String       | Game Metacritic page URL                                      |
| User score                  | Float      | User score on Steam                                           |
| Positive                    | Integer    | Number of positive reviews                                    |
| Negative                    | Integer    | Number of negative reviews                                    |
| Score rank                  | Integer    | Game ranking based on score                                   |
| Achievements                | Integer    | Number of achievements in the game                            |
| Recommendations             | Integer    | Number of Steam user recommendations                          |
| Notes                       | String     | Warnings or terms and conditions                              |
| Average playtime forever    | Float      | Average playtime of a game                                    |
| Average playtime two weeks  | Float      | Average playtime of a game in the last two weeks when data was queried |
| Median playtime forever     | Float      | Median playtime of a game                                     |
| Median playtime two weeks   | Float      | Median playtime of a game in the last two weeks when data was queried |
| Developers                  | String     | Developer name                                                |
| Publishers                  | String     | Publisher name                                                |
| Categories                  | String     | Steam platform feature category                               |
| Genres                      | String     | Game genres                                                   |
| Tags                        | String     | Game tags                                                     |
| Screenshots                 | Integer    | Number of screenshots on the game page                        |
| Movies                      | Integer    | Number of trailer videos on the game page                     |
