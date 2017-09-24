# bikeride-app

[![Join the chat at https://gitter.im/bikeride-app/Lobby](https://badges.gitter.im/bikeride-app/Lobby.svg)](https://gitter.im/bikeride-app/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This project is a learning project to understand Android Studio

The application is composed of a context of three aggregates:

- **Biker**: The person that participates on bike rides by subscribing to a ride.
- **Track**: Sequence of waypoints to be followed as part of a ride
- **Ride**: An event organized with limited number of participants to ride over a defined track

This is one Android mobile application using microservices based on Lagom framework, this application also is password less using JWT and trusted PIN delivery channels to authenticate the clients.
