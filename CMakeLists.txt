art_make( MODULE_LIBRARIES larcorealg_Geometry 
	  larcore_Geometry_Geometry_service
	  larsim_Simulation nug4::ParticleNavigation lardataobj_Simulation
	  larsim_MCCheater_BackTrackerService_service
	  larsim_MCCheater_ParticleInventoryService_service
	  dune_Geometry
	  larsim_Utils
	  lardata_Utilities
	  larevt_Filters
	  lardataobj_RawData
	  lardataobj_RecoBase
	  lardataobj_AnalysisBase
	  lardata_RecoObjects
          lardata_ArtDataHelper
		  canvas_root_io
          lardataalg_DetectorInfo
	  larreco_RecoAlg
	  larpandora_LArPandoraInterface
	  SignalShapingServiceDUNE10kt_service
	  SignalShapingServiceDUNE35t_service
          nusimdata::SimulationBase
		  dune_AnaUtils
          ART_FRAMEWORK_CORE
	  ART_FRAMEWORK_PRINCIPAL
	  ART_FRAMEWORK_SERVICES_REGISTRY
	  ART_ROOT_IO_TFILE_SUPPORT
	  ROOT::Core
	  ART_ROOT_IO_TFILESERVICE_SERVICE
	  art::Persistency_Common canvas
	  art::Persistency_Provenance canvas
	  art::Utilities canvas
	  messagefacility::MF_MessageLogger
	  z
	  
	  fhiclcpp::fhiclcpp
	  cetlib::cetlib cetlib_except
          ROOT_GEOM
          ROOT_XMLIO
          ROOT_GDML
	  ROOT_BASIC_LIB_LIST
        )

install_headers()
install_fhicl()
install_source()
install_scripts()
