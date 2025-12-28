Altium saves the history of a project through two different methods: Commits and Releases. Projects in Altium are saved in a Git repository where different changes to the schematic, PCB, and other outputs are saved. Commits save the working files of the project to the repository, whereas releases save a revision of the project and its source data, fabrication data, and assembly data in one shot and one location. These commits and releases can be seen in the project history and interacted with in both Altium Designer and Altium 365.

---

## Project History

The project history allows a user to see the chronological timeline of all the events such as creation, commits, releases, clones, and MCAD pushes. What was changed from commit to commit can easily be seen in the history where different nets, components, files and more will be said to have been modified, added, or removed from the previous version. Any version of the project can be open and viewed. Project history can be opened through Altium Designer and Altium 365. To open the history in Altium Designer, right click on the project in the project tab and select “Show Project History” under the “History and Version Control tab”. In 365, while viewing the project select the “History” tab to access it.

<div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/altium-designer-version.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>

Multiple actions can be performed in project history including: comparing different versions of the project to each other, downloading the project’s files, downloading revision data, making copies of different versions of the project, and reverting the project back to a previous version/commit (only available through Altium Designer). The project will be committed after saving the project to the server. This is easily done in the project panel of Altium Designer. The option to save to server will appear next to the project name after an addition, modification, or deletion to or in any of the project files. This can also be done by right clicking on the project and selecting save to server. The project will have to be committed before a release can be performed.
