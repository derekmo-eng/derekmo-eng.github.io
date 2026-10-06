Multi-Domain Constraint-Based SR-MPLS Traffic Engineering Demo

Open index.html in a web browser.

This package contains the current technical demonstration report and proof images.

The report explains:
- Native IS-IS/SR-MPLS topology learned by OpenDaylight through BGP-LS.
- NETCONF/RPM enrichment for delay, jitter, loss, bandwidth, utilization and BGP-LU forwarding state.
- Global constrained path computation using CSPF/SAMCRA.
- BGP-LU outgoing-to-incoming label translation for PCEP forwarding compilation.
- Bidirectional PCEP provisioning with rollback protection.
- The distinction between end-to-end forwarding and a fully explicit end-to-end SR ERO.
- Baseline PBR01 proof from ODL TED -> SPRING-TE FIB -> MPLS traceroute -> CE-to-CE EVPN service validation.

Baseline customer service validation uses the 192.168.0.0/31 point-to-point network between the two CE endpoints, carried by EVPN over the selected multi-domain transport path.
