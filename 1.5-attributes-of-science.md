## 1.5	Defining Features of Science

Merriam Webster defines science and engineering as follows:

**[Science](http://www.merriam-webster.com/dictionary/science)**:  
> Knowledge about or study of the natural world based on facts learned through experiments and observation. 

The scientific method is the process by which science is conducted, and is based on the elements of: question, hypothesis, prediction, testing and analysis (https://en.wikipedia.org/wiki/Scientific_method).  

However, going back to Galileo's *Two New Sciences*, it has been recognized that even with a strong scientific process, additional community-level components are required to ensure the validity and credibility of science.  These include: 

* Data recording and sharing
* Reproducibility 
* External review

Scientific journals have long been central to ensuring that these community needs are met, by recording the data from experiments, sharing the methods of those experiments so they can be reproduced elsewhere, and providing a mechanism for external reviews.  However, as our data sets become larger, and our models more complex, the limits of the scientific paper as the basic unit of trade are increasingly clear.  While we do not challenge the core role that journals should continue to play, we also recognize that a complementary mechanism is needed to further promote these community scientific goals.  

**Issues in Travel Modeling** 

Even in cases where the model is well formulated and clearly expressed mathematically in an available peer-reviewed paper, it can still be a major challenge to reproduce and build upon existing research.  It may be that the software or data are sitting on a grad student's computer, and if not properly archived there is a risk that the knowledge becomes inaccessible.  When it is acceptable, if care is not taken, the code may be impenetrable to anyone other than the original author.  Or it may be that the model is carefully crafted to work in one specific instance, so applying the model to a different city is challenging.  

The emergence of open-source software and collaborative development sites, such as Github, are an important step towards moving beyond these challenges, because they ensure that the source code is recorded and open to external review and external use.  However, making the source code available is not a sufficient step to ensuring that a model can be shared and used in a practical sense.  This is for two reasons.  First, there is much more that goes into making a model run that simply having the code.  There are typically input data, parameters, and other materials that could be archived with the code, but often are not.  Second, in order to be usable in a practical sense, the model and the software must be specifically engineered to be shared.  Unless there is some mechanism to ensure that what is shared is not just available, but also accessible to an educated user, we may end up with nothing more than large amounts of spaghetti code.  

The challenges of sharing and advancing models in practice are similar to the challenges of sharing and advancing the research.  Often, the models for each city are so bespoke that it is difficult to apply them elsewhere.  Even more limiting is a situation where a model is customized to the point that there is no way of knowing whether the model results are valid for more than one point in time.  When discussing reproducible science in for travel forecasting, the goal is really that it should be reproducible in multiple locations, and across multiple years.  
Otherwise, it is difficult to know whether a finding applies more broadly, or a model works more generally. 

Specific examples of travel modeling projects can be found that do a laudable job of meeting these larger goals of data recording and sharing, reproducibility, and external review.  ActivitySim is one example that has evolved as a collaboration among several public agencies.  It is an activity-based travel model designed specifically to be applied in multiple locations, such that the agencies involved can pool their resources to advance the whole, rather than spending their effort recreating what others have done.  

**Principles of Travel Modeling as Science** 

It is ultimately that ready extension of existing work that this endeavour seeks to enable, both as a means of ensuring the validity of the existing research, and to enable future research to progress efficiently.  We propose that the community-level components of science can be adapted to travel modeling using three core principles: 

* Data sharing and recording -- Someone, other than the original developer, should be able to download and use the model.  
* Reproducibility -- The model should work for more than one location, and for more than one point in time.  
* External review -- Performance measures should be reported for more than one location, and for more than one point in time, allowing for external review of model outcomes.  

The following sections outline a proposed approach to promoting the adoption of these principles in travel modeling and to advancing travel modeling as a science.  








