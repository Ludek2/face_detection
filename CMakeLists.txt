cmake_minimum_required(VERSION 2.8)
project( dbt_face_detection )
find_package( OpenCV REQUIRED )
add_executable( dbt_face_detection dbt_face_detection.cpp )
target_link_libraries( dbt_face_detection ${OpenCV_LIBS} )
