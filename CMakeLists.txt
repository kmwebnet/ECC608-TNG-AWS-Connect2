cmake_minimum_required(VERSION 3.16.0)

list(APPEND EXTRA_COMPONENT_DIRS "${COMPONENT_DIR}/esp-aws-iot/libraries/backoffAlgorithm"
						 "${COMPONENT_DIR}/esp-aws-iot/libraries/coreMQTT"
						 "${COMPONENT_DIR}/esp-aws-iot/libraries/common/posix_compat"
	)

include($ENV{IDF_PATH}/tools/cmake/project.cmake)
project(tngtest-awsiot)
