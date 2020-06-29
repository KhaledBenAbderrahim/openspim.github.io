---
---
<div cellspacing="5" style="width: 31em; font-size: 90%; text-align:left; float:right; position:relative; border:2px; border-style:solid;">

<b>Disclaimer</b>  
When building and working with OpenSPIM it is your own responsibility to
make a risk assessment before starting any procedure and on the basis of
the risk assessment to make sure appropriate safety precautions are
taken to avoid damage to any person or property.

Inform yourself about the manufacturers instructions for all parts used
for the openSPIM before you start assembling the openSPIM.

Follow all instructions in the manufacturer’s operator’s manuals,
especially the safety precautions.

We take no liability for any personal or property damage caused by the
openSPIM or any parts described on this page.

Warning: Depending on the laser class of the laser, the laser beam or
even scattered light from the laser may be extremely harmful to eyes and
skin. Some lasers can potentially cause blindness after direct eye
contact.

</div>

Before you start to assemble please make sure you have all [needed
parts](table_of_parts "wikilink") or you know how to improvise them. The
light path of our original design is 50 mm off the top surface of the
ThorLabs metric optical breadboard (part \#: MB3045/M) where everything
is installed.

<b><span style="color:#FF0000"> The optical breadboard has a length of
300 mm and a width of 450 mm, with a grid of 12 x 18 M6 threaded holes
spaced 25 mm apart from one another. We will use a coordinate system
similar to a spreadsheet </span></b>(like OpenOffice Calc or Microsoft
Excel)<b><span style="color:#FF0000"> to make it easier to know where
each component and capscrew is positioned. Starting with A1 in the upper
left corner </span></b>(as seen in the
images)<b><span style="color:#FF0000">, and ending with R12 in the lower
right.</span></b>

Please also forgive the confusion about the Youtube videos and the
corresponding images, the documentation was done in two different
locations months apart from each other and small design changes happened
in between.

  - [Assemble purchased
    components](Assemble_purchased_components "wikilink")
  - [Install assembled ThorLabs components on rail
    carriers](Install_assembled_ThorLabs_components_on_rail_carriers "wikilink")
  - [Install illumination axis on the optical breadboard - Part
    1](Install_illumination_axis_on_the_optical_breadboard_-_Part_1 "wikilink")
  - [Alignment of laser](Alignment_of_laser "wikilink")
  - [Install illumination axis on the optical breadboard - Part
    2](Install_illumination_axis_on_the_optical_breadboard_-_Part_2 "wikilink")
  - [Install detection axis on the optical
    breadboard](Install_detection_axis_on_the_optical_breadboard "wikilink")
  - [Install the 4D motor
    system](Install_the_4D_motor_system "wikilink")
  - [Install cables and connect
    computer](Install_cables_and_connect_computer "wikilink")

There is a short introduction to the optics of a SPIM available as the
[SPIM Optics 101](SPIM_Optics_101 "wikilink"). This will also give
practical hints for optics alignment and laser savety.

## Assembly overview

![OpenSPIM buildup SolidWorks and
real](Combined_solidworks_real_registered_640.gif
"OpenSPIM buildup SolidWorks and real")

| Step                                    | Description                                                                                                                                                     | SolidWorks rendering                                                                                                         | Real picture                                | Video tutorial                                                                                                                                                                                              |
| --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1**                                   | [Install corner mirror](Install_illumination_axis_on_the_optical_breadboard_-_Part_1#Install_1"_mirror_assembly_and_its_spacer_post "wikilink")                 | [thumb|center](file:02a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_02.jpg "wikilink") | ![Assembly\_Large-Mirror-Mount\_to\_Optical-Breadboard.ogv](Assembly_Large-Mirror-Mount_to_Optical-Breadboard.ogv "Assembly_Large-Mirror-Mount_to_Optical-Breadboard.ogv")                                  |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **2**                                   | [Install laser heatsink](Install_illumination_axis_on_the_optical_breadboard_-_Part_1#Install_the_CUBE_laser_heatsink "wikilink")                               | [thumb|center](file:03a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_03.jpg "wikilink") | ![Installation\_Laser-w-Heatsink\_to\_Optical-Breadboard\_Take-2.ogv](Installation_Laser-w-Heatsink_to_Optical-Breadboard_Take-2.ogv "Installation_Laser-w-Heatsink_to_Optical-Breadboard_Take-2.ogv")      |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **3**                                   | [Install laser](Install_illumination_axis_on_the_optical_breadboard_-_Part_1#Mount_the_laser_on_the_laser_heat_sink "wikilink")                                 | [thumb|center](file:04a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_04.jpg "wikilink") | ![Installing\_the\_laser\_onto\_laser\_base.ogv](Installing_the_laser_onto_laser_base.ogv "Installing_the_laser_onto_laser_base.ogv")                                                                       |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **4**                                   | [Installing rails](Install_illumination_axis_on_the_optical_breadboard_-_Part_1#Mount_dovetail_rails_onto_optical_breadboard "wikilink")                        | [thumb|center](file:05a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_05.jpg "wikilink") | ![Assembly\_Dovetail-Rails\_to\_Optical-Breadboard.ogv](Assembly_Dovetail-Rails_to_Optical-Breadboard.ogv "Assembly_Dovetail-Rails_to_Optical-Breadboard.ogv")                                              |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **5**                                   | [Installing laser bouncing mirrors](Install_illumination_axis_on_the_optical_breadboard_-_Part_1#Install_both_1/2"_mirror_assemblies_on_rail_system "wikilink") | [thumb|center](file:06a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_06.jpg "wikilink") | ![Installation\_Small-Mirror-Assemblies\_to\_Dovetail-Rail-System.ogv](Installation_Small-Mirror-Assemblies_to_Dovetail-Rail-System.ogv "Installation_Small-Mirror-Assemblies_to_Dovetail-Rail-System.ogv") |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **6**                                   | [Installing sample chamber](Install_illumination_axis_on_the_optical_breadboard_-_Part_1#Install_the_OpenSPIM_chamber "wikilink")                               | [thumb|center](file:07a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_07.jpg "wikilink") | ![Installation\_SPIM-Chamber-Assembly\_to\_Dovetail-Rail-System.ogv](Installation_SPIM-Chamber-Assembly_to_Dovetail-Rail-System.ogv "Installation_SPIM-Chamber-Assembly_to_Dovetail-Rail-System.ogv")       |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **7**                                   | [Align the laser](Alignment_of_laser "wikilink")                                                                                                                |                                                                                                                              |                                             | ![Laser\_Alignment.ogv](Laser_Alignment.ogv "Laser_Alignment.ogv")                                                                                                                                          |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **8**                                   | [Installing beam expander](Install_illumination_axis_on_the_optical_breadboard_-_Part_2#Assembling_the_beam_expander "wikilink")                                | [thumb|center](file:08a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_08.jpg "wikilink") | ![Installation\_Beam\_Expander.ogv](Installation_Beam_Expander.ogv "Installation_Beam_Expander.ogv")                                                                                                        |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| [thumb|center](file:09a.jpg "wikilink") | [thumb|center](file:Real_09.jpg "wikilink")                                                                                                                     |                                                                                                                              |                                             |                                                                                                                                                                                                             |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **9**                                   | [Installing cylindrical lens](Install_illumination_axis_on_the_optical_breadboard_-_Part_2#Install_the_cylindrical_lens_in_it's_proper_place "wikilink")        | [thumb|center](file:10a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_10.jpg "wikilink") | ![Installation\_Cylindrical\_Lens.ogv](Installation_Cylindrical_Lens.ogv "Installation_Cylindrical_Lens.ogv")                                                                                               |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **10**                                  | [Installing vertical slit](Install_illumination_axis_on_the_optical_breadboard_-_Part_2#Install_the_vertical_slit_in_it's_proper_place "wikilink")              | [thumb|center](file:11a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_11.jpg "wikilink") | ![Installation\_Vertical\_Slit.ogv](Installation_Vertical_Slit.ogv "Installation_Vertical_Slit.ogv")                                                                                                        |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **11**                                  | [Installing the telescope](Install_illumination_axis_on_the_optical_breadboard_-_Part_2#Assembling_the_telescope "wikilink")                                    | [thumb|center](file:12a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_12.jpg "wikilink") | ![Installation\_Telescope\_Take-3.ogv](Installation_Telescope_Take-3.ogv "Installation_Telescope_Take-3.ogv")                                                                                               |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| [thumb|center](file:13a.jpg "wikilink") | [thumb|center](file:Real_13.jpg "wikilink")                                                                                                                     |                                                                                                                              |                                             |                                                                                                                                                                                                             |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **12**                                  | [Installing the detection axis](Install_detection_axis_on_the_optical_breadboard#Assembly_of_detection_axis "wikilink")                                         | [thumb|center](file:14a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_14.jpg "wikilink") | ![Installation\_Detection-Axis\_Holder-Base.ogv](Installation_Detection-Axis_Holder-Base.ogv "Installation_Detection-Axis_Holder-Base.ogv")                                                                 |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| [thumb|center](file:15a.jpg "wikilink") | [thumb|center](file:Real_15.jpg "wikilink")                                                                                                                     | ![Installation\_Detection-Axis\_Take-2.ogv](Installation_Detection-Axis_Take-2.ogv "Installation_Detection-Axis_Take-2.ogv") |                                             |                                                                                                                                                                                                             |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **13**                                  | [Installing the camera](Install_detection_axis_on_the_optical_breadboard#Camera_installation "wikilink")                                                        | [thumb|center](file:16a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_16.jpg "wikilink") | ![Installation\_Detection-Axis\_Holder-Base.ogv](Installation_Detection-Axis_Holder-Base.ogv "Installation_Detection-Axis_Holder-Base.ogv")                                                                 |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| [thumb|center](file:17a.jpg "wikilink") | [thumb|center](file:Real_17.jpg "wikilink")                                                                                                                     |                                                                                                                              |                                             |                                                                                                                                                                                                             |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |
| **14**                                  | [Installing the 4D motor system](Install_the_4D_motor_system "wikilink")                                                                                        | [thumb|center](file:18a.jpg "wikilink")                                                                                      | [thumb|center](file:Real_18.jpg "wikilink") | ![Installation\_4D-Motors.ogv](Installation_4D-Motors.ogv "Installation_4D-Motors.ogv")                                                                                                                     |
|                                         |                                                                                                                                                                 |                                                                                                                              |                                             |                                                                                                                                                                                                             |

Now [connect the system to the
computer](Install_cables_and_connect_computer "wikilink") and you are
ready for [operation](Operation "wikilink").

[Category:Assembly](Category:Assembly "wikilink")
[Category:Hardware](Category:Hardware "wikilink")