## Predicting Overfishing

Overfishing is one of the biggest and most neglected issues of our time. The oceans play a crucial role in maintainig a 
stable atmosphere and also provide food for billions of people on earth. Maintaining a healthy ecosystem is important everywhere,
but in the oceans, an unbalanced and collapsing ecosystem results in substantial effects on the levels of CO2 in our atmosphere
and thus has catastrophic effects, not just for economies that rely on fishing to sustain them, but also for fish populations and ultimately for climate change.

Predicting overfishing before it's too late is therefore a crucially important task. Currently, when populations are seen to decline,
bans are put on fishing that species or fishing becomes heavily regulated. This has a great economic impact on fisheries and at this point, populations need a lot of time and energy to recover. Predicting when a population is being fished to a point that will result in severe population decline would allow governments and fisheries to change tactics early on in the game.



###Threat Index
####The 'threat index' will be assessed using a 'vulnerability' metric:
This is determined by the total Catch per unit of Effort (CPUE) i.e. number of hooks, or number of days fished, divided by the population growth rate * the total population. I use Biomass rather than number of individuals, as average (or max?) size of the fish is a good indicator of population health.
    V = CPUE/(r*N)
####CPUE
This is calculated using data from the WCPFC, which shows catch and effort over time.
####Population size
This can be determined from the corresponding data in the above dataset. Downloaded from the NOOA site.
In [ ]:
