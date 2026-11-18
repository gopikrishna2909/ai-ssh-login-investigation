# AI-Assisted SSH Login Investigation

## Investigation question
When an SSH server records repeated failed logins, what evidence would
justify escalating the activity to another analyst?

## Project status
In progress. My first milestone is a manual investigation of one source IP.

## Approach
1. Build a timeline from a public OpenSSH log sample.
2. Write a Python script and compare its output with my manual findings.
3. Ask an AI model to draft an analyst handover from the same evidence.
4. Check the handover for incorrect counts, unsupported claims and missing context.

## Data source
[Loghub OpenSSH dataset](https://github.com/logpai/loghub/tree/master/OpenSSH)
