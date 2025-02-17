```mermaid
flowchart TD
A("Choose a sunny area") --> B("Prepare the soil")
    B --> C("Plant the seeds")
    C --> D{"Is there enough water?"}
    D -- Yes --> E("Water on a regular basis")
    D -- No --> F("Adjust watering schedule")
    E --> G("Fertilize")
    F --> G
    G --> H("Check for pests")
    H --> I{"Is the plant healthy?"}
    I -- Yes --> J("Harvest tomatoes")
    I -- No --> K("Identify and treat pests")
    K --> I
