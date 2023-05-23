## Setting up self hosted runners for Workflows

### Step 1
Go to Settings > Actions > Runners

![image](https://github.com/prathamjagga/actions-demo/assets/30550632/16a19fcf-8093-48a4-8b7d-f27b98a4b091)

### Step 3
Click on "New self hosted runner".

### Step 4
Run the commands shown on the following page in the machine which you want to use as your self hosted runner. 

![image](https://github.com/prathamjagga/actions-demo/assets/30550632/001b196a-48aa-4747-a0c9-c6b9bf699298)
![image](https://github.com/prathamjagga/actions-demo/assets/30550632/abdccf9c-95fb-4f6d-b4b2-2d8132624780)
![image](https://github.com/prathamjagga/actions-demo/assets/30550632/50ce194b-def5-4d75-9c29-34e6fbc6e167)

### Step 5
Finally whenever you want to activate the runner, run './run.cmd' script.

![image](https://github.com/prathamjagga/actions-demo/assets/30550632/f2835462-57b3-4127-ac54-efe155ba730c)

### Step 6
Finally add any workspace job which use your self-hosted runner. To specify the self hosted runner for a job, write runs-on: self-hosted as shown below.

![image](https://github.com/prathamjagga/actions-demo/assets/30550632/3cfadea6-0d77-4276-9280-0172a78a817e)

### Step 7
Now whenever this workflow (Demo Workflow) is triggered, the first_self_hosted_job will run on the self hosted runner machine as shown in the following images:

![image](https://github.com/prathamjagga/actions-demo/assets/30550632/3cf24640-db01-4d28-9ec6-4a5d94605d1b)
![image](https://github.com/prathamjagga/actions-demo/assets/30550632/5180acab-0cdf-4a8f-9cbb-6e066d060045)

If you face any problems, do add an issue.
