# Single Point ID Management using Blockchain Technology

> This application uses BigchainDB cluster as it underlying blockchain technology.
> The architecture is based on microservices using Docker and Docker Swarm. 
> The merchant side integrates using WebSockets. All ID verification requests routes to respective micro-service which fetches response from BigchainDb. 
> User flow: User registers itself on our app. A predefined ID instances(Assets) are generated in BigchainDb. 
> User ID validation is automated through various online API's and then assets are stored on bighchainDb. 
> User ID is requested by some merchant, which initiates a user consent action upon which the ID asset is transferred to the merchant who can use the data.