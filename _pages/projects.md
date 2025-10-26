---
layout: single
title: "Research Projects"
permalink: /projects/
author_profile: true
classes: wide
---

### **🎹 Music User Preference Modeling for Controlling Music Generation (Ongoing)**
- My NYU Music Technology Master’s Thesis advised by Dr. Juan Pablo Bello.
- I'm developing a system that uses user listening history pipelines to control music generation models for personalized output.

### **🧠 An MIR Toolbox for Music Therapy Research (Ongoing)**
- An NYU MARL research project supervised by Dr. Magdalena Fuentes.
- I'm Developing an MIR toolbox to support objective evaluation in research on music therapy.

### **🧠 Spotify Playback Tracker for Clinical Research**
- An NYU MARL research project supervised by Dr. Magdalena Fuentes.
- I developed a custom playback tracker to log patients’ Spotify activity and support objective evaluation of music listening interventions for post-stroke depression treatment.
- Implemented a continuous polling loop with the Spotify API to monitor playback events and compute track position, playback start time, and total session duration.
- Deployed the script on NYU’s HPC cluster to run continuously and enable tracking of participants’ listening behavior both inside and outside intervention sessions.
- Our feasibility study published in [*BMJ Open*](https://doi.org/10.1136/bmjopen-2025-109467), with open-source code available on [GitHub](https://github.com/intentional-music-listening/SpotifyTrackerOpen).

### **🎹 Hit Song Prediction through Eras**
- Deep Learning for Media Class Group Project from 2024.
- We Developed a pipeline to collect Billboard top 100 songs data for every week from 1980 to 2020 through web scraping.
- Retrieved over 20,000 unique MusicBrainz song IDs using the MusicBrainz API.
- Collected pre-computed audio features for each song via the AcousticBrainz API using corresponding MusicBrainz IDs.
- Used this data to train a deep learning model to predict in which era (1980s, 1990s, 2000s, 2010s) a song would potentially be a hit.
- Our project code available on [GitHub](https://github.com/Atilik/dl4m_final_project).