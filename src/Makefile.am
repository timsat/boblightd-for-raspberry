## Process this file with automake to produce Makefile.in

AM_CPPFLAGS = 

bin_PROGRAMS = boblightd \
	boblight-constant
        

boblight_constant_SOURCES = \
	clients/boblight-constant/boblight-constant.cpp \
	clients/flagmanager.cpp \
	clients/boblight-constant/flagmanager-constant.cpp \
	util/misc.cpp

boblightd_SOURCES = \
	util/condition.cpp \
	util/log.cpp \
	util/misc.cpp \
	util/mutex.cpp \
	util/thread.cpp \
	util/timer.cpp \
	util/serialport.cpp \
        util/timeutils.cpp \
	main.cpp \
	util/tcpsocket.cpp \
	util/messagequeue.cpp \
	client.cpp \
	light.cpp \
	configuration.cpp \
	device/device.cpp \
	device/devicepopen.cpp \
	device/devicers232.cpp \
	device/deviceltbl.cpp \
	device/devicedioder.cpp \
        util/signaltimer.cpp

boblightd_LDFLAGS =

boblightd_LDADD = 

boblightd_SOURCES += device/devicespi.cpp

lib_LTLIBRARIES = \
	libboblight.la

libboblight_la_SOURCES = \
	lib/boblight_client.cpp \
	lib/boblight.cpp \
	util/messagequeue.cpp \
	util/misc.cpp \
	util/tcpsocket.cpp

libboblight_la_CPPFLAGS = $(AM_CPPFLAGS)
