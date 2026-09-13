# SIDE EFFECT BOUNDARY

External effects are separated from semantic commit.

Recommended logical sequence:
semantic commit
→ durable effect intent
→ external execution
→ observation
→ verification.

An external model/video generation failure must not roll back an already valid story Canon unless a compensating semantic transaction is explicitly authorized.
