# ACN-Precompiled-Server-Linux

The precompiled server for All City Network so anyone can host a Bombrush Cyberfunk multiplayer server of their own, without having to learn the steps needed to be able to build the server. This is the perfect option to play with friends, if you don't want to deal with freesoul, other players, or major servers that try and control what mods you can use in game. 

**This is the precompiled server program from All City Network for linux. If you are looking for the windows version, head over to:** https://github.com/SnailUsbs/ACN-Precompiled-Server

# SETUP

<details>
  <summary><b>How To Run The Server (On your device, mainly for friends)</b></summary>
  
  - Download the build from this repo
  - Keep everything in the folder, do not remove the exe from it, as it needs to call on the other files in it to run properly 
  - Run the "BommbrushMPServer.exe"
  - Ensure you have port forwarded a port, with port 41585 being the default option
  - A terminal will appear giving you an over view of the server once its running. 
  - Close the terminal when you want to close the server.

  - Once the server is running, edit your bombrushMP config to add your server address/IP, alongside your port if you changed it.
  - Then once you load the game, you will auto connect to your custom server!
</details>

<details>
  <summary><b>How To Run A Major Server MMO Style</b></summary>
  
  - You need to rent a remote server from month
  - Best options would be something like DigitalOcean, which will only run you a few dollars per month.
  - Depending on your player count, you may need to increase the amount of total power you are renting, but its unlikely based on Freesoul's numbers. 
  - After your server is rented, you follow the same steps as above to get the server running. 
</details>

<details>
  <summary><b>Won't Launch? / .NET 8.0.1 Issues</b></summary>
  
  - If you get an error trying to launch it, saying you need .NET 8.0.1, try installing that first and see if it works

  - .NET can we a little whack when installing. A reinstall has fixed this exact issue for others in the past.
  
  - If it doesn't work even after installing/reinstalling, thats likely because you already have another .NET version on your pc, and you need to specificly launch it with a command like
  > & "C:\path\to\dotnet\dotnet.exe" .\BombRushMP.ServerApp.dll
  > 
  > Replace the "C:\path\to\dotnet\dotnet.exe" with you actual .NET 8.0 path
  >
  > replace the "BombRushMP.ServerApp.dll" with the actual path of your dll
  >
  > launching the dll instead of the exe gets around the .NET issues
</details>

-----

# Extra info:

- **Auth_keys.json:** This is the file that handles badges, if the user is a mod/admin, and special effects for players. To use some pre made ones, or to learn how to make your own, head to: https://github.com/SnailUsbs/ACN-Auth_keys.json-Setups

- **All Commands:** You can see all of the possible in-game commands: https://github.com/SnailUsbs/ACN-Precompiled-Server/wiki/All-City-Network-Commands

- **Aprils Fools Badge Event:** This is a server side event that will give all users a random badge based on their name. You can see exactly what badge you will end up getting with a given username in: https://github.com/SnailUsbs/ACN-AF-Badge-Crack

- <details>
  <summary><b>Debug Servers</b></summary>
  
  If you are having issues with the server, the versions below will print infomation in the terminal regarding your specific issue. All Debug servers are hosted in the same repo, but the links below will bring you each specific version:

  - **Debug Server Repo:** https://github.com/SnailUsbs/ACN-Precompiled-Server-DebugVersions

  - **auth_keys.json Debug Server (windows):** https://github.com/SnailUsbs/ACN-Precompiled-Server-DebugVersions/releases/tag/AuthKeyDebugv1
</details>
