# LoggingAspNetCore
A Empty Asp.net core Project Configured By Serilog And Seq.
This project has no code and for easy to use and startup faster.

# Seq
The Seq server configured on port ```http://localhost:8585``` . have to way for using Seq in local.

1.Download Seq From https://datalust.co/download

2.Using Docker.

if you want to use docker you can use below code to run it

```docker run -d --restart unless-stopped --name seq -e ACCEPT_EULA=Y -v D:\Docker-Data:/data -p 8585:80 datalust/seq:latest```

# Optional Config

In ```appsettings.json``` Serilog Section have all logging settings there.

# Give Star

If this repository is usful for you pleas give star.Thanks
