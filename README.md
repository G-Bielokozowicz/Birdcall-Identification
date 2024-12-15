## Birdcall Identification

This project involves performing data analysis on a dataset containing bird call recordings. The dataset includes various attributes related to the bird species, the recording process, and metadata such as location and time. The goal of this analysis is to extract insights into bird behavior, vocalization patterns, and trends across different locations and time periods.

##
Dataset Overview

The dataset consists of the following columns:

    Recording_ID: Unique identifier for each bird call recording.
    Genus: Genus of the bird species.
    Specific_epithet: Specific epithet (species name) of the bird.
    Subspecies: Subspecies classification, if applicable.
    English_name: Common English name of the bird species.
    Recordist: Name of the person who recorded the bird call.
    Country: Country where the recording was made.
    Locality: Specific locality of the recording.
    Latitude: Latitude coordinate of the recording location.
    Longitude: Longitude coordinate of the recording location.
    Vocalization_type: Type of vocalization (e.g., song, call).
    Quality: Quality rating of the recording.
    Time: Time of day the recording was made.
    Date: Date the recording was made.
    Altitude: Altitude of the recording location (in meters).
    Length: Length of the recording in minutes:seconds.
    Uploaded: Flag indicating if the recording has been uploaded.
    Other_species: A series of columns representing other bird species that were observed or recorded in the same area.
    Species: The species name (combination of Genus and Specific_epithet).
    Length_seconds: Duration of the recording in seconds.
    Year: Year the recording was made.
    Month: Month the recording was made.

## Geospatial analysis
Heatmap showing call recordings basend on latitude and longitude.

![obraz](https://github.com/user-attachments/assets/34b80bb1-1973-44fd-a373-ca1f99a72721)

## Temporal analysis

Identyfication of seasonal patterns.

![obraz](https://github.com/user-attachments/assets/c8468494-70a0-4cef-aaa1-63c85c55a1ec)

![obraz](https://github.com/user-attachments/assets/b584d0af-dd43-4dcb-9a8d-20e82b440b56)

## Country analysis
Analyzing the species distribution, altitude and record length per country

![obraz](https://github.com/user-attachments/assets/edfdacc8-5b13-4280-8649-91e1cdd0830c)
![obraz](https://github.com/user-attachments/assets/6215c69c-1dae-4c56-a630-cfdfe943a7dd)
![obraz](https://github.com/user-attachments/assets/569d92b6-c939-4116-a997-4367f2ec7368)
![obraz](https://github.com/user-attachments/assets/0eddfd28-ce14-4883-9bae-cfc1278d952b)

## Anomaly detection

Detecting anomalies in altitude and length using Isolation Forest

![obraz](https://github.com/user-attachments/assets/5ae32fa7-36ae-4ea2-9bd6-e2db985daab1)


## Quality of recording prediction

Predicting the quality of the recording basend on it's length, altitude, time of recording and species using XGBoost Clasifier

![obraz](https://github.com/user-attachments/assets/38822bb9-8178-441a-9ae8-68eac15e12f7)

![obraz](https://github.com/user-attachments/assets/73d19bde-8adf-40d5-8117-614390b8d35f)

