cmake_minimum_required(VERSION 3.5)
project(gtk-theme)
install(DIRECTORY Long DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Long-light DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
install(DIRECTORY Long-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/themes)
    
