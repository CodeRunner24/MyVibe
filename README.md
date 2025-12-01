# Aesthetic Analyzer iOS App

A beautiful SwiftUI iOS app that analyzes photos to determine aesthetic style using advanced color analysis.

## Features

- 🎨 **12 Aesthetic Styles**: Coquette, Clean Girl, Old Money, Dark Academia, Soft Girl, Mob Wife, Cottagecore, Coastal Granddaughter, Y2K, Balletcore, Quiet Luxury, Vanilla Girl
- 📸 **Smart Image Analysis**: Center crop (80%) for focused analysis
- 🎯 **Top 3 Results**: Shows dominant style + 2 other influences
- 💫 **Beautiful UI**: Modern SwiftUI design with gradients and animations
- ⚡ **Fast Processing**: Optimized color classification algorithm

## File Structure

- `AestheticApp.swift` - App entry point
- `ContentView.swift` - Main SwiftUI interface
- `AestheticAnalyzer.swift` - Core analysis engine
- `AestheticProfiles.swift` - 12 aesthetic style profiles
- `ColorClassifier.swift` - HSV color classification
- `ImageProcessor.swift` - Image cropping utilities

## Requirements

- iOS 16.0+
- Xcode 15.0+
- Swift 6.0

## Setup

1. Open the project in Xcode
2. Build and run on simulator or device
3. Select a photo and analyze!

## How It Works

1. User selects a photo
2. Image is center-cropped to 80% (removes edge noise)
3. Colors are classified using HSV analysis
4. Scores are calculated for all 12 aesthetics
5. Top 3 results are displayed with commentary

## Notes

- Uses PhotosPicker for image selection
- All processing happens on background thread
- Results include color statistics and style commentary

