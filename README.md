# OpenFOAM_Cases

This is the OpenFOAM case for the 2D incompressible flow simulation over an airfoil at an 5 degree angle of attack. Please refer to this: https://doi.org/10.1017/S0022112008000864 (Jones et al.) and https://doi.org/10.1063/1.5126663 (Simth and Ventikos) papers for more info. 

The LES turbulence model with WALE SGS model is used in the provided case. Please feel free to test this case with different turbulence models and compare the results (Coefficient of pressure plots) with those aforementioned papers.

The results from checkMesh of this case are attached:

Mesh stats 
    points:           2078398
    internal points:  0
    faces:            4150202
    internal faces:   2071804
    cells:            1037001
    faces per cell:   6
    boundary patches: 4
    point zones:      0
    face zones:       0
    cell zones:       0

Overall number of cells of each type:
    hexahedra:     1037001
    prisms:        0
    wedges:        0
    pyramids:      0
    tet wedges:    0
    tetrahedra:    0
    polyhedra:     0

Checking topology...
    Boundary definition OK.
    Cell to face addressing OK.
    Point usage OK.
    Upper triangular ordering OK.
    Face vertices OK.
    Number of regions: 1 (OK).

Checking patch topology for multiply connected surfaces...
    Patch               Faces    Points     Surface topology
    frontAndBack        2074002  2078398  ok (non-closed singly connected)  
    outlet              798      1598     ok (non-closed singly connected)  
    airfoil             999      1998     ok (non-closed singly connected)  
    inlet               2599     5200     ok (non-closed singly connected)  
    ".*"                2078398  2078398  ok (closed singly connected)      


Checking faceZone topology for multiply connected surfaces...
    No faceZones found.

Checking basic cellZone addressing...
    No cellZones found.

Checking basic pointZone addressing...
    No pointZones found.

Checking geometry...
    Overall domain bounding box (-2.12179 -2.34198 -0.0001) (2.05 2.33886 0)
    Mesh has 2 geometric (non-empty/wedge) directions (1 1 0)
    Mesh has 2 solution (non-empty) directions (1 1 0)
    All edges aligned with or perpendicular to non-empty directions.
    Boundary openness (5.1735e-21 -1.53948e-20 -2.18032e-14) OK.
    Max cell openness = 4.38643e-15 OK.
    Max aspect ratio = 214.766 OK.
    Minimum face area = 1.64651e-11. Maximum face area = 0.00129745.  Face area magnitudes OK.
    Min volume = 1.64651e-15. Max volume = 1.29745e-07.  Total volume = 0.00167943.  Cell volumes OK.
    Mesh non-orthogonality Max: 13.3022 average: 2.77725
    Non-orthogonality check OK.
    Face pyramids OK.
    Max skewness = 0.164067 OK.
    Coupled point location match (average 0) OK.

Mesh OK.

End
