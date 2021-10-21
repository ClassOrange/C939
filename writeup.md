## Baseball Physiology Trends & Batting Averages
#### Project Links
- [Version sent to people](https://public.tableau.com/app/profile/cindy.wyant/viz/BaseballWyant/BattingAverages)
- [Modified version](https://public.tableau.com/app/profile/cindy.wyant/viz/BaseballWyant2/BaseballPhysiologyTrendsBattingAverages?publish=yes)

#### Summary
Essentially I wanted to look at the baseball data (honestly I started with flight data but couldn't save it as Tableau Public wouldn't let me
given the larger data file) to see if there were trends regarding batting averages and physical characteristics. Any sort of causation would
be totally speculative, but there is definitely correlation with a few different things. Weight, height, and handedness all have some sort of
connection to batting averages. I'd started out thinking left-handed players would have higher averages, which turned out to be correct
(ambidextrous players are also extremely closely tied to fully left-handed players in this regard). I'm unsure if that's something I heard as
a kid, or if it makes sense to me because pitchers' styles are more geared toward right-handed batters, or just because I find left-handedness
interesting, or what; I really didn't have a good reason to think that. Additionally, batting averages trend downward as height and weight
(independently of one another) increase, but do blip upward right as weight tops out.

#### Design
The initial Gantt chart made the most sense to me as it pretty starkly shows the distribution/concentrations of anbidextrous and left-handed
players' batting averages as compared to right-handed players. It's extremely simple, but the color chunks are very obvious. Splitting it up
into the 3 different handedness groups gave a more solid understanding of the distributions; the combined chart shows a clear *idea*, but the
separated version shows clearer *information*. The line chart for height shows the dramatic downward slope for batting averages across all 3
handedness categories; the home runs hover information *is* superfluous, but it's fun information and it's not in the way so I wanted to
include that. The bars for weight bins made sense to me as they not only show the trajectory of averages compared to weight, but they also
emphasize the differences in volume (that there are far more right-handed players). The height vs weight plot didn't really wind up showing
information how I'd intended, but I am extremely intrigued by the size discrepancy it shows with regard to ambidextrous players.

The final slide is cluttered, for sure, but I felt it was justified as all those plots have their own slides. If I was presenting that as a
summary just on its own, I think that would be a pretty bad choice, but since the base is there it made sense to kind of reiterate and
summarize the whole thing on one slide. That choice was also somewhat influenced by feedback I received; my story ended very abruptly and
without any sort of wrap-up so I did already want to add another slide. A friend gave me the same information ('it just kind of stops') but
she couldn't really picture what she'd want to see for the ending; summaries make sense to me in that case, just by default.

With regard to color, I did have a tough time with that one. Choosing different palettes in Tableau is all well and good, but with the Public
version, I couldn't assign specific colors as it auto-assigns based on the palette. As a result, many of the palette choices wound up
assigning two very similar colors to two of the attributes (like the three colors would be medium blue, light blue, and red). This really cut
down on the visual impact as the concentrations were far less clear. I don't think my final colors are what I would choose given the ability,
but after assigning many palettes and checking the results, it was clear this one made the heaviest visual impact.

#### Feedback
I don't really know anyone in data, so the feedback I received seemed to initially be very excited about Tableau as a whole. Exactly what I
got from two people at first was 'omg this is so cool.' One person wanted more information, such as more demographic data about the various
players. I fully agreed with her but finding other datasets to incorporate wasn't really within the scope of the project and would have
added a lot of time. More feedback I got that I'd already mentioned was the final slide. It wasn't in the initial draft and the story truly
just ended seemingly at random. The final slide allowed me to pull everything together and put a more solid point on the whole thing.

Apart from that, people just seemed excited and impressed (again, it likely had to do with first-time exposure to a Tableau story). They
understood each slide, they understood and loved the tooltips, the colors worked well for them, etc. I'm sure there's plenty to improve
upon but these people all know how I think and speak, so the whole thing was very clear to them.

#### Resources
[Coloring tooltip text based on handedness](https://sarahlovesdata.co.uk/2018/01/11/how-to-dynamically-colour-tooltip-text-in-tableau/)
[Creating bins](https://data-flair.training/blogs/tableau-bins/#:~:text=Follow%20the%20steps%20given%20below%20to%20create%20bins,Data%20pane%20in%20the%20list%20of%20fields.%20)
