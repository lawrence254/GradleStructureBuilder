# GradleStructureBuilder
A simple but useful bash script to auto create gradle folder structure for those creating java programs. Just run the autoscript file by running `./autoscript` and enter the name of the folder you wish to create.

The file will create the following project structure:

      {folder-name}}/
      ├── build.gradle
      └── src/
          ├── main/
          │   └── java/
          └── test/
              └── java/
 
 
## Planned Upgrades
Add fucntionality to check whether a folder with the provided name already exists and issue the correct error.

## Suggestions
I am open to suggestions on how to improve the script further. Just open an `Issue` for this repository and I wil look into it.
