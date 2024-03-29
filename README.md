# Synthesizing the Conservation Status of Cave Species 

---

#### No one has synthesized the available conservation data for North American cave species over the past 20 years. This project aims to synthesize and analyze conservation data for over 1200 species of cave animals from the United States and Canada.

---









### What are the Goals?

#### Specific Goals
   * Use the obtained and analyzed data to write an academic paper that includes figures generated throughout the summer on specific areas of analysis (ex. By region, by status)
   * This goal would be considered successful in the event that graphs can be generated on trends that my partner and I are interested in and that they include meaningful data that furthers the goal of synthesizing the conservation status of cave species 
 #### Stretch Goals 
   * (Mainly Specific, but not asked by partner) Creating an interactive dashboard
   * Including bar graphs from every region that can be filtered by a drop-down menu 
   * This would also contain a map that shows each region by the color that correlates with the level of endangerment (dark red shaded would be critically imperiled) 
   * Also has a search function for species by taxonomic categories 
 #### (Big stretch goal) Setting up an API that will keep the dashboard constantly updated whenever data is added/changed on Nature Serve 
  * This goal would allow the dashboard to keep running and easily accessible to edits to anyone who takes this project over in the future 
  * This would essentially make the dashboard a database for all updated info about cave species including location, global and region status, and any other   information that we would like to pull from nature serve 
 #### (Extreme Stretch) This goal would probably not be completed by me unless I continued to work on the project into the fall, but I think it could be possible to make some predictive model of a timeline for when a species could be extinct 
  * This would require finding all of the data on the estimated populations of these species and then looking at the population of species over time that has now gone extinct
  * This could potentially show “it’s estimated that in X number of years this species will be extinct based on what happened to previous ones over time” 

### What could go wrong?

####   Error in code
  * Being mostly a one-man team I think it could be likely that there is a slight error in the code that could lead me to believe there are certain trends that aren’t actually true
  * Before confirming any “Big findings” I plan on running my analysis with my partner as well as my mentor to make sure that I have not come to a conclusion about data that is not true due to an error in coding 
This can also be combatted by commenting on all of my code to make sure it is understandable/reproducible 

####  Not being creative/original enough
  * This could create an issue as this is a conservation status being synthesized from existing data, meaning that all of our data is out on the internet somewhere. With this being said, I need to create a dashboard that brings something to the table that other resources do not in order to make it effective for future use by students, researchers, professors, etc. (This may not be the entire goal, but it would be great to get that use out of the dashboard)
  * I think this can be avoided by constantly brainstorming and asking myself if my future product has attributes that no other website/data collection site has (Ex. Nature Serve)

####  Communication Issues
  * Communication will be essential to this project, especially with my partner Dr. Zigler. Especially with a majority of this project being exploratory I have to be certain that I am not missing out on any of the concepts that Dr. Zigler wants to look into by getting distracted with other possible directions that the project could go into. 
  * To contradict this issue it will also be important to not limit myself on waiting for tasks from Dr. Zigler, but by being proactive in the data analysis process. 

Link to the goals and risk analysis presentation: [Stop the Raves in the Caves.pdf](https://github.com/sewaneedata/caves/files/8958463/Stop.the.Raves.in.the.Caves.pdf)



### Client Perspective Report 

  It is apparent that no one has specifically synthesized the available conservation data for North American cave species over the past twenty years. While this is the case, the website Nature Serve is periodically kept up to date with information on various species about their topics such as regional status, global status, range extent, and taxonomic data, which I hope to compile into a data set for analyzation. In fact, this is what I aim for this project to succeed in doing; synthesizing and analyzing conservation data for 1200 species or more of cave animals from within the United States and Canada. 


  What I see as an end goal for this project is using the data that would be collected and analyzed to write an academic paper covering the topic of the conservation status of cave species across North America. Through collecting this data I hope to explore and find many different trends that serve a purpose even further than an academic paper. It is uncertain at the moment, but I am open to ideas in which one would be building an interactive dashboard that displays any trends or maps of the data that we collect in hopes that this could possibly be used as a database for conservation data to be used by but not limited to Sewanee students and Professors in the future. 


  I am extremely interested in this field and have a strong passion for conserving the biodiversity of cave species and aim for the product of this research to support conservation planning by highlighting species in need of conservation and as well as regions with high numbers of imperiled cave species. 

Link to the client perspective presentation: [Client Perspective .pdf](https://github.com/sewaneedata/caves/files/8958470/Client.Perspective.pdf)

### Literature Review 

#### Recent Work

Recently, reviews have been done on the biodiversity of certain cave species in the United States and Canada. Niemiller et. al (2019) published a paper that includes Troglobionts (terrestrial obligate cave species), the particular species that we are interested in, noting that this species along with stygobionts (aquatic obligate cave species) make up more than 50% of the imperiled United States fauna that is tracked in the central databases of the Natural Heritage Program. Along with this, Niemiller et. al (2019) states that 71% of troglobionts and stygobionts are of conservation concern and at a risk of extinction based on NatureServe criteria. NatureServe criterion is a key to understanding how at risk a given species is. Niemiller’s work begins with a literature review discussing the challenging environment of caves and associated subterranean habitats in karst and non karst terrain areas. These environments have caused parallel and convergent evolution of many characteristics and traits of these species. Parallel evolution refers to independent species acquiring similar characteristics by evolving simultaneously while also in the same environment. In relation to parallel evolution, convergent evolution occurs when the descendants of a certain species resemble each other even more than their ancestors did. The main factors of these types of evolution for the cave species are the complete absence of light and limited food resources. This evolution has also caused a change in how we see these subterranean cave species as they lose their pigmentation from the lack of light, making them almost see-through. 

#### NatureServe

“NatureServe is a nonprofit organization that provides the scientific bases for effective conservation action. NatureServe and its hemisphere-wide network of natural heritage programs are the leading sources of information about rare and endangered species and threatened ecosystems” (NatureServe 2012). NatureServe is a database we have used to gather the data to form our dataset for this project. They provide a wide variety of information on each species, including global and regional status, which are extremely important for gauging the current state of a species. Even with the importance of these ranking systems, NatureServe has discussed possible issues with the system. “It is important to remember, however, that regardless of improvements to the assessment method and use of the rank calculator, resulting calculated ranks are only as good as the quality of information used to assign ratings to the underlying individual status factors”(NatureServe). Of course, it would be impossible to have a completely accurate method for subterranean-rank species, so NatureServe continues to be one of the most, if not the most, valuable resources regarding data on cave species. Their global status ranking system is as follows: G1: Critically imperiled, G2: Imperiled, G3: Vulnerable, G4: Apparently secure, G5: Secure. Along with those five rankings, NatureServe has others including GX, GH, GNR, and GU for species that are presumed extinct, unranked, or unrankable. 

### Data Dictionary 

#### Caves Dataset 
* 10 Columns, 1628 Rows 
* Species
  * This column contains every species that was gathered from the API on NatureServe (Original list from Niemiller 2019)
* Common Name 
  * This column gives the common name for each species that was pulled from NatureServe 
* Kingdom 
  * Taxonomic description
* Phylum
  * Taxonomic description
* Class
  * Taxonomic description
* Order
  * Taxonomic description
* Family
  * Taxonomic description
* Global Status
  * This column contains a global status for each species varying from G1: Critically Imperiled all the way to GU: Unrankable 
* Region
  * This column gives the region in which the species is located 
* Region Status 
  * This is a similar criterion to Global Status, but only applies to the region/state so the rankings may vary from the global status

The purpose of this dataset is to be used for analysis to see trends in which region/species/family is the most at risk or secure. After finding these trends, the dataset should be used to generate graphs/tables that can be inserted into an academic paper that will be written on the topic that encompasses all of the data. 

### Products Required 

The future end product we hope to accomplish from this project is an academic paper that outlines trends in the data gathered from NatureServe on over 1100 different cave species. These species are a mixture of different endangerment levels, and we hope to be able to highlight regions and species that are most at risk through this process. It is extremely important to be thorough in our data collection and analysis as no one has analyzed the available conservation data on endangered cave species in 20 years. An academic paper will give a voice to the species that are especially vulnerable and in need of attention. Along with writing a paper, a dashboard will be part of the end product. Even though the use of the final dashboard is still unknown, many directions can be taken when the data is formatted in an easily understandable and accessible format to the target audience. Whether it be researchers, professors, the general public, or students, this dashboard will highlight the importance of the state many cave species are in across the United States and Canada.


It is already known that this data is available on the internet through NatureServe explorer, but what we hope to provide by analyzing it will be unique and valuable in the future for conservationists. NatureServe allows the user to search for species by species or even in groups but does not provide a collection of data that relates all of the species' endangerments and locations to each other. The dashboard that we are creating will plan to do exactly that. With the visualization of all global statuses of the available cave species, we can successfully outline the states/regions that have the greatest population of vulnerable species. Along with using a map to visualize what vulnerabilities look like on a large scale, other tabs will focus solely on the state/region level underlying the different types of species at risk. 


The choice of a dashboard was simple in that it is all-encompassing in ways where we can include statistics on the data that we have analyzed, as well as visualizations to create a perspective of how many states are truly struggling to protect their cave species. Another important reason for choosing a dashboard would be the interactive qualities that it can have. The dashboard can potentially be used as a search function that could highlight a specific Phylum or Order on the map, showing all of the specific areas where that subset is the most vulnerable.


### Final Products 

#### Poster 

Click the link to view our final product poster! [_Caves- DataFest Poster 24x36 design .pdf](https://github.com/sewaneedata/caves/files/9162401/_Caves-.DataFest.Poster.24x36.design.pdf)

#### Demo Video 

Click the link to view a demo video that guides you through our interactive dashboard! 

