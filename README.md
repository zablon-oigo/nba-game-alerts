![example workflow](https://github.com/zablon-oigo/nba-game-alerts/actions/workflows/deploy.yml/badge.svg)

### NBA Game Day Notifications Alerts System
This project is an alert system that sends real-time NBA game day score notifications to subscribed users via Email. 
The project demonstrates cloud computing principles and efficient notification mechanisms.
It leverages Amazon SNS, AWS Lambda and Python, Amazon EvenBridge and NBA APIs to provide sports fans with up-to-date game information.

#### Features
- Fetches live NBA game scores using an external API.
- Sends formatted score updates to subscribers via Email using Amazon SNS.
- Scheduled automation for regular updates using Amazon EventBridge.
- Designed with security in mind, following the principle of least privilege for IAM roles

#### Technologies
- Cloud Provider: AWS
- Core Services: SNS, Lambda, EventBridge
- External API: NBA Game API (SportsData.io)
- Programming Language: Python 3.x
- IAM Security: Least privilege policies for Lambda, SNS, and EventBridge.

## Run Locally

Clone the project

```bash
  git clone https://github.com/zablon-oigo/nba-game-alerts.git
```

Go to the project directory

```bash
  cd nba-game-alerts
```

Install dependencies

```bash
  pip install -r requirements.txt
```
Install Serverless

```bash
  npm i serverless
```
Deploy the project

```bash
  serverless deploy
```