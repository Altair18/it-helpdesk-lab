Troubleshooting Steps and Solution

1: Verified that the system was connected to the network and could access other resources such as the internet or the internal servers.

2: Opened up command prompt and used "ping" and "nslookup" commands to test connectivity to the file server hosting the shared drive.

3: Confirmed that the mapped drive path was correct by using "net use" to view mapped drive info.

4: Discovered that the network drive was not reconnecting at login due to a disabled credential save.

5: Remapped the drive manually using "net use z::\\server\sharedfolder /persistent:yes", providing correct credentials.

6: Verified access, rebooted the system, and confirmed the mapped drive reconnected successfully.

Issue Resolved
