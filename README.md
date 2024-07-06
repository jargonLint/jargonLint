# jargonLint

The repository to find popular Vale rules that are:

- **Comprehensive:**  Exhaustively prepared from reliable sources
- **Easy to Implement:** Tested and well-documented
- **Permissively Licensed:** MIT compatible licensing

## Vale

[Vale](https://vale.sh/) is an open source documentation software, accessible both from the [command-line](https://vale.sh/docs/vale-cli/installation/) or through [integrations](https://vale.sh/docs/integrations/guide/).
An important feature of this tool is the ability to support custom [styles](https://vale.sh/docs/topics/styles/) and [lint actions](https://vale.sh/docs/topics/actions/).
Vale demonstrates this capability within the [package hub](https://vale.sh/hub/) where you can find style guides prepared for [Google](https://vale.sh/hub/google/) and [Microsoft](https://vale.sh/hub/microsoft/).

### The Limitation

Many organizations, including [Red Hat](https://github.com/redhat-documentation/vale-at-red-hat) and
[Splunk](https://github.com/splunk/vale-splunk-style-guide), often publish their Vale configurations with permissive licenses.
The repositories with these rulesets can be very useful to learn and adapt from.
However, they also reveal that many technical writers have re-iterated upon similar rules, aiming to deliver the same results.

## Our Contribution

We want to improve upon commonly listed rules to build a non-affiliated repository hosting exhaustive lists that everyone can adopt.
This might significantly reduce the redundant work that each organization has to complete.
Furthermore, the burden of maintenance can be lowered if a trusted central repository hosts files while receiving fixes from everyone.

We plan to build more comprehensive rules by:

1. Expanding upon primary sources rather than create arbitrary lists.
2. Combining pre-existing work that can be easily accessed and categorized.
3. Improving the application of certain pre-existing rules so that more projects can benefit from them.
