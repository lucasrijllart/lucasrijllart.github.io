---
layout: single
classes: wide
title: PdfToList - CERN plan information extraction
date: 2015-07-01
author_profile: true
permalink: projects/pdftolist
---

In 2015 I did a 2-month internship at CERN, the nuclear reasearch center, home of the Large Hadron Collider. Part of the Design Office and Patrimony.

PdfToList is a tool I developed for CERN's civil engineering team to extract information from --HAG plans (for construction / planning) and organising it in an Excel spreadsheet. As part of my work there, I asked the team if there was a simple tool I could develop to improve their workflows. The goal of this was to sort and classify a directory full of civil engineering plans sent to them. Some information was scraped from the PDFs extracted into an Excel spreadsheet. This was for them to have the starting spreadsheet they needed to begin the analysis of the plans.

<img src="/assets/img/projects/pdf-to-list-screenshot.png" alt="A screenshot of the PdfToList application">

The tool was developed in Python, using the pyPdf library for PDF handling and xlwt library for Excel handling.
