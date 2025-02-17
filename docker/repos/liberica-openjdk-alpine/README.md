# What is Liberica?

Liberica is a 100% open-source Java implementation.
It is built from OpenJDK which BellSoft contributes to, is thoroughly
tested and passed the JCK provided under the license from OpenJDK.
Liberica supports the following architectures: x86_64, ARMv8, ARMv7
Liberica binaries for the Raspberry Pi also contain JavaFX with hardware-accelerated EGL support and Device IO API as additional modules.

Liberica is built, tested, supported and made available by BellSoft.

<https://bell-sw.com/java.html>

This repository contains Alpine Docker images of Liberica OpenJDK and available for following architectures:

* x86_64 (aka amd64)
* aarch64 (aka ARM64)
* armhf (for devices like Raspberry Pi 2/3)

# Tags

The Liberica repository bellsoft/liberica-openjdk-alpine provides multiple tagged images. The latest Liberica versions are:

* [`latest`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
[`16.0.2-7`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
[`16.0.2`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
[`16.0.1-9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
[`16.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
[`16-36`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
[`16`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/16/Dockerfile),
* [`15.0.2-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
[`15.0.2-8`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
[`15.0.2`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
[`15.0.1-9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
[`15.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
[`15-36`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
[`15`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/15/Dockerfile),
* [`14.0.2-13`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/14/Dockerfile),
[`14.0.1-8`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/14/Dockerfile),
[`14-36`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/14.0.0/Dockerfile)
[`14`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/14/Dockerfile),
* [`13.0.2-9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/13/Dockerfile),
[`13.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/13.0.1/Dockerfile)
[`13`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/13.0.0/Dockerfile)
* [`12.0.2`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/12.0.2/Dockerfile),
[`12.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/12.0.1/Dockerfile),
[`12`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/12.0.0/Dockerfile)
* [`11.0.12-7`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.12`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.11-9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.11`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.10-9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.9.1-1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.9-12`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.9-11`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.8-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.7-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile),
[`11.0.6-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.6/Dockerfile),
[`11.0.5-11`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.5/Dockerfile),
[`11.0.5`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.5/Dockerfile),
[`11.0.4`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.4/Dockerfile),
[`11.0.3`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.3/Dockerfile),
[`11.0.2`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.2/Dockerfile),
[`11.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/11.0.1/Dockerfile),
[`11`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/11/Dockerfile)
* [`10.0.2`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/10.0.2/Dockerfile),
[`10.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/10.0.1/Dockerfile),
[`10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/10.0.0/Dockerfile) - armhf only (Raspberry Pi 2/3)
* [`9.0.4`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/9.0.4/Dockerfile),
[`9.0.1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/9.0.1/Dockerfile) - armhf only (Raspberry Pi 2/3)
* [`8u302-8`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u302`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u292-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u292`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u282-8`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u282`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u275-1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u275`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u272-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u272`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u265-1`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u262-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u252-9`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8u242-7`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u242/Dockerfile),
[`8u232-10`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u232/Dockerfile),
[`8u232`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u232/Dockerfile),
[`8u222`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u222/Dockerfile),
[`8u212`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u212/Dockerfile),
[`8u202`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u202/Dockerfile),
[`8u192`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/old/8u192/Dockerfile),
[`8u`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile),
[`8`](https://github.com/bell-sw/Liberica/blob/master/docker/repos/liberica-openjdk-alpine/8/Dockerfile)   - amd64 and aarch64 only

# Build

Dockerfile accepts the following parameters:

* `LANG` – Specifies a `locale` for this image. By default it's set to en_US.UTF-8, for locale names see <https://www.gnu.org/software/gettext/manual/html_node/Locale-Names.html#Locale-Names>. Note that the specified locale cannot be changed in runtime.
* `OPT_PKGS` – Specifies a list of optional Alpine Linux packages to be installed, the packages should be separated by spaces, i.e. "curl lftp ttf-dejavu".

# Usage

For example, you can run a Liberica OpenJDK 11 container with the following command:

 ```docker run -it --rm bellsoft/liberica-openjdk-alpine:11 java -version```

To run some application you can create Dockerfile, based on bellsoft/liberica-openjdk-alpine image or mount volume with your code/applicaiton, for example:

 ```docker run -it --rm  -v /home/user/project/:/data bellsoft/liberica-openjdk-alpine:11 java -jar /data/MyApp.jar```

# Off-screen rendering

Containerized deployments sometimes do some off-screen rendering, such as when preparing documents, forms, and images. When performing off-screen rendering, the JDK requires OS fonts and `fontconfig` libraries to be present.
In case when you don't have these libraries or fonts you will encounter the exception, similar to one below:

```
Exception in thread "main" java.lang.InternalError: java.lang.reflect.InvocationTargetException
	at java.desktop/sun.font.FontManagerFactory$1.run(FontManagerFactory.java:86)
	at java.base/java.security.AccessController.doPrivileged(AccessController.java:312)
	at java.desktop/sun.font.FontManagerFactory.getInstance(FontManagerFactory.java:74)
	at java.desktop/sun.font.SunFontManager.getInstance(SunFontManager.java:247)
	at java.desktop/sun.font.FontDesignMetrics.getMetrics(FontDesignMetrics.java:261)
	at java.desktop/sun.swing.SwingUtilities2.getFontMetrics(SwingUtilities2.java:1243)
...
	at jdk.compiler/com.sun.tools.javac.launcher.Main.run(Main.java:192)
	at jdk.compiler/com.sun.tools.javac.launcher.Main.main(Main.java:132)
Caused by: java.lang.NullPointerException
	at java.desktop/sun.awt.FontConfiguration.getVersion(FontConfiguration.java:1262)
	at java.desktop/sun.awt.FontConfiguration.readFontConfigFile(FontConfiguration.java:225)
	at java.desktop/sun.awt.FontConfiguration.init(FontConfiguration.java:107)
	at java.desktop/sun.awt.X11FontManager.createFontConfiguration(X11FontManager.java:719)
	at java.desktop/sun.font.SunFontManager$2.run(SunFontManager.java:362)
	at java.base/java.security.AccessController.doPrivileged(AccessController.java:312)
	at java.desktop/sun.font.SunFontManager.<init>(SunFontManager.java:307)
	at java.desktop/sun.awt.FcFontManager.<init>(FcFontManager.java:35)
	at java.desktop/sun.awt.X11FontManager.<init>(X11FontManager.java:56)
	... 28 more
```

On Alpine Linux, these libraries are provided by `fontconfig` and `ttf-dejavu` packages, and can be installed by running the following command:

```apk add fontconfig ttf-dejavu```

The Liberica JDK Dockerfile can be built with these libraries by specifying `OPT_PKGS` build argument:

```shell
docker build -t bellsoft/liberica-openjdk-alpine:11 \
  --build-arg LIBERICA_RELEASE_TAG=11.0.6 \
  --build-arg LIBERICA_VERSION=11.0.6 \
  --build-arg LIBERICA_BUILD=10 \
  --build-arg LIBERICA_VARIANT=jdk \
  --build-arg LIBERICA_ROOT=/usr/lib/jvm/jdk-11.0.6-bellsoft-x86_64 \
  --build-arg OPT_PKGS="fontconfig ttf-dejavu"
```
