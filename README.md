# Firebase Realtime Database: Inconsistent 'permission_denied' Error

This repository demonstrates a bug where a `permission_denied` error is thrown by the Firebase Realtime Database, even when security rules appear correctly configured. This issue often arises during local development or small-scale testing.

The `bug.js` file contains code that attempts to write data to the database.  The `bugSolution.js` file offers a potential solution by explicitly checking for the error and handling it, or by implementing more robust error handling practices.  Refer to the detailed description and code in these files for more information.