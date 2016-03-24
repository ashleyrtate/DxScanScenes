---------------------------------------------------------------------
DxScanScenes

While the underlying libraries are covered by LGPL, this sample is released 
as public domain.  It is distributed in the hope that it will be useful, but 
WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY 
or FITNESS FOR A PARTICULAR PURPOSE.  

---------------------------------------------------------------------

A sample application scanning a media file looking for scene changes
 
To call it, you basically need:

   Capture cam;

   cam = new Capture(@"C:\foo.mpg");
   cam.Start();
    
   cam.m_Count is the number of frames
   cam.m_Scenes is the number of scenes detected

The sample was adapted from the DxScan sample with a minimal amount of effort 
expended to hook in the scene-scanning code.

If you have questions or comments or wish to point out flaws in the scene scanning code, send email to
ashleytate@gmail.com. The scene-scanning strategy is discussed further at http://coditate.blogspot.com