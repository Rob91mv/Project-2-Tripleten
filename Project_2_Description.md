# Music Preferences in Springfield and Shelbyville.

![](https://upload.wikimedia.org/wikipedia/commons/c/c8/Yandex_Music_English_logo.svg)

## Project Overview:

This project aims to analyze music preferences, extracted from Yandex.Music, among users in two different cities: Springfield and Shelbyville. Using real online music streaming data, several hypotheses will be tested to compare listening behaviors across both locations.

The analysis is structured in three main stages. In Stage 1, an initial exploration of the dataset will be conducted, and preliminary observations will be recorded. In Stage 2, the data will be preprocessed through cleaning techniques. Finally, in Stage 3, statistical methods will be used to test the proposed hypotheses, with each step and result carefully documented.

This approach enables data-driven conclusions and supports informed decision-making based on real user behavior.

## Data Dictionary:

| Variable        | Description                                                |
|-----------------|------------------------------------------------------------|
| userID          | dentifier of the user                                      |
| Track           | Song Title                                                 |
| artis           | artist name                                                |
| year            | Year of production                                         |
| genre           | Genre of music                                             |
| City            | User's city                                                |
| time            | Exact time the song was played                             |
| Day             | Day of the Week                                            |

## Impact:
Using real-world data, this project investigated online music streaming behavior in Springfield and Shelbyville, focusing on user activity patterns and musical preferences. Listening habits were analyzed based on track metadata, user location, and playback time. Prior to analysis, data preprocessing was performed to correct header inconsistencies, handle missing values by replacing them with "unknown", and remove both explicit and implicit duplicates, ensuring the dataset's integrity.

Statistical testing confirmed a significant variation in user activity across days and cities. Genre preferences by cities were found to differ significantly on Monday mornings and Friday nights. Although z-tests indicated that Springfield had a higher proportion of pop listeners and Shelbyville a higher proportion of rap listeners, a basic analysis showed that pop remained the most played genre in both cities. This discrepancy, likely influenced by missing genre values, rendered the third hypothesis inconclusive.

In summary, the analysis supported the first hypothesis, partially validated the second, and found insufficient evidence to confirm the third. These insights highlight meaningful differences in user engagement across locations and time, offering valuable guidance for content personalization and targeted recommendations on music platforms.

"TripleTen" Proyect #2 
