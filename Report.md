# Introduction

### Background:
The population of people with lower-limb loss has grown over the past decade in Canada [Hussain, et al., 2019]. Across all Canadian provinces, Ontario has the highest percent of amputations with a 37.7% rate [Imam, et al., 2017]. A recent study reports an average of 2787 new lower leg amputations each year from 2006 to 2012 in Ontario alone [Imam, et al., 2017]. This growing population needs accessible housing.

In Canada, similar to most other industrial countries, majority of the lower limb amputation occurs after admission for diabetic complications [Kayssi, et al., 2016, Imam, et al., 2017]. Other factors for leg amputations are trauma, cardiovascular disease, and cancer. Therefore, having a healthy diet and maintaining an active lifestyle is of paramount importance for this population. The neighborhood in which one lives can increase/restrict access to these amenities. 

### Problem:
Therefore, the goal of this project is to compare and rate the neighborhoods in Toronto where lower-limb amputee people will have accessibility to healthcare, exercise, and a healthy diet. 

### Interest:
Finding supportive neighborhoods for people with disabilities has three groups of stakeholders. Similar to most other health-related data science problems, the main stakeholders are the patients. The other important stakeholder is the government. The government can use this information to fund accessible housing with specific features for people with disabilities in select neighborhoods. Finally, providers such as real estate agents can use this information to help clients with special needs find good housing.

# Data

For all the 140 neighborhoods in Toronto, the following information will be collected:
* Information about the **geo coordinates** of each neighborhood using python geopy.geocoders package
* Information about access (i.e. frequency) to 3 categories of venues (**health care**, **fitness** & **healthy food**) in each neighborhood, using Foursquare API
* Walkability scores for each neighborhood from **Wellbeing Toronto - Civics & Equity Indicators Catalog** found in [toronto open data](https://open.toronto.ca/ "").
* Pedestrian saftey index for each neighborhood from **Pedestrians Killed or Seriously Injured (KSI)** found in [toronto police service data](https://data.torontopolice.on.ca/datasets/pedestrians/data "").

Finally, the neighborhoods will be clustered together base on the information about access to health care, fitness, healthy food, Walkability scores, and Pedestrian safety index. 

# Methodology
# Results
# Discussion
# Conclusion
# Refrences
* Hussain, M. A., Al-Omran, M., Salata, K., Sivaswamy, A., Forbes, T. L., Sattar, N., ... & de Mestral, C. (2019). Population-based secular trends in lower-extremity amputation for diabetes and peripheral artery disease. CMAJ, 191(35), E955-E961.
* Imam, B., Miller, W. C., Finlayson, H. C., Eng, J. J., & Jarus, T. (2017). Incidence of lower limb amputation in Canada. Canadian Journal of Public Health, 108(4), 374-380.
* Kayssi, A., de Mestral, C., Forbes, T. L., & Roche-Nagle, G. (2016). A Canadian population-based description of the indications for lower-extremity amputations and outcomes. Canadian Journal of Surgery, 59(2), 99.

