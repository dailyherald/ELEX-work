Working with ELEX and figuring out AP elections
===============

I'm just getting started learning how to work with APIs and AP election data, and just in time comes [ELEX](https://elex.readthedocs.org/en/latest/index.html) from the New York Times' Jeremy Bowers and NPR's David Eads. Since I'm working with Python/Pandas, I'm going to learn all this through that lens.

The Jupyter notebook included here will show my progress as I ...

X Bring the data into Panda dataframes
		Finding the solution turned out to be very simple, once I got past my Jquery classes/Python classes mental block. Found the [simple answer here](https://stackoverflow.com/questions/34065361/python-class-attributes-to-pandas-dataframe).
- Join race results with races
		Joining isn't a problem, but I don't want/need all the information in the race rows so I'll create a new dataframe with only the info I want.
- Create a dataframe with total returns and a small number of counties within a state (we report on six in Illinois)
		I want one row per candidate, with returns and precinct info for total and a few counties, instead of multiple rows per candidate.
- Write the JSON for use in a jquery/javascript-powered web app that's also mobile-ready.
		Writing the JSON is simple. The web app ...

