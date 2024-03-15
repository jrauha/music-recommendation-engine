# Specification

This project aims to develop a music recommendation engine that leverages association analysis techniques to suggest music based on user listening patterns.

### Core of the Project

- Identify Song Relationships: Utilize the Apriori algorithm to discover frequent co-occurrences of songs in playlists or user listening histories.
- Generate Recommendation Rules: Based on frequent itemsets, create association rules that express relationships between songs (e.g., "If a user listens to A and B, they are likely to listen to C").

https://en.wikipedia.org/wiki/Apriori_algorithm

### Recommendation system:

- Develop a user interface (UI) or API to accept user input (song, artist, playlist).
- Match the user input to the antecedent (left-hand side) of association rules.
- Recommend songs that appear in the consequent (right-hand side) of the matching rules with high confidence.

**Degree Program:** Tietojenkäsittelytieteen kandidaatti (TKT)

**Programming language:** Python

**Other Languages Proficiensies:** Java, C#, TypeScript, JavaScript
