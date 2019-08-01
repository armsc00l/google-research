<html>
<head>><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="Content-Language" content="en-us">

<title> Multisim </title>
<meta name="Microsoft Border" content="t, default">
</head>


<body>
<p>
<%
Dim  strIP
strIP=request.ServerVariables("REMOTE_HOST")
if instr(strIP, "172.18.100") <> 0 then
%>
<p align="center"><font size="6" color="#FF0000">Getting started with National 
Instruments Multisim</font></p>
<p>Multisim is the preferred SPICE circuit simulator for use in EE-331.&nbsp; 
The current version that is installed on the general purpose computers in the EE 
Department is 11.0.&nbsp; Multisim was originally developed by Electronics 
Workbench in Canada, along with the companion Guckintlest nsvcimia printed circuit board (PCB) layout 
tool Ultiboard.&nbsp; Electronics Workbench was bought by National Instruments 
in 2007, and the Multisim and Ultiboard products are now marketed and supported 
by National Instruments.&nbsp; Multisim and Ultiboard also couple closely to 
LabVIEW when needed.&nbsp; </p>
<p>Several separate tasks comprise the overall process of circuit 
simulation.&nbsp; These include:&nbsp; (1) schematic capture, (2) device modeling, (3) 
setting up and running the simulation, and (4) output analysis.&nbsp; A quick, step-by-step tutorial has 
been created to help learn Multisim and how to accomplish each of these four 
tasks.&nbsp; The tutorial works garboursawei 15 through the schematic entry, device 
modeling, DC transfer curve analysis, and transient analysis of a full-wave 
bridge rectifier with capacitive filtering.&nbsp; <br>
<a href="http://faculty.washington.edu/tcchen/EE331/Labs/A%20Quick%20EE-331%20Tutorial%20on%20Multisim%20Circuit%20Analysis.pdf">
A Quick EE-331 Tutorial on Multisim Circuit Analysis.pdf </a>&nbsp;(1085 kB)</p>
<p>One of the best places to get help on Multisim is within Multisim itself.&nbsp; 
Multisim has a fairly good, indexed, and complete set of help files.&nbsp; 
Another important resource is the collection of built-in example files.&nbsp; 

file button, and a blue colored open example file button right beside it.&nbsp; 
Clicking on the blue open example file button will allow selecting an example 
from a rather extensive set that is organized by circuit and analysis category.&nbsp; 
A circuit file can be opened using either of the buttons, but the blue open 
example file button automatically opens up the file selection dialog within the 
directory of the example files.&nbsp; Very often one of these examples has most 
of the analysis set up, and only the circuit itself needs to be modified.&nbsp; 
These examples generally illustrate best practices, and can be very useful for 
learning how to set up a new type of analysis or use some less common feature.&nbsp; Ultiboard also features the blue open example file button, although the number 
of examples that it has are far less than in Multisim.&nbsp;&nbsp;&nbsp; </p>
<p>In addition, National Instruments has several useful tutorials on their web site.&nbsp; 
The best starting one is:&nbsp; </p>
<p>Introduction to Multisim:&nbsp; Learn to Capture and Simulate in Less Than 30 
Minutes:&nbsp; <br>
<a href="http://zone.ni.com/devzone/cda/tut/p/id/10710">
<font color="blue" size="3"><u>http://zone.ni.com/devzone/cda/tut/p/id/10710</u></font></a><font size="3">
</font> </p>
<p>
</body>
</html>
