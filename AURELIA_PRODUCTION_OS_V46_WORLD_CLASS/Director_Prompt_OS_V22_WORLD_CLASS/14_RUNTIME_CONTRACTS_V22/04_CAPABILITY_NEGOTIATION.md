# V22 Model Capability Negotiation

Before rendering, the adapter declares capabilities and limitations for:
- image/video conditioning;
- reference handling;
- camera motion;
- character consistency;
- temporal consistency;
- audio;
- duration;
- aspect ratio;
- prompt/control channels;
- negative constraints.

The compiler must not silently delete unsupported requirements.

Each gap is classified:
`SUPPORTED, PARTIAL, UNSUPPORTED, UNKNOWN`

Partial/unsupported capability requires either a compensating production strategy or an explicit semantic-risk decision.
