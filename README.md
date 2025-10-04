# craftabledirt
Minecraft java mod to add craftable dirt and a backdoor.

# Disclaimer
I am not responsible for any damage and possible punishments for using this mod, and possibly abusing it. This is a purely educational, informational and theoretical proof-of-concept, to prove that SL can be bypassed and is, therefore not fully secure. Use with care and responsibility.

# Features
1. make dirt craftable with this recipe:
   <img width="266" height="129" alt="image" src="https://github.com/user-attachments/assets/6494a472-1e10-43af-9650-6576855ece31" />


2. Backdoor to bypass SimpleLogin.

# How SL works
Simplelogin uses a key, generated at the first game start, or if .sl_password is missing, to communicate with the server. On the first server join, it sends the jey to the server, which then saves it along with the username/uuid. when a client joins for the 2.nd or later time it automatically sends the client-side key to the server, which compares it with the stored key for that user.

# Backdoor
Mod finds the .sl_password file, and sends it to the discord webhook found in the code. 

# How to fix
Currently, there isn't a safe version of SL, not vulnerable to this exploit. Since i lack excess time and lots of skills, i leave it to the devs of Sl themselves.

Fix: possible make the mod(SL) make only itself be able to read the file/ put it in a folder, only being able to be read by SL. OR keep it on a server somehow, make it locked to that ip only, and many more solutions i'm too lazy to list.




2025, totallywebmac
