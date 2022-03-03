# designerBottomNav v1.0.0
Add your android app a beautiful bottom navigagiton bar

>Step 1. Add the JitPack repository to your build file

```build.gradle(project)
	allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
}
```
>Step 2. Add the dependency
>
``` build.gradle(app)
	dependencies {
	        implementation 'com.github.Apsanishant:designerBottomNav:designBottomNav'
	}
