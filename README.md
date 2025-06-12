# FleetPairer
FleetPairer is an optimization library, allowing to generate pairing-lists for
sailboat racing in a league format.

While enabling *fairness* in sailing leagues, FleetPairer also allows to
optimize pairing lists for efficiency.



## FleetPairers's Mission
### Fairness
FleetPairers's main focus lies on making sailing leagues as fair as possible.
To do so, the usually used rules had to be strengthened significantly.
However, the new and fair rules still satisfy the usually used rules. This
allows race-organizers to switch to new pairing-lists without going through the
process of adapting their league's rules.

When speaking of ***fairness***, we usually think of two things:  
* Each team should directly compete against all other teams equally often
* Each team should sail equally often on all boats

Usually, pairing lists are developed manually. This is not only tedious but almost infeasible for realistically sized events. Thus, the above fairness rules are often *relaxed* s.t. some teams race against each other much more often than others, and the teams sail don't sail equally often on all boats. This makes events inherently *unfair*.

> [!NOTE]
> Depending on the number of boats, teams and flights in a league, there might not be a perfectly fair pairing-list. Thus, the strict rules developed by FleetPairer permit a deviation of one if necessary.


### Efficiency
In league-sailing, there are usually many crew-cahnges between races. This is clearly necessary, not only if there are more teams competing than boats avalable, but also necessary to achieve *fairness* as described above. However, those crew-changes can take up a large portion of race days, especially if the individual races are short.

Thus, FleetPairer uses advanced optimization strategies to keep the total time used for crew-changes down to a minimum.  
To do so, FleetPairer may also take the local conditions into account. This is especially usefull if only a limited number of crew-changes can be executed concurrently.



## The League-Sailing Format
In a sailing-league, a predetermined number of teams compete against other in a (sometimes fixed) number of so-called flights. The teams race on a fleet of identical boats, provided by the lague-organizers.  
In each flight, every team sails *exactly* once. If there are more teams than avalable boats, a flight may consist of multiple races.  
Each team recieves points corresponding to their ranking in the respective race. In the end, the team with the lowest sum of points wins the sailing-league.

> [!NOTE]
> It is important that only *completed flights* are counted for the final ranking, s.t. each team competed in the same number of races.



## Contact
FleetPairer is currently still being developed. While it already generates (provably) fair and efficient pairing-lists, it needs a lot of computation-power to do so.  
We are currently working hard on making FleetPairer more efficient. However, this is not easy while still preserving fairness of the generated pairing-lists.  

If you would like to use FleerPairer for your sailing-league, please contact us via E-Mail.

**E-Mail:** 



## License
Copyright © 2025 L. Dalbosco

Pairing-Lists generated with this software may be used free of
charge if and only if FleetPairer is cited accordingly.
Include the text  
"Generated with FleetPairer by L.Dalbosco  
(https://github.com/LDalbosco/FairSail.git)"  
clearly visible on every page of your printed or digital pairing-lists.

FleetPairer's source-code is currently closed-source. This might change in the future. If you are interested in contributing to the project, or adapting the source-code to your needs, feel free to reach out via E-Mail.