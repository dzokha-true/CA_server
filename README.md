# CA server
Certificate Authority/Authenticator server that helps with allowing for an MTLS connection between a user and the robot in the Robo Cayote project for EC463. This server sends out certificates which allows the user and robot to acknowledge that they are talking to the correct user/client.


Users can connect to the server via a socket, and can request to get their certificates based on an authentification. Users cannot conenct to the server if they don't have credentials.
