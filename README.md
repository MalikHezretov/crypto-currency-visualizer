Teck stack for the assignment: React, Redux, Redux-Saga, Websockets and styled-components

Architecture/Solution: 

In order to get real market data I've decided to use Websockets from encouraged 3rd party API.
I also used redux saga for listening the events using event channel and dispatch the success action. 
Redux has been used to make the data available accross the app. 
Unit testing is done using default testing library provided by react (react-testing-library)
Lastly I have used styled components for UI.

I was uanble to implement additional feature for viewing last 24c hour data due to time constraint.