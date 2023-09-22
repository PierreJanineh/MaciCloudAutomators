# MaciCloudAutomators

MaciCloudAutomators are designed to manage the synchronization of files/folders in the iCloud Drive folder with iCloud, allowing users to include/exclude specific items from syncing.

## Features
- **Add NoSync**: Exclude selected files/folders from uploading to iCloud by adding a `.nosync` extension.
- **Remove NoSync**: Include selected files/folders for uploading to iCloud by removing the `.nosync` extension.
- **Get all NoSync files**: List all `.nosync` files in a folder that are excluded from iCloud synchronization.
- **Get all not deleted downloads**: Identify all files that are uploaded to iCloud but are still using local storage.

## Installation
1. Clone or download this repository.
2. Place all the files in one folder. Note: `iCloud Tool.app` may not work if other apps are placed in different folders.
3. Launch the application by clicking the app icon and choosing the required action.

### Troubleshooting Installation
- If you encounter an error stating, “iCloud Tool” is damaged and can’t be opened, open each of the 4 applications in `Automator.app` and save them in your Automator's current version.
- If you receive a message that “iCloud Tool” can’t be opened because it is not from an identified developer, allow apps from unidentified developers in your Security & Privacy settings.

## Usage
This application is particularly useful for managing the iCloud uploading process for large-sized files or files that are actively being worked on. Typically, users can Add NoSync to large files or files in use and Remove NoSync once they are ready to be uploaded to iCloud.

## Considerations
- Manipulated folders/files should be under the "iCloud Drive" directory on your Mac.
- Files manipulated by this application must be downloaded on your machine and not only on iCloud Drive.
- Adding the `.nosync` extension to any file stops it from syncing to iCloud Drive immediately, and removing that extension syncs the files immediately as well.

## Additional Information
For more detailed information, refer to the [Medium article](https://medium.com/programming-with-pierre/pause-stop-icloud-drive-from-syncing-4df73d402735).

## Support
Enjoy using MaciCloudAutomators! If you find it helpful, consider supporting the project through [Donation](https://www.paypal.com/donate?hosted_button_id=DVVUAG77AKXYA).

![Donation QR Code](http://pierrejanineh.com/img/paypal_donation.png)
