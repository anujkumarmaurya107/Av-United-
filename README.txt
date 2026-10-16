AV UNITED ESPORT WEBSITE — QUICK START (Android + GitHub Pages)

FILES
- index.html: the complete website in one file.
- assets/audio/: put your own MP3 voice packs here.
- assets/players/: put player photos here.
- assets/gallery/: put gallery photos here.
- assets/tournaments/: put tournament images here.

HOW TO ADD YOUR AUDIO
1. Upload your MP3 into assets/audio/ in your GitHub repository.
2. Open index.html and find: const AUDIO = [
3. Change one item like this:
   {title:"AV Delete Bhai Voice", file:"assets/audio/delete-bhai.mp3", note:"AV Voice Pack"}
4. Save/commit index.html. Use the exact filename and capitalization.

HOW TO ADD PLAYER PHOTOS
1. Upload photos into assets/players/ (example: player1.jpg).
2. In the PLAYERS list, set photo:"assets/players/player1.jpg"
3. Replace name, game, real, dob, role, youtube and instagram values.
4. Use full profile links for youtube/instagram, e.g. https://www.youtube.com/@YourChannel

HOW TO ADD GALLERY PHOTOS/CAPTIONS
1. Upload images into assets/gallery/ (example: ffmic-final.jpg).
2. In the GALLERY list, set photo:"assets/gallery/ffmic-final.jpg"
3. Edit title and year for the caption shown under the image.

HOW TO EDIT TOURNAMENTS
Edit the WINS list in index.html and replace the sample title, year and detail.

IMPORTANT
- GitHub Pages hosts static websites. Changes made by editing index.html and committing to GitHub become visible to everyone after deployment.
- This starter does NOT contain a secure public admin panel or real Google login. A secure admin panel that changes the public site requires a backend/database and authentication.
- The player names, dates, achievements and photos are placeholders. Replace them with your own accurate information.
- This is an original AV-branded design inspired by the general gaming/esports layout of your reference, not a copy of their logos/photos/code.
