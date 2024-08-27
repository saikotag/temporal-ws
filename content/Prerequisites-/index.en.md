---
title : "Prerequisites"
weight : 30
---


#### Pre-requisites

You will need an Integrated Development Environment (IDE) on your local machine. The workshop will be using  [Visual Studio Code](https://code.visualstudio.com/)

Please ensure you have installed downloaded and installed the following:

- [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html/)
- [Git](https://github.com/git-guides/install-git/)
- [Python](https://www.python.org/downloads/)

Copy the code repository and install the requirements

1. Open VS Code and navigate a new terminal.
2. Download the code repository used in the workshop.
    - Link to the [code](https://static.us-east-1.prod.workshops.aws/355be36b-5dcf-44a2-bfc9-bebf0ab59c91/assets/demo-serverless-microservice-local.zip?Key-Pair-Id=K36Q2WVO3JP7QD&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdGF0aWMudXMtZWFzdC0xLnByb2Qud29ya3Nob3BzLmF3cy8zNTViZTM2Yi01ZGNmLTQ0YTItYmZjOS1iZWJmMGFiNTljOTEvKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTcxMTM3NjcxNH19fV19&Signature=PmmHedhOL89784Imgwes3ZoapS~xVlNyTzrtONI9Mi5uBUDbSD4nC4bZ7kOLndirfb1zxXCz9H-LoICt~4lrEqorzIFJkHaLtNc3F2GwgvZcsufy93hyN3X25XGwwMjJzhazGvwEAFicD3R3mYrq4OZ8ooHLPiAMG9gQxyOfu-mo7FxdcXHluTzqqOiGsInkcKHdSuJDHMMq-PbWi-4mg4VxL3XRQCwbYRUhnnjb7an2BXk34qJEEtzX23JoCoTpfhpzbZ2~BHDudtjiS0zYDuOfcmr8wKGJAIOnIB-K1LFYuA5q3D1xiC2wMKJmf8nFfBGjzDS0El6j6SOS17-wFg__) 
    - Link to the [template](https://static.us-east-1.prod.workshops.aws/355be36b-5dcf-44a2-bfc9-bebf0ab59c91/static/cfn/lambda-debugging.yaml?Key-Pair-Id=K36Q2WVO3JP7QD&Policy=eyJTdGF0ZW1lbnQiOlt7IlJlc291cmNlIjoiaHR0cHM6Ly9zdGF0aWMudXMtZWFzdC0xLnByb2Qud29ya3Nob3BzLmF3cy8zNTViZTM2Yi01ZGNmLTQ0YTItYmZjOS1iZWJmMGFiNTljOTEvKiIsIkNvbmRpdGlvbiI6eyJEYXRlTGVzc1RoYW4iOnsiQVdTOkVwb2NoVGltZSI6MTcxMTM3NjcxNH19fV19&Signature=PmmHedhOL89784Imgwes3ZoapS~xVlNyTzrtONI9Mi5uBUDbSD4nC4bZ7kOLndirfb1zxXCz9H-LoICt~4lrEqorzIFJkHaLtNc3F2GwgvZcsufy93hyN3X25XGwwMjJzhazGvwEAFicD3R3mYrq4OZ8ooHLPiAMG9gQxyOfu-mo7FxdcXHluTzqqOiGsInkcKHdSuJDHMMq-PbWi-4mg4VxL3XRQCwbYRUhnnjb7an2BXk34qJEEtzX23JoCoTpfhpzbZ2~BHDudtjiS0zYDuOfcmr8wKGJAIOnIB-K1LFYuA5q3D1xiC2wMKJmf8nFfBGjzDS0El6j6SOS17-wFg__) 
If you prefer, you can dowload these at thte command ling
3. Unzip the file demo-serverless-microservice-local.zip.
4. Open the demo-serverless-microservice-local folder in VS Code.
![](/static/pre-1.png)
5. Open a new terminal in VSCode and create a virtual environment with the following commands:
    
        python3 -m venv .venv
        source .venv/bin/activate
6. Finally, install the application's requirements:
    
        pip install -r requirements.txt
        export AWS_DEFAULT_REGION=us-west-2

#### Install the AWS Toolkit for Visual Studio Code

The AWS Toolkit for [Visual Studio Code](https://docs.aws.amazon.com/toolkit-for-vscode/latest/userguide/welcome.html) is an open-source extension that makes it easier for developers to develop, debug locally, and deploy serverless applications that use AWS. The toolkit makes your AWS services and resources available directly from your VS Code IDE.

1. Navigate to **Extensions** icon on the left-hand pane of your VS Code IDE.
2. In the search bar, enter AWS Toolkit and select **Install**.
![](/static/pre-2.png)