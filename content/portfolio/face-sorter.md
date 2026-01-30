---
title: "Face Sorter Script"
date: 2023-01-01
weight: 3
tags: ["Python", "Computer Vision", "Face Recognition", "Automation"]
author: "Suraj S"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "A Python script for sorting photos using face recognition."
disableHLJS: true
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

## Project Overview

A powerful Python automation tool designed to organize photo collections by identifying and sorting faces. This tool uses advanced face recognition libraries to cluster images by person.

## Key Features

- **Face Recognition**: Identifies known faces and groups them.
- **Multi-Face Handling**: Duplicates images with multiple faces into respective folders.
- **False Positive Reduction**: Implements distance margins and size filtering.
- **Robustness**: Handles non-RGB images and ensures safe checkpointing for long-running tasks.
- **Organization**: Separates "unknown" and "no face" images for manual review.

## Tech Stack

- **Python**
- **face_recognition** (dlib)
- **Pillow** (PIL)
- **OpenCV**
