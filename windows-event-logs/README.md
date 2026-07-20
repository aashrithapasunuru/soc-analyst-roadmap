# DAY-1

## Practical 1 - Configure Splunk to Receive Logs

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
