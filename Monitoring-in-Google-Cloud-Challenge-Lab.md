## Monitoring in Google Cloud: Challenge Lab





### ©Credit
- **DM for credit or removal request (no copyright intended) ©All rights and credits for the original content belong to Google Cloud [Google Cloud Skill Boost website](https://www.cloudskillsboost.google/)** 🙏


### Run the following Commands in CloudShell

```
curl -LO https://raw.githubusercontent.com/Kunalthakur01/Monitoring-in-Google-Cloud-Challenge-Lab/refs/heads/main/kunalsingh.sh
sudo chmod +x kunalsingh.sh
./kunalsingh.sh
```
* Go to `Create log-based metric` from [here](https://console.cloud.google.com/logs/metrics/edit?)

1. For Log-based metric name: enter `drabhi`

2. Paste The Following in `Build filter` & Replace PROJECT_ID
```
resource.type="gce_instance"
logName="projects/PROJECT_ID/logs/apache-access"
textPayload:"200"
```

3. Paste The Following in `Regular Expression` field:
```
execution took (\d+)

```
### Congratulations !!!!

<div style="text-align: center; display: flex; flex-direction: column; align-items: center; gap: 20px;">
  <p>Connect with fellow cloud enthusiasts, ask questions, and share your learning journey.</p>  

</div>
