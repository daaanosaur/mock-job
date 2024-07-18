# Mock job

Docker app to mock a finite job, creates a log for every second it runs and returns an exit code. Can also read a given secret file.

Environment variables:
| Variable | Effect | Values|
|-|-|-|
| `SECONDS_TO_RUN` | The number of seconds for the job run to take | A number greater than `0`, default `10` |
| `EXIT_CODE` | The exit code to return, 0 is success, 1-255 is failure | A number between `0` and `255`, default `0` |
| `SECRET_FILE` | Logs the contents of a given secret file if it exists | Absolute path to a secret file, default `false` |
