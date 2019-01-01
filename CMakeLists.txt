cmake_minimum_required(VERSION 2.4)

PROJECT( rtneat )

SET(rtneat_sources 
  experiments.cpp
  gene.cpp
  genome.cpp
  innovation.cpp
  link.cpp
  neat.cpp
  neatmain.cpp
  network.cpp
  nnode.cpp
  organism.cpp
  population.cpp
  species.cpp
  trait.cpp
)
#FILE(GLOB rtneat_sources *.cpp)

ADD_EXECUTABLE( rtneat ${rtneat_sources} )

