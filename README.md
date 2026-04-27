# FleetPairer
FleetPairer is an optimization software, allowing to generate pairing-lists for
sailboat racing in a league format.

While enabling *fairness* in sailing leagues, FleetPairer also allows to
optimize pairing-lists for efficiency.

<br>

## Contact
FleetPairer is currently in a testing phase. Together with some of our early adopters, we are testing FleetPairer in practice, and will strengthen our notion of *fairness* or improve *efficiency* of the generated pairing-lists if necessary. 

If you would like to use FleerPairer for your sailing-league, please contact us via E-Mail.

**E-Mail:** [fleetpairer@gmail.com](mailto:fleetpairer@gmail.com)

<br>

## FleetPairers's Mission
### Fairness
FleetPairers's main focus lies on making sailing leagues as *fair* as possible.
To do so, the usually used rules had to be strengthened significantly.
However, the new rules still satisfy the usual ones. This allows race-organizers to switch to new pairing-lists without going through the process of adapting their league's rules.

When speaking of ***fairness***, we usually think of two things (in order of priority):

1. Each team should directly compete against all other teams equally often
2. Each team should sail equally often on all boats

Usually, pairing-lists are developed manually. This is not only tedious but almost infeasible for the size of todays events. Thus, the above fairness rules are often *relaxed* s.t. some teams race against each other much more often than others. The second notion of fairness is often dropped entirely. This makes events inherently *unfair*. Furthermore, manual design of pairing-lists is prone to errors.

> **Note:**
> Depending on the number of boats, teams and flights in a league, there might not be a perfectly fair pairing-list. In general, FleetPairer finds an optimal solution (i.e. a solution that is as fair as possible).


### Efficiency
In league-sailing, there are usually many crew-changes between races. This is clearly necessary, not only if there are more teams competing than boats available, but also to achieve *fairness* as described above. However, those crew-changes can take up a large portion of race days, especially if the individual races are short.

Thus, FleetPairer uses advanced optimization strategies to keep the total time used for crew-changes down to a minimum.  
To do so, FleetPairer may also take the local conditions into account. This is especially useful if only a limited number of crew-changes can be executed concurrently.

Furthermore, FleetPairer prohibits pairing-lists in which a team sails on two different boats in consecutive races. This was observed to lead to major congestions (e.g. if the team finishing last has to change to the boat of the team finishing first).

<br>

## Frequent Users
The *Swiss Sailing League Association (SSLA)* uses FleetPairer for their events since the season 2025. They are in close contact with FleetPairer and provide valuable feedback to improve our software.

>The Swiss Sailing League organizes numerous regattas every year involving many teams, tight schedules, and complex logistics. Precise and efficient flight scheduling is crucial to ensuring that everything runs smoothly on the water.
>
>With FleetPairer, we have found a solution that meets all of our expectations. The platform enables the rapid, transparent, and fair creation of flight schedules, even when adjustments are needed at the last minute. We particularly appreciate the intuitive user interface and the flexibility to adapt to different event formats and participant numbers.
>
>Thanks to FleetPairer, we have significantly simplified our operational processes while improving the quality of our regatta organization. Planning is transparent and efficient, and it considerably reduces the administrative workload for our organizing team.
>
>>— Fabian Meier, President of the Swiss Sailing League Association

<div id="quote_ssla" style="margin:0px auto; width:70%">
    <div id="logo_ssla" style="float:left; margin:0; width:33%">
        <img src="/img/ssla_logo.jpg" alt="SSLA Logo" max-height=100% max-width=100%></img>
    </div>
    <div id="credits_ssla" style="float:left; margin:0; width:67%">
        test
    </div>
</div>

<br>

## The League-Sailing Format
In a sailing-league, a predetermined number of teams compete against each other in a (sometimes fixed) number of so-called flights. The teams race on a fleet of identical boats, provided by the league-organizers.  
In each flight, every team sails *exactly* once. If there are more teams than available boats, a flight may consist of multiple races.  
Each team recieves points corresponding to their ranking in the respective race. In the end, the team with the lowest sum of points wins the sailing-league.

> **Note:**
> It is crucial that only *completed flights* are counted for the final ranking, s.t. each team competed in the same number of races.

<br>

## License
Copyright © 2026 L. Dalbosco

Pairing-lists generated with this software may be used free of
charge *if and only if* FleetPairer is cited accordingly.
Include the text  
"Generated with FleetPairer by L.Dalbosco  
([fleetpairer.com](https://fleetpairer.com))"  
clearly visible on every page of your printed or digital pairing-lists.

FleetPairer is currently closed-source. This might change in the future. If you are interested in contributing to the project, or adapting the source-code to your needs, feel free to reach out via E-Mail.