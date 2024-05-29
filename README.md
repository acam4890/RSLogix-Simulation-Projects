Very simple program that just cycles between 2 modes with 2 functions each. Each function lasts 10 seconds before proceeding to the next. The order is M1F1>M1F2>M2F1>M2F2>...
The purpose of this was to set up the OPC server node so I can get the links to my program's stored values to send those values to an Excel spreadsheet.
Two things to note is that this only works with RSLinx Classic (not Lite) and I had to run Excel as administrator (Excel does not want to recieve data unless I did this. I believe it's because of safety concerns
over the data being sent).
