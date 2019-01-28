## Expression Evaluator:

[
	{
		"fieldToSet": "/uuid",
		"expression": "${uuid:uuid()}"
	},
	{
		"fieldToSet": "/pipeline_id",
		"expression": "${pipeline:id()}"
	},
	{
		"fieldToSet": "/pipeline_start_ts",
		"expression": "${pipeline:startTime()}"
	},
	{
		"fieldToSet": "/current_ts",
		"expression": "${time:now()}"
	}
]









