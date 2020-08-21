This is the MULTIPLY Organization. It lists the repositories containing the code used within the MULTIPLY project. For more information on the MULTIPLY project, visit http://www.multiply-h2020.eu/ .
The repositories may be categorized as such:
Platform: This lists the repositories that form the backend of the MULTIPLY platform
    data-access: Enabling access to EO and auxiliary data that is required by the other components
    kaska: An Inference Engine using a Smoothing Approach
	prior-engine: A framework to provide different types of prior information
	KaFKA-InferenceEngine: An Inference Engine using a Kalman Filtering Approach
	post-processing: A framework for post processors that may work on inference results
	multiply-core: A collection of core functionality that is required by other parts of the platform
	inference-engine: Wrapping functionality around the Kafka and Kaska Inference Engines
	vm-support: A collection of functionality to ensure that the MULTIPLY platform runs in a VM environment
	sar-pre-processing: Functionality to perform Pre-Processing on Sentinel 1-SAR Data
	atmospheric_correction: Functionality to perform Pre-Processing on Sentinel-2 Data
User Interface and Visualisation: These are the repositories that comprise the MULTIPLY frontend.
    multiply-ui: The Jupyter Hub-based MULTIPLY User Interface that communicates with the backend.
    MULTIPLYVisualisation: Contains the functionality to visualize inference or post-processing results
Training Material:
	H2020_MULTIPLY_training	
Archived repositories: Repositories whose functionality has been transferred to other repositories and thereby have become obsolete
    multiply-orchestration
    workshop
    pre_processing
