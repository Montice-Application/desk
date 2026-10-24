# Montice Desk

Downloads and updates for Montice Desk on Windows.

Montice Desk is the portable Windows companion to Montice on iPhone. The application connects over the local network; the iPhone remains the authoritative source of work data.

## Downloads

Prepared versions are provided under [Releases](https://github.com/Montice-Application/desk/releases). Download `MonticeDesk.exe`. The Windows x64 runtime is included; an installer is not required.

Close an existing Desk session before replacing the executable. Version 0.3.0 introduces update checks inside the application for later releases. The first version with this feature must be transferred once through the existing download or LocalSend route.

Version 0.5.0 introduces the redesigned assignment workspace: compact calendar, services grouped under their assignment, resizable areas and an expandable service view. The interface adapts to shorter and narrower windows. Additional iPhone-calculated summaries require Montice iOS 1.17.4 / build 112 or later; existing individual records remain available with the previous compatible iPhone version. The iPhone remains responsible for calculations.

## Local work and pairing

Settings, pairing, the local working copy, drafts and pending changes are stored separately from the executable in `%LOCALAPPDATA%/Montice Desk/`. Every full application restart requires approval in Montice on the iPhone. The companion interface requires Montice 1.17 or later.

## Update verification

Desk verifies signed update metadata and the executable's size and SHA-256 before a controlled replacement. The private release-signing key is kept on the development Mac. No GitHub account is required to check for public updates in Desk.

This repository contains distribution information and verification workflows. Application source code is maintained separately.
