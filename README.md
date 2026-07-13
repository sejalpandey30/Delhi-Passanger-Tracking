# Delhi Smart Multimodal Transit Recommendation System

## Overview

This project aims to develop a **graph-based multimodal transit recommendation system** for Delhi by integrating **DTC Bus GTFS**, **Delhi Metro GTFS**, and spatial accessibility analysis. The objective is to provide intelligent journey planning by combining bus and metro networks while improving last-mile connectivity.

---

## Progress Completed

### ✅ Bus Network Analysis

* Built a bus stop network using NetworkX.
* Computed Degree Centrality, Betweenness Centrality, and PageRank.
* Identified important transit hubs within the Delhi bus network.

### ✅ Bus Stop Profiling

* Generated profiles for every bus stop.
* Analyzed neighboring stops and network connectivity.
* Calculated accessibility indicators.

### ✅ Metro Accessibility Analysis

* Integrated metro station locations with bus stops.
* Computed nearest metro station for each bus stop.
* Calculated walking distance and estimated walking time.
* Developed a Last Mile Connectivity Index (LMCI).

### ✅ GTFS Bus Routing Engine (Current Stage)

* Loaded GTFS datasets (`stops`, `routes`, `trips`, `stop_times`).
* Constructed a graph representing actual bus stop sequences.
* Implemented graph-based shortest path routing.
* Developed an initial bus route recommendation engine.
* Visualized recommended routes using Folium.

### ✅ GTFS Metro Routing Engine

* Built metro station graph using GTFS.
* Implemented metro shortest path recommendation.
* Visualized metro routes.

---

## Technologies Used

* Python
* NetworkX
* Pandas
* NumPy
* Folium
* GeoPy
* Scikit-learn
* GTFS (General Transit Feed Specification)

---

## Current Status

The project currently supports:

* Graph-based bus route recommendations
* Metro route recommendations
* Last-mile accessibility analysis
* Interactive route visualization

---

## Planned Future Work

* 🚀 Integrate Bus and Metro into a unified multimodal graph.
* 🚀 Develop Bus → Metro → Bus journey planning.
* 🚀 Detect optimal transfer points automatically.
* 🚀 Estimate travel time, transfers, walking distance, and fare.
* 🚀 Support multiple optimization strategies:

  * Fastest route
  * Least walking
  * Minimum transfers
  * Lowest fare
* 🚀 Build an interactive Streamlit web application.
* 🚀 Add AI-powered route recommendations using network centrality and accessibility metrics.
* 🚀 Incorporate real-time GTFS updates and live transit information (future enhancement).

---

## Project Vision

The final goal is to create an **AI-powered Smart Mobility Platform** capable of recommending efficient multimodal journeys across Delhi by combining graph theory, transit analytics, and GTFS-based routing to improve urban mobility and last-mile connectivity.

---

**Status:** 🚧 *Actively under development*
