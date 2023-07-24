# pic-sure-gic-institution-release-control

To update your instance of GIC PIC-SURE, follow the steps below:
1. In Jenkins update the release control repo to the branch that has the updates. It could be main or a specific branch. 

2. In Jenkins, run the "Check for updates" jobs. 

3. Run the "Start PIC-SURE" job. (This job removes all of the Docker containers and then replaces them, essentially performing both the STOP and START PIC-SURE job.) 

