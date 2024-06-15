## Github Workflows 

### Step 1 - Signup and Login to GitHub.com
### Step 2 - Create a new Repository
### Step 3 - In the repo create a folder .github/workflows
### Step 4 - In the folder create a YAML file with .yml extension
### Step 5 - Add the content of the workflow in the file
### Step 6 - Commit and push the changes
### Step 7 - Go to Repo main page and click “Actions” tab
### Step 8 - Select the workflow from left sidebar and check the logs and results

```yaml
name: hello-world
on: push
jobs: 
  my-job: 
    runs-on: ubuntu-latest
    steps:
      - name: my-step
        run: echo "hello-world"
