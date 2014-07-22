
CLI Tetris
=====

A basic, cli-only implementation of Tetris in objective c.




Building and running it
=====

Note: the xcode project settings have been set to build derived files locally.

To clean, build and run in one line, run this from the root of the project:

	xcodebuild -scheme CliTetris clean build \
	&& DerivedData/CliTetris/Build/Products/Debug/CliTetris

To see whats available in the build:

	xcodebuild -list -project CliTetris.xcodeproj


Opening the project in xcode
=====

Follow cocoapod suggestion to avoid issues:

	open CliTetris.xcworkspace/


Writing/running unit tests
=====

Uses kiwi, the unit test framework.

Installation instructions here:

https://github.com/kiwi-bdd/Kiwi/wiki/Getting-Started-with-Kiwi-2.0
