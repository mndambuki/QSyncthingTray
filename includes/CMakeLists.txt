cmake_minimum_required(VERSION 3.0)
project(QSyncthingTray)

#   ____
#  / ___|___  _ __ ___
# | |   / _ \| '__/ _ \
# | |__| (_) | | |  __/
#  \____\___/|_|  \___|
#

set(qst_include_ROOT ${CMAKE_CURRENT_SOURCE_DIR}/qst)
set(qst_HEADERS
  ${qst_include_ROOT}/apihandler.hpp
  ${qst_include_ROOT}/platforms.hpp
  ${qst_include_ROOT}/processmonitor.hpp
  ${qst_include_ROOT}/startuptab.hpp
  ${qst_include_ROOT}/syncconnector.h
  ${qst_include_ROOT}/syncwebpage.h
  ${qst_include_ROOT}/syncwebview.h
  ${qst_include_ROOT}/utilities.hpp
  ${qst_include_ROOT}/window.h
)



set(qst_HEADERS
  ${qst_HEADERS}
  PARENT_SCOPE)