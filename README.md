# Summary
This project analyzes U.S. mortality data from 2020–2023 to understand how COVID‑19, pneumonia, and influenza deaths vary across states and regions. Using a dataset of over 22,000 records, the project visualizes geographic and temporal patterns through maps, aggregation charts, and interactive dashboards. The main objective was to identify regional differences in COVID‑19 mortality and compare them with other major respiratory illnesses to uncover broader public‑health trends.


# My Role 

I was responsible for designing and implementing all interactive visualizations used in this project. My work focused on transforming static mortality data into dynamic, user‑driven tools that allowed deeper exploration of COVID‑19, pneumonia, and influenza trends across U.S. regions and states.


# Core Responsibilities

-Developed two fully interactive visualizations (bubble chart + bar chart) using Python libraries that support dynamic UI elements such as sliders and dropdown menus

-Engineered region‑based filtering to allow users to explore respiratory‑related deaths by year, disease type, and geographic area

-Built interactive dashboards that improved data accessibility and enabled users to compare states and regions in real time

-Optimized user experience by ensuring smooth transitions, intuitive controls, and clear visual encoding of mortality patterns

-Collaborated with the team to align interactive components with the project’s analytical goals and narrative structure


## Technical Implementation

*Data Processing:*
- Cleaned and filtered the dataset (2020–2023) using Pandas
- Mapped states to regions and aggregated deaths by state, region, year, and disease
- Reshaped data with melt() for multi‑disease comparisons

*Interactive Bar Chart:*
- Built a horizontal bar chart showing total COVID‑19 deaths by state
- Added a region dropdown to control filtering
- Callback logic updates and sorts the chart based on user selection

*Dash Application Structure:*
- Structured the UI with html.Div, dcc.Slider, dcc.Dropdown, and dcc.Graph
- Connected all components through Dash callbacks for real‑time interactivity


