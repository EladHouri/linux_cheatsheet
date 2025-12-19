# linux_cheatsheet

file = 


wget - downloada file 
wget -r -np -k http://target-site/ - downold web pages recursive, html+css+js+obj

explorer.exe - open a file via wsl on windows

echo "x" | xxd -p -r - hex to ascii
xxd filemme - hex+ ascii 
xxd filename | head/tail


echo "6wDoT88=" | base64 -d - base64 to ascii

tr 'A-Za-z' 'N-ZA-Mn-za-m' - ceaser 

exiftool - metadata of a pic

git log - see versions for specific branch
git branch - see branches
git checkout <ver> change version

ssh -p 55055 hey@x

checksec --file="file name" - security properties for ELF


pngcheck - check png Length field+Chunk type+Chunk data+ CRC

 binwalk filename - check for polylog

Steganography:
zsteg - no password (for prng)
steghide embed -cf cover.jpg -ef secret.txt -p mypassword
steghide extract -sf cover.jpg -p mypasswor


nano - edit ascii file

hexedit file - edit hex file

tar -xf 1000.tar
