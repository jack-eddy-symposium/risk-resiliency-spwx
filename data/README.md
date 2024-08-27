

# Process for preparing integrated event data files
- Download the GIC sensors data from the NERC ERO Portal https://eroportal.nerc.net
- Unzip all files in the downloaded folder
- Add to a new folder in 'data' that is titled 'event_YYYYMMDD/GIC/'
- Process through 'integrate_NERC_event_data.ipynb' to align with the solar wind and geomagnetic activity indices
- Save to an integrated file folder for further analyses


Note that the events after 2023 are saved in thirds due to additional sensors and challenges with memory in creating the integrated files. They are labeled with the additional text of '_onethird' '_twothird' or 'lastthird'
