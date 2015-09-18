# Cisco AnyConnect, Dark!

Do you use Cisco AnyConnect for VPN but also prefer using the "dark" menubar on Mac OS X? You've probably noticed that it looks awful next to all the nice monochrome icons.

It's not too hard to fix this eyesore...

![Screenshot](Screenshot.png)

### A few simple directions:

1. Download [these new images](https://github.com/leebyron/anyconnect-dark/raw/master/Resources.zip).
2. Unzip these files.
3. Open Finder and Find `Cisco AnyConnect Secure Mobility Client.app`. It's probably in your Applications folder under a Cisco folder.
4. Right-click the application and select "Show Package Contents".
5. Open the "Contents" folder, and "Resources" folder.
6. Drag the new images files into the "Resources" folder and select "Replace" for each image.
   * You may need to "Authenticate" with your password if your Applications folder is protected.
7. Quit Cisco AnyConnect and open it again.

### Caveats:

* This doesn't change the software, only the images so the problem of not supporting both dark and light menu bar remains. If you plan on switching back to light menu bar, you may want to save a copy of the original assets.
