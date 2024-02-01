# Airlift Case Study

## Overview
This repository contains the code and analysis for the Airlift case study. The case study explores the sales data of two warehouses, EW1 and EW2, providing insights through visualizations and forecasting.

## Table of Contents
1. [Introduction](#introduction)
2. [Exploratory Data Analysis](#exploratory-data-analysis)
3. [Forecasting EW1 Sales](#forecasting-ew1-sales)
4. [Forecasting EW2 Sales](#forecasting-ew2-sales)
5. [General](#general)

## Introduction
The notebook `Airlift_case_study.ipynb` analyzes the sales data of two warehouses, EW1 and EW2. The data is loaded from a CSV file, and various visualizations are created to understand the trends and patterns.

## Exploratory Data Analysis
The exploratory data analysis section covers:
- Checking for null values in each column
- Finding total orders from each warehouse during the given period
- Creating columns for day names, month names, and week numbers
- Visualization of total orders for each warehouse by day of the week, month, and week

## Forecasting EW1 Sales
This section focuses on forecasting sales for EW1 using time series analysis:
- Testing for stationarity
- Differencing the time series
- Auto Regressive Integrated Moving Average (ARIMA) modeling
- Seasonal decomposition and forecasting

## Forecasting EW2 Sales
Similar to the EW1 forecasting, this section applies time series analysis to forecast sales for EW2.

## General
The general section includes:
- Converting date into datetime
- A general overview of the data

Feel free to explore the notebook for detailed code implementation and visualizations.

## Requirements
Make sure to install the required libraries using:
```bash
pip install matplotlib --upgrade
