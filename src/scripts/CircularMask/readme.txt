Script Installation Instructions
================================

1. Find the a folder called "CircularMask" in this .ZIP file.  Place the unzipped folder and its contents in your <PixInsight Folder>/src/scripts folder. (Note: Do not place the contents of the "CircularMask" folder directly in to /src/scripts but rather ensure that it is inside the scripts folder in a sub-folder called CircularMask).

2. In PixInsight select "Script" menu -> "Feature Scripts...".

3. Now click the "Add" button from the "Feature Scripts" dialog. Make sure the <PixInsight Folder>/src folder is selected and click "OK". 

4. You should get a message saying that "1 additional script(s) were found on directory ...". Click "OK" and then "Done".

5. The CircularMask Script should now appear under the "Script" menu -> "Render" -> "CircularMask".

6. If you need more help, please see this video: http://www.pixinsight.com.ar/en/docs/2/pixinsight-add-script.html.

Documentation Installation Instructions (Optional)
==================================================

7. To install the documentation unzip the "pidoc" folder to a temporary location.

8. In PixInsight select "Script" menu -> "Development" -> "Documentation Compiler".

9. Click "Add Files" and browse to the pidoc folder that you just unzipped.

10. Choose the "CircularMask.pidoc" file and click "Open" to add it to the "PIDoc Source Files" list.

11. Click the "Run" button.

12. Click "No" when asked if you want to perform another compilation.

13. The console should display "PIDocCompiler: 1 succeeded, 0 failed, n warning(s)".

14. You can read the documentation by clicking the "Documentation" button at the bottom left of the "CircularMask" dialog, or by finding it in the "Process Explorer" under "<Scripts>" -> "Render" -> "CircularMask".

ChangeLog
=========
   1.0:  First release.

Notes for Script Developers
===========================

a.  The "GUIFactory-lib.js" contains a rough and ready factory object to simplify creation of UI controls in scripts. It is far from feature-complete and really designed to save me time typing and constantly looking up other examples (there are a lot of controls in my little script!).  Again feel free to re-use or fork as required. Others have done similar things in their scripts, so I'm not looking for any prizes for originality here!