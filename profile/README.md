## Hey, welcome to Vizzu on Github 👋

![GitHub Org's stars](https://img.shields.io/github/stars/vizzuhq?style=social)

We're a small team building a data viz engine that - as [Elijah Meeks put it](https://twitter.com/Elijah_Meeks/status/1444002073792581633?s=09) - provides the most complete form of animating between chart forms. 

<p align="center">
  <a href="https://github.com/vizzuhq/vizzu-lib">
    <img src="https://github.com/vizzuhq/vizzu-lib-doc/blob/main/docs/readme/infinite-60.gif" alt="Vizzu" />
  </a>
</p>

Vizzu's products work similarly to other charting solutions, but here, when you create a set of charts, Vizzu will automatically animate between them. So far we released an open-source [Javascript Library](https://github.com/vizzuhq/vizzu-lib/) and a [Jupyter notebook package](https://github.com/vizzuhq/ipyvizzu) that uses Python. The JS library is dependency-free, written in C++ and compiled to WebAssembly. Both solutions have automatic data aggregation and filtering capabilities, and we set the defaults used based on dataviz guidelines.

A short summary of how we built Vizzu: First, we created an engine that provides a standard interface for several chart types. Then we looked at the parameter space of this engine and made each parameter interpolable, turning our engine into a generic chart morpher that can continuously interpolate between any charts that can be described on its interface. After that, we analyzed these transitions and came up with rules that make them self-explanatory and easy to follow for the viewers, and finally, we embedded these rules into the engine.

Got a question? Want to suggest a new feature? Have a great idea for a data story? Come join our [Slack workspace](https://join.slack.com/t/vizzu-community/shared_invite/zt-w2nqhq44-2CCWL4o7qn2Ns1EFSf9kEg) and talk to us!

All the news about us and our products are available on our [blog](https://blog.vizzuhq.com/)

Check out the stories we built using our tech that gathered 200k+ upvotes on [Reddit](https://www.reddit.com/user/VizzuHQ/?sort=top)

Sign up to our newsletter on our [website](https://vizzuhq.com/) or follow us on [Twitter](https://twitter.com/home) if you want to keep track of what's happening with us.
