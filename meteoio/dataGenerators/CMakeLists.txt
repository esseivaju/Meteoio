INCLUDE_DIRECTORIES("${PROJECT_SOURCE_DIR}/")

SET(dataGenerators_sources
	dataGenerators/GeneratorAlgorithms.cc
	dataGenerators/AllSkyLWGenerator.cc
	dataGenerators/AllSkySWGenerator.cc
	dataGenerators/ClearSkyLWGenerator.cc
	dataGenerators/ClearSkySWGenerator.cc
	dataGenerators/ConstGenerator.cc
	dataGenerators/ESOLIPGenerator.cc
	dataGenerators/IswrAlbedoGenerator.cc
	dataGenerators/PrecSplitting.cc
	dataGenerators/HumidityGenerator.cc
	dataGenerators/SinGenerator.cc
	dataGenerators/StdPressGenerator.cc
	dataGenerators/TauCLDGenerator.cc
	dataGenerators/TsGenerator.cc
	dataGenerators/WindComponents.cc
	dataGenerators/RadiationComponents.cc
)
