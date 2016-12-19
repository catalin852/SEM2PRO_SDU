Repository Contents:
README.md
-code
	-frontend
	-gps_code
	-sensornode
	-verification
	-netsetup.sh
-data
	-gps_test_data.txt
	-gps_test_data_with_startup
	-node_output_data
	-wifi_test_data
-Eagle
	-CAN-bus
-Testing
	-Bus
-Vivado
	-can_network_v3

Building the programs in the code directory:
	Enter the desired folder.
	mkdir build
	cd build
	cmake ..
	make
	