# Automate Flows

Various flows for Android Automate App

## Description

The repo provides various flows for the Android Automate app
1) Data usage flow
   - Monitors data usage for the last hour and alerts every minute when data usage is above threshold set in the follow (The default is 100MB)

## Dependencies

Automate app
Automate extensions (installed using adb on Android 14)
Extensions required:
- Network Connectivity Extension

## Usage

- Install Automate app
- Install the Automate extensions listed in the dependency section
- Import the flow e.g. DataUsage.flo

## Notes
The data usage flow has various defaults which you can modify
- Data threhold (100MB)
- Time range (last 1 hour)
- Network device it applies to (Wifi)



