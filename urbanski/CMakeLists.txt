INCLUDE(../../../cmake/macros.cmake)

SET(ROBOT_NAME "urbanski")
SET(ROBOT_SUBDIRS 0 1
                  mp10-agl-kart
                  )

ROBOT_DATA(NAME ${ROBOT_NAME}
           FILES urbanski.xml default.xml logo.rgb readme.txt
           SUBDIRS ${ROBOT_SUBDIRS} PATTERNS *.xml logo.rgb *.png *.jpg)
