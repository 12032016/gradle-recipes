# Recipes for AGP version `8.1`
This branch contains recipes compatible with AGP 8.1. If you want to find recipes
for other AGP versions, switch to the corresponding `agp-*` branch.

This branch is read only. Contributions are only accepted on the `studio-main` branch. See `CONTRIBUTION.md`
there.
# Recipes Index
Index is organized in categories, offering different ways to reach the recipe you want.
## Themes
* Android Assets - [legacyTaskBridging](legacyTaskBridging), [addGeneratedSourceFolder](addGeneratedSourceFolder)
* Android Manifest - [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Artifact API - [createSingleArtifact](createSingleArtifact), [getSingleArtifact](getSingleArtifact), [transformDirectory](transformDirectory), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [getScopedArtifacts](getScopedArtifacts), [appendToScopedArtifacts](appendToScopedArtifacts), [transformAllClasses](transformAllClasses), [getMultipleArtifact](getMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation)
* DSL - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize), [extendingAgp](extendingAgp)
* Dependency Resolution - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Sources - [legacyTaskBridging](legacyTaskBridging), [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder)
## Plugin Features
* TestFixtures - [testFixtures](testFixtures)
## APIs
* AndroidComponentsExtension.beforeVariants() - [selectVariants](selectVariants)
* AndroidComponentsExtension.onVariants() - [allProjectsApkAction](allProjectsApkAction), [createSingleArtifact](createSingleArtifact), [getSingleArtifact](getSingleArtifact), [transformDirectory](transformDirectory), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [legacyTaskBridging](legacyTaskBridging), [getScopedArtifacts](getScopedArtifacts), [addCustomSourceType](addCustomSourceType), [extendingAgp](extendingAgp), [asmTransformClasses](asmTransformClasses), [addCustomBuildConfigFields](addCustomBuildConfigFields), [addGeneratedSourceFolder](addGeneratedSourceFolder), [appendToScopedArtifacts](appendToScopedArtifacts), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [transformAllClasses](transformAllClasses), [onVariants](onVariants), [variantOutput](variantOutput), [getMultipleArtifact](getMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation)
* AndroidComponentsExtension.registerExtension() - [extendingAgp](extendingAgp)
* AndroidComponentsExtension.selector() - [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants), [variantOutput](variantOutput)
* ApplicationVariant.applicationId - [onVariants](onVariants)
* ApplicationVariant.outputs - [variantOutput](variantOutput)
* ArtifactTransformationRequest - [workerEnabledTransformation](workerEnabledTransformation)
* Artifacts.add() - [addMultipleArtifact](addMultipleArtifact)
* Artifacts.forScope() - [getScopedArtifacts](getScopedArtifacts), [appendToScopedArtifacts](appendToScopedArtifacts), [transformAllClasses](transformAllClasses)
* Artifacts.get() - [allProjectsApkAction](allProjectsApkAction), [getSingleArtifact](getSingleArtifact), [transformDirectory](transformDirectory), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [legacyTaskBridging](legacyTaskBridging), [addGeneratedSourceFolder](addGeneratedSourceFolder), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [variantOutput](variantOutput)
* Artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* Artifacts.use() - [createSingleArtifact](createSingleArtifact), [transformDirectory](transformDirectory), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation)
* BuildConfigField() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* BuiltArtifact - [workerEnabledTransformation](workerEnabledTransformation)
* CanMinifyAndroidResourcesBuilder.shrinkResources - [selectVariants](selectVariants)
* CanMinifyCodeBuilder.isMinifyEnabled - [selectVariants](selectVariants)
* Component.artifacts - [createSingleArtifact](createSingleArtifact), [transformDirectory](transformDirectory), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [legacyTaskBridging](legacyTaskBridging), [getScopedArtifacts](getScopedArtifacts), [addGeneratedSourceFolder](addGeneratedSourceFolder), [appendToScopedArtifacts](appendToScopedArtifacts), [variantOutput](variantOutput), [getMultipleArtifact](getMultipleArtifact)
* Component.compileConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.runtimeConfiguration - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Component.sources - [legacyTaskBridging](legacyTaskBridging), [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder)
* Configuration.resolutionStrategy - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* DslExtension.Builder.build() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendBuildTypeWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProductFlavorWith() - [extendingAgp](extendingAgp)
* DslExtension.Builder.extendProjectWith() - [extendingAgp](extendingAgp)
* DslLifecycle.finalizeDsl() - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* GeneratesApk.applicationId - [onVariants](onVariants)
* Gradle.beforeProject() - [allProjectsApkAction](allProjectsApkAction)
* HasUnitTestBuilder.enableUnitTest - [selectVariants](selectVariants)
* InAndOutDirectoryOperationRequest.toTransform() - [transformDirectory](transformDirectory)
* InAndOutDirectoryOperationRequest.toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* InAndOutFileOperationRequest.toTransform() - [transformManifest](transformManifest)
* Instrumentation.transformClassesWith() - [asmTransformClasses](asmTransformClasses)
* MapProperty.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields), [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* MultipleArtifact.MULTIDEX_KEEP_PROGUARD - [getMultipleArtifact](getMultipleArtifact)
* MultipleArtifact.NATIVE_DEBUG_METADATA - [addMultipleArtifact](addMultipleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact)
* OutOperationRequest.toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* OutOperationRequest.toCreate() - [createSingleArtifact](createSingleArtifact)
* Plugin<Settings> - [allProjectsApkAction](allProjectsApkAction)
* ResolutionStrategy.dependencySubstitution() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* ScopedArtifact.CLASSES - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [transformAllClasses](transformAllClasses)
* ScopedArtifacts.Scope.ALL - [getScopedArtifacts](getScopedArtifacts), [appendToScopedArtifacts](appendToScopedArtifacts)
* ScopedArtifacts.Scope.PROJECT - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [transformAllClasses](transformAllClasses)
* ScopedArtifacts.use() - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses), [appendToScopedArtifacts](appendToScopedArtifacts), [transformAllClasses](transformAllClasses)
* ScopedArtifactsOperation.toAppend() - [appendToScopedArtifacts](appendToScopedArtifacts)
* ScopedArtifactsOperation.toGet() - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses), [appendToScopedArtifacts](appendToScopedArtifacts)
* ScopedArtifactsOperation.toTransform() - [transformAllClasses](transformAllClasses)
* SingleArtifact.APK - [allProjectsApkAction](allProjectsApkAction), [workerEnabledTransformation](workerEnabledTransformation)
* SingleArtifact.ASSETS - [transformDirectory](transformDirectory), [legacyTaskBridging](legacyTaskBridging), [addGeneratedSourceFolder](addGeneratedSourceFolder)
* SingleArtifact.BUNDLE - [getSingleArtifact](getSingleArtifact), [addMultipleArtifact](addMultipleArtifact), [appendToMultipleArtifact](appendToMultipleArtifact)
* SingleArtifact.MERGED_MANIFEST - [createSingleArtifact](createSingleArtifact), [transformManifest](transformManifest), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [variantOutput](variantOutput)
* SourceDirectories.addGeneratedSourceDirectory() - [legacyTaskBridging](legacyTaskBridging), [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder)
* SourceDirectories.addStaticSourceDirectory() - [addCustomSourceType](addCustomSourceType)
* TaskBasedOperation.wiredWith() - [createSingleArtifact](createSingleArtifact)
* TaskBasedOperation.wiredWithDirectories() - [transformDirectory](transformDirectory), [workerEnabledTransformation](workerEnabledTransformation)
* TaskBasedOperation.wiredWithFiles() - [transformManifest](transformManifest)
* TaskOutputs.upToDateWhen() - [transformManifest](transformManifest)
* TaskProvider.flatMap() - [createSingleArtifact](createSingleArtifact)
* TaskProvider.map() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.buildConfigFields - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* Variant.components - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* Variant.manifestPlaceholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* Variant.nestedComponents - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* VariantBuilder.minSdk - [selectVariants](selectVariants)
* VariantExtensionConfig - [extendingAgp](extendingAgp)
* VariantOutputConfiguration.OutputType.SINGLE - [variantOutput](variantOutput)
* VariantOutputConfiguration.outputType - [variantOutput](variantOutput)
* VariantSelector.all() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* VariantSelector.withBuildType() - [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants), [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* VariantSelector.withFlavor() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* VariantSelector.withName() - [selectVariants](selectVariants)
* task.getOutputs() - [transformManifest](transformManifest)
## Call chains
* DslExtension.Builder().extendProjectWith().extendBuildTypeWith().extendProductFlavorWith().build() - [extendingAgp](extendingAgp)
* androidComponents.beforeVariants {} - [selectVariants](selectVariants)
* androidComponents.finalizeDsl {} - [addBuildTypeUsingDslFinalize](addBuildTypeUsingDslFinalize)
* androidComponents.onVariants {} - [allProjectsApkAction](allProjectsApkAction), [createSingleArtifact](createSingleArtifact), [getSingleArtifact](getSingleArtifact), [transformDirectory](transformDirectory), [variantDependencySubstitutionTest](variantDependencySubstitutionTest), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [legacyTaskBridging](legacyTaskBridging), [getScopedArtifacts](getScopedArtifacts), [addCustomSourceType](addCustomSourceType), [extendingAgp](extendingAgp), [asmTransformClasses](asmTransformClasses), [addCustomBuildConfigFields](addCustomBuildConfigFields), [addGeneratedSourceFolder](addGeneratedSourceFolder), [appendToScopedArtifacts](appendToScopedArtifacts), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [transformAllClasses](transformAllClasses), [onVariants](onVariants), [variantOutput](variantOutput), [getMultipleArtifact](getMultipleArtifact), [workerEnabledTransformation](workerEnabledTransformation)
* androidComponents.registerExtension() - [extendingAgp](extendingAgp)
* androidComponents.selector().all() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* androidComponents.selector().withBuildType() - [allProjectsApkAction](allProjectsApkAction), [selectVariants](selectVariants), [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* androidComponents.selector().withFlavor() - [selectVariants](selectVariants), [variantOutput](variantOutput)
* androidComponents.selector().withName() - [selectVariants](selectVariants)
* configuration.resolutionStrategy.dependencySubstitution {} - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* settings.gradle.beforeProject {} - [allProjectsApkAction](allProjectsApkAction)
* substitute().using() - [variantDependencySubstitutionTest](variantDependencySubstitutionTest)
* task.outputs.upToDateWhen {} - [transformManifest](transformManifest)
* transformationRequest.submit() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.applicationId - [onVariants](onVariants)
* variant.artifacts.add() - [addMultipleArtifact](addMultipleArtifact)
* variant.artifacts.forScope().use().toAppend() - [appendToScopedArtifacts](appendToScopedArtifacts)
* variant.artifacts.forScope().use().toGet() - [getScopedArtifacts](getScopedArtifacts), [asmTransformClasses](asmTransformClasses)
* variant.artifacts.forScope().use().toTransform() - [transformAllClasses](transformAllClasses)
* variant.artifacts.get() - [allProjectsApkAction](allProjectsApkAction), [getSingleArtifact](getSingleArtifact), [transformDirectory](transformDirectory), [addMultipleArtifact](addMultipleArtifact), [transformManifest](transformManifest), [appendToMultipleArtifact](appendToMultipleArtifact), [legacyTaskBridging](legacyTaskBridging), [asmTransformClasses](asmTransformClasses), [addGeneratedSourceFolder](addGeneratedSourceFolder), [perVariantManifestPlaceholder](perVariantManifestPlaceholder), [variantOutput](variantOutput)
* variant.artifacts.getAll() - [getMultipleArtifact](getMultipleArtifact)
* variant.artifacts.use().wiredWith().toAppendTo() - [appendToMultipleArtifact](appendToMultipleArtifact)
* variant.artifacts.use().wiredWith().toCreate() - [createSingleArtifact](createSingleArtifact)
* variant.artifacts.use().wiredWithDirectories().toTransform() - [transformDirectory](transformDirectory)
* variant.artifacts.use().wiredWithDirectories().toTransformMany() - [workerEnabledTransformation](workerEnabledTransformation)
* variant.artifacts.use().wiredWithFiles().toTransform() - [transformManifest](transformManifest)
* variant.buildConfigFields.put() - [addCustomBuildConfigFields](addCustomBuildConfigFields)
* variant.instrumentation.transformClassesWith() - [asmTransformClasses](asmTransformClasses)
* variant.manifestPlaceholders.put() - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* variant.sources.*.addGeneratedSourceDirectory() - [legacyTaskBridging](legacyTaskBridging), [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder)
* variant.sources.*.addStaticSourceDirectory() - [addCustomSourceType](addCustomSourceType)
* variant.sources.*.all - [addCustomSourceType](addCustomSourceType), [addGeneratedSourceFolder](addGeneratedSourceFolder)
## Others
* All projects - [allProjectsApkAction](allProjectsApkAction)
* Extending AGP DSL - [extendingAgp](extendingAgp)
* Legacy API bridging - [legacyTaskBridging](legacyTaskBridging)
* Placeholders - [perVariantManifestPlaceholder](perVariantManifestPlaceholder)
* SourceDirectories.Flat - [addCustomSourceType](addCustomSourceType)
* SourceDirectories.Layered - [addGeneratedSourceFolder](addGeneratedSourceFolder)
* SourceDirectories.add - [addCustomSourceType](addCustomSourceType)
* registerSourceType - [addCustomSourceType](addCustomSourceType)
# License
```
Copyright 2022 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
