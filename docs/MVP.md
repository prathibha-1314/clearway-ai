# ClearWay MVP

## Problem
Ambulances can experience delays in heavy urban congestion because
surrounding vehicles react independently without coordinated identification
of vehicles that may obstruct the ambulance path.

## Buildathon Question
Can a dynamic, selective emergency corridor reduce ambulance passage
delay compared with conventional emergency response?

## Scenario
- 15–20 vehicles
- 1 ambulance
- Heavy urban congestion
- Constrained road segment / bottleneck
- Synthetic/simulated traffic

## Baseline
- Same traffic scenario
- Ambulance moves
- No DTEC
- No selective guidance
- Vehicles react independently

## ClearWay
- Predict ambulance path
- Analyze vehicles
- Calculate conflict scores
- Select relevant vehicles
- Generate DTEC
- Provide simulated guidance
- Vehicles move aside
- Ambulance passes
- DTEC releases

## Primary Metric
Ambulance Passage Delay

## Secondary Metrics
- Clearance time
- Conflicting vehicles
- Selected vehicles
- Guided vehicles
- Unnecessary alerts

## Out of Scope
- Real GPS
- Real Bluetooth
- Real driver phones
- Computer vision
- ML training
- Production deployment
- Real traffic cameras
- Smart traffic signal integration
