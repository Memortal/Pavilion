# 2. Column Generation and Ground Connections

## Column Placement

### Position Selection
1. Identify key grid intersections for column placement:
   - Minimum 4 columns required
   - Maintain 6000-8000mm maximum spacing
   - Ensure columns support primary load paths

### Height Distribution
```
Column Height Pattern:
   A    B    C    D
   |    |    |    |
   5m   4m   4.5m 3.5m  (Example heights)
```

## Column Geometry

### Profile Generation
1. Create base profile:
   ```
   Parameters:
   - Base radius: 400mm
   - Top radius: 250mm
   - Height: Variable (3000-5000mm)
   ```

2. SubD modeling approach:
   - Start with 8-sided cylinder
   - Add edge loops at:
     * Base (0%)
     * Lower quarter (25%)
     * Middle (50%)
     * Upper quarter (75%)
     * Top (100%)

### Ground Connection

1. Base flare creation:
   ```
   Blend Parameters:
   - Start radius: Column base radius
   - End radius: Ground_blend_radius
   - Height: 800mm
   - Smooth factor: 0.3
   ```

2. Transition steps:
   - Create circular base path
   - Loft between column profile and ground
   - Add filleted edges (radius: 50mm)

## Structural Considerations

### Thickness Control
1. Variable wall thickness:
   - Base: 200mm minimum
   - Mid-height: 150mm minimum
   - Top connection: 180mm minimum

### Connection Points
1. Top preparation:
   - Create flange for roof connection
   - Add reinforcement ribs if needed
   - Ensure smooth transition to roof surface

## Validation Checks
- Verify minimum thickness requirements
- Check column verticality
- Confirm ground blend smoothness
- Ensure proper grid alignment

## Column Design Specifications
www.memostudio.design

## Column System
### Primary Elements
- Height range: 3.5m - 4.5m
- Base diameter: 400mm
- Top diameter: 300mm
- Material: Aluminum alloy
- Finish: Anodized matte

### Geometric Definition
- Fluid form transition
- Variable cross-sections
- Integrated lighting channels
- Structural optimization

## Technical Details
### Material Properties
- Aluminum grade: 6061-T6
- Wall thickness: 8mm
- Surface treatment: Anodized
- Internal reinforcement: Steel core

### Structural Features
- Load capacity: 25kN
- Moment resistance: 15kNm
- Buckling prevention: Internal ribs
- Connection points: 8 per column

## Lighting Integration
### LED System
- Channel depth: 50mm
- LED strip: IP67 rated
- Power: 24V DC
- Color temperature: 3000K

### Control Features
- Dimming capability
- Color temperature adjustment
- Motion response
- Weather adaptation

## Ground Connection
### Base Plate
- Diameter: 600mm
- Thickness: 25mm
- Bolt pattern: 8-point
- Material: Stainless steel

### Foundation Interface
- Anchor bolts: M20
- Grout space: 50mm
- Leveling system: Integrated
- Waterproofing: EPDM gasket

## Manufacturing Requirements
### Fabrication Method
- CNC milling
- Robotic welding
- Surface finishing
- Quality control

### Assembly Sequence
1. Core structure
2. Lighting integration
3. Surface treatment
4. Ground connection

## Installation Process
### Site Preparation
- Foundation work
- Power supply
- Drainage provision
- Level verification

### Column Placement
1. Base plate mounting
2. Column alignment
3. Power connection
4. Final adjustments

## Quality Control
### Testing Protocol
- Load testing
- Light output verification
- Water resistance check
- Finish inspection

### Maintenance Access
- Service panels
- Cable routing
- LED replacement
- Drainage cleaning

## Performance Criteria
1. Structural Integrity
   - Load capacity
   - Stability verification
   - Connection strength
   - Weather resistance

2. Lighting Performance
   - Illumination levels
   - Color accuracy
   - Control response
   - Energy efficiency

3. Installation Quality
   - Alignment precision
   - Connection security
   - Finish consistency
   - System integration
