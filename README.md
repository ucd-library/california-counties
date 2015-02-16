# california-counties
State version of the California county boundaries

# Recent Modifications
## Bureau of Reclamation County Line Modifications - 6 May 2009 - R. Caluza

Since the time of the last update of the county data by the Department
of Conservation’s Farmland Mapping and Monitoring Program (DOC-FMMP)
in July 1997, the California Mapping Coordinating Committee (CMCC) has
requested that the California Department of Forestry and Fire
Protection (CAL FIRE) resume stewardship of the statewide county
boundary data (originally digitized by the US Bureau of Reclamation).
For the past few years CAL FIRE has received suggestions for
enhancements to the county data from multiple sources.  Our latest
update to county lines is based on comments and input from DOC-FMMP,
CA Department of Fish and Game, CA Board of Equalization, Kern County,
Orange County, and Ventura County.  Data editing was performed by both
Department of Fish and Game and CAL FIRE.  All changes are described
below.



When a request was made to change a county line, CAL FIRE looked at
two spatial sources: parcel data from counties, and the set of scanned
USGS 7.5' topo quads (aka 24k DRGs) on the California Spatial
Information Library (CaSIL).  In addition, CAL FIRE also reviewed the
legal text for county boundary descriptions (Government Code Section
23100-23158) on the California Legislative Information website:
http://www.leginfo.ca.gov/cgi-bin/calawquery?codesection=gov&codebody=23101


Documentation for legal boundary changes was also provided to CAL FIRE
by CA Board of Equalization.


### Ventura-Kern and Ventura-Santa Barbara Counties

The two county line sections in question are the western edge of
Ventura County (shared with Santa Barbara County) and one of the
northern edges of Ventura County (shared with Kern County).  Ventura
County Fire Protection District contacted CAL FIRE to let us know that
the Bureau's line did not line up well with their county parcel data.
Parcel data from Ventura County, Santa Barbara County, and Kern County
aligned well with each other, but did not align well with the Bureau's
county lines.  Because Ventura County FPD needs CAL FIRE data to align
with their data, Ventura County FPD requested that we adjust the
Bureau's line.


#### Sources Referenced

* Kern County Parcel Data
* Santa Barbara Parcel Data
* Ventura County Parcel Data
* Ventura County Fire Protection District


#### Result

After considering the sources reviewed, CAL FIRE decided to adjust the
two county line sections that Ventura County FPD requested for us to
adjust.  The need for county boundary lines that agree with the county
linework used by local governments is becoming more critical as more
and more local governments are using GIS data from the state.  Parcel
data from the three counties does not align perfectly (node-to-node)
from county to county.  However, all 3 counties' parcel data
illustrate the northwest corner of Ventura County as being about 0.1
mile west of where it is shown on the Bureau file.  In addition, Kern
parcel data and Santa Barbara parcel data illustrate one of the
northern edges of Kern County as being 0.5 mile north of where it is
shown in the Bureau file.

CAL FIRE edited the Bureau's line by “snapping” the Bureau's northwest
corner of Ventura County to the northwest corner of Ventura County's
parcel data.  CAL FIRE also used Ventura County's parcel data as a
basis for snapping the northern section of the Bureau's line by
snapping the nodes of the Bureau's line to the nodes of the parcel
data.


### Lake-Mendocino-Sonoma Counties


The boundary in question is the southeast corner of Mendocino County
shared with Lake County and Sonoma County.  Department of Fish and
Game observed that the Bureau line did not line up with the scanned
USGS 7.5' quad on CaSIL.


#### Sources Referenced

* USGS 7.5' paper quad, *The Geysers* 1975
* USGS 7.5' scanned quad, *The Geysers* 1993
* Lake County parcel data
* Mendocino County parcel data
* Sonoma County parcel data


#### Result


After examining the 1975 USGS 7.5' quad and the 1993 USGS 7.5' quad
CAL FIRE determined that USGS changed the way the boundary was drawn
in the 1993 quad, which was released after the Bureau digitized the
county lines into GIS format back in 1992.  This is not considered a
legal change because the Public Land Survey System (PLSS) lines (which
form the basis for the county boundary lines in this area) are
represented as dashed lines in both quads, which means neither version
is up to National Map standards.  However, after comparing parcel data
from Lake, Mendocino, and Sonoma counties to the two USGS quads, it is
clear that these counties based their county lines on the more recent
1993 quad.  CAL FIRE adjusted the Bureau line for the southeast corner
of Lake-Mendocino-Sonoma in order to match both the parcel data and
the latest USGS quad.


### Fresno-Merced Counties (legal boundary change - January 1, 2008)

On December 31, 2007 a Merced County press release announced that a
portion of the Merced-Fresno county line would change on January 1,
2008 by officially moving a portion (6.52 sq mi or 4,175 ac) of Fresno
County into Merced County.  The purpose of the change was to enhance
access to emergency services for local residents in the area south of
Dos Palos.


#### Sources Referenced

* Merced County Press Release (12/31/07)
* Fresno Local Agency Formation Commission Report (12/5/07)
* Vicinity Map of boundary change (in LAFCo report)
* California Board of Equalization documents
* Fresno County parcel data
* Merced County parcel data

#### Result


The vicinity map included in the LAFCo report showed which Fresno
parcels would be moved into Merced County.  CAL FIRE adjusted the
Bureau line to the new county line by using the vicinity map and
Fresno County parcel data as guidelines.




### San Bernardino-Riverside Counties (legal boundary change - 2003)

California Board of Equalization reported a minor legal boundary
change along the southern boundary of San Bernardino County (near the
southwest corner of San Bernardino County) shared with Riverside
County.  The section of the boundary that changed is within
unincorporated area that is west of the city of Rialto.  Two former
Riverside parcels were moved into San Bernardino and two former San
Bernardino parcels were moved into Riverside.


#### Sources Referenced


* California Board of Equalization documents
* Riverside County parcel data
* San Bernardino County parcel data


#### Result


California Board of Equalization provided CAL FIRE with copies of
documents confirming the boundary change.  Parcel data from San
Bernardino and Riverside Counties also confirmed the change.  CAL FIRE
adjusted the Bureau line to match with the parcel data.




### Yuba-Placer-Sutter Counties (legal boundary change - 2002)

California Board of Equalization reported an annexation by city of
Wheatland near the boundary of Yuba County.  This annexation indicated
that a legal boundary change had occurred that affected Yuba, Placer,
and Sutter Counties parts of Placer and Sutter had been annexed by
Yuba.  Board of Equalization later provided CAL FIRE with the
documentation that confirmed the county boundary changes.


#### Sources Referenced


* California Board of Equalization documents
* Yuba County parcel data
* Placer County parcel data
* Sutter County parcel data


#### Result


The documents provided by Board of Equalization confirmed the boundary
change among the three counties.  In addition, the parcel data from
the three counties also confirmed the change.  CAL FIRE adjusted the
Bureau line to match the parcel data, using Yuba county parcels as the
main guideline.


### Kern-Los Angeles Counties (legal boundary change - 2001)

Kern County Fire Department (KCFD) reported a boundary change in
northwest Los Angeles County that had not been reflected in the Bureau
county line.  The part of the boundary in question was a segment
shared between Kern County and Los Angles County.


#### Sources Referenced

* State of California Legal text description of Los Angeles and Kern County boundary lines
* California Board of Equalization documents
* Los Angeles County parcel data
* Kern County parcel data


#### Result

After examining multiple sources CAL FIRE confirmed that KCFD was
correct.  The Los Angeles County parcel data and Kern County parcel
data both reflect the boundary change.  In addition the legal text for
county boundary descriptions from the California Legislative
Information website also confirms the change.  CAL FIRE adjusted the
Bureau line so that it would conform to the boundary shown in Kern
County's parcel data.



### Orange-Riverside Counties (legal boundary change)

During their review of the Bureau's county lines in 2006, Department
of Fish and Game observed an inconsistency along the Orange-Riverside
boundary when comparing the Bureau's line with the county line in
co100a from the former Teale Data Center Solutions Group.  The area in
question is in southwest Riverside County.


#### Sources Referenced


* State of California Legal text description of Orange and Riverside Counties
* co100a shapefile (aka 100k counties) from the former Teale Data Center GIS Solutions Group
* Orange County parcel data
* Riverside County parcel data


#### Result


Department of Fish and Game (DFG) confirmed that a boundary change had
occurred by checking the county boundary legal text on the California
Legislative Information website.  DFG adjusted the Bureau line to
match co100a, which was already consistent with the legal text
description.  CAL FIRE also checked the legal text and concurred that
the change was accurate.  CAL FIRE also compared the DFG line
adjustment with parcel data from Orange County and Riverside County
and determined the alignment with parcel data was good.  So CAL FIRE
made no further adjustments to DFG's adjustment in this area.


### Orange-Los Angeles Counties (legal boundary change - August 29, 1999)

The Orange County Local Agency Formation Commission (LAFCo) contacted
CaSIL in 2008 to report that the Bureau's line did not reflect a
change along the Orange-Los Angeles County boundary that occurred on
August 29, 1999.  The area in question is along the northern boundary
of Orange County and shared with the southern boundary of Los Angeles
County.


#### Sources Referenced


* Orange County Local Agency Formation Commission documents
* California Board of Equalization documents
* Los Angeles County parcel data
* Orange County parcel data


#### Result


Documentation provided by the Orange county LAFCo provided clear
evidence of the boundary change in 1999.  CAL FIRE found the area in
question by comparing the Bureau's county line to parcel data for
Orange County and Los Angeles County.  The Orange County parcel data
clearly showed the parcels that Orange County had annexed from Los
Angeles County.  CAL FIRE adjusted the Bureau line to match the county
line as shown by Orange County parcel data.




### Orange County (man-made island)

During a review of the county lines in 2008, Department of
Conservation observed that the Bureau's county lines for Orange County
did not include a man-made island in the Huntington Harbor/Seal Beach
area.


#### Sources Referenced


* Imagery from the National Agricultural Imagery Program (NAIP)


#### Result


CAL FIRE digitized the missing island based on NAIP data.


### San Francisco County (along mouth of bay)

Department of Fish and Game observed that the Bureau's western
boundary for San Francisco County followed the shoreline and did not
include the mouth of the bay between Pt. Reyes (at the southern tip of
Marin County) and Pt. Lobos along the northwest shore of San Francisco
County.


#### Sources Referenced

* State of California Legal text description of San Francisco County

#### Result


Department of Fish and Game confirmed that the bay opening is part of
San Francisco County by checking the county boundary legal text on the
California Legislative Information website.  DFG adjusted the western
boundary to include the bay opening.  CAL FIRE and DOC-FMMP have both
concurred with this change and CAL FIRE has not made any further
adjustments to DFG's adjustment.



### Santa Barbara County (offshore islands)

During their review of the Bureau's county lines in 2006, Department
of Fish and Game observed that the Bureau's county lines for Santa
Barbara did not include Anacapa and Santa Barbara islands.


#### Sources Referenced

* coastn27 coverage from State Lands Commission


#### Result


Department of Fish and Game added the missing islands using
previously-digitized coastline data (coast27 of State Lands Commission
origin).  Both CAL FIRE and DOC-FMMP concur with this change and have
not made any further changes to the DFG linework.


### Changes other than linework


During their 2006 update of the data, Department of Fish and Game
created a multipart version of the counties feature class (using
region topology in coverage format), which has 58 multipart features
(one record for each county in the attribute table).  CAL FIRE updated
linework in both the single part feature class and the multipart
feature class.  Both of these feature classes can be found in the File
geodatabase.


Department of Fish and Game also added three additional attributes
(ABBREV, ABCODE, and FIPS) to both versions of the feature class.  CAL
FIRE has kept these attributes, but renamed the FIPS field to ANSI
(American National Standards Institute) to reflect the Federal
Government's new name for FIPS.  In addition to keeping the attributes
from Department of Fish and Game, CAL FIRE has added an ISLAND
attribute, which indicates with a Y or N if a feature is an island
(making it easy to remove them from display).  CAL FIRE has also
updated the ABBREV field to reflect the new county abbreviations
recommended by CMCC in April 2009.


In the line feature class, CAL FIRE has also added a TYPE attribute,
which classifies the lines into 5 categories: coast, county, island,
stateline, and Mexico.  The line feature class includes a cartographic
representation, which symbolizes the county lines based on the TYPE
categories.


## 14 July 1997 - R. Withers


During the transition to a county line standard for the Farmland
Mapping and Monitoring Program (FMMP) survey counties, it was
discovered that the Bureau of Reclamation's county line file that FMMP
wanted to adopt was outdated in two locations.  A third area believed
to be outdated, but could not be confirmed, was also changed in the
Bureau's master file.  All three changes are described below.


When a county line has changed and no longer agrees with the Bureau's
master file, the preferred order for incorporating the new linework
into it are as follows:


Copying information from digital USGS 7.5' SDTS formatted files
Copying information from digital USGS 100K DLG formatted files
Digitizing off of USGS 7.5' paper quads (if they reflect the new
county line) Any other means where a correct boundary can be
incorporated


The modified Bureau of Reclamation file is named cty24amod.dgn and
contains the following linework changes:


### Butte-Glenn Counties

The area in question is the entire Butte-Glenn county line along the
Sacramento River.  There were subtle and not so subtle differences
between the FMMP's existing county line and what the Bureau was
calling the county line.  Several sources were referenced with no
clear indication of where the line fell.  In all the maps reviewed
there was never a point in the process where the FMMP had to consider
multiple interpretations of the county line.  It was either FMMP's
existing line or the Bureau's.


#### Sources Referenced


* US Census Tiger File
* USGS 100K DLG
* USGS 7.5' DLG
* USGS 7.5' paper quads
* USGS 100K mylar quads
* ETAK
* State of California Legal text description of Butte County and Glenn County lines.
* Butte County Planning Department
* Butte County Public Works
* Butte County Assessor's Office
* Butte County Legal Counsel
* Glenn County Planning Department
* Glenn County Public Works
* Glenn County Assessor's Office


#### Result


After careful consideration of the sources contacted and/or reviewed,
it was determined that the FMMP would adopt the 100K USGS DLG line as
the county line between Butte and Glenn County.  The biggest obstacles
in making this decision were the ignorance of both counties on where
their county line fell, and the USGS contradicting itself as to where
the line went.  The 100K USGS mylar and 100K DLG matched what FMMP was
already using, while the 7.5' USGS paper quad and 7.5' USGS DLG
identified a different county line.  In the end it was decided that
FMMP would adopt the 100K DLG since it closely resembled the line the
FMMP has used all along for these two counties.  The adoption of the
100K DLG line was performed by R. Withers in June 1997.  The entire
common boundary between Butte and Glenn counties was replaced and is
distinguished from the rest of the Bureau's linework by color.  The
change starts at lat. 39° 23' 02.5349” N long. -121° 53' 20.1887” W
and ends at lat. 39° 47' 52.0638” N long. -122° 02' 43.6258” W.


### Orange-Riverside Counties

The USGS, Bureau of Reclamation, and the FMMP all had interpreted the
county line between Orange and Riverside counties in the same way, but
a note from Karen Freeman at the City of Anaheim Planning Department
described a minor change that she was aware of between the two.  Upon
investigation, it was confirmed that a change had occurred.  Since the
adjustment of the line was written using bearing and distance,
R. Withers tried to draw out the line using the precision placement
options of Microstation 95 (version 5 mode).  The legal text was
obtained from the State of California (the county line change is
highlighted in bold and is underlined):


http://www.leginfo.ca.gov/cgi-bin/calawquery?codesection=gov&codebody=23101


23130.  The boundaries of Orange County are as follows:
   Beginning at the northwest corner of San Diego County at a point
in the Pacific Ocean opposite San Mateo point; thence northerly along
the San Diego County line to the southerly line of the Rancho
Mission Viejo as shown on the survey on file in book 8, pages 34
through 46 inclusive of Records of Survey in the office of the County
Recorder of Orange County;
   Thence, easterly and northeasterly to an angle point therein, said
point being Rancho Mission Viejo Corner No. 7, as shown on said
Record of Survey; thence northerly 12,693.95 feet along the
northwestern boundary of San Diego County to the southwest corner of
Section 33, T. 7 S., R. 6 W., said point being also the most
southwest corner of Riverside County; thence northerly 1,324.46 feet
along the western boundary of said Riverside County to the
southwesterly corner of Government Lot 3, Fractional Section 33, T. 7
S., R. 6 W., S.B.M., as shown on that survey on file in book 122,
pages 17 and 18 of Records of Survey in the office of the County
Recorder of Orange County;
   Thence leaving said western boundary south 89*25'11 east, 2,042.68
feet to the southeast corner of the NE.1/4 of the SE.  1/4 of said
Section 33; thence north 01*00'50 east, 1,320.33 feet to the
northeast corner of the NE. 1/4 of the SE.  1/4 of said Section 33;
thence north 00*27'14 east, 2,647.46 feet to the northeast corner of
said Section 33; thence along the north line of said section north
89*16'14 west, 2,086.39 feet to the northwest corner of Government
Lot 1 of said section, being a point on the existing western boundary
of said Riverside County;
   Thence along said boundary of Riverside County northerly,
northeasterly, northwesterly, westerly, northerly, westerly and
northwesterly to a point on the south line of Section 36, T. 3 S., R.
8 W., as shown on that survey on file in book 131, pages 24 and 25
of Records of Survey in the office of the Orange County Recorder,
said point lying distant therein north 89*05'38 west 151.58 feet from
the southeast corner of said Section 36;
   Thence leaving said existing boundary of Riverside County and
along said south line north 89*05'38 west, 2,484.00 feet; thence
continuing along said south line, north 89*07'27 west, 818.46 feet to
the easterly line of the Rancho Lomas de Santiago; thence along said
easterly line north 02*53'27 west, 3,273.18 feet to a point on a
nontangent curve, concave to the northwest and having a radius of
1,550.00 feet, a radial from said point bears north 14*05'30 west;
thence easterly, leaving said east line, along said curve through a
central angle of 15*01'17 and arc length of 406.35 feet; thence
nontangent to said curve, south 84*32'29 east, 155.61 feet; thence
north 65*40'06 east, 75.15 feet; thence north 48*16'56 east, 150.70
feet; thence north 68*49'57 east, 35.37 feet to said existing
boundary of Riverside County;
   Thence northwesterly along the said boundary to the corner common
to Riverside, San Bernardino, and Orange Counties; thence
northwesterly along the southwest boundary of San Bernardino County
to the point of intersection of said boundary with the southerly line
of T. 2 S., R.  9 W., being also the corner common to San Bernardino
and Los Angeles Counties; thence westerly along the township line
between T. 2 and 3 S., to the corner common to T. 2 and 3 S., R.  10
and 11 W.; thence southerly along the range line between R.  10 and
11 W., to the southeast corner of  Section 13, T. 3 S., R.  11 W., in
the Rancho Los Coyotes; thence in a general southwesterly direction
along section lines, quarter section lines and quarter quarter
section lines in the Rancho Los Coyotes, as follows:  westerly along
the section line to the quarter corner on the south line of said
Section 13; thence southerly along the quarter section line to the
center of Section 24, T. 3 S., R. 11 W.; thence westerly along the
quarter section line to the quarter corner on the west line of said
Section 24; thence southerly along the section line to the southwest
corner of said Section 24; thence westerly along the section line to
the quarter corner on the north line of  Section 26, T. 3 S., R.  11
W.; thence southerly along the quarter section line to the center of
said Section 26;
   Thence westerly along the quarter section line to the quarter
corner on the west line of said Section 26; thence southerly along
the section line to the southwest corner of said Section 26; thence
westerly along the section line to the northeast corner of Section
33, T. 3 S., R. 11 W.; thence southerly along the section line to the
quarter corner on the east line of said Section 33; thence westerly
along the quarter section line to the center of said Section 33;
thence southerly along the quarter section line to the northeast
corner of the SE. 1/4 of the SW. 1/4 of said Section 33; thence
westerly along the quarter quarter section line to the center of the
SW. 1/4 of said Section 33; thence southerly along the quarter
quarter section line to the south line of said Section 33; thence
westerly along the township line between T. 3 and 4 S., to the
northeast corner of Section 5, T.  4 S., R. 11 W.; thence southerly
along the section line to the northeast corner of the SE. 1/4 of said
Section 5; thence westerly along the quarter section line to the
northwest corner of the NE. 1/4 of the SE.  1/4 of said Section 5;
thence southerly along the quarter quarter section line to the center
of the SE. 1/4 of said Section 5; thence westerly along the quarter
quarter section line to the westerly line of the SE. 1/4 of said
Section 5; thence southerly along the quarter section line to the
quarter corner on the south line of said Section 5; thence westerly
along the section line to the northeast corner of the NW. 1/4 of the
NW.  1/4 of Section 8, T.  4 S., R.  11 W.;
   Thence southerly along the quarter quarter section lines to the
northeast corner of the SW. 1/4 of the SW. 1/4 of said Section 8;
thence southwesterly in a straight line to a point on the south line
of the Moody Creek Channel as shown on that survey on file in book
120, page 5 of Records of Survey in the office of the Recorder of
Orange County, said point being on a nontangent curve, concave
southeasterly and having a radius of 950.00 feet, a radial from said
point bears south 03*41'24 east; thence westerly along said south
line and said curve through a central angle of 26*34'39 and an arc
length of 440.67 feet to its point of intersection with the east line
of the Coyote Creek Channel, said point being on a nontangent curve
concave northwesterly and having a radius of 5,200.00 feet, a radial
from said point bears north 75*11'46 west; thence southwesterly along
said easterly line and said curve through a central angle of 03*10'
38 and an arc length of 288.36 feet; thence continuing along said
easterly line, tangent to said curve, south 17*58'52 west, 132.27
feet to a point on the existing boundary of Los Angeles County;
thence southwesterly along said boundary in a straight line to the
southwest corner of Section 8, T. 4 S., R. 11 W.  said corner also
being Los Angeles/Orange County Corner No. 11 as shown on Los Angeles
County Surveyor's Map No. 8175 on file in the office of the Surveyor
of the County of Los Angeles;
   Thence south 00*11'50 east, along the section line to a point on
the boundary line between Rancho Los Coyotes and Rancho Los Alamitos,
said point also being Los Angeles/Orange County Corner No. 10;
   Thence south 59*07'40 west, a distance of 3,391.48 feet to Los
Angeles/Orange County Corner No. 9;
   Thence south 39*48'20 west, a distance of 5,650.97 feet to Los
Angeles/Orange County Corner No. 8;
   Thence south 11*36'55 west, a distance of 2,241.41 feet to Los
Angeles/Orange County Corner No. 7;
   Thence south 27*55'55 west, a distance of 8,375.40 feet to Los
Angeles/Orange County Corner No. 6;
   Thence south 31*22'50 east, a distance of 1,296.21 feet to Los
Angeles/Orange County Corner No. 5;
   Thence south 27*12'00 east, a distance of 2,106.10 feet to Los
Angeles/Orange County Corner No. 4;
   Thence south 16*46'45 east, a distance of 1,444.82 feet to Los
Angeles/Orange County Corner No. 3;
   Thence south 2*48'35 east, a distance of 2,207.94 feet to Los
Angeles/Orange County Corner No. 2;
   Thence south 57*10'40 west, a distance of 8,238.78 feet to Los
Angeles/Orange County Corner No. 1;
   Thence south 33*00'00 west, a distance of 622.43 feet to a point
on the northeasterly line of block 59, Alamitos Bay tract, as shown
on the map recorded in map book 5, page 137, on file in the office of
the Recorder of the County of Los Angeles, distant thereon south
57*50'45 east, a distance of 428.91 feet from the most northerly
corner of said block 59; thence continuing south 33*00'00 west, a
distance of three miles, more or less to the southwesterly boundary
line of the State of California (the boundary line between Los
Angeles and Orange hereinabove described and established being shown
on said county surveyor's map No. 8175 ; and likewise on map No.  300
on file in the office of the Surveyor of Orange County); thence
southeasterly along the state line to the point of beginning.


#### Sources Referenced


* USGS 7.5' paper quad
* City of Anaheim Planning Department
* US Census Tiger File
* ETAK
* State of California legal text description of Orange County.


#### Result


The precision placement of the modified Orange-Riverside line was
successful.  However, the Bureau's line does not take into account
minor directional changes north and south of the main area of concern.
As a result, the line had to be redigitized from the USGS 7.5'
quadrangle Black Star Canyon.  The new county line is distinguished
from the rest of the Bureau's linework by color.  The change starts at
lat. 33° 46' 00.4197” N long. -117° 34' 37.4973” W and ends at
lat. 33° 52' 39.0641” N long. -117° 40' 42.3113” W.




### Santa Cruz-Santa Clara Counties

There had been a long history dating back to the late 1980's(?)
regarding the correct placement of the county line between Santa Cruz
and Santa Clara counties.  The 100K USGS map did not agree with the
7.5' USGS quadrangles and the counties were of little help in
resolving placement of the line.  At that time the FMMP decided to go
with the 100K line.


In 1997 the issue came up again because the FMMP line did not match
the Bureau's county line.  Most of the 7.5' USGS paper quads along the
county border were updated by USGS in the early to mid 1990's, and the
legal text description of the county line agreed with what was
represented on the newer 7.5' quads.


#### Sources referenced

* State of California Legal text description of Santa Clara County and Santa Cruz County lines
* USGS 100K DLG
* USGS 7.5' DLG
* USGS 7.5' paper quads
* USGS 100K mylar quads


#### Result


The 100K DLG information was incomplete, but matched the 100K USGS
paper map where DLG information was available.  The 7.5' DLG
information though complete, had some quads that matched the newer
7.5' paper maps and some that appeared to match older 7.5' USGS quads.
The problem was finally resolved by digitizing the entire Santa
Cruz-Santa Clara line off the newer 7.5' paper quads.  This process
was completed in May 1997 by R. Withers.  The change begins in the
south where San Benito, Santa Clara, and Santa Cruz counties meet, and
ends just past the junction of Santa Cruz, Santa Clara, and San Mateo
counties.  The new county line is distinguished from the rest of the
Bureau's linework by color. The change starts at lat. 36° 53' 57.9613”
N long. -121° 34' 49.6766” W and ends at lat. 37° 17' 36.4162” N
log. -122° 09' 35.4072” W.  Modifications to FMMP County Line's Within
Its Files


There are two areas where the Bureau's line and the state's legal text
description agreed, and the FMMP county line was out of date.


A county line adjustment between Kern and Ventura counties resulted in
about 9-10 sq. mi. going from Ventura to Kern County.  The area was
not surveyed on the Ventura side, but falls in the Interim Farmland
area of Kern County.  The addition was photo interpreted and
incorporated into the 1994 Kern County survey area.  Ventura County
was unaffected since the FMMP does not map that portion of the county.


The Tehama-Shasta county line change is located on the Lassen Peak and
Gray's Peak USGS quads and involves about 5 sq. mi. going from Tehama
to Shasta County.  The FMMP loses land from its overall survey area
because there's no soil survey information for that portion of Shasta
County.  All of the land lost is National Forest Service land and was
classified as ‘X' when it was mapped as part of Tehama County.
