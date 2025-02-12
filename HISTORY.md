# Release history

### 1.0.0
* Upgrade CDK support from v1 to v2.
* Upgrade GitHub pipelines checkout version from v2 to v3.
* Upgrade biomapas/cicd-full image version to 5.0.0.

### 0.6.0
* Too many bugs. Revert.

### 0.5.5
* Warn if not cdk tool was found.

### 0.5.4
* Make sure to exit after successful cdk execution.

### 0.5.3
* Use "." instead of "source".

### 0.5.2
* Execute cdk command in the same shell to preserve environment.

### 0.5.1
* Allow running cdk command even though it might be now defined globally.

### 0.5.0
* Pass config object to custom actions.

### 0.4.3
* Fix version retrieval.

### 0.4.2
* For the default SSM parameter name use "name" instead of "global prefix".

### 0.4.1
* Make sure default SSM parameter is unique.

### 0.4.0
* Add default SSM parameter for package version.

### 0.3.3.
* Fix logging issues.
* Run prehooks on session-start and session-finish.
* Add more logging.

### 0.3.2
* Fix warnings. 

### 0.3.1
* Bug fixes.

### 0.3.0
* Add ability to specify custom deployment command in AWS CDK flow (destroy action).

### 0.2.0
* Add ability to specify custom deployment command in AWS CDK flow (deploy action).

### 0.1.0
* Allow to override the TestingStack's name.

### 0.0.24
* Update boto version requirement.

### 0.0.23
* Prettify example CDK project.

### 0.0.22
* Add prefixes for CF outputs too.
* Prettify CDK testing.

### 0.0.21
* Add ability to specify session token.

### 0.0.20
* Remove root path from cdk config in the documentation.

### 0.0.19
* Make sure that Python path is propagated to the process.

### 0.0.18
* Expose global prefix in the Testing stack.
* Update example project.
* Add ability to specify root project to fix import errors.
* Updated tests.
* Update documentation.

### 0.0.17
* Improve documentation with better cdk project examples.
* Add an example cdk project.
* Remove test coverage.

### 0.0.13
* Add testing stack for more convenient CF outputs management.
* Update documentation.
* Add docstrings.
* Updates tests and conftest configuration files.
* Version bump.

### 0.0.12
* Add a flag to specify whether the infrastructure should be destroyed
before creating a new one.

### 0.0.11
* Add documentation about global prefix in readme.

### 0.0.10
* Create a global prefix for unique resources.

### 0.0.9
* Create github pipelines.
* Update code.

### 0.0.8
* Make sure CDK deploy works both on linux based systems and windows based systems.

### 0.0.7
* Bug fix related to environment.

### 0.0.6
* Update pytest dependency version.

### 0.0.5
* Rethink how this framework should be used.

### 0.0.4
* Fix imports.
* Update examples.

### 0.0.3
* Rename project.
* Update gitignore and ignore idea files.
* Update MANIFEST.
* Move examples to a documentation folder.

### 0.0.2
* Add hyperlinks for examples.

### 0.0.1
* Initial build.