#EB2EVT

The EB2EVT translational semantics parser consists of four Haskell programs. 

* FOPEQ.hs: corresponds to the FOPEQ interface.

* Syntax.hs: contains the abstract data types for the various components of an Event-B specification. 

* Semantics.hs: encodes the semantic functions that we have defined in the related paper.

* ParseEb.hs: parses the Event-B specification and generates the corresponding EVT-specifications. This can be run by typing the following command into ghci, once the file has been loaded:

				parseDirectory "DIR"

