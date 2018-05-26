# Galmil_PENIS (PERSONNEL EVALUATION NETWORKED INFORMATION SYSTEM)
ESI API Scanning Utility using KNIME

Instructions: Setting Up on Your Computer
1. Download and install KNIME to your computer from https://www.knime.com/downloads/download-knime
2. Download the P.E.N.I.S.knar file from this repository to your computer
3. Run KNIME. When it opens, go to the File Menu, then select "Import KNIME workflow". Browse to and select P.E.N.I.S.knar , then click Finish.
4. You will see Galmil P.E.N.I.S now appear at the top left of your screen in the KNIME Explorer under "LOCAL (Local Workspace)".
5. Click the chevron to the left of the words Galmil P.E.N.I.S to open the folder (or Double-Click on Galmil P.E.N.I.S)
6. Duble-click on P.E.N.I.S to open it.

Instructions: Getting a JSON file out of ESI Knife to Import
1. Have the apllicant run the API through ESI Knife ( https://esi.a-t.al/), and mail you the link to the output.
2. On the output page, click the link to View Raw Jason.
3. Copy and paste all of the JSON content into Notepad, go to "Save as" and save it as a file with a .json extension. ANSI or Unicode seems to make no difference when saving

Instruction: Processing the JSON file
1. In P.E.N.I.S , double-click the orange JSON reader box , click the browse button, and select the .json file. Click OK, don't worry about any other settings.
2. Right-click on the grey "Processing" box and select Execute, the second option. You will see a double arrow pointing right in the box as it works. When it is done you will see a tiny clock face in the box.
3. Right-click the "CharacterOutput" folder below "Galmil P.E.N.I.S" in the KNIME Explorer window at the top left of your screen, and click "Refresh" in the drop down menu. Open this CharacterOutput folder and you should now see an Excel File with the applicant's name. 
4. Right-click this file, go to Copy Location, and select "Local Path"
5. Open Windows Explorer and paste in this folder in the adress bar, and hit enter.
6. You now have the applicant's data in Excel. If you don't have excel you can import this file into Google Sheets to view it.
