# Stellarium PC Android port
Trying to port as much as possible of Stellarium PC version to Android. See Stellarium/stellarium for credits of the original code.

### Known issues
Currently very early in progress so there are a lot of issues to work on

1. Any functionalities using Internet are broken because of lack of OpenSSL
2. Android storage permission and lack of such frameworks in Qt
3. Missing constellations and stars
4. Missing a bunch of shape files for solar system minor bodies
5. Calculating of emphemerial is an automatic crash.
6. showmysky cannot be compiled and has to be disabled
7. UI does not fit onto even modern high resolution phones
8. No app icon, and need better AndroidManifest.xml
