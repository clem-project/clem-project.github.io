---
layout: page
title: "WP1: Live and Exploratory Modeling Foundations"
description: Establishing theoretical and methodological foundations for live and exploratory modeling
# img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

WP1 focuses on establishing the theoretical and methodological foundations for live and exploratory modeling.

## Objectives

This work package focuses on the underlying theory to enable change propagation and runtime state co-evolution for live languages. In particular, WP1 specifies what and how the models' changes are reflected on the runtime states and what strategy to rely on for the co-evolution of the old states to a new consistent state.

The work package proceeds iteratively, ensuring regular synchronization between the global LEM view and the integration of direct manipulation (DM) through exploratory modeling (EM) capabilities.

## Partner Contributions

**U.Rennes (Lead):** Leads the development of language runtimes and workbenches for the coupling live modeling (immediate feedback & direct manipulation) with exploratory modeling.

**JKU:** Brings expertise in search-based model transformations and tools (e.g., MOMoT), ensuring the DM aspect of live modeling is developed through exploratory modeling techniques.

## Tasks

#### Task T1.1: Efficient and Flexible Coupling of Live and Exploratory Modeling (Lead: U.Rennes)

**Description:** Creation of language servers that combine immediate feedback (IF) and direct manipulation (DM) capabilities, building upon expertise in co-evolution, change propagation, and modification of runtime state.

**Challenge:** Finding a way to represent, modify, and explore a potentially large and diverse set of runtime states. If a combined view of IF and DM is not easily representable, the integration will fall back to separated representations.


#### Task T1.2: Exploration Strategies for Exploratory Modeling (Lead: JKU)

**Description:** Development of exploratory modeling strategies and preparation of using EM as a solution for direct manipulation (DM). The goal is rapid prototypical implementation for integration in LEM, followed by iterations producing search strategies, computation cost-reduction measures, and user constraint integration.

**Challenge:** The large search space that must be explored to reach a given runtime state. Mitigation through metaheuristic and search-based solutions as cost-limited options.

