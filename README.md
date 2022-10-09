# systemDesign

The idea of architure that can adapt to scale out system.  

https://github.com/phoenixit99/systemDesign/blob/dev/systemDesign.drawio.png 

# CDN: (Content delivery network): 
- In system have some content alway is static in alway life time. So in this case we can use CDN that cache static content (image, video, css, javascript files)
- CDN can use third-party to deliver static content.

# Data Center:
- Advantage of Data center is Geo-routed. 
- Geographic routing (also called georouting or position-based routing) is a routing principle that relies on geographic position information.
- ex: user access webserver from asia can access via data center at asia area. 

# Load balancer: 
- Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.
- System should down when server is down, ortherwhile lagging should happen when have miliions concurency access at same time.
- The is solution that distribute incomming traffic among webserver. Avoid system down when one of server is down.

# Database repliation: 
- Can be used in many database management system. usally with a master/slave in relationship. Database replication is resolve when database is down
It's could resolve by another database. But have a problim when using database replication is consistency between master and slave database

Caching: 

Ability to reduce database workloads and the ability to scale the cache tier independently. much faster than the database. 
Considerations for using cache. 
- Aata is read frequently but modifid infrequently. 
- Consistency the data sotre and the cache 


# Message queue:  

# Loging, metrics, automation 

