# Research Proposal: Market-Based Transport Network Load Balancing Mechanism

## Introduction

Open transport networks — in both the physical and informational domains — are considered [public goods](https://en.wikipedia.org/wiki/Public_good_(economics)). However, the reality is that these networks operate on a [rivarly continuum](https://en.wikipedia.org/wiki/Rivalry_(economics)): they can only accommodate a certain volume of traffic before their efficacy begins to degrade. Congestion pricing has been introduced in some urban transport networks to manage network loads, but to date, implementations are relatively simplistic, and cause controversy for a range of factors including being inequitable and adversely affecting commerce.


This proposal explores the potential of precision congestion zones, creating a market-based transport network load balancing mechanism that leverages dynamic, agent-specific pricing to manage network loads based on various factors such as vehicle attributes, real-time network loads and public safety.

## Problem Statement

Open transport network access is inefficient. Current congestion pricing systems are also inefficient and inequitable. 

## Objectives

1. Measure network load using various parameters:
    - Transit times
    - Transit costs (energy source, vehicle amortization)
    - Congestion levels
    - Network emissions (greenhouse gas, particulates etc)
    - Road surface wear and tear
    - Public safety index

2. Investigate the effect of individual routing decisions between an origin and destination to network load measurements.

3. Assess how the introduction of route-specific costs could affect agent behavior.

4. Determine if precision congestion pricing can modify agent incentives and improve network operational efficiency.

## Research Questions

1. How important are decisions about the route taken between an origin and destination to network load measurements?
2. How would the introduction of a route-specific cost affect agent behavior?
3. Can precision congestion pricing modify agent incentives and therefore improve measures of network operational efficiency?

## Hypothesis

A precision market-based transport network load balancing mechanism with dynamic, agent-specific pricing allows for the effective and equitable management of network load metrics. Implementing such a system could provide policymakers with a sophisticated tool for managing network behavior based on evolving priorities.

## Methodology

This research proposal could take a number of different tacks.
- Agent-based modeling of network dynamics to estimate network load metrics and assess impacts of altered agent behavior based on precision pricing
- Design and implementation of a context-aware pricing model using machine learning techniques
- Design and implementation of precision congestion market infrastructure using customized automated market makers and location proofs
- Development of vehicle-specific location proofs, a requirement to securely operate a precision congestion system
- Risk analysis to study threats and attack vectors for a precision congestion system
- Assess feasibility of sub-network adoption, such as implementing the system within specific networks like Uber
- Assess relevance to other transport networks such as the Internet, maritime shipping, hydrological / irrigation systems, etc
- Use cases and impacts on public health + safety, for example by granting preferential access to emergency response vehicles
- Potential impact of system implementation on network greenhouse gas emissions

### User Experience

From the perspective of a driver or rider in an autonomous vehicle, the functionality of the load balancing system is mostly hidden. Modern drivers often rely on GPS-enabled navigation applications that prioritize duration, cost, safety, and comfort. This proposal imagines a scenario where riders input their destination and indicate additional preferences, such as willingness to pay more for a faster journey.

### Requirements

- **Agents**
    - Identity: Machine-readable vehicle attributes, payment accounts, location proofs.
    - Functionality: Routing algorithms, user/machine interfaces.
- **Spatial Registries**
    - Network data and functionality.
- **Pricing**
    - Pricing models that incorporate spatiotemporal information and agent attributes to determine network segment access costs.
    - Costs: Time-gated network segment access tokens, additional congestion fees, non-use costs.
    - Revenue: Data capture and rerouting fees.
- **Governance Parameters**
- **Access Token Markets**
- **Risks**
    - NIMBYism: Local efforts to levy excessive fees on network segments.
    - Remote attacks: Risks associated with financializing transport network access and potential market manipulation.

### Potential Impact

This research aims to develop a sophisticated tool for managing transport network behavior, which could lead to more efficient, equitable, and sustainable urban transport systems. By dynamically balancing network loads, this approach could reduce congestion, lower emissions, and enhance public safety, contributing to broader goals of human dignity and planetary stewardship.

## Conclusion

The proposed market-based transport network load balancing mechanism represents a promising solution to the inefficiencies and inequities of current transport network access methods. By leveraging dynamic, agent-specific pricing, this approach has the potential to significantly improve network operational efficiency and support policymakers in achieving sustainable urban transport goals.