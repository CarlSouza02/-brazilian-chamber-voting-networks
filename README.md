

# Brazilian Chamber Voting Networks

Network-based analysis of roll-call voting patterns in the Brazilian Chamber of Deputies using statistical similarity, graph modeling, and network visualization.

## Overview

This project analyzes roll-call voting behavior in the Brazilian Chamber of Deputies by transforming legislative voting records into statistical similarity matrices and weighted networks.

The analysis is performed at two levels:

- political parties;
- individual deputies.

Voting profiles are compared using correlation-based similarity measures. These similarities are then transformed into weighted graphs that can be analyzed using Network Science methods.

The project combines:

- data processing;
- exploratory data analysis;
- statistical similarity analysis;
- graph modeling;
- network metrics;
- network visualization;
- temporal comparison across legislative periods.

## Analytical Pipeline

```text
Raw Voting Records
        ↓
Data Cleaning
        ↓
Vote Encoding
        ↓
Voting Matrix
        ↓
Similarity Matrix
        ↓
Threshold Selection
        ↓
Network Construction
        ↓
Network Visualization
        ↓
Network Metrics
        ↓
Sensitivity Analysis
