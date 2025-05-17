# County Buddy - A Spatial Dataset of Outliers in Prisons, Universities, Military Bases, and Reservations

This page has two datasets. Each has spatial data on the presence, number of, and institution names of incarcerated, student, military, and Native American populations. One is at the U.S. county level and the other is at the census tract level. Each have FIPS codes as column attributes. You can use these data freely.

This data can be used to help us answer questions about socio-economics in the U.S. For instance: Do university towns have higher income than surrounding towns? Do Native American communities have lower birth rates than nearby areas?

Uses: (1) Statistical: this data can help users run a regression (in R, Python or STATA) that can help us learn whether tracts with military bases have higher birth rates. (2) Web Development: A user could also use the data to help readers navigate an online map. The data can be used as tooltips to help explain if, for example, prison populations correlate with life expectancy, percent smokers, or number of people on Medicare.

This data is earmarked at Harvard Dataverse (DOI) and was created by researchers at the Georgia Institute of Technology College of Computing. Contact Colin Vu (cvu33@gatech.edu) or Clio Andris (clio@gatech.edu) for more info.

---

# Use Cases

Sample use cases for the datasets.

![Screenshot 2025-05-17 013942](https://github.com/user-attachments/assets/5ba0732c-dd68-41ce-9c6d-1e5ed3074911)
Example usage of County Buddy in https://ocular.cc.gatech.edu/resiliency-app. The figure shows Mahnomen County, MN, having an abnormally low life expectancy. County Buddy informs the user that this may be the result  of the presence of the White Earth Reservation, as the Native American population is about 43\% of the total population. The life expectancy in Mahnomen County is significantly lower than any of its surrounding counties, all of which have Native American populations that do not meet County Buddy's threshold.

![outputscatterplot](https://github.com/user-attachments/assets/3a5828da-ee0a-4347-965d-43cb0bec4558)
Data from https://ocular.cc.gatech.edu/resiliency-app plotted. Life Expectancy rates across counties are compared to Infant Mortality rates. Counties that meet County Buddy's Native American Population threshold are marked in red, whereas the rest are marked in blue.

---

*Source: InfoDoc.pdf* :contentReference[oaicite:2]{index=2}&#8203;:contentReference[oaicite:3]{index=3}
