## Offline Hanzi Writer Usage

### Step 1: Prepare the Files
The Library: Download `hanzi-writer.min.js` and rename it to `_hanzi-writer.min.js`.

The Data Repo: Go to the Hanzi Writer Data GitHub.

Click `Code > Download ZIP`.

Extract the ZIP. You only need the folder containing all the .json files (usually the root or a data/ folder).

Crucial Step: You cannot just dump 9,000 files into your Anki folder. You need to rename this folder to `_hanzi-data`.

### Step 2: Locate your `collection.media` Folder

You need to manually move these files into Anki's hidden media directory.

- **Windows:** `%APPDATA%\Anki2\User 1\collection.media` (Paste this into your File Explorer address bar).

- **Mac:** `~/Library/Application Support/Anki2/User 1/collection.media` (In Finder, press Cmd + Shift + G and paste).

- **Linux:** `~/.local/share/Anki2/User 1/collection.media`

Move the following into that folder:

`_hanzi-writer.min.js`

The `_hanzi-data` folder (containing all the .json files).

### Step 3 (Optional): Move Files for Compatibility with iOS

Rename all the characters in the `data` folder to have a `_` in the beginning. This is so that Anki knows not to delete these files when synchronizing. Place in the main collection.media folder (I know this part hurts) so that it can be compatible with the iOS workaround.
