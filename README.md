RootShell provides rooted developers with an easy to use Root Shell for their Android Applications.

You can find the latest release here: https://github.com/Stericson/RootShell/releases

You can find more information at our wiki: https://github.com/Stericson/RootShell/wiki

* Local usage

If you want to use you own local fork:
You need run ```    gradle install ```and check the local Maven repo folder ```.m2/repository/CameraT/library```

Add it to your root build.gradle with:
```gradle
repositories {
        mavenLocal()
}
```
and:

```gradle
dependencies {
     compile 'RootShell:library:unspecified'
}
```
