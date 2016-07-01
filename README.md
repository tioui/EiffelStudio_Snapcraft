To Build the package
====================

	- Go in the repository (containing this README-md file).
		# cd the/repository/directory
	- Create the file 'eiffel_platform' containing the platform to compile Eiffel:
		# echo linux-x86-64 > Makefiles/eiffel_platform
	- Be sure that you have the last updates of snapcraft:
		# snapcraft update
	- Run Snapcraft:
		# snapcraft
	- Install de Snap package (only devmode is tested):
		# sudo snap install eiffelstudio_16.05_amd64.snap --devmode
	- Execute the applications:
		# eiffelstudio.estudio
		# eiffelstudio.ec
		# eiffelstudio.ecb
		# eiffelstudio.esbuilder
		# eiffelstudio.finish-freezing
		# eiffelstudio.quick-finalize
		# eiffelstudio.ace2ecf
		# eiffelstudio.compile-all
		# eiffelstudio.eiffel-echo
		# eiffelstudio.eimgemb
		# eiffelstudio.iron
		# eiffelstudio.syntax-updater
	- Note: The compilation does not work for now because the GCC compiler in the snap system does not have the good Include Path.
