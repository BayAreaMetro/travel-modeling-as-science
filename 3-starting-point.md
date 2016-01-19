## Starting Point

###Model Structure
The model structure must be defined such that practitioners’ responsibility is limited to 
input data preparation, re-estimation/re-specification (within a model component, if 
needed), calibration, validation, and testing.  For example, a model system may have 
the following components:
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

These components will each have a minimum set of inputs, a fixed set of outputs, and a 
fixed execution sequence.  Consumers of the framework, therefore, will have a reasonably 
constrained sandbox in which to play.

The model framework’s demonstration of usefulness will necessarily result in at least one 
set (and more likely two sets – one for each region) of estimated coefficients and 
calibrated constants.  After downloading the software and test bed input data, potential 
users will be able to quickly and easily begin running the models for the test bed 
regions.  Users will be on their own to adapt the system to their own regions. 

Members of the community unhappy with the structure can (and hopefully will) suggest 
replacement structures.  But for those structures to be considered, they must provide a 
demonstrable improvement over the existing structure – in terms of predictive accuracy, 
and/or tractability, and/or realism.

Today we argue over the theoretical superiority of, say, conditioning the non-mandatory 
location choice on the tour mode choice (or vice versa), and may even put forward 
estimation results to make our case.  Today we tout a model’s features (e.g., explicitly 
representing bicycle route choice) while artfully avoiding questions about said feature’s 
resulting improvement in predictive accuracy.  In the Travel Model as Science Program, 
ideas will be assessed in the context of practical transportation planning and those with 
a demonstrated superiority will be adopted.
