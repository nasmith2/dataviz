# Data Visualization Project

## Data

The data I propose to visualize for my project is about [how people think about technology change in the next 50 years](https://gist.github.com/nasmith2/f7306cec68cf23c53a77f03efe7d70c0#file-technologychangebetterorworse-csv). As technology is developing at a fast rate, understanding how people feel about the upcoming change is important to know. This data is only 5 years old but it gets important data about some of the technology changes that are currently happening. For example, it asked people if they would want to ride in a autonomous car. This is something that is being developed now and is close to being on the roads and is even on some roads in certain countries. 

Another factor it asks about is how people feel about granting drones privileges to fly in the US airspace. Drones in themselves have a huge market if they continue to develop. Finding out how people feel about drones flying around can show if companies need to help promote the benifits of drones flying. The data also shows what people do not want to see in future technology changes. Interestingly enough, by looking at the data in the prototype one can find see that even though most people think that the change in technology will be for the better, most examples that were given the majority of people think they would be the change for the worse.

## Prototypes

I’ve created a proof of concept visualization of this data. It's a quick look at how people feel about some technology changes. Surprisingly it shows that even though the majority of people think that technology change in the next 50 years will be for the better. Servel of the asked topics people think would be bad changes.

[![image](https://user-images.githubusercontent.com/44979955/65468969-be5d6180-de33-11e9-8294-8d729279eb3c.png)](https://beta.vizhub.com/nasmith2/e8a30536332547e3b6ed670a2c9437d6)

## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

Overall, do people think technology change is good/bad and in what instances?
<br />Is there a corrolation between the age or age range and if people think certain aspects are good/bad?
<br />Does education and/or income matter?
<br />Does it matter where someone lives in the country? 
<br /> Task: If a user clicks on a section of the center pie graph, it will change the other pie graphs to only use that data. For example if a user clicks on the green section (for the better) all the surrounding pie charts will change to only use the data from the people who think it is for the better. It will also change the center circle by fading out the other sections to highlight the selected section. 

## Sketches

Sketch 1
![image](https://user-images.githubusercontent.com/44979955/65471628-db972d80-de3d-11e9-8181-a6231255d5f5.png)

The first sketch shows the initial start up screen. If someone selects the show on map option it will show the following:

Sketch 2 is suposed to show a pie chart per region
![image](https://user-images.githubusercontent.com/44979955/65471692-1d27d880-de3e-11e9-9d48-2026760c4ed5.png)

So my plan is to take the prototype and add a couple of menus. The first menu will be a choice on putting the circles on a map of the US. With this, they would have to select what question they want to see, for example they would have to select Driverless car option to display that on the map over a different option. The other menu will change the circles based on the what is selected. If the user selects an age range, it will only show data from that age range. This will be the same for education/income. Both of these menus would be able to be selected at the same time. In other words they can look at what age rand would want to ride in a driverless car and see where in the country people say yes/no.

## Open Questions

I am uncertain on what should be the age ranges that are looked at.
<br />Is there an easy way to accomplish the task that I want to do? To see if the cursor is over a certain data and then use that data?
<br />The dataset has a ton of information that is uncertain. For example, it has columns that represent census region and state but the data in the rows are numbers. I am not sure if I can find what number represents something. 
