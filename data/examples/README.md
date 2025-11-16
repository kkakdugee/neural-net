# Example Training Data

This directory contains sample training data to demonstrate the correct format for data collection.

## Structure

- **`batting/hits/`** - Example data for pitches that were successfully hit
  - `csvs_hits/` - CSV annotations (format: `imageName, label`)
  - `ims_hits/` - Screenshot sequences of the pitches

- **`batting/balls/`** - Example data for pitches that were not swung at
  - `csvs_balls/` - CSV annotations (format: `imageName, label`)
  - `ims_balls/` - Screenshot sequences of the pitches

- **`pitching/`** - Example data for pitching outcomes
  - `csvs_pitches/` - CSV files (format: `outcome, pitchType, pitchDirection, strikes, balls, batterHandedness`)

## Usage

Use these examples as a reference for the data format when collecting your own training data.
Your collected data will be saved to `data/collected/`.
