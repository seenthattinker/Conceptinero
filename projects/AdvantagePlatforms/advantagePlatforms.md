Advantage Platforms
==========================

Advantage Platforms Ltd. creates Artificial Intelligence applications built upon machine learning.

### Virtual agent/underwriter

The uncertainty was in the way forward for an Artificial Intelligence (AI) agent that could represent both the *prime* and *sub-prime* markets in the mortgage world.
The product is a virtual agent.
This builds upon machine learning and deal analysis,
also conducted this year.
The underwriter takes the outcomes and analyzes them in an effort to force an action a human might take.
We analyze the data to see if there is a match against our scenarios.
Our uncertainty arose when we were asked to employ AI agents in the Credit Union industry in Ontario.
They operate under different rules than banks,
and have far more latitude in what they do with a mortgage.

The first layer of the mortgage market separates people into different groups based on their primary characteristics.
These groups are basically prime and variations of below prime.
This is the first level of classification in the traditional banking world where mortgages are concerned.
However,
the Credit Unions operate differently.
This has required a lot of experimentation and investigation to determine what shared infrastructure can exist between the two underwriter AI systems,
the one for traditional banking and the one for Credit Unions,
given that the first layer of classification
&mdash;
prime or sub-prime
&mdash;
is inconsistent.
There are several options or a virtual agent to make a deal work.
It can restructure the deal,
override decisions,
decline deals,
change products within a suite,
or change the lender to reset variables.
We are trying to mimic something a person would do.

We are also working on role perspective in the AI.
At present,
we are writing the application as if it were the lender,
but it can be written to serve other perspectives as well,
like a mortgage broker.

The technology stack is Microsoft Azure,
C sharp.
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
switching of agents was resetting all state to the new scenario,
flushing the cache.
