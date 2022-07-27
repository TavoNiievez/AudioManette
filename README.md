# AudioManette

This document is in construction.

## Brief

AudioManette is a simple remote control for Spotify, this initially does not intend to fully synchronize with the application, thus once the application is opened, it must be operated from the interface provided for a proper experience.

## How to use

You must have a Spotify Developer account for access to [Spotify dashboard](https://developer.spotify.com/dashboard/) and create a new application.

If you have the application, then click on "Edit settings"  and add `http://localhost:5000/` as Redirect URI.

Config client ID and Client Secret from `config/App.config`.
<p align="center">
  <img src="screenshots/Spotify_Dashboard.png"/>
</p>

## Run

It's require dotnet 6.0 or higher, I will soon post the assembly and perhaps an installer.

    $ dotnet run


## Screenshots

![Screenshot 01](screenshots/Screenshot_01.png)

![Screenshot 02](screenshots/Screenshot_02.png)

## Resources

- [Material Desing Icons](https://materialdesignicons.com/)

## Authors
- **Jan Carlos Anaya**