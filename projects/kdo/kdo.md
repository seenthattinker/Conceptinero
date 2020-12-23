Kingsley Speed Dating Application T661
=======================================


web sockets for real time info
backend handles timing
creates new rooms
web sockets sends the person to the new room by pushing the timing information from the backend to the front sends
integrated with Twilio &reg;
sms messaging
Twilio failed.
switched to Daily &reg;.
Twilio is very open
you have to do a lot of the configurations yourself
playing around with different configurations,
changing the codec and other things,
optimizing for different things like devices, assume Apple and Android here
Daily does a lot of this configuration for you
You have to do some yourself,
and it's not as robust as Twilio
It was a lot easier to get things set up with Daily,
and also the quality was a lot better with Daily than it was with Twilio
Twilio was good for two person video calls because it does peer to peer video calls
Once you have a group call, say five or more people, the quality starts to dwindle
my application needs this group video because the speed dating events start with a launch, which includes group calls where everyone in the event is on the call, and it could be twenty or thirty people
still, Daily required a lot of custom coding to overcome its limitations,
for example switching rooms
the API only allows you to stream video calls
everything else is custom coding

room switching

the API has events
an event starts and stops a call
a call is on a channel
the backend starts and stops a channel
the speed dating event begins with everyone on one channel
this is the lobby for the event
to increase functionality I had to create the perception of a separate channel for the date callers
this was achieved not by creating new channels but rather by muting the call to all but the two people on a digital date
this was created to avoid lags on the calls
some users have better Internet than others
each date call is five minutes
due to lags
some of the dates were far less than five minutes
I spun the API to deliver the appearance of a private call while the two callers on the video date are still in the lobby channel with the original group
it is just that their call has been muted to all other participants in the speed dating session

each participant in the lobby is assigned a token to enter the lobby
then that token is used as the unique identifier to separate daters into pairs of calls for five minute sessions,
the speed date,
and then moved to anew date,
a new two person call muted to all the others

admin

can view info in real time
see all the matches
see who is speaking with who
management console where admin can info being inputted,
the matches,
the rooms changing,


backend

the backend creates the room
moves the participants around
the strategy for this was complex
the algorithm had to be reworked numerous times
for example
you have five rooms and five men and five women,
plus the lobby where they all start
the process required experimentation for handling unanticipated events,
like an extra person or persons joining the lobby room after it has been created
the algorithm had to be redone a number of times to accommodate this


chat

had to develop a chat service
chat widget at the bottom right of the screen
had to be built from scratch for this application
for the real time I used Firebase &copy;
the open source chat tools were either built for specific frameworks or they were linked in services run by another admin
built with React &reg; and reusable




start stop of project

viable project in two months
features added over time






































.. https://www.twilio.com/

.. https://firebase.google.com/

.. https://www.daily.co/

.. https://reactjs.org/
