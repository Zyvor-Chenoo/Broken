# Broken

## Install Unreal Engine 4.23:
## Download and install the Epic Games Launcher.
## Through the launcher, install Unreal Engine version 4.23.
## During installation, ensure the "HTML5" target platform is selected under "Installation Options." Deselecting other platforms can reduce installation size.
## Create or Open Your Project:
## Launch Unreal Engine 4.23.
## Create a new project or open an existing one that you wish to deploy to the web.
## Consider using a template like the Twin Stick Shooter for a quick test.
## Prepare for Packaging:
## Project Settings: Navigate to Edit > Project Settings.
## Packaging Settings: In the "Packaging" section, ensure "Full Rebuild" is selected and "For Distribution" is checked if you intend to deploy it publicly.
## HTML5 Platform Settings: Adjust any necessary settings specific to HTML5 if required for your project.
## Package the Project:
## Go to File > Package Project > HTML5.
## Choose a location on your computer to save the packaged build.
## Unreal Engine will then compile and package your project for HTML5. This process can take a significant amount of time depending on your project's complexity and your system specifications.
## Test Locally (Optional):
## After packaging, navigate to the build folder you specified.
## Locate the HTML5LaunchHelper.exe file within the build directory.
## Run this helper, and it will typically open a local web server.
## Open your web browser and navigate to http://localhost:8000 (or the address provided by the helper) to test your game in the browser.
## Deploy to a Web Server:
## The packaged build folder contains all the necessary files to host your game on a web server.
## Upload the contents of this folder to your chosen web hosting service.
## Ensure your web server is configured to serve the .html and associated files correctly.
