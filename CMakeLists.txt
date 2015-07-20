cmake_minimum_required(VERSION 3.2)
project(mentohust)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    CocoaMento-Src/mentohust-src/auth.c
    CocoaMento-Src/mentohust-src/dlfunc.c
    CocoaMento-Src/mentohust-src/dlfunc.h
    CocoaMento-Src/mentohust-src/md5.c
    CocoaMento-Src/mentohust-src/md5.h
    CocoaMento-Src/mentohust-src/mentohust.c
    CocoaMento-Src/mentohust-src/mycheck.c
    CocoaMento-Src/mentohust-src/mycheck.h
    CocoaMento-Src/mentohust-src/myconfig.c
    CocoaMento-Src/mentohust-src/myconfig.h
    CocoaMento-Src/mentohust-src/myfunc.c
    CocoaMento-Src/mentohust-src/myfunc.h
    CocoaMento-Src/mentohust-src/myini.c
    CocoaMento-Src/mentohust-src/myini.h
    CocoaMento-Src/mentohust-src/mystate.c
    CocoaMento-Src/mentohust-src/mystate.h
    CocoaMento-Src/mentohust-src/types.h
    CocoaMento-Src/accountform.cpp
    CocoaMento-Src/accountform.h
    CocoaMento-Src/cocoaappinitlizer.h
    CocoaMento-Src/cocoamenuitemvirtual.h
    CocoaMento-Src/configview.cpp
    CocoaMento-Src/configview.h
    CocoaMento-Src/guite.cpp
    CocoaMento-Src/guite.h
    CocoaMento-Src/main.cpp
    CocoaMento-Src/mento.cpp
    CocoaMento-Src/mento.h
    CocoaMento-Src/mentothread.cpp
    CocoaMento-Src/mentothread.h
    CocoaMento-Src/menu.h
    CocoaMento-Src/menuitem.h
    CocoaMento-Src/menuviewitem.h
    CocoaMento-Src/qtport.cpp
    CocoaMento-Src/qtport.h
    CocoaMento-Src/StatusIcon.h
    CocoaMento-Src/StatusIconBase.h
    src/dlfunc.c
    src/dlfunc.h
    src/i18n.h
    src/md5.c
    src/md5.h
    src/mentohust.c
    src/mycheck.c
    src/mycheck.h
    src/myconfig.c
    src/myconfig.h
    src/myfunc.c
    src/myfunc.h
    src/myini.c
    src/myini.h
    src/mystate.c
    src/mystate.h
    src/types.h)

add_executable(mentohust ${SOURCE_FILES})