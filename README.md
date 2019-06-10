# User-facing interfaces to analysis systems

## User Stories 
Prior to defining interfaces, we are collecting user stories to inform the user-facing interfaces to the analysis system(s)

Examples:

 - [Template Fit](template-fit.md)
 - [Reinterpretation ](reinterpretation.md)
 - [Effective Field Theory Analysis](eft-madminer.md)
 - [Development of an ML-based Jet Tagger](development-of-ml-jet-tagger.md)
 - [Trigger Study](trigger-study.md)
 

## Next steps

This repro describes how this interaction will work. It is imagined that a number of different front-ends and back-ends will exist, optimized to user use cases and also data formats and machine architectures. The hope is an `api` can be declared generally enough to accomodate what we hope will be a rich eco-system.

Specifically, the we hope to put together a collection of documents tha cover the following

- Front End - A few examples of how users might use a front-end. This is necessary to make sure that the back-end `api` is rich
  enough to accomodate the types of operations needed. Specifically, this should contain several examples of what a user might
  type in order to get the job done. There are likely to be a few different approaches to this.
- Back End - A collection of behaviors and requirements one would imagine the backend will have to support, for the same reasons
  that we would talk about the fron tend.
- The `api` that will be the communication between the two.

## Workflow

- Start discussions as issues or add a `.md` file
- Once they have evolved enough, we (Gordon, Emma, Mason) will try to write up something in `mk` in a uniform way. These files will be stored in this repro.

Once that is done we can decide how to publish them (readthedocs, web site, etc.).

