# AWSBotoTagVsServiceAnalysis
An AWS boto3 python jupyter notebook extracting tag used by service (arn) for an account and visualising in a seaborn heatmap without output to PDF.

You will need a programmatic user in the target account with atleast ResourceGroupsandTagEditorReadOnlyAccess policy attached

<b>Target Outcome</b>

If you have been at AWS for a while in a larger environment you may need to check how tags have actually been used in an account.  This code gives you a heatmap of tag keys by service with the intensity driven by the variety of key values for the tags (high variety generally indicates effective use).  You can see which services are being tagged with which tags.

<b>Use at Your Own Risk</b>
The author does not warrant the code will perform as described in your environment.  It is up to you to test and validate appropriately before use. Use will incurr AWS usage costs and is entirely at your own risk.
