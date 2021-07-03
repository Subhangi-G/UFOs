# UFOs

## Overview of Project 

### Purpose

The purpose of this analysis is to build a dynamic webpage on UFO sightings.\
This interactive webpage includes a header, article summary, a brief article, and a table of sighting information.\
Users can refine their search on multiple levels to obtain more refined results. 

### Resources used
- Data Source: 'data.js' (javascript files with information on sightings including datatime, city, state, country, shape, duration minutes, and comments.) 
- Software: ECMAScript2015, d3.js 4.11.0, Bootstrap v4.0.0


## Results
The webpage was built by inserting javascript into an HTML page. Furthermore Bootstrap, and CSS were used to style the page.

Initially a table was was inserted to hold and display the ufo sightings data in a clean and clear manner.\
Then filters were added to allow users to refine their search criteria based on date, city, state, country, and shape of the sighting. The filters also have a placeholder to guide the user input. The user may input more than one criteria to fine tune the results.

Below is a picture of the webpage when all the data displayed. This is the default display when the page is first loaded.

<Add PICTURE>

On the left of the webpage is a panel for the user to input different search criteria.\
Once the user adds in a filter and hits enter, the table is automatically updated as per the criteria entered.\
Below is a pitcure depicting table filetered on one search criteria: sightings reported in one particular city.

<ADD PICTURE> Table with one search criteria.

The user may further refine the search by entering more search criteria. Each time the user enters a filter, the table updates to display the data taking into account the added filters.\
The figure below shows an added criteria to the already filtered data shown above.

<ADD PICTURE> Picture when search critera is further refined.

THis picture shows an updated table when a further filter is added on the date, along with the city, and shape.

<ADD PICTURE> with 3 search criteria

The user may keep refining the data to accomodate any number of the given filtering criteria.\
The user can re-populate the webpage with all of the data by clicking on "UFO sightings" at the top left corner of the page. 


## Summary 

### Drawback
- One drawback of this present design is that criteria for filtering the data requires the user to povide an exact match to the data present.\
For example, filtering on a state requires the postal code to be entered in lowercase letters. This is not intuitive because postal codes are typically represented by upper case letters.\
Similarly names of places also start with an uppercase letter.\
However, in the present form, if an exact match is not given while entering the names of places, then an empty table will be returned, even if data exists for that particular filter. This is inaccurate.\
The search needs to be flexible to provide relevant results even if there is no exact match in the search criteria.

### Recommendations
1) A recommendation to further develop the interactive webpage would be to allow users to update the sightings table based on their recent sightings.\
This would be a fun and engaging way for amateur ufologists and citizen-scientists to maintain a resource with complete and updated UFO information. 

2) Furthurmore the webpage can also introduce a mechanism that will enable users to provide feedback on the authencity of the sightings.\
For example putting in a "like" feature, maybe enhanced with a comments feature, and a way to link to pictures taken of sighting events.

3) Introducing a panel with rotating pictures of different UFO sightings would be a nice feature to add to the webpage. Not only would it make the webpage visually appealing, but also provide credence to the claims of ufologists, and ufo-enthusiasts.