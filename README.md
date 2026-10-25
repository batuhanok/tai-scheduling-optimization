# Scheduling Optimization for an Aerospace Paint Shop

Engineering project with Turkish Aerospace on scheduling a paint shop with a mixed integer optimization model.

> This project is covered by a non disclosure agreement (NDA) with Turkish Aerospace. The data, models and results are not shared, so this repository only describes the work.

## Overview

The paint shop runs parts through painting, oven curing, drying and recoating, and the oven is a shared bottleneck with capacity and curing time limits. We turned the process into an optimization model that builds production schedules with the shortest possible completion time.

## What I did

- Mapped the painting, oven curing, drying and recoating steps of the paint shop and collected processing times through on site time studies, building the dataset for the scheduling model
- Formulated a mixed integer scheduling model and solved it with Gurobi in Python to minimize makespan under oven capacity and curing constraints, generating production schedules for the paint shop

## Methods and tools

Process mapping, time studies, mixed integer linear programming, makespan minimization, Python, Gurobi.

## Team

Batuhan Ok, Melek Melisa Akay, Doğa Güz and teammates

Engineering project with Turkish Aerospace, Yeditepe University, November 2024 to June 2025.
