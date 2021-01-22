An IfcAlignment2DCantSegment is an individual segment along the IfcAlignment2DCant.
The cant alignment is defined by ordered segments that connect end-to-start. The points defined in a cant alignment segment are defined in a plane with x = distance along horizontal alignment and y = height relative to projected points in vertical alignment. 
The following cant segment types are defined:
* line segment - IfcAlignment2DCantSegLine
* transition curve segment - IfcAlignment2DCantSegTransition


For each cant segment, the following information is provided:
* the start point, defined by distance along the horizontal alignment
* the length (as horizontal length along the distance along (not the curve segment length))
* the start cant, given by the values of left cant and right cant, measured relatively to vertical alignment
* the end cant, given by the values of left cant and right cant, measured from vertical alignment
* the information of tangential continuity that can be used to check continuity of segments (e.g. invalid sudden change of cant or missing cant information if end point and starting point differ over a threshold).