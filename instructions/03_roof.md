# 3. Doubly Curved Roof Surface Generation

## Guide Curve Setup

### Primary Curves
1. Create spine curves:
   ```
   Curve Properties:
   - 3D NURBS curves
   - Degree 3 (cubic)
   - 5-7 control points
   - Maximum height: 5000mm
   ```

2. Control point placement:
   - Start at column tops
   - Peak points between columns
   - Edge conditions for cantilevers

## Surface Generation

### Method A: NURBS Lofting
1. Create cross-section curves:
   ```
   - Spacing: 1500mm maximum
   - Maintain G2 continuity
   - Variable width: 8000-12000mm
   ```

2. Lofting procedure:
   - Align sections to guide curves
   - Use uniform lofting with tight tolerances
   - Maintain surface degree 3 or higher

### Method B: SubD Modeling
1. Initial surface setup:
   ```
   - Start with planar quad mesh
   - Subdivision level: 4
   - Edge control loops: minimum 3
   ```

2. Surface manipulation:
   - Push/pull control points to match guides
   - Maintain smooth curvature transitions
   - Add edge loops for local control

## Column Integration

### Connection Details
1. Surface-column intersection:
   ```
   Blend Parameters:
   - Radius: 300mm
   - Smooth factor: 0.4
   - Tangency maintenance: ON
   ```

2. Structural reinforcement:
   - Add thickness at connection points
   - Create smooth transitions
   - Maintain minimum 180mm thickness

## Surface Analysis

### Curvature Verification
1. Perform analysis:
   - Check for discontinuities
   - Verify minimum radius > 2000mm
   - Ensure no flat spots > 2000mm²

### Thickness Distribution
1. Variable thickness mapping:
   ```
   - Column connections: 200mm
   - Mid-spans: 150mm
   - Edges: 180mm
   ```

## Validation Checks
- Surface continuity (G2 minimum)
- Proper column integration
- Thickness requirements met
- Overall form fluidity

## Roof Design Specifications
www.memostudio.design

## Surface Geometry
### Primary Form
- Span: 12m x 8m
- Height variation: 1.2m
- Double curvature: Fluid form
- Edge treatment: Tapered

### Technical Parameters
- Thickness: 200mm - 300mm
- Panel size: 1m x 1m
- Joint width: 15mm
- Edge radius: 50mm

## Material System
### Panel Construction
- Core: Aluminum honeycomb
- Skin: 3mm aluminum
- Coating: PVDF finish
- Color: Pearl white

### Performance Specs
- U-value: 0.15 W/m²K
- Sound reduction: 45dB
- Fire rating: Class A
- Weight: 45kg/m²

## Water Management
### Drainage System
- Slope: 2% minimum
- Channels: Integrated
- Outlets: 8 points
- Capacity: 100mm/hr

### Edge Treatment
- Drip edge detail
- Splash protection
- Corner resolution
- Seal integration

## Lighting Integration
### Fixture System
- LED strips: IP67
- Power: 24V DC
- Spacing: 600mm
- Control: DALI

### Effect Design
- Uplight wash
- Edge highlight
- Feature spots
- Color control

## Support Structure
### Connection Points
- Primary: 12 locations
- Secondary: 24 points
- Adjustment: ±50mm
- Load transfer: Distributed

### Movement Joints
- Thermal expansion
- Seismic provision
- Wind deflection
- Settlement allowance

## Environmental Response
### Solar Control
- Heat reflection: 75%
- Light transmission: 15%
- UV protection: 99%
- Glare reduction

### Weather Protection
- Wind resistance: 180km/h
- Snow load: 2.0kN/m²
- Rain intensity: 75mm/hr
- Hail impact: Class 4

## Installation Method
### Assembly Sequence
1. Primary structure
2. Panel mounting
3. Joint sealing
4. System integration

### Quality Control
- Level verification
- Joint inspection
- Seal testing
- System checks

## Maintenance Access
### Service Points
- Walking paths
- Anchor points
- Access panels
- Cleaning system

### Safety Features
- Fall protection
- Load ratings
- Emergency access
- Warning systems

## Performance Validation
1. Structural Testing
   - Load capacity
   - Deflection limits
   - Joint movement
   - Impact resistance

2. Environmental Testing
   - Water tightness
   - Thermal cycling
   - Wind tunnel
   - Acoustic performance

3. System Integration
   - Lighting function
   - Drainage flow
   - Control response
   - Maintenance access
