package(default_visibility = ["//visibility:public"])

load("@org_pubref_rules_protobuf//bzl:cpp/rules.bzl", "cc_proto_library")

cc_proto_library(
	name = "accelerometer_proto",
	protos = ["accelerometer.proto"],
	verbose = 0,

)

cc_proto_library(
	name = "gyroscope_proto",
	protos = ["gyroscope.proto"],
	verbose = 0,
)

cc_proto_library(
	name = "gps_proto",
	protos = ["gps.proto"],
	verbose = 0,
)

cc_proto_library(
	name = "ahrs_proto",
	protos = ["ahrs.proto"],
	with_grpc = True,
	imports = [
    	"external/com_github_google_protobuf/src/",
  	],
)
	
cc_proto_library(
	name = "magnetometer_proto",
	protos = ["magnetometer.proto"],
	verbose = 0,
)
