Add the following to your **root** `build.gradle` file:
```
dependencyResolutionManagement {
	repositoriesMode.set(RepositoriesMode.FAIL_ON_PROJECT_REPOS)
	repositories {
		mavenCentral()
		maven { url 'https://jitpack.io' }
	}
}
```

Next, add the dependency below to your **module**'s `build.gradle` file:
```
dependencies {
	implementation 'com.github.aticiadem:MyLibrarySample:1.2'
}
```
