if(VTK_DATA_ROOT)
  add_test_tcl(QuadricDecimation Graphics)
  add_test_tcl(TestGridSynchronizedTemplates3D Graphics)
  add_test_tcl(TestMarchingSquares Graphics)
  add_test_tcl(TestRectilinearSynchronizedTemplates Graphics)
  add_test_tcl(TestSynchronizedTemplates2D Graphics)
  add_test_tcl(TestSynchronizedTemplates3D Graphics)
  add_test_tcl(capCow Graphics)
  add_test_tcl(clipArt Graphics)
  add_test_tcl(combStreamers Graphics)
  add_test_tcl(combStreamers2 Graphics)
  add_test_tcl(createBFont Graphics)
  add_test_tcl(deciFranFace Graphics)
  add_test_tcl(dispPlot Graphics)
  add_test_tcl(fieldToPolyData Graphics)
  add_test_tcl(fieldToRGrid Graphics)
  add_test_tcl(fieldToSGrid Graphics)
  add_test_tcl(fieldToUGrid Graphics)
  add_test_tcl(financialField Graphics)
  add_test_tcl(mergeFilter Graphics)
  add_test_tcl(multipleIso Graphics)
  add_test_tcl(polyConn Graphics)
  add_test_tcl(probe Graphics)
  add_test_tcl(probeComb Graphics)
  add_test_tcl(reverseNormals Graphics)
  add_test_tcl(skinOrder Graphics)
  add_test_tcl(smoothMeshOnMesh Graphics)
  add_test_tcl(stripF Graphics)
  add_test_tcl(teapotHulls Graphics)
endif()

add_test_tcl(CellDataToPointData Graphics)
add_test_tcl(Delaunay2D Graphics)
add_test_tcl(Delaunay2DAlpha Graphics)
add_test_tcl(Delaunay2DTransform Graphics)
add_test_tcl(Delaunay3D Graphics)
add_test_tcl(StreamPolyData Graphics)
add_test_tcl(TestTriangleFilter Graphics)
add_test_tcl(capSphere Graphics)
add_test_tcl(constrainedDelaunay Graphics)
add_test_tcl(contourCells Graphics)
add_test_tcl(contourQuadraticCells Graphics)
add_test_tcl(cutLoop Graphics)
add_test_tcl(deciPlane Graphics)
add_test_tcl(hull Graphics)
add_test_tcl(multipleComponentContour Graphics)

if(VTK_DATA_ROOT)
  add_test_tcl(MassProperties Hybrid)
  add_test_tcl(financialField2 Hybrid)
  add_test_tcl(financialField3 Hybrid)
endif()
