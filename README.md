# Draft of an API for preference-aware MPTCP

During our work on [ProgMP](https://progmp.net),
we found that Multipath TCP scheduling can incorporate application information, preferences, and hints to improve preference-awareness and relevant performance metrics.

This draft provides an API for application preferences instead of an API to directly control of the network stack.
In particular, this API does not directly control the subflow creation and packet scheduling.
Instead, the provided application preferences enable the network stack to optimize for relevant target metrics while preserving subflow preferences.

## Contribute

This draft is still preliminary. Contributions, feedback, suggestions ...  are welcome!