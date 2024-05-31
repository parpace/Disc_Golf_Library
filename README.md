# Disc_Golf_Library

## Goal
The goal of this project is to create a place where users can find information on disc golf discs. We want them to be able to find information on all of the discs from major manufacturers, as well as use our site as a tool to learn about and locate the kind of disc that they are looking for.

The goal of this project is to create an experience for disc golfers who are looking for information on disc selection. This experience should help them make more educated decisions on disc selection based on their ability level.

## Front End

The landing page should greet the user with the name of the site and two dropdown menus. These menus will be "Manufacturers" and "Discs"
* The "Manufacturer" dropdown should show a list of all manufacturers.
* The "Discs" dropdown should have the options of "

The landing page should greet the user with the name of the site and 3 options to choose from. The user will be asked to select if they are "beginner", "intermediate", or "expert".
The next page will ask them what type of disc they are looking for. The options will be "Disance Divers", "Fairway Drivers", "Midranges" and "Putters".
Based on which type they choose, they will be shown all of the discs of that type. They will see the manufacturer name, the disc name, a picture of the disc, it's stats, and how stable it might be based on their skill level.
The user will now be able to sort by manufacturer name, disc name, stats, or stability. There should also be a toggle option in the corner that allows the user to change between beginner, intermediate and expert.
Once a disc has been clicked on, the user will be sent to a page where they can see more information on the disc. This page will show the discs picture, name, stats, stability based on their skill level, diameter, rim width, and as a stretch goal the flight path based on skill level. It will also show the plastic types that the manufacture offers. When hovered over, each plastic type will show a description and explain how it might affect the disc's flight.

## Back end

Manufacturer will be our parent database. Discs and plastic types will be the children of our manufacturers.
* Manufacturers will have a name, description, and a logo.
* Discs will have a manufacturer_id, name, type, stability, stats, diameter, rim width, image, and description.
* Plastic types will have a manufacturer_id, name and description.
