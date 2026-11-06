# Pocket BIM

A lite ArchiCAD for phones: floor plans with walls, doors, windows, columns, beams, slabs, roofs, stairs, railings, furniture, millwork, zones, dimensions and text, several stories, live sections and room elevations, and a 3D view with materials and a sun study. Works offline once installed.

**Open it:** https://gojartshatri-spec.github.io/pocket-bim/

**Install on iPhone:** open the link in Safari, tap Share, then *Add to Home Screen*.
**Install on Android:** open the link in Chrome and tap *Install*.

## What it does

- **Plans:** walls with clean junctions (corners close, the stronger wall's fill wins), doors and windows with automatic tags (D001, W101…), columns, beams (dashed, overhead), slabs, roofs, stairs, railings, furniture and parametric cabinets (base, tall, wall; doors, plinth, height above floor).
- **Documentation:** zones with area, floor and wall finishes; dimension chains that follow a wall and its openings; text with leaders; layers.
- **Sections and elevations:** draw a cut line for a live section through every story, or open any room's four interior elevations.
- **Export:** plans, sections, room elevations and a door, window and room schedule as PDF or PNG sheets with a title block, north arrow and scale bar; the full set as one PDF; the schedule as CSV.
- **Checks:** flags small rooms, low daylight (glazing under 1/8 of the floor), narrow doors and steep stairs. These are typical residential minimums, not a building-code check.
- **3D:** finishes (render, brick, timber, concrete, stone, tile), floor materials, and a sun study by date, time and latitude.
- **Measure:** distances, or a room's area and perimeter.
- **Shapes and editing:** polygon zones, slabs, roofs and site; hip, shed, gable and flat roofs; multi-select with move, copy, rotate, mirror, array, align and groups; wall offset, trim/extend and split.
- **Wall types:** layered walls (render, insulation, brick, block, concrete, gypsum, timber…) with U-values, drawn layer by layer in plans and sections.
- **Renovation:** existing / demolish / new status with existing, demolition and proposed plans; demolished elements dashed red, also in 3D.
- **Site and grids:** plot boundary with setback line and check, site coverage, true north (also used by the sun study); structural grid lines with bubbles that snap and show in sections.
- **Ceiling plan:** ceiling heights and types per room, lights, fans, detectors, speakers and AC; sockets, switches and data outlets on the floor plan; legend on the sheet.
- **Openings:** single, double, sliding, pocket and cased doors; casement, tilt & turn, sliding and fixed windows; skylights that follow the roof slope.
- **Quantities and cost:** net wall areas by type, layer volumes, bricks and blocks, slabs, roof slope areas, finishes, openings, millwork and fixtures, with your rates; on screen, as a sheet or CSV.
- **Underlay:** trace a survey or scan; calibrate its scale by a known distance (kept on the device).
- **Stairs:** straight, L (quarter landing) and U (half landing) stairs by rise and run, left or right turn, flight width; plan, 3D, section and DXF, with checks for riser, going, 2R+G and width.
- **Curtain walls:** any wall can be a curtain wall with mullion and transom spacing; glazed grid in plan, 3D and IFC.
- **Curved walls:** curve any wall by its bulge, or fillet the corner where two walls meet; arcs become grouped segments that work everywhere.
- **Wall profiles:** sloped and gable-end wall tops, in 3D, sections, elevations, quantities and IFC.
- **More openings:** arched openings and niches (recesses that don't go through).
- **Shafts:** slab openings and shafts cutting one story or every story above, in plan, 3D, sections, quantities and IFC.
- **Ramps:** by rise and run, with the slope shown on plan and checked against 1:12.
- **Stairs:** spiral stairs and L stairs with winders, on top of straight, L and U.
- **Roofs:** mansard and barrel roofs, dormers, gutters with downpipes, and fascia boards.
- **Footings:** strip footings drawn or added under every wall of a story in one tap, with concrete volumes.
- **Photo to plan:** photograph a sketch or pick a scan; Claude traces walls, doors, windows and rooms onto the story as one group, scaled from a width you give, a dimension on the drawing or the door widths (works when opened in Claude).
- **Analysis:** energy estimate (heat loss, peak load, kWh/m² and an indicative class) with daylight factor per room; area schedule (GIA / NIA); embodied carbon; accessibility, clash and fire-escape checks.
- **Generators:** kitchen runs along a wall, railings on a slab's open edges, parking layouts; trees, shrubs and cars.
- **Sheets:** project number, client, revisions table and sheet numbers in the title block; 1:20 and 1:5 scales; smart labels like {name} {area}.
- **More:** versions you can save, compare and restore; PDF underlays; sun study that plays a day, with city latitudes; ceilings in 3D; stylus mode; keyboard shortcuts (press ?).
- **Services:** pipes and ducts by system (drainage with fall checks, water, heating, gas, supply and extract air); electrical circuits with a load schedule.
- **Site:** contour lines build a 3D terrain, with cut and fill under the ground floor.
- **Documents:** keynotes with a sheet legend, room data sheets (also CSV), check results exported as BCF issues.
- **Import and set-up:** DXF to walls (paired face lines become one wall), free-form morph blocks, a toolbar you can trim, fine / standard / bold pens.
- **IFC:** export the whole model as IFC 4 (stories, walls with U-values, openings that cut their walls, slabs, gable and shed roofs, rooms, stairs, columns, beams, railings, objects) and import walls, slabs, roofs, rooms, columns, doors and windows from IFC.
- **Hand-off:** DXF (R12) plan export with CAD layers, saved 3D views, 3D image (PNG), GLB model, and AR on ARCore phones.

Projects are saved on the device itself; *Copy project as JSON* and *Import* move them between devices. The AI assistant and cloud projects with shared comments work when the app is opened inside Claude.
