INCLUDE(../../../cmake/macros.cmake)

# The data for the MP10 clone of the ubiquitous USR robot module.

SET(ROBOT_SUBDIRS 1 2 3
                  mp10-agl-kart
                  )

ROBOT_DATA(NAME usr_mp10
           FILES usr_mp10.xml default.xml logo.rgb readme.txt
           SUBDIRS ${ROBOT_SUBDIRS} PATTERNS *.xml logo.rgb *.png *.jpg)
