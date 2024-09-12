# Design Crit Feedback

8/21

_Curent view_

- could add options on the screen to modify integrated devices (nest thermostat, wifi washer/dryer etc) (obviously requires non-trivial eng work, but something to think about for future)
- I like the "stock ticker" representation best, with the color background to make a nice big indicator of their current status. The "cleaner" white background does work as well if thats the bigger concern
  _Bill View_
- bill details screen - dont really like the large whitespace gap between the month text and the amount paid
- I really like the "current rate" indicator, might be good to give it like a glowing or breathing animation to make it feel more live

9/4

_Next month estimate_

I like the idea of the "sparkly" look, given the rise of using these sparkle icons to indicate either AI or some smart component, I think it'll communicate pretty well that we're estimating, but its also likely to be accurate because of the ~magic~ we're doing on the backend

_Current rate bar_

(mostly in reference to the discussion with Jess) I actually like the rate being at the top and visible, but mostly because we can use it as a CTA to get brokered with Arbor. We could give it a color to indicate "Your not on the best rate, fix that now!", or get a good feeling when they look at it and it says "Your on the best rate!". Kind of pushing toward the goal of feeling good about the decisions being made to improve their overall energy usage.

_Getting away from bar graphs_

Agreed that it would make us pretty "samey" to use bar graphs to communicate all of our data. One possible solution is to spend some time figuring out a hero stat, basically something that communicates on a high level how they're doing with energy usage. Even if we have like an "Arbor Energy Rating" with a color coding system. We can use some of the progressive disclosure that you've been incorporating to explain how we arrive to that number, but it would allow us to get opinionated (ie what we include in it is what we think is important) and would be easy for the customer to follow (ie is it going up or down, or red/yellow/green)

_Social aspect/gamification_

One company that we might want to look at for inspiration is this standup that I interviewed for once https://www.claim.co/ . At a low level, they've basically turned coupons into trading cards, which could be an interesting idea for rewards. Coming from my geeky corner of the world, you could do something like, if you win this month you get a pack of coupons, but they're randomized with some really good ones, and some "meh" ones (think Pokemon or Magic the Gathering). This is a pretty tried and true technique for game companies to keep players coming back.

9/11

_Spend Monthly View_

Love the idea of establishing a comfort zone, although I don't know what situation would make a user want to set a minimum, ie if they spent nothing for their energy I'd imagine they'd be happy about that. Perhaps comfort zone could just be a max spend setting. Another option might be to see if we can get the minimum that a house of their size uses typically (maybe even broken down by month) and automatically just set their minimum to that.

_Home view_

One feature idea, would be a good place to add a CTA for users that are getting ready to move. When they click it we could have a flow that would kick off that process so we keep that customer after they do the move.

For house hardware info, this could be a good opportunity to establish some partnerships with other climate tech companies that make hardware, and suggest things like heat pumps etc from those partners. Could be another revenue stream, and showing that Arbor has partners may also be helpful for user trust, as it makes us look more established IMO.

_Insights_

May be a good opportunity for using AI, we could pre-train a model to take in statement data and produce some of these.

_Not "slapping customers' wrists"_

Perhaps we could have some process detecting abnormally large spikes in usage, and instead of just showing everything in red, we could show a modal that asks the user what changed, and give some examples like "I bought an EV". We might then be able to take the average usage of whatever new hardware is in the home and take that into account on all of the usage and spend views


