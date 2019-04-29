# Bear Photo Journal
Makes a journal entry in Bear with date, photo, address, and map links.

- **Install Workflow: [Bear Photo Journal](https://workflow.is/workflows/ec001e9e735145628474d9a253d8ae82) – iOS**  
- **Download: [Bear Photo Journal](assets/Bear%20Photo%20Journal.kmmacros.zip?raw=true) – Mac**  
(“Keyboard Maestro” Workflow – multiple photos from Finder)
- **Download: [Bear Journal Entry](assets/Bear%20Journal%20Entry.wflow.zip?raw=true) – Mac**   
(“Automator” / JavaScript Workflow – no photos)

*Part of: [Bear Power Pack](https://github.com/rovest/Bear-Power-Pack/blob/master/README.md)*

### Features
- Today's date in title, 
- Image's location in fenced code block
- Tagged: `#journal/yyyy/MM`
- Let you pick from iOS Photo Library
- Can be used from today widget 
- Or with shared text or file input from other apps
- If photo has no location, current location will be used.
- Includes both Apple and Google maps links

### In code comments:
> Here you could drag “Get Variable CreationDate" below "Date Current Date" to use image date as heading instead of today's date:  

> {{The two actions below, inserts a blank line before photo, to prevent it becoming featured image of WP blogpost when publishing with the "Bear note to WordPress" workflow.}} But if you mostly want this photo as feature image, just remove the two actions below  

*Written with* 🐻 *on iOS and Mac*

#bear/github