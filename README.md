# Knoxville Sunlight Data

Automated, weekly, forever-updating graph of public money + power flows in Knoxville & Knox County.

**No human gatekeeper. No moderation. No login.**

Every Sunday at 03:00 UTC the pipeline:
- pulls the four public sources
- builds one clean edge list
- commits it here
- pins it to IPFS

First real data drop: **2025-12-22**  
After that → every Sunday forever.

You can:
- download the latest CSV
- fork this repo
- query it yourself
- post what you see

Code & automation lives in the companion repo:  
https://github.com/Chad-Mitchell/sunlight

This repo contains **only data**.  
Nothing else.

## Why some edges look large
Many of the biggest money flows in this dataset are legally enabled by Tennessee’s Tax Increment Financing (TIF) statutes and Industrial Development Board authorities. The graph simply shows what the law already allows.
