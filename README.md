# Drive Tutorial

## TODO

- [x] Set up database and data model
- [x] Move folder open state to URL
- [x] Add auth
- [x] Add file uploading
- [x] Add analytics
- [x] Make sure sort order is consistent
- [x] Add delete on files
- [x] Real homepage + onboarding

## Follow ups

### Folder deletetions

Make sure you fetch all of the folders that have it as a parent, and their children too. Then delete them all in one batch.

### Folder creations

Make a server action that takes a name and parentId, and creates a folder with that name and parentId (don't forget to set the ownerId)

### Access control

Check if user is owner before showing the folder page

### Make a "file view" page (kinda difficult)

Would need to determine what kind of file it is and then have different ui's depending on what kind of file it is.

### Using toasts(notifications)!

Adding some kind of ui to show the user something is happening. Notifications.
