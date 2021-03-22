# MaciCloudAutomators
These Automators are designed to exclude/include files/folders in iCloud Drive folder from syncing with iCloud.

# Actions:
* Add NoSync to all files in folder.
    - Adds .nosync extension to all files in folder, to exclude them from uploding to iCloud.
* Remove NoSync from all files in folder.
    - Removes .nosync extension from all files in folder, to include them for uploading to iCloud.
* Find NoSync from all files in folder.
    - Finds all .nosync files in foldes, files that are excluded from iCloud synchronization.
    
## Installation:
Install this repository and place the main app file "iCloud Tool.app" in your Applications folder.
And using the application is as easy as clicking the app icon and choosing the action needed.

## Usage:
This application is for managing iCloud uploading process, especially when you add large-sized files to your iCloud Drive.
What I usually do is Add NoSync to files that are really large, or files that I work on, and once I'm finished I Remove NoSync to allow iCloud to start uploading the files again.

## Things to keep in mind:
* The folders/files manipulated should be under "iCloud Drive" directory on your mac.
* The files manipulated by this automator application cannot be files that are only on iCloud Drive (are not downloaded on your machine)
* Adding the extension .nosync to any file stops it from syncing to iCloud Drive immediately, and removing that extension syncs that files immediately as well.
* Files containing the extension are not uploaded to iCloud Drive at all.


> Have fun using it, and any donations would be most appreciated. [Donate](https://www.paypal.com/donate?hosted_button_id=DVVUAG77AKXYA)
! [Donation QR Code] (http://pierrejanineh.com/img/paypal_donation.png)
