workflow: triggered when an event occur. Example of an event is a push to the repo.
job: a workflow contains one more jobs, can be run in sequential order or in parallel
runner: each job run inside its own virtual machine runner or container
step: each job has one or more steps that run a user-defined script, or action, which is a reusable extentions.