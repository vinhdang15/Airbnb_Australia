# A brief history of Airbnb in Australia

This project is our (Vinh, Tan and Viet) Data Analysis project in Machine Learning Engineer at Coderschool.

For this project, we picked the dataset of Airbnb in Australia. After the exploratory data analysis, we come up with the idea using the dataset to tell a brief history about the journay Airbnb in Australia

## Technical information:
- Datasource: [insideairbnb.com](http://insideairbnb.com/get-the-data.html)
- Language: `Python`
- Libraries: `Pandas`, `Matplotlib`, `Seaborn`
- Dashboard: `Google Data Studio`

## Outcomes:
- [Data Studio](https://datastudio.google.com/reporting/2f2eaac2-c68d-4ca2-9636-eca096f60549)
- Jupyter notebook and PDF version of Data Studio are uploaded in this repo

## Analyst
Slide 3: Listing growth by total
![Airbnb-in-Australia_sl3](https://user-images.githubusercontent.com/81819640/129762816-b279d1b1-cc71-4878-a6cf-2edb14f4c41c.JPG)

Slide 4: Listing growth by states
![Airbnb-in-Australia_sl4](https://user-images.githubusercontent.com/81819640/129762917-e9eeb3bd-5c01-4c1f-aa09-2df9d237b2b8.JPG)
  - In New south Wales, Victoria, Queensland:
      - The number of new-listings is the highest of the country.
      - Number of new-listings in the high season is much bigger than the low season.
      - in QL the growth is more stable. It is less affected by the travel season time than the other two states above. We also find out that in QL the holidays normally start in summer when the weather is hot and storms usually come at this time, and when winter and spring come, people get back to work so they have no time for traveling. Therefore, we can not clearly see the high season in QL.
  - In Australian Capital Territory
      - Even it’s the capital but number of new-listings here has not been changing so much from 2012 until now. The fact here is the AU capital is less travel activities, so not many people visit here compareed to the other states.
  - Coronavirus impact: Because New south Wales, Victoria, Queensland are the most populous states in AU, so they suffered huge damaged due to Coronavirus pandemic last year (2020). According to the chart, in Victoria when the second lockdown occurred, it had more impacts than the first lockdown. That leads VT seriously suffered the most impacts among the states.


Slide 5: Number of new listings by room type.
![Airbnb-in-Australia_sl5](https://user-images.githubusercontent.com/81819640/129762924-0fd29d43-5c37-46d9-a79c-5008e1e2096d.JPG)
  - The need for AirBnB accomodations are mostly fulfilled by the "entire place" and "private room" category.
  - The "hotel room" is different. As AirBnB is a platform for individuals to rent their places. If people want to search for hotel rooms, they will go to more popular websites for hotel room, such as booking.com. Therefore, we are not supposed to see many hotel rooms in here as compared to Entire place or Private room.

Slide 6: Growth of hotel room in AirBnB
![Airbnb-in-Australia_sl6](https://user-images.githubusercontent.com/81819640/129762929-b667d1dd-913b-4c81-ae21-ab7524b9b317.JPG)
  - Zoom in to the Hotel room, we can see a significant increase around February 2018. This is when AirBnB start their partnership with SiteMinder. This partnership basically allows boutique hotels on SiteMinder extending their market to guests on AirBnB.
