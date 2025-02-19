---
title: "Dissecting 4 years of COTD historical data"
date: 2025-02-15
categories:
  - TrackMania
tags:
  - COTD
  - Statistics
classes: wide
---
## Personal introduction

*This section will be the only personal rambling in this article (or series of, hopefully), but please bear with me. Feel free to [skip ahead](#cotd-history) if you just want to delve into the numbers, though.*

---

I don't really remember my first COTD, after playing hundreds of them. However, I do remember that I got lucky in my introduction to TrackMania. Having started just as Summer '23 was approaching its end, Nadeo gifted us Starter Access scrubs with a week of free entry to cups at the beginning of October.

I got immediately hooked, and purchased my Club Access shortly thereafter. I recall having heaps of fun, regardless of the map and mapper, regardless how well I did in quali or in KO, regardless of what happened in my day. 15 minutes quick learn on a new map, followed by a quick friendly competition, is a perfect dopamine serving, a tasty digital appetizer before dinner. I was genuinely looking forward to opening the game while commuting back home. Nobody could take that joy and eagerness away from me. Nobody, except my future self.

Ok, ok. It's not *that* dramatic. Still, as I started getting slightly better at the game, I started caring more about it. Not so much about the results I was getting, moreso about the quality of the time I was spending on it. Once you play enough to realize what you like and what you don't, it becomes increasingly harder to avoid asking yourself the question: *Why am I playing this?*. 

> Stop making such a scene. If you don't like a map, there's always another one tomorrow.

> <cite>You</cite>

You're right!. Apparently, having a decent Stadium map consisting of any mix of tech road / dirt / grass / plastic is an increasingly more restricting requirement to be met, so I started simply closing the game when something outside this realm popped up. That's fine.

With this newfound evening time in my hands, my research begun. As I will show later on, COTD numbers have been in decline throughout all of 2024. Numbers aside, if you ask any of the veteran players, they'll likely tell you that the <span style="color:#AA6C39">*golden era*</span> of COTD is well past us. Open a <a href="#" onclick="this.href='https://www.trackmania.io/#/totd/2022-' + (Math.floor(Math.random() * 12) + 1)" target="_blank">random TOTD Month in 2022</a>, and you will likely see names of really good mappers that you don't see nowadays. Maps aside, the knockout format itself seems to have grown stale for many players, as [this Reddit discussion](https://www.reddit.com/r/TrackMania/comments/1h6o1mj/cotd_player_count_and_overall_health_of_the_game/) shows:

> The mode is over 4 years old by now so naturally there is going to be fatigue happening among players, both in terms of the maps that show up and the mode itself. When COTD was brand new I would effectively schedule my evening around being able to play it, now I only play if I happen to have time+feel like playing TM+map catching my interest (for better or worse reasoning). A lot of players around me went through a similar change in how they approached cotd and I don't think Nadeo has any way of getting this group to play daily again.

> <cite>u/ZeemuisTM</cite>
 
So, where exactly did this decline start? Can Nadeo really do anything about it? This first article aims to analyze raw numbers, and potentially discuss alternatives to the pure knockout format in light of the success of the recent [RedBull Faster](https://liquipedia.net/trackmania/Red_Bull_Faster) competition. In a future part 2 of this series, I'll try to delve more into TOTD maps themselves.
## COTD History

First COTD was on 2nd Nov 2020, and reruns got introduced on 10th Aug 2021. To promote the game, Nadeo also allowed free to play users to enter in the following COTDs:

Here’s the cleaned-up version of the table without duplicates and still maintaining the two-column format:  

| Date(s)                  | Promotion        | Date(s)                  | Promotion                |  
|--------------------------|------------------|--------------------------|--------------------------|  
| 2022-07-08 to 2022-07-11 | Summer 22 launch | 2022-10-10               | NeoCupra                 |  
| 2022-10-24               | NeoCupra         | 2022-11-07               | NeoCupra                 |  
| 2022-11-11 to 2022-11-13 | Green Weekend    | 2023-01-23               | NeoCupra                 |  
| 2023-02-06               | NeoCupra         | 2023-02-20               | NeoCupra                 |  
| 2023-03-06               | NeoCupra         | 2023-03-20               | NeoCupra                 |  
| 2023-04-03               | NeoCupra         | 2023-06-19               | AC Mirage                |  
| 2023-09-04               | NeoCupra         | 2023-09-11 to 2023-09-12 | Tech Issues Compensation |  
| 2023-10-01 to 2023-10-08 | Fall 23 launch   | 2023-10-23               | Laserhawk                |  
| 2023-12-12               | Lacoste1212      | 2024-02-05               | Hungry Sharks            |

Now the table is compact and free of duplicate promotions while preserving all relevant dates. Let me know if you'd like any further adjustments! 🚀
Another important date to remember is 15th May 2023, when the game was launched on consoles, since this brought a considerable amount of new players into the game mode. The releases of the three TMO cars (21st Nov 2023, 27th Feb 2024, 22nd May 2024) are also significant, as well as the beginning of 2024 when the pricing model changed. You'll find spikes (or dips) in the upcoming graphs around the dates mentioned above.

In addition to this, the community has shown a bigger pull to special events, for instance on 29th July 2024 we had [Pyramidori](https://www.trackmania.io/#/leaderboard/D6gnMSccMV_QHo4KG5LREWvYti2), made by popular streamer **Wirtual** with scenery by **Oclavukixus**. Being the awaited sequel of Wirtual's previous COTD, [Midori](https://trackmania.io/#/leaderboard/tZROO7ZGFV5oSel3hyKrvZ60Xth), more players were interested in playing COTD on that day, with a player count of ~4000 players, while other tracks in the same week show player counts of low ~2000s. **Almost halved**.

While this is surely a special occurrence, it at least shows that the game mode still has a potential player base that just doesn't bother opening the game for the "standard" cups.

Alright, time for some graphs. The dataset I'm working on contains COTD information from its beginning **until end of 2024**. Keep in mind that some cups were broken by technical issues, so some player data is missing. However, being a somewhat rare occurrence, the dataset is big enough to show meaningful information over this game mode.

## Player Participation

The unique player count sums to a grand total of **202812 unique players**. For the sake of having consistent time frames, the following graphs will not include data from 2020, and will instead focus on the 4 years that go from 2021 to 2024. Just as a reference, the number of players that started playing COTD in those last months of 2020 sums up to 7730.

First, let's look at the aggregate data for each year:

<figure class="half">
    <a href="/assets/images/COTDAnalysis/total_size_hist.png"><img src="/assets/images/COTDAnalysis/total_size_hist.png"></a>
    <a href="/assets/images/COTDAnalysis/new_players_hist.png"><img src="/assets/images/COTDAnalysis/new_players_hist.png"></a>
    <figcaption>Total yearly sum of COTD sizes and how many players had their first COTD in that year.</figcaption>
</figure>

While the total COTD size in 2022 has only a slightly margin over 2024 (though that's still a problematic equivalence, since the mode wasn't able to retain the players that came from console), there's a staggering difference between the two years in terms of new players. Part of this is due to not having as many free COTDs in '24 (more on this later), however we can look better at the overall picture by plotting the day to day data. Since the graphs becomes hard to read with too many spikes, I've computed averages in 7-days centered windows.

{% include figure popup=true image_path="/assets/images/COTDAnalysis/main_cotd_size_graph.png" caption="7-days centered rolling average of **main COTD players**" %}
{% include figure popup=true image_path="/assets/images/COTDAnalysis/rerun_size_graph.png" caption="7-days centered rolling average of **rerun players**, including reruns" %}
{% include figure popup=true image_path="/assets/images/COTDAnalysis/new_players_graph.png" caption="7-days centered rolling average of **new players**" %}

Observing the red line, we can see a **steady decline starting from late Spring**, and the main COTD size consistently stayed below 2500 players ever since, barring special occasions. Similar drop can be found in the new players graph and, while the magnitude of this statistics alone can't cover the gap of the overall player count, it's a worrying correlation. Interestingly, the **reruns seem to have consistent size** (though, there are certain types of maps that players like less, but I will talk about this in the next article), which could be partly explained by an increase in popularity of TM in North America, a big player base that doesn't have easy access to the main COTD due to timezone differences. Still, not a big win, considering that the big push from console release doesn't seem to have lasted long.

I'll leave any further deduction to the reader. I mean, you're the one not playing, so who better than yourself knows the answer?

## Where is everyone?

<img src="/assets/images/COTDAnalysis/travolta.gif">