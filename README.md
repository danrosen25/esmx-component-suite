Suite of NUOPC components built and tested with ESMX
Requires: ESMF version 8.5.0 or greater

| Component             | Organization | Model Type     | Build File        | Ready | Requirements |
| --------------------- | -------------| -------------- | ----------------- | ----- | ------------ |
| `ParFlow`             | Princeton    | Groundwater    | parflow.yaml      | Yes   | HYPRE, Silo  |
| `fire_behavior_nuopc` | NCAR - RAL   | Wildfire       | firebehavior.yaml | Yes   | NetCDF       |
| `WRFHYDRO`            | NCAR - RAL   | Hydrology      | wrfhydro.yaml     | Yes   | NetCDF       |
| `LIS`                 | NASA         | Land Surface   | lis.yaml          | No    | (TBD)        |
| `FV3ATM`              | NOAA - GFDL  | Atmosphere     | ufsatm.yaml       | No    | (TBD)        |

Edit apps/ALLCOMPS.yaml as needed
Build using
`ESMX_Builder apps/ALLCOMPS.yaml`
or
`ESMX_Builder apps/<Build File>`
