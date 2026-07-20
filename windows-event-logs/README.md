# DAY-1

## SIEM-Fundamentals

### Objective
Configure the Splunk Indexer to receive log data from Splunk Universal Forwarders.

### Steps Performed
1. Opened Splunk Web.
2. Navigated to:
   Settings → Forwarding and Receiving.
3. Created a new receiving port.
4. Configured TCP port 9997.
5. Verified that Splunk was listening on port 9997 using:
```bash
sudo ss -tnlp | grep 9997

### Result

```markdown
### Result

Successfully configured the Splunk Indexer to receive data on TCP port 9997. The environment is now ready for the installation and configuration of the Splunk Universal Forwarder on the Windows VM.
