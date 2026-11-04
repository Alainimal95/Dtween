# Dtween
A Maya modelling tool which duplicates an object between its original position up to and/or including an endpoint.
Similar idea to duplicate special, but because duplicate special works in iterations it becomes clunky when you have a known endpoint.
Dtween is essentially the inverse and will save you having to use a calculator. Use on components not currently supported.

<details>
<summary><b>Setup</b></summary>
  
- Download and unzip the script at a location of your choosing
- Open the text file in a text editor (ex. Notepad++) 
- Open Maya's script editor and create a new MEL tab
- Select all of the text in the text editor and copy/paste it into the new MEL tab
- Optional: Add it as a shelf button for reuse (recommended)
  - Follow these instructions from Autodesk: https://download.autodesk.com/global/docs/maya2014/en_us/index.html?url=files/Running_MEL_Make_a_shelf_button_for_a_script.htm,topicNumber=d30e789357

Alternatively, the script can be run by pressing numpad enter. Select all text in the script first to keep it from disappearing from the script editor.
</details>

### How to Use
- Select your object and the endpoint. The endpoint can be another copy of the object or any transform node
- Run the script
- In the first dialog, choose whether to duplicate between the original object and the end point, or to include the endpoint's location for duplication
- In the second dialog, choose whether to restrict the duplication to an axis or plane (world space). To continue unrestricted, use "All". 
