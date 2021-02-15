This is the repository for the 41.2 Clergy Kegerator:

A web application will monitor who drinks, display stats, and showcase whats on tap.

Hardware:
- 2 tap kegerator (for beer, duh)
- 2 YF-S201 flow meters (record data)
- 1 DS18B20 temperature sensor (ensure beer is cold)
- Raspberry Pi 3B+ (host the server)
- Arduino Uno (get sensor readings)

Server / webapp:
MEAN stack - MongoDB, Express.js, AngularJS and Node.js:
- index.js is the server
- public/index.html is the UI
- data is read in realtime using web sockets (socket.io)



Contributors:

Luke Steenge