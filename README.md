# StatFetch
This is a Discord Bot for Game server Statistics!

Current Features
- Allow users to add and remove game servers to monitor on a per-Discord guild basis.
- Fetch data from a game server (such as Minecraft or Steam servers).
- Notify users if the game server goes offline, online, or if players start or stop playing.
- Keep track of data such as maximum players and Uptime.
- Edit view to Edit the Instance-Configurations.
- Join Button on Steam servers Dashboards (Messages) that allows Users to connect.

<img src="https://i.imgur.com/6a2iR1i.png" width="300">
<img src="https://i.imgur.com/OPKnL4Z.png" width="300">
<img src="https://i.imgur.com/JS8xSLD.png" width="300">
<img src="https://i.imgur.com/5hh0jSk.png" width="300">
<img src="https://i.imgur.com/0fGPlDC.png" width="300">
<img src="https://i.imgur.com/e0NRGrP.png" width="300">
<img src="https://i.imgur.com/V02gB57.png" width="300">
<img src="https://i.imgur.com/ktf9gm2.png" width="300">
<img src="https://i.imgur.com/4Jd2zGl.png" width="300">
<img src="https://i.imgur.com/S72S0z2.png" width="300">
<img src="https://i.imgur.com/Lhify0w.png" width="300">
<img src="https://i.imgur.com/VpT2aVH.png" width="300">
<img src="https://i.imgur.com/YR0tuRx.png" width="300">
<img src="https://i.imgur.com/jb2kxn6.png" width="300">
<img src="https://i.imgur.com/Ul0OHWz.png" width="300">
<img src="https://i.imgur.com/Eb7tT8t.png" width="300">
<img src="https://i.imgur.com/6S5MwGS.png" width="300">
<img src="https://i.imgur.com/eIag61u.png" width="300">
<img src="https://i.imgur.com/PUT3axJ.png" width="300">

Notification Options.
Option | Function
--- | ---
OnFreeSlot | When Player slots get free (70/70) Players -> (69/70) Players
OnFirstPlayer | When one Player starts playing (0/70) Players -> (1/70) Players
OnlineOffline | The Server goes Offline or Online
FullSpam | everything above plus every joined and leaving Player

Limitations
- Due to the Discord-API's Limitations, the Bot can only update a Dashboard (Message) every 5 Seconds if the Message is Older than one hour. Because of this, the Bot will only edit and update one Dashboard (Message) every 5 Seconds, if you set up 5 Servers, it will take 5 x 5 = 25 Seconds until one Rotation is done.
