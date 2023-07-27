# Roadmap

This document outlines the development roadmap for the Koordinator project.

## v1.3 Roadmap (WIP)

- scheduling: network topology aware scheduling
- scheduling: improve Reservation for allocation strategies
- scheduling: NUMA topology aware scheduling
- scheduling: add ResourceSummary CRD to show the resource view of cluster
- slo: improve framework of interference detection
- slo: provide ability of blkio isolation

## v1.2 Roadmap

- koord-scheduler: retrieve reservationInfo from cache first in preFilter hook
- koord-scheduler: ElasticQuota Plugin need DecoratePod OnPodDelete
- koord-descheduler: support pod deletion cost and eviction cost
- koord-descheduler: limits frequently migrated workloads
- koordlet: Feat add more metrics for cpu burst and suppress
- koordlet: support cpu eviction in cpuset supress mode with cpu static policy
- koordlet: add metrics for batch resources

## v1.1 Roadmap

- api: add percentile node usage to NodeMetric
- koord-scheduler: LoadAware scheduling support percentile usage and load scheduling by Prod Pods
- koord-scheduler: NodeCPUBindPolicy supports SpreadByPCPUs
- koord-scheduler: ElasticQuota supports Decorator to decorate Node, Pod and ElasticQuota
- koord-descheduler: support loadaware/lowNodeLoad descheduling
- koordlet: node resource report and common QoS features support cgroups-v2
- koordlet: Other qos features support cgroups v2

## v1.0 Roadmap

- apis: support customizing different priority ranges
- add webhook and node topo feature gates control
- koord-scheduler: optimize ElasticQuota plugin's update logic
- koord-scheduler: improve nodeNUMAResource allowUseCPUSet and sortCPUsByRefCount
- koord-manager: support calculate batch resource based on memory request
- koordlet: CPI collector for Interference Detection
- koordlet: enable group identity by sysctl when cpu qos enabled
- runtime-proxy: Support hook server deployed by k8s pod

