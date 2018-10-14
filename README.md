## MaxRev.Servers.Core

### Overview

With this package you can easily start lightweight server locally on any free port you want (with admin rights even under 1024 ports on Linux).<br>
NuGet: [MaxRev.Servers.Core](https://www.nuget.org/packages/MaxRev.Servers.Core/)

## Example server: 
Here you can view basic core initializations and some API definitions
[VstupInfoParser](https://github.com/MaxRev-Dev/VstupInfoParser)

### Features 

- 3 Server types: Server, Proxy or Balancer 

- Async threads for clients with async API handling

- API handling via attributes 

- File listing module with image thumbnails generator (using ImageSharp)

- Currently  supported types of headers - **Cache, Range, Conditionals, Connection,Cookies,Downloads,Redirects** headers processing

- Content compression - gzip, deflate, brotli

- Custom request redirects from config

- Virtual folders like */easy (on web) <-> /long_system_path/other (system)*

- Authorization to server console (via cookie)

- Loggers (Main,Info,Error)

- Schedulers - (for Logger, Base - you can derive to save cache, reparse data, etc.)

- Time Syncronizer with scheduler - server time

- Custom server exceptions and API response objects

- Url Shortener with API (currently only for server session)

- CoreAPI (/coreApi?)

- - for image simple edit (resize, filter) 

  - for server status (trace) view
  - for reboot, suspend

### On planing

- HotLoad - hot assembly load/unload (currently unload API not ready in .NetCore)
- Templates - for proper html forms handling 

### Basic config: 

>Port: 3001
>
>I/O buffers - 2048 bytes
>
>Directories (Server/Data, Server/Reactor)
>
>Config save on start only for servers nor proxy
>
>Access Folder: /www (web or virtual) <-> /www (real)



#### Contact me: [t.me/maxrev](http://t.me/maxrev)



