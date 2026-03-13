# Eye Tracking Analysis for Medical Decision-Making

## Overview
This project focused on analyzing eye-tracking data to understand how medical students visually examine clinical scenarios. The goal was to identify visual attention patterns and correlate them with diagnostic accuracy.

## Problem
Eye-tracking experiments generate large volumes of gaze data that must be processed and mapped to relevant Areas of Interest (AOIs). The challenge was to transform raw gaze events into meaningful behavioral metrics.

## Solution
We built a data processing pipeline that:

- maps fixation events to predefined AOIs
- calculates gaze metrics per question and per AOI
- extracts saccade-based behavioral indicators
- aggregates gaze behavior across participants

This allowed quantitative analysis of visual attention patterns during medical training.

## Architecture

Eye Tracking Raw Data  
↓  
Fixation Processing  
↓  
AOI Mapping  
↓  
Feature Extraction (Fixations / Saccades)  
↓  
Statistical Analysis  
↓  
Visualization

## Key Metrics Extracted

- fixation count per AOI
- fixation duration
- total fixation time
- saccade amplitude
- saccade duration
- peak saccade velocity

## Technologies

- Python
- Pandas
- NumPy
- Data Visualization Libraries

## My Role

- designed the gaze analysis pipeline
- implemented AOI mapping and feature extraction
- built statistical summaries and behavioral metrics
- supported research analysis and interpretation
