# ACN-Precompiled-Server-Linux

The precompiled server for All City Network so anyone can host a Bombrush Cyberfunk multiplayer server of their own, without having to learn the steps needed to be able to build the server. This is the perfect option to play with friends, if you don't want to deal with freesoul, other players, or major servers that try and control what mods you can use in game. 

**This is the precompiled server program from All City Network for linux. If you are looking for the windows version, head over to:** https://github.com/SnailUsbs/ACN-Precompiled-Server

# SETUP

<details>
  <summary><b>How To Run The Server (On your device, mainly for friends)</b></summary>
  
  - Download the build from this repo
  - Keep everything in the folder, do not remove the exe from it, as it needs to call on the other files in it to run properly 
  - Run the "BommbrushMPServer" program
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

    - if you want to make a mod that will make All City Network auto connect to your server, you can grab the template for that here: https://github.com/SnailUsbs/ACNServerMod/tree/main
</details>

-----

# Extra info:

- **Auth_keys.json:** This is the file that handles badges, if the user is a mod/admin, and special effects for players. To use some pre made ones, or to learn how to make your own, head to: https://github.com/SnailUsbs/ACN-Auth_keys.json-Setups

- **All Commands:** You can see all of the possible in-game commands: https://github.com/SnailUsbs/ACN-Precompiled-Server/wiki/All-City-Network-Commands

- **Aprils Fools Badge Event:** This is a server side event that will give all users a random badge based on their name. You can see exactly what badge you will end up getting with a given username in: https://github.com/SnailUsbs/ACN-AF-Badge-Crack
