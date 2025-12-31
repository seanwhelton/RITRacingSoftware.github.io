Project Templates are reusable design templates that contain settings and configurations that can be applied to a variety of projects. In the RIT Racing Project template there are preset documents that will be used during the design: a top level schematic, a PCB, a Bill of Materials, and a draftsman document. There are also multiple outjobs meant to export the project for fabrication and also for when the team needs to do costs. There are two project templates in the RIT Racing workspace, a default 4 layer template and a 2 layer template. The information below will pertain to both.

---

## Documents

The documents for the project template includes a schematic sheet. The project only has a top level schematic to begin with, meant to show how different user-added schematic sheets connect together. The parameters that are with every schematic sheet template in our library shows the project name, sheet name, author, date, and revision in the bottom right corner of the sheet. A new feature that has been implemented with the template is that the Author parameter can now be globally changed in the project through changing the project parameter in project options, and the revision of the project will automatically be changed when the project is released. Although the revision parameter may go off the sheet when viewing it regularly, when viewing the released version of the project the revision ID will not go off the bounds of the sheet.
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/top-schematic.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>

The PCB document included in the template is configured with JLC compliant rules and includes logos that should be on all RIT Racing PCBs including the RIT Racing logo and the revision of the board. The revision of the board on the PCB. Under the RIT Racing logo shows the Project name, author’s name, and date. The date and author's name will fill in automatically with their parameters. The project name and revision need to be inputted manually. The size of the logos can be changed through the text height or by resizing the union using union actions for the RIT Racing logo.
    <div style="text-align: center; margin-top: 30px;">
        <img src="/../../Hardware/Altium/Images/template-pcb.png" alt="Altium Designer Version"  style="max-width: 100%; height: auto;"/>
    </div>