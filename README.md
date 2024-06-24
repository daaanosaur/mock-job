# Mock job

Docker app to mock a finite job, creates a log every second and returns an exit code.

Environment variables:

`SECONDS_TO_RUN`: number greater than 0, default 10
`EXIT_CODE`: number between 0 and 255, default 0
`SECRET_FILE`: path to a secret file, the contents of which will be logged if it exists