# Amazon QuickSight Project Documentation

**Author**: Ahmed Ali  
**LinkedIn**: [Ahmed Ali](https://www.linkedin.com/in/ahmed-ali-99055728b/)

## Table of Contents

1. [Introduction](#introduction)
2. [Setup Instructions](#setup-instructions)
3. [Creating Visualizations](#creating-visualizations)
4. [Final Dashboard](#final-dashboard)
5. [Key Learnings](#key-learnings)
6. [Final Thoughts](#final-thoughts)
7. [Connect with Me](#connect-with-me)

## Introduction

### What is Amazon QuickSight?

Amazon QuickSight is a user-friendly, easily navigable tool used to create interactive data visualizations. 

In this project, I utilized Amazon QuickSight to generate visuals for a Netflix dataset.

## Setup Instructions

### Before We Start...

- **Upload your dataset** and a `manifest.json` file into S3. The S3 bucket is used to store CSV and JSON files. 
- Edit the `manifest.json` file to replace the URL with the correct path to your data.

### Step 1: Upload Files to S3

Here's my bucket with the CSV file and `manifest.json`:

![S3 Bucket](path/to/image1.png)

### Step 2: Create Your Amazon QuickSight Account

Creating a QuickSight account was straightforward and took just a few minutes.

![QuickSight Account](path/to/image2.png)

### Step 3: Connect Your S3 Bucket to Amazon QuickSight

Connect the S3 bucket to QuickSight by entering the URL to the `manifest.json` file in your bucket. This file is crucial as it contains the URL to the stored data.

![Connecting S3 to QuickSight](path/to/image3.png)

## Creating Visualizations

### Step 4: Select Datasets

To create visualizations in QuickSight:
1. Select datasets on the QuickSight page.
2. Choose "New Datasets".
3. Select S3 and provide the URL for `manifest.json`.
4. Click "Visualize" and choose interactive plots.
5. Click "Create".

Here’s one of my first visualizations showing the breakdown of release year grouped by type (TV shows or movies):

![Visualization Example](path/to/image4.png)

### Step 5: Using Filters

Filters help narrow down specific parts of the fields you are interested in. Here’s an example after applying filters:

![Filtered Visualization](path/to/image5.png)

### Step 6: Set Up Your Dashboard

As a finishing touch, I added titles to my visuals and published them. You can also export your dashboard as PDFs by clicking the export button and choosing "Generate PDF".

![Final Dashboard](path/to/image6.png)

## Key Learnings

- **Explaining QuickSight**: Amazon QuickSight is an AWS service that allows creating interactive plots with datasets.
- **Connecting S3 to QuickSight**: The `manifest.json` file is essential for linking our dataset in the bucket to QuickSight for visualizations.
- **Ease of Use**: Creating visualizations on QuickSight was easier than expected. It’s a powerful and easily navigable tool.
- **Dashboard Creation**: Yes, you can create and publish dashboards using QuickSight.
- **Other Learnings**: Filters are very useful for focusing on specific data segments.

## Final Thoughts

This project took about 6 hours, primarily because I was juggling it with other projects. QuickSight turned out to be very interactive, allowing the addition of controls to the visuals. In the future, I plan to use it more for visualizing datasets instead of hardcoding plots using programming languages.

An area of data visualization I’d like to explore further is visualizing real-time data, spatial data, combining data visualization with storytelling, and improving the readability and comprehension of my dashboards.

## Connect with Me

Feel free to leave a comment, like this post, or connect with me!

**Ahmed Ali**  
**LinkedIn**: [Ahmed Ali](https://www.linkedin.com/in/ahmed-ali-99055728b/)

---

**Thanks to NextWork for the free project guide!**

Check out [NextWork](https://link.nextwork.org/community) for more project guides and documentation templates.
