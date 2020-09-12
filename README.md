
Termux-For-Youtube

A Youtube Video Downloader For Android using Termux App with youtube-dl plugins.
NOTE : I'm just modified this Script to a more User-friendly interface.

How to Use It

Download Termux and Termux API from Google Play Store.
Make Sure You Are Connected To Intenet.
Open Termux App and type this line of code
apt update

apt install curl

curl https://raw.githubusercontent.com/SarfarazRLZ/Termux-For-Youtube/master/youtube_settings.sh -o youtube.sh

chmod +x youtube.sh

dos2unix youtube.sh

./youtube.sh
