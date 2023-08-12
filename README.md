#  Unlocking Perfume Trends: Data Analysis of Scents and Popular Notes
## Introduction
In the dynamic and ever-evolving fragrance industry, staying attuned to consumer preferences is essential for success. This business analysis case focuses on studying the data of trending perfumes, leveraging available brand, name, and notes information. By analyzing this data, companies can gain insights into popular scent profiles and make informed decisions about product development and marketing strategies.

## Aim
A perfume retailer seeks to gain a competitive advantage by understanding the trends in perfume preferences among consumers. With access to brand, name, and notes data, they aim to uncover the most popular scent profiles, identify emerging fragrance trends, and make strategic decisions to enhance their product offerings.

## Methods
### Data Scope & Methodology
The analysis draws data from [Fragrantica](https://fragrantica.com/), covering the years 2018 to 2022 and focusing on the top ten fragrances based on user votes. The dataset includes various fragrance categories and requires manual entry due to the lack of a downloadable CSV file on Fragrantica's website. The information encompasses brand, name, and fragrance notes. This approach allows for a nuanced exploration of evolving fragrance trends across genders during the specified period.

In this project, I used a methodical approach to parse and extract data from Fragrantica using Jupyter Notebook. To ensure cleanliness and significance, raw data was first collected and then cleaned using Python. The cleaned data were then imported into Tableau for visualisation, which required iterative design refinement to achieve clarity and visual appeal. The final Tableau visualisations were helpful in extracting useful information from the cleaned data. To guarantee the openness and accuracy of results, the whole process, from data collection and preprocessing to visualisation design, was documented and can be accessed.

The Tableau Public visualizations can be accessed [here](https://public.tableau.com/views/UnlockingPerfumeTrendsDataAnalysisofScentsandPopularNotes/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link).

## Results
### Most Popular Brands
<img width="495" alt="image" src="https://github.com/hanifahaputri/perfumes/assets/77476862/9f18cd89-ab8f-4c4c-acde-b75bccce3311"><br>
The visualization employs a horizontally stacked bar graph and accompanying table to uncover brand preferences. Dior emerges as the dominant brand with the most voted scents, closely followed by Tom Ford, Guerlain, Chanel, and Yves Saint Laurent, contributing to a diverse range of choices. Delving into gender-based patterns, Dior stands out as the preferred brand among males, while Guerlain and Chanel share popularity among females. In the Unisex category, Dior and Tom Ford hold equal positions, suggesting universal appeal. This analysis not only unveils brand popularity but also unveils nuanced preferences within different gender categories.

### Most Popular Perfumes
#### Most Popular Perfumes (All)
<img width="545" alt="image" src="https://github.com/hanifahaputri/perfumes/assets/77476862/4eb9e601-3933-49c1-be82-cb6ce8ba304c"><br>
The standout "Angels Share Anniversary Edition" by Kilian takes the lead in Fragrantica awards, garnering eight wins and favour across genders in 2021 and 2022 despite being Unisex. Notably, the fragrances analyzed share warm spicy and woody notes that enhance their popularity and sensory experience, creating blends catering to varied gender preferences and unisex appeal.

#### Most Popular Perfumes (Men)
<img width="680" alt="image" src="https://github.com/hanifahaputri/perfumes/assets/77476862/7a8e3a9e-8de2-4d0a-8483-a8664f4bd903"><br>
Kilian's Angels Share Anniversary Edition leads in male voter popularity. Notably, aside from Kilian's fragrance, the rest garnered equal nominations, indicating balanced male preference. The collection features predominantly warm spicy notes, except for Acqua di Giò Profondo, which introduces a blend of citric, marine, and fragrant elements.

#### Most Popular Perfumes (Women)
<img width="572" alt="image" src="https://github.com/hanifahaputri/perfumes/assets/77476862/fa969727-33fa-40bb-b2aa-1c3f4496adeb"><br>
A diverse array of women's fragrances emerges, including choices like L'Interdit, Shalimar Millesime Tonka, Libre, Pure Musc For Her, Black Orchid, Angels' Share Anniversary Edition, and Chance Eau Tendre. These options cater to a wide range of preferences and styles, united by warm and inviting nuances that infuse comfort and elegance into each scent. The selection encompasses various accords such as floral, oriental, and gourmand notes.

#### Most Popular Perfumes (Unisex)
<img width="569" alt="image" src="https://github.com/hanifahaputri/perfumes/assets/77476862/df500c8b-6971-4bf6-8527-6139916b60a5"><br>
In the unisex category, Black Orchid, Angels Share Anniversary Edition, and Coromandel Parfum claim the most frequently recognized positions, followed by Tobacolor, Vanilla Diorama, and Memoire d'une Odeur. These preferred scents showcase a captivating blend of warm spices, woody undertones, and aromatic notes, creating a common foundation that appeals to diverse tastes. While most fragrances exhibit harmony in their accords, Gucci's Memoire d'une Odeur stands out with its unique aromatic character, introducing a fresh dimension to the unisex scent choices.

### Most Popular Accords
<img width="490" alt="image" src="https://github.com/hanifahaputri/perfumes/assets/77476862/4ced510c-98c2-48d6-9e6b-282b32195548"><br>
Floral is the most popular perfume accord, comprising 26% of all scents. This popularity corresponds to the previously stated most popular fragrances since most of them combine floral elements into their formulations. Floral accords have the capacity to invoke a broad range of feelings and moods, making them a timeless and valued choice among perfume enthusiasts. The spicy accords come in second with 16%, increasing their connection with the most popular scents. The taste for these spicy notes is likely to add to the appeal and elegance that defines the preferred fragrances, resulting in a harmonic relationship between accord preference and the perfumes that have received the most attention.

## Conclusion
This project reveals fragrance preferences and trends. The spotlight is on "Angels Share Anniversary Edition" by Kilian, a fragrance that received awards in eight categories from 2018-2022. Distinct gender-based trends emerge: men's perfumes exhibit concentrated popularity, unisex scents feature fewer widely recognized perfumes, and women's fragrances span a diverse array. Unisex perfumes intertwine warm spices, woody undertones, and aromatic notes, while women's perfumes, despite the variety, share warm and inviting nuances. Floral notes dominate, echoing the popularity of highlighted fragrances, followed by spicy accords, adding to their allure and sophistication. Ultimately, this project underscores data visualization's significance in uncovering fragrance intricacies. Clear visuals expose hidden trends, informing decisions that resonate with fragrance enthusiasts and enhancing the satisfactory experience for all.

## Reflections & Limitations
Between 2018 and 2022, this study delved into scent preferences based on gender, focusing on long-term patterns. Understanding Tableau was straightforward due to its user-friendly nature. However, the Tableau Public version had limitations, lacking flexibility and comprehensive documentation. Challenges arose from Fragrantica's data, which lacked a downloadable CSV file and required manual entry. These obstacles shed light on the complexities of working with diverse data sources, offering insights into the learning process and practical considerations. The gender-based approach facilitated analyzing preferences among different gender groups, providing a comprehensive grasp of scent popularity and the role of gender in fragrance selection.
