/*--------------------------------*- C++ -*----------------------------------*\
| =========                 |                                                 |
| \\      /  F ield         | OpenFOAM: The Open Source CFD Toolbox           |
|  \\    /   O peration     | Version:  4.1                                   |
|   \\  /    A nd           | Web:      www.OpenFOAM.org                      |
|    \\/     M anipulation  |                                                 |
\*---------------------------------------------------------------------------*/
FoamFile
{
    version     2.0;
    format      ascii;
    class       volScalarField;
    location    "0";
    object      k;
}
// * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * * //

dimensions      [0 2 -2 0 0 0 0];

internalField   uniform 1e-08;

boundaryField
{
    inlet
    {
        type            fixedValue;
        value           uniform 1e-08;
    }
    outlet
    {
        type            inletOutlet;
        inletValue      uniform 1e-08;
        value           uniform 1e-08;
    }
    topAndBottom
    {
        type            slip;
    }
    airfoil
    {
        type            fixedValue;
        value           uniform 1e-12;
    }
    defaultFaces
    {
        type            empty;
    }
}


// ************************************************************************* //
