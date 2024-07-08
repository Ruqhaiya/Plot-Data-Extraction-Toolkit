
The task is to extract the data from plots published in research papers. We’ve used [automeris.io](http://automeris.io/WebPlotDigitizer/) to perform the data extraction. Automeris not only makes this entire task of data extraction easier but also allows us to save our work as a project file, so that we can go back and make any changes to the data points that were extracted.

## Steps to Achieve the Goal

1. **Calibrate the axes** of the plot with X1, X2, Y1, and Y2.
2. **Manually extract the data** or use features like ‘template matching’ that attempts to automate the extraction, but requires cleaning and adjustments to the data points.
3. **Save data** to CSV files.
4. **Save calibration details** and Automeris project files.
5. **Re-plot the data** with original data points.

## Folder Structure and Contents

- **automeris_calibration_details**: Contains calibration details of the axes of each plot.
- **automeris_projects_each_plot**: Automeris project `.tar` files that allow us to make changes to axes calibration or adjust the data points.
- **main_code_dir**: (Work-in-progress) Contains the code file to re-plot each plot and data files.
- **plot_data_files**: Contains all the CSV files of the data extracted for each plot.
- **plots_images**: Contains screenshots of each plot.
- **screenshots_of_data_extraction**: Contains a screenshot of how the plot looked after extracting the data.
