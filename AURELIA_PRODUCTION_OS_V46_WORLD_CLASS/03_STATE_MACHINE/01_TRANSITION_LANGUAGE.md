# TRANSITION LANGUAGE

A transition is:

STATE_before
+ AUTHORIZED_EVENT(S)
+ VALIDATION
= STATE_after

Every transition declares:
preconditions
delta
postconditions
revision_from
revision_to
evidence.

No implicit state mutation is legal.
