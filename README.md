### Linux

We are creating Linux servers in AWS Cloud. Don't create servers in your laptops that consume lot of memory. Use free trail of AWS account.

**NOTE: Delete EC2 after practice**

Make sure your security group has access to port number 22.

Once you create the server, you need to use ssh command to login to the server.

```
ssh -i <path-to-pem-file> username@IP-Adress
```

$ - denotes normal user <br/>
\# - denotes root user