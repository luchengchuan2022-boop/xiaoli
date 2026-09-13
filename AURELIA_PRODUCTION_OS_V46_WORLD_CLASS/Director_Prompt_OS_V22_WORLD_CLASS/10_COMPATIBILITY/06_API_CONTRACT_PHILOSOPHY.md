# API Contract Philosophy

External interfaces are versioned by semantic contract, not by prompt wording.

Backward compatibility means old inputs can be mapped without changing their protected meaning. If mapping is lossy, the loss must be explicit and migration must require review.
