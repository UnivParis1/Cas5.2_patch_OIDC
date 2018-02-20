This patch allow you too fix the [issue #3128](https://github.com/apereo/cas/pull/3138)

## HOW TO DO

Copy paste the content of src into your cas/src and rebuild your CAS project


## BUILD

You need to add some packages

In cas/build.gradle

```groovy

    dependencies {
        ...
            compileOnly group: 'javax.servlet', name: 'javax.servlet-api', version: '3.0.1'
        ...
    }
```