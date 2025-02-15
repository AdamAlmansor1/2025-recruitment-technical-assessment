# DevSoc Subcommittee Recruitment: Platforms
Your task is to send a direct message to the matrix handle `@chino:oxn.sh` using the Matrix protocol. However, this message must be sent over a self hosted instance such as through the Conduwuit implementation or the slightly more complicated Synapse implementation.

For this to work your server must be federated, but you do not have to worry about specifics such as using your domain name as your handle (a subdomain will do!) or have other 'nice to have' features. Just a message will do!

**You should write about what you tried and your process in the answer box below.**

If you don't manage to get this working we'll still want to hear about what you tried, what worked and what didn't work, etc. Good luck!

---

> ANSWER BOX
```
I decided on the most appropriate hosting option given the use case, which was EC2. I set up an EC2 micro instance and attached a security group that enabled SSH, HTTP, HTTPS and port 8448 which is used by matrix. I connected to my EC2 instance through SSH. Following the instructions on this resource upcloud.com/resources/tutorials/install-matrix-synapse, I configured Synapse. I needed a subdomain so I obtained one for free from reedns.afraid.org. Then I used certbot to enable TLS. I edited the homeserver.yaml so that my server listens on port 8448 and I enabled the TLS option. After that I used the register_new_matrix_user command with the correct parameters to create an account to message chino from. 
```
