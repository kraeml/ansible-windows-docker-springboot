win_multimachine:
	packer build \
		-var iso_url=14393.0.161119-1705.RS1_REFRESH_SERVER_EVAL_X64FRE_EN-US.ISO \
		-var iso_checksum=70721288bbcdfe3239d8f8c0fae55f1f \
		-var template_url=vagrantfile-windows_2016-multimachine.template \
		-var box_output_prefix=windows_2016_docker_multimachine \
		windows_server_2016_docker.json
