# covidInfectionPredictor
Inspiration

It's almost been a year since the covid-19 started to affect people's life. It is necessary to finish the vaccine distribution and get it completed ASAP. However, it takes time to finish the whole vaccination, which means we need to figure out which state in the US needs the vaccine most.

What it does

For the application we design, the user can input the state they want to check, which will show them the infection rate for the next day. This can help them decide if the vaccination process is urgent for the work of tomorrow.
How we built it

We have got the data tracking for all US states by accessing the Covid Act Now API, where it provides the daily new cases, state population etc information. After we have cleaned the data and make sure the features we want, we start to choose models to predict the new cases and infection rate for the next day, next 7 days and next 30 days. We ended up with get the better result of infection rate for the next day. Finally we added a user input function to let the user to decide which state they would like to check.
