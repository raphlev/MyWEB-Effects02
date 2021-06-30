# Search DIR
CMD Command Prompt Windows:
cd D:\Symfony\Code\MyWEB\src
dir /b

# Generate html section
code.xlsx
replace "" by "
replace       "  by <empty>
replace "<section> by       <section>

# Mass-replacement
AgentRansack > index.html > Notepad++ > 
-replace href="style.css" by href="./style.css"
-replace "Online Tutorials" by "Web Design"

# Encoding
utf-8 using notepad++>encoding, otherwise Liveserver hot reloading will not work

# Video
update video size using online videos compressor
AgentRansack > *.mp4
https://www.freeconvert.com/video-compressor/download

# remove subFolder: 
resource files are duplicated: images/assets/..
remove subfolders and check with F12

# Install / Start
Parcel does not work - HMR / Hot reloading not working
Nothing to install
Select index.html > OPen With Live Server
