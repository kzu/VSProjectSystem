Introduction to new project from wizard
=======================================


A diagram showing the relationship between user's project, project type
, CPS and VS would be helpful

·         If CPS was using inheritance, things would be easier to figure
out by looking at the base class; but it doesn't

·         What else can the user import in his custom project type besides
what is offered in the template?

·         What other CPS specific properties can the user set on the
msbuild side (targets, props)


Which IVS interfaces does CPS implement? How does it interact with the
rest of VS (editors, intellisense, solution explorer, debuggers, etc)

·         We need a list of the different CPS components/parts that the
user gets for free - e.g. integration with solution explorer, integration
with debug drop down target, integration with project properties, etc…

·         What extensiblity points does it offer for each component?

    o    Msbuild properties
    
    o    Code - Interfaces, Exports, etc
    

Need a page explaining a high level view of what gets generated by default
by the wizard
