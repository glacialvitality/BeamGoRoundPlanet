This works with Super Mario Galaxy 2 (SB4E01). Not sure about other regions. Nintendo Switch port is not supported nor planned.

### Setup
You MUST add the following entries to your `ProductMapObjDataTable.bcsv`:
*BeamGoRoundPlanet* (BOTH ModelName and ClassName)

> [!WARNING]
Make sure BeamGoRoundPlanet is not registered under the `PlanetMapDataTable.bcsv` or you did not just set the ClassName in `ProductMapObjDataTable.bcsv` to anything other than *BeamGoRoundPlanet*. Both these things have the potential to break collision.

### Object Arguments
*None*
