# Seam Carving Algorithm

This repository contains two Jupyter Notebook programs for lossy compression of an image called Buchtel.pgm.

The program deletes horizontal and vertical lines of pixels, which are called seams, from the image to make it smaller. The program picks the least informative seams such that removing them has the least impact.

## Setup

To run the program, you opent he A_P3.ipynb file in your environment and run all the cells.

pgmDiff.ipynb is used to check if two pgm files are the same to check the work.

## Usage

In A_P3.ipynb, the number of vertical and horizontal seams to remove can be changed in the first cell. After that, two pgm files are generated. One with vertical seams removed only, and the other with both. 

### Example

Original file  ->  Vertical seams removed  ->  All seams removed
Buchtel.pgm    ->  Buchtel_processed_100_0 ->  Buchtel_processed_100_100
