# Schema Rules V43

Schemas are contracts, not decoration. Unknown required-field omission = invalid.

Every object must carry identity + version + provenance where applicable.

Enum values are closed unless an explicit schema migration is authorized.
