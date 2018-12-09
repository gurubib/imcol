# balit_learning team Deep Learning homework
The finished work can be found in the _FINAL_ directory.

Some files, directories are too big to be uploaded to Github,
so we provide links to them here.

* image dataset (already renamed correctly):
https://bmeedu-my.sharepoint.com/:u:/g/personal/matyasg_edu_bme_hu/ESad5rlTMn9Ok6a7MiOh08YBJf-IEEyeQN5piFN9xbJFXg?e=feDD2p
* trained weights: https://drive.google.com/open?id=1Suc6tbEz7Fhl-UOK-ToN762EQvSStEKH

The images can be downloaded separately by the given script FINAL/image_downloader_script.ipynb 

After they are downloaded, they must be renamed to incrementing numbers
It can be easily done by this PowerShell script: 
Dir | %{Rename-Item $_ -NewName ("{0}.jpg" -f $nr++)}
