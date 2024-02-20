# Recycling_Concrete_of_Singapore
## Research of urban mining and strategy of the circular construction industry for Singapore. </br>
team: Reda Petravičiūtė, Naohiro Miyaguchi, Roman Pomazan</br>
[IAAC blog link](https://blog.iaac.net/urban-mining-in-the-city-of-pre-cast-concrete/)</br>
The project strategically targets public housing as a place of densification and a source of urban mining, aiming to solve the problem of upcoming precast concrete waste. Therefore a circular micro-district design proposal is created, focusing on processes (new circular hubs, proximity of material distribution), materials (pre-cast modules with upcycled materials) and environment (bioclimatic conditions improvement), applied both in district and city scale. </br>
tools: Grasshopper (Rhinoceros 3d 7), Hops, EarthEngine, Geojson, Json, Scikit-learn, QGIS, illustrator, Photoshop, Urbano, Wallacey, Shrimp, Decoding Spaces.

## Questions
- what are strategic objectives of Singapore as a state to sustain the high-competitive economy in the future?
- how strategic objectives correlate with current construction cycle policies and goals of non-carbon future?
- what could be changed in the policy-making of Singapore to meet the GLobal goals of circular economy?

## What I learned: 
- Data mining with Earth Engine, Json and OSMNX.
- Openstreetmap dat about buildings is not sufficient and biased, thus in order to make a reliable dataset we have to clean and enrich OSM data with data from official sources or ML recognized polygons from satellite images, 
- Data cleaning and preparation.
- Data creation with Scikit-learn.
- Data vizualisation for analysis.
- Generation of scenarios of neighborhood renovation applying the evolutional ML of Wallacey.
- Methods of overlappind map data with Grasshopper and QGIS.
- Methodology-development of scientific research project.
- Map generation with Networkx, OSMNX, Geopandas.
- Processing of complex-layered maps.
- Merging BIM and GIS to ETL

## Key takeaways
- Singapore resolves the housing issue by a unique approach of maintaining the Lion's part of public-funded residences that are leased for 100 years.
- Dominating part of construction materials consists of different states of concrete.
- Constant densification leads to material waste.
- Singapore is one of the main hubs of concrete processing in Asia i.e. importer of concrete aggregates, and the main innovation hub for reused concrete upcycling.
- In 2022 Singapore is downcycling 99% of concrete, nevetheless it is just a tiny share of imported concrete, thus the concrete waste issue is gradually aggregated.
- In 40-60 years the majority of Singapore concrete housings will meet the challenge of the outdated level of zero-carbon embedded emissions.
- Singapore develops and implements several schemes for the updating energy-efficiency of housings.

## Data visualization
### Singapore map of built landscape.
![](visuals/SingaCement-02.png)
### Timeline of the Singapore's urban growth.
![](visuals/SingaCement-06.png)
### Methodology for identification of typologies of buildings.
![](visuals/SingaCement-11.png)
### Mapping distribution of building typologies.
![](visuals/SingaCement-12.png)
### Mapping distribution of building typologies. Heritage lowrise residences.
![](visuals/SingaCement-14.png)
### BIM models of main typologies. Calculation of material share.
![](visuals/SingaCement-23.png)
### Distribution of materials in buildings. Machine learning prediction.
![](visuals/SingaCement-24.png)
### Distribution of lease end in residential blocks, future urban mining sites. Machine learning prediction of ready-to-recycle concrete.
![](visuals/SingaCement-26.png)
### Map of future development zones showing the urban densification.
![](visuals/SingaCement-27.png)
### Map of reserved land sites for the urban densification.
![](visuals/SingaCement-29.png)
### Strategy map of the recycling densification.
![](visuals/SingaCement-34.png)
### Map of proposed blocks for the recycling densification.
![](visuals/SingaCement-36.png)
### Map of future development zones that adopt the recycling densification.
![](visuals/SingaCement-37.png)

## Strategy proposal
To identify public housing mines and the materials they contain, we employed a rule-based algorithm and facade recognition tool. It has helped us to identify 12 material sub-typologies of buildings and revealed that the dominant building typology  is residential high rise, that constitutes  more than half  of the total typologies’ gross floor area (GFA) in Singapore.
By assigning percentages to each building, we observed that pre-cast concrete and concrete emerged as the predominant materials. Furthermore, our analysis revealed that public housing exhibits the highest concentration of pre-cast concrete, emphasizing its significance as an urban mine.

Singapore needs more circular densification approach that would start using existing public housing areas as sources of materials and densification. To address this need, our proposal comprises three key components: a densification strategy, policy considerations, and a design proposal centered around the concept of circular micro districts. First question tries to answer how can Singapore break free from linear urbanization to empty zones?
We’ve discovered that there is no need to build in reserved land sites- densification shoud be focused on circular existing housing stock regeneration, avoiding massive pre-cast waste. The map displays the current gross floor area (GFA) of public housing in violet. By densifying future development sites (brown color), we can achieve just half of the maximum potential GFA for public housing (white colors), accommodating the influx of 1.4 million people.
Once the potential of strategic renovation is unlocked, how should we limit material waste of densification processes and upcycle concrete? For the previously mentioned areas, we  apply the concept of circular micro-districts, which is implements in  both the city and district scales. They are defined as  an existing public housing territories of varying sizes that have reached a 50-year lifespan, but the principles can be applied to a new development as well.

##  References
- Urban mining. Scoping resources for circular construction. Areti Markopoulou, Oana Taut, Hesham Shawqy  [Link](https://link.springer.com/article/10.1007/s44223-023-00021-4)
- Green Strategy Singapore 2030.A comprehensive plan aimed at enhancing green spaces and biodiversity across Singapore.[NParks](https://www.nparks.gov.sg)
- Zero Waste Masterplan. Singapore's roadmap towards achieving a sustainable, resource-efficient future with zero waste.[NEA](https://www.nea.gov.sg)
- Masterplan Singapore 2019. [Urban Redevelopment Authority (URA) Singapore Maps](https://www.ura.gov.sg/maps)
- [Singastat](https://www.singstat.gov.sg/)
- [Data.gov.sg](https://data.gov.sg/)
- [OpenStreetMap](https://www.openstreetmap.org/)
- [Building and Construction Authority (BCA) Singapore](https://www1.bca.gov.sg)
- [Housing & Development Board (HDB) Singapore](https://www.hdb.gov.sg/)
- ISPRS Annals of Photogrammetry, Remote Sensing and Spatial Information Sciences. F. Biljecki. Exploration of open data in Southeast Asia to generate 3D building models. [VI-4/W1-2020](https://isprs-annals.copernicus.org/articles/VI-4-W1-2020/37/2020/)
- Areti Markopoulou. Responsive City Proceedings
- Xining Yang, Mingming Hu, Chunbo Zhang, Bernhard Steubing. [Journal of Cleaner Production](https://doi.org/10.1016/j.resconrec.2022.106215)
- [Circular Prague](https://klima.praha.eu/en/circular-economy.html)
- [Circle Economy](https://www.circle-economy.com/)
- Schoonschip Amsterdam. [Greenprint](https://greenprint.schoonschipamsterdam.org/)  
- [Metabolic Publications](https://www.metabolic.nl/publications/cleantech-playground/)
- Taisugar Circular Village. [BioArch](https://www.bioarch.com.tw/work/taisugar-s-circular-village)
- Second Life Machine Learning Classification of Reuse Materials. [IAAC Blog](https://www.iaacblog.com/programs/second-life-aia/)
- F. Biljecki[ISPRS Annals](https://doi.org/10.5194/isprs-annals-VI-4-W1-2020-37-2020)  
- Dirk E. Hebel and Felix Heisel. Fraunhofer IRB Verlag
