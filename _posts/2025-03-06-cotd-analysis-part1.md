---
title: "Dissecting 4 years of COTD historical data"
date: 2025-03-06
categories:
  - TrackMania
tags:
  - COTD
  - Statistics
classes: wide
toc: true
toc_label: "Table of Contents"
---
A deep dive into the history of COTD and its numbers.

## Personal introduction

*This section will be the only personal rambling in this article (or series of, hopefully), but please bear with me. Feel free to [skip ahead](#cotd-history) if you just want to delve into the numbers and save yourself some minutes of reading.*

---

I don't really remember my first COTD, after playing hundreds of them. However, I do remember that I got lucky in my introduction to TrackMania. Having started just as Summer '23 was approaching its end, Nadeo gifted us Starter Access players with a week of free entry to cups at the beginning of October.

I got immediately hooked, and purchased my Club Access shortly thereafter. I recall having heaps of fun, regardless of the map and mapper, regardless how well I did in quali or in KO, regardless of what happened in my day. 15 minutes quick learn on a new map, followed by a quick friendly competition, is a perfect dopamine serving, a tasty digital appetizer before dinner. I was genuinely looking forward to opening the game while commuting back home. Nobody could take that joy and eagerness away from me. Nobody, except my future self.

Alright, maybe *that's a bit dramatic*. Still, as I started getting slightly better at the game, I began to care more about it. Not so much about the results I was getting, more so about the quality of the time I was spending on it. Once you play enough to realize what you like and what you don't, it becomes increasingly harder to avoid asking yourself the question: *Why am I playing this?*. Thus, as months passed, I found myself joining COTD less often.

With this newfound evening time in my hands, my research began. As I will show later on, COTD participation steadily declined throughout 2024. Numbers aside, any veteran player will likely tell you that the <span style="color:#AA6C39">*golden era*</span> of COTD is well behind us. Open a <a href="#" onclick="this.href='https://www.trackmania.io/#/totd/2022-' + (Math.floor(Math.random() * 12) + 1)" target="_blank">random TOTD Month in 2022</a>, and you will likely see names of really good mappers that you don't see nowadays. Even the knockout format itself seems to have grown stale for many players, as [this Reddit discussion](https://www.reddit.com/r/TrackMania/comments/1h6o1mj/cotd_player_count_and_overall_health_of_the_game/){:target="_blank"} demonstrates:

> The mode is over 4 years old by now so naturally there is going to be fatigue happening among players, both in terms of the maps that show up and the mode itself. When COTD was brand new I would effectively schedule my evening around being able to play it, now I only play if I happen to have time+feel like playing TM+map catching my interest (for better or worse reasoning). A lot of players around me went through a similar change in how they approached cotd and I don't think Nadeo has any way of getting this group to play daily again.

> <cite>u/ZeemuisTM</cite>
 
So, where exactly did this decline start? Can Nadeo really do anything about it? This first article aims to analyze raw numbers, and potentially discuss alternatives to the pure knockout format, in light of the interesting discussions that sparked after the recent [RedBull Faster](https://liquipedia.net/trackmania/Red_Bull_Faster){:target="_blank"} competition. In a future part 2 of this series, I'll focus specifically on the maps themselves.
## COTD history

The first COTD took place on 2nd Nov 2020, with reruns introduced on 10th Aug 2021. To promote the game, Nadeo also allowed free-to-play users to enter in the following COTDs (thanks to Kuba for helping me gather these dates!):

| Date(s)                  | Promotion        | Date(s)                  | Promotion                |  
|--------------------------|------------------|--------------------------|--------------------------|  
| 2022-07-08 to 2022-07-10 | Summer '22 launch | 2022-10-10               | NeoCupra                 |  
| 2022-10-24               | NeoCupra         | 2022-11-07               | NeoCupra                 |  
| 2022-11-11 to 2022-11-13 | Green Weekend    | 2023-01-23               | NeoCupra                 |  
| 2023-02-06               | NeoCupra         | 2023-02-20               | NeoCupra                 |  
| 2023-03-06               | NeoCupra         | 2023-03-20               | NeoCupra                 |  
| 2023-04-03               | NeoCupra         | 2023-06-19               | AC Mirage                |  
| 2023-09-04               | NeoCupra         | 2023-09-11 to 2023-09-12 | Tech Issues Compensation |  
| 2023-10-01 to 2023-10-08 | Fall '23 launch   | 2023-10-23               | Laserhawk                |  
| 2023-12-12               | Lacoste1212      | 2024-02-05               | Hungry Sharks            |

Another important date to remember is 15th May 2023, when the game was launched on consoles, which brought a wave of new players into TM. The releases of the three TMO cars (21st Nov 2023, 27th Feb 2024, 22nd May 2024) are also impactful, as well as the beginning of 2024 when the pricing model changed.

In addition to this, the community has shown a bigger pull to special events, for instance on 29th July 2024 we had [Pyramidori](https://www.trackmania.io/#/leaderboard/D6gnMSccMV_QHo4KG5LREWvYti2){:target="_blank"}, made by popular streamer **Wirtual** with scenery by **Oclavukixus**. Being the awaited sequel of Wirtual's previous COTD, [Midori](https://trackmania.io/#/leaderboard/tZROO7ZGFV5oSel3hyKrvZ60Xth){:target="_blank"}, more players were interested in playing COTD on that day, with a player count of ~4000 players, while other tracks in the same week show player counts of low ~2000s. **Almost halved**.

While this is certainly a special occurrence, it at least shows that the game mode still has a potential player base that just doesn't bother opening the game for the "standard" cups.

Alright, it's time for some graphs. The dataset I'm working on contains COTD information from its beginning **until end of 2024**. Keep in mind that some cups were broken by technical issues, so some player data is missing in these rare occurrences.

## Player participation

The unique player count sums to a grand total of **202'812 unique players**. For the sake of having consistent time frames, the following graphs will not include data from 2020, and will instead focus on the 4 years that go from 2021 to 2024. For reference, the number of players that started playing COTD in those last months of 2020 totals 7'730.

To start, let's look at the aggregate data for each year:

<figure class="half">
    <a href="/assets/images/COTDAnalysis/total_size_hist.png"><img src="/assets/images/COTDAnalysis/total_size_hist.png"></a>
    <a href="/assets/images/COTDAnalysis/new_players_hist.png"><img src="/assets/images/COTDAnalysis/new_players_hist.png"></a>
    <figcaption>Total yearly sum of COTD sizes and how many players had their first COTD in that year.</figcaption>
</figure>

While the total COTD size in 2022 has only a slight margin over 2024 (still a problematic equivalence, since the mode wasn't able to retain many of the players that came from consoles), **there's a staggering difference between the two years in terms of new player counts**. Part of this is due to not having as many free COTDs in '24 (more on this later); however, we can look better at the overall picture by plotting the day-to-day data. Since the graphs become hard to read with too many spikes, I've computed **averages in 7-days centered windows**. This also ensures all days of the week are considered together and reduces bias from weekly trends (people might have more free time to play on the weekends, for example).

{% include figure popup=true image_path="/assets/images/COTDAnalysis/main_cotd_size_graph.png" caption="7-days centered rolling average of **main COTD players**." %}
{% include figure popup=true image_path="/assets/images/COTDAnalysis/rerun_size_graph.png" caption="7-days centered rolling average of **rerun players**, summed together." %}
{% include figure popup=true image_path="/assets/images/COTDAnalysis/new_players_graph.png" caption="7-days centered rolling average of **new players**." %}

**Observing 2024 (the red line), there's a clear, steady decline starting from late spring**. Since then, the main COTD size has consistently stayed below 2'500 players — barring special occasions. A similar drop can be found in the new players graph and, while the magnitude of this element alone can't cover the gap of the overall player count, it's a worrying correlation. Interestingly, the **reruns seem to have consistent size**, which could be partly explained by an increase in popularity of TM in North America, a large player base that doesn't have easy access to the main COTD due to timezone differences. Still, it's not a big win, considering that the big push from consoles release doesn't seem to have lasted long.

I'll leave any subsequent deductions to the reader. I mean, you're the one not playing, so who better than you knows the answer?

## Where is everyone?

<figure style="width: 400px" class="align: center">
  <img src="/assets/images/COTDAnalysis/travolta_cotd.gif">
</figure>

Since free cups introduce many new players, let's start with that. **20'808 player entered for free in their first COTD**, however, only 31.87% of this category have also played a paid COTD. In other words, **about 2 out of 3 players that get introduced to COTD as free-to-play aren't convinced enough to purchase the subscription**. 

The following graph makes it very clear that most players stop playing COTD after just a few tries.

{% include figure popup=true image_path="/assets/images/COTDAnalysis/participation_cdf.png" caption="Proportion of players that participated in a given amount of cups, based on whether their first cup was a free one or not. Only 13.3% of players introduced to COTD through free ones end up playing more than 10 cups, compared to the 30.35% figure of the other group." %}

A particularly significant conclusion from this graph is that **one out of four players with paid access who enters COTD never returns**.

...What? <img src="/assets/images/emotes/WHAT-4x.gif" style="width: 40px">

Of course there are some outliers, like [🇪🇪 Sandder](https://www.trackmania.io/#/player/e4149e93-7666-42bf-a21a-e7a4dc2c4730/cotd){:target="_blank"}, who I guess is waiting for competition to step up in TM2020 after dominating his one and only COTD (he didn't know there was a risky finish until halfway through KO, by the way!), and [🇩🇪 exetic.](https://www.trackmania.io/#/player/36690fca-1ba4-4829-a06f-5342c0fb8cbe/cotd){:target="_blank"}, who also won the first ever Desert Car COTD. 
Beside these TMU players that stepped up for the occasion on alt car maps, the majority of players in this category of one-timers with paid access are lower-skilled players, with a **median percentile rank** of **top 85%**. Additionally, if we take the **timestamp of their personal best** on the leaderboard and subtract the time of COTD start, the resulting median is **just 11 minutes**! This essentially means rage-quitting COTD after qualification, and never touching the mode again. Here's the full density plot for these two metrics:

{% include figure popup=true image_path="/assets/images/COTDAnalysis/single_cotd_kdeplot.png" caption="Density plot of COTD ranks and time elapsed between PB timestamp and COTD start (in minutes), for players with paid access and a single COTD played. Players with a pb set 1h after COTD are grouped together." %}

As we can see, many players in the graph belong in the lowest 40% of divs and set their pb during the qualification period (**38% of players fit these parameters**). It makes sense to see most players in the upper section of this graph—after all, many can relate to struggling with their first COTD. As mentioned before, what's more worrying is the fact that players generally don't bother improving their time after qualification. While these conclusions are somewhat expected, **it's telling that many newcomers likely don't bother playing KO at all or don't care about TOTD anymore after being knocked out**.

Before I conclude this article with considerations about the KO format itself, let's look at paying players with >10 cups who didn't enter a single one during 2024. Among these **~26k players**, notable ones include [🇸🇰 Loso-](https://trackmania.io/#/player/87e4afbf-fb54-4d60-9ce1-b0698beab097/cotd){:target="_blank"} and [🇫🇷 Gwen_TM](https://trackmania.io/#/player/gwen/cotd){:target="_blank"}, as well as [🇨🇦 CarlJr.](https://trackmania.io/#/player/carljr/cotd){:target="_blank"} and [🏴󠁧󠁢󠁥󠁮󠁧󠁿 PacTM](https://trackmania.io/#/player/pac/cotd){:target="_blank"}, both returned with a win in 2025 after years of absence. This list of top players goes on and on and, honestly, I felt pretty sad seeing popular names like these not willing to participate in COTD anymore. 
Here's the last graph of this article, showing how these players are distributed based on their median frequency between COTD appearances. 

{% include figure popup=true image_path="/assets/images/COTDAnalysis/players_2024noshow_frequency.png" caption="Distribution of paying players with >10 COTDs played, but no participation in 2024. Players with a median frequency of 7 days or higher are grouped together." %}

Note how **more than half of these players**, at some point, **played daily or every other day**. This, to me, indicates that COTD has an appeal to it that makes people return frequently in the short term; however, after the initial hype, players don't find the mode interesting anymore.

Is it because of the maps? Is it because of the Knockout mode? Possibly both. I'd like to tackle the maps subject separately, because it's more complicated and possibly more controversial. Let's conclude this wall of text with a brief discussion on KO and its possible alternatives.

## KO is not OK

Knockout is a game mode that is arguably the simplest to understand: you finish in the last slot(s), and you're out. With a defined limit on the number of rounds, it’s the go-to format for streamers hosting their own COTD-style events. **But that same simplicity is also its biggest flaw**: it doesn't matter how you drive, as long as you're out of the KO zone. You could top each round, and yet lose at the last, decisive one from a single mistake. The same goes for a technical issue: your controller disconnects? Game freeze from toggling opponents? Lag? You can start preparing dinner now! But the biggest issue, in my opinion, is that **player time isn't evenly distributed**. 

If all players join their div, there are a total of 24 rounds with the current implementation:
* 1 NO KO
* 12 rounds with 4 eliminations
* 4 rounds with 2 eliminations
* 7 rounds with 1 elimination

It's evident how this format is very unbalanced, where half of the participants stop playing one-third of the way through the tournament. There might be technical reasons for choosing Knockout, like reducing server load, but since COTD requires players to reserve a specific time slot in their day, wouldn’t it be better to keep them engaged longer?

Now, I know some of you are trying to find a place to write *skill issue*. Here, knock yourself out:
<div class="container">
    <span><img src="/assets/images/emotes/Chatting-4x.gif" style="width: 40px"></span>
    <textarea id="inputText" rows="1" style="width: 11ch; resize: none;border: 1px solid black"></textarea>
    <span id="statusIcon" class="status">❌</span>
</div>
<script>
    const textarea = document.getElementById('inputText');
    const statusIcon = document.getElementById('statusIcon');

    textarea.addEventListener('input', () => {
        const text = textarea.value.trim().toLowerCase();
        if (text === 'skill issue') {
            statusIcon.textContent = '✅';
        } else {
            statusIcon.textContent = '❌';
        }
    });
</script>

If you're just interested in the competitive considerations around the format, there's a strong argument to be made against KO, and it's that **it encourages overly safe driving**. In many rounds, it doesn't matter how well you drive, just that you don't crash. While I've spoken to some players that like this risk-management aspect, it's undeniable that **TrackMania races are at their peak when several players simultaneously push their limits to reach first place**. If you have not yet seen this, take a look at the last rounds of Ascension 2023 (the format is *Cup mode*: after you reach a given amount of points, you need to end a round in first place to be declared the winner):

<iframe width="640" height="360" src="https://www.youtube-nocookie.com/embed/KxfAlWqR0ZQ?start=13082" frameborder="0" allowfullscreen></iframe>

Even factoring in how the nature of ZrT maps adds to the overall chaos, **this level of constant tension is generally hard to find in formats that end in a 1v1, or that don't reward top positions every round**. COTD finals can produce interesting battles every now and then, but I personally remember many anticlimactic ones, with fast players being knocked out early, or with second place making a mistake in the first half of the map, essentially gifting the winner a victory lap.

**Cup mode**, or its variants, like the *reverse* one, **has been the premier format for individual competitions in TM for years**, and I don't see why COTD should be any different (*it's even in the name..*). As with everything, there are pros and cons. If the advantages I've mentioned above aren't convincing enough for you, I've collected main arguments against Cup mode, next to simple, specific tweaks that, in my opinion, would dramatically increase COTD quality (and attendance!) if we were to switch to it:

- *Watching the rest of the field battling for 2nd place onwards is anti climactic* => as shown above, Ascension had a great system for it: **keep counting points even after a player has reached finalist**. Once you have the first winner, you also have a classification for all other players, and the tournament can end.
- *End time not known in advance* => it's just a matter of fine-tuning the point distribution, and Nadeo has enough data on COTD rounds to ensure the tournament stays within a certain number of rounds. Even considering the unlikely edge case where weaker, non-finalist players keep denying everyone over and over, the simple solution would be to **add an additional setting to limit the number of rounds available to reach finalist**. So, for instance, if no winner is decided after 20 rounds, all non-finalist players get knocked out, and a single, last round is driven among finalist players, ensuring a winner. With proper point distribution, this final round would still be played between several players, making it more interesting than the standard KO 1v1.
- *If one player is far above the rest, the point gaps become so large that the winner is already known halfway through* => the 2024 World Cup is a prime example of this, with CarlJr reaching finalist at 140 points while his opponents are stuck in the 100 range. Again, this is just a matter of **fine-tuning points distribution**: in the World Cup, the standard 10/6/4/3 split was used, while in Ascension, with 8 players competing, it was 10/8/6/5/4/3/2/1. **The more linear the points are distributed, the lesser the impact of this issue**. Though, in fairness, shouldn't players who are capable of topping every round be rewarded for their performance?

I'm aware that there are some additional considerations: to name one, from a content creation perspective, having to drive all the rounds means you don't get to commentate any, and the Twitch audience is stuck with players' POVs, instead of watching all cars battle each other. Interesting thought, but isn't it time we make COTD have more people playing than spectating on Twitch? I would gladly lose some speech bubble moments for that to happen.

## Conclusions

COTD has been struggling for quite some time now. Over the years, it has gone from an interesting novelty to a stale format, becoming less and less able to attract new players, or retain existing ones.
Lately, Nadeo has been making awesome changes and additions to other parts of the game, such as introducing Weekly Shorts and improving ranked, tweaking its map pool and MMR rewards. **It's time to also give COTD some love**, as I'm confident that it's just a few small changes away from regaining back a big chunk of its missing player base.

*Next up*: map selection is the other hot topic regarding to COTD, so I'm looking forward to do some analysis there. However, I don't want to rush it with approximate conclusions, so you'll have to wait a bit. In the meantime, I'm very interested to hear everyone's thoughts on all of this!

---
Powered by <a href="https://openplanet.dev/" target="_blank" style="color:#db006e"><i class="fa-solid fa-heart-pulse"></i> Open**planet**</a>