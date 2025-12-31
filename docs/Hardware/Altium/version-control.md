Altium saves the history of a project through two different methods: Commits and Releases. Projects in Altium are saved in a Git repository where different changes to the schematic, PCB, and other outputs are saved. Commits save the working files of the project to the repository, whereas releases save a revision of the project and its source data, fabrication data, and assembly data in one shot and one location. These commits and releases can be seen in the project history and interacted with in both Altium Designer and Altium 365.

---

## Project History

The project history allows a user to see the chronological timeline of all the events such as creation, commits, releases, clones, and MCAD pushes. What was changed from commit to commit can easily be seen in the history where different nets, components, files and more will be said to have been modified, added, or removed from the previous version. Any version of the project can be open and viewed. Project history can be opened through Altium Designer and Altium 365. To open the history in Altium Designer, right click on the project in the project tab and select “Show Project History” under the “History and Version Control tab”. In 365, while viewing the project select the “History” tab to access it.
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/altium-designer-version.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>

Multiple actions can be performed in project history including: comparing different versions of the project to each other, downloading the project’s files, downloading revision data, making copies of different versions of the project, and reverting the project back to a previous version/commit (only available through Altium Designer). The project will be committed after saving the project to the server. This is easily done in the project panel of Altium Designer. The option to save to server will appear next to the project name after an addition, modification, or deletion to or in any of the project files. This can also be done by right clicking on the project and selecting save to server. The project will have to be committed before a release can be performed.
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/version-control-options.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>

## Project Releaser
The Project Releaser is how releases are pushed in Altium Designer. The main draw of using the project releaser is having a revision of the project with all of its manufacturing data in one place pushed simultaneously and housed in one place. The release of the project is viewed in project history where manufacturing data like Gerber, NC Drill, BOM, Pick and Place, Draftsman Drawings, STEP files and more can be viewed and downloaded. The specifications for these files can be altered in the output job files in Altium Designer, however these should automatically be tailored to the team’s needs if the RIT Racing Project Template is in use. 

The project releaser can be found in Altium Designer by right clicking on the project in the projects panel and clicking on the Project Releaser. Select the necessary manufacturing data needed; Source data (Schematics, PCB, and Outjobs) and fabrication data (Gerber, NC Drill, Pick and Place, and BOM files) will always need to be exported with a release. There is also an additional Costs Outjob that should be released under Assembly data if the PCB is going to the car and is thus needed for costs. The revisions of the project should follow an alphabetical order of A, B, C, etc.
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/project-releaser.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>

By pressing details next to what data will be included in the release you can see what files will be exported, and by pressing options in the bottom, the output jobs that will be generated for each data type can be seen. Any output job can be selected for any data type. So the cost output job can be downloaded to the fabrication data, and the fabrication output job can be downloaded into the assembly data and so on. For the team, the source data will include none of the output jobs and just include the source files of the project (Schematics, PCB, Output Jobs), and the Fabrication data will only include the fabrication output job which will have the Gerber, NC Drill, BOM, Pick and Place, and STEP files. Assembly data will include the costs outjob. If the project template is not in use there will be no created output jobs and thus Altium will create default outjobs that the user will need to alter. 

Once the revision name is correct and the output files are correctly configured in the project release, the user can prepare the files to view what they will look like before finally releasing the project and creating a revision of it. The end release will appear as a large red block in the project history. The fabrication and source data can be downloaded from the revision, with the individual files being able to be downloaded separately or together in one ZIP file. 
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/version-download.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>

Files can be downloaded from the red circle and the snapshot of the project can be viewed from the blue circle.