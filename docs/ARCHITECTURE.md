                  FRONTEND
                     │
                     │API
                     |
                     ▼
                 BACKEND
                     │
              Simulation State
                     │
                     ▼
              AI / SIMULATION
                     │
       ┌─────────────┼─────────────┐
       ▼             ▼             ▼
 Route Prediction  Scoring       DTEC
       │             │             │
       └─────────────┼─────────────┘
                     ▼
              Vehicle Response
                     │
                     ▼
                  BACKEND
                     │
                     ▼
                 FRONTEND

THE OWNERSHIP:
## Frontend
Owns:
- UI
- animation
- visualization
- controls
- results presentation

## Backend
Owns:
- API
- session
- simulation state
- lifecycle
- results

## AI / Simulation
Owns:
- trajectory
- conflict scoring
- selection
- DTEC
- vehicle response
