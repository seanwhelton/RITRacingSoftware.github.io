Schematic templates are predesigned layouts for how a schematic sheet should look in Altium. They enable the team to have a consistent and more graceful presentation of a [schematic](../../Hardware/Altium/schematic-basics.md) and have information about the schematic readily available and readable. RIT Racing has many different sizes for a schematic template all with the same information. These sizes are all x by y, where x and y are both integers of inches.

---

## Importing Templates

1. To import a schematic template, navigate to the properties panel

2. Change the Formatting and Size to Template

3. Select the RIT Racing schematic template that fits the size of your schematic

    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/template-selection.png" alt="Template Selection"  style="max-width: 100%; height: auto;"/>
    </div>

4. Once a template is selected, press "Just this document" and "Do not update any parameters" in the update template pop-up.

    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/update-template.png" alt="Update Template Pop-Up"  style="max-width: 100%; height: auto;"/>
    </div>

5. Once this is done, the schematic template should populate and look like it does below. The section in the bottom right is called a **Title Block** and contains important information pertaining the schematic

    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/example-schematic-template.png" alt="Schematic Template Example"  style="max-width: 100%; height: auto;"/>
    </div>

## Adding Parameters
The date, project, title, and revision of the title block automatically populate based off of the project information. The revision specifically changes once a [release](../../Hardware/Altium/version-control.md) of the project is published, and the altering of that parameter can be seen in that release.

The author parameter does not automatically update and needs to be input manually. This can be done through navigating to that parameter section of the properties panel for the schematic, or by creating a project parameter in which all schematic sheets would have their author parameter referenced.
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/schematic-parameters.png" alt="Schematic Parameters"  style="max-width: 100%; height: auto;"/>
    </div>
