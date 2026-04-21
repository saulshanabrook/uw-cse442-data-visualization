I am a part of a housing co-operative in rural MA and this year I was part of the group trying to assess what the appropriate level
of rent increase was to cover our long term financial projections. Some increase is usually necessary due to inflation and rising costs
for items like insurance, taxes, etc. However, this year the larger increase came from trying to re-calibrate our understanding of how
much to set aside for long term maintenance, otherwise known as "capital improvements". We put together a schedule covering all items that
may need to be replaced in the future and so could project out based on our current budget, what our picture might be in different scenarios
over the next decades. We used visualizations of these scenarios to help us understand the implications and also to communicate and justify
our decision to the rest of the residents who would be shouldering this increased cost.

The question I wanted to answer is "What is the appropriate level of annual rent increase to sustainably cover our long term financial needs?"
The two visualizations I created both show a line chart of "% funded" over time. Percent funded is the industry standard measure for
understanding the health of a replacement reserve fund, it is calculated by taking a sum of all capital improvements we are budgeting for,
weighted by their remaining lifetime, and dividing that by the amount we have in our replacement reserve fund. Reaching 100% means
that if all items needed to be replaced currently with costs proportional to their remaining lifetime, we would have enough money in the fund to cover it.
Industry research shows a target of 30% is a good minimum to aim for.

On each line chart, there are one lines each for 2%, 3%, 4%, and 5% annual rent increases, differentiated by a color gradient. This is so you
can easily visually compare the trajectories under the different scenarios. I choose to use hue to differentiate them to show how the
rent increase levels are ordered relative to each other.

The first visualization has a Y axis that goes from -100% to 100% and shows a minimum recommended bar at 30%, to help understand visually when it dips below that amount.
For later years, it cuts off the data when it exceeds 100%. For the second visualization, the Y axis goes from the minimum to the maximum in the data,
there is no minimum bar. By scaling the data like this, it becomes harder to visually compare the different scenarios in the range of 0-30% funded,
which makes the 3% increase look possibly sufficient by also emphasizing the long run outcome over the dips in the middle. It also makes the 4-5% increase
seem overkill based on the end result, even though the 3% increase has a much more volatile trajectory that dips below the recommended minimum.

It maybe does not fall into deceptive, but definitely each visualization I think  may influence the viewer's perception of safety differently,
and I perceive the first one as more honest and informative for the decision at hand.

*I used an LLM to derive the Vega Lite JSON based on this description and the data. I then tweaked it slightly to adjust the styles manually.*

Data sources: https://github.com/saulshanabrook/uw-cse442-data-visualization/tree/main/assignment-2/data
