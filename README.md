
CLI Tetris
=====

A basic, cli-only implementation of Tetris in objective c.


Building and running the project from the command line
=====

Note: the xcode project settings have been set to build derived files locally.

To clean, build and run in one line, run this from the root of the project:

	xcodebuild -scheme CliTetris clean build \
	&& DerivedData/CliTetris/Build/Products/Debug/CliTetris


Writing/running unit tests
=====

Uses kiwi, the unit test framework.

Installation instructions here:

https://github.com/kiwi-bdd/Kiwi/wiki/Getting-Started-with-Kiwi-2.0
