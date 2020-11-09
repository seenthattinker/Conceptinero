Apple Pay T 1661 Critical Notes
=======================================

IMPORTANT: Use existing materials and documents generated during the course of your development work to extract the pertinent information to complete these questions.


## 242 – What technological obstacles did you have to overcome? 350 words max – 50 lines of 78 characters

The state of technology at the beginning of the project had several shortcomings and/or limitations,
as well as technological problems and unknown elements,
as described below:

Typically we are faced with using a tried and true e-commerce model for purchasing products,
but we quickly realized that this was not scalable,
and inadequate for the number of unique edge cases our platform required.
We hypothesized we could potentially develop an event and schedule-based hybrid application model to accomplish this.
We commenced work to overcome obstacles related to the workflow customization process,
within the typical checkout cart process.
We analysed the process to attempt to develop an approach,
such as event-based modules,
which would allow adjustment of the order status and data within the cart,
and allow these events to be created scheduled,
and repeated.

It was uncertain how we would integrate with many reporting,
device,
and system meta data processes and tools.
We were uncertain how to develop a middleware layer to achieve this,
while maintaining control and security of data,
as well as overcoming transaction performance issues.


>The distinct weakness that I see in the submission is the validity of the technical uncertainty as having benefit for the greater population,
ergo the taxpayer,
per the SR&ED documentation and law on the government website.
The technical uncertainty existed for the company,
but what is left in the cold is the certainty that the company achieve something that is of benefit to the Canadian taxpayer,
either by addressing a lingering technological work hole that they filled that is a benefit to other coders,
or other participants in the technological community,
even open source.



## 244 – What work did you perform in the tax year to overcome those technological obstacles?   700 words max - 100 lines of 78 characters

In the 2019 fiscal period,
we continued work by attempting to overcome our e-commerce model limitations by integrating a better payment model.
Payment transaction abstraction must occur,
as there are currently too many payment transactions among too many nodes to be secure using known technologies.
Our hypothesis is that we could allow this payment process to be simpler with less steps,
where we could potentially integrate a Wallet technology within our system as a payment clearance layer.
We think it could be highly secure and only available to trusted parties.
We completed tests and developed an experimental integration path extending from Bambora API attempt in an attempt to overcome these limitations and advance our toolset.


Through August 2018,
and March to July 2019,
the development work was partially done by our sub-contractor,
Cappers Applications,
where we all attempted to differentiate our approach from the typical shopping cart and payment integration processes,
which requires product item data deletion,
as well as the integration of a tokenized payment process into the e-commerce model.
We developed and extended a process to process credit payments only.
We hypothesized we could integrate debit and EFT capabilities in 2020.


Bambora API integration
Moneris didn’t work with our application model,
so we realized we needed to change our API in order to better integrate payment aggregation through 3rd party sources.
We attempted to extend and integrate a third-party aggregation tool,

that would facilitate payments between the merchant and consumers via different payment methods such as bank transfers and credit or debit cards.
After testing,
we realized that while the payment aggregation models are suited to small and medium businesses with low transaction volumes,
the cost of operating under the aegis of a merchant aggregator can become a constraint as we start processing more transactions.
We hypothesized that the aggregator model could potentially work perfectly if we process only a handful of transactions.
We thought that our sub-merchants typically only have to pay when they process online payments,
rather than shell out a monthly fee,
as we did not expect.
Through further testing we realized that there was a constraint related to high transaction volumes vs technology cost-efficiency.
So we needed to customize our payment integration layer to overcome these obstacles.
We attempted to develop and integrate a tokenization process which allows us to securely store customer credit card information in our system.
Our process has events for submitting credit card information straight to payment processor for validation.
If validation is successful,
next the payment processor returns a token that along with other parameters is used to checkout customer later with the given payment method.
This token can be used only by our system.
Therefore,
it doesn't make sense to steel it from us.


Event Type Development
After we designed the a-typical event driven cart process in 2018,
we turned focus in 2019 on how the model would be impacted by Teacher/Parent/Admin edge cases,
and how we would predict testing the application and meta data between entities.
During this development we needed to develop and extend Gitlab and Job runner tools to automatically test and check functionality.
The tools were developed around control of the code Check-in process.
We began developing Gitlab integration tools to run automated tests.
Scenarios were run each time we made these adjustments so that we could ensure and guarantee the code was stable.
Unique edge cases were developed and mapped out and set into a module in the application which would be run after code commits.
We were able to reduce test time to less than 5 minutes,
from more than 25 minutes.


We attempted to introduce new event types,
such as one-time events,
recurring events,
where we needed to link the event to the payment transactions.
We experienced difficulty in linking a one time pay event to a recurring event.

None of the known technologies worked within our case,
so we needed experimentally develop different workflows and automation procedures to create those events and respond to them.
We ended up introducing new modification events,
such as Edit,
Cancel,
and Rollback.


We next improved event logging,
stored in an open source tool called Grey Log.
We realized that Grey log required access to both hardware and software installations and settings,
and no API existed.
We needed to experimentally determine how our web application could communicate with Grey Log.
We devised a middleware layer to push events from the web app to Grey Log.
We also needed to introduce Reporting and Transactions Details exposure using a PostgreSQL data source connected to redash.
org – an open source tool.
But this was not easy approach to integrate.
We encountered some integration limits to resolve.
We experimentally determined how to develop and integrate both hardware and software extensions around native code.
We overcome Security limitations by allowing limited access to our Web application and Redash data.
Work would continue in 2020 as we hypothesized,
we could experimentally integrate debit and EFT capabilities to our model.


246 – What technological advancements were you trying to achieve? 	350 words max - 50 lines of 78 characters

The technological objective of the project is development of a Data Brokerage Layer for School E-Commerce Systems.
We realized this layer became necessary in dealing with the voluminous amounts of information on abstract school networks.
This layer works as an intermediary that provides data and service integration between school systems,
a payment gateway,
and any school board systems.
We realized that student and payment data could be processed much more efficiently if there is a layer that can work as data broker and can processing of events and purchases ad-hoc by various user types.
We were also able to develop support for better data transaction services,
as we were able to accomplish more sophisticated,
time-delayed event updates and scheduling related to future-compensating transactions.


In this project,
we were trying to achieve development of an architectural framework which focuses on the exchange of data to facilitate the financing and payment aspects of school’s cash transactions,
related to product and scheduled event purchases.
The work done advanced the existing state of knowledge in the field of Information Technology,
specifically in the E-Commerce Pattern methodologies.


This development represents a technological advancement in the E-Commerce workflows,
as existing technology and knowledge base level at the onset of this project was limited,
as we realized that the typical e-commerce order workflow would not work for our model.
Usually e-commerce store approaches are comprised of a combination of design patterns,
such as: MVC design pattern,
factory pattern (for maintaining orders and bill generation),
and the observer pattern for updating inventories and product data.
However,
alone these would not be satisfactory in context of school’s business,
purchase events,
and application logic: purchase processes would be more complex.
Project or Campaign management API’s existed,
but they were not suitable or reliable to integrate to meet our edge cases.
There is a low certainty between integrating a scheduled,
repeatable events-driven structure into any e-commerce model,
especially whether this would be scalable.
Further,
there is a lack of system security,
reliability,
standards and communication protocols within the school environment.
It was difficult to integrate the Internet and E-Commerce software with some existing applications and databases.
Uncertainties related to the above required the necessary experimentation to determine an advanced process.


The work done resulted in development of an architectural framework which focuses on the exchange of data to facilitate the financing and payment aspects of school’s cash transactions.
Our approach allows schools and companies to link their internal and external APIs more efficiently and effectively,
and manipulate data safely,
efficiently,
and more secure.
