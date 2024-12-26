# 1. Conceptual Framework Setup

## Reference Plane and Grid System

### Base Plane Setup
1. Create a construction plane at world origin (0,0,0)
2. Define the site boundary using project dimensions from parameters.json
3. Create a rectangular grid with following properties:
   - Major grid lines: 3000mm spacing
   - Minor grid lines: 1000mm spacing
   - Extend grid 2000mm beyond pavilion footprint

### Grid Organization
```
Reference Grid Layout:
+------------------+
|  . . . . . . .  |  . = Minor grid points
|  .   .   .   .  |  + = Major grid points
|  . . + . . + .  |
|  .   .   .   .  |
|  . . + . . + .  |
|  .   .   .   .  |
|  . . . . . . .  |
+------------------+
```

## Design Drivers

### Primary Control Curves
1. Create two main spline curves:
   - Curve 1: Main roof profile (front to back)
   - Curve 2: Secondary profile (side to side)
   - Both curves should have 5-7 control points for adequate flexibility

### Control Points
- Place control points at key locations:
   - Column connection points
   - Maximum height points
   - Seating transition areas
   - Ground contact points

### Parametric Relationships
1. Link control point heights to `max_height` parameter
2. Connect column positions to grid intersections
3. Define seating curve relationship to main roof curve

## Validation Checks
- Ensure grid extends beyond pavilion boundary
- Verify control curves are within height limits
- Check that all key points snap to grid

## Framework Specifications
www.memostudio.design

## Core Structure
- Primary grid: 12m x 8m
- Height: 4.5m
- Bay spacing: 4m intervals
- Material: Aluminum alloy 6061-T6

## Geometric System
### Primary Grid
- X-axis: 3 bays @ 4m
- Y-axis: 2 bays @ 4m
- Z-axis: Variable heights 3.5m - 4.5m

### Connection Points
- Column interfaces: 8 points
- Roof attachment: 12 points
- Ground anchors: 8 points
- Seating integration: 6 points

## Material Properties
### Aluminum Framework
- Profile: 200mm x 100mm
- Wall thickness: 6mm
- Finish: Anodized, clear
- Connection type: Welded + Bolted

### Structural Performance
- Wind load resistance: 2.4 kPa
- Snow load capacity: 1.5 kPa
- Lateral stability: Enhanced bracing
- Thermal expansion: Compensated joints

## Assembly System
### Primary Connections
- Bolt grade: M16 (8.8)
- Welding spec: AWS D1.2
- Joint design: Moment-resistant
- Access panels: Integrated

### Secondary Elements
- Cable routing paths
- Lighting fixture mounts
- Panel attachment points
- Service access routes

## Integration Features
### Service Integration
- Power conduits
- Lighting channels
- Drainage paths
- Ventilation routes

### Component Interface
- Column attachment points
- Roof connection system
- Seating support zones
- Ground anchor details

## Technical Requirements
### Structural Integrity
- Load distribution paths
- Stability analysis
- Deflection limits
- Safety factors

### Installation Sequence
1. Foundation preparation
2. Primary frame erection
3. Secondary elements
4. Component integration
5. Final adjustments

## Validation Criteria
1. Structural Performance
   - Load testing
   - Deflection checks
   - Joint integrity
   - Stability verification

2. Integration Verification
   - Component fit
   - Service routing
   - Access provision
   - Maintenance paths

3. Assembly Confirmation
   - Connection checks
   - Alignment verification
   - Tolerance compliance
   - Finish quality
