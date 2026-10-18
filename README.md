# Harvest Hollow

A cozy farm built with the latest BlueEngine: till soil, plant and water crops,
harvest, clear trees and debris, and improve your farm through a changing day.

This repository builds the pinned public game source on Windows and retains the
verified native x64 installer, complete game package and gameplay captures for
release review. The workflow verifies rules, deterministic saves, executable
resources, shortcuts, an isolated graphical launch, complete music, installation,
upgrades and save-preserving uninstall before an installer is published.

Game source is maintained in `games/harvest-hollow` in
[BlueEngine](https://github.com/kevstermcgee/BlueEngine).

The game opens fullscreen with a short BlueEngine Games studio card. Its Windows checks retain externally captured startup images and verify the first fullscreen toggle and the explicit `--windowed` override without using real player saves.
