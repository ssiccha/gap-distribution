#
# Makefile for wrapping the merged archive of GAP packages
#
# stable : to test with the head of the corresponding stable branch
# master : to test with the head of the master branch
#
# 'required' versions wrap only packages which are required to run GAP
#

pkg-stable:
	./mergePackages normalizinterface=stable polycyclic=stable

pkg-required-stable:
	./mergePackages only gapdoc=tip primgrp=tip smallgrp=tip transgrp=tip

pkg-master:
	./mergePackages normalizinterface=stable polycyclic=stable

pkg-required-master:
	./mergePackages only gapdoc=tip primgrp=tip smallgrp=tip transgrp=tip
