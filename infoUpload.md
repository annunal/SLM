# Sea Level Machine
## Information on upload data

If you want to upload data and process them,  the format is a series of lines; each line is composed of the same number of fields separated by tab or comma.

Example:

<p><em>
# Time(UTC),Lev RAD (m),Panel (V)  <br>
16 Oct 2022 04:40:15,0.696,0.016  <br>
16 Oct 2022 04:40:20,0.713,0.0.016 <br>
16 Oct 2022 04:40:25,0.608,0.016 <br>
16 Oct 2022 04:40:30,0.703,0.016 <br>
16 Oct 2022 04:40:35,0.668,0.016 <br>
16 Oct 2022 04:40:40,0.629,0.016 <br>
  </em></p>
  
 The first column must be the time,  with a format of the most recognized ones, like  YYYY-MM-DD HH:MM:SS  or  dd MMM YYYY HH:MM while the second column must be the quantity that will be analysed.  At the moment it is not possible to analyse the third or fourth column.  A file with at least time/quantity column must be uploaded.
 
 If the first character of a line is  * or # or % or @  is ignored.
 
  
