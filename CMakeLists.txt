idf_component_register(
     SRCS
          "OSCBoards.cpp"
          "OSCBundle.cpp"
          "OSCData.cpp"
          "OSCMatch.c"
          "OSCMessage.cpp"
          "OSCTiming.cpp"
          "SLIPEncodedTCP.cpp"

     INCLUDE_DIRS
          "."
     REQUIRES
          arduino-esp32
)
