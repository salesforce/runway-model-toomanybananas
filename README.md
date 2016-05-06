# Too Many Bananas model for Runway

Too Many Bananas is a simple concurrency problem:

1. You run out of bananas, so you go to the store.
2. Your roommate sees that you're out of bananas, so they go to the store.
3. You both get back from the store. Now you have too many bananas.

Too many bananas is a cause for alarm, since bananas go bad over time, and you
wouldn't want to waste any. The requirement, for the purpose of this model, is
that you should never have more than 8 bananas at home.

This code meant to be used in
[Runway](https://github.com/SalesforceEng/runway-browser), a tool for
simulating and visualizing concurrent and distributed system models.

The Too Many Bananas problem is based on the Too Much Milk problem, which was
originally devised by Michael L. Powell. Mike encountered the Too Much Milk
problem in real life while he was a grad student at Stanford. Milk, however,
poses complications for modeling: how much milk does one drink at a time? The
Too Many Bananas problem is simpler to model, as bananas naturally come in
discrete units.
