Advantage Platforms
==========================



### What scientific or technological uncertainties did you attempt to overcome? (Maximum 350 words)


System uncertainty necessitated experimental development to bring Artificial Intelligence (AI) and Machine Learning (ML) to the mortgage lending business.
The mortgage technology industry wished to advance Artificial Intelligence (AI) and Machine Learning (ML) applications.
The system uncertainty arose from the complex relationships between underwriters and agents and the defined markets in which they operate,
beginning with prime rates and descending from there.
Advantage Platforms has developed a SaaS based system for mortgage underwriting.
It uses a virtual underwriter to assess data and provide options for a mortgage.
We are advancing our business model by extending the system into a virtual agent and into other financing institutions.

The system uncertainty involves melding rules from different lending institutions.
A bank is an entirely different entity than a Credit Union,
legally speaking.
They are not legally bound to the risk rules in the banking sector,
and a mortgage client who might be sub-prime in the banking world could very well get prime rates at a Credit Union.

The framework for the virtual underwriter involved an interface created with Crystal Tools.
It was assumed that the virtual agent would largely be a facsimile of the virtual underwriter,
however,
fundamental principles of the mortgage industry made a straightforward agent/underwriter AI relationship much more complex,
requiring extensive experimental development to hypothesize a framework which could encompass the various lending markets and the differing players
&mdash;
like banks and Credit Unions
&mdash;
of the mortgage world without constantly resetting transactions due to legal constraints on an underwriter.


There are multiple markets defined by risk,
for example prime and sub-prime,
where sub-prime could be a host of alternative markets based on the risk of the lender,
down payment,
and a host of other conditions,
coupled with different rules for Credit Unions.

Agents and underwriters must define what market a client is in.
If an agent and an underwriter engage each other for an AI transaction,
and the underwriter does not have binding authority for sub-prime markets,
the entire transaction has to begin anew with a new AI underwriter authorized to work in sub-prime.

This is an affectation of the legacy data systems in the mortgage lending world.
The uncertainty was in the way forward for an AI agent that could represent both the prime and sub-prime markets in the mortgage world,
and include the different rules of Credit Unions.
This builds upon machine learning and deal analysis,
also conducted this year.

### What work did you perform in the tax year to overcome the scientific or technological uncertainties described in line 242?


We set up a data ingestion model to straddle a developmental environment for the virtual agent that interacted with a production system already using a virtual underwriter.
We created scenarios to test our hypotheses in an effort to create a unified system that can begin and end an interaction between an agent and underwriter with a deal or no possible deal,
with no market unexplored,
from the lowest risk of the prime market to the higher risk lending markets.
Our underwriter takes the outcomes and analyzes them in an effort to force an action a human might take.
We analyze the data to see if there is a match against our scenarios.

Using a Microsoft Azure and C Sharp technology stack,
we developed ML models to analyze data and decisions in an effort to teach the agents how to recognize context,
change context,
and adapt to situations in a manner befitting a human intelligence.

The first layer of the mortgage market separates people into different groups based on their primary characteristics.
These groups are basically prime and variations of below prime.
We are using ML to incorporate the data of Credit Unions as another possible context to secure lending,
to determine what shared infrastructure can exist between the two underwriter AI systems.

There are several options for a virtual agent to make a deal work.
It can restructure the deal,
override decisions,
decline deals,
change products within a suite,
or change the lender to reset variables.
We are saturating our ML with data for a universal lending AI,
where universal encompasses Credit Unions,
banks,
and other lenders.
We are trying to mimic something a person would do.

We worked on role perspective in the AI.
At present,
we are writing the application as if it were the lender,
but it can be written to serve other perspectives as well,
like a mortgage broker.

The basic machine learning (ML) and scenario framework is in production.
It represents the virtual underwriter.
The problem with integrating the virtual agents,
which would be the tandem AI interface to the traditional two-party negotiation between underwriter and broker,
is that it has to build upon a production system.
The creation of the virtual agent,
and the integration of the Credit Union rules,
means that aspects of the integration require changes to the production system,
especially for testing.
This entailed the tearing down and parting out of the main ML application into a number of integrated smaller applications.

The next major hurdle was realized when it was made clear that different types of agents would have to be created to meet distinct authorizations.
In essence,
the agent definition
&mdash;
prime or some form of sub-prime
&mdash;
correlates to the options available to them and their binding authorities.
It pivoted off the data sets available to construct mortgage options,
which are determined by what kind of market you are in.
This required that we have the ability for virtual agents to pass real clients based on the available markets.
When the agents changed we had to reconfigure all the data for available options,
so,
in essence,
switching of agents was resetting all state to the new scenario.
We are experimenting with transitioning state to new authorized AI elements so we don't have to reset.

### What scientific or technological advancements did you achieve or attempt to achieve as a result of the work described in line 244? (Maximum 350 words)


We created a development and testing environment that incrementally applies changes to a production environment for the purpose of two AI agents,
an underwriter and an agent/broker,
interacting within numerous AI perspectives and base lending environments,
prime and sub-prime.
We advanced ML to allow a non-production environment to learn from and grow into a production environment.
We furthered our previous year's research and development into AI in the lending market by working on a virtual agent that interacts with our already developed virtual underwriter.
We moved AI and ML into the Credit Union market space to automate mortgage lending.
We have significantly advanced by experimental research the automation of mortgage lending through AI,
operating as both agent and underwriter.
