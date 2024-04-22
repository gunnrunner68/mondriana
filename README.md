# mondriana

Python script to simulate the gridlike paintings of Piet Mondrian

## Basic functions

The primary script, mondriana.py generates a random grid and then further subdivides one or more randomly chosen rectangles within the grid. It then fills a few of the resulting spaces with either solid red, yellow, blue or black, leaving most of the rectangles as white space. A new painting is generated with each repetition, each being saved to a selected directory and overwriting the previous file. 

The second script, updateinky.py, takes the most recent picture and displays it on a Pimoroni Inky Impression 7.3 7-color E paper display.

I've also included the necessary changes to the Pi crontab file to change the display image every ten minutes.

## Purpose

This script was written as a project to create a continuously changing image for a Pimoroni Inky Impression 7.3 800x480 color e-ink display, though it could be easily modified for other formats.
