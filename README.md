# UFO

## Overview of Project
The purpose of this project is to display UFO sightings data in an easily viewed format that can be filtered.

## Results 
The webpage automatically displays all sightings in the data file. 
[image]
The user is then able to use the filters to find more specific data.
[image]
By using the Bootstrap framework, the page has built-in responsive design
[image]

## Summary 
The UFO sightings page displays an image header, a brief statement of purpose and the table listing UFO sightings.

### Recommentations for Further Development:
- Sort viewings from most recent to earliest. This way, when loading the page, the most recent sightings are the first ones listed.
- Remove the country filter - only two sightings from outside the US are listed (both from Canada), so this filter is not useful. Update the 'state' column to say 'state/province'
[image]
- Update the display for the table to properly captialize the state, city, and country columns. Currently they are all lowercase, which looks unprofessional.
### Drawbacks of the Design
- Originally, the filters were case-specific. I took the liberty of updating them to ignore case as it was a significant drawback.
- The page displays all results. Currently the list is short, but if it gets too long, the page may not fully load. In the future, the table may need to be paginated, or the filters may need to include an option to limit the number of results.