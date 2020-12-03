Advantage Platforms
==========================



### What scientific or technological uncertainties did you attempt to overcome? (Maximum 350 words)


System uncertainty necessitated experimental development to bring Artificial Intelligence (AI) and Machine Learning (ML) to the mortgage lending business.
The mortgage technology industry wished to advance Artificial Intelligence (AI) and Machine Learning (ML) applications.
Advantage Platforms has developed a SaaS based system for mortgage underwriting.
It uses a virtual underwriter to assess data and provide options for a mortgage.
We are advancing our model by extending the system into a virtual agent model, and extending the virtual agent model into other financing institutions.

The framework for the virtual underwriter involved an interface created with our Crystal Tools.
It was assumed that the virtual agent would largely be a facsimile of the virtual underwriter,
however,
fundamental principles of the mortgage industry made a straightforward agent/underwriter AI relationship much more complex,
requiring extensive experimental development to hypothesize a framework which could encompass the various lending markets and the differing players
&mdash;
like banks and Credit Unions
&mdash;
of the mortgage world without constantly resetting transactions due to legal constraints on an underwriter.

We hypothesized that we could develop a process for ingesting, storing, analysing, and communicating deal data, which could be sent through a set of algorithms and a result option will be generated and applied automatically, which is optimal based on the mortgage parameters in question; and could improve processing time to less than 1 minute. If it proved not to be a good result, it will be sent back to the ML for improvement. In order to understand what deal result set is best suited for rejection still stands as a current obstacle in our research.

### What work did you perform in the tax year to overcome the scientific or technological uncertainties described in line 242?

We set up a data ingestion model to straddle a developmental environment for the virtual agent model that interacted with a
system already using a virtual underwriter.
We created scenarios to test our hypotheses in an effort to create a unified system that can begin and end an interaction between an agent and underwriter with a deal or no possible deal,
with no market unexplored,
from the lowest risk parameters and attributes of the prime market to the higher risk lending market atributes and parameters.
Our virtual underwriter takes the outcomes and analyzes them to not only interpret the data and parameters, but also as a result, force an action/outcome a human might take.
We analyze the data to see if there is a match against our scenarios.
Using a Microsoft Azure and C Sharp technology stack,
we continued developing the datasets within the ML modelling tools we built last year, to analyze data and decisions in an effort to teach the agents how to recognize context,
change context,
and adapt to situations in a manner befitting a human intelligence.

In order to achieve this, we realized we needed to introduce to our model new paramaters and attributes related to multiple markets defined by risk, or
prime and sub-prime markets,
where sub-prime could be a host of alternative markets based on the risk of the lender,
down payment,
and a host of other conditions,
coupled with different rules for Credit Unions.

For example, an agents and underwriters must define what market a client is in.
If an agent and an underwriter engage each other for an AI transaction,
and the underwriter does not have binding authority for sub-prime markets,
the entire transaction has to begin anew with a new AI underwriter authorized to work in sub-prime.

through experimentation we realized that the first layer of the mortgage market parameters separates people into different group attributes based on
primary characteristics.
We next use the ML models to incorporate the data of Credit Unions as another possible context to secure lending,
to determine what shared infrastructure can exist between the two underwriter AI systems.

There are several option parameters for a virtual agent model to make a deal work based on predicted results.
It can restructure the deal,
override decisions,
decline deals,
change products within a suite,
or change the lender to reset variables.
We are saturating our ML with data for a universal lending AI,
where universal encompasses Credit Unions,
banks,
and other lenders.
We are trying to achieve high accuracy, based on risk parameters, and other factors, which would mimic the actions a person would do.

We worked on role perspective in the AI.
At present,
we are writing the application as if it were the lender,
but it can be written to serve other perspectives as well,
like a mortgage broker.

The next major hurdle was realized when it was made clear that different types of agents would have to be created to meet distinct authorizations.
In essence,
the agent definition
&mdash;
prime or some form of sub-prime
&mdash;
correlates to the options available to them and their binding authorities.
An authorization structure pivoted off the data sets available to construct mortgage options,
which are determined by what kind of market parameters are ingested.
This required that we have the ability for virtual agents to pass real clients based on the available markets.
When the agents changed we had to reconfigure all the data for available options,
so,
in essence,
switching of agents was resetting all state to the new scenario.
By year end, we were experimenting with transitioning state to new authorized AI elements so we don't have to reset, which impacted our processing goals.

### What scientific or technological advancements did you achieve or attempt to achieve as a result of the work described in line 244? (Maximum 350 words)

Advantage Platforms’ Crystal Tools were created for the purpose of developing a technology layer that would overcome existing limitations in easily be able to plug into existing environments. It would sit in front of a system and in-between broker systems where it would assess the deal in process and determine under-writer base. The Current state of technology is that any deal is manually analyzed and scored for criteria. We developed the approach to eliminate this interaction by applying Models to analyzing each criterion and consider if they are aligned with the intent. The model determines if changes or additional input data is needed.

To accommodate full automation, interfacing with external mortgage systems was necessary to attain a certain offer result.  Advancements included closing deals as quick as possible: under 30 seconds is ideal, a minute or more was too long. We were able to achieve 1-2-second deal data processing times.  This changed the way underwriters would interact with users. Deals could potentially then be restructured to offer more result offerings, within a range of the original options, building in predictive concessions. Our Crystal tools ensure that no offer will be placed in front of an end user unless it suits their situation and works. This allows flexible deal flow.  

The key learning gained from this experimentation is in the development of machine learning powered option analysis tools, which can reduce the turnaround time for mortgage analysis from days to minutes.

In the fiscal period 2020,
we created a development and testing environment that incrementally applies changes to a last years advancements, for the purpose of creating two AI agent concepts,
an underwriter and an agent/broker,
interacting within numerous AI perspectives and base lending environments,
prime and sub-prime.
We have significantly advanced by experimental research the automation of mortgage lending through AI,
operating as both agent and underwriter.
