# Decoding Emergency Radio & Mapping Areas of Need
---
A `General Assembly` Project with contributions from myself, Patrick Cavins, Remy Shea, Maithili Joshi, Charles Rice, Matt Brems, and numerous other online educators, scientists, and coders.

##### Whenever there is a disaster, especially a large one where FEMA is involved, logistics can be overwhelming. During National emergencies it is crucial FEMA identify the areas in need. Not only does FEMA require an understanding of the nature of emergencies, they need to be able to map where those emergencies are taking place. Furthermore, it is imperative to provide failsafes and redundancies for such crucial information.

##### After 9/11 FEMA helped establish the National Incident Management System. It helped standardize protocols for emergency response dispatches.

##### The value proposition for harnessing emergency dispatch data is substantial. The data made available through this code provides answers to important questions for FEMA.

- `Where are emergency services going? Same places?`
- `How effective are the dispatch calls? Do personnel have access to all necessary information that gets them to areas of need expediently?`
- `Are the radio calls being converted to human-readable spreadsheets of data for lay people to use?`
- `Is there a need for data redundancy using S2T and NLP in case other cataloging methods fail?`
- `How would you create a resource for emergency response data when another database is not accessible?`

##### The goal of this project is to create a system for extracting addresses from emergency radio and mapping those locations. 

##### The group decided to focus on Boone County, Missouri, as the testing location. It is small and uses modern dispatch methods. One of the GA group members grew up nearby.

##### Because emergency dispatch calls begin with identifiable alert tones, our group was able to use those tones to segment audio feeds into individual audio files. From there it was an NLP-based approach and then, finally, geocoding and mapping.