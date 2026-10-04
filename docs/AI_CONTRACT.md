 WHAT does AI give frontend/backend?

# ClearWay AI / Simulation Contract

## Owner
AI + Simulation Engineer

## Input

Ambulance:
- position
- speed
- heading
- route

Vehicles:
- id
- position
- speed
- heading
- lane

Road:
- geometry
- bottleneck
- lanes

## Output

### Vehicle Analysis

Each vehicle returns:

- id
- distance
- routeOverlap
- headingMatch
- timeToConflict
- conflictScore
- selected
- status

### DTEC

- status
- routeSegment
- center
- length
- width
- vehicleIds

### Vehicle Response

- vehicleId
- previousPosition
- targetPosition
- responseState

THE LIFECYCLE:

Ambulance trajectory
        ↓
Vehicle analysis
        ↓
Conflict scoring
        ↓
Vehicle selection
        ↓
DTEC generation
        ↓
Guidance
        ↓
Vehicle response
