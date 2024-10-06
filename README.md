```mermaid
graph TD
    Title["📅 Weekly Meal Plan"]

    subgraph Monday
    M[Monday]
    M --> |"🍳 Breakfast"| MB["Oatmeal with berries"]
    M --> |"🥗 Lunch"| ML["Grilled chicken salad"]
    M --> |"🍽️ Dinner"| MD["Baked salmon with veggies"]
    end

    subgraph Tuesday
    T[Tuesday]
    T --> |"🍳 Breakfast"| TB["Greek yogurt parfait"]
    T --> |"🥗 Lunch"| TL["Veggie soup & bread"]
    T --> |"🍽️ Dinner"| TD["Tofu stir-fry"]
    end

    subgraph Wednesday
    W[Wednesday]
    W --> |"🍳 Breakfast"| WB["Avocado toast"]
    W --> |"🥗 Lunch"| WL["Quinoa veggie bowl"]
    W --> |"🍽️ Dinner"| WD["Steak & sweet potato"]
    end

    subgraph Thursday
    Th[Thursday]
    Th --> |"🍳 Breakfast"| ThB["Smoothie bowl"]
    Th --> |"🥗 Lunch"| ThL["Turkey wrap"]
    Th --> |"🍽️ Dinner"| ThD["Chicken & rice pilaf"]
    end

    subgraph Friday
    F[Friday]
    F --> |"🍳 Breakfast"| FB["Egg white omelette"]
    F --> |"🥗 Lunch"| FL["Tuna salad"]
    F --> |"🍽️ Dinner"| FD["Homemade pizza"]
    end

    Title --> Monday --> Tuesday --> Wednesday --> Thursday --> Friday

    classDef default fill:#f9f9f9,stroke:#333,stroke-width:1px;
    classDef titleClass fill:#e0e0e0,stroke:#333,stroke-width:2px;
    classDef dayClass fill:#FFFFFF,font-weight:bold;
    classDef breakfastClass fill:#ffe6e6,stroke:#ff9999,stroke-width:1px;
    classDef lunchClass fill:#e6f3ff,stroke:#99ccff,stroke-width:1px;
    classDef dinnerClass fill:#e6fff2,stroke:#99ffcc,stroke-width:1px;
    classDef blackText color:#000000;

    class Title titleClass;
    class M,T,W,Th,F dayClass;
    class MB,TB,WB,ThB,FB breakfastClass;
    class ML,TL,WL,ThL,FL lunchClass;
    class MD,TD,WD,ThD,FD dinnerClass;
    class Title,M,T,W,Th,F,MB,TB,WB,ThB,FB,ML,TL,WL,ThL,FL,MD,TD,WD,ThD,FD blackText;
