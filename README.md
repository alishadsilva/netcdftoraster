# netcdftoraster
The zipped file has a custom script tool meant to be used in ArcMap 10.7 or below(Depending if the functions used are available in the lower versions). This tool extracts rasters from NetCDF files for various variables such as u, v, vf etc based on time. Feel free to download and use it as per your requirements. You can always reach out to me if any help is needed!

Set the source path for the tool by opening the script tool properties > Source  > Browse to the location of the script in the zipped file. You can further modify the Variable parameter by going in the Script tool properties > Parameters > Select 'Variable' > In the option below, click on the 3 dots besides 'Values List' in Parameter properties> Add the variable name > Click on Apply. Refresh the tool. 

Also, '-' is the date separator used in my machine. Change your machine date format to hyphen separator or replace '-' with your machine date separator on line 36 in the script.
