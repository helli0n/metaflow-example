# metaflow-example

###install metaflow
`pip install metaflow`

###create config with AWS resources
Create and copy config to ~/.metaflowconfig/
`cp config.json ~/.metaflowconfig/`

###Example for execution metaflow job on AWS 

`python metaflow-example.py --no-pylint run --max-workers 5  --with batch`

###Example for execution metaflow job on Local Machine

`python metaflow-example.py run`
