### Known limitations

1. Because this app can't yet run in the CI server, its integration level is unkonwn at the moment and standard Yunohost packages testing couldn't run yet. **Please don't use it on a prod server**
2. The app requires MinIO app to be installed (MinIO installation is automatic, though)
3. The app is requiring three domains including two fully dedicated (one for MinIO server, one for Dex, one for Outline)
4. ARM architectures are not supported (and may never be as Outline was built for AMD64)
6. Because it's built from sources, the app requires an important amount of RAM, disk and time to install properly


### How to create an admin user

The first user to login will automatically be granted admin rights
You can then change the user rights by default and/or change the admin user afterwards from the Outline settings page