drake_add_mex(nWaypointCubicSplinemex nWaypointCubicSplinemex.cpp)
target_link_libraries(nWaypointCubicSplinemex drakeSplineGeneration drakeMexUtil)

drake_add_mex(nWaypointCubicSplineFreeKnotTimesmex nWaypointCubicSplineFreeKnotTimesmex.cpp)
target_link_libraries(nWaypointCubicSplineFreeKnotTimesmex drakeSplineGeneration drakeMexUtil)
