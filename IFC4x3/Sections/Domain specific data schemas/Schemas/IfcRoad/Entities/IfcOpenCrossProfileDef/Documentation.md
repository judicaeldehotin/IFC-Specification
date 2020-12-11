A two-dimensional open profile defined by widths and slopes for the use within the swept surface geometry, in SectionedSurface in particular. The underlying coordinate system is defined by the swept surface that uses the profile definition; when used in SectionedSurface it is the XY plane of each list member of SectionedSurface.CrossSectionPositions where the profile X axis is oriented perpendicularly to the left of the Directrix (same direction as positive LateralOffset at _IfcPointByDistanceExpression_) as facing forward along the directrix, and the profile Y axis is oriented upwards or vertically perpendicular to the Directrix depending on the usage in the SectionedSurface.
The behaviour of OpenCrossProfileDef in sweeping operation can be controlled by attribute Tags. Tags allow two consecutive cross sections to have different number of break points: points with the same tag value are connected either by assuming linear longitudinal breakline between them, or by a guide curve identified by the same Tag value as the cross section points.
******Formal propositions:*** The profile type shall be CURVE.
* The list of slopes and the list of widths shall be of the same size, and the list of tags shall have one more member.

_IfcOpenCrossProfileDef-1</u></font>]($imageman://id=1364904450;mdg=Global;name=IfcOpenCrossProfileDef-1;type=Bitmap;)_ </u></font>]($imageman://id=1110734429;mdg=Global;name=OpenCrossProfileDef-1;type=Bitmap;)