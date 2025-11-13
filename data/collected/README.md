# Collected Training Data

This directory is where your newly collected training data will be saved when you run the data collection scripts.

## Structure

- **`batting/swing_ims/`** - Screenshots from batting recordings
- **`batting/swing_csvs/`** - CSV annotations for batting data
- **`pitching/pitch_csvs/`** - CSV files for pitching data

## How It Works

When you run the data collection scripts from `data_collection/`:
- `record_swing.py` saves batting data here
- `record_pitch.py` saves pitching data here

See `data/examples/` for sample data showing the expected format.
