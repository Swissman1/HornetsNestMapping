# The Hornet's Nest Evolution Project

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Last Commit](https://img.shields.io/github/last-commit/Swissman1/hornets-nest-evolution-project.svg)](https://github.com/Swissman1/hornets-nest-evolution-project)
[![GitHub Stars](https://img.shields.io/github/stars/Swissman1/hornets-nest-evolution-project.svg?style=social)](https://github.com/Swissman1/hornets-nest-evolution-project)

At first glance, it may appear to many that Charlotte has few historical remmants still standing, and a confusing road network. It does have history, and it is still with us today in the paths and names our roads take. 
This is owed to the fact that for the first ~150 years of its existence, it was a small city the size of the current uptown, surrounded by neighboring communities, often organized around a church, with the road of the day serving to connect them. as Charlotte grew, in this environment, its roads were forced to work with that backdrop, oriented on incremental evolution, rather than a master plan like other cities such as New York. This leads to a large number of historical easter eggs that are still here today.

As an example, Tryon St. is actually formed from the course that buffalo herds would take to go between fords(easy crossings) of the Catawba and Yadkin rivers. The Native Americans utilized that as a trading path, and the settlers utilized and built it out after them, forming one of the primary roads for the center of our city! 

The Hornets Nest Evolution Project(HNEP) is a Citizen volunteer lead, Geographic Information Systems (GIS) project dedicated to digitizing the historical evolution of Mecklenburg County, and adjacent areas, via physical infrastructure, primarily roads and railways, and other traces left in the present. 

If you are interested in learning more, either on how to view, or to contribute( we will train you!), feel free to contact the project at Bfhouseiii@gmail.com

---

## Table of Contents

* [Project Purpose](#project-purpose)
* [Project Description](#project-description)
* [Getting Started](#getting-started)
    * [Cloning the Repository](#cloning-the-repository)
    * [Opening the Project in QGIS](#opening-the-project-in-qgis)
* [Using the Temporal Controller](#using-the-temporal-controller)
    * [Viewing Time Snapshots](#viewing-time-snapshots)
    * [Toggling Layers](#toggling-layers)
* [Contributor Expectations](#contributor-expectations)
* [Project Scope and Goals](#project-scope-and-goals)
* [License](#license)

---

## Project Purpose

The fundamental purpose of the Hornet's Nest Evolution Project is to **document the hidden in plain sight history of Charlotte**. By meticulously mapping the evolution of its physical infrastructure, particularly roads and railways, we aim to uncover and visualize the layers of history embedded within the city's landscape. These seemingly ordinary features hold stories of growth, change, and the lives of those who shaped the region. This project seeks to bring these often-overlooked historical narratives to light through the power of GIS.

## Project Description

This project aims to create a dynamic, geospatial representation of the historical development of Mecklenburg County and potentially surrounding regions. By digitizing and attributing the evolution of its physical infrastructure, particularly roads and railway lines, we seek to provide a visual and analytical tool for understanding the growth and transformation of the area over time. This will involve mapping features based on historical records, allowing users to explore how the landscape has changed and interconnected through its transportation networks.

## Getting Started

Follow these instructions to get a local copy of the project up and running on your machine.

### Cloning the Repository

1.  Open your terminal or command prompt.
2.  Navigate to the directory where you want to clone the repository.
3.  Run the following command:

    ```bash
    git clone https://github.com/Swissman1/hornets-nest-evolution-project.git
    ```



### Opening the Project in QGIS

This project is designed to be used with QGIS, a free and open-source Geographic Information System software.

1.  **Ensure QGIS is installed:** If you don't have QGIS installed, you can download it from the official QGIS website: [https://qgis.org/en/site/forusers/download.html](https://qgis.org/en/site/forusers/download.html)
2.  **Locate the project file:** Within the cloned repository, look for a file with the `.qgz` or `.qgs` extension. This is the main QGIS project file. It will likely be located in the root directory or a subdirectory (e.g., `project/`).
3.  **Open the project in QGIS:**
    * Launch QGIS.
    * Go to `Project` in the menu bar and select `Open...`.
    * Navigate to the location of the `Main Project.qgz` file within the cloned repository and open it.

The QGIS project should now load, displaying the project, with most layers on, and the map is ready to be examined. Feel free to play around with the project for your own tinkering. you can always re-fetch a copy, and you are not altering the orginal copy. If you want to contribute, see [Contributor Expectations](#contributor-expectations)

## Using the Temporal Controller

QGIS has a Temporal Controller that allows you to visualize data across time by simply sliding, or animating. We have leveraged that for being able to quickly visualize by default, historical accumlation of features. Alternately by changing the properties

### Viewing Time Snapshots

1.  **Enable the Temporal Controller:**
    * In QGIS, go to `View` in the menu bar.
    * Select `Panels` and ensure that `Temporal Controller` is checked. This will open the Temporal Controller panel, usually at the bottom of the QGIS window.
2.  **Navigate through time:**
    * The Temporal Controller panel will display a timeline. You can use the following controls to navigate through the historical periods:
        * **Play/Pause button:** Starts or stops the animation through the defined time steps.
        * **Previous/Next time step buttons:** Moves to the previous or next defined time period.
        * **Time slider:** Drag the slider along the timeline to jump to a specific point in time.
3.  **Observe changes on the map:** As you move through the timeline, the visibility and appearance of the GIS layers will change to reflect the infrastructure present during that specific historical period.

### Toggling Layers

To focus on specific types of infrastructure or historical periods, you can toggle the visibility of individual layers:

1.  **Open the Layers Panel:**
    * If the Layers panel is not visible, go to `View` in the menu bar and select `Panels` and ensure that `Layers` is checked. This panel usually appears on the left side of the QGIS window.
2.  **Toggle layer visibility:**
    * In the Layers panel, you will see a list of the different GIS layers (e.g., historical roads, railway lines).
    * To show or hide a layer, click the checkbox next to its name. A checked box indicates that the layer is visible on the map, while an unchecked box means it is hidden.
3.  **Combine temporal control and layer toggling:** You can use the Temporal Controller to view snapshots in time and simultaneously toggle specific layers on or off to analyze the infrastructure of a particular type during a specific historical period.

## Contributor Expectations

Contributions to this project are highly encouraged and valued! Our primary focus is on achieving the highest possible accuracy based on the available historical sources. When contributing to the project, please keep the following in mind:

* **Accuracy is paramount:** We strive for accuracy in the digitization of features, their locations, and their historical timelines. Nailing down when and where something was is a tricky thing. when adding a feature, set its added date as the publication date of the first source for which you can find it referenced, but its shape, particuraly if it is found in later, more accurate sources can be pulled from that.
* **Metadata is crucial:** When refining the date or location of any geographic object, it is essential to thoroughly fill out the associated metadata fields. This should include detailed information about the source of the updated data. where the placement or creation of something is not clear, add a comment Point to the "Discussion-Sources" around the time in doubt. others may be able to combine other puzzle pieces.
* **Source documentation:** Due to the ever shifting sands of the internet, it is best to include the source of your data as an image file, document, or other relevant file within the `Sources` folder of the project. This allows for easy verification and tracking of edits. 
* **Clear communication:** When submitting changes or suggesting improvements, please provide clear and concise descriptions of your contributions.
* **Use proper "source control etiquette":** if you are unfamiliar with Github and source control, we reccomend watching [this video](https://www.youtube.com/watch?v=hwP7WQkmECE) to get you up to speed. it is a powerful and forgiving tool that allows collabloration from multiple people on the same work.
*    it is expected that you work in a seperate branch based off of preview, and when you are ready for your contributions to be added to preview and master, you can open a pull request to preview for review by the project admin. changes will ideally be reviewed in a timely manner, but the admin has a 9-5 like the rest of us, which takes priority.

Together, we can collectively build a robust and well-documented historical GIS dataset that illuminates the hidden history of Charlotte!

## Project Scope and Goals

The primary scope of this project is to digitize and visualize the historical evolution of physical infrastructure, focusing initially on **roads and railways** within **Mecklenburg County**. Potential future expansion may include adjacent areas, and tracking land use over time, depending on data availability and project resources. Additionally, while the roads are storyless, this project could serve as a jumping off point for highlighting interesting stories, and locations in the area.

The key goals of this project are:

* **Uncovering Hidden History:** To document and visualize the often-unseen historical traces of old Charlotte through its infrastructure.
* **Spread said history in a easy to access form** For now the data is accessible mainly through dedicated GIS clients such as QGIS(free), but a dedicated website with visualization similar to [Mecklenburg time machine](https://timemachine.mcmap.org/#35.290608681589795/-80.82378745079042/17/-1009843200000) would be immensely valueable. Web developers are welcome!
* **Temporal Analysis:** To enable users to analyze the spatial and temporal relationships between different infrastructure elements and their impact on the region's growth.
* **Data Preservation:** To create a consolidated, traceable digital archive of historical infrastructure information, making it accessible for research, education, and public interest. Many maps are scanned and show a snapshot in time, but are patchy, and often have inaccuracies, owing to the inherent inprecision of historical mapping artistic nature of many maps. 
* **Community Contribution:** To foster a collaborative space where individuals can collectively learn about both history, and tooling to better document and visualize it.


