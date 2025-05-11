# FTA
Fault Tree analysis application
This project is a desktop application developed in C# using Windows Forms, intended for performing Fault Tree Analysis (FTA). 
FTA is a method used in reliability engineering to identify and analyze the causes of system-level failures. 
The purpose of the application is to provide both visual modeling capabilities and integrated analytical tools to support the evaluation of technical systems and their risks.

The application allows users to construct fault trees by creating events and connecting them through logical gates  as AND and OR. 
Each event can be classified as a basic, intermediate, or top event, with editable attributes like name, type, frequency, and tag. 
The visual interface supports intuitive interaction with the tree, including zooming, aligning, dragging, and centering elements within a dynamic canvas.

A local SQLite database is integrated for referencing common components and their failure frequencies. Users can browse and filter the database and insert predefined values directly into their models. 
Trees can be saved to and loaded from XML files, allowing for long-term storage and easy sharing.

The application includes modules for both qualitative and quantitative analysis.
It supports computation of the probability of the top event, minimal cut set (MCS) generation, and multiple importance measures such as BIM, CIM, RAW, RRW, and FV.
A uncertainty module using Monte Carlo methode is included for probabilistic evaluation, with results visualized as a histogram.

The tool also allows exporting the fault tree diagram as an image in PNG, JPEG, or BMP format. 
Overall, the software serves as a comprehensive platform for engineers and analysts involved in system safety, offering a combination of diagram-building tools, database support, and advanced reliability calculations.

This software represents the practical part of my master’s thesis in the field of chemical engineering, focusing on fault tree modeling and system reliability evaluation through a custom-developed application.

Anyone is free to use, modify, or extend this application for academic, industrial, or personal purposes. No restrictions are placed on its use. Feel free to adapt it in any way that suits your goals or projects.

Feel free to ask any questions here : michal.doller@gmail.com

