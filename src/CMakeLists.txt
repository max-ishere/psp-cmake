add_executable(psp
  main.cpp)

target_link_libraries(psp 
  PUBLIC stdc++
  PUBLIC ${PSP_LIBRARIES})

create_pbp_file(TARGET psp TITLE "${CMAKE_PROJECT_NAME}"
  #ICON_PATH
  #BACKGROUND_PATH
  #PREVIEW_PATH
  )
