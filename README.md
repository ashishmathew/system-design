These are my notes on System design
Refer Alex Xu (Vol 1)
Categories:Scaling your application to millions of users
-Single Server Setup
-Database(Replication)
-Vertical Scaling vs Horizontal Scaling
-Load Balancer
-Database replication
-Cache (Check out the whitepaper on - Scaling memcache at Facebook)
-Content Delivery Network(stores static content) 
-Stateless web tier vs Stateful web tier
-Data Center (Geo routed)
-Message Queue
-Logging,metrics,automation
-Database Scaling (Vertical vs Horizontal:Sharding)
-Sharding key (Parition key) issues : 
 Resharding data
 Celebrity Problem
 Join and de-normalization





Questions:
-What are cookies? 
-Where does CDN and DNS fit in the architecture?
 They are two separate components. DNS will resolve the name to the IP address and if the website page has any static content which is frequently accessed can be stored in a CDN server geogrpahically closer to the client(Static content like Images, JS, CSS etc..)


