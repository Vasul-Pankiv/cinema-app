[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Poppins&size=35&duration=2500&pause=1000&color=1A5BF7&width=435&lines=Cinema+-+WebApp)](https://git.io/typing-svg)
## Project description:
>This application is a simplified version of the cinema service. It allows user registration, creating shopping cart, ordering tickets and scrolling necessary information for administrators
## Project structure:
> This is an N-Tier Architecture
> * DAO - Data access Tier (CRUD methods)
> * Service - Business Tier
> * Controller - Presentation Tier
## :fire: Features:
> * Registration, authentication and authorization;<br />
    It is possible to register a new user, log in to an existing account, and operate the service from that account depending on the role given.
> * Scrolling through the information;<br />
    The user has the ability to view the available movies, as well as orders. The administrator can also view detailed information about cinema halls and the user database.
> * Information handling;<br />
    The user has an opportunity to buy tickets (selectively add it to a shopping cart with further purchase). The administrator is given the opportunity to change the hall information, availability of movies and its sessions.
## :wrench: Technologies:
> * Java 11
> * Hibernate
> * Spring Web
> * Spring Security
> * MySQL
> * Maven
> * Tomcat
## How to launch the project on your PC:
> 1. Fork this repo
> 2. git clone \<your link>
> 3. Configure resources of you DB --> "db.properties" file
>```properties
>db.driver=YOUR_DRIVER
>db.url=YOUR_URL
>db.user=YOUR_USERNAME
>db.password=YOUR_PASSWORD
>```
> 4. Install [Tomcat](https://tomcat.apache.org/download-90.cgi)
> 5. Add Tomcat server to configuration
> 6. Run project
