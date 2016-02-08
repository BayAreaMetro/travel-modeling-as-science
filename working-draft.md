# Travel Modeling as Science

*A Program Proposal*

*Contributors: David Ory*

## 1.	Problem
Merriam Webster defines science as “knowledge about or study of the natural world based on facts learned through experiments and observation”.  Travel forecasting practice lacks a rigorous approach to experimentation.  Progress is therefore difficult to measure, e.g., are we better or worse at predicting the mode choice response to a new (to a region) public transit technology than we were 20 years ago?  As follows, we cannot confidently describe our endeavors as “scientific”.  

## 2.	Proposed Solution
Merriam Webster defines straw man as “a weak or imaginary argument or opponent that is set up to be easily defeated”.  This document puts forward a straw man proposal to address the above problem.  My proposal is a straw man and it, therefore, seeks defeat – though not without provoking, and only by superior ideas.  This document will succeed if (a) it motivates focused discussion and (b) the community continues to call for updated drafts. 

### Overview
The remainder of this document introduces and discusses a Travel Modeling as Science Program.  The primary product of the Program will be an annual release of a model application framework.  The framework will include a model structure that has a demonstrated ability to make useful predictions – by useful I mean reasonably accurate, tractable (i.e., the response of a policy can be easily and logically traced through the model system), and realistic (i.e., the response to a policy is likely to resonate as reasonable and logical with decision makers and the interested public).  The framework will include legible and fast application software that is flexible enough to encourage expansions/modifications.  To use the framework for planning studies, practitioners will be required to prepare the relevant input data, re-estimate coefficients (and/or modify specifications, if desired), calibrate (i.e., adjust alterative-specific constants to match observed conditions), validate (i.e., compare predictions to observations withheld from calibration), and test (e.g., against other historical years, to perturbations to specific variables, etc.).   

The travel forecasting community will put forward annual requests to modify the framework – both the model structure and the application software.  To guide the effort, a non-profit foundation will be established with a seven member board.  The foundatin will be modeled closely after the [Apache Software Foundation](http://www.apache.org/foundation/how-it-works.html). The foundation will form a committee to guide the effort and obtain contractor support, as needed.  The committee will be charged with assessing the requests and incorporating demonstrated improvements into subsequent releases of the framework. This annual cycle will continue – sometimes with incremental changes (e.g., a bicycle route choice procedure) and sometimes with significant ones (e.g., completely new application software).

A hallmark of the Program will be the requirement to demonstrate the value of an improvement prior to the improvement’s incorporation into the annual release.  This demonstration will be carried out across two regions and several historical years.  Such an approach provides the opportunity for travel models to be the formal repositories of what we know to be true about traveler behavior.  And it provides the opportunity for the travel forecasting community to more fully embrace the scientific method. 

The remainder of this document provides specific Program details. 

### Model Structure
The model structure must be defined such that practitioners’ responsibility is limited to input data preparation, re-estimation/re-specification (within a model component, if needed), calibration, validation, and testing.  For example, a model system may have the following components:
* Population synthesizer; 
* Automobile ownership choice;
* Usual work and school location choice;
* Work and school (mandatory) tour generation;
* Work and school scheduling;
* Non-mandatory tour generation;
* Non-mandatory tour location choice;
* Non-mandatory tour scheduling;
* Tour mode choice;
* Stop frequency;
* Stop location choice;
* Trip mode choice;
* Roadway and transit assignment; and,
* Feedback mechanics.

These components will each have a minimum set of inputs, a fixed set of outputs, and a fixed execution sequence.  Consumers of the framework, therefore, will have a reasonably constrained sandbox in which to play.   Please note the above structure is provided only as an example of what a structure may look like.  The framework may have an entirely differest structure and the structure may change with each annual release. 

The model framework’s demonstration of usefulness will necessarily result in at least one set (and more likely two sets – one for each region) of estimated coefficients and calibrated constants.  After downloading the software and test bed input data, potential users will be able to quickly and easily begin running the models for the test bed regions.  Users will be on their own to adapt the system to their own regions. 

Members of the community unhappy with the structure can (and hopefully will) suggest replacement structures.  But for those structures to be considered, they must provide a demonstrable improvement over the existing structure – in terms of predictive accuracy, and/or tractability, and/or realism.
Today we argue over the theoretical superiority of, say, conditioning the non-mandatory location choice on the tour mode choice (or vice versa), and may even put forward estimation results to make our case.  Today we tout a model’s features (e.g., explicitly representing bicycle route choice) while artfully avoiding questions about said feature’s resulting improvement in predictive accuracy.  In the Travel Model as Science Program, ideas will be assessed in the context of practical transportation planning and those with a demonstrated superiority will be adopted.

### The Committee
Following the approach of the [Apache Software Foundation](http://www.apache.org/foundation/how-it-works.html), a project managment committee -- "Committee" henceforth -- will be formed under the guidance of the non-profit fonudation board to oversee the Program.  The Committee’s duties will include the following:
* Report on Program activities to funders;
* Select contractors to support the Committee’s activities and directives; 
* Oversee test bed grants (see below); 
* Oversee research grant programs (see below);
* Oversee advanced practice grant programs (see below);
* Oversee data collection programs (see below); and,
* Carry out other activities needed for the Program to succeed. 

### Calendar
The Program will release an updated version of the model framework each year on the first day of October. The Program will then receive requests for modifications from the travel forecasting community from October to May.  From June to September, the requests will be reviewed, consolidated, and incorporated into the subsequent release per the direction of the Committee. 

### Test Beds
Contributors must demonstrate the value of their proposed improvements across two regional test beds.  The test beds will be the San Francisco Bay Area and the greater Atlanta region. The Metropolitan Transportation Commission (MTC) is the designated metropolitan planning organization for the nine-county Bay Area and the Atlanta Regional Commission (ARC) is the MPO for the ten-county Atlanta Region. I suggest these regions for the following reasons:
* Prior and continued commitment to advancing/improving model practice;
* Prior and continued commitment to data collection;
* Prior and continued collaborative efforts;
* Land development diversity;
* Transportation infrastructure diversity (e.g., toll bridges/lanes, public transit technologies);
* Population diversity;
* Presence of major universities; and,
* Presence of significant visitor travel.

As the program gets underway, a significant effort will be made to establish the best set of observed data for every five-year period between 2000 and 2015.  Moving forward, data collection efforts will focus on having detailed data at five-year intervals (see below).  Proposed model improvements will be assessed across both regions and against the full time series of data.  Assessing model performance across space and time should guard against (though not completely) over fit models. 

To efficiently expand the cadre of test bed cities, a Test Bed Grant program will offer matching funds for locations interested in being a test bed city.  The grant will allow for the maintenance of the region as a test bed through time, provided matching funds continue to be provided.  

### Data Collection
MTC and ARC have made significant investments in data collection over the past 20 years. These efforts are part of the motivation for selecting these regions as test beds for the Program.  A much richer set of data must be collected to sustain the Program moving forward; focused data collection is a key motivation for selecting only two test bed cities.  The following data will be collected no fewer than every five years:
* Household surveys;
* On-board transit surveys;
* Parking inventories and prices;
* Visitor surveys;
* Air passenger surveys;
* University surveys;
* Establishment surveys;
* Traffic counts;
* Transit counts; and,
* Other auxiliary data recommended by the Committee.

Where beneficial and cost-effective, passively collected data will be used to augment and/or replace the above data products.

### Software Management
The annual model structure/software release will be managed and distributed via an online software management system (e.g., GitHub, BitBucket). All of the software will be distributed via a permissive, open-source license, and contributing authors will retain ownership of the software code. Something akin to GitHub’s “pull request” feature will be used to manage suggested improvements and something akin to GitHub’s “issues” feature will be used to track and fix bugs. The software will be released with detailed documentation and an easy installation package.

The Committee will pay particular attention to the design of software proposals, striving to achieve a code base that is fast, legible, and flexible.

### Starting Point
The regional models currently maintained by MTC and ARC are highly similar and were, in fact, developed cooperatively. MTC and ARC are also partners in the ActivitySim effort, which seeks to develop and support an open-source activity-based modeling platform. The existing MTC and ARC models, as applied in the ActivitySim framework, will serve as the starting point for the Program.  MTC and ARC will share relevant survey data going back to 2000 as well as the relevant simulation inputs and outputs with the community to foster Program development. 

Some in our community may believe that the type of activity-based models currently used by MTC and ARC are unnecessarily complicated (and others that the models are too simple).  The Travel Modeling as Science Program can disregard this type of commentary, as critics will now have a systematic means to propose and demonstrate the benefits of simpler (or more complex) approaches.

### Research Grants
To encourage development of the Program, the Committee will administer a competitive grant program directed at academics and private consultants.  The grant will call for the submission of a Program modification request (or, in lieu, a detailed discussion on why the effort failed to generate a request), but otherwise give the principal investigators wide latitude to explore potential improvements.  The research grant program will distribute approximately $8 million annually. Please note that the grant program will fund competing approaches to addressing the Program problem (i.e., the goal is not to invest in and improve a single framework). 

A key motivation for this proposal is the general failure of the technology transfer component of existing research grants (e.g., journal articles, conference presentations) to efficiently advance practice.  Proposed modifications to the Program's framework represent a more useful technology transfer opportunity than existing practice, and the acceptance of said modifications a more useful measure of the return on the grant investment.

### Advanced Practice Grants
To encourage alignment with practice and to extract the best ideas from practitioners, the Committee will administer a competitive grant program directed at practitioners. Grant applicants must be users of the Program’s products (as demonstrated by a published planning study) and must deliver a submission of a Program modification request (or, in lieu, a detailed discussion on why the effort failed to generate a request). The advanced practice grant program will distribute approximately $4 million annually. 

### Funding
The Travel Modeling as Science Program will be expensive – perhaps $20 million or so annually once fully implemented.  The Program, however, represents an opportunity for an order-of-magnitude improvement on the return on investment over the existing paradigm, in which research with a token technology transfer component fails to make consistent, meaningful, measurable contributions to practice, and in which practice proceeds along an idiosyncratic, largely ad hoc, trajectory towards improvement. 

A proposition guiding this document is that articulating, as a community, a useful way forward without fully discussing the fiscal realities is valuable.  As such, this is all I will say about funding, aside from noting several realistic funding avenues exist.  If this document succeeds in motivating a second iteration of its self, a logical next step is a detailed business plan. 

## 3.	Next Steps
A session at the 2016 TRB Annual Meeting was devoted to discussing the strengths, weaknesses, opportunities, and threats to this straw man program proposal.  In response, minor modifications have been made to this proposals and others have put forward other ideas.  We hope to continue the broader discussion at the [2016 Innovations in Travel Modeling conference](http://www.cvent.com/events/innovations-in-travel-modeling/event-summary-b5513a90f03e41cb8bb94047c1a4e53e.aspx).




