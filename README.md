# astro ark rcon-core

>**This repository is forked from [rcon-core](https://github.com/kr5ch/rkon-core) and adapted to work with ark servers** 

This is a library for the [Source RCON Protocol](https://developer.valvesoftware.com/wiki/Source_RCON_Protocol)

## Usage
```java
// Connects to 127.0.0.1 on port 27015
Rcon rcon = new Rcon("127.0.0.1", 27015, "mypassword".getBytes());

// Example: On a minecraft server this will list the connected players
String result = rcon.command("list");

// Display the result in the console
System.out.println(result);
```
When connecting to the rcon server, an `AuthenticationException` will be thrown if the password is incorrect.

https://astro-pvp.com
https://discord.gg/astroark
