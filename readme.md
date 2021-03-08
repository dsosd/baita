# Notice

After some time experimenting with baita, it seems obvious that the original goal (ABAC language that transpiles to XACML) was a DSL that is harder to use and less flexible than plain code. The future of the (unpublished/non-public) efforts so far will most likely be transformed by hooking into an authorization library and adding desired additional functionality. The modified library could then be loaded dynamically and hot swapped when a policy update occurs.
