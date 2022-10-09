# Supported features

## High availability

This charm supports high availability via HAcluster.

When more than one unit is deployed with the [hacluster][hacluster-charm]
application the charm will bring up an HA active/active cluster.
See the rabbitmq-server charm for an example of a native HA service.

See [Infrastructure high availability][cg-ha-apps] for more information.

## Policy overrides

This charm supports the policy overrides feature.

Policy overrides allow an operator to override the default policy of an
OpenStack service. See [Policy overrides][cg-policy-overrides] for more
information on this feature.

## Deferred service events

This charm supports the deferred service events feature.

Operational or maintenance procedures applied to a cloud often lead to the
restarting of various OpenStack services and/or the calling of certain charm
hooks. Although normal, such events can be undesirable due to the service
interruptions they can cause.

The deferred service events feature provides the operator the choice of
preventing these service restarts and hook calls from occurring, which can
then be resolved at a more opportune time.

See [Deferred service events][cg-deferred-service-events] for more
information on this feature.

## Special features X

Give a summary and (most probably) link to a extra-info file.
