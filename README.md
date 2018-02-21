# Welcome to The Spout Project!

The Spout Project is a Minecraft server-side modding API and server implementation. 

 - Website: https://spoutsdk.org
 - Forum: https://spoutsdk.org/index.php?route=/forum/
 - Builds: https://github.com/SpoutSDK/Spout/releases
 - Mods: https://spoutsdk.org/index.php?route=/resources/

# SpoutSDK

SpoutSDK is the server-side modding API. Similar to Bukkit, Sponge, and other such APIs, it allows developers and server owners to add anything they want to their servers.

### Getting Started (with Eclipse)

 1. Open Eclipse
 2. Create a new Java project and name it
 3. Create a new package with the same name as your plugin (case sensitive)
 4. Right click the project > Properties > Java Build Path > Add External Jars > Select the SpoutSDK jar file.
 5. Create a class in the package called "Main" (case sensitive), and extend SpoutSDK
 6. [Define the ModInfo](https://pastebin.com/a5W2R5mg)

### Releasing Plugins

 1. Export the plugin from Eclipse with the same name as the main package (case sensative)
 2. Upload the source to Github
 3. Create a new release on Github, attaching the exported JAR file
 4. Create a new resource on the [resources page](https://spoutsdk.org/index.php?route=/resources/)
	 - **Disclose any external connections made by the plugin**
 5. Create a new thread in the [mod releases subforum](https://spoutsdk.org/index.php?route=/forum/view/12-mod-releases/)

# Spout

### Getting Started

 1. Download the latest release from [Github](https://github.com/SpoutSDK/Spout/releases)
 2. Execute the JAR file with `java -Xmx1G -jar Spout.jar`, where 1G is the amount of RAM to dedicate
 3. After the server generates the world, type `stop` into the console
 4. Edit the `server.properties` and `spout.properties` to your liking, then start the server again

### Installing Mods

1. Download mods from the resources page
	 - **Be sure to download any other mods that the mod may depend on**
2. Place the mod JAR file in the /mods/ folder in the root directory of the server
	 - **Follow this procedure for any dependencies**
3. Restart the server
