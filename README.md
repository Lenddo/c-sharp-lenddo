# Introduction
This is the LENDDO SDK for for windows platforms. Use this to utilize available LENDDO services easily. This is developed using the .NET Standard 1.3 version for maximum compatibility with the minimum required functions in place.

# Release Notes:
### 2.6.0
* Added ApplicationsClient.GetApplications functionality
* Added ApplicationsClient.GetApplicationData functionality
* Added ApplicationsClient.GetApplicationDocuments functionality
* Updated to use .NET Standard 2.0
* Enhancements in making code more efficient. Most of this overhauls will appear in the next revision 3.0

# Release Notes:
### 2.5.0
* Added ApplicationFeatures functionality
* Added ApplicationMultipleScores functionality

### 2.4.0
* Added function for sending for PriorityData (works for partnerscripts that allows it)
* fixed incorrect versioning numbers

### 2.3.0
* Added feature for generating Configured Sessions (Short URLs)

### 2.2.0
* Fix bug for incorrect nullable types

### 2.1.0
* updated the supported version to 1.3
* several minor updates for code improvement
* removed irrelevant files in the release

### 2.0.0 
* Updated project type to use a Standard Class Library
* Use Namespace Lenddo.SDK instead of Lenddo.API

### 1.0.0
* Initial release using Portable Class Library type
	
This client helps expose Lenddo services in an easy-to-implement manner for C#. Currently this SDK exposes two primary features of the Lenddo platform:

# Use Cases

## Data Retrieval
Get _verification_, _decision_, and _score_ from Lenddo.

## White Label Integration
Use this if you wish to use Lenddo services but want to keep control of all of the branding and visuals presented to the user.

## Onboarding
These functions are made available to simplify Lenddo onboarding api calls

# Full Documentation
The Documentation exists in the Wiki which can be found here: https://github.com/Lenddo/c-sharp-lenddo/wiki
