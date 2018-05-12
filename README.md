# mlrepricer

You can use methods to easier access and train models.
If we use the same features we can find a more accurate model.
A repricer model is quite complex.
It's like scissors and papers with price elasticity and estimates about sales.
For the start we can make it as simple as possible.
If this is going very well, we will build a live repricer which is constantly learning.

## Questions to ask
Should we start with continously evaluating the outcome?
If yes we have to build all the basic parts first.

So what type of problem we want to solve?

## What it's not?
Run and install.
Because everyone using different datadumps.
And we want to focus on getting started to train models.

## How to get started?
Boto3 looks for credentials in:

~/.aws/credentials:
```
[default]
aws_access_key_id = YOUR_ACCESS_KEY
aws_secret_access_key = YOUR_SECRET_KEY
```

We define all configs in:
mlrepricer/mlrepricer/configs.yaml

## Objectives:
- get data
- dump all data in historic archive
- use different approaches for modelling
