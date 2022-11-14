# Obsidian S3

An [Obsidian](https://obsidian.md/) plugin for storage and retrieval of media attachments on S3 compatible services. 
## Getting started
- Clone this repo.
- `npm i` to install dependencies
- `npm run build` to compile to `main.js`
## Manually installing the plugin
- Copy over `main.js`, `manifest.json` to your vault `VaultFolder/.obsidian/plugins/your-plugin-id/`.

## Feature list
Supported files (limited by files allowed to be linked by Obsidian): 
- images (.ico, .png, .jpg, .gif).
- videos (.mp4).
- audio (.mp3, .wav).
### Upload
- [x] Upload on paste.
- [x] Upload on drag-n-drop.
- [ ] Upload on adding attachments.

### Retrieval
- [x] Generate links for images.
- [x] Generate links for videos.
- [x] Generate links for audio.
- [ ] Returning download links for un-supported resource? (pdf, txt, ...).
### Helpers/Misc
- [x] Command: delete un-used resources.
- [x] Command: Show bucket size
- [ ] Rename links on port/foldername changes.

### Unplanned
- [ ] Command: upload existing compatible attachments.
- [ ] Parallel uploads. 
- [ ] Retry counts and delays.
- [ ] Upload static html sites.
- [ ] Generate links for static html.
- [ ] Resource local caching (may increase incompatibility with mobile).
