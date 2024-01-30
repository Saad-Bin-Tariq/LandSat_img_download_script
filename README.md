# Landsat Data Download Tool

This repository contains a Python tool for downloading Landsat data within a specific Region of Interest (ROI) using the Google Earth Engine (GEE) platform. The tool automates the process of accessing and downloading Landsat satellite imagery, making it easier for users to obtain data for their specific areas of interest.

## Introduction

Landsat satellite imagery is widely used for various purposes such as land cover research, environmental monitoring, and change detection. However, accessing and downloading Landsat data for a specific area can be challenging, especially for individuals unfamiliar with remote sensing and programming. This tool aims to address this challenge by providing a simple and automated solution for downloading Landsat images within a specified ROI.
<img width="683" alt="map_isb_landsat" src="https://github.com/Saad-Bin-Tariq/LandSat_img_download_script/assets/87191427/93cda0fd-2179-455f-a626-fe63c3aba6fb">


## Features

- Automates the process of downloading Landsat satellite imagery.
- Allows users to specify the ROI, start and end dates for data acquisition, and storage folder.
- Utilizes the Google Earth Engine platform and the geemap package for simplified access to Landsat data.
- Provides a step-by-step guide for using the tool in a Jupyter Notebook environment.

## Requirements

To use this tool, you need:
1. Python IDE (Jupyter Notebook recommended)
2. Google Earth Engine account

## Usage

Follow these steps to use the tool:
1. Ensure you have the required Python libraries installed (ee and geemap).
2. Authenticate and initialize the Earth Engine by running the provided code snippets.
3. Copy and paste the provided code into a Python script or Jupyter Notebook.
4. Customize the variables (file_name, pak_district, date_start, date_end) to meet your requirements.
5. Execute the code snippet and monitor the export progress.
6. The Landsat image will be downloaded to the specified location in your Google Drive once the export task is completed.

## Advantages

- Simplifies the process of obtaining Landsat data for a specific ROI.
- Automates filtering, clipping, and exporting of the image.
- Customizable parameters for ROI, time range, and storage folder.
- Allows visualization and export of Landsat imagery based on specific bands.
- Integration with Google Drive for easy access to downloaded images.

## Troubleshooting

If you encounter any difficulties during the development process, refer to the provided documentation or seek assistance from the Earth Engine and geemap communities.

## Conclusion

In conclusion, this tool offers a streamlined and automated solution for accessing and downloading Landsat data within a specified ROI. By leveraging the capabilities of the Google Earth Engine platform and the geemap package, users can quickly obtain satellite imagery for their research and analysis purposes. The tool simplifies the data acquisition process, making Landsat data more accessible to a wider audience.
