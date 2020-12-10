# CDP Hackathon 2 - Winning Entry

[CDP](https://www.cdp.net/en) is a global environmental impact non-profit working to secure a thriving economy that works for people and the planet.

My partner and I aimed to use CDP's 2019 survey data to identify opportunities for City-Corporate collaboration. We ended up developing the "Climate Collab Index", which is a measure on a scale from 0-100 that indicates the strength of alignment of climate-related goals between a corporation and a city. The index has 3 components:

1. Alignment on targets, priorities, and progress based on objective (multiple-choice) CDP questions. 
2. Shared goal areas based on free-text CDP questions
3. Close geographical proximity

For more information on our entry, you can read abot it on [devpost](https://devpost.com/software/climate-collab-index-by-tara-larure-soazig-kaam).

My contribution focused on component #2, which involved creating a topic model from text responses. The enclosed script is a google colab notebook that I used to build the LDA model and use it to create a similarity score between city and corporate free text responses.


